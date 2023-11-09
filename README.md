### ***Title*** : LAB14
### ***Aim*** : Linked List
### ***Algorithm*** : 

Linked List Node Structure:
Each item in the list is called a "node."
Each node has two parts: a "value" (which is the data we want to store) and a "pointer" (which points to the next node in the list).

Global Head Pointer:
We keep track of the first node using a special pointer called "head."
Initially, the list is empty, so the head is set to "nowhere" (nullptr).

Adding a Node at the Beginning:
Create a new node.
Put the desired value in the new node.
Make the new node point to the current first node.
Update the head to point to the new node.

Adding a Node at the End:
Create a new node.
Put the desired value in the new node.
If the list is empty, make the new node the head.
If the list is not empty, find the last node and make it point to the new node.

Deleting a Node from the Beginning:
Check if the list is empty. If it is, show an error message.
If the list is not empty, take note of the current first node.
Update the head to point to the next node.
Delete the node we noted earlier.

Deleting a Node from the End:
Check if the list is empty. If it is, show an error message.
If there's only one node, delete it and update the head to nullptr.
If there are more than one node, find the second-to-last node.
Make the second-to-last node point to nullptr.
Delete the last node.

Displaying the Linked List:
Start at the head.
Print the value of each node.
Move to the next node and repeat until reaching the end (nullptr).
Print "NULL" to indicate the end of the list.

Main Function and Menu:
Display a menu with options for the user.
Get the user's choice.
Perform the chosen operation using the functions described above.
Repeat until the user chooses to exit.

This algorithm provides a simple way to manage a linked list, allowing users to add and remove items at the beginning or end of the list and see the current state of the list.
### ***Explanation*** :

Imagine a linked list as a chain of containers, where each container holds something special. In our case, each container is a "node" that stores a number, and it has a pointer pointing to the next container in the chain.

Starting Point:

We have a special pointer called "head" that tells us where our chain of containers begins. At the beginning, it points to nothing (nullptr) because our chain is empty.

Adding a Number at the Beginning:
Imagine we have a new container.
We put our desired number in this new container.
We make the new container point to where the head is pointing.
We update the head to point to our new container.

Adding a Number at the End:
Imagine we have a new container.
We put our desired number in this new container.
If our chain is empty, we make the head point to our new container.
If our chain is not empty, we find the last container and make it point to our new container.

Removing a Number from the Beginning:
If our chain is empty, we say, "Sorry, there's nothing to remove."
If our chain is not empty, we look at the first container and remember it.
We update the head to point to the next container.
We say goodbye to the container we remembered.

Removing a Number from the End:
If our chain is empty, we say, "Sorry, there's nothing to remove."
If there's only one container, we remove it and update the head to nullptr.
If there's more than one container, we find the second-to-last container.
We make the second-to-last container point to nullptr, and we remove the last container.

Displaying the Numbers:
We start at the head and look inside each container.
We shout out the number we find.
We move to the next container and repeat until we reach the end, where we shout "NULL."

Main Function and Menu:
We show a menu with choices like "Add at the Beginning," "Add at the End," "Remove from the Beginning," "Remove from the End," "Display," and "Exit."
We ask the user to pick a choice.
Based on the choice, we perform the corresponding action (adding, removing, displaying).
We keep doing this until the user says, "I'm done" (chooses "Exit").

In a nutshell, our linked list is like a chain of containers, and we can add, remove, and see the numbers inside those containers based on what the user wants.

### ***Output Screenshot*** :

Code:

https://github.com/anikethmehta/LAB14/blob/main/code1.png

https://github.com/anikethmehta/LAB14/blob/main/code2.png

https://github.com/anikethmehta/LAB14/blob/main/code3.png

https://github.com/anikethmehta/LAB14/blob/main/code4.png

https://github.com/anikethmehta/LAB14/blob/main/code5.png

https://github.com/anikethmehta/LAB14/blob/main/code6.png
