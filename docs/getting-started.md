# Getting started with Strobe Web

Strobe is a platform for sharing photos with family and friends. This guide covers accounts, connecting to an API, and finding people.

## Creating an account

1. Open the app and choose **Sign up**.
2. Enter your email address and a password. Passwords must be **at least 8 characters**.
3. Choose an account role: **User** or **Moderator**.
4. Click **Sign up**, then log in with the same email and password.

Your email address is also used as your username.

## Connecting to an API

Strobe Web is only the front end. It needs a Strobe API to talk to.

- The default API is `http://localhost:3000`.
- To change it permanently, set `VITE_API_BASE_URL` in a `.env` file (copy `.env.example`) and restart `npm run dev`.
- To change it for your browser only, click **Change API URL** on the login or sign-up screen. Click **Use .env/default** to go back.

## Finding people

- Use the search box in the top bar to find users. Up to 8 matches are shown.
- Open someone's profile to follow or unfollow them.
- The right-hand bar lists who you follow and who follows you.

## Deleting your account

You can delete your account from the menu in the top bar. This cannot be undone.
