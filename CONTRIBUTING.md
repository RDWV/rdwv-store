# Contributing to RedWaves Store

Welcome, and thank you for your interest in contributing to RedWaves Store!

Our [central contributing guidelines](https://github.com/rdwv/rdwv/blob/master/CONTRIBUTING.md) apply to all RedWaves repositories.

Below are the instructions for setting up development environment with RedWaves Store.

## Setting up development environment

Some general advice can be found in our [central contributing guidelines](https://github.com/rdwv/rdwv/blob/master/CONTRIBUTING.md#setting-up-development-environment).

Installation instructions:

```bash
git clone https://github.com/<<<your-github-account>>>/rdwv-store.git
cd rdwv-store
yarn
```

To launch:

```bash
# serve with hot reload at localhost:3000
yarn dev

# build for production and launch server
yarn build
yarn start
```

From now on, development environment is ready.

**Note**: we use pre-commit hooks for development, you can install pre-commit and it's hooks like so:

```bash
curl https://pre-commit.com/install-local.py | python3 -
pre-commit install
```

Make sure to follow [our coding guidelines](https://github.com/rdwv/rdwv/blob/master/CODING_STANDARDS.md) when developing.

# Thank You!

Your contributions to open source, large or small, make great projects like this possible. Thank you for taking the time to contribute.
