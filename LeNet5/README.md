# LeNet 5

The research paper can be found at http://yann.lecun.com/exdb/publis/pdf/lecun-98.pdf

Standard fully connected neural networks have many drawbacks when it comes to dealing with images. A large enough FC network would work but it may end up with multiple units having similar weight patterns which is something CNN explicitly forces while providing computational advantage. Fully connected neural networks also ignores spatial features of the images i.e. pixels closer to each other are highly correlated and these "local" features can be extracted and classified into number of categories like edges, corners, etc. CNN forces this by keeping extraction of features to be local. Thus convolutional Neural Network worksbetter on images that standard neural networks for many reasons : local receptive fields, shared weights and spatial sub-sampling!
