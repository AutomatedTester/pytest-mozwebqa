Change Log
==========

0.7 (unreleased)
----------------

 * Added support for privacy markers
 * Capture final URL on test failures (reported in terminal)
 * Capture log on test failures if test is marked as public
 * Capture HTML and screenshot only on test failures
 * Improved the debug gathering

0.6 (beta)
----------

 * By default Sauce Labs jobs are public (restricted) - fixes issue #14
 * Avoid running configuration hook for all slave processes - fixes issues #22 and #23
 * Add test durations to HTML report when running with multiple processes - fixes issue #9

0.5 (beta)
----------

 * Added a build identifier for when running with continuous integration

0.4 (beta)
----------

 * Changed default HTML report to results/index.html
 * Send pass/fail status to Sauce Labs - fixes issue #21
 * Added support for custom tags for Sauce Labs jobs
 * Added support for configuration files
 * Remove test names from Sauce Labs tags - fixes issue #20

0.3 (beta)
----------

 * Added error count to custom report - fixes issue #15
 * Catch exceptions thrown when attempting to capture screenshots - fixes issue #16

0.2 (beta)
----------

 * Added custom HTML reports

0.1 (alpha)
-----------

 * Initial release