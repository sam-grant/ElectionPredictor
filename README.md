# Election modelling using ML

Presently, I can make predictions with an average accuracy of ~60%. I use logitistic regression and a random forest classifier -- the accurancy is identical between them. 

Notes: 
* My dataset is currently a bit limited and I only use two features: unemployment rates and consumer inflation. These have good annual data *and* a reasonable correlation with left/right political lean. 
* I currently only go back as far as 1960, due to aforementioned limitatations with the dataset. Also, assigning a clear left/right affiliation to presidental candiations becomes increasingly difficult the further back you go. 
