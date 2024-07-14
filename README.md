# 🎭 Playwright TypeScript Example 🎭


## 🛠️ Tech Stack

| Tool                                                                        | Description                                                  |
|-----------------------------------------------------------------------------|--------------------------------------------------------------|
| [Playwright](https://www.npmjs.com/package/playwright)                                       | A framework for Web Testing and Automation                   |
| [@types/node](https://www.npmjs.com/package/@types/node)                               | TypeScript definitions for Node.js                               |

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

```bash
npx playwright test
```

## 📊 Viewing Test Results

Playwright automatically generates an HTML report for test runs. To view the report:

```bash
npx playwright show-report
```

## ℹ️  View Help And Other CLI Options

```bash
npx playwright test --help
```