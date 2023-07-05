# Song Recommendation App
#### Video Demo: 
#### Description:

## About The Project

**Song Recommendation App** is a Python-based gui application that recommends songs based on the user's mood, their favorite artists and genres.The app utilizes the `Spotify API` to retrieve artist information and using audio features  provides recommendations according to moods(such as happy, sad, energetic, or calm).Each recommendation includes the song's name and a direct link to listen to it on Spotify via a web browser.Standard GUI python library [Tkinter](https://python.readthedocs.io/en/stable/library/tkinter.html) is used for user interface.

## Folder Contents
- **project.py**: This is the file which contains ```main``` function and the other functions necessary to implement the app.
- **auth.py** : This file contains the authorization code to get access token from spotify using [client-credentials flow](https://developer.spotify.com/documentation/web-api/tutorials/client-credentials-flow)
- **.env**: This file stores CLIENT_ID and CLIENT_SECRET
- **app.png**: Backgroung image of an application.
- **requirements.txt**: All ```pip```-installable libraries used for this project are listed here.
- **test_project.py**: This file contains test functions for ```project.py```

## Getting started
1. Create a [Spotify developers account](https://developer.spotify.com/dashboard/)
2. Create an app by clicking on *create an app* and giving name and description for the app
3. Take a note of your *Client ID* and *Client Secret* from the app's page
4. Open your terminal and run `git clone https://github.com/Unnati-60/song-recommendation-app` or optionally download the zip file
5. replace CLIENT_ID and CLIENT_SECRET with your *Client ID* and *Client Secret* in .env file
6. Finally, run `python project.py`
7. In GUI,Enter the names of your favorite artists in the designated input field.
8. select your mood from the available options.
9. finally, click the ```Generate Recommendations``` to get recommendations.

## Prerequisites
Run the following command in the terminal after navigating to the project's directory:
```
pip install -r requirements.txt
```