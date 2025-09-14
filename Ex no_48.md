# EX 48 C functions to perform all basic operations in Doubly Linked List.
## DATE:
## AIM:
To write a C functions to perform all basic operations in Doubly Linked List.

## Algorithm
1. Start.
2. Define a variables.
3. Write a function to search an element in the double linked list..
4. Read the value using scanf.
5. Ask the user to make an input.
6. Print out the answer.
7. End.

## Program:
```
/*
C functions to perform all basic operations in Doubly Linked List.

Developed by: SRINIVASAN V
RegisterNumber: 212222043008 
*/
```
```
struct Node 
{ 
struct Node *prev; 
struct Node *next; 
int data; 
}*head; 
 
void search(int data) 
{ 
struct Node *temp; 
int item=data,i=0,flag; 
temp=head; 
if(temp==NULL) 
{ 
printf("Empty list\n"); 
} 
else{ 
while(temp!=NULL) 
{ 
if(temp->data == item) 
{ 
printf("item %d found at location %d",item,i+1); 
flag=0; 
} 
i++; 
temp=temp->next; 
} 
if(flag!=0) 
{ 
printf("Item not found\n"); 
} 
} 
}
```

## Output:
<img width="928" height="820" alt="441361394-e1a2f71b-4dd1-4e50-ad5e-ea4e1b69f084" src="https://github.com/user-attachments/assets/3847180a-04e1-4381-a3d2-08887c730437" />




## Result:
Thus the program was executed and the output was verified successfully.
