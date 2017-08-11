# Firebase-Auth

Firebase auth for iOS and Android

# Install
```
git clone https://github.com/lukeaus/react-native-firebase-auth
```

Create a new [Firebase](https://firebase.google.com) project

Get your credentials from firebase and put them in ```secrets.js``` file in project root
```
export default {
  apiKey: 'my-key',
  authDomain: 'foo.firebaseapp.com',
  databaseURL: 'https://foo.firebaseio.com',
  projectId: 'foo123',
  storageBucket: 'fooboo',
  messagingSenderId: '123'
};
```

# Install
// Note: node and npm required
// Xcode required for iOS development on mac
```
cd auth
npm install
```

# Run
```
react-native run-ios  // ios
react-native run-android  // android
```

