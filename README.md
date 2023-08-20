# Cat-Dog-Classification  project 


## How to Run the application in local system

1. conda create -n catdog python=3.7 -y
2. conda activate catdog
3. pip install -r requirements.txt
4. python app.py
5. open in browser: http://localhost:8080/

# Point to note while coding the app.py
 Host and Port number not required in app.py.



# Steps for Azure Deployment


## Step 1: Go to Azure Portal and click on Create a Resource
![image](https://github.com/ravi0dubey/Cat-Dog-Classification-Azure-main/assets/38419795/37ab5ec7-cbc7-4b73-b9fb-45b91c4b9cb4)

## Step 2 : Select Web-App
![image](https://github.com/ravi0dubey/Cat-Dog-Classification-Azure-main/assets/38419795/faf9edf9-d21f-4932-9b74-178d56e98abe)

## Step 3: Create a Web-app by first selecting resource-group and then giving app name = "cat-dog"

![image](https://github.com/ravi0dubey/Cat-Dog-Classification-Azure-main/assets/38419795/b2c3783f-6945-4417-8137-8f6c608466c9)

## Step 4: Click on Create 

![image](https://github.com/ravi0dubey/Cat-Dog-Classification-Azure-main/assets/38419795/736e9a3f-64f7-4454-a6f3-d9cf83baa432)

## Step 5: Once Deployment is complete click on Go to resource

![image](https://github.com/ravi0dubey/Cat-Dog-Classification-Azure-main/assets/38419795/0d33dd64-6d56-4299-88fd-29353babe30b)

## Step 6: In resource section click on Deployment Centre. There select Source = "Github" and the Authorize Github
![image](https://github.com/ravi0dubey/Cat-Dog-Classification-Azure-main/assets/38419795/68fe7392-6a3e-462a-93bc-0576d2d59854)

## Step 7: After authorization enter github repository and branch name
![image](https://github.com/ravi0dubey/Cat-Dog-Classification-Azure-main/assets/38419795/ba3bbebb-9b4b-4e20-8113-97e3817247f7)

## Step 8: Click Preview and then save at the top.

On the Bell icon one message will be flashing, click on it which says "Deployment Succeeded".

![image](https://github.com/ravi0dubey/Cat-Dog-Classification-Azure-main/assets/38419795/00e7cf59-25a7-4199-9bbd-d77083024eeb)

## Step 9: In Github repository. Github/workflows folder will get added
![image](https://github.com/ravi0dubey/Cat-Dog-Classification-Azure-main/assets/38419795/59546976-d57c-4723-bc55-51521341deb7)

## Step 10 : At same time deployment to Azure will get triggered and it will get deployed to Azure Portal
![image](https://github.com/ravi0dubey/Cat-Dog-Classification-Azure-main/assets/38419795/6971ae57-ee93-43a0-b106-1fef4068964e)

## Step 11: Refresh Azure Portal. Click on Default Domain icon to browse the deployed project on web
![image](https://github.com/ravi0dubey/Cat-Dog-Classification-Azure-main/assets/38419795/e26b94ce-edc8-48ce-9167-dc6114275bfb)

## Do the Prediction
![image](https://github.com/ravi0dubey/Cat-Dog-Classification-Azure-main/assets/38419795/ae44302f-d0c6-4366-8342-c7640530f05c)



