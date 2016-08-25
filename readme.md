# Star Wars: Fall of the Jedi -  Mr Pitiful's Open Source Fan Edit of Episodes I - III

This is one Star Wars fan's passion project of taking the mess of Episodes I-III 
and editing them into a single, cohesive, and hopefully dececent film.

It is also an attempt to show this can be done legally and through open source.
This repo includes only the Adobe Premeire project files and reference stills.

To watch the movie, legally owned copies of the source films will need to be 
added to the project, and then the film can be rendered.  

How do you do that?  Instructions below!

## How to Render and Watch!?

A quick introduction of the minimal setup you need to watch this film.

### What You'll Need to Get Started:
* **Adobe Premeire**
  * Available for $19.99 - $29.99/mo from [Adobe Creative Cloud](https://creative.adobe.com/plans?single_app=premiere)
* **Legal Digital Copies of Star Wars Episodes I - III**
  * From iTunes Store (recommended)
    * [Star Wars: The Phantom Menace](https://itunes.apple.com/us/movie/star-wars-the-phantom-menace/id975080816)
    * [Star Wars: Attack of the Clones](https://itunes.apple.com/us/movie/star-wars-attack-of-the-clones/id975101586)
    * [Star Wars: Revenge of the Sith](https://itunes.apple.com/us/movie/star-wars-revenge-of-the-sith/id975521762)
  * Have Different Legal Digital Copies of Episodes I-III?
    * Don't worry, they will likely still work.  You just need to get them into a format that you can import into Premeire. 
    * Email me at scott.monaghan@gmail.com and I can help if you have any trouble.
* **Noteburner** (only for iTunes copies of the movies)
    * Removes DRM from iTunes movies to allow them to be imported into Premeire
    * $19.99 from [noteburner.com](https://noteburner.com)
* **The latest commit of this Premeire Project!**
  * [Download it here!](https://github.com/ScottMonaghan/Star_Wars_Fall_of_the_Jedi.mrpitiful_fan_edit/archive/master.zip)!

### I: Remove DRM from the iTunes Source Files 

In order to import your source files into Premeire, you will need to make sure DRM is removed.  If you already have legal DRM-free digital copies of Episodes I-III you can skip this step.  This tutorial only covers removing DRM from movies downloaded from the iTunes store.  If you own legal copies in a different format, (e.g. Blu-Ray), contact me at scott.monaghan@gmail.com and I'll give you a hand.  Also, if you happen to be successful doing this yourself and want to update this tutorial with instructions, feel free to update and send me a pull request.

#### Convert Your Files with Noteburner M4V Converter Plus
![Noteburner Example](http://imgur.com/8Hl1AKg.png)
1. Be sure you've downloaded all 3 movies on your local copy of iTunes
2. Open Noteburner M4V Plus
3. Choose the Episode I-III
...It should look like the screenshot above
4. Press Convert
**NOTE: This will take A WHILE. You might want to leave this running over night**
**When finished, spot check your videos to be sure to check that the audio and video properly converted.**


### II: Unzip the Master.zip!
  ![Expected File Structure After Unzip](http://imgur.com/z3anl6x.png)
* The unzipped file structure should look similar to above.
* Don't worry if the hidden files are missing (.DS_Store, .git, .gitignore)


### III: Copy the Converted Source Files into a "source" Folder Wherever you Unzipped Master.zip
  ![Expected File Structure with Source Files](http://imgur.com/cjBIHrN.png)
* After copying the source the file structure should look like above
* Again, don't worry if the hidden files are missing (.DS_Store, .git, .gitignore)
 

### IV: Import the Source Files
1. Open Star_Wars_Fall_of_the_Jedi.mrpitiful_fan_edit.prproj in Adobe Premeire
2. In the project window, expand the Source > Raw Footage Folder.
3. The 3 clips should have question marks as shown below:
  ![Raw Footage Folder in Premeire](http://imgur.com/GBQvBL8.png)
4. Right-Click (Windows) or Control-Click (Mac) on Star Wars_ Attack of the Clones.mp4 and choose "Replace Footage..."
  ![Replace Footage...](http://imgur.com/nEWbm6O.png)
5. Find select Star Wars_Attack of the Clones.mp4 on disk.
  ![Select mp4 file](http://imgur.com/HFvENMD.png)
6. After selecting the clip in the Premeire Project pane should have changed from a question mark to an audio/video icon:
  ![Audio/Video Icon](http://imgur.com/QooSGn2.png)
7. Repeat steps 4-6 for Phantom Menace and Revenge of the Sith


### V: Align the Source Sequences

If you've used the iTunes versions of these movies, chances are, everything is now aligned properly, but it's a good idea to check, and if you are using another footage source, this step is crucial.

To get this whole thing to work, I have a single reference frame in video track 3 of Alignment Sequences of the exact point when the Star Wars logo first appears.  As long as you align the clip in video track 2 to match the reference frame perfectly, the edits for the whole movie should be correct.

####Here's what we need to do:
1. Expand the "Episode I" folder under the "Source" folder in the Project window.
2. Double Click on "Episode I Alignment Sequence"
...![Alignment Sequence in Project Window](http://imgur.com/lw4Wuo3.png)
3. In the Sequence pane target the V3 track
  * Click on the V3 and make sure it is dark blue as shown below:
...![Target V3] (http://imgur.com/DaiH7Ss.png)
4. Be sure the Sequence pane is selected and press the down arrow key until the blue scrubber is lined up exactly at the beginning of the clip in V3 as so:







