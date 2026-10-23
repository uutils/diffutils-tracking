# Various tracking tools for diffutils

Tracking the evolution of https://github.com/uutils/diffutils

## GNU testsuite comparison

Below is the evolution of how many GNU tests uutils/diffutils passes.

![GNU testsuite evolution](gnu-results.svg)

Refreshed twice a day by github actions. Changes are documented in the json file ([gnu-result.json](gnu-result.json)).

Compares only the Linux execution.

Based on:
* https://github.com/uutils/diffutils/blob/main/tests/run-upstream-testsuite.sh
