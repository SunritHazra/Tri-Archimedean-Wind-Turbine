---
**Title:** Tri-Archimedean-Wind-Turbine
**Author:** Sunrit Hazra  
**Description:** A triblade wind turbine with blades shaped as Archimedean spirals, designed to explore spiral-based wind energy generation, based on the Liam F1 Archimedes.  
**Created on:** 16-03-2026  
**Designing Progress (%): 70%**
**Building Progress (%): 0%**
---

# Day 1 — 16.03.2026: Foundational Research

Ever since I came accross the concept of Archimedes Wind Turbines, I have always wanted to make one. Archimedes wind turbine is a type of wind turbine that is extremely efficient in small-scale set ups. The triblade architecture of the windmill inspired by the Archimedes wind turbine takes advantage of the turbulance of the wind in non-open small-scale places, unlike regular triblade rotor. Designed for urban and residential rooftops, its nautilus shell-like shape allows it to automatically face the wind, capturing wind from any direction while operating silently and safely for wildlife.

> "The Archimedes windmill is a new type of wind turbine comprising three circular blades which are wrapped around one another and then expanded. This creates a three-dimensional conical turbine, similar to elongated shells found on the beach. The special design ensures that wind is drawn into the turbine. The average yield is many times higher compared to a normal urban windmill propeller."
> — [thearchimedes.com](https://thearchimedes.com/#)

Today, I did some foundational research on the concept of Archimedes Wind Turbines. Right before creating this project, I hopped into researching deeply about this fascinating concept.

These windmills served as the inspiration for my project:

- [This](https://thearchimedes.com/) created the initial spark of making this project.
- [This](https://www.archimedesgreenenergys.com/) introduced the basic concept.
- [This](https://photon-renewables.co.uk/solar-products/liam-f1-archimedes-turbine/) is the Liam F1 Archimedes.
- [This](https://www.youtube.com/watch?v=hCAunoANn3U) video also taught me the concept.

This is the archimedes windmill by the Dutch Dutch MSc Marinus Mieremet:

<img width="2500" height="1196" alt="image" src="https://github.com/user-attachments/assets/1d90b17c-c825-4568-b2e4-769618cd884f" />

Visually, it seemed like a cool complex-organic piece of machinery, especially due to the triblade spiral rotor. To me, it seemed that I could divide this project into three different parts: 

1. Structural Parts: The frame, fasteners
2. Mechanical Parts: The triblade-rotor, bearings, axle
3. Electronic Parts: The generator motor, and the PCBA

Just as I had the basic idea of how this thing works, it seemed like I should dive into modelling the windmill. But it seemed it is better to just watch a tutorial for the time-being. To be specific, I watched [this](https://www.youtube.com/watch?v=vfy-T7bE3I0) tutorial video on how to model the rotor, and actually understood how to do it. Before this video I had watched 3 more, but actually struggled how to understand this concept.

To visually study the model, I needed some 3D models to study. Thus, I went to Sketchfab, GrabCAD and Printables for reliable models for the windmill I am going to make. These are some models I downloaded and studied:

- Found [this](https://sketchfab.com/3d-models/archimedes-wind-turbine-bd6e893a660e430f8a36c028dcada6ed) from Sketchfab
- Found [this](https://grabcad.com/library/archimedes-liam-f1-wind-turbine-1) from GrabCAD
- Found [this](https://www.printables.com/model/753160-liam-f1-wind-turbine-fibonacciarchimedes-golden-ra) from Printables.

I imported the models one by one into Autodesk Fusion and studied the structure of the frame on which the rotor stood and especially the rotor's spiral triblade architecture.

<img width="1366" height="733" alt="image" src="https://github.com/user-attachments/assets/2f79eedc-35e7-486f-9b76-ff9facf04aa7" />

Then I went through [this](https://thearchimedes.com/images/pdf/AWM%20brochure%20Respect%202023%20HQ%20compressed.pdf) brochure from the archimedes website. This is some basic information about thier product.

<img width="789" height="445" alt="image" src="https://github.com/user-attachments/assets/bbee7790-d9bb-4f6b-a959-ac3a52b4a835" />

After reading the brochure, especially the power output of the system, I was wondering something critical. I next did some research using AI (ChatGPT) on this project, asked it critical questions that were unavailable on the internet, and guideance on how to make this project and with how much budget. The one question that stood out the most to me was this:

> "Is there any reliable way of fabricating the rotor without using industrial machinery?"
> I could of course 3D print the rotor, but it would be significantly small in size and not produce any meaningful output. I have seen some videos in YouTube where they have used flatenned PVC pipe sheets and made a not-too-big rotor: this way is quite unreliable. On the other hand, the industry must be relying on heavy machinery with I can nor access or study due to restrictions.
> Thus, I am deciding to produce this project in small scale and 3D print the rotor at maximum size in my school's Bambu Lab H2D. Still, I am very open to choose a better and more reliable way.

I made some mental calculations about the span of the rotor blades and made ChatGPT apply the required formulae to produce a chart on how much the power output would increase based on the surface area of the triblade rotor exposed to the wind.

While surfing through the internet, I found [this](https://thearchimedes.com/products) page with the power output of their two products, based on the speed of the wind they are exposed to. This proved how important speeds and blade spans are to determine the output by the rotor.

Then came the crucial step of naming this project. Thanks to ChatGPT, it helped me to decide a name that sounds technically correct, unique and also a little aligned towards convential naming. I wanted "Archimedes"-related something in the name of the project, "Tri-" as a prefix and either "Turbine" or "Windmill" in the name of the project. With some AI-assisted brainstorming, I confirmed the name of the project to be "Tri-Archimedean Wind Turbine", which sounds quite good and also describes the thing exactly, simultaneously.

Total time spent: 6h 45m

---

# Day 2 — 17.03.2026: Modelling the Rotor & Frame

Today was the first day of modelling this turbine. The very first thing I did was to model the blades, which was the core of the whole turbine.

With the help of [this](https://www.youtube.com/watch?v=vfy-T7bE3I0) tutorial, I had previously learned how to model the Archimedean Spiral Blade of the Wind Turbine. This time, I tried it myself completely on my own. I honestly, did not know about the angle, diameter, height or anything I needed. I just copied the exact values of the tutorial without understanding. 

But, anyways, here's how I did it:

**1. Sketching the Span of the First Blade:** I decided to keep the span of the blade at 250 mm and the height of the blade at 500 mm. I drew a sketch and then I continued with a revolution and helix type of coil that will act as the edges of the blade. I kept the angle at -43.5 degrees, exactly as stated in the tutorial I have seen before. I kept the radius of the blade at 500 mm (1 metre diameter), as I planned to make a small Wind Turbine, with a small blade.

<img width="1366" height="733" alt="image" src="https://github.com/user-attachments/assets/7eae2097-e4f4-4bfa-8aac-9d1a01c02801" />

<img width="1366" height="733" alt="image" src="https://github.com/user-attachments/assets/ee114455-3f4b-4aad-a725-3e5a5e02b5cc" />

**2. Modelling the First Blade:** To model the first blade, I used surface loft to connect the outer and inner edges of the internal triangular type of coil with section of 10 mm.

<img width="1366" height="733" alt="image" src="https://github.com/user-attachments/assets/ec3c7d99-e3c6-479b-a162-4d7d8f4543dc" />

<img width="1366" height="733" alt="image" src="https://github.com/user-attachments/assets/442305a5-a15f-44d9-a617-3551ad1718e3" />

**3. Modelling the Axis:** To model the axis I made a simple sketch along the centre of the blade. Then using revolve tool I joined it with the alreasy made blade.

<img width="1366" height="733" alt="image" src="https://github.com/user-attachments/assets/3af59a17-1ea4-42ea-8cc7-4ec093d7b47c" />

<img width="1366" height="733" alt="image" src="https://github.com/user-attachments/assets/7529de6f-6b7d-4ba8-ad5e-cf6ee075492c" />

**4. Modelling the other two blades:** Using circular pattern, I modeled the other two blades, with the axis selected as the body I just joined with the blade in the previous step. Then using the combine tool, I merged them into a single body.

<img width="1366" height="733" alt="image" src="https://github.com/user-attachments/assets/29543ccc-c0b5-4c97-b51c-8996b8499df1" />

<img width="1366" height="733" alt="image" src="https://github.com/user-attachments/assets/58c44a95-02fa-40fc-9044-acdb1f4d5e59" />

**5. Scaling the model down:** I realised that this blade is way too big to print, if I don't have the option of Sheet Metal due to cost. I then decided to make it small enough to make it possible to print it in a single piece in the build volume of a Bambu Lab H2D. Thus, I scaled it down by the factor of 325/1000. Then I preass pulled to make the axis thicker as the last blade's ends were folating.

<img width="1366" height="733" alt="image" src="https://github.com/user-attachments/assets/6fd60d05-acd7-450c-9292-0f75382cfb2d" />

<img width="1366" height="733" alt="image" src="https://github.com/user-attachments/assets/5cfb7b86-6b76-44fa-a6b8-cdd19c7e4cc9" />

**6. Slicing the model to check it:** As I want the whole blade in one single piece, I sliced it in Bambu Studio to make sure that it is printable in H2D build volume. The result was positive.

<img width="1366" height="733" alt="image" src="https://github.com/user-attachments/assets/cfe33ce9-ebf3-4c4c-9441-50cc791b296a" />

<img width="1366" height="733" alt="image" src="https://github.com/user-attachments/assets/2ddb568c-79a0-4d5e-9911-bc297bcacca5" />

Next thing to model was the frame.

**1. Sketching the Frame:** To model the frame, I spent about 5 minutes researching about the Liam F1 Archimedes. I looked at its frame, manually made up proportions in mind by visually looking at the pictures and then I started with a circle of 575 mm. I had to make sure everything fits together perfectly. Worst thing is that I forgot to enable Parametric Modelling after I disabled it for some reason.

<img width="1366" height="733" alt="image" src="https://github.com/user-attachments/assets/61f46fd5-de70-4bc1-bcb7-4ad37d2f0b8d" />

<img width="1366" height="733" alt="image" src="https://github.com/user-attachments/assets/bcee5df4-a11e-4ce7-a23b-893aa59ac41d" />

**2. Forming the Frame Body:** I symmetrically extruded 20 mm both sides, then using a sketch below, I cut it in two parts.

<img width="1366" height="733" alt="image" src="https://github.com/user-attachments/assets/a65a243f-7831-4226-b4b5-2e0e17d5f694" />

<img width="1366" height="733" alt="image" src="https://github.com/user-attachments/assets/998a2a99-675f-4a6f-8761-b7928cd1a7d3" />

**3. Connecting and dividing the Frame:** I first connected both sides of the Frame to merge them into a single body. Then, I realised that it is too large to be printed in a single piece even in the Bambu Lab H2D. So, I had to divide it in a way that
everything is symmetrical, and stays nice.

<img width="1366" height="733" alt="image" src="https://github.com/user-attachments/assets/944d3dec-63f2-439c-a863-7de7aaf9f7d2" />

<img width="1366" height="733" alt="image" src="https://github.com/user-attachments/assets/c6397d14-3c37-43b3-8105-27bc8647698e" />

**4. Adding joints:** I needed the two divided structures to connect strongly and seamlessly. For that, I made extusions one one face and cuts on the other. Then, I added clearence and holes for securing them with fasteners.

<img width="1366" height="733" alt="image" src="https://github.com/user-attachments/assets/664b226a-6c34-4eae-bf8c-13e5077560b5" />

<img width="1366" height="733" alt="image" src="https://github.com/user-attachments/assets/34f007b7-a207-4373-abc2-e5fe945848d2" />

**5. Modelling the frame stand:** The structure needed to stand on something. Thus, I had to model a rigid structure that can bear the mass and movement of the whole system above. I created the frame using lofts to connect two circular faces to make a cone, and then using sketches again I cut holes into the structure.

<img width="1366" height="733" alt="image" src="https://github.com/user-attachments/assets/ca49e2a3-10c8-45a6-9f43-859f49034d6e" />

<img width="1366" height="733" alt="image" src="https://github.com/user-attachments/assets/6b41a5c2-2d90-445f-ab19-89892a606f2b" />

Total time spent: 6h 35m

---

# Day 3 — 18.03.2026: Progressing the Structure & Researching on Electronics



Total time spent: 7h 45m

---

# Day 4 — 19.03.2026: Adding Motors and Bearings & Optimizing for Manufacturing

Total time spent: 3h 05m

---

# Day 5 — 20.03.2026: Optimizing for Aerodynamics

Here's the lapse of today's session: [TAWT-LPS-1-D5](https://lapse.hackclub.com/timelapse/pTWpnDaI6UNO)

Total time spent: 1h 10m

---

# Day 6 — 30.04.2026: Researching on Electronics & Drawing the Schematic

Total time spent: 3h 00m

---

# Day 7 — 22.07.2026: Journaling & Catching up After Months

Here's the lapse of today's session: [TAWT-LPS-2-D7](https://lapse.hackclub.com/timelapse/GkcBGLRQ85SD)

Total time spent: 1h 40m

---

# Day 8 — 23.07.2026: Journaling

Here's the lapse of today's session: [TAWT-LPS-3-D8]()

Total time spent: 0h 00m

---
