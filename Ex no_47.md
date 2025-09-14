# EX 47 C function to insert a node in a linked list.
## DATE:
## AIM:
To write a C function to insert a node in a linked list.

## Algorithm
1. Start.
2. Define a variables.
3. Write a function to insert a node in a linked list.
4. Read the value using scanf.
5. Ask the user to make an input.
6. Print out the answer.
7. End

## Program:
```
/*
C function to insert a node in a linked list.

Developed by: SRINIVASAN V
RegisterNumber: 212222043008
*/
```
```
struct Node{ 
char data; 
struct Node *next; 
}*head; 
 
 
void insert(char data) 
{ 
struct Node *n=(struct Node*)malloc(sizeof(struct Node)); 
struct Node*temp; 
if(head==NULL) 
{ 
head=n; 
n->data=data; 
n->next=NULL; 
temp=head; 
return; 
} 
 
}  
else 
{ 
while(temp->next!=NULL) 
{ 
temp=temp->next; 
} 
n->next=NULL; 
n->data=data; 
temp->next=n; 
} 
}
```


## Output:

<img width="530" height="669" alt="441360120-79377a3c-5c8a-4cae-a24e-2b08f4099894" src="https://github.com/user-attachments/assets/ac1b7095-76cb-4e47-b99b-5374c7e62db5" />


## Result:
Thus the program was executed and the output was verified successfully.
