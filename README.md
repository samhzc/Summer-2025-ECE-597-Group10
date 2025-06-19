# Summer-2025-ECE-597-Group10
**UVIC MTIS Capstone Project**
Dataset:
https://www.kaggle.com/datasets/wcukierski/enron-email-dataset

**Project Design and Development**

The project aims to design and implement a Machine Learning (ML) model to detect abnormal emails, whether due to phishing, spamming, etc. The problem is framed as a binary classification issue. You should follow these general guidelines for designing any classification model:

**Literature Review and Learning Phase**

Study existing research on email-based phishing detection. Discuss the challenges and strategies in detecting abnormalities through email characteristics.

**Data Understanding**

Initially explore the email dataset, understanding its structure and typical features found in emails (e.g., subject line, sender information, body text).

**Data Preprocessing and Feature Engineering**

Employ techniques for preprocessing email data, such as tokenization, removing stop words, and handling HTML content. Introduce feature engineering specific to emails, such as extracting header information, hyperlinks, and stylistic features. Prepare using bag-of-words or similar approaches.

**Machine Learning Training and Implementation**

Train using traditional ML techniques on text data, utilizing the features extracted from the above step, like Naive Bayes, Logistic Regression, and Random Forest. Since it is a binary classification problem, you need to use the AUC, confusion matrix, and the balanced accuracy for assessment and model selection. You need to report all of them and get insights from all of them.

**Model Optimization and Validation**

Apply techniques to optimize ML models to handle imbalanced data, which is common in phishing detection. Use validation strategies, including cross-validation and employing a hold-out test set specifically designed to evaluate email classification.

**More Advanced Features: Embeddings**

Redesign your ML model (including all the above steps) using embeddings, which transform email text into dense vector representations, capturing subtle semantic meanings. This advanced feature set enhances your machine learning models, improving their ability to distinguish between normal and phishing emails.

**General Guidelines**

This section provides general guidelines for the project and some logistics, including documentation, software and tools, weekly meetings, and grading policy.

**Documentation**

All your work should be very well documented using three main methods, all of which will constitute part of the grade:

**GitHub**

Each group should create their GitHub repository, to which they continuously push their code, comments, issues, etc. All group members should be on the repo. The repo name should be: *Summer-2025-ECE-597-GroupX*, where X is the group number: 1, 2, ...10. Please, each group should add me to your repo so I can follow your progress. My GitHub account is: https://github.com/RihamAlTawy

 

**Technical Report**

Each group should compose a technical report that will be submitted by the end of the project and should contain all necessary information on the project, with the appropriate technical report structure: abstract, introduction, literature review, methods, experiments and results, and conclusion.

**Presentation**

Each group prepares a presentation, which is essentially the slide version of the technical report. This means writing should be minimal, and presentation materials such as figures and tables should be emphasized.

**Software and Tools**

You can use any software, any programming language (although Python and its ML libraries are highly recommended), and any tools. You are more than welcome to use LLMs, e.g., ChatGPT 4.0, to help generate code. However, you are 100% responsible for understanding every single character in your model and code. You should be able to answer any questions about your deliverables.

**Meetings**

In addition to following your weekly progress on GitHub, I need to meet with each group biweekly starting tomorrow for a maximum of 10 minutes for verbal follow-up and discussion. The meetings will be through my official Zoom room, on Tuesdays starting from 3:30 pm, with each group scheduled as Group 1 at 3:30 pm, Group 2 at 3:40 pm, Group 3 at 3:50pm, and so on) 

 

Topic: Riham AlTawy's Personal Meeting Room

Join Zoom Meeting

https://uvic.zoom.us/j/3094740732?pwd=Q05zRjBUcEZwaWdjZDdXaTZnQkJNZz09

Meeting ID: 309 474 0732

Password: 865836

 

Grading Policy
The grade will be split as follows: 60% on the progressive GitHub contributions and weekly meetings, 20% on the report, and 20% on the final presentation. For MTIS students, ECE597 is a pass/fail course, there is no grade for it. The assessment weights are to highlight how passing the course will be determined. For instance, you need to have Git contributions and show up in meetings in order to get the full 20% for the report and 20% in the presentation, and pass the course. Similarly, for MADS students, the weights for report and presentation also rely on your activities (Git contributions and meetings) in the project. In other words, 60% of your report and presentation grade can be secured by contributing with your team.
