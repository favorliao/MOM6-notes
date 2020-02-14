## MOM6 Grid  
```
MOM6 hgrid description  
```
[https://gist.github.com/adcroft/c1e207024fe1189b43dddc5f1fe7dd6c](https://gist.github.com/adcroft/c1e207024fe1189b43dddc5f1fe7dd6c)

MOM6 Cgrid (H point and C point) description
[https://mom6.readthedocs.io/en/latest/api/generated/modules/mom_grid.html](https://mom6.readthedocs.io/en/latest/api/generated/modules/mom_grid.html)

## MOM6 input files   
[ftp://ftp.gfdl.noaa.gov/perm/Alistair.Adcroft/MOM6-testing/](ftp://ftp.gfdl.noaa.gov/perm/Alistair.Adcroft/MOM6-testing/)



## MOM6 diagnostics (Output)
MOM6 diagnostics configurations  
The strings %yr, %mo, %dy, %hr %mi, %sc are expanded to the current year, month, day, hour, minute and second respectively   

[https://mom6.readthedocs.io/en/latest/api/generated/pages/Diagnostics.html](https://mom6.readthedocs.io/en/latest/api/generated/pages/Diagnostics.html)


## Freshwater flux varialbes 
```
"PRCmE" = precip(lprec+fprec)+evap(-1)+lrunoff+frunoff+vprec+seaice_melt
"precip" = liquid precpitation + frozeon precipitation
"evap" : (-1)*fresh water flux evaporated out of the ocean
"vprec" virtual liquid precip associated w/ SSS restoring
"frunoff": Frozen runoff (calving) and iceberg melt into ocean
"lrunoff": liquid runoff
"seaice_melt" can not be saved by MOM6, need to update code
```
