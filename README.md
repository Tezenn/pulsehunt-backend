# Pulse Hunt (server/backend)

Pulse Hunt is a solo prject of a Codeworks student, developed in one week. We decided as a learning experience to jump in and implement some of the features that the orignal author wished to see.
On the backend we developed an authentication middleware using JsonWebToken.
On the frontend we added a landing login/signup page, made the layout responsive for any device resolution and slightly improved/smoothened the UI.
Below you can find the original Readme of the project.
___

Pulse Hunt is a market place where Indie Trainers can offer their workout sessions to users. The project was initiated as a one week solo project when attending [Codeworks](https://codeworks.me) Coding Bootcamp in Barcelona.

This is the server/backend. The client/frontend can be found [here](https://github.com/cherlin/pulsehunt-frontend "Pulse Hunt backend")

## Getting started

### Prerequisites
* You need to have MongoDB installed on your local machine.
* You need a [Cloudinary](https://cloudinary.com/) account.

You can run this backend isolated, but it will make more sense if you combine it with the [the corresponding frontend](https://github.com/cherlin/pulsehunt-frontend "Pulse Hunt backend").

### Tips!
* Use [Postman](https://www.getpostman.com) for testing the backend. A *postman.json* file is included in the repo for easy setup.
* [MongoDB Compass (Community Edition)](https://www.mongodb.com/products/compass) is a nice GUI for MongoDB.

### Installing
* Clone this repo: `git clone https://github.com/cherlin/pulsehunt-backend`
* Move into the folder: `cd pulsehunt-backend`
* Install all dependencies: `npm install`
* Rename the `.env.default` file to `.env`: `mv .env.default .env``
* Enter the required details (Can be found on your Cloudinary dashboard).
* Run `mongod` in a separate terminal session to start your local mongo instance.
* To start the frontend with nodemon (automatic restart of server on file changes), run `npm run dev` or `yarn run dev`. 

## Tech Stack
* [Koa](https://koajs.com)
* [MongoDB](https://www.mongodb.com)
* [Cloudinary](https://cloudinary.com) - Cloudinary is a media management platform, providing storage, image manipulation and CDN (with a lofty free tier).

## TODOs
* Testing!
* Add additional filtering for the episodes endpoint
* Authentication (see [frontend repo](https://github.com/cherlin/pulsehunt-frontend))
* ..
* ..

## Feedback
If you have any feedback, send me an [email](mailto:christofer.herlin@gmail.com) or open an issue on the repo.

## Collaboration
All improvements welcome! Open a pull request and let's discuss.
