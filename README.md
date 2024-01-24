This simulation was created for an applied physics masters thesis. Radiation transport simulations were carried out in OpenMC and the human phantom was prepared in Cubit Coreform.

The jupyter notebook file contains the OpenMC code. 

The materials file contains all the materials found in the phantom. 
The source is an isotropic gamma source, either Co-60 or Cs-137. 
Volume flux tally is later converted into uSv/hr equivalent dose rate. 
Later particle tracks are converted into .vtk files that can be vizualised in ParaView. 

For further interest, please ask for the phantom in email- krislin.sartakov@gmail.com
