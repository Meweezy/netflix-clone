- Get TMDB API Key
- Create a react app (using npx create-react-app)
- Setup firebase hosting
- Get all movies
- Build the Rows
- Build the Banner
- Build the Navbar
- Add Trailer popups (download 2 packages: npm i react-youtube, npm i movie-trailer)
- Deploy to Firebase

@cleverqazi
@ssssangha

Deploying to Firebase:
from Terminal , run

- Firebase login
- firebase init
  - select hosting
  - use existing project
  - enter "build" at the prompt "What do you want to use as your public directory?"
  - enter "y" at promt "Configure as a single-page-app"
- enter "npm run build"
- enter "firebase deploy" to deploy the app.
