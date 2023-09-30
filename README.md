# Turborepo TypeScript Boilerplate

A boilerplate for quickly building monorepo project using Turborepo and TypeScript

## Features

- **Monorepo**: using [turborepo](https://turbo.build/repo/docs).
- **Shared TS Config**: monorepo [tsconfig](https://www.typescriptlang.org/docs/handbook/tsconfig-json.html).
- **Git hooks**: using [husky](https://github.com/typicode/husky) and [lint-staged](https://github.com/okonet/lint-staged).
- **Linting**: [prettier](https://prettier.io/).

## Get Started

- Clone this repo
  ```bash
  git clone https://github.com/irfnd/turborepo-ts-boilerplate
  ```
- Rename this boilerplate to whatever you want and move to that folder
  ```bash
  cd turborepo-ts-boilerplate
  ```
- Delete .git folder
- Reinitialize your git
  ```bash
  git init .
  git add .
  git commit -m "Your initialize commit"
  ```
- Install all packages by typing `pnpm i`.
- Project ready to develop.
- You can push/publish to your own github by changing some configuration in `package.json` based on the configuration you want.

## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

- Fork the Project
- Create your Feature Branch `git checkout -b feature/AmazingFeature`
- Commit your Changes `git commit -m '[Add] - some AmazingFeature`
- Push to the Branch `git push origin feature/AmazingFeature`
- Open a Pull Request

## License

Distributed under the [MIT](https://github.com/irfnd/turborepo-ts-boilerplate/blob/master/LICENSE) License.
