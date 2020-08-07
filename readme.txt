"realfiftyimages.ipynb" contains the script that could generate training samples.
The folder "fiftyimages" should contain the firsthand image that are used to generate training data. The images should be named as "fiftyimage (i)", "i" is a constant.
The four folders "rescaledimage","randomperspective", "homographyparam", "inverse" are the folders that the generated data would be saved in.
"handwriting1.tif" is the sample image that would be used to test the neural network.
"finalscript.ipynb" is the script that would input the sample image into the network.
"dataset.py", "model.py", "train.py" are used to define and train the network. "dataset.py" preprocesses the data. "model.py" defines the network. Run "train.py" to train the network. They are cited from https://github.com/paeccher/Deep-Homography-Estimation-Pytorch/blob/master/dataset.py
Before training the network, you would have to put the images that you wish to use as training data into the 3 folders in the "data" folder, which are "test2014", "train2014" and "val2014"

To fully go through the project, first use "realfiftyimages.ipynb" to generate training samples. And the train the network on the generated images. Then run "finalscript.ipynb" to test the result.

It seems like Github could not upload empty folders. So one may want to create the folders on their own. Or one could download the rar file which include the entire structure of the files and folders.

Images and the trained network model are also too big to be uploaded. Please contact 985468562@qq.com if needed.
