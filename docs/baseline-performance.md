# baseline performance
While convolutional networks have been around for a long time, they have recently found success. The advancements in technology have allowed larger networks than ever before and even bigger datasets of training images. The capacity and capabilities of deep convolutional networks have risen rapidly in recent years.

Typically convolutional networks are used for classification and given a fairly large image to classify to a single class label. Through a revolutionary method of localization, a method in which a large image is broken down into many smaller images called patches.

There are several factors to keep in mind when using this approach. The two drawbacks are that this method is slower, as every individual patch of an image must be run through the network one at a time. Secondly, there is the trade-off between localization accuracy vs. context. Bigger patches can be bad for localization accuracy while patches too small can provide little useful context.

We use this all as the foundation for the “fully convolutional network”. This will use fewer training images to produce outputs with more accurate segmentations, and these segmentations are cropped into smaller, overlapping segments. These segments are cropped down to a point until they are upscaled back up, and an important part of U-net is that during the upscaling there are features applied. This feature of U-net and the overlapping allows for the extrapolating of context when it might not be there.

In this project, we use satellite images as the training set for our network using the principles of U-net approach. We have a training set of some satellite images, we break these images down into smaller segments and use localization and context to train our network to making more accurate outputs with as low a loss as we can.
