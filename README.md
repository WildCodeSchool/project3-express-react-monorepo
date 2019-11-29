# Express/React monorepo

**Instructors**:

* Get this boilerplate (without the Git history) with `npx degit WildCodeSchool/project3-express-react-monorepo`,
* rename it to the project's name,
* edit the application names in `package.json`, `back/package.json`, `front/package.json`,
* initialize a new Git repo,
* and **remove these lines** before handing the project over to the students!

## Installation

Clone this repo.

Then from its root, run:

    npm install
    npx lerna bootstrap

This will install dependencies in both `back` and `front` directories.

## Usage

Run `npm start` from the root.

## Style guide

This project includes ESLint, with the [Airbnb JavaScript Style Guide](https://github.com/airbnb/javascript).

It is set up with Husky pre-commit hooks, which check that the code in both `back` and `front` is compliant with the style guide. `git commit` fails if this is not the case!
