# Weekly Report 1: 08/31/2023
## Vidit Bhargava

## Summary

This week I used the TDF Computational Design project files to get started with Rhino and Grasshopper. As someone with no experience using computational 3D modelling software this was a good starting point to explore the space and start using Laser Cutter and 3D printing tools in the Maker space.

My Process: 
I started with the Grasshopper and Rhino Files, learning how to use the tools using the worked example. I then spent some time defining my project scope, i.e. defining what I wanted to achieve with the stand and how it’d be useful to someone using it. I fed my design calculations into the Grasshopper interface, and generated the files to cut. I then evaluated my first laser cut and made a note of changes that’d make the design better. I gave a second cut and after I was satisfied with the results, I moved on to the 3D model. For the 3D model I took the same design considerations to generate a 3D model that’d help me, then I 3D Printed the files.

Following the completion of the process, I made a note of where I wanted to take the process in the future and designed a quick mock up of an aspirational cell phone stand that I hope to laser cut this week.

## Step 0: Getting to Know Grasshopper:

To get started with Grasshopper I used the solved examples to alter the parameters and understand how changing various blocks affected the design in Rhno.

I made sure to make modifications based on my phone’s dimensions

![Grass Hopper 1][grasshopper1]
![Grass Hopper 2][grasshopper4]

##  Defining the Objective

### Project Goals
I defined the project goals as follows: 
- Make a phone stand to record the video in at least the horizontal orientation. The phone angle should be such that the phone’s camera can capture what I am doing in front of my table. 
Extra Considerations:

- Support the phone horizontally and vertically.
- Support multiple screen sizes
- Support the phone with or without cover

## Designing

To start with the design process I made calculations of my phone with and without a case. I also used a larger phone to support at least one more size.

![measurements 1][measurement1]
![measurements 2][measurement2]
![measurements 3][measurement3]
![measurements 4][measurement4]
![measurements 5][measurement5]



I then defined the phone dimensions to create a hypothetical device that used the optimum parameters from the reading.

|Dimensions | iPhone 12 mini Without Case	| iPhone 12 mini With Case | iPhone 14 Pro without Case |
|---------- | --------------------------- | ------------------------ | -------------------------- |
|Depth      | 7.71                        | 10.47                    | 8.44                       |
|Width      | 64.44                       | 67.90                    | 71.63                      |
|Height     | 131.77                      | 135.44                   | 147.62                     |



I then adjusted the phone stand to include horizontal as well as vertical components by defining the prism such that it didn’t include the top holder this gave me the freedom to adjust the phone in the stand in whichever orientation I wanted.

![Grass Hopper 3][grasshopper2]
![Grass Hopper 4][grasshopper3]

I baked the files, and generated illustrator files for the first laser cutting.

### Print
A video of my first laser cut:

[![Laser Cutter Video](https://img.youtube.com/vi/1GZ71lY4LRw/0.jpg)][videoLaser]

## Observations

The laser cut sheets after assembly didn’t fit firmly and the phone kept toppling over after a few seconds.


![Design Fail 1][designFail1]
![Design Fail 2][designFail2]
![Design Fail 3][designFail3]
![Design Fail 4][designFail3]


## Corrections

To correct these errors, I measured the thickness of the plywood, and created a press fit dimension (5.25 mm for a 5.4mm thick material) 

I adjusted the grasshopper file to improve on the stand and laser cut again.

This time the corrections worked and the stand was able to hold both the phones in both orientations

![Corrections][corrections]


## Final Stand

![Final Stand 1][finalStand1]
![Final Stand 2][finalStand2]
![Final Stand 3][finalStand3]

## 3D Model

### Design Considerations

I adjusted the cone-height to accommodate both smaller and larger phones and made sure that the inner and diameter range was such that it allowed holding both phones. 

This meant making the stand smaller, so that it could hold the smaller and larger phone easily.

![Ultimaker][ultimaker]

### Bake and Print!

[![3D Video](https://img.youtube.com/vi/6rePAKOlDkU/0.jpg)][video3D]

![3D 1][3D1]
![3D 2][3D2]
![3D 3][3D3]

### Ideas for the future
I want to use the MagSafe puck to enable charging the phone while using it as a stand. Using the MagSafe also simplifies the design, as the use of magnet ensures we don’t’ need horizontal arms to support the phone’s weight.

![speculation 1][speculation1]
![Speculation 2][speculation2]



[grasshopper1]: weekly-reports/img20230831/Grasshopper_1.png
[grasshopper2]: weekly-reports/img20230831/Grasshopper_2.png
[grasshopper3]: weekly-reports/img20230831/Grasshopper_3.png
[grasshopper4]: weekly-reports/img20230831/Grasshopper_4.png

[ultimaker]: weekly-reports/img20230831/Ultimaker_1.png

[measurement1]: weekly-reports/img20230831/phone_small_1.png
[measurement2]: weekly-reports/img20230831/phone_small_2.png
[measurement3]: weekly-reports/img20230831/phone_small_3.png
[measurement4]: weekly-reports/img20230831/phone_large_1.png
[measurement5]: weekly-reports/img20230831/phone_large_2.png


[designFail1]: weekly-reports/img20230831/Design_fail_1.png
[designFail2]: weekly-reports/img20230831/Design_fail_2.png
[designFail3]: weekly-reports/img20230831/Design_fail_3.png
[designFail4]: weekly-reports/img20230831/Design_fail_4.png

[correction]: weekly-reports/img20230831/corrections_1.png

[finalStand1]: weekly-reports/img20230831/final_Stand_1.png
[finalStand2]: weekly-reports/img20230831/final_stand_2.png
[finalStand3]: weekly-reports/img20230831/final_stand_3.png

[3D1]: weekly-reports/img20230831/3D_1.png
[3D2]: weekly-reports/img20230831/3D_2.png
[3D3]: weekly-reports/img20230831/3D_3.png


[speculation1]: weekly-reports/img20230831/speculation_1.png
[speculation2]: weekly-reports/img20230831/speculation_2.png

[videoLaser]: https://www.youtube.com/watch?v=1GZ71lY4LRw
[video3D]: https://www.youtube.com/watch?v=6rePAKOlDkU
