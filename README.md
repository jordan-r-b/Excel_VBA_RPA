# Projects:

# Hungary_final

Business Problem: Need to convert various payroll forms, such as expense reports, into a flat file that can be read by the payroll vendor's bank. 

Excel macro for ETL which imports an .xls or .csv file from payroll system. Parse data into correct format for a flat file to be imported by third party payroll system. Multiple built in checks before user confirms export. Files are in Hungarian and must be removed. Converting the file to UTF-8 is insufficient as these characters would not be included.

Pressing button will ask for input of file. Export is for payroll system.

# Chile_Data_Analysis

Business Problem: Company was manually compiling data from different timekeeping reports to analyze and determine whether an employee was complying with attendance policy. This automates this analysis.

Excel macro will input report data, compile, and analyze.

# Replace_CZ_Diacritics

Business Problem: Payroll team was manually going in and removing diacritics from file as it would fail when importing into payroll system. This automates this process greatly increasing speed and accuracy. Diacritics in the Czech language are not included in UTF-8 and would not be processed properly if the file was simply converted. 

Highlight text and run the Excel macro. This will remove all diacritics.
