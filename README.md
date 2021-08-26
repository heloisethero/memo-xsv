# memo-xsv

https://github.com/BurntSushi/xsv

## Basic tricks

xsv headers truc.csv

xsv count truc.csv

xsv stats truc.csv | xsv table

xsv slice truc.csv -s 3173948 | xsv table

xsv sample 10 truc.csv | xsv table

xsv select column1,column2 truc.csv > short_truc.csv

xsv frequency -s City worldcitiespop.csv --limit 5


## To count the number of unique values of each column

xsv stats ./data/posts_condor_groups_1.csv --everything | xsv select field,cardinality
