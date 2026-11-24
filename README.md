# EX. No. 2.2 – CREATE A 3D SOLID MODEL FROM ISOMETRIC DRAWING

## DATE:

## AIM

To create a 3D solid model from the given isometric drawing using Autodesk Fusion 360.

## REQUIREMENTS

1. Autodesk Fusion 360
2. Windows 10
3. 16 GB RAM (integrated graphics: 1 GB or more recommended)
4. 2.5 Mbps or faster download speed and 500 Kbps or faster upload speed

## PROCEDURE

### STEP 1: Start a New Sketch

1. Open Autodesk Fusion 360 and create a new design.
2. Select **Sketch > Create Sketch**.

### STEP 2: Select the Sketch Plane

1. Select the **Top (XY) Plane**.

### STEP 3: Create the Base Sketch

1. Select **Sketch > Rectangle > Center Rectangle**.
2. Place the cursor at the sketch origin and click to start the rectangle.
3. Enter **56 mm** for the width and **18 mm** for the height.
4. Select **Sketch > Arc > Center Point Arc** and create the arc as shown in the input drawing.
5. Set the arc radius to **18 mm**.
6. Select **Sketch > Circle > Center Point Circle** and create the circle at the position shown in the drawing.
7. Set the circle diameter to **16 mm**.
8. Click **Finish Sketch**.

### STEP 4: Extrude the Base Sketch

1. Select **Solid > Create > Extrude**.
2. Select the base sketch profile.
3. Enter an extrusion distance of **8 mm**.
4. Press **Enter** to confirm.

### STEP 5: Create a Sketch on the Base

1. Select **Sketch > Create Sketch**.

### STEP 6: Select the Sketch Plane

1. Select the **top surface of the 3D block**.

### STEP 7: Create the Rectangle

1. Select **Sketch > Rectangle > Center Rectangle**.
2. Place the rectangle at the required position on the top face.
3. Enter **40 mm** for the width and **10 mm** for the height.
4. Click **Finish Sketch**.

### STEP 8: Extrude the Rectangle

1. Select **Solid > Create > Extrude**.
2. Select the rectangular profile.
3. Enter an extrusion distance of **32 mm**.
4. Press **Enter** to confirm.

### STEP 9: Create the Triangle

1. Start a sketch on the required face/plane.
2. Select **Sketch > Triangle > Center Triangle**.
3. Place the triangle at the position shown in the isometric drawing.
4. Enter **32 mm** for the width and **12 mm** for the height.
5. Click **Finish Sketch**.

### STEP 10: Extrude the Triangle

1. Select **Extrude** and choose the triangular profile.
2. Set the extrusion distance to **6 mm** and use the **Two Sides** direction option, as specified in the original dimensions.
3. Press **Enter** to confirm.

### STEP 11: Create the Polygon Profile

1. Start a sketch on the required face/plane.
2. Select **Sketch > Polygon > Circumscribed Polygon**.
3. Place the polygon at the position shown in the drawing.
4. The original procedure specifies **40 mm × 30 mm** and **3 sides**, while naming the profile a *pentagon*.
5. Click **Finish Sketch**.

> **Dimension check:** A polygon with 3 sides is a triangle, not a pentagon. Confirm the intended number of sides from the drawing/model before treating this feature as a pentagon.

### STEP 12: Extrude the Polygon Profile

1. Select **Extrude**.
2. Select the polygon profile created in Step 11.
3. Enter an extrusion distance of **10 mm**.
4. Press **Enter** to confirm.

### STEP 13: Create the Circular Profile

1. Start a sketch on the end face identified in the drawing.
2. Select **Sketch > Circle > Center Point Circle**.
3. Create the circular profile at the position shown in the drawing.
4. The original procedure lists **Ø30 mm** and **Ø20 mm** as the inner and outer diameters, respectively.

> **Dimension check:** The listed inner diameter (Ø30 mm) is larger than the listed outer diameter (Ø20 mm). Verify the intended inner and outer diameters against the input drawing before creating this feature.

5. Click **Finish Sketch**.

### STEP 14: Extrude the Circular Profile

1. Select **Extrude**.
2. Select the circular profile created in Step 13.
3. Set the extrusion distance to **10 mm on both sides**, as specified in the original procedure.
4. Press **Enter** to confirm.

## INPUT

![Isometric input drawing](https://user-images.githubusercontent.com/113594316/198523331-05ace360-502b-4569-b9b4-31c60e3cd554.png)

## OUTPUT

<img width="1015" height="716" alt="Fusion 360 model output – screenshot 1" src="https://github.com/user-attachments/assets/f7a9a099-1e60-4dfa-8a75-d7bef29b9ea0" />

<img width="1915" height="1021" alt="Fusion 360 model output – screenshot 2" src="https://github.com/user-attachments/assets/cbf4d009-3cc9-43a5-a76f-7f926958b4c4" />

## RESULT

Thus, the 3D solid model is created from the given isometric drawing using Autodesk Fusion 360.
