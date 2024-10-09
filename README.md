# NASA Space Apps Challenge 2024 
## Landsat Reflectance Data: On the Fly and at Your Fingertips
### Challenge
Develop a web-based application that supports the comparison of ground-based observations with Landsat data by allowing users to define a target location, receive notifications when Landsat is to pass over that location, and then access and display the corresponding Landsat SR data.

This project also includes email notifications on the arrival times of teh satelites over specified areas, and alerts when the data is ready to view.
![image](https://github.com/user-attachments/assets/b979a6ef-5f97-4eca-a370-78d52f991864)

## Tech Stack
Frontend: React

Backend: Python

Email Service: Mailgun

Containerization: Docker

Deployment: Nginx

## Requirements
You will need a MapBox API key, which should be stored in a .env file to run the frontend.

## Running Locally
Navigate to the backend directory (timeAndData) and run the app:
```bash
python app.py
```

Navigate to the frontend directory, install dependencies, and start the development server:
```bash
npm install
npm run
```


![image](https://github.com/user-attachments/assets/ba37c220-86f1-483a-9c6a-53fa4f9efa15)
![image](https://github.com/user-attachments/assets/ec282940-70c2-49a6-ba2f-f7c76f930520)


