# SWDB_2022
![SWDB_2022](/resources/cropped-SummerWorkshop_Header.png)

This is the repository for the course materials for the 2022 Summer Workshop on the Dynamic Brain. But it's my fork!

# Environment Setup
If you using the jupyterhub we have setup for you, you don't need to do anything, just [login](https://allen-swdb.2i2c.cloud/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2FallenInstitute%2Fswdb_2022&urlpath=lab%2Ftree%2Fswdb_2022%2F&branch=main) and you should be able to start working. 

To setup an environment using conda that has all the packages you need to run this repository, first install [anaconda](https://www.anaconda.com/products/distribution). If on an a mac, install the intel version rather than the M1 version as some dependancies are not yet updated to support M1 compilation. 

Then open a terminal (on Windows, open the command prompt from Anaconda navigator). Navigate to this repository directory using cd. 

If you are using the repo on the harddrive on Windows (say Brain2022 shows up as E: on your computer), type 
```
E:
cd swdb_2022
```

If on a Mac, open a terminal and type
```
cd /Volumes/Brain2022/swdb_2022
```

On Linux, open a terminal and type
```
cd /media/$USERNAME/Brain2022/swdb_2022
```

Then, on any platform run:
```
conda env create --name swdb2022 --file=environment.yml
```

# Support Policy

We are releasing this code as part of the 2022 Summer Workshop on the Dynamic Brain and will only be supporting and developing it for the context of this workshop. The community is welcome to submit issues, but you should not expect an active response outside of the context of the course.

Copyright 2022 Allen Institute
