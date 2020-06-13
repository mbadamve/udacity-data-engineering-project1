# Project Description:

The project aims to perform ETL operations on various collections of song and log files to create a PostgreSQL database called Sparkify. There are 1 data folder, 2 jupyter notebooks, 3 python files and a README markdown file in the directory. Below is an explanation of each file usage in this project.

1. data - folder containing song and log files that are generated
2. create_tables.py - python file that contains code for creating the Sparkify database.
3. sql_queries.py - python file that contains drop, create and insert SQL commands to be performed on the database.
4. etl.py - python file that contains etl functions and operations to perform on each file in the data folder.
5. etl.ipnyb - jupyter notebook that shows step-by-step detailed information of how data can be loaded and the packages required to perform these operations in Jupyter.
6. test.ipnyb - jupyter notebook that lets the user test if tables and insertion operations are properly done.

## Dependencies:

1. Python 3.7+ and above.
2. IDE that runs Jupyter notebook
3. Packages inside the Jupyter the notebook especially psycopg2.
4. After the packages are pre-installed, then they are imported in the notebook as per usage.

Order of running the python files:
sql_queries.py >> create_tables.py >> etl.py

If the order is missed by mistake, then the kernel needs to be restarted to avail a fresh connection to PostgreSQL database.

## How to run python scripts in Jupyter:
1. In Jupyter, click on File>New>Terminal. It creates new terminal in the workspace.
2. run the command **python file_name.py** in the command line. For example, **python etl.py** runs the etl python scripts and when the operation is completed, you can run another script in the same terminal.

Note: Any changes in the python files made will be processed only by restarting the kernel. and running them again.

For easy flow, please follow this order of running the files.
**sql_queries.py >> create_tables.py >> etl.ipnyb >> test.ipnyb >> etl.py**