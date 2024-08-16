# 🎭 Playwright TypeScript Example 🎭

![twitter](https://img.shields.io/twitter/follow/NirTal2)
![dev run](https://github.com/nirtal85/playwright-typescript-example/actions/workflows/devRun.yml/badge.svg)
![nightly](https://github.com/nirtal85/playwright-typescript-example/actions/workflows/nightly.yml/badge.svg)

## 📃 Articles written about this project


## 🛠️ Tech Stack

| Tool                                                                                     | Description                                                  |
|------------------------------------------------------------------------------------------|--------------------------------------------------------------|
| [@stylistic/eslint-plugin](https://www.npmjs.com/package/@stylistic/eslint-plugin)                                        | Stylistic formatting rules for ESLint                        |
| [@types/node](https://www.npmjs.com/package/@types/node)                                 | TypeScript definitions for Node.js                           |
| [@typescript-eslint/eslint-plugin](https://www.npmjs.com/package/@stylistic/eslint-plugin)                        | ESLint plugin for TypeScript                                 |
| [@typescript-eslint/parser](https://www.npmjs.com/package/@typescript-eslint/parser)                               | Parser for TypeScript-specific linting rules                 |
| [allure-playwright](https://www.npmjs.com/package/allure-playwright)                      | Allure framework integration for Playwright Test framework   |
| [ESLint](https://www.npmjs.com/package/eslint)                                                            | A tool for identifying and reporting on patterns in JavaScript |
| [eslint-config-prettier](https://www.npmjs.com/package/eslint-config-prettier)             | Turns off all rules that are unnecessary or might conflict with Prettier |
| [eslint-plugin-import](https://www.npmjs.com/package/eslint-plugin-import)                | ESLint plugin with rules that help validate proper imports   |
| [eslint-plugin-playwright](https://www.npmjs.com/package/eslint-plugin-playwright) | ESLint plugin for Playwright tests                           |
| [eslint-plugin-prettier](https://www.npmjs.com/package/eslint-plugin-prettier)             | Runs Prettier as an ESLint rule                              |
| [Playwright](https://www.npmjs.com/package/playwright)                                                    | A framework for Web Testing and Automation                   |
| [Prettier](https://www.npmjs.com/package/prettier)                                                         | An opinionated code formatter                                |
| [TypeScript](https://www.npmjs.com/package/typescript)                                            | A typed superset of JavaScript                               |

## ⚙️ Setup Instructions

### Step 1: Clone the project

```bash
git clone https://github.com/nirtal85/playwright-typescript-example.git
cd playwright-typescript-example
```

### Step 2: Install dependencies

```bash
npm install
```


### Step 3: Install playwright browsers

```bash
npx playwright install --with-deps
```

## 🏃‍♂️ Running Tests

Run tests:

```bash
npx playwright test
```

Run the test with UI mode:

```bash
npx playwright test --ui
```

## 📊 Viewing Test Results

### Install Allure Commandline To View Test results

#### For Windows:

Follow the instructions [here](https://scoop.sh/) to install Scoop.<br>
Run the following command to install Allure using Scoop:

```bash
scoop install allure
```

#### For Mac:

```bash
brew install allure
```

### View Results Locally:

```bash
allure serve allure-results
```

### View Results Online:

[View allure results via Github pages](https://nirtal85.github.io/Playwright-Typescript-Example/)

## ℹ️  View Help And Other CLI Options

```bash
npx playwright test --help
```