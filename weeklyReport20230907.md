# Weekly Report 2: 09/07/2023

## Summary
This week I used the Grasshopper and Rhino to develop a computational design model for a watch charger. In some ways, an extension of the Cell Phone stand project, the watch charger model designs a 3D Model of a charging stand that takes into account the size of a watch charger, its orientation and designs a stand around it.

The goals for this project were to design and 3D print an Apple Watch charger that doubles up as a night stand for the watch. 

Accomplishments: I was able to create a Grasshopper Model and slice my 3D Asset (STL file) in Cura to 3D print them at the Makerspace.

—
## Process
### Step 1: Designing the Watch Charger
 Before setting up Rhino and Grasshopper files, I spent sometime designing the watch charger. Most existing chargers in the market place the watch’s charging puck horizontally liked they’d place a phone, I wanted it to be more like a watch stand which places the watch in a way that it can act as a night stand that also shows time.

![Existing Chargers][existingChargers]

My Sketches:
![My Sketches][drawing]

### Step 2: Designing the Grasshopper System

Once I had a design in mind, I started designing my charger in grasshopper. 

![Grasshopper Setup][grasshopper1]

I broke down my concept into simple geometrical objects i.e. Cubes, Spheres, and Cylinders. I inserted the objects in Grasshopper, performed the Boolean Operations.

![Rhino Preview][rhino1]

With a design preview ready I went on define the parameterised values that I wanted the user to control, and added them to the Remote Panel.

![Grass Hopper 2][grasshopper2]

I also added additional controls such as orientation of the charging puck.

![RemotePanel 2][remotePanel]

### Step 3: Bake the files, Slice in Cura

Once everything was ready, I baked the file, exported it to STL and sliced it in Cura.

![Cura][cura]

Now: I will now upload the files to a Prusa 3D printer at Jacobs and test the resultant prototype on an actual Apple Watch.

### Accomplishments so far:

I was able to create a Grasshopper Model and slice my 3D Asset (STL file) in Cura to 3D print them at the Makerspace.

The files:
[Grasshopper File][grasshopperFile]
[Baked 3D Geometry][rhinoFile]
[STL File][stlFile]

### Future Ideas

After the completion of a basic Grasshopper Model, I hope to take my learnings to build a eyeglass gallery in grasshopper, that offers users the option to customise the Eyeglass model by selecting the frame type: “Supra, Rimless or Rimmed” , the lens type “Circular or Super Ellipse” and the standard eyeglass parameters “Temple Length, Bridge Measurement, Eye Width”.

[existingChargers]: weekly-reports/img20230907/existingChargers.jpg
[desiredOutcome]: weekly-reports/img20230907/desiredOutcome.jpg
[grasshopper1]: weekly-reports/img20230907/grasshopper1.jpg
[grasshopper2]: weekly-reports/img20230907/grasshopper2.jpg
[remotePanel]: weekly-reports/img20230907/remotePanel.jpg
[cura]: weekly-reports/img20230907/cura.jpg
[drawing]: weekly-reports/img20230907/drawing.jpg
[rhino1]: weekly-reports/img20230907/rhino1.jpg

[grasshopperFile]: weekly-reports/files20230709/WatchCharger.gh
[rhinoFile]: weekly-reports/files20230709/BakedCharger.3dm
[stlFile]: weekly-reports/files20230709/Charger.stl


