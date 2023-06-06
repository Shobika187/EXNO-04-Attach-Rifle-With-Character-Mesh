# EXNO-04-Attach-Rifle-With-Character-Mesh
```
Devlepoed by : Shobika P
Register No : 212221230096
```
## Aim:
To Attach Rifle with character mesh and implementation bullet spawn from Rifle.
## Procedure:
### Step1: 
Import the character mesh that you chose and the suitable gun mesh.Ensure all the files are imported correctly.
### Step2: 
Create action events to trigger them by pressing the respective key.
![image](https://github.com/Shobika187/EXNO-04-Attach-Rifle-With-Character-Mesh/assets/94508142/68a55cdf-c6ac-42ff-b136-48a1106cc66b)
### Step3: 
Open the SKELETAL MESH of the imported character and direct yourself to the skeleton tree. Here we have to create socket at the spinal and in right hand part of the skeleton tree.
### Step4:
Attach the rifle model to the character's attachment point using the appropriate parenting or socketing mechanism provided by your game engine. This will ensure that the rifle follows the character's movements and animations correctly.
### Step5:
After this we have to create a bullet actor, gunactor and specify the direction of the bullet to launch. In event graph make required connection so that the bullet launches correctly.
### Step6: 
In event graph create connection for the gun spawn so that when we click the triggering key and the gun gets spawned to hand.
![image](https://github.com/Shobika187/EXNO-04-Attach-Rifle-With-Character-Mesh/assets/94508142/64efcd80-d858-44d5-99e9-0a14251f6bd4)
### Step7:
Now create an event to trigger bullet fire and make appropriate connections so that when key is pressed, the bullet launches. Correct the initial and final velocity of the bullet before compiling.
![image](https://github.com/Shobika187/EXNO-04-Attach-Rifle-With-Character-Mesh/assets/94508142/976858fe-4939-41fd-9045-5512af4a6286)
### Step8: 
Adjust the velocity of the bullet in ullet actor and make sure all the connections are correctly made.
### Step9: 
Additionally make sure that when the gun is spawned to spinalcord the bullet fire option should be disabled.
## Output:
### GUN ATTACHED TO CHARACTER:
![p36](https://github.com/Shobika187/EXNO-04-Attach-Rifle-With-Character-Mesh/assets/94508142/044e45c1-54f5-4b87-9220-1e91533d7dd9)
### GUN EQUIP:

![p34](https://github.com/Shobika187/EXNO-04-Attach-Rifle-With-Character-Mesh/assets/94508142/f93a442c-c332-47df-9af5-8ca71e84358d)
### BULLTE FIRE:
![p55](https://github.com/Shobika187/EXNO-04-Attach-Rifle-With-Character-Mesh/assets/94508142/21909e4c-dd91-4f35-9ff1-7f98f6b71be2)
![p51](https://github.com/Shobika187/EXNO-04-Attach-Rifle-With-Character-Mesh/assets/94508142/249cb12e-5476-411b-8df7-7b1c69ec608d)
## Result:
By following the above mentiioned steps we can successfully attach the riffle to the character and fire the bullet when triggering their respective buttons.

