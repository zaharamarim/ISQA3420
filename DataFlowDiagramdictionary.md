#Data Flow Diagram Dictionary

### ntities:
######Corporate Developer: a person develop a software.
######National Vulnerability Database: is an entity that hold vulnerability data.
######Corporate Manager: a person who lead the team project.
######Hardware Software System Interfaces Data and Informatiom People System: is an entity that hold data and information. 
###Process:
######Mange Code Stream: is a process that manage the files and packages come from the Corporate Developer. 
######Manage Project Information: is a process that manage the project information.
######Manage CPE Information (Daily Job): process the data.
######Risk Determination: is a process that determine the database risk.
######Control Recommendation: is a process that recommend data from risk database.
######Vulnerability Identification: in a process that identify a package vulnerabilities.
###Data Store:
######Risk DB: store vulnerability packages and CPE information.
######NIST CPE Information: is a database where Mange Code Stream stored.
###Data Flow:
######File: sent by the Developer to Mange Code Stream process.
######Package: sent by the Developer to Mange Code Stream process.
######Package Query: sent by the Mange Code Stream processer to NIST CPE Information Data Store.
######CPE Information: sent by NIST CPE Information to Mange Code Stream process.
######CPE File: sent by Manage CPE Information (Daily Job) to NIST CPE Information.
######CPE Request: is a request sent by Manage CPE Information (Daily Job) process to National Vulnerability Database.
######CPE Response: is a response receive by Manage CPE Information (Daily Job) from National Vulnerability Database.
######Project Info Request: is a request sent by Corporate Manager to Manage Project Information.
######Project Info Response: is a response receive by Corporate Manager from Manage Project Information.
######Package Information Request: is a request sent by Manage Project Information processer to Risk DB.
######Package Information Response: is a response receive by Manage Project Information processer from Risk DB.
######Package and CPE Information: is Package and CPE Information sent by Mange Code Stream to Risk DB.
######Input: carry a request sent to Corporate Developer.
######List of Potential Vulnerabilities: is a request sent by National Vulnerability Database to  Vulnerability Identification.
######CPE Control: is a request sent by Risk Determination to Control Recommendation
######Data Request: is a request sent by Risk DB to Risk Determination.
