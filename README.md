# MLH OriHack Board

![Node.js Supported Version](https://img.shields.io/badge/node-%3E%3D14.17.0-blue?style=flat-square)
[![Frontend Dependencies](https://img.shields.io/david/sudiptog81/mlh-orihack-frontend?label=frontend&style=flat-square)](https://github.com/sudiptog81/mlh-orihack-frontend/)
[![Backend Dependencies](https://img.shields.io/david/sudiptog81/mlh-orihack-backend?label=backend&style=flat-square)](https://github.com/sudiptog81/mlh-orihack-backend/)
![License](https://img.shields.io/github/license/sudiptog81/mlh-orihack?style=flat-square) [![All Contributors](https://img.shields.io/badge/all_contributors-5-orange.svg?style=flat-square)](#contributors-)

As developers we sometimes forget to reach out for help from others. We get wrapped up in a problem and knock our heads around searching for the most optimized anwer. To attempt to solve this, we created a social platform where users can post issues or PRs linked to open source projects from GitHub. Then using their feed they can engage with other developers to both get valuable feedback and pose suggestions.

![Screenshot](https://i.imgur.com/eW9ROCe.png)

## Technologies

- Vue.js
- Vuex
- [Stylex](https://github.com/ladifire-opensource/stylex)
- MongoDB
- Express.js
- Node.js

## Getting Started

Clone this repository along with all submodules and navigate to the cloned repository:

```bash
$ git clone --recurse-submodules https://github.com/sudiptog81/mlh-orihack.git
$ cd mlh-orihack
```

Navigate to the `frontend` folder, install project dependencies and create a production build:

```bash
mlh-orihack $ cd frontend
frontend $ npm install
frontend $ npm run build
```

Navigate to the `backend` folder, create a new file called `.env` from the given template in [`.env.example`](https://github.com/sudiptog81/mlh-orihack-backend/blob/main/.env.example):

```bash
frontend $ cd ../backend
backend $ cp .env.example .env
```

Go to GitHub Developer Settings and create a new GitHub OAuth Application, note down the Client ID and generate a new Client Secret. Populate the Callback URL field with `http://localhost:3000/auth/github/callback` to work with the application locally. This would also be the time to note down the MongoDB connection URI. Populate the values in `.env` with these details.

Now, install project dependencies and start the application, while still being in the `backend` folder:

```bash
backend $ npm install
backend $ npm run start
```

Congratulations, the application should now be running at `http://localhost:3000/`.

## Development

If you want to contribute to this project, you will need to set up a development environment. Ensure you can use the application after following the instructions given in the previous section.

On a terminal emulator, navigate to the `frontend` folder and execute the following command:

```bash
frontend $ npm run serve
```

On another terminal, navigate to the `backend` folder and execute the following command:

```bash
backend $ npm run dev
```

You can now access the application running on `https://localhost:8080/`. The development server will proxy all requests to the backend whenever needed.

## License

[The MIT Open Source License](./LICENSE.md).

## Contributors ✨

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center"><a href="https://conwell.info"><img src="https://avatars.githubusercontent.com/u/9061382?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Joe Conwell</b></sub></a><br /><a href="#design-jmc529" title="Design">🎨</a> <a href="https://github.com/sudiptog81/mlh-orihack/commits?author=jmc529" title="Code">💻</a> <a href="#ideas-jmc529" title="Ideas, Planning, & Feedback">🤔</a> <a href="https://github.com/sudiptog81/mlh-orihack/pulls?q=is%3Apr+reviewed-by%3Ajmc529" title="Reviewed Pull Requests">👀</a></td>
    <td align="center"><a href="https://github.com/desirekaleba"><img src="https://avatars.githubusercontent.com/u/46345872?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Desire Kaleba</b></sub></a><br /><a href="https://github.com/sudiptog81/mlh-orihack/commits?author=desirekaleba" title="Code">💻</a> <a href="#ideas-desirekaleba" title="Ideas, Planning, & Feedback">🤔</a> <a href="https://github.com/sudiptog81/mlh-orihack/pulls?q=is%3Apr+reviewed-by%3Adesirekaleba" title="Reviewed Pull Requests">👀</a></td>
    <td align="center"><a href="https://sohamp.dev"><img src="https://avatars.githubusercontent.com/u/55358652?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Soham Parekh</b></sub></a><br /><a href="https://github.com/sudiptog81/mlh-orihack/commits?author=und3fined-v01d" title="Code">💻</a> <a href="#ideas-und3fined-v01d" title="Ideas, Planning, & Feedback">🤔</a> <a href="https://github.com/sudiptog81/mlh-orihack/pulls?q=is%3Apr+reviewed-by%3Aund3fined-v01d" title="Reviewed Pull Requests">👀</a></td>
    <td align="center"><a href="https://sudipto.ghosh.pro"><img src="https://avatars.githubusercontent.com/u/11232940?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Sudipto Ghosh</b></sub></a><br /><a href="https://github.com/sudiptog81/mlh-orihack/commits?author=sudiptog81" title="Code">💻</a> <a href="https://github.com/sudiptog81/mlh-orihack/commits?author=sudiptog81" title="Documentation">📖</a> <a href="#ideas-sudiptog81" title="Ideas, Planning, & Feedback">🤔</a> <a href="https://github.com/sudiptog81/mlh-orihack/pulls?q=is%3Apr+reviewed-by%3Asudiptog81" title="Reviewed Pull Requests">👀</a></td>
    <td align="center"><a href="http://linkedin.com/in/aayush-gupta-447978164/"><img src="https://avatars.githubusercontent.com/u/47032027?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Aayush Gupta</b></sub></a><br /><a href="https://github.com/sudiptog81/mlh-orihack/commits?author=aayush-05" title="Code">💻</a> <a href="https://github.com/sudiptog81/mlh-orihack/commits?author=aayush-05" title="Tests">⚠️</a> <a href="https://github.com/sudiptog81/mlh-orihack/commits?author=aayush-05" title="Documentation">📖</a></td>
  </tr>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!

This repository was created by the members of Pod 3.0.0 "Fast Tortoise" for the MLH Fellowship Orientation Hackathon.
