## Next Word Prediction

![R](https://img.shields.io/badge/-R-000000?style=flat&logo=R)
![Shiny](
https://img.shields.io/badge/ShinyApps-blue?style=flat&labelColor=white&logo=RStudio&logoColor=blue
)

![alt text](https://github.com/danvargg/r-next-word/blob/main/images/next_word.PNG)

### The project

This is a usable public data product in the area of natural language processing. It predicts the top 3 most likely words 
that follow a prompt.
The application can be found [here](https://danvargg.shinyapps.io/shiny/)

### The data

The data comprises texts extracted from news, blogs and tweets in English. The corpora comprises **4.26
million lines** and **102.4 million words** in **799.5 Mbs**.

### Processing the data

Below, there is a visualization of how I processed the data to feed the prediction algorithm.

![alt text](https://github.com/danvargg/r-next-word/blob/main/images/algflow.png)

### The application

The application predicts the next word based on N-gram "Stupid Backoff" model
algorithm ([Brants et al 2007](http://www.cs.columbia.edu/~smaskey/CS6998-0412/supportmaterial/langmodel_mapreduce.pdf)).

Below, there is a visualization of how the application works.

![alt text](https://github.com/danvargg/r-next-word/blob/main/images/appflow.png)
