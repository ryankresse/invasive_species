## Invasive Species
The goal of the [Kaggle's Invasive Species competition](https://www.kaggle.com/c/invasive-species-monitoring) was to create a model that could detect invasive hydrangea in pictures of the Brazilian forest like this one:

![Invasive hydrangea](https://raw.githubusercontent.com/ryankresse/invasive_species/master/73.jpg)


My approach was to finetune a vgg-16 network, which scored an AUC of .964. I could have improved that score by:
- using a more modern network, like inception
- adding data augmentation to prevent overfitting

Files:
- invasive_species.ipynb: finetuning a pretrained vgg-16 model to create a submission 
