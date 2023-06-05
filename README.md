# FilmEnclave

**Main features in our application Login/Signup, Upload, Thumbnail, Like/Dislike, Comment/ Reply, Subscribe, Side Video.**

**Login/Signup:** The user can register and then login for uploading their own videos. This helps in maintaining the identity of the users and creators.

**Upload:** This includes the title and description of the video. It helps the creator in making the video more interactive by selecting the best suitable title and description in order to double the views on the video.

**Thumbnail:** User can select a particular image or snapshot of the video to display on the viewing screen.

**Like/Dislike:** Users can like or dislike a particular video. This helps in increasing interaction between the video uploader and the viewer. 

**Comment/Reply:** User can comment on the video and other users can reply on the same comments. It helps the viewers to provide their reviews for the video.

**Subscribe:** User can subscribe for instant updates of the new videos.

**Side Video:** A different section on the screen where the user can see other related videos from the video that is being watched.



<!-- ------------------------------------------------------------------------------------------------------------------------------------------------------------- -->
## Usage
Create .env file in the server folder and add the following environment variables:
```
# MONGO = 
# JWT = 
# PORT = 3001
```
Create .env file in the client folder and add the following environment variables, values can be found from firebase project setup
```
# REACT_APP_FIREBASE_KEY = 
# GENERATE_SOURCEMAP=false
```
### Install dependencies
```
# Backend deps
cd server
npm install
# client deps
cd client
npm install
```
### Run Server
```
# Backend Server (Local)
cd server
npm start

# client Server (Local)
cd client
npm start
```

you need to setup new project in firebase and enable storage and signin with google option

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- ------------------------------------------------------------------------------------------------------------------------------------------------------------- -->
