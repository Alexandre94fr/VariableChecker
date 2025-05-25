# VariableChecker

## ➤ Creation context :
During several group game development projects on the Unity engine, I noticed that developers often forgot to validate critical serialized variables through the inspector or code. These oversights led to numerous runtime exceptions and bugs, often hard to track. 

_I have lost the count of the number of hours wasted debugging code just to realize that an object reference in a prefab that had nothing to do with the problem and was external to the prefab (and therefore not saved by Unity) was missing._

So to prevent this kind of problem from happening again, I have created the VariableChecker (a centralized tool that handles variable validation in a clean and extensible way).

I'm sharing this tool with you for free and open-source use.


## ➤ Description :
### ▸ What is VariableChecker ?

VariableChecker is a static Unity utility script that simplifies the process of verifying / checking the content of a variable in your game objects or even static scripts.

By using VariablesChecker.AreVariablesValid(...), you can:

- Log errors when variables' value are null, zero, or negative.
- Write cleaner Start/Awake methods with centralized error logging.
- Avoid repeating tedious if (x == null) code everywhere.
- Easily add your own generic checks if needed.

By using VariableChecker.AreVariablesValid(...), you can write safer, more maintainable, and faster variable checking, especially in collaborative projects.

No need to write and rewrite the same if statements for every class. Just plug and play.

**Here’s is a typical example of variables checks, with and without the VariableChecker :**

![VariableCheckerComparaison1](https://github.com/user-attachments/assets/a1d45565-5c95-4f08-9d10-6ac5fdb74b9b)
![VariableCheckerComparaison2](https://github.com/user-attachments/assets/cde0ad80-6d47-4b2d-8cd4-ca08f7781195)


## ➤ Utilization examples :

Here’s are typical examples of how to use the VariableChecker tool in a MonoBehaviour class :

**N°1 example (classic use) :**

Code :

![VariableCheckerUseExample1](https://github.com/user-attachments/assets/8636dd46-e6cf-4d4e-bbf8-be991c76c784)

Object :

![VariableCheckerUseExample2](https://github.com/user-attachments/assets/6460b870-4577-424d-844b-6a0564663f08)

Result :

![VariableCheckerUseExample3](https://github.com/user-attachments/assets/db940a17-f5e4-48e1-a36c-da1f2dbded9d)

**N°2 example (custom check use) :**

Code :

![VariableCheckerUseExample4](https://github.com/user-attachments/assets/46745bea-b005-4d5a-ae09-c7ab08e63d23)
![VariableCheckerUseExample5](https://github.com/user-attachments/assets/cf637d27-5533-4cee-ba94-30273a49565b)


Result :

![VariableCheckerUseExample6](https://github.com/user-attachments/assets/6a669115-819b-4564-8ecf-4126dfed1ea8)

**Note :** If you need more documentation check out the VariableChecker class.


## ➤ Installation :

In reality there is no need of downloading the projet, I made this tool compatible with the Unity's package manager.

In order to install the tool, follow this steps :

- Open the Unity's package manager

At the **top of the Unity application** you will see multiple dropdown, please **click on the 'Window'** one 

![image](https://github.com/user-attachments/assets/826603ad-3a94-437c-9e41-09537c40cf5a)

After that **click on the 'Package Manager' button**

![image](https://github.com/user-attachments/assets/bb4905eb-d86c-47dd-9da3-ef81e274f8b5)

- Add the package

Now that the Package Manager is open, click on the '+' dropdown

![image](https://github.com/user-attachments/assets/ab62972c-8340-4f3a-9b13-ce8ed35d1de1)

After that **click on the 'Add package from git URL...' button**

![image](https://github.com/user-attachments/assets/125918bd-e34d-41b5-96ee-49f6dcdb42e7)

Copy (Ctrl C) and paste (Ctrl V) the project link [ https://github.com/Alexandre94fr/VariableChecker.git ] into this :

![image](https://github.com/user-attachments/assets/1a486ff7-0708-4faf-9e59-4194044a2fa7)

And finally **press the 'Add' button**

![image](https://github.com/user-attachments/assets/c1e655a5-7b00-44b4-9c77-104036514461)

Good job, now you can use the VariableChecker, have fun ^^


## ➤ License :

As mentioned earlier, you're free to use VariableChecker in your projects. 

If you release a game using this tool, I’d appreciate a small credit, for example, as “External Technical Help”.

Thank you ! :D


## ➤ Credits :

### ▸ Programmers :
- [Alexandre RICHARD](https://github.com/Alexandre94fr)

### ▸ External assets
- No external assets used
