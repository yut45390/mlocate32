
Cloned from repository at github "kobake/mlocate32"
on 29 May 2017

* changes to use visual studio 2017 community edition
open the locate32 project
Properties >> configuration properties >> general>>
Windows SDK Version
change from 8.1 to 10.0.14393.0

* change to where boost was built
properties >> configuration properties >> vc++ directories>>
include directories
Add c:/sources/boost_1_64_0

* change location of libraries
properties >> configuration properties >> linker >>
Additional library directories
Add c:\sources\boost_1_64_0\stage\lib

* retarget for vs 2017
right click on project "locate32" >> "retarget project" >>
select 10.0.14393.0

right click on project "updatedb32" >> "retarget project" >>
select 10.0.14393.0

