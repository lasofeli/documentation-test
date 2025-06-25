# 3D-Printer yappery
## disclaimer:
- i am not an expert nor have i actually been trained for fablab intern stuff yet (idk if its even gonna happen anymore), if maam rc, rc, or marvin is there, they can probably help you better than i can
## on the off chance you've never opened up prusaslicer before and need to set it up:

just run through setup, though if sir rc is there it's probably better to ask him since i don't remember everything i did during set up 

since you're just using my filament, if you're asked to select filament profiles then


when you get to picking printer models, find this + the 0.6 nozzle version
i *think* it's this one?
also i don't know if you need *this* either but just in case

# lithophane websites
- [link for converting images to lithophanes stl files](https://lithophanemaker.com)
- [other lithophane website thing; idk you pick](https://tool.itslitho.com/CreateModel)

get an stl file; for next section
# slicer & sd card stuff
## slicing model for printing
> [!NOTE]
>images using random models for reference
 
- open prusaslicer
- drag stl file to slicer
- typical settings i use:
	- if you use the 3rd printer from the right, you need to set the printer to the 0.6 nozzle version
	  
	set size here, use the plate on the printbed to reference; changing the % here should update the preview's size after hitting `enter`
	size on plate

> [!POSSIBLE ISSUE]
> if you get this icon next to your file listing, just click it; it resolves itself.

if all is well, just hit `slice now`; gets you estimated time needed to print the file

stick around for at least however long it takes to print the first layer or so, to make sure no stringing or that the print doesn't come off the plate
in this example, 20 minutes 
- if for some reason, print keeps fucking up, you can set the speed to be slower on the printer itself but either way just stick around for the first few layers
if you need to change the size or something, go hit the cube button on the bottom left' right is preview (shows supports as well if you have any)
once everything's ok, hit `export g-code` (lower right)
either move it to the sd card or export it to the sd card directly (adapters should be next to the 3d printers)

sd card: ateneo -> students -> make your own folder with your name or just use mine, either works, eject sd card when done
## you shouldn't need this but slicer troubleshooting
- i don't *think* lithophanes need supports but in the case that it does, or you plan to print something else that **does** need supports:
	- (top left) print settings -> support material -> optional materials for support material and raft -> style -> set to organic

# 3d printer itself

## actually printing

- presuming you already put the sd card in with your gcode, etc
- by the way don't use the black filament, atm i'm not even sure this will work very well with the purple filament; ideally white but idh any unless someone's willing to let u use theirs
- someone unloaded my filament ystd so you have to find my spool and load it again
controls:
- spin knob for going through menu
- press for confirm/select, in case it's just on the display it also pops up the menu


un/loading filament:
- hit knob
- menu -> un/load filament (if it asks, select pla)
- wait for it to heat up, follow instructions on display
- while it heats up cut the end of the filament to an angle there should be lil snip thingys nearby
- check if it's alr extruding the right colour, if not, hit no

also: make sure you have plate on: preferably one with the grid like in a previous example image; some plates have diff textures and i;m not sure but using the wrong plate (like rough vs smooth) might break something

and i'd rather not

heads up, plate is magnetic, align the gap with the lil metal bits on the bed (idr i think they're just screws?)


anyway actually printing:
- hit knob (or assuming you just put the sd card in immediately, should show folders), go to yours, select gcode of the print, ignore the firmware upgrade notice by pressing the knob again
## removing off of build plate
- lift plate off of print bed
- you can bend the plate a bit to loosen the adhesion of print on plate
- if it doesn't seem to be coming off, find plastic scraper (either the top hat looking thing or something that looks like this), ![[{4D620E11-B39F-4A47-AA89-77245817811C}.png]] then go at it until it comes off
- for the love of god don;t use metal scraper
## MORE troubleshooting
- if 3d printing goes wrong (print comes off plate, stringing, etc)
- press knob, -> stop/abort print  ( i don't remember the exact phrasing)

quick examples:
- stringing
- spaghetti hell 

if print goes wrong again you can set speed to be slower on printer itself

if somethign else goes wrong or i forgot to write something down, either ask maam rc, one of the fablab interns, or dm me

Donec sed nunc dolor. In commodo a elit sed lacinia. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer consequat sem eget libero cursus iaculis. Integer fringilla sem in nisi ullamcorper, vitae sollicitudin nisi porta. Nulla eget molestie lectus. Mauris porta porttitor ligula at maximus. Cras ultrices leo eu tempus vehicula. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer quis nulla sodales, venenatis tellus a, maximus felis. Sed vitae arcu a lectus commodo pretium. 
