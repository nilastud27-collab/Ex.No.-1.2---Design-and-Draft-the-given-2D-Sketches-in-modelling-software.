# Ex.No.-1.2-Design and Draft the given 2D Sketches in modelling software.

## AIM
 To sketch the given drawing with dimensions using fusion 360 tool.
 
## REQUIREMENTS
 1. Autodesk fusion 360
 2. Windows 10
 3. 16 GB of RAM (integrated graphics recommend 1 GB or more)
 4. 2.5 Mbps or faster download; 500 Kbps or faster upload 
 
 ## PROCEDURE
## Step 1: Document Setup & Initializing Sketch 
1. Launch Autodesk Fusion 360. 
2. Save the project with a relevant name (Exercise 1.2). 
3. Set the default units to Millimeters (mm) in the Browser tree 
under Document Settings. 
4. Click on Create Sketch in the Solid toolbar and select the XY 
Plane (Front plane) to begin drawing.

<img width="462" height="465" alt="Screenshot 2026-10-08 205244" src="https://github.com/user-attachments/assets/09e343b1-c778-4da7-94d5-c9f50c0d21b6" />

## Step 2: Drawing the Center Hub Feature 
1. Select the Center Diameter Circle tool (Shortcut: C). 
2. Click on the origin  
(0, 0)
circles: 
and draw the following concentric 
○ Inner Core Hole: Diameter 32 mm (Radius 21 × 2𝑅16 × 2)
○ Slot Inner Boundary: Diameter 42 mm (Radius 32 × 2
○ Slot Outer Boundary: Diameter 64 mm (Radius ). 
○ Outer Hub Profile: Diameter 80 mm (Radius 40 × 2)

 <img width="555" height="462" alt="Screenshot 2026-10-08 205438" src="https://github.com/user-attachments/assets/f76ca79d-7e7c-48e2-a0e6-5c9458f5cb1f" />

## Step 3: Creating the Circular Hub Slots 
1. Select the Line tool (Shortcut: L) and create vertical and horizontal 
construction lines passing through the origin. 
2. Select the Offset tool (Shortcut: O) and offset the vertical and 
horizontal construction lines by 3 mm on both sides to achieve the 
total slot web width of 6 mm or mirror the one side 3mm line with 
having a centre line. 
3. Use the Trim tool (Shortcut: T) to remove the unwanted segments 
of the circles and offset lines, forming the six symmetrical curved 
slot segments inside the inner ring.

 <img width="637" height="542" alt="Screenshot 2026-10-08 213424" src="https://github.com/user-attachments/assets/5760cd90-737d-42f8-a9e8-f2c1913b8fcf" />

## Step 4: Sketching the Symmetrical Outer Lugs (Holes) 
1. Select the Center Diameter Circle tool (C) to draw the inner 
holes of the outer lugs: 
○ Top & Bottom Lugs (4 total): Positioned at coordinates. Draw circles with a diameter of 30 (𝑋 =± 50,𝑌 =± 60)mm (Radius 15 × 2). 
○ Side Lugs (2 total): Positioned along the X-axis at coordinates  (calculated as 50𝑚𝑚 + 20𝑚𝑚𝑅15 × 2(𝑋 =± 70,𝑌 = 0).Draw circles with a diameter of 30 mm (Radius ). 
2. Draw the outer profiles around these centers: 
○ Concentric circles of radius R21 (Diameter 42 mm) 
around the four top and bottom centers. 
○ Concentric circles of radius R20 (Diameter 40 mm) 
around the two side centers. 

<img width="273" height="532" alt="Screenshot 2026-10-08 213524" src="https://github.com/user-attachments/assets/62cdb722-abfe-4035-a92d-2dd58c825515" />

## Step 5: Defining Outer Connectors & Fillets 
1. Select the Line tool (L) and draw straight lines connecting the outer boundary of the top/bottom lugs (𝑅21boundary of the side lugs to the outer 20)
2. Apply the Tangent Constraint between these straight lines and both sets of outer circles to ensure smooth transitions. 
3. Select the 2-Point Arc or Fillet tool to add the internal 
blending arcs: 
○ Create inner blending fillets of radius R20 between the outer hub and the top/bottom outer lug extensions
4. Apply the Equal Constraint where necessary to mirror the geometry automatically across the quadrants. 

## Step 6: Final Cleaning and Dimensioning 
1. Use the Trim tool (T) to carefully cut away all overlapping 
internal overlapping arcs, ensuring a single closed profile body 
is formed. 
2. Apply the Sketch Dimension tool (Shortcut: D) to add all 
constraints as shown in the blueprint image to verify the 
sketch is Fully Constrained (all sketch lines turn from blue to 
black). 
3. Click Finish Sketch in the top right corner.

## Step 7: Extruding into a 3D Model 
1. Switch to the Solid tab in the top menu bar. 
2. Click the Extrude tool icon (Shortcut: E). 
3. Select the closed profile zones of the sketch by clicking inside 
the main orange body areas. 
4. Leave the 6 bolt holes and the central slot cutouts 
unselected so they automatically become hollow openings. 
5. In the Extrude dialog box, enter your desired thickness value 
in the Distance field (20mm). 
6. Ensure the Operation dropdown menu is set to New Body.
7.Click OK or press Enter to finalize and generate the complete 3D mechanical component.

<img width="320" height="422" alt="Screenshot 2026-10-22 121133" src="https://github.com/user-attachments/assets/60420b35-05ab-45a0-b987-137d26493c49" />
<img width="825" height="651" alt="Screenshot 2026-10-08 192844" src="https://github.com/user-attachments/assets/4dbc279f-edc9-4c2e-b43d-94d0b6feaac5" />

 ## SKETCH
 ![image](https://user-images.githubusercontent.com/113594316/198233336-dd9f5c19-481b-486a-928a-99c32a732f89.png)

 ## OUTPUT
 <img width="862" height="677" alt="EXERCISE 1 2 sketch" src="https://github.com/user-attachments/assets/4cc7b8c0-4302-4c9a-b2e7-2cf6b7352314" />
 <img width="1016" height="717" alt="Exercise 1 2 Drawing" src="https://github.com/user-attachments/assets/13f0b245-fd91-4388-9b28-24bc2950ebb5" />

## RESULT
 The 2D mechanical engineering sketch was 
successfully drawn, constrained, and drafted inside 
Autodesk Fusion. The blueprint coordinates perfectly 
with the given technical design dimensions, 
maintaining true geometric symmetry across all axes.

ILANILA VINNARASI.K.V
26017175
08.10.2026
