# CAT DOG classification Using TF

Hi! myself **Siddharth** I have made a simple classification project using the TensorFlow library 



# Files

Images has be downloaded from Kaggle.com 
(link to image dataset) ==> [Cats-vs-Dog Dataset](https://download.microsoft.com/download/3/E/1/3E1C3F21-ECDB-4869-8368-6DEBA77B919F/kagglecatsanddogs_5340.zip)


## Creating files and folders

We then upzip the folder and then arrange the files in order accordingly creating the following folders having the files
* **tmps** 
* **imagetest**

* tmps/cats-v-dogs\training 
* tmps/cats-v-dogs\validation 
* tmps/cats-v-dogs\training\cats 
* tmps/cats-v-dogs\training\dogs
* tmps/cats-v-dogs\validation\cats 
* tmps/cats-v-dogs\validation\dogs

The imagetest folder consist of images which u can download from WEB  

## Model

* The model uses Convolution to find out important features of Data 
To know more medium link [About Convolution and Its derivation](https://towardsdatascience.com/deriving-convolution-from-first-principles-4ff124888028)
- The first layer, Conv2D, is a convolutional layer with 3x3 filters and ReLU activation function.
	- It takes in 150 x 150 pixel input images and outputs the result as 3 x 3 feature maps.
	- MaxPooling2D, is a max pooling layer with 2x2 filters and ReLU activation function.
	- It takes in 2 x 2 feature maps from the previous layer and outputs one final feature map with size of (150, 150).

* Repeating the same for 3 times ( my cpu is suffering from strokes 😂😂)
* Then we Flattern it 
* Finally now model is ready to get trained

## Testing 

* After the model gets trained we can now test it using custom inputs which u can input 

## Fine tuning Model
The model can be fine tuned much more here are few things u can do 
* Changing the Image Augmentation like
	* Changing the Dimensions of the image
	* Cropping the Image
	* Shearing the Image
	* Adding Noise
* Adding more Convolutional Layers
* Adding Droupouts (set it to 0.3 max) 

## Help required 
If anyone out there in the community knows how to use GPU's in laptop/computers please help me to use the GPU and also help me how to use GPU parallelization to run the models even more faster 

**GPU SPEC**
* Currently using a Laptop GPU (GTX 1650 TI) 

### If any more info required please comment it out
* [Linkedin](https://www.linkedin.com/in/siddharth-d-816074217/)
* [Instagram](https://www.instagram.com/siddhu252004/)
