# Option_Models
Excel templates and self-coded methods for deriving option values.


## Cox-Ross-Rubenstien Excel Model
Contains two models. One can adjust for up to 170 time steps while the other is a two step model.

The 170 time steps is due to a number size limitation in Excel surrounding 170 factorial.

[Link to Excel](https://docs.google.com/spreadsheets/d/12XWUjqbgzTlJuxgLns5KciBKrSm8FRY-/edit?usp=sharing&ouid=102432506864806831840&rtpof=true&sd=true)


## CRR Model R
This .Rmd file uses the method identified in the first Excel file to speed up European Call/Put CRR calculations. Similiar to the Excel file, R hits a number size limitation when computing the time steps up to (but not including) 270. 

To see an example output, view the pdf file of the same name.
