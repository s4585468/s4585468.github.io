# **Bird in the hand bird in the screen. Is it a bird?**
# **00-is-it-a-bird-creating-a-model-from-your-own-data.ipynb**

After much trouble I managed to successfully run the is it a bird example on the fastai course. I beilieve one of the error is duckduckgo is scraping an image which has a file extension the python script cannot handle then again what do I know.

I managed to successfully carry on as the jupyter notebook allows for me to pick up from the next line of code and even with the errors the code manages to snag enough pictures of birds. 

My undestanding of the 00 example in fastai course is its a tutorial on how to construct a deep learning model to seperate images into relevant categories. It uses python librarires and fastai to perform these tasks. It is fascinating to see the success rate of pre-trained models. 

**My key takeaways from this example:**
1. Ive never used DuckDuckGo before for anything its such a powerful tool!
2. I had no idea how high-level FastAi was before beginning I was expecting to have hundreds of lines of code to achieve a minor task. 
3. The tutorial was really good on teaching us how to prepare the data for being used for the task. Creating directories, storing images for training. Also the section about cleaning corrupted files was very helpful.
4. FastAI DataLoader and DataBlock was also discussed in this example.
5. ResNet18 and pre-trained models deomonstrated the power and how useful/effecient using these models are. Its trained to classify birds and forests.
6. '''python fine_tune()''' was used in the 00 example to check how accurate the method was. 

# **Imrpovements**
This example was great to wrap my head around fast ai below is a list of things I can use the learning from this example and build upon. 

1. More categories of animals see if it'll work with specific bird species. 
2. Improve the data cleaning 
3. Use different models as ResNet18 is a pretrained model could try using ResNet34, ResNet50 or even a more recent architecutre such as EfficientNet. 
4. User Interaction: Create a mode where user can upload their own images.
5. Monitoring and updating the model.

