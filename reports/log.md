# Public Use Dataset Verification Scanning Log

## 2020-08-31

```
[1] "../data/raw/COVID_Cases_Public_Limited_08312020.csv"
[1] "Existing suppression summary:"
                        na_count na_percent
race_ethnicity_combined        6      0.00%
sex                           18      0.00%
age_group                     94      0.00%

SDC summary for k-anon-level( 5 ).
The input dataset consists of 3662325 rows and 11 variables.
  --> Categorical key variables: race_ethnicity_combined, sex, age_group
----------------------------------------------------------------------

Information on categorical key variables:

Reported is the number, mean size and size of the smallest category >0 for recoded variables.
In parenthesis, the same statistics are shown for the unmodified data.
Note: NA (missings) are counted as seperate categories!


            Key Variable Number of categories       Mean size              Size of smallest (>0)     
 race_ethnicity_combined                    9  (9) 406925.000 (406925.000)                     6  (6)
                     sex                    6  (6) 610387.500 (610387.500)                    18 (18)
               age_group                   11 (11) 332938.636 (332938.636)                    94 (94)
----------------------------------------------------------------------

k-anon violations ( 0 ) for k=( 5 ) and quasi identifiers( race_ethnicity_combined sex age_group ). If greater than zero violations then here's 5 violations.

Writing out a privacy eval report to: ../reports/COVID_Cases_Public_Limited_08312020.csv.html 

Processing l-diversity ( 2 ) checks for < ../data/raw/COVID_Cases_Public_Limited_08312020.csv > that has < 3662325 > records; < 11 > variables; < 3 > quasi-identifiers ( race_ethnicity_combined sex age_group ); and < 1 > confidential attributes ( pos_spec_dt ).
checking l-diversity manually for < pos_spec_dt >, found < 0 > l-diversity violations.
[1] race_ethnicity_combined sex                     age_group               pos_spec_dt             fk                      ldiv                   
<0 rows> (or 0-length row.names)
```