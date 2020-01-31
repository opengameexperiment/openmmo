# openmmo
The idea of an openmmo is that we should build an mmo game from the ground up, with the players having direct knowledge of what is in the game and being able to contribute to the game actively if they so desire. We'll not limit players to having to play as an mmo, and they can pick up packages of the game and run them directly on their own and play with just them and their friends. We can't even really stop someone else from running their own version of the server with different capabilities, but the one deployed here will be in this repo.
We'll likely need to rely on donations or ad revenue to run the server once it starts up, but this project is merely for fun and is not meant to be something where we make money, but being able to pay bills with the work we do here definitely helps!

# Technologies
The following technologies are those that are used at the core. This is not to say we must only use these technologies, but using other similar technologies will clash with these, and as such we should convene on these specific Technologies for their use case:

- Typescript: Main language for the game, both backend and frontend!
- Npm: Dependency management system for the game. This one is a little loose as I'm simply familiar with it, but I'm open to change.
- Docker: We should containerize the app for ease of autoscaling and deployment.
- Angular: UI framework, I choose Angular simply because I have used a form of it, and its written in typescript, so its nice.
- Bootstrap: I've used Boostrap quite a bit, and it is really nice. Why not use it?
- Express: I've used Express to start up servers and it is quite nice on NodeJS.
- Colyseus: Very good javascript/typescript library for match finding and building. When we put together "rooms" for people to drop into (places they go, maybe sharded so not everyone in one location is in one room), this will be quite helpful.
- Phaser: Pretty good javascript frontend game platform. We'll see how it matches up with what we can do.
- Auth0: Need to authorize users, and rather than write this ourselves we should use a standard service. Auth0 is a great one I've used on a number of occasions.
