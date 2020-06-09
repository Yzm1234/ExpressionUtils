# ExpressionUtils
A module to upload, download and export RNASeq Expression data obtained by either StringTie or Cufflinks Apps.

## Current Status

| Branch  | Build                                                              | Coverage                                                                         | LGTM Alerts                                                     |
| ------- | ------------------------------------------------------------------ | -------------------------------------------------------------------------------- | --------------------------------------------------------------- |
| master  | [![KBase SDK Tests](https://github.com/kbaseapps/ExpressionUtils/workflows/KBase%20SDK%20Tests/badge.svg)](https://github.com/kbaseapps/ExpressionUtils/actions?query=workflow%3A%22KBase+SDK+Tests%22)  | [![codecov](https://codecov.io/gh/kbaseapps/ExpressionUtils/branch/master/graph/badge.svg)](https://codecov.io/gh/kbaseapps/ExpressionUtils)  | [![Total alerts](https://img.shields.io/lgtm/alerts/g/kbaseapps/ExpressionUtils.svg?logo=lgtm&logoWidth=18)](https://lgtm.com/projects/g/kbaseapps/ExpressionUtils/alerts/)  |

## Details
This is a [KBase](https://kbase.us) module generated by the [KBase SDK](https://github.com/kbase/kb_sdk).

TODO:
- ReadsAlignmentUtils and this kbase module both use a set of utility functions in a python module
called script_utils. This module should be placed in a separate github respository and then imported
into these and other kbase modules that require the utility functions.
