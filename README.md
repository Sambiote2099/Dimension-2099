We used C++ to do this...

The edit, remove part is a bit complex...

What happens in the edit() & remove() is that 2 files are opened at the same time Data(Database.txt) & Data1(Database1.txt).
Then All the contents from Data(Database.txt) are transferred to Data1(Database1.txt).
After that Data(Database.txt) file is deleted & the Data1(Database1.txt) file is renamed into "Database.txt" from "Database1.txt". That way only 1 file exists at the end istead of two.
