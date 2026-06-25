# Planner App

A simple shared planning board for scheduling times, collecting activity ideas, tracking people, and chatting around a plan.

## Local Preview

```sh
python3 -m http.server 4173
```

Then open:

```text
http://127.0.0.1:4173
```

## Firebase Setup

This app is prepared for Firebase Hosting, Authentication, and Firestore.

1. Re-authenticate Firebase CLI if needed:

```sh
firebase login --reauth
```

2. Pin the local app to your Firebase project:

```sh
firebase use --add
```

3. Copy your Firebase web app config into `firebase-config.js`.

4. Deploy hosting and rules:

```sh
firebase deploy
```

# Huddle
