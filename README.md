# passportjs-google

Create & Update the `.env` file at the root of the project folder with your Google Client ID and Google Client Secret as below:

File: `.env`
```
GOOGLE_CLIENT_ID=<CLIENT_ID>
GOOGLE_CLIENT_SECRET=<CLIENT_SECRET>
```

Goto: `https://console.cloud.google.com/apis/credentials?project=<your project>`

Under "OAuth 2.0 Client IDs" select the Web Client

Client ID & Secret will be available here.

Also configure the "Authorized JavaScript Origins" and "Authorized redirect URIs"

## Authorized JavaScript Origins

`http://localhost:3000`

## Authorized redirect URIs

`http://localhost:3000/oauth2/redirect/google`


**Then run the below commands:**

```
npm install

npm start
```

Open `http://localhost:3000` in your browser
