# Image Comparison
A python project that uses image processing libraries for measuring similarities between images and drawings.

The idea behind this project came from a friend that was doing some studies about neuropsychological assessments in which examinees are asked to reproduce a complicated line drawing such as the [Rey-Osterrieth complex figure](https://www.researchgate.net/profile/Stephen-Smith-112/publication/221594112/figure/fig2/AS:667654494879758@1536192644901/The-Rey-Osterrieth-Complex-Figure-Typically-20cm-in-length.png). A little about the background of this assessment is that examinees are asked to first draw a copy of the Rey complex figure through recognition, and then draw it from memory. This type of test is often used to evaluate different aspects of the examinees such as their memory abilities, attention span, planning techniques, and working memory. Additionally, this type of test is often used to find any secondary effect from brain injuries and to test for the presence of dementia.

As a result, the neuropsychological assessment caught my attention and I decided to make a project similar to it. In this project, CV2 library from Python was used to make use of the ORB object that will help scoring the similarities between images with different dimensions.
Additionally, image_slicer library was also imported to split the images in different parts and do the comparison by parts. Through this way, I will also be evaluating each 
scoring to see which one is more accurate, by parts or by the entire image. 
