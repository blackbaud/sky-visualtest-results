# sky-visualtest-results

This repository is used to store screenshots of visual test failures during a [Sky build](https://magnum.travis-ci.com/blackbaud/sky).

## How to use this repo

When a visual test fails, a new branch is created in this repository, and the name of this branch corresponds with the number of the Travis build that failed.  The new branch will contain a "failures" folder and an "all" folder.  The "failures" folder contains screenshots of any tests that failed and display in pink the pixel differences between the baseline screenshot and the screenshot that was taken at the time of the test.  The "all" folder contains the original baseline screenshots as well as the screenshot taken at the time of the test so that you can visually inspect individually them without the pink pixel differences.
