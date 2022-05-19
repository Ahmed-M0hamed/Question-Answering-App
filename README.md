# Question Answering App 
this app answer a question given a context 
I tested the app on passage about adolf hitler and the answers were really good 

-------------------------------------------

## who the app work 
- we used react to build the ui 
- we used fast api for the backend server 
- we used pretrained hugging face model to do inference  

-------------------------------------------------------

## how you can run the app 
- clone the repo 
```bash 
git clone repo 
cd repo 
``` 
- move to the frontend and install the dependencies 
- run the app 
```bash 
cd frontend
npm install 
npm start
``` 
- move to backend 
- start the server it may take a while first time because the hugging face model has to be loaded 
```bash 
cd backend 
uvicorn main:app --reload 
``` 
- open the browser and enjoy 