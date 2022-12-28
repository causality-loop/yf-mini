# yf mini

## description
- a small script which scrapes price data from Yahoo Finance
- for the symbol(s) inputed, the price, market change, and market change (percent) are shown
- shows pre-market or post-market prices when appropriate
 
## what problem does this solve?
- there are a number of excellent CLI-based programs of a similar nature, however they are not trivial to install on Android
- this script is truly distro agnostic because is is written in BASH and its only requirement is the `jq` package

## install
- install `jq`
- download the script
- optional: move the script to a directory in `PATH`

## usage
```sh
yf SPY DIA QQQ IWM
```

## references
- code lifted from the below sites:
  - https://github.com/mop-tracker/mop/wiki/How-to-fetch-market-data-from-Yahoo!-Finance-in-CSV-form,-from-the-command-line
  - https://misc.flogisoft.com/bash/tip_colors_and_formatting
  - https://stackoverflow.com/questions/64957982/how-to-pad-numbers-with-jq
  - https://stackoverflow.com/questions/1729824/an-efficient-way-to-transpose-a-file-in-bash

