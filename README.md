# Reading-Carbon-Nanotubes-DataSet
Reading a dataset and write in a MySQL Database: Using MySql And Python  (Carbon Nanotubes Data Set)

 
Data Set Information:
CASTEP can simulate a wide range of properties of materials proprieties using density functional theory (DFT). 
DFT is the most successful method calculates atomic coordinates faster than other mathematical approaches, and it also reaches more accurate results. 
The dataset is generated with CASTEP using CNT geometry optimization. Many CNTs are simulated in CASTEP, then geometry optimizations are calculated. 
Initial coordinates of all carbon atoms are generated randomly. Different chiral vectors are used for each CNT simulation. 
The atom type is selected as carbon, bond length is used as 1.42 AÂ° (default value). CNT calculation parameters are used as default parameters. 
To finalize the computation, CASTEP uses a parameter named as elec_energy_tol (electrical energy tolerance) (default 1x10-5 eV) which represents that the change 
in the total energy from one iteration to the next remains below some tolerance value per atom for a few self-consistent field steps. 
Initial atomic coordinates (u, v, w), chiral vector (n, m) and calculated atomic coordinates (uâ€™, vâ€™, wâ€™) are obtained from the output files.


Attribute Information:
The summary of the attributes is given below. Please read the papers ([Web Link] and [Web Link]) for detailed descriptions of the attributes.

Chiral indice n: n parameter of the selected chiral vector.
Chiral indice m: n parameter of the selected chiral vector.
Initial atomic coordinate u: Randomly generated u parameter of the initial atomic coordinates of all carbon atoms.
Initial atomic coordinate v: Randomly generated v parameter of the initial atomic coordinates of all carbon atoms.
Initial atomic coordinate w: Randomly generated w parameter of the initial atomic coordinates of all carbon atoms.
Calculated atomic coordinate uâ€™: Calculated uâ€™ parameter of the atomic coordinates of all carbon atoms.
Calculated atomic coordinate vâ€™: Calculated vâ€™ parameter of the atomic coordinates of all carbon atoms.
Calculated atomic coordinate wâ€™: Calculated wâ€™ parameter of the atomic coordinates of all carbon atoms.

How to read a dataset and write in a SQL Database: Using MySql And Python
 (Carbon Nanotubes Data Set)



1. Connecting the database with MySQL and Python

2. Creating A Database

3. Creating new table to store the data

4. Taking the dataset from the UCI Machine Learning Repository and write it down inside a database




