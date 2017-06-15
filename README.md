Project - Logs Analysis

Launch Vagrant VM by running `vagrant up`, followed by `vagrant ssh`

To load the data, use the command `psql -d news -f newsdata.sql` to connect a database and run the necessary SQL statements.

The database includes three tables:
- Authors table
- Articles table
- Log table

To execute the program, run `python newsdata.py` from the command line.