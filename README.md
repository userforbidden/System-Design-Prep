# System-Design-Prep

I use this space to learn on how System Design interview questions can be answered. How to ask questions to the Interviewers on the vague topics. 
How to ask clarifying questions. How to manage the 45-60mins interview very efficiently 

## Clarify the problem Statement 
1. What does daa analysis mean?
2. Who sends us data ?
3. Who uses results of this analysis?
4. What real-time really means? 

Two big reasons why you should ask clarifying questions
1. First reason is for interviewer -  he/she wants to undertand how the candidate deals with ambiguity  
2. Second reson is important to you - There are many solutions for the problem asked and only when we fully understand what features of the system we need to design we can come up with proper set of technologies the solution can be developed on 

## Why Requirements classification is so important

|Users/ Customers|Scale(read and werite)|performance|cost|
|--------------|---------|-------------|-------------|
|Who will use the system?|How many read queries per Second?|What is expected write-to-read data delay?|Should the design minimize the cost of development?
|How the system will be used?|How much data is queried per second?|What is expected p99 latency for read queries?|Should the design minimize the cost of maintenance?
||How many video views are processed per second?|
||Can there be spikes in traffic?