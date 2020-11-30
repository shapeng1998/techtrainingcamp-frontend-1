# techtrainingcamp-frontend-1

> A simple implementation of 2048 game, supports scoreboards, multiplayer mode, difficulty adjustment and smooth animation. Some logic is referenced from project [2048-multiplayer-client](https://github.com/pietrushka/2048-multiplayer-client) and [2048-multiplayer-server](https://github.com/pietrushka/2048-multiplayer-server). Both frontend and backend have CI/CD using [Github Actions](https://github.com/features/actions).

## Additional features

1. League table
2. Easy and hard mode
3. Multi-player chatting
4. Preparation part of multi-player phase
5. Fluent animation

## Dev setup

Frontend:

```bash
# clone the project
git clone https://github.com/shapeng1998/2048-frontend

# enter the project directory
cd 2048-frontend

# install dependency
npm install

# develop
npm start
```

Backend:

```bash
# clone the project
git clone https://github.com/shapeng1998/2048-backend

# enter the project directory
cd 2048-backend

# install nodemon
npm install nodemon -g

# install dependency
npm install

# develop
npm run dev
```

## Technology stack

Frontend:

- [React](https://reactjs.org/)
- [TypeScript](https://www.typescriptlang.org/)
- [Socket.IO](https://socket.io/)

Backend:

- [Express](https://www.expressjs.com)
- [MongoDB](https://www.mongodb.com/)
- [Socket.IO](https://socket.io/)

## Related projects

- [2048-frontend](https://github.com/shapeng1998/2048-frontend)
- [2048-backend](https://github.com/shapeng1998/2048-backend)

## Demo

- [2048-game](http://47.101.139.249)
