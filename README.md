# DynamicsNavTools
Some useful Dynamics Nav Snippets

Codeunit 66500 
-LoggingFunction
 WriteLogFile(GETLASTERRORMESSAGE);
 
-Search unwanted or harmfull signes
 CheckTable(0,IndexOnly) 0 = All Tables, IndexOnly = Loggs in which Table,Record,Field a bad sign is
 
 -Check Tablerelation Structure for quality (You know TableRelations to Fields with other Lenghts or Datatypes) ;)
   CheckTableRelation(0) 0 = All Tables
