# EX 49 C function to search an element in the doubly linked list.
## DATE:
## AIM:
To write a C function to search an element in the doubly linked list.

## Algorithm
1. Start.
2. Define a variables.
3. Write a function to search an element in the double linked list..
4. Read the value using scanf.
5. Ask the user to make an input.
6. Print out the answer.
7. End

## Program:
```
/*
C function to search an element in the doubly linked list.

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
 
 SAVEETHA ENGINEERING COLLEGE  
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
```


## Output:
<img width="670" height="595" alt="441362470-45caff34-3faa-42bf-a98a-295918b4e877" src="https://github.com/user-attachments/assets/89134c2c-c959-4d0e-b888-eee373905ddf" />





## Result:
Thus the program was executed and the output was verified successfully.
