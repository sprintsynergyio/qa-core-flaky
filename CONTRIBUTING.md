# Contributing

Node.js 22.6 or later is required.

```sh
git clone https://github.com/sprintsynergyio/qa-core-flaky.git
cd qa-core-flaky
npm ci
npm run typecheck
npm test
```

`npm test` builds `dist/` and runs the unit tests. Those tests do not install browsers and they do not call the network.

Found a bug or have an idea? Open an issue. We review pull requests case by case. The license is MIT.
