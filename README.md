# V6_ENGINE
Designing a detailed V6 engine in SolidWorks from scratch using real references, modeling all components, and simulating crank-piston motion to analyze the V-angle’s impact.
-----------------------------------------
🗓️ Date: [19 June]  
⏱️ Time Spent: [30min]  
📍 Part: [Crankshaft]

🛠️ What I did:
- [1.Create a circle of radius 63.5 and extrude it to (54.62/20
   2.Then choose one of its face and sketch on it another circle bigger than previous one by 12.7
   3.Create one more circle(88.9mm) on top of them and use lines to complete the profile
   4.Trim entities get the external profile extrude it to 19mm
   5.Draw another circle on it radius 76.2 extrude it by 53.34/2
   6.Mirror it]

⚠️ Issues Faced:
- [we use the 3 point arc to get a sleeker design and we need to finish the sketch because only finished and closed sketches can be extruded]

📸 Screenshot Saved As: [Not done yet]  
💾 File Saved As: [Part2.sldprt]

🔜 Next Step:
- [Finishing the crankshaft]

---------------------------------------------------------------------------------------------------------------------------------------

🗓️ Date: [21 June]  
⏱️ Time Spent: [ 1 hour 30 mins]  
📍 Part: [Crankshaft ,Piston HEAD]

🛠️ What I did:
- [1.Use linear pattern feature
   2.Use reference geometry to create a centreline which would decide how the crankshaft rotates.
   3.Rotate the linear pattern in reverse directions by 120 deg.
   4.For the piston we are choosing the front plane we create the profile and use the revolved base/boss feature.
   5.Using this creates the hollowed out cylinder in one step and then we sketch a rectangle on the front plane itself to create the cutout portion.
   6.Use 19mm as the axis of revolution and material is present till 19mm below which it is hollowed out.
   7.3.81 is the thickness of the piston ring and 2.54 is how deep it is.]

⚠️ Issues Faced:
- [1.Why didn't he use mirror instead of linear pattern
   2.Instead of using reference geometry we can also choose a plane create centreline and all that we did while creating the 4 cylinder engine.]
   3.Why did we use 120 deg and not 180 deg?]
  
📸 Screenshot Saved As: [crank_shaft_img.jpg,piston_head_img.jpg]  
💾 File Saved As: [CRANKSHAFT.sldprt,PISTON HEAD.sldprt]

🔜 Next Step:
- [Connecting rod]

------------------------------------------------------------------------------------------------------------------------------------------

🗓️ Date: [22 June]  
⏱️ Time Spent: [45 MINS]  
📍 Part: [Connecting Rod]

🛠️ What I did:
- [1.Sketch two circles on the front plane one is of dia 76.20 and other of 50.80,this end fits on the main journal hence the dia of 76.20
   2.Sketch two other circles of radii 44.4 and 31.75 this is where the connecting rod cap will be connected]

⚠️ Issues Faced:
- [1.I couldn't make the two lines equal because i was adding two many coincident relations and also when you begin sketching the two lines they should start from same x coordinate i don't know why
   2.I don't understand how to see the filler dimensions]

📸 Screenshot Saved As: [connecting_rod_img.jpg]  
💾 File Saved As: [CONNECTING ROD.sldprt]

🔜 Next Step:
- [What you plan to work on next]

------------------------------------------------------------------------------------------------------------------------------------------

🗓️ Date: [22 June]  
⏱️ Time Spent: [2 hour 15 mins]  
📍 Part: [ Connecting Rod Cap,Piston Pin,Piston assembly,Engine block]

🛠️ What I did:
- [1.Create two center points arc of radii 44.45 and 31.75mm
   2.Using the offset feature in extrude cut to get the tapered cut,is there any other way to do it
   3.Assemble the piston
   4.For engine block,the radii of arc is 63.5 which is also the radii of piston head
   5.To create the cut we first convert entities of the extruded face and then use offset entities]
 
⚠️ Issues Faced:
- [1.I don't have hole wizard
   2.Why did we fillet edge 3 and edge 4 after filleting edge 1 and edge 2 and not just together,why was there an error
   3.What is the rib feature
   4.It is a bit tricky to understand dimensions from drawing for the engine block]

📸 Screenshot Saved As: [connecting_rod_cap_img.jpg,piston_pin_img.jpg,piston_img.jpg,engine_block_img.jpg]  
💾 File Saved As: [CONNECTING ROD CAP.sldprt,PISTON PIN.sldprt,PISTON.sldprt,ENGINE BLOCK.sldprt]

🔜 Next Step:
- [Rocker arm]

------------------------------------------------------------------------------------------------------------------------------------------

🗓️ Date: [23 June]  
⏱️ Time Spent: [Duration, e.g., 1 hour]  
📍 Part: [Rocker arm]

🛠️ What I did:
- [Created the parts for rocker arm assembly]

⚠️ Issues Faced:
- [1.I could select the two rectangles and make them equal when i choose the plane on body but now when i chose the top plane idk why]

📸 Screenshot Saved As: [e.g., piston_done.png]  
💾 File Saved As: [e.g., piston_v1.sldprt]

🔜 Next Step:
- [Assembly]

------------------------------------------------------------------------------------------------------------------------------------------
🗓️ Date: [24 june]  
⏱️ Time Spent: [ 1 hour]  
📍 Part: [Assembly of Rocker arm,Cylinder head]

🛠️ What I did:
- [Brief bullet list of actions you took
   Lofted cut]

⚠️ Issues Faced:
- [1.I don't have the toolbox so i used traceparts to download the screw file.
   2.understanding lofted cut
   3.I couldn't make the linear pattern because i didn't turn on the geometry pattern]

📸 Screenshot Saved As: [cylinder_head_img.jpg,rocker_arm_assembly_img.jpg]  
💾 File Saved As: [ROCKER ARM ASSEMBLY.sldasm,CYLINDER HEAD.sldprt]

🔜 Next Step:
- [Finishing the cylinder head]

------------------------------------------------------------------------------------------------------------------------------------------

🗓️ Date: [25 june]  
⏱️ Time Spent: [Duration, e.g., 1 hour]  
📍 Part: [Exhaust Manifold]

🛠️ What I did:
- [1.Corner rectangle of dimensions 63.50 and 387.35 then on its face sketch another rectangle of dimensions 31.75 into 38.10,we created similar rectangle in cylinder head while creating loft cut
   2.146.05 is the distance we have been using while creating linear patterns ]
   3.Use ellipse and trim entities to create cutouts of desired shape
   4.Create a circle of dia 38.10 at a distance of 63.5 from the sketch in the left plane
   5.Create two reference planes from the right plane at a distance of 146.05 using offset under reference geometry
   6.Open plane 1 and make a circle of dia 54.9 concentric with the previous circle and then open plane 2 and make a circle of dia 57.15
   7.Use the boundary boss/base feature,tangency to face and normal to profile
⚠️ Issues Faced:
- [Any problems or confusion you encountered and fixed]

📸 Screenshot Saved As: []  
💾 File Saved As: []

🔜 Next Step:
- [What you plan to work on next]




