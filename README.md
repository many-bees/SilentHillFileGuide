# Silent Hill 1
### [Duckstation 3D Screenshot](https://github.com/scurest/duckstation-3D-Screenshot)
Models don't come rigged so it's not an ideal solution but it gets everyothing out perfectly fine.

# Silent Hill 2
### [Silent Hill Texture Explorer](https://www.silenthillmemories.net/sh2/modding_en.htm)
Allows the browsing of various archives to view and extract textures from them. This page also lists a model exporter but it's in .obj format so you're better off just downloading stuff from [Silent Hill Museum](https://silenthillmuseum.org/).

### [Silent Hill Explorer](https://drive.google.com/file/d/1aVf7DRGpgFQgle50gO6HSkozNHjlJVgr/view)
General extraction tool for various files found in Silent Hill 2 & 3. Can be used to get stuff like .mdl files and .adx files from the game but usually other programs are needed to convert those files into a usable form.

### [Psilent pHill 2](https://github.com/pmttavara/ph2/tree/main)
Silent Hill 2 map viewer that allows maps to be exported into .obj format. For some reason when you loaed them into Blender their massive though so scale the mesh down a bunch if you wanna actually see it.

# Silent Hill 3
### [Silent Hill Texture Explorer](https://www.silenthillmemories.net/sh2/modding_en.htm)
Seems to have some problems with SH3 specifically but I'm not sure if that's the program's fault or the game's. Just keep in mind that some textures may need to be edited.

### [Useful guide for .mdl files](https://youtu.be/zdLDgnbHfHU)

### [Silent Hill Explorer](https://drive.google.com/file/d/1aVf7DRGpgFQgle50gO6HSkozNHjlJVgr/view)
Exports usable files from .arc files

### [SH3_chr](https://github.com/alanm20/SH3_chr/tree/main)
Despite being called a character loader it can also load anything else that's in the .mdl format such as items and weapons.

### [Perdedork's Silent Hill Level Viewer](https://www.silenthillmemories.net/sh2/modding_en.htm)
Unfortunately this doesn't allow for maps to be exported but I've managed to sorta save them using [3DVIA Printscreen](https://dassault-systemes-3dvia-printscreen.software.informer.com/download/) and this website called [3dEncoder](https://3dencoder.com/). Unfortunately that method doesn't include textures and I haven't yet figured out a way to extract all map textures but I'm working on it.

### [alamn20's Silent Hill 3 Map Noesis Plugin](https://github.com/alanm20/SH3_map0
Discovered this way after Peredork's level viewer and what do you know, it actually does allow you to export maps. When I look at the map in Noesis most of the materials are assigned to the wrong slots but that's apparently only happened to me and it's easy to fix in Blender anyways. It's compatible with the SH4 mesh plugin but conflicts with Spargas's plugins.

# Silent Hill 4
### [sh4worldmeshimport](https://github.com/HunterStanton/sh4worldmeshimport)
Blender addon to import .bin files that contain world meshes. Works with the PC version only.

### [Silent Hill Texture Explorer](https://www.silenthillmemories.net/sh2/modding_en.htm)
Site lists it as only working for 2 and 3 but it works for 4 as well. Has a tendency to leave out textures though.
### [Silent Hill 4 Noesis Plugin](https://youtu.be/4fNbtRQ7irM)
Only works with .bin files from the xbox version of the game so you'll probably have to download a ROM. Also you have to remove fmt_bin.py from your Noesis plugins folder because it conflicts with this plugin.

### [Spargas Silent-Hill Noesis Plugins](https://github.com/Sparagas/Silent-Hill)
This can extract textures from .bin files and unlike the texture explorer tool it doesn't have a problem of leaving anything out. Also doesn't work if you've got the xbox plugin listed above installed.


I figure everyone here knows how to download Noesis and Blender already and I don't need to list them. Also audio files from these games can be opened and converted with VLC Media Player.
