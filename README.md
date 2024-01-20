## Technical Achievements

This project is aimed to showcase my skills in building a full-stack web app that imitates the functionality and design of Spotify, a popular music streaming platform for your local files. 

## Problems Faced and Solutions
Authentication:
I wanted to create a secure and user-friendly authentication system for the app, which would allow users to sign in, create their Spotify accounts, and access their data and playlists locally. However, I faced some challenges with Next.js while handling the OAuth 2.0 flow and storing user data. To overcome these challenges, I decided to use Clerk, a platform that provides authentication and user management for web applications. Clerk offers various authentication methods, including passwords, email codes, OAuth, and more. It also provides pre-built UI components such as sign-in, sign-up, and user profile, which can be customized and themed to match my branding. I integrated Clerk with Next.js using Clerk's SDK and React hooks.

Real-time data:
I wanted to make the app more interactive and responsive by allowing users to see the current playing track and control the playback. However, I faced some difficulties in implementing real-time data updates and communication. To overcome these challenges, I used a JavaScript library that allows you to create a custom player. I created a custom player component that can play, pause, skip, shuffle, repeat, and adjust the volume of the music.

## Frontend development: 
I utilized Next.js, to create the front end of the app. I used React hooks and custom components to generate a dynamic and responsive user interface. Additionally, I used Tailwind CSS and Shadcn-ui, to style the app and make it look like the original Spotify platform. Tailwind CSS allowed me to create custom designs without writing any CSS.  Shadcn-ui library provided me with ready-made components and icons that were compatible with Tailwind CSS. 

## Backend development: 
I used Supabase, to handle the backend logic and data storage of the app. I integrated PostgreSQL, with Supabase to store and query the music data. 

## Deployment: 
I deployed the app on Vercel. I configured the app to use environment variables and secrets to store the API keys and credentials. I also enabled HTTPS and SSL encryption to ensure the security and privacy of the app and its users.
