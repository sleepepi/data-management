Data Entry Procedures and Conventions
=====================================

CONTENT
-------

* Data Naming Convention
	- File Naming
	- Choice Naming
* Processing of Data
* Storing of Data
* Collection and Verification of Data
* Querying of Data
* Data Scoring and Analysis

Data Naming Conventions
-----------------------

* File Naming

	Files will be named as follows: study ID number, followed by the
	subject namecode, followed by the visit (ie. 00 for baseline, 02 
	for two-month, etc.), finally followed by the type of assessment 
 	(ie. PWV for Pulse Wave Velocity files, BP for electronic blood 
 	pressure files, etc.). Data files will be stored logically under 
 	a data folder on the Sleep Medicine Epidemiology Program's 10 
 	terabyte server share, managed at the Needham Data Center site, 
 	organized by data type, subject, and visit.

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

 Storing of Data
 ---------------

 * Form Design

 	Forms are designed in a standard manner. The forms always contain 
 	a header section, generally consisting of patient-specific 
 	information (ie. study ID number, namecode, date of measurement,
 	etc.). This header section is then followed by the actual fields
 	on the form. Questionnaires are distributed and administered 
 	either in person at the visit, or via US mail with a prepaid 
 	return  envelope. Forms that are filled out at the time of the 
 	visit are stored in subject binders until the time of the visit. 
 	Electronic copies of all forms are stored on the Program's server 
 	share for study staff to access and download as needed. Older 
 	versions of forms are archived on the server with their date or 
 	version number appended to the title for ease of identification.

 Collection and Verification of Data
 -----------------------------------

 * Data Entry Process

 	Data is given to unblinded study staff members to enter 
 	electronically in a timely manner after visits. Most data is
 	entered and saved within 7 days of the study visit; all data is 
 	entered within 2 weeks of the visit date.

 * Data Verification Process

 	Data is verified in one of two ways:

 	1) Data is entered once by one study staff member, who would mark 
 	it as 'Ready to be reviewed' electronically and then is reviewed 
 	in a timely manner by a second study staff member and compared to 
 	the original data. The second staff memeber will then make any
 	necessary corrections and mark it as 'Completed' or 'Reviewed'.

 	2) In the second verification method, double data entry is 
 	utilized. Two staff members will enter identical data sets into 
 	the collection instruments, and a third staff member will then
 	compare the two entries for discrepancies, make corrections, and
 	then merge them into one complete, verified file.

 Querying of Data
 ----------------

 * Data Queries

 	Data queries are forwarded from staff members to members of the
 	Research Informatics department. SAS© is the primary program
 	utilized in data queries. Custom programs are written to analyze
 	electronically stored data for discrepancies including outlier
 	values, missing or unverified forms and data fields, and the 
 	overall state of data collection and entry. Reports are generated
 	from these programs and then distributed to the appropriate study
 	staff members, who then correct or verify the error. Reports are
 	then regenerated to verify the correction.

 Scoring and Analysis of Data
 ----------------------------

 * Data Scoring

 	Data is scored after it is entered and verified by study staff.
 	The primary tool for scoring is SAS© software. Programs are 
 	custom-designed for the individual measure and study, as to ensure
 	proper scoring and emphasis of results. Depending on the data 
 	collection software used by the study, scoring tools can also be
 	naturally integrated into the collection process.

 * Data Analysis

 	After being electronically and hand scored, the resulting data 
 	sets are then handed off to various staff members including the
 	study coordinator and statisticians who then analyze the data for
 	results.