# AI-Powered secure e-voting system - MS-Engage-22:
It is an online voting system in which, a voter can vote online with two step verification: Face recognition &amp; detection, OTP verification

# # Frauds and Risk in our current voting system:
•	Every election, we get to hear fraud voters trying to manipulate either the Ballot papers(US) or cast fraud votes in the EVM (India).<br/>
•	During Covid-19 Pandemic, election did happen and people in long queues and crows casted their votes. There was a heavy risk of outbreak of the disease among them.<br/>
•	Apart from the elections to elect the govt, there are other elections, like for the student president, leader of NGO or self-help groups, which were conducted  online through forms.<br/>

# # Features
•	2 Step verification for improved security: Face-recognition and OTP.<br/>
•	Hussle free, voting can be done using a few clicks, data privacy ensures while transmission and ballots verification.<br/>
•	Uses more advanced and appeasing technologies that drive development.<br/>
•	Voter’s profile and vote is being monitored and stored in real time, increases transparency in vote casting & protects the uncertainty of identity of voter.<br/>
•	Easy calculation and storage of data.<br/>

# # Benefits:
•	With a few mouse clicks, one can administer voter participation in real time and engage voters. Election organization is substantially simplified with easy ballot production and personal election invitation design, as well as automatic vote counting. Voting on paper is both expensive and damaging to the environment.<br/>
•	Simple, location-independent, and accessible voting should be the norm. To increase turnout, lower the obstacles to participation and provide secure online voting to your eligible voters. The addition of an online voting option allows qualified voters to vote at any time throughout the election period and from any location.<br/>
•	Using OTP on a mobile phone/email. It is argued that Internet voting is insecure since client-side security is not controlled, in addition to the risks of absentee voting, such as ballot coercion and vote buying and selling, and the vulnerabilities of paperless electronic voting machines.<br/>
•	In online voting, a face detection and recognition technology is utilized as an authentication method. Voting through the internet allows voters to vote from anywhere in the state or from outside the state. The image of the voter is recorded and sent to a face detection algorithm, which detects his face and saves it as the first matching point.<br/>
•	Voter and Admin persona: A voter can independently cast his vote without any subject of external forces/pressures just with a few clicks and one individual can neither see nor manipulate someone’s vote. The admin has the access to voting results and can also see pie chart with the vote distribution.<br/>


# # How to run the project:

•	Install `Python 3.7.3`. <br/>
•	Install pip latest version using `python install pip`. Pip version used in this project is `pip==22.1` .<br/>
•	Clone this repository on your computer using `git clone https://github.com/Amlan-prog/-AI-Powered-secure-voting-system-MS-Engage-22.git`<br/>
•	`cd` to this directory.<br/>
•	run `pip install -r requirements.txt` inside the file directory.<br/>
•	Run `python app.py` inside this directory to run the project.<br/>
•	Enjoy the AI-powered secure E-voting system!

# # Algorithms used:
# # # LBPH Algorithm
I used the LBPH algorithm for face detection and recognition: The Local Binary Pattern (LBP) texturing operator labels pixels in an image by thresholding each pixel's neighborhood and treating the result as a binary number. We must first train the algorithm. We'll need a dataset containing the faces of the people we wish to recognize. We must also assign each image an ID (which might be a number or a person's name) so that the algorithm can recognize an input image and provide you with output.
##### Flowchart for LBPH Algorithm
![image](https://user-images.githubusercontent.com/106246237/170875535-d2a5745f-157e-4bbb-846b-a38ced3504c5.png)


# # # Haar-cascade Algorithm
Rather than using the pixel's intensity data, it alters the contrast between neighboring rectangular groupings of pixels. The contrast variances between pixel groupings are used to estimate the relative bright and dark areas. Two or three neighboring groups with relative contrast variance constitute a Haar-like characteristic. Having an accuracy of 95%, the algorithm is extremely successful in face detection. Haar classifier cascades need to be trained for detection of facial features of human i.e., mouth, eyes, nose etc.
##### Flowchart for Haar-cascade Algorithm
![image](https://user-images.githubusercontent.com/106246237/170875641-f25afa92-880b-4d47-85d6-e7dfe6ea2759.png)


## System Architechture
![image](https://user-images.githubusercontent.com/106246237/170875663-8cfefd74-b098-4b0a-bb96-e3326c7b5151.png)



## Link to PPT
https://docs.google.com/presentation/d/1X2DS4oQx7-ns9vRKsWSMlbcEgEavgOVP/edit?usp=sharing&ouid=103275090668226320175&rtpof=true&sd=true
















