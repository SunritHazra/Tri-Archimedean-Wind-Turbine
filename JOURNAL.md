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

Next thing to model was the frame itself. To model the frame, I spent about some minutes researching about the Liam F1 Archimedes. [This](https://photon-renewables.co.uk/solar-products/liam-f1-archimedes-turbine/) was my inspiration, especially for the frame.

**1. Sketching the Frame:** I looked at its frame, manually made up proportions in mind by visually looking at the pictures and then I started with a circle of 575 mm. I had to make sure everything fits together perfectly. But a problematic thing is that I forgot to enable Parametric Modelling after I disabled due to some problems.

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

With  this the frame and the blade was modeled.

Total time spent: 6h 35m

---

# Day 3 — 18.03.2026: Progressing the Structure & Researching on Electronics

The basic structure is done. Now, I guess the next step is to reinforce and work on what's already done. By the way, [this](https://drive.google.com/file/d/1qaffLusWx64qEn7S2Rdufs02tpBj00Fq/view?usp=drive_link) is the final result of what was done.

/## **1. Remodelling the Blade (1 hour 42 minutes)**

From the structure I have made, the blade appeared to be disproportionate. So, I remodelled the blade with many many different proportions and styles, with different angles, different pitch and different height. I edited the Coil function more than 23 times. Then I sliced it everytime to see if it fits with the supports. I made about 27 different blades, and even the slicer software struggles to arrange the Blade. But after multiple trial and errors, here is the final result:

<img width="1366" height="733" alt="image" src="https://github.com/user-attachments/assets/8e238753-b6b0-4324-b822-055e4a9fef79" />

<img width="1366" height="733" alt="image" src="https://github.com/user-attachments/assets/d5d33064-4ad2-42bf-98bc-753775d7cb14" />

/## **2. Adding Blade Shaft Hubs (25 minutes)**

I added shaft hubs for the blade on both sides of the frame. I did this using sketches and extrusions.

<img width="1366" height="733" alt="image" src="https://github.com/user-attachments/assets/3c36afb8-7c36-4676-8624-a2f97ba78251" />

<img width="1366" height="733" alt="image" src="https://github.com/user-attachments/assets/c67fd0fb-0f01-4ad3-b40a-88a5145f07e7" />

/## **3. Adding Joints for the Frame Stand (48 minutes)**

I wanted the structure to be rigid and firm, supported by its own structure. For that, I made the Lower Frame connect the Upper Frame, and the Upper Frame connect the lowermost part, the Frame stand. I added a hole so that the whole Frame Stand can go inside the Upper Frame hole.

<img width="1366" height="733" alt="image" src="https://github.com/user-attachments/assets/c81aea7b-4a62-4419-805d-93c9831bcbc3" />

<img width="1366" height="733" alt="image" src="https://github.com/user-attachments/assets/d250d7e4-d2ac-4c49-b5d8-9858b50bde7e" />

/## **4. Adding the Fasteners (34 minutes)**

I had already made the holes, now I added the fasteners that will make the struture stronger. I am not using any standard screw as I don't want to use washers, or else the metal may bite into the 3D printed frame, if overtightened. This also ensured that the whole system is connected through only two fasteners. I also added threads to the screws.

<img width="1366" height="733" alt="image" src="https://github.com/user-attachments/assets/02252df4-f016-4e2c-8fff-44aba3b5c929" />

<img width="1366" height="733" alt="image" src="https://github.com/user-attachments/assets/f967f12e-dd62-4539-af10-343c59c50d62" />

/## **5. Integrating the Blade in the Assembly. (15 minutes)**

Most of the Structure was completed. Now it was the time to integrate the Blade into the assembly. I added a new axle shaft with proper clearence. Then I added motions to the model at last.

<img width="1366" height="733" alt="image" src="https://github.com/user-attachments/assets/16d0c3e2-f372-403a-af46-38f572bd24a8" />

<img width="1366" height="733" alt="image" src="https://github.com/user-attachments/assets/efa162f1-c8ac-4948-b166-1461421579d6" />

My project's mechanical and structural part is mostly done. What now remains is to make the thing actually function by integrating proper electronics. This is where the real transformation happens—from a rotating structure to a working energy system.

/## **1. Researching About the AWM-750D-150W**

After about 55 minutes of reading through articles and researching about the official [AWM-750D-150W](https://thearchimedes.com/products), I realised this:

The 0.75 meter diameter version of the official Archimedes Wind Turbine costs absolutely $1700 minimum. My diameter is **0.39 m**, which is about **1.92 times smaller**. Additionally, I am using custom built parts with no factory or mass production setup, so $700 to $900 is the absolute minimum and sane range. But I am targeting maximum $100 for this project.

Their product gives about 10 W of energy in 5 m/s wind. With my smaller blade, this output drops significantly at 5 m/s wind.

<img width="992" height="866" alt="image" src="https://github.com/user-attachments/assets/0a244534-7339-4b6b-9295-f3cc152cc1c2" />

/## **2. Calculating Sweep Area of the Blade (32 minutes)**

Before jumping into electronics, I needed to understand what kind of power I can even expect from this little turbine. The sweep area of the blade determines how much wind energy is being captured.

After correcting the dimensions, the **blade diameter is 390 mm (0.39 m)**:

* Radius = 0.195 m
* Sweep Area ≈ π × (0.195)² ≈ **0.119 m²**

Since my design is based on a tri-blade Archimedean spiral, I calculated the effective area of one blade and then considered all three combined. This gave me a rough idea of the energy scale I am dealing with, and it became clear early on that this is a low-power system, where efficiency matters more than anything else.

/## **3. Finding the Appropriate Motor (42 minutes)**

I already had some **NEMA 17** stepper motors, so I started there. First, I tested whether they were functional, and thankfully, they were. However, once I tried to reason it out, I realised something important—the turbine simply wouldn’t be able to generate enough torque at low wind speeds to rotate a stepper motor effectively.

That was a turning point (because I had literally 4 NEMA 17 motors in perfect condition!). The system is not brute-force driven, instead it depends on subtle motion. So I dropped the stepper motor idea (unfortunately) and shifted towards brushless DC motors, which are far better suited for low-resistance rotation and energy generation in such conditions.

After exploring options, I selected the **[DYS D3536-9 910 KV BLDC Motor](https://robu.in/product/dys-d3536-9-910-kv-bldc-motor/)**, mainly because of its larger stator size, better torque characteristics, and overall efficiency at lower RPM ranges. By the way, I thought the NEMA 17 would look cool, but this looks cooler.

<img width="1366" height="733" alt="image" src="https://github.com/user-attachments/assets/b75fcff1-da04-4b66-bbab-20cb8889ab72" />

/## **4. Finding the Appropriate Rectifier (25 minutes)**

The motor generates 3-phase AC (kind of like any other BLDC motor out there), which is not directly usable. I needed a way to convert that into DC.

That’s where the rectifier comes in. After looking at different options, I decided to go with the **[ATORSE 3-Phase Bridge Rectifier](https://amzn.in/d/01Bq0PjP)**. It simplifies the process significantly and avoids the complexity of building a custom diode bridge.

<img width="1366" height="733" alt="image" src="https://github.com/user-attachments/assets/5cc7c79c-22fb-4c53-9e81-932a3dc7a865" />

/## **5. Finding the Appropriate Capacitor (18 minutes)**

Once the AC is converted to DC, the output is still not stable—it fluctuates with wind speed. To smooth this out, I added capacitors.

I chose **[2 × 1000µF, 25V electrolytic capacitors](https://robu.in/product/1000uf-25v-electrolytic-capacitor-dip-pack-of-5/?gad_source=1&amp;gad_campaignid=17427802703&amp;gbraid=0AAAAADvLFWdoU8ETCY7L4Jk7JtQiLVYpi&amp;gclid=Cj0KCQjwmunNBhDbARIsAOndKpn8g1YaEd46AuHutQtw_pX00QtMXT71daDhztqtxJNMG3HaxQKSYS8aAi7DEALw_wcB)**, connected in parallel. This effectively increases the total capacitance and helps stabilize the voltage before it goes into the next stage. This step is subtle but critical, because unstable input can completely break downstream electronics.

<img width="1366" height="733" alt="image" src="https://github.com/user-attachments/assets/af0d2da8-17c5-41c4-8cd1-e6e29cf5e19d" />

/## **6. Finding the Appropriate Boost Converter (20 minutes)**

At this point, I had DC—but it was too low to be useful. The voltage coming from the turbine is often less than 1V, which is not enough for charging or powering anything.

So I introduced a boost converter. I selected the **[XL6009 DC-DC Boost Converter](https://robu.in/product/xl6009-dc-dc-step-up-converter-performance-ultra-lm2577-booster-circuit-board/)**, which can step up low input voltages to a stable output, typically around 5V.

<img width="1366" height="733" alt="image" src="https://github.com/user-attachments/assets/ea43bead-e397-442b-ba3e-fafc47e0e413" />

/## **7. Finding the Appropriate Charging Module (12 minutes)**

Now that I have usable voltage, I needed a safe way to store it. Directly connecting a battery is dangerous and inefficient.

So I used the **[TP4056 Charging Module](https://robu.in/product/tp4056-1a-li-ion-lithium-battery-charging-module-with-current-protection-type-c/?gad_source=1&amp;gad_campaignid=21296336107&amp;gbraid=0AAAAADvLFWfIVKpodbBiwwStvgjfAd9AA&amp;gclid=Cj0KCQjwmunNBhDbARIsAOndKpkr0DUxdLOvePmfRXMjHUz1TEuaEtSA7X1qSXegPcqnVKEs85l3oL8aAhxaEALw_wcB)**, which is designed specifically for charging lithium-ion cells. It regulates both current and voltage, ensuring safe and controlled charging.

<img width="1366" height="733" alt="image" src="https://github.com/user-attachments/assets/33ec4fd8-8300-40d4-85f5-578e5a357dd5" />

/## **8. Finding the Appropriate Battery (5 minutes)**

Finally, I needed a way to store the generated energy. I decided to use a standard **18650 lithium-ion battery**, since it is compact, efficient, and works perfectly with the TP4056 module.

This completes the energy chain: from wind to stored electrical energy.

## **Final Component Summary**

| Name                         | Purpose                    | Cost (USD) | Qty | Total (USD) |
| ---------------------------- | -------------------------- | ---------- | --- | ----------- |
| TP4056 Charging Module       | Charge battery from output | $0.15      | 1   | $0.15       |
| XL6009 DC-DC Boost Converter | Increase output voltage    | $0.66      | 1   | $0.66       |
| 1000µF 25V Capacitor         | Smooth output              | $0.24      | 2   | $0.48       |
| ATORSE 3-Phase Rectifier     | Convert AC → DC            | $18.27     | 1   | $18.27      |
| DYS D3536-9 910KV BLDC Motor | Generate electricity       | $17.72     | 1   | $17.72      |

Total time spent: 7h 45m

---

# Day 4 — 19.03.2026: Adding Motors and Bearings & Optimizing for Manufacturing

Previosly, I had finalised all (at least most, I guess) the electronic components, now its the time to integrate them into the assembly, so that I can optimize the design best for the components. By the way this is the final look.

<img width="1366" height="733" alt="image" src="https://github.com/user-attachments/assets/d0daa1ae-40ff-41d4-b775-fa9b26ad927d" />

/## **1. Adding the BLDC Motors (45 minutes)**

The **DYS D3536-9 910 KV BLDC Motor** has the job of converting the rotational energy of the Rotor to electrical energy. I have chosen that not randomly, but because it requires little tourqe and is highly efficient.

To integrate this, I searched for some footprints and 3D models in the internet, and then I found the model from **GrabCAD**. I imported the model, and made significant changes to the **Mechanical Components** and **Structual Components** through extrusions, sketches, combine cut and face offsets. I also added joints and motions.

<img width="1366" height="733" alt="image" src="https://github.com/user-attachments/assets/e1bf6eb0-8c33-4503-b9c4-e5aedd3fbf68" />

<img width="1366" height="733" alt="image" src="https://github.com/user-attachments/assets/3c417d21-3184-4a5e-b830-8cf4c818ca1b" />

---

/## **2. Adding & Integrating Bearings (35 minutes)**

The structure obviously needed something to reliably rotate on, so bearings are a must. I again went to the internet, specifically JLCMC and Robu.in to find bearings with **10 mm Inner Diameter**. The JLC site was crazy, and continiously said No Page available whenever I selected any bearing. In the Robu.in site I found the perfect bearing, which was 6200ZZ.

Then, from McMaster-Carr I imported two **5972K326_Steel Ball Bearing** and added them to the assembly by making holes, and adding more material to the hubs.

<img width="1366" height="733" alt="image" src="https://github.com/user-attachments/assets/5766b3a0-e9a6-440c-b10c-ba719d481368" />

<img width="1366" height="733" alt="image" src="https://github.com/user-attachments/assets/f6e24e86-3f04-40f7-9fa1-2ed01f542d58" />

/## **3. Fixing the Lower Frame Hub (12 minutes)**

The hub of the Lower Frame was made from a circle, so I had to fix it by adding extrusions, that made it a flat face. Then, I added cuts for the bearing.

<img width="1366" height="733" alt="image" src="https://github.com/user-attachments/assets/2e3836d7-c908-4caa-8f6a-a65097992b6c" />

<img width="1366" height="733" alt="image" src="https://github.com/user-attachments/assets/cc2d1eaf-b4c9-4636-8fbf-e0ec26cc3b5a" />

/## **4. Dividing the Lower Frame into Components (30 minutes)**

I peacefully started my work with Hacktime Lapse, after clicking **"Create"**. Then after about an half-an-hour, I saw nothing was recorded. And, I tried everyway to record something more, but nothing worked. Lapse is not working for me! The UI is just unresponsive!

Anyways, what I did was, I noticed that printing the Lower Frame would need a lot of supports, so, I thought of seperating it into Components for asssembly. I also added clearence.

<img width="1366" height="733" alt="image" src="https://github.com/user-attachments/assets/9dc9b1bd-73c5-411f-ac4f-ab84e7c7c4c7" />

<img width="1366" height="733" alt="image" src="https://github.com/user-attachments/assets/abd59c36-4758-4fc6-adad-6751554aeddc" />

/## **5. Dividing the Lower Frame into Components (25 minutes)**

This Upper Frame needed even more supports, so I intended to do the same. But after sometime I realised that it will make the overall structure less sturdy. Eventually, I had to drop the idea.

<img width="1366" height="733" alt="image" src="https://github.com/user-attachments/assets/ea4e4318-74fd-47aa-b496-bd236707d6ca" />

<img width="1366" height="733" alt="image" src="https://github.com/user-attachments/assets/3bc5389e-8a72-40a6-ae98-2cd6a80b9b50" />

Total time spent: 3h 05m

# Day 5 — 20.03.2026: Optimizing for Aerodynamics

Now it's time for a bit of aerodynamics. Where I live, strong winds are rare, but I don't want to take any risks. Thus, I am adding two aerodynamic parts that will redirect the strong blowing wind to the blade, increasing efficiency! And of course, here is the final look:

<img width="1365" height="740" alt="image" src="https://github.com/user-attachments/assets/68e666fd-7a3c-405b-961a-dc84995416b6" />

---

## **Adding Nose Cone &amp; Dome (1 hour 4 minutes)**

I added aerodynamic nose cone and dome to ensure that any strong winds will be redirected to the Blade, and it will not cause any strain on the structure. Additionally, it hides the BLDC motor, and makes the overall structure look better.

By the way, I made my first succesful **[timelapse](https://lapse.hackclub.com/timelapse/pTWpnDaI6UNO)** by using Microsoft Edge instead of Google Chrome. Now I can finally show more than type.

<img width="1366" height="733" alt="image" src="https://github.com/user-attachments/assets/87fc0c53-1484-41e5-b6b5-3bafc01002a5" />

<img width="1366" height="733" alt="image" src="https://github.com/user-attachments/assets/68c813e5-916f-43e0-b188-edc2f70d1068" />

---

Here's the lapse of today's session: [TAWT-LPS-1-D5](https://lapse.hackclub.com/timelapse/pTWpnDaI6UNO)

Total time spent: 1h 10m

---

# Day 6 — 30.04.2026: Researching on Electronics & Drawing the Schematic

As the model was mostly completed, it was now time to get started with the PCBA. But before, I did a final review on the electronics I will be using. So, I did some research on that for about 35 minutes and then I drew the schematic.

<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/833744f2-9230-4f41-96f3-e4a724c942f5" />

---

## **1. Researching on the Electronics (40 minutes)**

I started with the BLDC motor, and then I moved to the rectifier, both of which I confirmed were still the right choices. Then I went through the whole power chain step by step. I checked how the 3-phase output from the **DYS D3536-9** motor goes into the **ATORSE 3-phase bridge rectifier**, then through the fuse, the TVS diode for protection, the big electrolytic capacitors for smoothing, the **XL6009 boost converter**, and finally into the **TP4056 charging module**.

I had to go through the datasheet of **[DYS D3536-9](https://www.dys.hk/product/D3536.html)** to make sure everything is fine.

## **2. Drawing the Schematic in KiCad (2 hours 5 minutes)**

Drawing the schematic in KiCad took quite a while. I began by placing all the connectors first — J1 for the three phases coming from the motor, J4 for the rectifier input, J2 for the battery, and J3 for the load output.

After that I added the rectifier module, the fuse, the TVS diode, and the bank of 1000µF capacitors. I used global labels a lot because I wanted the schematic to stay clean and not look like a mess of crossing wires (kind of like my other PCBs).

<img width="443" height="244" alt="image" src="https://github.com/user-attachments/assets/06919098-3d1f-487b-9635-52644cf8d3c2" />

<img width="434" height="137" alt="image" src="https://github.com/user-attachments/assets/88ce9021-a06b-4115-804e-b8ab4b641b99" />

Connecting the **XL6009 boost converter** took some time because I had to be careful with where the input comes from, and of course I made repeated mistakes and there were uncountable ERC violations.

I placed the small 100nF capacitors where they made sense for decoupling and ran the Electrical Rules Check several times. Every time it showed some small mistakes like unconnected pins or wrong labels, so I had to go back and fix them. It was a bit annoying. By the time I finished, the whole power flow from the motor phases all the way to the load output looked logical and well-protected.

<img width="658" height="381" alt="image" src="https://github.com/user-attachments/assets/405e036a-4cde-4962-ba4c-7bf50ccf7510" />

Total time spent: 3h 00m

---

# Day 7 — 22.07.2026: Journaling & Catching up After Months

blah blah blah

Here's the lapse of today's session: [TAWT-LPS-2-D7](https://lapse.hackclub.com/timelapse/GkcBGLRQ85SD)

Total time spent: 1h 40m

---

# Day 8 — 23.07.2026: Journaling

Here's the lapse of today's session: [TAWT-LPS-3-D8]()

Total time spent: 0h 00m

---
