FuelPHP Orm Model Generation Task
=================================

This is a FuelPHP Task that generates a/multiple Orm Models from a database.

The models are populated with as many properties and other setup as possible (more may be added), unlike `oil generate model` which only puts in the basics.


If the Task detects that it would be overwriting a file then it prompts you for confirmation, so that you do not loose any models you have already written.

Usage
-----
To generate models for all of the tables in your database

	php oil migrate orm 


To generate a model for just one table

	php oil migrate orm:generate_model table_name
