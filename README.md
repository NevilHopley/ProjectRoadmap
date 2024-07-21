# ProjectRoadmap

This code was inspired from part of a 5-day training course run by the Scottish Government in Apr/May 2024, called 'Fit for the Future'.

On the last day of the course, there was a session about Project Roadmaps. Many of us were challenged about how to best draw a slide that looked like a meandering road, that has markers placed on it.

This R code generates such an image, and animates markers moving down the road.
See the folder called `examples` to view some `.xlsx` files that subsequently generate the corresponding `.gif` files.
The `.mp4` file is creating by submitting the `.gif` file to [this FreeConvert website](https://www.freeconvert.com/convert/gif-to-mp4/download)

To generate your own animated Project Roadmaps:
1. Create a folder and put the `Project Stages.xlsx` and `Project Roadmap.Rmd` files into it.
2. Edit the `Project Stages.xlsx` file to have as many stages as you wish to include in your animation.
3. Create a sub-folder called 'output'.
4. When run in RStudio, the `.Rmd` file creates a `.gif` file in the `output` folder.

Happy Project Roadmap creating!
