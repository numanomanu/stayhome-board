stayhome-board
stayhome-board is a super simple online sticky note collaboration tool.

Code is too short, you can make it your self!

![result](https://user-images.githubusercontent.com/11643610/80408949-fd402200-8902-11ea-9029-70d283b73b76.gif)

### install

1.clone

```
git clone git@github.com:TsuyoshiNumano/stayhome-board-minimum.git
```

2. add [firebase realtime database](https://firebase.google.com/docs/database)

3. copy .env.sample to .env and add your firebasekey

```
REACT_APP_API_KEY=
REACT_APP_AUTH_ADMIN=
REACT_APP_DATABASE_URL=
REACT_APP_PROJECT_ID=
REACT_APP_STORAGE_BUCKET=
REACT_APP_MESSAGING_SENDER_ID=
REACT_APP_APP_ID=
REACT_APP_MESUREMENT_ID=
```

4. start server

```
yarn && yarn start
```
