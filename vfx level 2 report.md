## Color Page 
The **Color Page** in DaVinci Resolve is where we improve how a video looks by fixing exposure, correcting colors, and giving the footage a certain mood or style. It is mainly used after editing is completed.

----------

### **Why We Use the Color Page**

When a video comes directly from a camera, it may look dull, flat, or slightly incorrect in terms of brightness and color. The Color Page helps us:

-   Fix lighting issues
    
-   Correct color imbalance
    
-   Enhance details
    
-   Create a specific visual style (warm, cool, cinematic, etc.)
    

----------

### **Nodes – How Work Is Organized**

Instead of layers, DaVinci Resolve uses **nodes**.

-   Each node represents one correction or effect.
    
-   Nodes are connected in a flow from left to right.
    
-   This makes the grading process clean and easy to manage.
    
-   We can turn nodes on or off to compare changes.
![nodes](https://i.imgur.com/MowvDoZ.png)
    

----------

### **Color Wheels (Primary Controls)**

Color wheels are the most basic and important tools in the Color Page.

-   **Lift** controls the dark areas (shadows).
    
-   **Gamma** controls the midtones (most visible parts of the image).
    
-   **Gain** controls the bright areas (highlights).
    
-   **Offset** adjusts the entire image evenly.
    
![color wheels](https://i.imgur.com/fe1LZSE.png)
These controls help fix exposure and balance brightness before moving on to creative grading.

----------

### **Curves – Fine Control Over Colors**

Curves allow more precise adjustments than color wheels.

-   They are used to control contrast and brightness in a very controlled way.
    
-   Special curves like **Hue vs Saturation** and **Hue vs Hue** allow us to adjust only specific colors (like sky or greenery) without affecting the whole image.
    
-   Curves are especially useful when we want natural-looking color enhancement.
![curves](https://i.imgur.com/wXUNAy6.png)    

----------

### **Color Space (Why Footage Looks Flat)**

Footage may look flat because it is recorded in **Log** or **RAW** format.

-   Log footage preserves more detail but looks washed out.
    
-   Color Space Transform or LUTs are used to convert this footage into a display-ready format like **Rec.709 or Rec.2100**.
    
-   This step gives the footage contrast and color so grading becomes easier.
    
----------

### **LUTs (Look-Up Tables)**

LUTs are predefined color looks.

-   They can instantly change the mood of a clip.
    
-   LUTs are usually applied after basic corrections.
    
-   Their strength should be kept low to avoid unnatural results.
    

----------

### **Scopes – Reading the Image Correctly**

Scopes are tools that help us understand the image more accurately than just using our eyes.

-   **Waveform** helps check brightness levels.
    
-   **RGB Parade** helps balance colors.
    
-   **Histogram** shows tonal distribution.
    
-   **Vectorscope** shows color saturation and direction.
    
![scopes](https://i.imgur.com/XCxXLuR.png)
Scopes ensure our grading is technically correct and consistent.

###  my workflow :
I added **six serial nodes using Alt + S** and worked on one feature in each node to keep the grading process clean and organized.

![color page](https://i.imgur.com/21XPULP.png)

-   **Node 1 – White Balance**  
    I first corrected the white balance to remove unwanted color casts and get a neutral base image.
    
-   **Node 2 – Exposure**  
    In this node, I adjusted Lift, Gamma, and Gain to balance shadows, midtones, and highlights. The waveform scope was used to make sure the exposure looked natural and details were preserved.
    
-   **Node 3 – Contrast**  
    Contrast adjusted to add depth to the image and improve separation between dark and bright areas without overdoing it.
    
-   **Node 4 – Curves**  
    Curves were used for selective color adjustments. Hue vs Saturation and Hue vs Hue helped enhance sky and background colors while keeping the rest of the image unchanged.
    
-   **Node 5 – Color Space Transform (CST)**  
    A Color Space Transform was applied to convert the footage from log format to Rec.2100, ensuring correct color and brightness representation for display.
    
-   **Node 6 – LUT**  
    Finally, a LUT was applied to give the footage a polished look. The intensity was kept low so it blended well with the earlier corrections.
    

----------

### **Final Output**

All changes were reviewed by toggling nodes on and off and checking scopes to ensure the final video looked balanced, natural, and visually appealing.

[find the video here](https://youtu.be/-UARjpVskiM?si=tHLJAANPjGmlcQwy)
