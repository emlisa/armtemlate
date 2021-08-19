# armtemlate

This template creates a new logical server that will contain a zone redundant copy of an existing database. Specify the following values:\

Server name is the name of your new logical server.\
Database id is the id of the existing database you would like to make a copy of.\
Copydb name is the name of new zone redundant copy database.\
Location is the Azure region you would like your zone redundant copy database to reside in.\
Administrator login is the username for your new logical server.\
Administrator login password is the password for your new logical server.\

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Femlisa%2Farmtemlate%2Fmain%2Fcreatenewzrdb-copytonewserver.json)
