# express-react-example

Example of using express to provide a data API and serve React.

View the running app on [Heroku](https://express-react-example.herokuapp.com/)

Like my work? Tip me! https://www.paypal.me/jessamynsmith

This project is based on Dave Ceddia's tutorial here:
https://daveceddia.com/create-react-app-express-backend/

### Development

Fork the project on github and git clone your fork, e.g.:

    git clone https://github.com/<username>/express-react-example.git

Ensure you have node and yarn installed (I recommend using homebrew on OSX), then use yarn to install JavaScript dependencies:

    yarn install

Run tests:

    cd client && yarn test

Run server:

    yarn start

By default you can view the running server on port 3000:

    http://127.0.0.1:3000/

### Deployment

This project is already set up for deployment to Heroku.

Make a new Heroku app and deploy from the command line:

    heroku apps:create <appname>
    git push heroku master
