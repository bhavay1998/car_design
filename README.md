# Image Classification in Computer Vision
The main library used to create the notebook: **fast.ai** <br><br>
The aim of the project is to use CNN based resnet18 model for image classification (4 design categories). The project is carried out using transfer learning to differentiate between four car body designs: Van, Hatchback, Convertible and Pickup Truck. The model is deployed as a web application where users can insert any vehicle's image and the model will classify its body design out of the 4 categories. An overview of the most common body designs can be found here: https://www.motorist.sg/article/722/the-different-types-of-car-body-styles-explained/

### Dataset
The dataset for the purpose of training the model is created using *duckduckgo* image search API. Each category of car design rougly includes 200 images. For model training, 20% of the data is kept as validation set.

### Model File
In order to re-create the model the notebook can also be run on *Kaggle* with **GPU accelaration enabled**. After all cells in the notebook are executed, the model is exported as an outpul file named *bd_design.pkl*. This file can be imported back in a new environment/notebook to perform image classification tasks.

### Web Application
The created model is deployed using the *HuggingFace API*. The interface is constructed using *Gradio*. A notebook explaining how the model has been deployed is included in the repository.<br><br>
- Link to the web application: <u>https://huggingface.co/spaces/webjar/car_design</u>
- Link to the notebook explaining model deployment: <u>https://github.com/bhavay1998/car_design/blob/main/Creating_web_app_gradio.ipynb</u>
