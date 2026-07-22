---
**Title:** Tri-Archimedean-Wind-Turbine
**Author:** Sunrit Hazra  
**Description:** A triblade wind turbine with blades shaped as Archimedean spirals, designed to explore spiral-based wind energy generation, based on the Liam F1 Archimedes.  
**Created on:** 16-03-2026  
**Designing Progress (%): 70%**
**Building Progress (%): 0%**
---

# Day 1 — 30.06.2026: Modelling the Rotor & Frame

Ever since I came accross the concept of Archimedes Wind Turbines, that challenged conventional wind turbines in small scale, I have always wanted to make one. So, right before creating this project, I hopped into researching about this concept. I am really excited to get started with the modelling.

The very first thing I did was to model the blades: The core of the whole turbine.

With the help of a tutorial, I had previously learned how to model the Archimedean Spiral Blade of the Wind Turbine. This time, I tried it myself completely on my own.

/### **1. Sketching the Span of the First Blade**

I decided to keep the span of the blade at 250 mm and the height of the blade at 500 mm. I drew a sketch and then I continued with a revolution and helix type of coil that will act as the edges of the blade. I kept the angle at -43.5 degrees, exactly as stated in the tutorial I have seen before. I kept the radius of the blade at 500 mm (1 metre diameter), as I planned to make a small Wind Turbine, with a small blade.

<img width="1366" height="733" alt="image" src="https://github.com/user-attachments/assets/7eae2097-e4f4-4bfa-8aac-9d1a01c02801" />

<img width="1366" height="733" alt="image" src="https://github.com/user-attachments/assets/ee114455-3f4b-4aad-a725-3e5a5e02b5cc" />

/### **2. Modelling the First Blade**

To model the first blade, I used surface loft to connect the outer and inner edges of the internal triangular type of coil with section of 10 mm.

<img width="1366" height="733" alt="image" src="https://github.com/user-attachments/assets/ec3c7d99-e3c6-479b-a162-4d7d8f4543dc" />

<img width="1366" height="733" alt="image" src="https://github.com/user-attachments/assets/442305a5-a15f-44d9-a617-3551ad1718e3" />

/### **3. Modelling the Axis**

To model the axis I made a simple sketch along the centre of the blade. Then using revolve tool I joined it with the alreasy made blade.

<img width="1366" height="733" alt="image" src="https://github.com/user-attachments/assets/3af59a17-1ea4-42ea-8cc7-4ec093d7b47c" />

<img width="1366" height="733" alt="image" src="https://github.com/user-attachments/assets/7529de6f-6b7d-4ba8-ad5e-cf6ee075492c" />

/### **4. Modelling the other two blades**

Using circular pattern, I modeled the other two blades, with the axis selected as the body I just joined with the blade in the previous step. Then using the combine tool, I merged them into a single body.

<img width="1366" height="733" alt="image" src="https://github.com/user-attachments/assets/29543ccc-c0b5-4c97-b51c-8996b8499df1" />

<img width="1366" height="733" alt="image" src="https://github.com/user-attachments/assets/58c44a95-02fa-40fc-9044-acdb1f4d5e59" />

/### **5. Scaling the model down**

I realised that this blade is way too big to print, if I don't have the option of Sheet Metal due to cost. I then decided to make it small enough to make it possible to print it in a single piece in the build volume of a Bambu Lab H2D. Thus, I scaled it down by the factor of 325/1000. Then I preass pulled to make the axis thicker as the last blade's ends were folating.

<img width="1366" height="733" alt="image" src="https://github.com/user-attachments/assets/6fd60d05-acd7-450c-9292-0f75382cfb2d" />

<img width="1366" height="733" alt="image" src="https://github.com/user-attachments/assets/5cfb7b86-6b76-44fa-a6b8-cdd19c7e4cc9" />

/### **6. Slicing the model to check it**

As I want the whole blade in one single piece, I sliced it in Bambu Studio to make sure that it is printable in H2D build volume. The result was positive.

<img width="1366" height="733" alt="image" src="https://github.com/user-attachments/assets/cfe33ce9-ebf3-4c4c-9441-50cc791b296a" />

<img width="1366" height="733" alt="image" src="https://github.com/user-attachments/assets/2ddb568c-79a0-4d5e-9911-bc297bcacca5" />

/## **B. Modelling the frame (4 hours and 52 minutes)**

/### **1. Sketching the Frame**

To model the frame, I spent about 5 minutes researching about the Liam F1 Archimedes. I looked at its frame, manually made up proportions in mind by visually looking at the pictures and then I started with a circle of 575 mm. I had to make sure everything fits together perfectly. Worst thing is that I forgot to enable Parametric Modelling after I disabled it for some reason.

<img width="1366" height="733" alt="image" src="https://github.com/user-attachments/assets/61f46fd5-de70-4bc1-bcb7-4ad37d2f0b8d" />

<img width="1366" height="733" alt="image" src="https://github.com/user-attachments/assets/bcee5df4-a11e-4ce7-a23b-893aa59ac41d" />

/### **2. Forming the Frame Body.**

I symmetrically extruded 20 mm both sides, then using a sketch below, I cut it in two parts.

<img width="1366" height="733" alt="image" src="https://github.com/user-attachments/assets/a65a243f-7831-4226-b4b5-2e0e17d5f694" />

<img width="1366" height="733" alt="image" src="https://github.com/user-attachments/assets/998a2a99-675f-4a6f-8761-b7928cd1a7d3" />

/###  **3. Connecting and dividing the Frame.**

I first connected both sides of the Frame to merge them into a single body. Then, I realised that it is too large to be printed in a single piece even in the Bambu Lab H2D. So, I had to divide it in a way that
everything is symmetrical, and stays nice.

<img width="1366" height="733" alt="image" src="https://github.com/user-attachments/assets/944d3dec-63f2-439c-a863-7de7aaf9f7d2" />

<img width="1366" height="733" alt="image" src="https://github.com/user-attachments/assets/c6397d14-3c37-43b3-8105-27bc8647698e" />

/### **4. Adding joints**

I needed the two divided structures to connect strongly and seamlessly. For that, I made extusions one one face and cuts on the other. Then, I added clearence and holes for securing them with fasteners.

<img width="1366" height="733" alt="image" src="https://github.com/user-attachments/assets/664b226a-6c34-4eae-bf8c-13e5077560b5" />

<img width="1366" height="733" alt="image" src="https://github.com/user-attachments/assets/34f007b7-a207-4373-abc2-e5fe945848d2" />

/### **5. Modelling the frame stand**

The structure needed to stand on something. Thus, I had to model a rigid structure that can bear the mass and movement of the whole system above. I created the frame using lofts to connect two circular faces to make a cone, and then using sketches again I cut holes into the structure.

<img width="1366" height="733" alt="image" src="https://github.com/user-attachments/assets/ca49e2a3-10c8-45a6-9f43-859f49034d6e" />

<img width="1366" height="733" alt="image" src="https://github.com/user-attachments/assets/6b41a5c2-2d90-445f-ab19-89892a606f2b" />

Total time spent: 6h 35m

---
