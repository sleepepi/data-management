Data Entry Procedures and Conventions
=====================================

CONTENT
-------

* Data Naming Convention
	- File Naming
	- Choice Naming
	
Data Naming Conventions
-----------------------

* File Naming

	Files will be named as follows: study ID number, followed by the
	subject namecode, followed by the visit (ie. 00 for baseline, 02 
	for two-month, etc.), finally followed by the type of assessment 
 	(ie. PWV for Pulse Wave Velocity files, BP for electronic blood 
 	pressure files, etc.). 

* Choice naming

 	Option choices on all survey are coded with a set of certain
 	naming conventions. The convention is as follows: For all
 	'yes' or 'no' options, 'yes' is always coded as '1' and 'no'
 	is always coded as '0'. On forms for which there are multiple
 	possible choices, the options are numbered starting from '0'
 	and going to the highest number, with '0' representing the 
 	first option. For instances where a question may be regarded
 	as 'Not Applicable' to a certain subject, or the response may 
 	be missing, a series of missing codes are set, with '-8' 
 	representing 'Not Applicable' and '-9' representing values 
 	which are missing. '-10' is a separate missing code that is 
 	used for fields where the data enterer is confused (ie. 2 answer 
 	choices bubbled in, unclear markings, etc.). When arranging the
 	variable choices, missing codes are always placed at the bottom
 	of the options; this prevents 'clipping' of choices and questions
 	when importing data into a spreadsheet.