# 3150 Final Project 

### About the project

**Please look at the final.ipynb to view my project, the backup isn't important for the project, just peices of code I wanted to keep.**

There are some folders labeled "data",  which contain some images and pictures I've used testing and comparing with some of the different functionality from the given programs.  
Likewise, the "models" folder contains data for the SVM classifier and the an additional file for the for normalizing the vector values going into the model.
Both were from the libsvm python library, I did have to create a folder for the data to be accessible in the notebook.  This is most likely due to how my enviroment is configured on my laptop.

**This is more a general overview of how the project came to be. This is being written after everything.** 

Initially I was trying to come up with something engaging as a image processing project.  I'm more of a data guy and while it was tempting to implement some machine learning type problem, I wanted to stay true to the course and requirements.
I thought it would be cool to do some kind of like data analysis for an image, generalizing a report of sorts that can provide value for someone or anyone looking to get something technical from said image.
To me, color(s) and where my eyes lead me in a image, made the basis for what I thought would do that.  Kind of analyzing color, what part of an image is "more" important, and grading an image I thought fit a "image report".
There is nothing really based on that assumption, just a lot of liberty that those functions for image reporting, generally capture the gist of an image.
This of course could be way off and I did preface that wthin the project.

I looked around for a while on Google looking at ideas that I thought we're good and things I'd like.
I wanted to do something that wasn't just another image processing project where I didn't really give an attempt at my own idea.
Note, that the code used in this project is sourced from other projects or websites.  However, the "new" or my take on it, is using these tools for a different purpose then the function they solve.
The creative aspect isn't in my own attempt to solve the problems I had in this, but rather applying them to an abstract idea, the image report.
I suspect that my scope was too big and I did more than I should of, especially after giving the presentation for the project.
In theory though, I thouht that if you were a photographer or artist or maybe even a person looking to value your art, this would have some application.

In truth, I would've wanted the code to be constructed as a python project.  Where you, the end user, run a project that opens up a GUI and offers the three choices of: color analysis, visual saliency, and a BRISQUE score.
The user would just drop their iamge or photo into the GUI as input and then be prompted for a response on which action to take.
However; here, this is ran on a jupyter notebook, mainly for convience on my own, but also you can just see the output to get a sense of what the project ideally was supposed to offer.

Finally, last bit of reflection here.  I treated this like a data analysis of a some object.  When I really started looking at what I did and what it meant with regards to an image.  I discovered that doing a machine leanring project to determine emotion from an image would be a really cool project.
That really is something I think is truly interesting and even my searches on the web returned that this hasn't been done really.  There was some baseline attempts from extracting features, but nothing really a model that does this.
If I could go back, I might have tried this, using the colors in an image, along with texture, and maybe even pixel intensity to accomplish that.  These are some image processing tools, so it its within the context of the project.
I think of warm or cool colors evoking a atmosphere, where say cool colors may indicate sadness.  If the pixel intensity was low, or the image was fairly dark, I think the same arguement can be made for that as well.  Even the texture in paintings where the artist might have used really muddled compositions could indicate the intention in the paintings.
Again, thre isn't much backing these ideas, in fact, its more intrinsic in nature that, seeing a baby smiling or puppy dogs are usually seen as a positive or good thing.  Same with a relaxing on the beach or on the other end with an iamge of war or a ward in a hospital as a negative thing.

I didn't have a real goal in mind when I started, just ideas I thought were cool, if I was going to analyze something, it'd be these things.
Getting through all of this, lead me to the closing point of this readme.  Hopefully, this makes sense and the project is coherent enough to stand on its own as it is, for what it is.
