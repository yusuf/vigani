# VIGANI
Auto navigation system for a survey robot

## SETUP
1. Read Way Points from SD Card
2. Get Home
## LOOP
3. Get Next Destination Way Point (DWP) if NONE goto 10
4. Check Current Location 
5. Compare Current Location to Destination Way Point 
6. Calculate the DWP Heading Degree
7. Calculate the Distance to DWP
8. Start/Continue Navigation for the Way Point
9. If Current Location is within a 3m radius of DWP find next way point, and loop through 3.
10. Go to HOME