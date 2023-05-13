# Emotions Database 
This repository contains a database consisting of different images/videos collected from undergraduate students of the University of Monterrey who were experiencing various emotions due to audiovisual stimuli. The collection process was supported by previous experimentation aimed at eliciting these emotions. Our ultimate objective was to perform facial analysis and utilize a neural network architecture to classify the specific type of emotion exhibited by the users in response to the stimulus in question.
## Table of Contents

- [Background](#background)
- [Methodology](#methodology)
- [Data available](#data-available)
- [Access Data](#acces-data)
- [Apply for Acces to Data](#apply-for-acces-to-data)
- [Application Review](#application-review)
- [Contact](#contact)

## Background
This dataset was used for the thesis project titled 'Emotion Recognition through Facial Analysis' to fulfill the requirements for obtaining a Bachelor's degree in Mechatronics Engineering at Universidad de Monterrey. Our motivation stemmed from the need to address security concerns reported by users, particularly female passengers, of private transportation platforms such as Uber, Didi, Cabify, etc. Our proposal involved developing a computer vision application with a camera installed in the vehicle cabin, capable of detecting specific emotions in passengers to predict potentially risky situations while using these services. We employed neural networks and generated our own dataset through multiple ethical research studies on emotion generation to train our algorithm. 

## Methodology 
The experimental tests were conducted in a designated room within the facilities of the Universidad de Monterrey. The participants were university members who voluntarily chose to participate in the research after reading and signing the informed consent form. The study population consisted of Spanish-speaking adults, including 60 men and 60 women aged between 18 and 23 years old.

Upon arrival, the volunteers were welcomed into the room and provided with an explanation of the research protocol. Any doubts or questions raised by the volunteers regarding the protocol were addressed, and their signatures were collected on the informed consent form.

We explained to the participants that we would be recording their responses while showing different movie scenes on a laptop, while they simultaneously wore a pulse oximeter. We informed them that the purpose of the study was to gain a deeper understanding of emotions, which required the presentation of movie clips that had the potential to evoke a wide range of emotional responses. Additionally, we asked the volunteers to keep their hands on the desk as much as possible and face the clips.

The volunteers were informed that they had the right to withdraw from the study at any time and that their responses would remain anonymous. This was the general procedure followed to collect the database.

1. The volunteer must sit in a chair in front of a table, the same position in which they will remain for approximately 15 minutes, and the pulse oximeter will be placed on the tip of the index finger.
2. The participant will perform the designated test to transmit **anger** 
  - Visual stimulus: 
     - Excerpt from the film “American History X” (A neo-Nazi kills a man by crushing his head) https://www.youtube.com/watch?v=b0vHfAh9Nfk
3. It takes 2 minutes for the participant to complete a distraction task: it will consist of 30 seconds in which they will be asked to identify geometric figures with some particular characteristic to capture attention.
4. The participant will carry out the test designed to transmit **happiness**
- Visual Stimulus: 
   - Film fragment "When Harry Met Sally" (Sally simulates an orgasm in a cafeteria) https://www.youtube.com/watch?v=HPeYdQdzlb4
5. It takes 2 minutes for you to complete a distraction task.
6. The participant will see the scene designated to transmit **fear**
- Viual Stimulus
   - Segment of the movie "The Blair Witch Project" (Final scene in which the protagonists apparently die) https://www.youtube.com/watch?v=pOB7Hl4YHt8
7. It takes 2 minutes for the participant to complete a distraction task.
8. This last clip is intended to facilitate the emotional recovery process, particularly after exposure to negative stimuli.
- Audiovisual stimulus
   - Excerpt from the song “Dancing Queen” by ABBA
9. To end the experiment, the pulse oximeter is removed from the participant and they are thanked for their participation.
  The participant is asked to fill out the post-test form: It is pointed out that they must answer this by reporting what they personally felt while viewing the scene and not what they thought people should feel with that scene.
## Data Available 
After collecting the data using the aforementioned methodology, we obtained a total of 603 videos, consisting of 5 cropped videos for each of the 120 volunteers who experienced specific emotions (anger, happiness, fear, and neutral). Additionally, we have a set of frames that we handpicked from each cropped video, showcasing various gestures. These frames were used to train the neural network for each emotion. You are welcome to check them out or select your own frames from the original videos. 
### Data code name 
Each video and frame are coded for it to be anonymous, for example "S101-E02.jpeg" for a frame refers to the second image of volunteer 101th experimenting anger. 
- SXXX: volunteer number 
- Letter after dash: 
   - E: anger 
   - F: happiness
   - M: fear
   - N: neutral
- E0X: frame number for that emotion
## Acces Data 
All data are shared through a Google Drive unit, which is secured and managed by the Universidad de Monterrey (UDEM) as a research data repository. Interested scientists can request access to the videos and images in the dataset for scientific investigations, teaching purposes, or planning research studies related to emotions, computer vision, AI, or other relevant fields. Access will be granted based on adherence to the Data Use Agreement and the publication policies outlined in the documents listed below. Please note that these documents are subject to updates by UDEM and the researchers.

 - Data Use Agreement
 - Group Acknowledgements List 

Data from pulsioximeter is complementary to the database and are also available through the application.** 

** May not be available at the time the database is being published 

## Apply for acces to data 

The application process includes acceptance of the *Data Use Agreement* and submission of an online application form. The application must include the
investigator’s institutional affiliation and the proposed uses of the data. Data may not be used for commercial products or redistributed in any way.

Apply in the following link: 
- link **

## Application Review
The Data Sharing and Publications Committee generally reviews data use applications within two weeks of submission. Each application is carefully reviewed to verify investigator affiliation with a scientific or educational institution and on the basis of the proposed research or data use. Incomplete applications or those without a clear focus will not receive approval. The results of the Committee's review will be sent via email. Approved applicants will receive login information to access and download the desired data. 

## Contact
For questions or other requirements you can contact either of the members who took part in the research:
- PhD. Antonio Martínez Torteya - Advisor (antonio.martinez@udem.edu)
- André Luna Flores - Student (andre.luna@udem.edu)
- Jenyfer Eugenia Toj López - Student (jenyfer.toj@udem.edu)
- Juan Carlos Aguilar - Student (juancarlos.aguilarr@udem.edu)
