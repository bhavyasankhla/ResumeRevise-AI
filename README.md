

# CV Improver using Machine Learning
Hello :smiley: thank you for being here!

This is a Python project that will help you improving the CV using Artificial Intelligence. 
In particular, we will use the ChatGPT API to improve the __summary__ of  your CV and the AI will also review your work experience, making it more appealing for recruiters!

This project has two important applications. 
Let's  describe them

## 1. Application script

The application script uses the __streamlit__, that is an open-source app framework for Machine Learning and Data Science. 
In order to run it, once you download the folder and the ```pip install requirements.txt``` file, you have to change the ```constants.py``` file and change it with the Open AI API key †. (Unfortunately, OpenAI blocks your keys when they are shared online, so mine wont work and you have to put yours).

† If you do not have an Open AI API key, please follow the [Open AI blogpost](https://openai.com/blog/openai-api/).

Once that you have followed the procedure, what you'd have to do is to run the app using:

```streamlit run app.py```

and follow the procedure that the app will ask you. The app will provide you with a ```cv_template.txt``` file. Download it, fill it up with all your details. You can add __Experiences__, update the __summary__, delete __experiences__. 

The app will provide the details of everything that is happening, the summary and the work experience proposal will be printed and the result will be given in terms of a downloadable file that you can easily download with a button. :rocket:

## 2. main.py script

The application script uses the __streamlit__, that is an open-source app framework for Machine Learning and Data Science. 
In order to run it, once you download the folder and the ```pip install requirements.txt``` file, you have to change the ```constants.py``` file and change it with the Open AI API key †. (Unfortunately, OpenAI blocks your keys when they are shared online, so mine wont work and you have to put yours).

† If you do not have an Open AI API key, please follow the [Open AI blogpost](https://openai.com/blog/openai-api/).

Once that you have followed the procedure, what you'd have to do is to run the app using:

```python main.py```

In this file, change the 'cv_example.txt' file with the file that you want to be analyzed. Look for this line:

```uploaded_file = open('cv_example.txt','r')```

This script is less "user friendly", but very efficient. It doesn't print anything but it outputs a "cv_reviewed.txt" file that is the file with the proposal change in the summary and work experiences. 

## 3. Examples

__Input EXPERIENCES:__ 

_EXPERIENCE 1:_

Software Engineer [SEP]
WorkSafeBC [SEP]
<2023/05-2023/12>[SEP]
Enhanced the accuracy of BERT Machine Learning (ML) model by leveraging OpenAI GPT-4 LLM
 Automated deduplication of daily scraped news by utilizing text embeddings in a vector database.
 Created ChatGPT powered private documents chatbot using LangChain with Pinecone vector DB
 Developed Natural Language to SQL query Python app using OpenAI ChatCompletion API
 Designed and developed Enterprise Signals Mining app using Python and Flutter to summarize PDF documents, assign relevant topics using OpenAI Assistant API and Chain of Thought prompt[SEP]


_EXPERIENCE 2:_

Senior Member of Technical Staff [SEP]
Oracle[SEP]
<2020/06-2022/09>[SEP]
Engineered an Enterprise Analytics Data Pipeline to analyze user behavior by processing Oracle
Analytics Cloud (OAC) user events, resulting in dashboard metrics that offer valuable insights into
Daily Active Users (DAU), Monthly Active Users (MAU), and overall user adoption.
Collaborated with leadership in system design discussions, contributing to the implementation of a
distributed data pipeline for processing Oracle Analytics Cloud application logs.
Orchestrated the design of the data collector microservice using Java 8 and the Spring Boot,
specializing in extracting, transforming events, and loading data into the data warehouse. (ETL)
Designed and Developed the Task Manager microservice to orchestrate cloud-deployed
components, including the data-collector and data-processor.
 Developed Global Collector microservice for Cloud Product Analytics (CP360) which uses the Boomerang JS library to monitor end-user performance by capturing client-side metrics.
 
 Implemented Spark Dataflow to collect data from Oracle Fusion in distributed data pipeline.
Successfully lead the effort to move all Spring Boot microservices to dedicated Docker images.
Spearheaded the integration of Oracle Key Management Service (KMS) to enhance security
measures, effectively managing user credentials within the application.[SEP]


_EXPERIENCE 3:_

Member of Technical Staff[SEP]
Oracle[SEP]
<2018/05-2020/06>[SEP]
Developed Fusion Analytics Warehouse (FAW), which includes backend development on Java 8
SpringBoot framework, front-end development for FAW UI on Oracle JET (UI framework).
Implemented a Machine Learning driven SLA auditor which predicts the runtime of ETL jobs and
compares them against SLA, to send out notifications ahead of time.
Built model on Python (Pandas, NumPy, fbprohpet, catboost) which auto trains daily with the
pipeline data to notify for jobs which are running beyond expected time and are expected to fail.
Implemented Apache Kafka to receive events from
BoomerangJS
and store it in a messaging queue.
Implemented Quartz Scheduler to schedule and manage ETL activation plan job runs.
Developed Job Management Console using SpringBoot and Oracle JET that for DevOps to manage
Data Warehouse ETL jobs[SEP]



*** 
__AI Improved EXPERIENCES:__

_EXPERIENCE 1:_


Software Engineer
WorkSafeBC | May 2023 - December 2023

Contributions to Machine Learning and Automation:

Elevated the accuracy of the BERT Machine Learning (ML) model by incorporating the capabilities of OpenAI GPT-4 LLM, showcasing a commitment to cutting-edge technologies.
Text Data Processing and Deduplication:

Automated the deduplication process of daily scraped news through the implementation of text embeddings in a vector database, streamlining information processing and improving data accuracy.
Innovative Chatbot Development:

Spearheaded the creation of a private documents chatbot powered by ChatGPT, utilizing the LangChain platform and Pinecone vector database. This initiative enhanced document retrieval and accessibility through natural language interactions.
Natural Language to SQL Query Application:

Developed a Python application for converting Natural Language queries into SQL queries using the OpenAI ChatCompletion API, contributing to more intuitive and user-friendly data querying.
Enterprise Signals Mining Application:

Designed and implemented an Enterprise Signals Mining application using Python and Flutter. This application efficiently summarizes PDF documents and assigns relevant topics by leveraging the OpenAI Assistant API and Chain of Thought prompts. This innovation enhances information extraction and knowledge discovery within large document sets.
These experiences underscore my proficiency in leveraging state-of-the-art technologies, my commitment to enhancing efficiency through automation, and my ability to design and implement innovative solutions in both machine learning and application development domains.

_EXPERIENCE 2:_


I engineered an Enterprise Analytics Data Pipeline to analyze user behavior by processing Oracle Analytics Cloud (OAC) user events, resulting in dashboard metrics that offer valuable insights into Daily Active Users (DAU), Monthly Active Users (MAU), and overall user adoption. I collaborated with leadership in system design discussions, contributing to the implementation of a distributed data pipeline for processing Oracle Analytics Cloud application logs. I orchestrated the design of the data collector microservice using Java 8 and the Spring Boot, specializing in extracting, transforming events, and loading data into the data warehouse (ETL). Additionally, I designed and developed the Task Manager microservice to orchestrate cloud-deployed components, including the data-collector and data-processor. To further enhance the application, I developed a Global Collector microservice for Cloud Product Analytics (CP360) which uses the Boomerang JS library to monitor end-user performance by capturing client-side metrics. 

_EXPERIENCE 3:_



Member of Technical Staff
Oracle | May 2018 - June 2020

Contributions to Fusion Analytics Warehouse (FAW):

Spearheaded the development of Fusion Analytics Warehouse (FAW), showcasing proficiency in Java 8 and the SpringBoot framework for backend development.
Designed and implemented the FAW User Interface (UI) using Oracle JET, a robust UI framework.
Machine Learning-Driven SLA Auditor:

Innovated a Machine Learning-driven SLA auditor capable of predicting ETL job runtimes and comparing them against Service Level Agreements (SLA), ensuring proactive notifications.
Engineered a Python-based model leveraging Pandas, NumPy, fbprophet, and catboost, which automatically trains daily with pipeline data to identify jobs running beyond expected durations, anticipating potential failures.
Integration with Apache Kafka and Quartz Scheduler:

Successfully integrated Apache Kafka to receive events from BoomerangJS, storing them in a messaging queue for streamlined data processing.
Implemented Quartz Scheduler to schedule and manage ETL activation plan job runs, ensuring efficient and timely execution.
Job Management Console for DevOps:

Developed a Job Management Console using SpringBoot and Oracle JET, empowering DevOps teams to efficiently manage Data Warehouse ETL jobs.
The console provides a user-friendly interface for scheduling, monitoring, and troubleshooting ETL job executions, contributing to enhanced overall workflow efficiency.
These experiences highlight my ability to contribute to the full software development life cycle, from conceptualization and design to implementation and maintenance, while leveraging diverse technologies and frameworks.



***

### Contacts!

Thank you so much for reading this! If you want to stay in touch add me on 

* [Linkedin](https://www.linkedin.com/in/bhavya-sankhla-b4ab5b88/)

