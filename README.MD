# Contact-Tracker

Contact Tracker is a Fullstack MERN application that allows users to register and manager their contacts via a responsive web interface. A demo of this application can be seen [HERE](https://contact-tracker.christopherwall.online/)

## Environment Variables

The environment vareables for this appliction are installed in /config/default.json for development and /config/production.json for production. For this application to function correctly, ensure the below variables are set in these files

- "mongoURI": "YOUR_URI"
- "jwtSecret": "YOUR_SECRET"

## Building the application

To build the client side code run the below command from the client directory:
`npm run build`

This will create the /client/build directory will all the production dependencies
