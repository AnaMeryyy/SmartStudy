# SmartStudy
SmartStudy AI – Personalized Study Planner

Final project for the Building AI course

##Summary
SmartStudy AI is an intelligent study planner that helps students organize their study time efficiently by predicting workload difficulty and recommending optimized schedules based on past performance and deadlines. It uses machine learning to adapt to each student’s habits and improve productivity over time.

Building AI course project

Many students struggle with:
Poor time management and last-minute studying
Difficulty estimating how long tasks will take
Stress caused by overloaded schedules

This problem is very common among university students, especially in technical degrees like Computer Science.
My motivation is personal: I often find it difficult to balance multiple assignments, exams, and projects, and I want a system that helps reduce stress and improve planning.
This project is interesting because it combines AI with a real everyday problem affecting productivity and mental well-being.

How is it used?

The user inputs:
Subjects and assignments
Deadlines
Estimated difficulty (or past grades/time spent)

The system then:
Predicts time required for each task
Builds a personalized weekly study schedule
Updates recommendations based on user progress

It would be used mainly by students (university and high school), but also by professionals preparing certifications or exams.The app could be used on mobile or web, ideally checking daily recommendations.

Data and AI methods
Data sources:

User input data (tasks, deadlines, study time)
Optional historical academic performance data
Possibly anonymized datasets from student productivity studies

AI techniques:
Linear regression (predict study time per task)
Logistic regression (predict task difficulty: easy/medium/hard)
Clustering (group similar types of tasks or students)
Reinforcement learning (future improvement: adapt scheduling strategy)

Tools:
Python
scikit-learn
Pandas
Challenges

This project does not:
Guarantee perfect productivity results
Account for unexpected life events (illness, emergencies)
Fully understand human motivation or procrastination

Other challenges:
Data privacy (student performance data is sensitive)
Accuracy depends heavily on user honesty
Risk of over-reliance on AI for personal planning

Future improvements:
Add integration with Google Calendar or Notion
Build a mobile app version
Add AI chatbot for study coaching
Improve predictions using neural networks
Include group study planning features

With more data, the system could evolve into a full academic assistant.

Acknowledgments Inspired by:

Elements of AI course by University of Helsinki & Reaktor
OpenAI documentation and machine learning tutorials
General productivity tools like Notion and Google Calendar
