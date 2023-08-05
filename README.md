# TweetApp

## Install prerequisites

- Node.js (18.x or newer)
  - See <https://app.path.progate.com/tasks/PuSZdMDZJY_cksKGNxs4b/preview>
- Puppeteer
  - See <https://app.path.progate.com/tasks/CwBFxQbIm54hr-bxtmMn9/preview>
- MySQL (8.x or newer)
  - See <https://app.path.progate.com/tasks/sQ4PifQLeD6eHeTiJ0i5i/preview>

## Install

call install command on project root.

```:console
npm clean-install
```

## Start development mode

call watch command on project root.

```:console
npm run watch
```

and access to `http://localhost:8000`

## Start production mode

call start command on project root.

```:console
npm start
```

and access to `http://localhost:8000`

## Command

npm command list. call `npm run [command]`. for example:

```:console
npm run test:e2e
```

will run all tests in this project.

- `test:e2e`: run e2e test,
- `watch`: start development mode,
- `lint:check`: check code style by eslint,
- `lint:fix`: check code style by eslint with auto fix,
- `format:check`: check format by prettier,
- `format:fix`: check format by prettier with auto fix,
- `start`: start production mode
