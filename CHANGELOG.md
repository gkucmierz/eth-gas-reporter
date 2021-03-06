## Changelog: eth-gas-reporter

0.0.12 / 2017-10-28
===================

  * Add config. Add gasPrice and currency code options
  * Improve table clarity
  * Derive block.gasLimit from rpc

0.0.11 / 2017-10-23
==================

  * Add Travis CI
  * Fix bug that crashed reported when truffle could not find required file

0.0.10 / 2017-10-22
==================

  * Add examples

0.0.10 / 2017-10-22
==================

  * Filter deployment calls that throw from the stats

0.0.8 / 2017-10-22
=================

  * Filter method calls that throw from the stats
  * Add deployment stats
  * Add number of calls column

0.0.6 / 2017-10-14
================

  * Stop showing zero gas usage in mocha output
  * Show currency rates and gwei gas price rates in table header
  * Alphabetize table
  * Fix bug caused by unused methods reporting NaN
  * Fix failure to round avg gas use in table
  * Update dev deps to truffle4 beta

0.0.5 / 2017-10-12
=================

  * Thanks
  * Update image
  * Finish table formatting
  * Add some variable gas consumption contracts
  * Working table
  * Get map to work in the runner
  * Get gasStats file and percentage of limit working
  * Test using npm install
  * Add gasPrice data fetch, config logic
  * More tests
  * Abi encoding map.

0.0.4 / 2017-10-01
==================

  * Add visual inspection test
  * Fix bug that counted gas consumed in the test hooks
