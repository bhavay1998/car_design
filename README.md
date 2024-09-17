# Image Classification in Computer Vision
The main library used to create the notebook: *fast.ai* <br><br>
The aim of the project is to use CNN based resnet18 model for image classification (4 design categories). The project is carried out using transfer learning to differentiate between four car body designs: Van, Hatchback, Convertible and Pickup Truck. The model is deployed as a web application where users can insert any vehicle's image and the model will classify its body design out of the 4 categories.
<br><br>
### Dataset
The dataset for the purpose of training the model is created using *duckduckgo* image search API. Each category of car design rougly includes 200 images. 

### Web Application
The created model is deployed using the *HuggingFace API*. The interface is constructed using *Gradio*. A notebook explaining how the model has been deployed is included in the repository.<br><br>
Link to the web application: <u>https://huggingface.co/spaces/webjar/car_design</u>

