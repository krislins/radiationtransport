This simulation was created for an applied physics masters thesis. Radiation transport simulations were carried out in OpenMC and the human phantom was prepared in Cubit Coreform.

The jupyter notebook file contains the OpenMC code. 

The materials file contains all the materials found in the phantom. 
The source is an isotropic gamma source, either Co-60 or Cs-137. Both sources have the activity of 20 Ci. 
Volume flux tally is later converted into uSv/hr dose rate. 
Later particle tracks are converted into .vtk files that can be vizualised in ParaView. 

The human phantom can be downloaded from this dropbox link- https://www.dropbox.com/scl/fi/agvhxk20nauidvu5hi4li/AM.h5m?rlkey=oc706pkocpnvztts7wsw90cp8&dl=0
