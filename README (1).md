A10
Infrastructure Bootcamp Assignment MERN Stack Blog App Deployment on AWS

Scenario: Blog App Deployment
Deploy a MERN stack blog application on AWS using free-tier eligible services. The backend (Express) will run on EC2, the frontend (React) will be hosted via S3 static website hosting, and MongoDB Atlas will be used as the database. Media uploads will be handled through another S3 bucket with appropriate IAM permissions.

Part1: 
A : S3 Bucket for Frontend
￼![PM2 Backend](https://github.com/shaima-Alrefaei/Repo10/blob/main/Screenshot%20of%20S3%20public%20URL%20loading%20index.html.png?raw=true )


B : curl -I output showing 200 OK

￼
![PM2 Backend](https://github.com/shaima-Alrefaei/Repo10/blob/main/curl%20-I%20output%20showing%20200%20OK.png?raw=true)



![PM2 Backend](https://github.com/shaima-Alrefaei/Repo10/blob/main/Online_server.png?raw=true)



Test uploading and retrieving a file

￼![PM2 Backend](https://github.com/shaima-Alrefaei/Repo10/blob/main/upload1.png?raw=true)

￼![PM2 Backend](https://github.com/shaima-Alrefaei/Repo10/blob/main/upload.png?raw=true)
￼

Part 2: IAM user and policy for S3 media bucket access
![PM2 Backend](https://github.com/shaima-Alrefaei/Repo10/blob/main/IAMUSER.png?raw=true)

￼

Part 3: EC2 Backend Setup

￼![PM2 Backend](https://github.com/shaima-Alrefaei/Repo10/blob/main/EC2%20Backend%20Setup.png?raw=true)


Screenshot of backend server running via pm2
￼![PM2 Backend](https://github.com/shaima-Alrefaei/Repo10/blob/main/Screenshot%20of%20backend%20server%20running%20via%20pm2.png?raw=true)


Screenshot of frontend s3 web page
￼![PM2 Backend](https://github.com/shaima-Alrefaei/Repo10/blob/main/Screenshot%20of%20S3%20public%20URL%20loading%20index.html.png?raw=true)

