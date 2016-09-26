# tennis-pokemon-class
This is the bootstrapping TDD in Javascript for BUU class

## How to setup project
* *npm init* to create package.json file
* *npm install --save-dev jasmine* to install jasmine test suite
* *node_modules/.bin/jasmine init* to setup jasmine environment
* Create *spec* folder
* Create test file in spec folder. The file name must be in [test name].spec.js. For example, tennis.spec.js

## Jasmine example
```javascript
describe('Tennis', function () {
  it('should be pass', function () {
    expect(true).toBe(true);
  });
});
```
