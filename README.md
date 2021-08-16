# Facial-Emotion-Recognition-Visual-and-Audio-


#### Initially Mel Frequency Cepstral Coffecients alone were considerd enought to map and extract the essential features but that assumption soon proved wrong from the accuracy that resulted. Therefore the noted and learnt features which can always be used to improve and help map the features of an audio signal are: 

* Spectral Roll Off
* Spectral Centroid
* Spectral Bandwidth 
* Zero crossing Rate
* Chroma
* The 1st and 2nd derivatives of the Mel Frequency Cepstral Coefficients. 

 #### I was not able to compute the classification report for both the portions of the Facial Emotional Recognition since honestly MY GPU started misbehaving after all the long hours of training and hibernating. 

### With enough compute power it'll be easy to render the input facial video and predict the visibly expressed emotions, but there's one caveate:

* #### Not all the times are the emotions obvious from the facial expression and only such cases shall audio signals be used to compute the possible emotions. 
* #### With audio signal a new dimension to the emotion recognition can be relatively much more easily unlocked than it is possible visually, which is the *intensity* of the emotion. 
* This is way of adopting to audio recognition was not suggested in the linked paper and could be a very useful way of combining the visual and audio signal inputs to compute the emotion and the intensity of the emotion. 
* To reduce the computational a relatively simpler neural network can be used on the embeddings of the video frames. A pretrained model really boosts the predictive capabilities of the model and a fast way of deriving the embeddings from the video frames or reducing the sampling rate to meet the renderring requirements will prove worthy. 

please contact me at vishakarudhra@gmail.com if faced with any trouble regarding the vgg16 face descriptor model weights file. 
