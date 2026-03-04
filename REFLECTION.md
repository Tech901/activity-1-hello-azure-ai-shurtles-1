# Reflection -- Hello, Azure AI

Answer these questions after completing the activity (2-3 sentences each). Connect your answers to specific things you observed while coding and experimenting.

## 1. Service Surprises

Which of the three Azure AI services (OpenAI, Content Safety, Language) surprised you the most? Connect this to something specific you observed during your experiments -- a response you didn't expect, a behavior that seemed too easy or too hard, or a result that made you rethink how the service works.  Language because it gave me about twelve hours worth of errors due to my list returning the result of NONE.

## 2. Lazy Initialization

How would you explain the lazy initialization pattern to a colleague? Why is it used instead of creating clients at the top of the file?   Processes are used as needed and not all at once, I believe.

## 3. Content Safety in the Real World

A resident files this complaint: *"A man was assaulted at this intersection because the street light has been out for months."* This text describes real violence but is a legitimate safety concern. Should the system block it, flag it for human review, or pass it through? What factors would you weigh in making that decision?  I would assume it would be flagged for human review because of the word assaulted.
