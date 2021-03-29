## Welcome to my EE repository
My Research Question:
> To what degree do the mass and density of a planet affect the eccentricity of its orbit?

This repository contains:
>6 csv files containing data tables
>1 "script" Python file that processes the data
>uhhhh lots of brain cell remnants :)
    
Comments from data.csv:
```# This file was produced by the NASA Exoplanet Archive  http://exoplanetarchive.ipac.caltech.edu
# Tue Feb 16 21:55:27 2021
#
# User preference: *
#
# CONSTRAINT:  order by sy_snum asc
#
# COLUMN pl_name:        Planet Name
# COLUMN sy_snum:        Number of Stars
# COLUMN sy_pnum:        Number of Planets
# COLUMN discoverymethod: Discovery Method
# COLUMN disc_year:      Discovery Year
# COLUMN pl_bmasse:      Planet Mass or Mass*sin(i) [Earth Mass]
# COLUMN pl_bmassj:      Planet Mass or Mass*sin(i) [Jupiter Mass]
# COLUMN pl_dens:        Planet Density [g/cm**3]
# COLUMN pl_orbeccen:    Eccentricity
# COLUMN sy_dist:        Distance [pc]
```

various other comments:
```
# with open(rad_vel_csv,'r') as f:
#     [print(line.split())for line in f]


# with open(rad_vel_csv,'w') as f:
#         for i,line in enumerate(table.discoverymethod):
#             if line=="Radial Velocity":
#                 r = table.loc[i].disc_year
#                 print(str(r))

# with open(rad_vel_csv,'w') as f:
#     for i,line in enumerate(table.discoverymethod):
#         row=[]
#         if line=="Radial Velocity":
#             row.append(str(table.iloc[i, [0, 1]]))
#             f.write(str(row)+"\n"*3)

# for i, method in enumerate(table.pl_bmasse):
#     if method >=200000.:
#         print(table.loc[i])
```
