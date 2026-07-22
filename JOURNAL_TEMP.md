---
**Title:** Tri-Archimedean-Wind-Turbine
**Author:** Sunrit Hazra  
**Description:** A triblade wind turbine with blades shaped as Archimedean spirals, designed to explore spiral-based wind energy generation, based on the Liam F1 Archimedes.  
**Created on:** 16-03-2026  
**Designing Progress (%): 70%**
**Building Progress (%): 0%**
---

# Day 1 — 30.06.2026: Drawing the Schematic & Assigning Footprints

Ever since I came accross the concept of Archimedes Wind Turbines, that challenged conventional wind turbines in small scale, I have always wanted to make one. So, right before creating this project, I hopped into researching about this concept. I am really excited to get started with the modelling.

The very first thing I did was to model the blades: The core of the whole turbine.

With the help of a tutorial, I had previously learned how to model the Archimedean Spiral Blade of the Wind Turbine. This time, I tried it myself completely on my own.

---

### **1. Sketching the Span of the First Blade**

I decided to keep the span of the blade at 250 mm and the height of the blade at 500 mm. I drew a sketch and then I continued with a revolution and helix type of coil that will act as the edges of the blade. I kept the angle at -43.5 degrees, exactly as stated in the tutorial I have seen before. I kept the radius of the blade at 500 mm (1 metre diameter), as I planned to make a small Wind Turbine, with a small blade.

![image](https://stasis.hackclub-assets.com/images/1773639930823-5x3hak.png)

![image](https://stasis.hackclub-assets.com/images/1773639558635-u0fjcf.png)

---

### **2. Modelling the First Blade**

To model the first blade, I used surface loft to connect the outer and inner edges of the internal triangular type of coil with section of 10 mm.

![image](https://stasis.hackclub-assets.com/images/1773640397762-ofqckn.png)

![image](https://stasis.hackclub-assets.com/images/1773640431326-xecsab.png)

---

### **3. Modelling the Axis**

To model the axis I made a simple sketch along the centre of the blade. Then using revolve tool I joined it with the alreasy made blade.

![image](https://stasis.hackclub-assets.com/images/1773640645452-inrozj.png)

![image](https://stasis.hackclub-assets.com/images/1773640649409-249jug.png)

---

### **4. Modelling the other two blades**

Using circular pattern, I modeled the other two blades, with the axis selected as the body I just joined with the blade in the previous step. Then using the combine tool, I merged them into a single body.

![image](https://stasis.hackclub-assets.com/images/1773640836510-w60pc9.png)

![image](https://stasis.hackclub-assets.com/images/1773640874598-xyc0an.png)

---

### **5. Scaling the model down**

I realised that this blade is way too big to print, if I don't have the option of Sheet Metal due to cost. I then decided to make it small enough to make it possible to print it in a single piece in the build volume of a Bambu Lab H2D. Thus, I scaled it down by the factor of 325/1000. Then I preass pulled to make the axis thicker as the last blade's ends were folating.

![image](https://stasis.hackclub-assets.com/images/1773642013593-7343ku.png)

![image](https://stasis.hackclub-assets.com/images/1773642080919-xswsge.png)

---

### **6. Slicing the model to check it**

As I want the whole blade in one single piece, I sliced it in Bambu Studio to make sure that it is printable in H2D build volume. The result was positive.


![image](https://stasis.hackclub-assets.com/images/1773644770123-u4ob9w.png)

![image](https://stasis.hackclub-assets.com/images/1773644782223-o9ws58.png)

---

## **B. Modelling the frame (4 hours and 52 minutes)**

### **1. Sketching the Frame**

To model the frame, I spent about 5 minutes researching about the Liam F1 Archimedes. I looked at its frame, manually made up proportions in mind by visually looking at the pictures and then I started with a circle of 575 mm. I had to make sure everything fits together perfectly. Worst thing is that I forgot to enable Parametric Modelling after I disabled it for some reason.

![image](https://stasis.hackclub-assets.com/images/1773645681068-hcny1y.png)

![image](https://stasis.hackclub-assets.com/images/1773645696692-khfnwm.png)

### **2. Forming the Frame Body.**

I symmetrically extruded 20 mm both sides, then using a sketch below, I cut it in two parts.

![image](https://stasis.hackclub-assets.com/images/1773645775931-cddqfn.png)

![image](https://stasis.hackclub-assets.com/images/1773646064264-4o06qs.png)

---

###  **3. Connecting and dividing the Frame.**

I first connected both sides of the Frame to merge them into a single body. Then, I realised that it is too large to be printed in a single piece even in the Bambu Lab H2D. So, I had to divide it in a way that
everything is symmetrical, and stays nice.

![image](https://stasis.hackclub-assets.com/images/1773759049982-jy99t4.png)

![image](https://stasis.hackclub-assets.com/images/1773759154442-k3mp05.png)

---

### **4. Adding joints**

I needed the two divided structures to connect strongly and seamlessly. For that, I made extusions one one face and cuts on the other. Then, I added clearence and holes for securing them with fasteners.

![image](https://stasis.hackclub-assets.com/images/1773759133500-6kjm7z.png)

![image](https://stasis.hackclub-assets.com/images/1773759272608-b1vfwt.png)

---

### **5. Modelling the frame stand**

The structure needed to stand on something. Thus, I had to model a rigid structure that can bear the mass and movement of the whole system above. I created the frame using lofts to connect two circular faces to make a cone, and then using sketches again I cut holes into the structure.

![image](https://stasis.hackclub-assets.com/images/1773759605527-bvwqu3.png)

![image](https://stasis.hackclub-assets.com/images/1773759743601-uhjj4l.png)

---
