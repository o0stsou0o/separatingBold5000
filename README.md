# separatingBold5000
This experiment is an attempt to separate the responses in the 3 datasets in Bold5000 (Imagenet, COCO and Scene Understanding) in hilbert space.  

The data is V4 in a macacque collected across 12 days with between 25 and 35 channels recorded every day and between 2 and 3 repeats of the stimuli per day.  

Initially TSNE was used with little visible clustering.  

Then, a one vs. one SVM was used with a decoding accuracy averaging around 38 percent.  This is better than chance (33 percent) but not much better.  

Then, a k-nearest neighbors was used which also yielded a decoding accuracy between 37 and 40 percent accuracy.  Again, better than chance but not much better.  

