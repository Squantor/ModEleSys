# ModEleSys
This repository contains a modular system for electronics projects. It encompasses a backplane of which a few variants exist. Next to that there are various modules that are plugged into this backplane. These modules are 4 by 5 cm in size and the current backplane can contain 4 of them in a 2 by 2 grid. 
These modules come in different sizes, a 1by1 module occupies just one spot on the backplane, the 2by1 and 1by2 module occupy two spots and are for larger projects. Hypothetically there would also be a 2by2 module also but if you have that, why do you need a backplane?
If you use stackable headers for the modules, in principle you could stack multiple modules on top of eachother.

There are various modules available with the following functions:

* Power supply in a few different variants
* Microcontroller boards in a few different variants

These are "generic" building blocks so they can be used in many different projects. Project specific modules usually are owned by the projects themselves. Below is a non exhaustive list of projects using this system:
* [Ultra pure oscillator](https://github.com/Squantor/Metrology/tree/master/electronics/oscillator_variant_2) and [notch filter](https://github.com/Squantor/Metrology/tree/master/electronics/notch_filter)

I intend to use this system for many projects I have in mind.

## Structure
* [electronics](electronics/README.md) contains all the electronic hardware
* [software](software/README.md) contains all the software used in the project. Mostly contains examples for the microcontroller boards using this system.
* [mechanical](mechanical/README.md) contains all the CAD drawings, mostly 3d printable objects.
* [documentation](documentation/README.md) contains more in depth information and examples using this system.
## Cloning
This repository makes extensive use of submodules, use ```git clone --recurse-submodules https://github.com/Squantor/generic_project_template.git``` to clone everything in one go.

