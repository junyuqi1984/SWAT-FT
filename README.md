# SWAT-FT
Modified file:	
modparm.f		
allocate_parms.f		
clicon.f		
readfile.f		
subbasin.f		
surface.f		
virtual.f		
zero2.f		
		
Added file:		
soltemp.f	see subbasin.f	new soil temperature module
soltphys_in.f	see soltemp.f	
solthermal.f	see soltemp.f	
soltly.f.f 	see soltemp.f
soltbott.f	see soltemp.f	
soltsurf.f	see soltemp.f
soltcal.f	see soltemp.f	
soltphys_out.f	see soltemp.f
soltout.f	see soltemp.f	
soltfretha.f	see soltcal.f	
snom1.f	see surface	new snow module
hruday1.f	see virtual.f	for output
hrudayt.f	see virtual.f	for output
subday1.f	see virtual.f	for output
		
search " Junyu Qi" or "SWAT-FT" for changes		

Borrow exsiting parameters to calibrate soil temperature see soltemp.f:
pot_tilemm
pot_nsed
pot_volxmm
pot_volmm

Please cite : Qi, J., Li, S., Li, Q., Xing, Z., Bourque, C.P.A. and Meng, F.R., 2016. A new soil-temperature module for SWAT application in regions with seasonal snow cover. Journal of Hydrology, 538, pp.863-877.
