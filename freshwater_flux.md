"PRCmE" = precip(lprec+fprec)+evap(-1)+lrunoff+frunoff+vprec+seaice_melt

"precip" = liquid precpitation + frozeon precipitation. 
"evap" : (-1)*fresh water flux evaporated out of the ocean.    
"vprec" virtual liquid precip associated w/ SSS restoring. 
"frunoff": Frozen runoff (calving) and iceberg melt into ocean.  
"lrunoff": liquid runoff.  
"seaice_melt" can not be saved by MOM6, need to update code.  
