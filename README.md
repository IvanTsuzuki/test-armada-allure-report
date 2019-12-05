# testarmada-allure-report
This is allure reporter adapter for testarmada tests, which generates xml reports that are consumed by allure during generation.

## Using Reporter In test armada
In global js file add reporter like this

```javascript
var allure = require("testarmada-allure-report");

module.exports = {
    reporter: allure.write
};

```
This will generate xml reports in allure-results directory at root.

You can use [allure generate](https://github.com/allure-framework/allure-core/wiki#generating-a-report) for report generation
