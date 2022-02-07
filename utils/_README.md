### src/assets/css/lib/shared-scss/utils

This folder should contain any of the utility needs for anywhere in the CSS for
the full family of JHU sites, which should only consist of reusable, includable
variables and mixins.

**There should be NO parseable CSS in these files at all. This means that all of
these files can be included many different times without duplicating processed
CSS in the finished .css files.**

Note: main.scss in this file should include all of the other files so that
@use '../lib/shared-scss/utils/main' will import all of the utilities at once.
