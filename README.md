# nexly-ai-saas-realtime-video-sharing

 Architecture:

 1) NextJS - For frontend of the application
 2) Clerk - Authentication
 3) Electron.JS - To allow users to record their desktop screen, as we do not want them to restrict to the web browser only. It is an open-source framework to develop desktop apps using the web technologies rendered using a version of the chrome browser and Node.js runtime env which will help us in building this native app.
 4) Express JS - a separate server for sockets listening for the data from the electron app.
 5) AWS (S3) / Microsoft Azure (Azure Blob Storage) - Real-time video file storage system.
 6) AWS Cloudfront / Azure CDN - for the streaming services and also to help get the data from the private S3 bucket.
