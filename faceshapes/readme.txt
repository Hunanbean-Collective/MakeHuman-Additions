Replace the faceshapes.mxa file in the MHX2 plugins subfolders.
During Import do 'Override Exported Data', check mark 'Face Shapes' and 'Merge Body Parts'
Any other options as you prefer.

Use Papagayo-NG with my additions found in this git https://github.com/Hunanbean-Collective/Papagayo-NG-Additions
prepare and export you .dat file

Import the Papagayo .dat file with https://github.com/iCEE-HAM/io_import_lipSync-blender2.8 plugin.
Suggested settings of 
skscale 1.00
offset 0  :or whatever you need to set it at to sync to your .dat
Ease in 5
hold gap 1
Ease Out 5

make sure you are at frame 1 before, and after this procedure.
in blender, drag your matching audio file into 'video sequencer'
back in the 'timeline' make sure you set, under playback, to sync audio and video.

More detailed instructions to come in the near future.


Here is a full 39 Viseme set for use with MakeHuman in coordination with Papagayo-NG and Blender

These were designed with a combination of Targets by:
montybot   https://github.com/montybot/FACSHuman
Thomas Larsson   https://bitbucket.org/Diffeomorphic/
Hunanbean   https://github.com/Hunanbean-Collective/

All credit for the MHX2 Plugin belongs to Thomas Larsson, without which this would not be possible in its current easy form.
