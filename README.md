# MedPal Pro AI

Welcome to the Medpal Pro AI! 

Checkout MedPal Wiki page at https://github.com/HealthInnovators/medpal-pro/wiki

Almost 10 years ago, we built a Telehealth Application for patient engagement called Healthouts, we now want to make Healthouts AI enabled.

Paco Doc prototype was built to provide AI assistance to Doctors during an online consultation with making a diagnosis and generating a consultation report after the consultation using Large Language Models.

We would like to combine both the functionalities of Healthouts and Paco Doc AI features to rebrand it as MedPal Pro AI.

**About Healthouts**:

Healthouts is an online Healthcare Marketplace, enabling messaging capabilities with the best medical experts to receive trusted healthcare advice.

**Benefits for Health Consumers (patients)**:
Online health profile to maintain all their health information. Ask anonymous health questions for FREE. Find the best doctors based on the ranking, answering systems. Patients can schedule appointments Online. Patients can chat with the Doctors online. Patients can consume trusted health blogs. 24/7 availability from multiple devices and everywhere.

Benefits for Health Providers (Doctors, Nurse Practitioners, Physician Assistants):
Doctors can build their digital presence and improve their digital reputation Doctors can improve their digital presence by answering questions for free, these questions are made public without PHI and are fed into SEO to improve their digital presence and digital authority Doctors can improve their revenue by providing online consultations for first or second opinions. Doctors can manage their appointment bookings: Doctors can set their availability on their calendar. Doctors can communicate with other Doctors in the network to discuss clinical cases or transfer knowledge.

**Healthouts Features**

**Features for the Patients/End Users**:
===================

Patients/users can Login/Registrations using Single Sign-on using Social media platforms.
Patients/users can build their online health profile/medical records online.
Patients/users can book appointments with Doctors for online or offline consultation.
Patients/users can ask anonymous health questions for free.
Patients/users can make a payment via Email to the doctor.
Patients/users can find the most recommended Doctors from their social media connections on Healthouts.
Patients/users messaging capabilities are based on XMPP, web chat (Whatsapp).
Basic Android Patient app with registrations,booking appointments is ready.

**Features for the Doctor**:
===========

Doctors can manage their online profile along with their ratings and the free health questions answered by them.
Doctors can communicate with other Doctors and health providers in the network to discuss clinical cases.
Doctors can manage their online availability with the web/android mobile app.
Doctors can receive payments via Email.
Doctors messaging capabilities are based on XMPP, web chat (Whatsapp).

**Admin Panel for Hospital/Clinics**
============

Detailed list of all the free questions answered by all the Doctors
Detailed list of all the paid questions all in real-time.
Doctors email Campaigns delivered using Amazon SES.
Healthouts Technology Stack
Heathouts was architected for scalability using Amazon cloud computing services. Heathouts was built using Bootstrap, OpenFire Messaging Server, Java, Structs, Hibernates, Mysql, Amazon EC2, Amazon RDS, Amazon Route 53, Amazon SES.

**Healthouts Technology Stack**

Healthouts engagement marketplace technology solution was built using robust web technologies using the Java EE based Apache Struts 2 framework, which was an elegant, extensible framework for creating enterprise-ready Java web applications and Struts 2 is a pull-MVC framework. i.e. the data that is to be displayed to the user has to be pulled from the Action.

This web application uses various web technologies that are listed out below.

1.Front-end Technologies:

**Twitter Bootstrap 3.0**, HTML,JSP,CSS, javascript, jquery,json, Ajax.

Twitter Bootstrap 3.0 framework is used for developing responsive user interfaces. Bootstrap is a collection of tools to develop front end interfaces for web and mobile platforms.

2.Server Back-end Technologies:

**Struts 2.x, Hibernate**

Struts 2 framework is a java EE base abstract layer on servlets and JSPs and it is built as an MVC framework (model, view, controller), which is useful for large scale applications.
Hibernate was used to write persistent logic in applications.
Hibernate is java based ORM(Object Relation Model) framework, which is a very flexible framework for connecting any data bases without bothering to write SQL queries.

3. **Chat Component**:

