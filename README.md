# ai-github-action

[![npm version](https://img.shields.io/npm/v/ai-github-action.svg)](https://www.npmjs.com/package/ai-github-action)
[![npm downloads](https://img.shields.io/npm/dm/ai-github-action.svg)](https://www.npmjs.com/package/ai-github-action)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)


Generate GitHub Actions workflows from plain English. Stop copy-pasting from StackOverflow.

## Install

```bash
npm install -g ai-github-action
```

## Usage

```bash
npx ai-github-action "test and deploy on push to main"
npx ai-github-action "run eslint and prettier on PRs" --install
npx ai-github-action "build docker image and push to ECR" -o deploy.yml
```

## Options

- `--install` - Write directly to `.github/workflows/`
- `-o, --output <file>` - Write to specific file

## Setup

```bash
export OPENAI_API_KEY=sk-...
```

## License

MIT
