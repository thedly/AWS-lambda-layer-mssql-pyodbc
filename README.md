# lambda-layer-mssql-pyodbc
A python 3.8 layer which can be included in the AWS lambda function to connect to Oracle databases. It contains the pyodbc library which will be used as a dialect by SqlAlchemy and the sql server client files zipped together. This is compatible with python >= 3.8 which will use sqlalchemy to connect to sql server database. Feel free to use the layer directly.
