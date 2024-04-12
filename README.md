# TNSDC_Generative_AI

how to run my code:
There are 3 segement of code ,

A)if you want to check my prediction ,follow the follwing steps:
step 1:Set the Environment 
          *Interpreter python 3.11
          *Install cvzone , mediapipe ,numpy and tensorflow packages
step 2:run 'prediction.py'
step 3:check the predicted alphabet is I ,if true otherwise wrong output

B)if you want to put test image by own:
step 1: run "Test_data_Collection.py"
step 2: show the ASL(American Sign Language) symbol to webcam .Then press 's' once
step 3:Terminate the Program
step 4: goto test_img folder and rename image name like 'Image.jpg'
step 4: follow A steps

C) if you want to add more symbols 
step 1: open 'dataCollection.py' 
step 2:Change the new Symbol class name (12th line eq:data/#PRAVEEN ==> data/[your_class_name])
step 3:Save the file and run the "dataCollection.py"
step 4:show the new symbol to webcamera and press 's' for n times (freq: n>300 for good predictions)
step 5:Terminate the program
step 6:follow B and A steps
