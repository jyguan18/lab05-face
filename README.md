# lab06-proceduralFace

Link to my Shadertoy: [https://www.shadertoy.com/view/wXBfDV](https://www.shadertoy.com/view/wXBfDV)

And some images from my gingerbread man!

<img width="961" height="542" alt="image" src="https://github.com/user-attachments/assets/56445ea9-1f1a-4da4-85ce-87ff21763b1f" />
<img width="958" height="540" alt="image" src="https://github.com/user-attachments/assets/3ec0f89e-c658-4226-98db-41ee8a0d696c" />
<img width="953" height="542" alt="image" src="https://github.com/user-attachments/assets/d92263b8-dff4-4894-89fd-5baa69c657cc" />



## Setup
Start by forking [this shadertoy](https://www.shadertoy.com/view/XftyR8)

## Task 1
In the faceSDF function, add a new float parameter called SUPRISE a value between 0 and 1. Copying the way EYE_SEPARATION is used, modify the face such that the gingerbread face looks more or less surprised based on the value of SURPRISE. SURPRISE = 0 should be not very surprised, and SUPRISE = 1.0 should look very surprised. Note that the face shouldn't look broken for any value in that range!
Changing this parameter should change at least 3 geometic attributes of the face and more than one facial feature (just eyebrows are NOT SUFFICIENT).

![image](https://github.com/user-attachments/assets/76d63b1b-f3af-456a-8031-8b8da0abe125)

## Task 2
Your own parameter! Create a new attribute of your choice that maps to a procedural face characteristic in the domain of [0,1]. It SHOULD NOT be a literal attribute, eg. eye-separation or mouth size, but instead a more qualitative, subjective quality that you tie to specific geometic parameters using your design sense. Have fun!

## Extra Credit
In the faceSDF function, create a new float parameter called SADNESS. Follow the same guidelines as outlined in Task 1.
 
## Submission
- Create a pull request to this repository
- In the README, include the names of both your team members
- In the README, create a link to your shader toy solutions
- Make sure your shadertoy is set to UNLISTED or PUBLIC (so we can see them!)

