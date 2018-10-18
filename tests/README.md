Tests and Coverage
================
18 October, 2018 14:44:34

This output is created by
[covrpage](https://github.com/yonicd/covrpage).

## Coverage

Coverage summary is created using the
[covr](https://github.com/r-lib/covr) package.

    ## ⚠️ Not All Tests Passed
    ##   Coverage statistics are approximations of the non-failing tests.
    ##   Use with caution
    ## 
    ##  For further investigation check in testthat summary tables.

| Object                                             | Coverage (%) |
| :------------------------------------------------- | :----------: |
| covrpage                                           |    10.06     |
| [R/badge.R](../R/badge.R)                          |     0.00     |
| [R/coverage\_skip.R](../R/coverage_skip.R)         |     0.00     |
| [R/covrpage\_snapshot.R](../R/covrpage_snapshot.R) |     0.00     |
| [R/covrpage.R](../R/covrpage.R)                    |     0.00     |
| [R/map\_testthat.R](../R/map_testthat.R)           |     0.00     |
| [R/tencrypt.R](../R/tencrypt.R)                    |     0.00     |
| [R/testthat\_summary.R](../R/testthat_summary.R)   |     0.00     |
| [R/vignette.R](../R/vignette.R)                    |     0.00     |
| [R/covrpage\_checks.R](../R/covrpage_checks.R)     |    21.43     |
| [R/create\_chunks.R](../R/create_chunks.R)         |    72.41     |
| [R/use\_covrpage.R](../R/use_covrpage.R)           |    79.41     |

<br>

## Unit Tests

Unit Test summary is created using the
[testthat](https://github.com/r-lib/testthat)
package.

| file                                               | n |  time | error | failed | skipped | warning |   |
| :------------------------------------------------- | -: | ----: | ----: | -----: | ------: | ------: | - |
| [test-check\_utils.R](testthat/test-check_utils.R) | 5 | 0.100 |     0 |      0 |       1 |       0 | 🔶 |
| [test-covrfuns.R](testthat/test-covrfuns.R)        | 3 | 0.052 |     3 |      0 |       0 |       0 |   |

<details open>

<summary> Show Detailed Test Results
</summary>

| file                                                   | context                    | test                           | status  | n |  time |   |
| :----------------------------------------------------- | :------------------------- | :----------------------------- | :------ | -: | ----: | - |
| [test-check\_utils.R](testthat/test-check_utils.R#L4)  | check for tests            | tests are detected             | PASS    | 1 | 0.022 |   |
| [test-check\_utils.R](testthat/test-check_utils.R#L12) | check for packages         | packages are detected          | SKIPPED | 3 | 0.031 | 🔶 |
| [test-check\_utils.R](testthat/test-check_utils.R#L23) | use covrpage               | test use\_covrpage             | PASS    | 1 | 0.047 |   |
| [test-covrfuns.R](testthat/test-covrfuns.R#L5)         | check summary covr         | covr\_summary: standard input  | PASS    | 1 | 0.031 |   |
| [test-covrfuns.R](testthat/test-covrfuns.R#L9_L11)     | check summary covr         | covr\_summary: empty input     | PASS    | 1 | 0.002 |   |
| [test-covrfuns.R](testthat/test-covrfuns.R#L19)        | check summary output types | with data: short               | ERROR   | 0 | 0.008 |   |
| [test-covrfuns.R](testthat/test-covrfuns.R#L23)        | check summary output types | with data: long                | ERROR   | 0 | 0.010 |   |
| [test-covrfuns.R](testthat/test-covrfuns.R#L27)        | check summary output types | with data: no data             | ERROR   | 0 | 0.000 |   |
| [test-covrfuns.R](testthat/test-covrfuns.R#L35)        | check covr to df           | covr object to df: empty input | PASS    | 1 | 0.001 |   |

</details>

<details>

<summary> Session Info </summary>

| Field    | Value                               |
| :------- | :---------------------------------- |
| Version  | R version 3.5.1 (2018-07-02)        |
| Platform | x86\_64-apple-darwin15.6.0 (64-bit) |
| Running  | macOS High Sierra 10.13.6           |
| Language | en\_US                              |
| Timezone | America/New\_York                   |

| Package  | Version    |
| :------- | :--------- |
| testthat | 2.0.0.9000 |
| covr     | 3.2.0      |
| covrpage | 0.0.60     |

</details>

<!--- Final Status : error/failed --->
