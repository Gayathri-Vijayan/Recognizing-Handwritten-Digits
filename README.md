# Recognizing-Handwritten-Digits

Recognizing handwritten text is a problem that can be traced back to the first automatic machines that needed to recognize individual characters in handwritten documents. Think about, for example, the ZIP codes on letters at the post office and the automation needed to recognize these five digits. Perfect recognition of these codes is necessary in order to sort mail automatically and efficiently


<b> The objective is to predict the handwritten digits and validating the model using various ranges of training and testing sets.</b>

We chose <b> K-Nearest Neighbor </b> classifier for the training purpose. It is a Machine Learning model that tries to classify new value by comparing it with the values of its closest neighbors. Here we chose the number of neighbor’s as 7. As the initial set of data we took 1795 test images and the rest two images for training. The tested image is also further plotted.

Initial training was conducted using 1795 images and for the rest of the two images in the dataset was used for testing, which yielded 100 percent accuracy. Following this, we used a train to test ratio of 1700:97, 1400:397 and 1600:197, which in-turn yielded accuracies 0.96,0.95 and 0.948 respectively.

<h2> An approxiamte accuracy of 95% is obtained </h2>
