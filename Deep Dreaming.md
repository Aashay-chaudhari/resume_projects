Link to colab implementation: https://github.com/Aashay-chaudhari/DL-Projects/blob/master/DL%20Image%20Projects/Object%20Detection%20Using%20Pretrained%20Model%20(yolo).ipynb

DeepDream is a computer vision algorithm developed by Google that utilizes artificial neural networks, particularly Convolutional Neural Networks (CNNs), to generate and enhance images. It was initially designed to explore the inner workings of neural networks and understand what features they learn from training data. However, it has also gained popularity as a creative tool for generating psychedelic and surreal images.

Here's how DeepDream works:

Convolutional Neural Networks (CNNs): DeepDream uses pre-trained CNN models, such as Google's Inception architecture. CNNs are designed for image recognition tasks and have multiple layers that extract features at different levels of abstraction from an input image.

Feature Visualization: DeepDream starts with an existing image and passes it through the neural network. It then selects a specific layer within the network to enhance features. This layer is often chosen because it has been found to capture exciting patterns or objects.

Feature Amplification: The algorithm amplifies the patterns and features that the selected layer detects in the image. It does this by iteratively modifying the input image to maximize the activation of specific neurons within the chosen layer. In essence, it encourages the network to "dream" about the patterns it has learned.

Repetition: The process is repeated multiple times, each time selecting a different layer or combination of layers. This gradually leads to the emergence of abstract and hallucinatory patterns in the image.

Outputs: 

Initial Image:
![dd2](https://github.com/Aashay-chaudhari/resume_projects/assets/93089131/6cc99552-70af-4c60-872b-fd9d9a335452)

Transformed Image: 

![dd1](https://github.com/Aashay-chaudhari/resume_projects/assets/93089131/fbe23289-61a2-4be6-b4b6-9d2341968178)
