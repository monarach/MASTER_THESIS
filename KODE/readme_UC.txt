Uniaxial compression image files C:\Users\monar\Documents\PC Master\preliminary_tests\UC_tests
Every UC folder contains images from cam1 copied from hard drive provided by Vegard
Uniaxial compression image files --> DIC folder inside hard drive 

Folder: UC_1 <--- Uniaxial compression test 1
dic1 <--- contains subset and inputfile for dic 1.try
... dic9 <--- contains the last dic try that ran successfully
cam1 <--- images from camera 1 during experiment

DIC subset settings: 
- 6DOF linear and 2DOF ridgid
Subset size: 
- 250-300 (easier to track images)
- tried multiple subsets in "job", chose best subset. 
- only displacement from top plate is tracked 

Force-displacement data: 
Gathered in pixels v-direction (vertical)

Comments on tests/DIC: 
-specimens can be cut to avoid elephant foot
-all tests had the same pix/mm ratio except UC_9
-measurements of specimen length should be taken pre and post testing
-all DIC subtracking has been visually inspected prior to running subtracking to make sure no "jump" in tracking points

Subtracking observarions
UC_1: 
  - dic1 <--- subtracking ok
  - 6dof linear
  - pixel/mm: 1771pix/10mm

UC_2: 
  - dic1 <--- subtracking ok frameID [1,1388], FAILED [1389,1400]
  - dic2 <--- fail
  - dic3 <--- subtracking ok frameID [1,1388], FAILED [1389,1400]
  - 6dof linear
  - pixel/mm: 1771pix/10mm
Decided to export dic3 frame-disp file

UC_3: 
  - dic1 FAILED
  - dic2 <--- subrtacking __ frameID [1,1223], hopp i bildet frame 1224->1225, test ferdig (unload) ikke relevant
                      FAILED frameID [1224,:]
  - 2dof rigid
  - pixel/mm: 1771pix/10mm

UC_4:
  - dic1 <--- subtracking ok on all framesID's 
  - 2dof rigid
  - pixel/mm: 1771pix/10mm

UC_5
  - 2dof rigid
  - pixel/mm: 1771pix/10mm

UC_6
  - dic1 <--- subtracking ok all frames
  - 2dof rigid 
  - pixel/mm: 1771pix/10mm

UC_7
  - dic1 <--- subtracking ok all frames
  - 2dof rigid 
  - pixel/mm: 1771pix/10mm

UC_8
  - dic1 <--- subtracking ok all frames
  - 2dof rigid 
  - pixel/mm: 1771pix/10mm

UC_9
  - dic1 <-- subtracking ok all frames
  - 2dof rigid
  - pixel/mm: 1782pix/10mm
 
 