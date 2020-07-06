# Welcome to Vallabh's Portfolio

This website exists primarily to share my data science projects and learnings with anyone who's willing to listen to my ramblings. But it may evolve over time.

## About Me

My name is Vallabh Reddy. I have a bachelor's in Computer Science and a master's in Business Analytics. I have been working in the Data Science field since 2015 across a few domains, namely, fintech, healthcare and retail. Mu Sigma, a decision sciences firm to which companies outsource their analytics and problem solving, was my first company. After which I worked at Amazon's Last Mile department. I'm a 2020 University of Cincinnati grad. Yes, I'm one from the Coronavirus wave of Bearcats.

In my free time I like to read non-fiction works detailing natural and man-made systems and I play squash and videogames. Also, I'm always willing to try new board games.

# Portfolio
Below is a list of complete and ongoing public Data Science projects of mine. 

1. [Image Classification on the Fashion MNIST dataset using Convolutional Neural Networks](#fashion_MNIST)
2. [Multilingual Toxic Comments Classification with only English training data - RoBERTa NLP Transformer](#multilingual_RoBERTa)
3. [USA Foreign Trade Analysis](#US_trade_analysis)
4. [Kickstarter Campaign Success Prediction](#Kickstarter)


 
## 1. Image Classification on the Fashion MNIST dataset using Convolutional Neural Networks <a name = 'fashion_MNIST'></a>

Github does not represent certain features of a jupyter notebook well, such as the intra notebook anchors, so here's a link to open the notebook through **[NBViewer]**(https://nbviewer.jupyter.org/github/VallabhReddy/Image-Classification-Fashion-MNIST-CNN/blob/master/Fashion%20MNIST%20Image%20Classification.ipynb).

Here is the **[Github link]**(https://github.com/VallabhReddy/Image-Classification-Fashion-MNIST-CNN/blob/master/Fashion%20MNIST%20Image%20Classification.ipynb) for the same notebook.

### Introduction
The objective of this project was to build an image classifier that could recognize the category of apparel in the photo fed into it.

### Dataset
The model is trained and tested on the [Fashion MNIST dataset](https://github.com/zalandoresearch/fashion-mnist). The dataset is provided by the research branch of Zalando, a European e-commerce company. The dataset is made up of 28x28 grayscale images of 10 categories of apparel. There are 60,000 observations in the training set and 10,000 observations in the test set. The mapping for the 10 categories of apparel is given below.

<table>
<thead>
<tr>
<th>Label</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr>
<td>0</td>
<td>T-shirt/top</td>
</tr>
<tr>
<td>1</td>
<td>Trouser</td>
</tr>
<tr>
<td>2</td>
<td>Pullover</td>
</tr>
<tr>
<td>3</td>
<td>Dress</td>
</tr>
<tr>
<td>4</td>
<td>Coat</td>
</tr>
<tr>
<td>5</td>
<td>Sandal</td>
</tr>
<tr>
<td>6</td>
<td>Shirt</td>
</tr>
<tr>
<td>7</td>
<td>Sneaker</td>
</tr>
<tr>
<td>8</td>
<td>Bag</td>
</tr>
<tr>
<td>9</td>
<td>Ankle boot</td>
</tr>
</tbody>
</table>

### Methodology
Using Keras for Python, the model is built of Convolutional Neural Networks(CNN) which are especially effective in image comprehension. The notebook contains several architectures of CNNs and their performance is compared. I used the GPU implementation of TensorFlow since this increases the speed of deep learning model training exponentially, but the drawback is that the results are not perfectly reproducible and setting a seed does not work for the randomizing operations performed by the GPU.

### Results
I was able to achieve a 91-93% accuracy of classifications on the test set using a 13 layer network.

Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)


For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/VallabhReddy/Data-Science-Portfolio---Vallabh-Reddy/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
