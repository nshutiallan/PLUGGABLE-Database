 creating-PDB-database
  PDB Management in Oracle Database

This project involves creating and deleting Pluggable Databases (PDBs) using SQL queries and Oracle Enterprise Manager.

 Steps:
1. Creating a Pluggable Database (PDB)
   - Query:
   CREATE PLUGGABLE DATABASE plsql_class2024db
ADMIN USER al_plsqlauca IDENTIFIED BY allan21c
FILE_NAME_CONVERT = ('/path_to_your_cdb/', '/path_to_your_pdb/');

  CREATE PLUGGABLE DATABASE plsql_class2024db
ADMIN USER al_plsqlauca IDENTIFIED BY allan21c
FILE_NAME_CONVERT = ('/path_to_your_cdb/', '/path_to_your_pdb/');

   - Explanation: This query creates a PDB with an administrative user.

2. Deleting a Pluggable Database (PDB)
   - Query:
     DROP PLUGGABLE DATABASE pdb_name INCLUDING DATAFILES;
   
   - Explanation: This query deletes the PDB and its associated data files.
 
 Oracle Enterprise Manager
Screenshot: (add your screenshot links here)

![Screenshot 2024-09-29 181615](https://github.com/user-attachments/assets/e11910de-459e-4cf1-97c9-1eac9ed569c8)
![Screenshot 2024-09-29 181031](https://github.com/user-attachments/assets/a7a3e840-b9da-40e3-9cd8-b6d2d9ee8dfd)
![Screenshot 2024-09-29 184646](https://github.com/user-attachments/assets/e85a891e-e411-4674-802a-eac248516c27)
![Screenshot 2024-09-29 182034](https://github.com/user-attachments/assets/13a7cbf0-e503-42a0-9bf4-dff0475f1de8)
