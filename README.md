# cypress-mocha-version-warning-repro

## Steps to reproduce
1. `git clone https://github.com/jluttrell/cypress-mocha-version-warning-repro.git`
1. `cd cypress-mocha-version-warning-repro`
1. `npm ci`
1. `npm test`

Notice `Couldn't determine Mocha version` is printed to console once before test runs start and once after the first spec file is run. 