Openfire server and Jabber based XMPP protocol.

Openfire is an instant messaging (IM) and group chat server that uses XMPP server written in Java and licensed under the Apache License 2.0. Currently we are using smack client library.
Extensible Messaging and Presence Protocol (XMPP​) is a communications protocol for message-oriented middleware based on XML.

4. **Database**:

The database is MySql.
Since we are using Hibernate, it does’t matter what database is used, however currently MySql is being deployed.

5. **Web Server**:

Apache Tomcat 7 Web server

6. **Payment Gateway**:

For national and international transaction working with Citrus Pay ​payment gateway API’s

7. **Hosting**:

Healthouts was hosted on AWS(Amazon Web Services) public cloud computing service.
Healthouts use AWS services like EC2, RDS, Email delivery, Route 53, S3 storage.
EC2: ​ Amazon Elastic Compute Cloud (Amazon EC2) provides scalable computing capacity, Virtual computers to host the app server.

Some of the features of EC2 are:

  - Virtual computing environments, known as instances.
  - Various configurations of CPU, memory, storage, and networking capacity for your instances, known as instance types
  - RDS: ​ Amazon Relational Database Service (or Amazon RDS​) is a distributed relational database service provide different type of relational database instances from cloud.
  - Route 53:​ This service provides scalable and highly available Domain Name System (DNS).
  - S3 Storage: ​S3​(Simple Storage​Service) is an online file storage ​web service, provides storage ​through web services interfaces
  - SES : Simple email Service, ​is the email service used internally for all triggers to communications.

8. Version control system :

GitHub ​ is used as an online repository to manage Healthouts application files and versioning
Git is a local repository to manage the code and communicate with remote repository.

9. Application Scalability:

Healthouts at present is built for scalability using the Amazon cloud computing services, however depending on the requirement for estimated growth figures, system will be scaled in hours after evaluating the cost requirements.

The only current limitation for scalability are the Openfire concurrent chat connections.

10. Social networking API’s:

Working with Facebook, Twitter, Google+ API’s
​These API’s allows application to use the social connections and profile information to make application more involving and publish activities on Facebook, Twitter, Google+.

**AI Digital Assistants for Doctors**

PaCo Doc is an AI Digital assistant for Doctors & Patients (just like Github co-pilot for programmers). PaCo Doc helps Doctors during a Telehealth consultation. It helps the Doctor come up with the diagnosis of the patient, it assists the Doctor in what questions to ask next and summarizes the medical consultation that includes clinical notes, medications and lab tests. 

PaCo Doc is built using GPT4 and Lang chain, it is primarily built for assisting Doctors during a live telehealth consult. PaCo Doc has a dashboard with many web frames and helps Doctors during live telehealth consult. 

PaCo Doc mainly uses **speech-to-text** aduio capture functionality. 

Below are some links to our product:

Contanarized repo - https://github.com/yyu233/doctor-ai/tree/test/yyz/dockerize_app
Youtube Video of Paco Doc prototype- https://youtu.be/XffCdV6OOns
We would like to build a product like this - https://www.youtube.com/watch?v=mbiAp7P8thI&t=0s 

PaCo Doc web UI has four web frames:

1. Patient Diagnosis - PaCo Doc acts as a clinical decision support system for the Doctor and helps with coming up with differential diagnoses that are derived from the live doctor/patient interaction. We listen in on the doctor/patient conversation and do inference at the same time in real-time.
2.Suggested Questions - It suggests and helps the Doctor to ask any questions they have missed to ask the patient.
3. Doctor consultation notes - Includes the summary of the Diagnosis, medications prescribed and lab tests ordered.
4. Your conversation - Displays the raw conversation in real-time and supports multiple languages. Real-time audio inference to identify whether it was a doctor or a patient speaking, we perform speech to text in real-time.

Features of PaCo Doc:

Real-time clinical decision support: For technology to be assistive in diagnosis, we need to have it be part of the diagnosis process so we had to figure out how do we listen in on the doctor/patient conversation and do inference at the same time? Also, output the results fast enough that they're useful to the doctor that they can glance at easily. There was audio editing, prompt engineering so that we could run 
parallel models. One model giving differential diagnosis, the other model providing suggested questions to ask. Real-time audio inference to identify whether it was a doctor or a patient speaking, audio to text how high quality it was so that was more on the real time

