# VIGANI
Auto navigation system for a survey robot

## SETUP
1. Read Way Points from SD Card
2. Get Home

## LOOP
1. Get Next Destination Way Point (DWP) if NONE goto 8
2. Check Current Location 
3. Compare Current Location to Destination Way Point 
4. Calculate the DWP Heading Degree
5. Calculate the Distance to DWP
6. Start/Continue Navigation for the Way Point
7. If Current Location is within a 3m radius of DWP find next way point, and loop through 3.
8. Go to HOME
