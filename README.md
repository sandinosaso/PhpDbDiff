PhpDbDiff
=========

A simple class for extracting the schema and performing the comparison between extracted schemas and a user interface to the class  Since we need to be able to access databases on different hosts, the solution I am using is to serialise the schema information and give it back to the user. The user is then required to copy and paste this data from separate instances back into a form so that the comparison can be performed.  The user interface provides the user with a list of pre-configured databases to choose from, and also allows the user to enter connection details in the form.