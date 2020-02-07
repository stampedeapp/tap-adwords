# Changelog

## meltano.1.0.2
  *  [#2](https://gitlab.com/meltano/tap-adwords/issues/2) Fix tap-adwords failing on MacOs due to strftime() returning `4Y` instead of the year (e.g. `4Y-02-01` instead of `2020-02-01`)

## meltano.1.0.1
  *  [#1](https://gitlab.com/meltano/tap-adwords/issues/1) Add option to set the primary keys for Performance Reports through the configuration file. 
     For example: `"primary_keys": {"KEYWORDS_PERFORMANCE_REPORT": ["keywordID", "day"], ... ...}`

## meltano.1.0.0
  *  Fork version 1.12.0 from https://github.com/singer-io/tap-adwords