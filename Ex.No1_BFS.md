# Ex.No: 1  Implementation of Breadth First Search 
### DATE: 23.03.2024                                                                           
### REGISTER NUMBER : 212221040181
### AIM: 
To write a python program to implement Breadth first Search. 
### Algorithm:
1. Start the program
2. Create the graph by using adjacency list representation
3. Define a function bfs and take the set “visited” is empty and “queue” is empty
4. Search start with initial node and add the node to visited and queue.
5. For each neighbor node, check node is not in visited then add node to visited and queue list.
6.  Creating loop to print the visited node.
7.   Call the bfs function by passing arguments visited, graph and starting node.
8.   Stop the program.
### Program:
```
hypothesis (Patient, german_measles) :-

symptom (Patient, fever),

symptom (Patient, headache),

symptom (Patient, runny_nose),

symptom (Patient, rash).

hypothesis (Patient, flu) :-

symptom (Patient, fever),

symptom (Patient, headache),

symptom (Patient, body_ache),

symptom (Patient, conjunctivitis),

symptom (Patient, chills),

symptom (Patient, sore_throat),

symptom (Patient, runny_nose),

symptom (Patient, cough).

hypothesis (Patient, common_cold) :-

symptom (Patient, headache),

symptom (Patient, sneezing),

symptom (Patient, sore_throat).

hypothesis (Patient, chicken_pox) :-

symptom (Patient, fever),

symptom(Patient, chills),

symptom(Patient, body_ache),

symptom (Patient, rash).

hypothesis (Patient, measles) :-

symptom (Patient, cough),

symptom(Patient, sneezing),

symptom(Patient, runny_nose).

symptom(raju, headache).

symptom(raju, sneezing).

symptom(raju, sore_throat).
```












### Output:
![image](https://github.com/vishnupriya20052004/AI_Lab_2023-24/assets/133640291/53ff042a-30b5-49b2-9b2c-0b7756adbb98)




### Result:
Thus the breadth first search order was found sucessfully.
