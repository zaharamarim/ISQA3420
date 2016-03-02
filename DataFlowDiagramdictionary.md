#Data Flow Diogram Dictionary

### ntities:
###### Corporate Developer: a person develop a software.
######National Vulnerability Database: is an entity that hold vulnerable data.
######Corporate Manager: a person who lead the team project.
###Process:
######Mange Code Stream: is a processer that manage the files and packages come from the Corporate Developer. 
######Manage Project Information: is a processer that manage the project information.
######Manage CPE Information (Daily Job): process the data.
###Data Store:
######Risk DB: store vulnerable package and CPE information.
######NIST CPE Information: is a database where Mange Code Stream stored.
###Data Flow:
######File: sent by the Developer to Mange Code Stream processer.
######Package: sent by the Developer to Mange Code Stream processer.
######Package Query: sent by the Mange Code Stream processer to NIST CPE Information Data Store.
######CPE Information: sent by NIST CPE Information to Mange Code Stream processer.
######CPE File: sent by Manage CPE Information (Daily Job) to NIST CPE Information.
######CPE Request: is a request sent by Manage CPE Information (Daily Job) processer to National Vulnerability Database.
######CPE Response: is a response receive by Manage CPE Information (Daily Job) from National Vulnerability Database.
######Project Info Request: is a request sent by Corporate Manager to Manage Project Information.
######Project Info Response: is a response receive by Corporate Manager from Manage Project Information.
######Package Information Request: is a request sent by Manage Project Information processer to Risk DB.
######Package Information Response: is a response receive by Manage Project Information processer from Risk DB.
######Package and CPE Information: is Package and CPE Information sent by Mange Code Stream to Risk DB.<p/>
