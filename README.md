# memo-xsv

https://github.com/BurntSushi/xsv

xsv headers truc.csv
xsv count truc.csv

xsv stats truc.csv | xsv table

xsv slice truc.csv -s 3173948 | xsv table

xsv sample 10 truc.csv | xsv table
xsv sample 10 truc.csv > test.csv

xsv select column1,column2 truc.csv > short_truc.csv

xsv frequency -s City worldcitiespop.csv --limit 5
