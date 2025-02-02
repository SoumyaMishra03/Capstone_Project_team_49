EXPLANATION OF APPROACH TO "DETECTION AND MITIGATION OF REPLAY ATTACKS IN CCTV CAMERAS USING AI" 

what is basically happening is that our AI which is embedded in an edge device(which is the local system; it is totally dependant on the system's performance). The AI uses GAN and ConvoLSTM to look for anomalies in the footage. 
There are three operations going to take place: 
> Incase there is a replay attack then the AI will throw an error that the footage has been replayed and needs to be troubleshooted. It also wont allow further storage of the footage in the cloud server(Microsoft azure).

The second operation is basically 
if the AI detects valid footage then it will breake the footage into different frames and then hash them which will be encrypted all is happening using the blockchain technology. Then the hashed frames are stored in
a secure cloud storage which is Azure cloud storage. 

