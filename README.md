# Synopsis

Warning: Large images.

This contains examples of my data Extract-Transform-Load (ETL) experience. These tools are automated and mapped out visually to show you the scope of just one automation.

# Redpoint Architecture.png - Description

Each node is a single function. Each line represents a path for data to be piped to the next function. This language is not object oriented.

The input for this automation is a list of names and addresses that have not been sanitized. They arrive to us from 15 different sources, including mostly outside vendors. The output is a data file which can be used to accurately contact donors by direct mail, and track the results of the mailing. The data is ready-to-print after it completes this process.

This process also creates reports which can be read to determine exactly what was changed, where it was changed, and what it used to be. No data is lost.
