# PHP Development Container

![GitHub repo size](https://img.shields.io/github/repo-size/michaelbragg/devcontainer-php)
![GitHub last commit](https://img.shields.io/github/last-commit/michaelbragg/devcontainer-php)

A Development Container, primarily for local PHP and Node-based development in VS Code.
The devContainer has Docker, PHP and Node installed for serving your project and local toolings such as Composer and NPM.

## Dependencies

- [Docker Desktop](https://www.docker.com/products/docker-desktop/)
- [VS Code](https://code.visualstudio.com/)

## Features

- [Docker in Docker]()
- [Git](https://github.com/devcontainers/features/tree/main/src/git)
- [GitHub CLI](https://github.com/devcontainers/features/tree/main/src/github-cli)
- [NodeJS](https://github.com/devcontainers/features/tree/main/src/node)
- [PHP](https://github.com/devcontainers/features/tree/main/src/docker-in-docker)

## Getting started

Download this release or clone via:

```bash
git clone --depth=1 --branch=master https://github.com/michaelbragg/development-devcontainer.git {project-name}
rm -rf ./{project-name}/.git
rm -rf ./{project-name}/{readme,license}.md
```

## License

MIT License: Copyright (c) 2022-2023 Michael Bragg

## Contact

If you want to contact me you can reach me at <email@michaelbragg.com>.
