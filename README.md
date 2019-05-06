This app detects a face in an image that you supply by URL. It keeps track of the number of times you submit an image and provides this to you in the UI.

The app is secured by userid and password, and requires a quick registration process. Although the passwords are kept in a secure format unreadable to me or others, I recommend using a simple password just for this app.

The app is built using React.js, Express, postgreSQL and is hosted on Heroku. 
It utilizes the Clarifai API to perform facial recognition and then the app provides the outline. Currently it will only recognize a single face, but the app is being updated to recognize multiple faces.

Steps to use the app:
1) Register via the Register link (any email address can be used, there is no functionality to use the email address for anything other than a username)

2) Copy a URL to an image and submit it.

3) See the results

The URL for the app is: https://smart-brain-kc.herokuapp.com/

Thanks for giving it a try!

-Ken

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

