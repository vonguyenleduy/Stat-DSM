# Stat-DSM
Stat-DSM: Statistically Discriminative Sub-Trajectory Mining With Multiple Testing Correction


## Requirements to run the code

Knowledge about database management system, i.e., PostgreSQL, is required


1. Install and setup PostgreSQL

2. Create the database 
   - Please refer to the file "data_structure_for_hurricane_data.txt" for the details
   
3. Import data to the created database in Step 2
   - The dataset used in this code is Hurricane dataset (1 vs 4), which can be found at 
https://bitbucket.org/anfer86/acmsac2018_movelets/src/master/datasets/ACMSAC2018/E1/

4. Modify Line 14 of the file "stat_dsm.py" with the "user" and "password" of your database

5. Run the code
   ```
	>> python stat_dsm.py
	```
   The output of this code is the adjusted significance level.