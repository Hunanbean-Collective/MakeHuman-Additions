1. Get MakeHuman: http://www.makehumancommunity.org/content/makehuman_120.html

2. (Probably already in the version of MakeHuman you downloaded. Skip step 2. as needed) Get the MHX2 Plugin for MakeHuman http://www.makehumancommunity.org/content/plugins.html and install

3. Get the MHX Plugin for Blender side: http://www.makehumancommunity.org/content/plugins.html and install

4. Download faceshapes.mxa from here

5. In your Blenders installed plugins folder for the MHX plugin -- Example: C:\Users\YouUserNameHere\AppData\Roaming\Blender Foundation\Blender\3.3\scripts\addons\import_runtime_mhx2\data\hm8\faceshapes -- Rename the faceshapes.mxa file to something like, faceshapes.maxORG

6. Copy the faceshapes.mxa file you downloaded from here to that same folder that you renamed the original faceshapes file in


During MHX2 Import select 'Override Exported Data', check mark 'Face Shapes'
Any other options as you prefer.

Import the Papagayo .dat file you made in to Blender by using the https://github.com/Hunanbean/Papagayo-NGLipsyncImporterForBlender Pick the version that matches your Blender version
Suggested settings of 
skscale .66 Varies
offset 0  :or whatever you need to set it at to sync to your .dat
Ease in 3
hold gap 0 or 1
Ease Out 3    But all of this is a matter of preference.
Remember to select your mesh before attempting to change settings or import, as that plugin has 2 ways of doing things depending on whether you have the Mesh or the Armature selected.


Description:
Here is a full 39 Viseme set for use with MakeHuman in coordination with Papagayo-NG and Blender

These were designed with a combination of Targets by:
montybot   https://github.com/montybot/FACSHuman
Thomas Larsson   https://bitbucket.org/Diffeomorphic/
Hunanbean   https://github.com/Hunanbean-Collective/

All credit for the MHX2 Plugin belongs to Thomas Larsson, without which this would not be possible in its current easy form.

This works quite well.
