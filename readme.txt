If you use this corpus / data:

Please cite: M. Hodosh, P. Young and J. Hockenmaier (2013) "Framing Image Description as a Ranking Task: Data, Models and Evaluation Metrics", Journal of Artifical Intellegence Research, Volume 47, pages 853-899
http://www.jair.org/papers/paper3994.html

!!!!!!!!!!!!!!!!! IMP !!!!!!!!!!!!!!!!!!!!!!!!!:
ALL ABOUT DATASETS:
To download this Flicker8k_Datasets refer to the provided links(once downloaded paste them into location where other .ipynb files are):
https://github.com/jbrownlee/Datasets/releases/download/Flickr8k/Flickr8k_Dataset.zip
https://github.com/jbrownlee/Datasets/releases/download/Flickr8k/Flickr8k_text.zip

Flickr8k.token.txt - the raw captions of the Flickr8k Dataset . The first column is the ID of the caption which is "image address # caption number"
Flickr8k.lemma.txt - the lemmatized version of the above captions 
Flickr_8k.trainImages.txt - The training images used in our experiments
Flickr_8k.devImages.txt - The development/validation images used in our experiments
Flickr_8k.testImages.txt - The test images used in our experiments

ExpertAnnotations.txt is the expert judgments.  The first two columns are the image and caption IDs.  Caption IDs are <image file name>#<0-4>.  The next three columns are the expert judgments for that image-caption pair.  Scores range from 1 to 4, with a 1 indicating that the caption does not describe the image at all, a 2 indicating the caption describes minor aspects of the image but does not describe the image, a 3 indicating that the caption almost describes the image with minor mistakes, and a 4 indicating that the caption describes the image.

CrowdFlowerAnnotations.txt contains the CrowdFlower judgments.  The first two columns are the image and caption IDs.  The third column is the percent of Yeses, the fourth column is the total number of Yeses, the fifth column is the total number of Noes.  A Yes means that the caption describes the image (possibly with minor mistakes), while a No means that the caption does not describe the image.  Each image-caption pair has a minimum of three judgments, but some may have more.


!!!!!!!!!!!!!!!! IMP !!!!!!!!!!!!!!!!!!!
ABOUT CODE:
There are 2 main .ipynb file. One is 'CompleteCode' another is 'GenerateNewCaptions'. At First u have to run CompleteCode.ipynb file in order to create some additional files(extract_features, descriptions, etc.) and also define Deep learning model(which in our case will be trained for 6 iterartions). Once u have fully ran the CompleteCode.ipynb file now u can use GenerateNewCaptions.ipynb file only(u don't have to run CompleteCode.ipynb file anymore unless and until u want some changes/delet some files) to create new captions.
