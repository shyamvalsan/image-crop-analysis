# Linguistic bias against non-latin languages in Twitter's image cropping model

This is a repo that contains Twitter's Image Crop Analysis model and the data and code that shows how it is biased against text written in non-latin alphabet based languages. 

The premise of this analysis is that Twitter's image cropping model is unintentionally biased in favor of text written in the latin alphabet (specifically English, but also other latin scripts such as French). Considering that the majority of humans today speak (as their native language) a non-English and specifically non-latin script based language this unintentional bias could have far reaching impacts. 

In this analysis, we highlight bias against some of the most widely used non-latin languages such as:
- Chinese (1 billion+ speakers)
- Hindi (350 million+ speakers)
- Bengali (300 million+ speakers)
- Arabic (250 million+ speakers)

This bias has the primary effect of unintentionally under representing users from non-western countries who do not use languages written in the latin script. Chinese and Arabic speakers are the obvious examples here, India - which traditionally has had a majority of english speaking Internet users is now shifting to native languages for Internet usage with the advent of inexpensive wireless internet and smartphones. This trend could be replicated in other countries as well.

This bias may prevent Twitter users from non-western countries not being able to see the relevant information in Twitter image previews and also in many cases could highlight a section of the image that the poster did not intend to highlight. Considering Twitter's use in many countries as a real time tool that helps people organize in a democratic manner unimpeded by political crackdowns, the lack of access to relevant information at the right time could have serious consequences. 

This bias also unintentionally punishes businesses and individuals who use non-latin based text by reducing their visibility compared to latin based text users. This may have significant economic repurcussions when considered at scale (across entire Twitter user-base across many months & years).


# Instructions

- Open the notebook file in notebooks in Google colab
- Run the notebook and study the results with accompanying text to illustrate the bias mentioned above
- If you want to experiment with your own data please upload any additional images with `*.jpg` extension in DATA_DIR, which is `./data`


Citation for Twitter Image Crop Analysis Mode: 
```
@ARTICLE{TwitterImageCrop2021,
       author = {{Yee}, Kyra and {Tantipongpipat}, Uthaipon and {Mishra}, Shubhanshu},
        title = "{Image Cropping on Twitter: Fairness Metrics, their Limitations, and the Importance of Representation, Design, and Agency}",
      journal = {arXiv e-prints},
     keywords = {Computer Science - Computers and Society, Computer Science - Computer Vision and Pattern Recognition, Computer Science - Human-Computer Interaction, Computer Science - Machine Learning},
         year = 2021,
        month = may,
          eid = {arXiv:2105.08667},
        pages = {arXiv:2105.08667},
archivePrefix = {arXiv},
       eprint = {2105.08667},
 primaryClass = {cs.CY},
}
```
