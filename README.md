# StudyNotion: EdTech Web App for Students and Instructors

StudyNotion is a versatile educational technology (EdTech) web application that caters to both students and instructors, providing a comprehensive platform for learning, collaboration, and instruction. With its intuitive interface and powerful features, StudyNotion aims to enhance the educational experience for all users involved.

## Tech Stack

  - ReactJS
  - NodeJS
  - ExpressJS
  - MongoDB
  - TailwindCSS
  - Cloudinary
  - Razor Pay



## Commands

All commands are run from the root of the project, from a terminal:
  - Clone the repository `git clone https://github.com/singhisking123/studynotion-edtech.git`.
  - Install Dependencies in server's folder `cd server` and `npm i`.
  - Install Dependencies for client do `npm i` in the root directory.
  - Run client at `localhost:3000` using `npm start`.
  - Run server at `localhost:4000` using `npm run dev`.

## Environment Variables 
  - For server (.env)
    ```
    JWT_SECRET="asdfasdfasdf"
    
    MONGODB_URL="Insert Mongodb URL here. Local or ATLAS"
    
    MAIL_HOST= Hostname of the mail server used for sending emails
    
    MAIL_USER= Username of the email account used for sending emails
    
    MAIL_PASS= Password of the email account used for sending emails
    
    RAZORPAY_KEY= Razorpay key
    RAZORPAY_SECRET= Razorpay secret
    
    CLOUD_NAME= 'Cloudinary name'
    API_KEY= 'Cloudinary api key' 
    API_SECRET= 'Cloudinary secret api' 
    
    
    FOLDER_NAME="CLOUDINARY_FOLDER_NAME"
  ```
      
