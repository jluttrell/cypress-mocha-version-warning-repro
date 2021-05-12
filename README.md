# cypress-mocha-version-warning-repro

## Steps to reproduce
1. `git clone https://github.com/jluttrell/cypress-mocha-version-warning-repro.git`
1. `cd cypress-mocha-version-warning-repro`
1. `npm ci`
1. `npm test`

Notice `Couldn't determine Mocha version` is printed to console once before test runs start and once after the first spec file is run.
Also notice the following warnings after `npm install`:
```
npm WARN cypress-multi-reporters@1.5.0 requires a peer of mocha@>=3.1.2 but none is installed. You must install peer dependencies yourself.
npm WARN mocha-junit-reporter@2.0.0 requires a peer of mocha@>=2.2.5 but none is installed. You must install peer dependencies yourself.
```