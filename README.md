# Introduction
In universities, students have a lot to manage. They have complex degree
rules, many courses, and deadlines. The old academic platforms that schools
use are often just databases. They store information but do not help the
student plan. The student must do all the hard work of planning and finding
information. This can cause bad planning and make students take the wrong
courses.

Our project, ’Orbis’, offers a new way. It is an intelligent support system.
Our main goal is to build a platform that uses AI to act like a personal
advisor for each student. It is built to be an *assistant*, not just a database.
The main new idea in Orbis is its two AI features:

1. A Course Recommendation Engine: This is our primary use case.
This tool looks at a student’s old courses, their GPA, and the list of
all university courses. Then, it recommends the best courses for the
student to take next semester.

3. A RAG Assistant: This is an AI chatbot for students. We gave it all
the university’s documents (course catalog, rules, etc.). Students can
ask questions in normal language, like ”how many credits do I need to
graduate?” The chatbot finds the correct answer from the documents
and shows it.

The system also has a ”degree progress” page. This page shows the
student exactly which courses they finished and which ones they still need
to graduate. This report explains the full design of the Orbis system. We
will talk about the system architecture, the UI design, and the engineering
standards (like IEEE) we followed to make it a reliable and secure project.