Techstack for Doctor UI (Doctor digital assistant)

1. Langchain framework - https://python.langchain.com/docs/get_started/introduction.html
2. GPT4 - https://openai.com/blog/gpt-4-api-general-availability
3. Whisper - Speech to text (listens to Raw transcripts and then creates a clinical note) - https://openai.com/research/whisper
4. Google text to speech includes language translation - https://cloud.google.com/text-to-speech
5. Front-end is build using https://svelte.dev/
6. Back-end to front-end connection is via https://socket.io/ (This is where we are having a problem. The socket protocol has a server and a web agent. The server is generating data but the web agent is not displaying the data on the front-end. The data being transmitted is JSON)
7. Prompt engineering: Doctor assistant has four prompt engineering models in the following areas
 - Patient Diagnosis: Differential diagnosis model via prompt engineering. We have used GPT to help write the prompt. The prompt for the differential diagnosis used is this: Based on the provided transcript snippets from a doctor patient consultation and considering the stated symptoms and medical history, parse the information to generate a differential diagnosis and list it all out with confidence scores.
 - Suggested Questions: Suggested question model via prompt engineering. We have used GPT to help write the prompt. The prompt for the suggested questions used is this: Based on the provided transcript snippets from a doctor patient consultation and considering the stated symptoms and medical history, parse the information to generate a list of next questions to ask. While the suggested question model is running, we are keeping the differential diagnosis silent and then it's suggesting questions based on the silent differential diagnosis. We are using Chain of Thought prompting without actually displaying the Chain of thought and then having the questions suggested by the model.
 - Doctor consultation notes: Takes the raw transcript plus any hints or notes from the doctor and then creates a full note
 - Your conversation: Speech to text model that is transcribing 
 
Patient UI (Patient digital assistant) 

For the patient UI, we constrained the model to the use case that we needed it to fulfill which was to answer follow-up questions about the interaction with the doctor and about the prescription via prompt engineering. We restricted the prompt model to only answer questions about the medications, the tests, the prescription, the transcript that was fed into the prompt and if any question was asked outside of that domain we instructed the model to defer answering it or sent for triage or to book a follow-up consultation with a doctor or maybe flag it for a nurse or patient care coordinator to pick up the ticket. Another Guard railing we thought of using are adversarial dialogue based agents (GAN) that compete with each other to make sure the answer provided to the patient is correct (This feature has not been implemented in this code).

Steps to Run the model

In the terminal, you type "npm run dev", after you go into the front-end directory
You create another terminal and run "python main.py" after you go into the root directory

**What We're Building**

MedPal AI is envisioned as a comprehensive telehealth platform with features like:
Real-time clinical decision support for healthcare professionals.
Speech-to-text technology for capturing consultation details.
AI-powered analysis of consultations to:
 - Suggest questions for the healthcare professional.
 - Assist in diagnosing patient problems.
 - Recommend potential lab tests.
 - Recommend possible medications (after confirmed diagnosis).
 - Report generation with key takeaways from the consultation.

**Current Focus Areas**

We are currently focusing on open-sourcing the following components:

Speech-to-Text Module: We're exploring open-source speech-to-text libraries and tools to ensure accurate capturing of consultations.
AI Assistant for Diagnosis Support: We're investigating open-source large language models (LLMs) and fine-tuning them for the healthcare domain, adhering to data privacy regulations.
Clinical Question Prompt Library: We're building a collection of open-source question prompts to guide healthcare professionals during consultations.

**How You Can Get Involved**

We welcome contributions from developers, data scientists, healthcare professionals, and anyone passionate about improving healthcare access. Here's how you can participate:

Contribute code: Fork our repositories, make improvements, and submit pull requests.
Join the discussion: Engage in our online forum (https://discord.gg/eVKVcneU) to discuss ideas, ask questions, and collaborate.

Help us document: Improve our documentation to make it easier for others to contribute.
Spread the word: Share our project with others who might be interested in getting involved.
