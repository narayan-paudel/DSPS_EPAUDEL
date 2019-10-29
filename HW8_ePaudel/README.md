# Reading
Any one of ther 7 papers listed here. There selection and short description of each paper is from this blog post by Enrico Bertini, NYU.


[Graphical Perception: Theory, Experimentation, and Application to the Development of Graphical Methods](https://www.diliaranasirova.com/assets/PSYC579/pdfs/03.2-Cleveland&McGill.pdf). William S. Cleveland; Robert McGill

(E. Bertini's description:)

What’s in it? The paper describes a series of experimental user studies to understand how basic visual primitives like length, size, color, etc., compare in terms of visually carrying out quantitative information.

Why is it important? Cleveland with this paper introduced the idea and concept (quite vigorously) of visualization based on rigorous experimentation. People like Bertin many years before started ranking visual features but never before this ranking was validated with a scientific method.

What can you learn? The basics of data visualization. That visual encoding is hard stuff and you shouldn’t take it too lightly. And that visual primitives do have a ranking that you have to take into account if you want to design effective data visualizations.

[The Structure of the Information Visualization Design Space](https://www.academia.edu/4338732/The_structure_of_the_information_visualization_design_space?auto=download). Stuart K. Card and Jock Mackinlay

(E. Bertini's description:)

What’s in it? The paper describes what are the basic components that build up a visualization and how to put them together to build a new design.

Why is it important? Because it is one of the first attempt to describe the visualization space in a systematic way.

What can you learn? You learn that in order to design innovative visualizations you have to know what the building blocks are and how to connect the. In my experience this is one of the most important, and often neglected, skills.

[Visual Information Seeking: Tight Coupling of Dynamic Query Filters with Starfield Displays](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.123.4320&rep=rep1&type=pdf). Christopher Ahlberg and Ben Shneiderman

(E. Bertini's description)

What’s in it? It describes one of the first attempts to make visualization dynamics and controlled by the user through interactive queries.

Why is it important? The whole idea of dynamic filtering had a huge impact on the way data is visualized interactively. We can see the effect of this idea everywhere. Before that, there where queries in a database. After that, it was clear how powerful interactive visualization could be.

What can you learn? You learn how powerful data visualization can be when interactive capabilities are added to static representations. After more than 10 years we are still learning this lesson.

[High-Speed Visual Estimation Using Preattentive Processing.](https://www.csc2.ncsu.edu/faculty/healey/download/tochi.96.pdf) C. G. Healey, K. S. Booth and J. T. Enns

(E. Bertini's description)

What’s in it? It describes how the concept of preattentive processing can help in guiding the design of visualization and user interfaces. It contains several experimental studies.

Why is it important? Nobody before the work of Healey (maybe Colin Ware?) pushed the limits of perception applied to visualization so far. I bet many of the results of his studies have yet to be exploited.

What can you learn? You learn what preattentive processing is and how to apply it to the design of information visualizations. (As a byproduct you might also learn how tough this stuff is!)

[Automating the Design of Graphical Presentations of Relational Information](https://research.tableau.com/sites/default/files/p110-mackinlay.pdf). Jock Mackinlay

What’s in it? Jock presents a system called APT (A Presentation Tool) whose purpose is to automatically design effective visualizations automatically by matching data features with visual features through the use of logic rules.

Why is it important? It is not only important because it contains some visionary perspective in visualization but also because part of the work was focussed on the definition of visual primitives (starting from the work of Bertin) and on the way data features should match visual features.

What can you learn? Knowing how to match data features to visual features is one of the most important skills of knowledgeable data visualization experts.

[How NOT to Lie with Visualization](https://pdfs.semanticscholar.org/058e/2e38420b61d8d870590d971d4e7d1cd078c2.pdf). Bernice E. Rogowitz, Lloyd A. Treinish

What’s in it? A detailed explanation of how the visual eye can be mislead if the wrong (color) mapping is used. Plus a thorough discussion of how to build effective color scales that take into account data distribution.

Why is it important? I still see a lot of people using color badly. By reading this I hope this number will get smaller and smaller. It is also an early example of how automatic computation and interaction can go happily together.

What can you learn? This paper will give you solid arguments about why mapping color badly is bad. Plus you will learn how to build effective color scales. On a side note, the same is true for every other visual feature you want to use.

[The Eyes Have It: A Task by Data Type Taxonomy for Information Visualizations](https://www.cs.umd.edu/~ben/papers/Shneiderman1996eyes.pdf). Ben Shneiderman

What’s in it? A classification of information visualization techniques according to data type. More importantly the explanation of the visual information seeking mantra: “overview first, zoom and filter, details on demand”.

Why is it important? The visual information seeking mantra has been the reference model for interactive visualization for 15 years. Hundreds of systems have been developed under this paradigm.

What can you learn? The classification by data type will help you mentally organize visual designs into classes (even if I must admit I am not a big fan of this classification). The visual information seeking mantra will guide you in designing and evaluating interactive visualizations: do you have an overview? zoom and filter capabilities? details on demand? tools to relate things? history facilities?


# Homework
 
 Create a plot, of whatever data (and models if you want) you choose from open data (if you have doubt about whether your dataset is relevant for this homework please email me.)

You can make the plot in any coding language you want (e.g. python, javascript, R...), as long as you upload the code that generates the plot onto your repo (which means no tableau, or any other non reproducible).

Create a directory HW8_<firstLast> in your DSPS repo . The plot neads to be uploaded onto the HW8_<firstLast> folder in your github repo and be embedded in the README.md. That means: when I click on the HW8_<firstLast> link the plot must be rendered in the front page of the repo. Your readme must contain the plot, and a brief caption (see [here how to](https://github.community/t5/How-to-use-Git-and-GitHub/How-do-you-put-Images-on-the-README-md-file/td-p/3203)). If it is an interactive graphic, upload a static image of it in the README and provide a link to the interactive version.

Please make an effor to make it a compelling graphic. Put though into the esthetic of the plot, how clearly the content is communicated, avoid clutter, avoid misleading elements, mind your choice of colors accordingly to what was discussed in class. But you can violate the rules we discussed in class on purpose if you want! My main recommandation is that you have fun with this plot! 

Each of you needs to upload their own plot, no group submissions.

If your plot shows up as I described above in the repo and the code is also uploaded you will get 100% of the HW points. (Next week you will be tasked to review 3 plots of your classmates and you will be graded on the quality of the review.)

# Homework 2 (667 and Extra Credit): 

Practice contour-scatter plots following [this skeleton notebook](scattercontour.ipynb)

