# HOMO and LUMO calculation
As with any molecule, we can define the Highest Occupied Molecular Orbital and Lower Unoccupied Molecular Orbital.
We can use an option of pp.x to visualize them, by plotting the charge density for a specific k-point and band

## Purpose
  1. Use pp.x to visualie the HOMO and LUMO of a molecule

## Runing the exercise
  1. Run the script 'run_pp' to perform the calculation of the 5th (HOMO) and 6th (Lumo) band for 2 different cellsize
      ```
      ./run_pp
      ```
  2. Use xcrysden to visualize the charge in the same way of exercise '0.3'
      ```
      xcrysden --xsf FILE_NAME
      ```
