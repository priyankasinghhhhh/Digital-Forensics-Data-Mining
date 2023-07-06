# Digital-Forensics-Data-Mining
Our proposed model is the combination of digital forensics and data mining. Our proposed system helps to increase the security of the organization. When an incident reported, it investigates and report is saved in the database. Using crime data mining tool the nature of the attack is identified and alert administrator about similar attacks in future. Proactive measures can be initiated to prevent future cyber attacks. Figure shows the Block diagram of our proposed tool. 


 Block Diagram of the Proposed System Graphical User Interface: It is used by the forensic investigator to enter case details and apply tools (File system, Network) to collect evidences. Investigators can input their queries in the system. This also displays the result of the query in the form of Bar chart or report. It is the presentation layer of our three tier architecture.

•	File System Analyser: This tool Collects evidence from the file system, it recovers all files, searches data in the free space, slack spaces and deleted spaces.
•	 Network Analyser: This tool collects data from the network traffics and server log files. 
•	Database: Database loader collects evidences from the above tools and loader loads into the database as attributes of the tables. OLTP (Online Transaction Processing): Set relations between the tables of the detected crime attributes. This applies data mining and extracts of required data. OLAP (Online Analytical processing) apply analytical queries and retrieves the output/decisions. Database server helps to store and retrieve crime attributes and results. 
•	Decision Making System: This module applies data mining algorithm and also SQL queries into the database and generates reports. 

