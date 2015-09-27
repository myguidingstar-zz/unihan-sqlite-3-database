This system is based on the _SQLite 3_ relational database engine. It uses the `Unihan.txt` _tagged_ database from _Unicode.org_ and an awk script (which uses _gawk_ extensions) to create a normalized _SQLite 3_ database which can then be used either interactively, or by executing _SQLite 3_ script files to obtain table data which can then be imported into spreadsheets or other DBMS systems.

Since there are bindings for _SQLite 3_ for a number of popular computer languages, this project could also contain Python, PHP, Perl and other scripts or systems to further parse and/or analyze the data contained in the Unihan database.

More details can be obtained in the file, `project.txt`.