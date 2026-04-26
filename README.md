# AI Phishing Detection Lab

## Objective  
In this solo project, I built a phishing detection system using Python and machine learning to classify emails as either phishing or safe. The goal was to simulate how a SOC analyst would triage suspicious emails by automating detection, generating realistic attack data, and logging alerts for investigation. This project gave me hands-on experience with applied AI in cybersecurity, threat detection, and building end-to-end security pipelines.

---

## What I Did  

**Building a Machine Learning Detection Model**  
I developed a phishing detection model using TF-IDF vectorization and Logistic Regression. The model analyzes email content (sender, subject, and body) to determine whether an email is malicious or legitimate. The trained model is saved and reused for real-time analysis.

---

**Simulating Phishing Attacks**  
To replicate real-world attack scenarios, I created a script that generates realistic phishing and safe emails. These emails are automatically stored in an inbox directory and used as input for the detection system.

---

**Automated Email Analysis Pipeline**  
I built an analysis pipeline that processes incoming emails, extracts key features, and runs them through the trained model. The system outputs predictions and flags suspicious emails for review, similar to a SOC workflow.

---

**Real-Time Alerting and Logging**  
When phishing emails are detected, the system generates alerts and logs them to a file. This simulates how SIEM tools notify analysts of potential threats and maintain records for investigation.

---

**Testing the System in a Virtual Lab**  
I deployed and ran the entire system inside a Kali Linux virtual machine using VirtualBox. This provided a controlled environment to simulate attacker behavior and analyze detection results.

---

**Screenshot 1:** Click on the image to zoom in and view the details more clearly.  

![Virtual Machine Setup](VM.PNG)

---

**Running the Phishing Detection System**  
I executed the main script to analyze generated emails. The system correctly identified phishing emails and produced alerts based on suspicious senders and content patterns.

---

**Screenshot 2:** Click on the image to zoom in and view the details more clearly.  

![Detection Output](mainrun.PNG)

---

**Inspecting the Project Structure**  
I organized the project into modular components, including model training, feature extraction, analysis, logging, and attack simulation scripts.

---

**Screenshot 3:** Click on the image to zoom in and view the details more clearly.  

![Project Directory](folder.PNG)

---

**Reviewing the Detection Logic**  
I implemented detection logic that processes emails, classifies them, and triggers alerts for phishing attempts.

---

**Screenshot 4:** Click on the image to zoom in and view the details more clearly.  

![Analyzer Code](grep.PNG)

---

**Building the Machine Learning Model**  
The model uses TF-IDF vectorization and Logistic Regression to classify emails based on text patterns commonly found in phishing attacks.

---

**Screenshot 5:** Click on the image to zoom in and view the details more clearly.  

![Model Code](model.PNG)

---

**Training and Saving the Model**  
I trained the model on sample phishing and safe emails, then saved it as a reusable file for future predictions.

---

**Screenshot 6:** Click on the image to zoom in and view the details more clearly.  

![Model File](modelpkl.PNG)

---

**Working with Email Data**  
I created structured JSON email data to simulate real-world messages, including phishing scenarios like account suspension and safe workplace communications.

---

**Screenshot 7:** Click on the image to zoom in and view the details more clearly.  

![Email Data](dataemail.PNG)

---

## Skills Gained  
- Building machine learning models for cybersecurity applications  
- Detecting phishing and social engineering attacks  
- Creating automated security analysis pipelines  
- Simulating attacker behavior in a controlled lab  
- Logging and alerting for incident response workflows  
- Working with JSON data and feature extraction  
- Applying Python for real-world security problems  

---

## Tools Used  
- Python  
- Scikit-learn (TF-IDF, Logistic Regression)  
- Kali Linux (Virtual Machine)  
- Oracle VirtualBox  
- JSON for structured data handling  
