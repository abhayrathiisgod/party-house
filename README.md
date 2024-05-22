# House Party

Django React Application with Spotify API

1. User can authenticate our application to access their data with a certain scope

2. After the user has logged in and granted authorization we obtain access/refresh tokens

3. User access token is used to make requests to the Spotify API

4. After one's access token has expired, we request a new one using the refresh token (stays constant) to continue interacting with the Spotify API


![house_party](https://github.com/abhayrathiisgod/party-house/assets/86717847/06ae2461-05fa-4679-825f-d761c2da6331)


## Setup Instructions

### Install Required Python Modules

```bash
pip install -r requirements.txt
```
### Start Web Server

To start the web server you need to run the following sequence of commands.

Run the django web server.
```bash
python manage.py runserver
```

### [Install Node.js](https://nodejs.org/en/)

### Install Node Modules

First cd into the ```frontend``` folder.
```bash
cd frontend
```
Next install all dependicies.
```bash
npm i
```

### Compile the Front-End

Run the production compile script
```bash
npm run build
```
or for development:
```bash
npm run dev
```

npm run dev
