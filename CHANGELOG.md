# Changelog

Only listing significant user-visible, not internal code cleanups and minor bug fixes.

## 0.6.0 (upcoming)

* [QA-189] Removed extra dot in 'service response status' step. Old step removed.
* [QA-152] New aspect merging 'include' and 'loop'. Old aspects removed.

## 0.5.0 (June 12, 2017)

* [QA-342] New cucumber tag @loop to multiple scenario executions

## 0.4.0 (March 06, 2017)

* [QA-272] better classes packaging
* [QA-298] Apache2 license. Step definitions redefined

## 0.3.0 (January 26, 2017)

* CukesGHooks will invoke the logger with each step

## 0.2.0 (June 2016)

* Ignored scenarios will fail if ignore cause was an already done jira ticket
* No more a submodule project
* Added new aspect to force the browser name and version in tests development ,using FORCE_BROWSER (even availableUniqueBrowsers factory is defined).

  Eg: mvn -U verify -DSELENIUM_GRID=jenkins.stratio.com:4444 **-DFORCE_BROWSER=chrome_33**
