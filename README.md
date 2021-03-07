# PandemicsSSIS
SQL Server &amp; SSIS Pandemics Study


In this projet, I have created a Visual Basic SSIS Project file to merge three different tables with Pandemic data - h1n1, COVID, and SARS - into a final master table in SQL Server. An inner join was made with the "Country" column as the primary key between all three data sets  - first the initial two tables, and then between the resulting table and final data set. The final result was exported to SQL Server via the final SSIS step, and thereafter SQL queries were run in order to make an informed comparisons between the outbreaks. A detailed overview of the project and the queries can be seen in the Pandemics SSIS.docx file. In order to replicate the dtsx SSIS project, new connection managers must be made in order to ensure a correct path 
