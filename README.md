Main structure of project:

(MP) Lua Scripts:
A folder containing only Lua scripts that act as individual microcontroller components. In the context of writing the code, I'm the author.


microprocessors:
A folder of microcontroller projects. They combine algorithmic programming with BOOL, Float, Sound, Video, and Composite inputs and outputs and scripting in Lua.

---Naming system---

 BOOL - Working only with logical signals
 MATH - Working only with arithmetic signals
 CONV - Working with logical and arithmetic signals
 CTRL - Working with composite signals, in addition can work with logical, arithmetic and sound signals
 DISP - Working with video signal, in addition can work as CTRL

 
vehicles:
A folder containing full-fledged projects. They combine microcontrollers and sandbox elements to create various functional devices.

---Naming system---

 LND - Any mobile land vehicle
 AIR - Any mobile aircraft
 SEA - Any mobile water or submerged craft 
 SPC - Any mobile spacecraft
 BLD - Any immobile building (Can include mobile components)
 CMP - Immobile component of any project
 HBR - Hybrid like LND + AIR
