Replace, or manually merge, the faceshapes.mxa file in the MHX2 plugins subfolders of Blender.
During MHX2 Import select 'Override Exported Data', check mark 'Face Shapes'
Any other options as you prefer.

Edit: My changes have been merged into papagayo-ng. no need to use the papagayo files from this repository, they are already included in Papagayo-NG.
//Use Papagayo-NG with my additions found in this git https://github.com/Hunanbean-Collective/Papagayo-NG-Additions
//prepare and export you .dat file   


Import the Papagayo .dat file you made in to Blenderby using the https://github.com/iCEE-HAM/io_import_lipSync-blender2.8 plugin.
Suggested settings of 
skscale 1.00
offset 0  :or whatever you need to set it at to sync to your .dat
Ease in 4
hold gap 0 or 1
Ease Out 4    But all of this is a matter of preference.
Remember to select your mesh before attempting to change settings or import, as that plugin has 2 ways of doing things depending on whether you have the Mesh or the Armature selected.

To see the audio and lipsync synced
make sure you are at frame 1 before, and after this procedure.
in blender, drag your matching audio file into 'video sequencer'
back in the 'timeline' make sure you set, under playback, to sync audio and video.


Here is a full 39 Viseme set for use with MakeHuman in coordination with Papagayo-NG and Blender

These were designed with a combination of Targets by:
montybot   https://github.com/montybot/FACSHuman
Thomas Larsson   https://bitbucket.org/Diffeomorphic/
Hunanbean   https://github.com/Hunanbean-Collective/

All credit for the MHX2 Plugin belongs to Thomas Larsson, without which this would not be possible in its current easy form.

This works quite well as it is now. The only future changes would be to further perfect the mouth shapes, if needed.
