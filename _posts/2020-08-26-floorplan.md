---
title: 'Making a Floorplan (and uses)'
date: 2020-08-07 00:00:00
featured_image: '/images/posts/floorplan/floorplan-3d.png'
excerpt: There are handful of reasons to have a floorplan of where you live, it's helpful for working out where things can fit and/or go, and assist with general day-to-day.
---

# Data
There are handful of reasons to have a floorplan of where you live, it's helpful for working out where things can fit and/or go, and assist with general day-to-day life planning. If you're renting you can often find a floor plan diagram either from the estate agent listing or Googling your address and adding `"floorplan"` to find an old listing that has it.

That doesnt work in all instances so alternatively there are loads of apps that use Augmented Reality and allow you to "draw" the floorplan as you move around, identifying where corners/walls are. These are cool but force you to walk the entire internal perimeter of your house and the accuracy is only as good as the device/AR app - so maybe do a test before taking the time to do your whole house.

![iPad App](/images/posts/floorplan/floorplan-iphone-app.jpg "This is a Title")

But why put in that much effort when you already have a little worker that maps your home (hopefully) multiple times a week, your robot vacuum.
## Robot Vacuums
### Extraction
I can only speak from the tech/experiences I've had so your mileage may vary but extracting the floor maps from Neato was pretty simple. They have a share button that extracts the generated floorplan as a .png ... I guess if you want to show your friends?!

![Raw Neato Floorplans](/images/posts/floorplan/floorplan-neato-three.png)

For the sake of accuracy with my odd-shaped apartment I extracted three maps from different days where Neato cleaned in every room. If you have a fairly perpendicular living space you could definitely get away with just using one.

### Virtual Tidying (optional)
Nothing really exaggerates how much furniture/clutter you have in your home than comparing a vacuum's floorplan to reality. While you can certainly tidy up your real home to get as pure an output as possible, you will still have things like beds and sofa's that you won't bother to move and your vacuum can't crawl under.

![Three Neato Floorplan(s) overlaid](/images/posts/floorplan/floorplan-neato-combined.png)

With the purpose of this source image to be a decently accurate drawing to then create a floorplan on-top of, a lot of these things are obvious to design around when in a more perpendicular home. As I eluded to before, I live amongst a mix of angles so had to put a bit more effort in to make sense of the raw images. I laid three Neato extracts on top of each other in Photoshop with mild opacity and content-awared out obvious anomalies.

# Translate, Refine & Build
For the final conversion, I used [Floorplanner](https://floorplanner.com/) after seeing them recommended on Home Assistant forums. You could just draw something in Photoshop but a purpose-built tool like this has several advantages and takes a lot of the faff out of the equation. For free, Floorplanner allows you to make a basic floor plan and export a 2D image*, their pay option gives more functionality but is aimed more at house design so not needed here.

![floorplan.com](/images/posts/floorplan/floorplan-floorplanner-com.png)

Once you import your floorplan source image, there's an option to add a reference measurement for "accurate" scaling (easiest with a doorway/hallway) - this will be useful for the next step.

You can then probably just go straight into wall/room creation, tip: make a complete room and then add the doors/windows after. I had to go wall by wall to account for funky angles but, with this being a purpose-built tool nothing was particularly taxing.

Unless you've already taken them into account, you'll probably now see a bunch of weird abscesses where vacuum-unfriendly furniture/appliances lie. For me this also included two entire bathrooms I don't let Neato into in case they're damp - so out with the measuring tape and, as long as you set your scale to be fairly accurate when importing the base image, it should be easy enough to modify.

![3D Floorplan](/images/posts/floorplan/floorplan-3d.png)

Some final touches just to make it more appealing, this app has a host of options which are preconfigured to take a lot of the mental effort out, including pre-built assets if you want to put some furniture in and pre-assigned pastel room colours for differentiation.

*With regard to exporting the finished image, the official 2D export is absolute trash, I got much better results by just screenshotting the window and removing the background in Photoshop (for #darkmode).

![2D Finished](/images/posts/floorplan/floorplan-2d.png)

# My Uses
So why go through all that hassle for what is basically just a picture of a house you already know the layout of, firstly ... why not?, secondly there are handful of applications that can take a map of your home and offer some cool outcomes.

## Home Assistant
I've recently installed Home Assistant and still in the process of exploring what it can do. One of the key benefits is the ability to elevate the controls of a multitude of disparate systems, platforms, and services to a single easy to use combined interface. Taking that a step further, you can combine ultra-high level controls into a single image - the floorplan.

![Home Assistant Dashboard](/images/posts/floorplan/floorplan-homeassistant.png)

With the base floorplan image you can overlay anything from sensor data, to switches for lighting and media which was my key driver. All of my lighting (and media to some extent) is automated but I still have the human desire to manually ensure everything is off before my head hits the pillow. This home overview serves that purpose and, depending on your sensor collection, could be extended to show; open/closed ingress points, temperature/thermostat data per-room, smart device activity, and much more.


## Unifi
I'm a massive proponent of Ubiquiti kit, both networking and security cameras (though minimal need for the latter so far). Both the Unifi Networking and Unifi Video (no need for Protect, yet) allow you to upload a floor plan and overlay your hardware. 

![Unifi Wifi](/images/posts/floorplan/floorplan-unifi.png)

The use case is predominantly for big businesses/institutions where it's actually hard to immediately know where an AP or Switch is physically located but it's still cool to see as a prosumer - with the added benefit of visualised coverage maps. Filed firmly in the nice to have category.
