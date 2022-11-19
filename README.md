# Sign-Language-Translator-
#An LSTM-mediapipe deep learning  model used to perform sign language translation

Problem Statement
<ul>
<li>The only way the speech and hearing impaired (i.e dumb and deaf) people can communicate is by sign language. The main problem of this way of communication is normal people who cannot understand sign language can’t communicate with these people or vice versa.
</li>
<li>Our project aims to bridge the gap between the speech and hearing impaired people and the normal people. The basic idea of this project is to make a system using which dumb people can significantly communicate with all other people with the help of gestures. The system does not require the background to be perfectly black. It works on any background. 
</li>
<li>The project uses image processing system to identify, especially English alphabetic sign language used by the deaf people to communicate and converts them into text</li>
</ul>



<h1><span style = "color:blue">Key reasons as to why we choose LSTM-MEDIAPIPE over LSTM-CNN
</span></h1>


<ol>
<li>LESS DATA REQUIRED
</li>
<p>Since we are only storing the keypoint values in our dataset , size is not an issue than when compared to the frames to be stored in the case of a CNN model.
</p>
<li>FASTER to TRAIN</li>
<p>Keypoints from MediaPipe helps us focus only on the essential features of the  dataset rather than  concerning much about the surroundings which not only helps us to train our model faster but also makes our model much more efficient.</p>
<li>FASTER DETECTIONS</li>
<p>Our Neural network being more dense with an arguably comparable size of the dataset makes the model detect much faster.
</p>
</ol>




