# Weekly Report: Week of 09/14/2023
## Vidit Bhargava

## Summary

This week I created a new Grasshopper model from scratch complete with remote panel controls, custom materials and modular components for Project 1. 

![Header][header]

## My Topic: Customisable Eyewear Model using Computational Design

## Process
I started by researching on how eyewear measurements are currently taken. I found it was a thorough process that took into account the various sizes and measurements of a person’s face and so I decided to use it for my own grasshopper model too.


![Eye Dimensions][eyeSize]

I then moved on to sketch the details of my eyeglasses, the mathematical measurements I needed to make and the parameters I wanted to adjust.
![Sketch][sketches]

![Grasshopper 1][grasshopper1]

After all was setup. I started working on my grasshopper model, starting with lens holders, then nose bridge, and then the temple sticks, and finally a flow for creating half-rimmed alternatives. Once I had everything setup, I grouped them and made the necessary dimensions available in the remote panel.

![Grasshopper 2][grasshopper2]

After setting everything up, I moved on to make my custom materials for the sunglasses, I designed the Acetate, Gold and Glass material files in Rhino, Saved them to my folder, and then imported the URL into grasshopper. 

![Materials][materials]

Here’s a video of my project:
[![Video](https://img.youtube.com/vi/kLXWczYozy4/0.jpg)][video]


## Future Goals

1. More shapes of eyewear
2. Handle values externally using JSON
3. Create a visual interface for adjusting parameters

## Speculation on human experiences, impact engineering, intersection with AI

Personally I feel customisable eyewear is an important area of exploration, because eyewear is so sensitive to minute changes in measurements that standard sizes are often not adequate.

It’s also one of the most stylistically varied wearable and having control over how you want them to look is a big plus. With computational design, that level of control is easily achievable.




[eyeSize]: weekly-reports/img20230914/eyeSize.jpg
[grasshopper1]: weekly-reports/img20230914/grasshopper1.jpg
[grasshopper2]: weekly-reports/img20230914/grasshopper2.jpg
[header]: weekly-reports/img20230914/header.jpg
[materials]: weekly-reports/img20230914/materials.jpg
[sketches]: weekly-reports/img20230914/sketches.jpg

[video]: https://www.youtube.com/watch?v=kLXWczYozy4
