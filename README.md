# NFZ-Queue-Simulator
Data structures and algorithms project containing a set of operations on a priority queue. 

## Queue 
**Priority queue** is built out of patients which are waiting for their visit to a doctor. A single patient has: first name, surname, age, PESEL (something similar to Social Security Number), gender and time of his/her visit.

## Priority
Time of the visit is a deciding factor where in the queue we can find particular patient. You can set time of the visit as you sign up a patient or you can insert a patient at the specific position if the time gap is sufficient between patients. Patients are stored in a list sorted using _hipsort algorithm_ which updates the list after every patient is done with their visit.
