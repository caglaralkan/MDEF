---
hide:
    - toc
---

# Prototyping for Design


**Prototyping for Design**

##Class Task No:1##
First day class was quite intense in terms of content. I am confident with the circuits, but coding language is still complicated for me. I guess it will take some time to get familiar and feel comfortable about this language. I searched and found a code to work the piezzo buzzer on ESP32 feather on arduino. I tried to figure out about the whole code, but still I am still far away to be able to design one by my own.

<div style="position: relative; width: 100%; height: 0; padding-top: 56.2500%;
 padding-bottom: 0; box-shadow: 0 2px 8px 0 rgba(63,69,81,0.16); margin-top: 1.6em; margin-bottom: 0.9em; overflow: hidden;
 border-radius: 8px; will-change: transform;">
  <iframe loading="lazy" style="position: absolute; width: 100%; height: 100%; top: 0; left: 0; border: none; padding: 0;margin: 0;"
    src="https:&#x2F;&#x2F;www.canva.com&#x2F;design&#x2F;DAFZbWMu3FY&#x2F;view?embed" allowfullscreen="allowfullscreen" allow="fullscreen">
  </iframe>
</div>
<a href="https:&#x2F;&#x2F;www.canva.com&#x2F;design&#x2F;DAFZbWMu3FY&#x2F;view?utm_content=DAFZbWMu3FY&amp;utm_campaign=designshare&amp;utm_medium=embeds&amp;utm_source=link" target="_blank" rel="noopener">circuit</a> by caglaralkan

##Class Task No:2##
As a second task, after the presentation about the 2D-3D modeling softwares, I decided to discover Grasshopper. I am good at using Rhineceros as a 3D modeling application, but mostly I am a bit old fashion. My knowledge based on more technical aspects. If I want to change a small thing on my design after finalizing a 3D model, I need to start to work from the beginning. So, Ahmed helped me to discover Grasshopper and now I do understand what is parametric design is in a better way. As we are planning to work on a modular indoor water-wall, it would be useful for me to design with the help of parametric design tools.

<div style="position: relative; width: 100%; height: 0; padding-top: 56.2500%;
 padding-bottom: 0; box-shadow: 0 2px 8px 0 rgba(63,69,81,0.16); margin-top: 1.6em; margin-bottom: 0.9em; overflow: hidden;
 border-radius: 8px; will-change: transform;">
  <iframe loading="lazy" style="position: absolute; width: 100%; height: 100%; top: 0; left: 0; border: none; padding: 0;margin: 0;"
    src="https:&#x2F;&#x2F;www.canva.com&#x2F;design&#x2F;DAFZ7gYBm2Q&#x2F;view?embed" allowfullscreen="allowfullscreen" allow="fullscreen">
  </iframe>
</div>
<a href="https:&#x2F;&#x2F;www.canva.com&#x2F;design&#x2F;DAFZ7gYBm2Q&#x2F;view?utm_content=DAFZ7gYBm2Q&amp;utm_campaign=designshare&amp;utm_medium=embeds&amp;utm_source=link" target="_blank" rel="noopener">discovering grasshopper</a> by caglaralkan

##Class Task No:3##
By using Rhineceros I designed a laptop-stand which stands by the idea of interlocking. As a first step, I checked the materials and their thicknesses. The material thickness is the most important factor for interlocking designs because hacks-notches are keys for the quality of the design.
After discussing with Adai about the design and tolerances of the outlines, I modified my design according to fit the pieces on a single cardboard (60X100cm). I cut 2 pieces as a demo in order to test the hacks-notches to get the best results and stability of the stand.
During the process I figured out how to use the laser cutter. Beyond the procedures that we have to follow, technical details as; the order of the pieces that we want to cut classified by color coding, and the datas about different materials for various thicknesses and colors hanging on the wall is quite helpful to learn about the details. On the other hand, interface of the software to use the laser cutter is quite easy and clear. Thanks to Adai and Josep again for their support.

<div style="position: relative; width: 100%; height: 0; padding-top: 56.2500%;
 padding-bottom: 0; box-shadow: 0 2px 8px 0 rgba(63,69,81,0.16); margin-top: 1.6em; margin-bottom: 0.9em; overflow: hidden;
 border-radius: 8px; will-change: transform;">
  <iframe loading="lazy" style="position: absolute; width: 100%; height: 100%; top: 0; left: 0; border: none; padding: 0;margin: 0;"
    src="https:&#x2F;&#x2F;www.canva.com&#x2F;design&#x2F;DAFaxSCJDpY&#x2F;view?embed" allowfullscreen="allowfullscreen" allow="fullscreen">
  </iframe>
</div>
<a href="https:&#x2F;&#x2F;www.canva.com&#x2F;design&#x2F;DAFaxSCJDpY&#x2F;view?utm_content=DAFaxSCJDpY&amp;utm_campaign=designshare&amp;utm_medium=embeds&amp;utm_source=link" target="_blank" rel="noopener">Interlocking - Cardboard Laptop Stand</a> by caglaralkan

##Class Task No:4##
Building a telegraph like device with LDR and LED with arduino was the fourth task. Even it looked like simple to work with photocell and LED an first glance, it was not possible to go further and built a code for decoding the light signals into Morse code.

We started to work with Ahmed on circuit of LDR-photocell and we found the code to work, we thought that we succeed in that but after Victor joined us he remarked that there is a problem with the code because there were a lot of noise in the reading of the amount of the light. As I remember correctly we damaged one Ahmed's board because we connected the LDR to 5V pin rather than 3-3.3V and it was the main reason of that noise.

Then, we continued with the LED circuit. But, we couldn't achieved with ESP32 and as Wen joined us, we tried to build the circuit with Arduino-UNO. We tried several circuits and codes but we failed. After Victor helped us we checked the items of the circuit with Multimeter and we discovered that one of the cables misbehaved! Additionally, we have learned another important thing about coding; the code is not active on an additional page and it has to be in color to work which we missed.

Finally, we put the LDR and LED circuits in a box and tried to build an isolated environment to read the signals from LED when we push the bouton shortly and longer. But, the code that we found to encode and decode the readings and convert those into Morse code and letters had so much lines of problems. So, we were not able to go further in order to build a telegraph with LDR and LED.

<div style="position: relative; width: 100%; height: 0; padding-top: 56.2500%;
 padding-bottom: 0; box-shadow: 0 2px 8px 0 rgba(63,69,81,0.16); margin-top: 1.6em; margin-bottom: 0.9em; overflow: hidden;
 border-radius: 8px; will-change: transform;">
  <iframe loading="lazy" style="position: absolute; width: 100%; height: 100%; top: 0; left: 0; border: none; padding: 0;margin: 0;"
    src="https:&#x2F;&#x2F;www.canva.com&#x2F;design&#x2F;DAFaSpXjb1s&#x2F;view?embed" allowfullscreen="allowfullscreen" allow="fullscreen">
  </iframe>
</div>
<a href="https:&#x2F;&#x2F;www.canva.com&#x2F;design&#x2F;DAFaSpXjb1s&#x2F;view?utm_content=DAFaSpXjb1s&amp;utm_campaign=designshare&amp;utm_medium=embeds&amp;utm_source=link" target="_blank" rel="noopener">LDR circuit and Code</a> by caglaralkan

##Challenge No:1##

As a group, after discussing about our common interest and as we want to work on water bricks to store domestic grey water, we decided to work on something related to modularity, interchangeability, personalisation of a product… We ended up with the idea of building a DIY toolkit which provides designing unique tile decorations and patterns made of those.

Firstly, we talked on 3D and 2D options and then we decided to focus on 2D option. For a simple tile decoration we need vinyl designs which needs to be sticked on stencil to transfer the ceramic ink. Instead of providing ready to use patterns, stickers, vinyls we preferred to work on a grid board which provides the user to make their own unique design.

Tile-Deco is a concept of grid that made of acrylic and magnets and has geometric pieces which can be located on and stick by magnets to the grid in order to form various tile decorations. Through the design process of the grid board we tried to prevent from shades and reflections which ruins the quality of the photo-digitalisation process of the vinyl. But, as the acrylic thickness and magnet sizes are defined, we couldn’t avoid from that. On the other hand, we covered the acrylic surfaces with a mat vinyl to prevent the reflections. At least we succeeded to get rid of the reflections to enhance the quality of the photo-digitalisation process. But, of course the transfer of the vinyl on the grid board was not easy, we were not satisfied with the first attempt and for the second one magnets destroyed the grid engraved vinyl and fortunately we satisfied with the third vinyl design.

Another problem that we faced with was the unsuitability of some geometric pieces which helps to generate the tile decoration design. Some geometric items has only a single magnet on them and this cause a unstable position on the gird. (During the presentation one of the constructive critic was to make the grid board double size in order tom prevent this problem, this could be a perfect solution for the problem)

The next step was making the patterns aligned with the photo-digitalisation process. As we took some tile decoration samples photos and we also worked on the various patterns options on 2D softwares. We used Illustrator and Inkscape to generate some patterns.

To sum up, the grid board building process was a good experience to use the laser cutter after designing that on Rhinoceros and worked on the technical details to get the best results with the magnets we had to locate on the grid. The final result can be improved by using a thinner and mat acrylic and also by using smaller magnets. This will prevent the shades during the photo-digitalisation process and improve the quality of the edges of the tile decorations. Additionally, building it double size will provide all geometric shapes which helps to build the tile decoration completely stable on the grid.

As a development plan; we can continue with 3D options but, we are not sure about how to integrate electronics on our project to develop for the next stages.

<div style="position: relative; width: 100%; height: 0; padding-top: 56.2500%;
 padding-bottom: 0; box-shadow: 0 2px 8px 0 rgba(63,69,81,0.16); margin-top: 1.6em; margin-bottom: 0.9em; overflow: hidden;
 border-radius: 8px; will-change: transform;">
  <iframe loading="lazy" style="position: absolute; width: 100%; height: 100%; top: 0; left: 0; border: none; padding: 0;margin: 0;"
    src="https:&#x2F;&#x2F;www.canva.com&#x2F;design&#x2F;DAFavYB6CeY&#x2F;view?embed" allowfullscreen="allowfullscreen" allow="fullscreen">
  </iframe>
</div>
<a href="https:&#x2F;&#x2F;www.canva.com&#x2F;design&#x2F;DAFavYB6CeY&#x2F;view?utm_content=DAFavYB6CeY&amp;utm_campaign=designshare&amp;utm_medium=embeds&amp;utm_source=link" target="_blank" rel="noopener">Tile Deco</a> by caglaralkan

Repository link;
https://github.com/paresmarc/tiledeco

##Class Task No:5##

Contrary to the previous tasks, rather than modeling some basic thing on Rhinoceros I decided to download a 3D shark model which has has connected pieces in order to test the 3D printers capacity. I downloaded the file from "thingiverse.com" and I discovered that the file has some specifications to help-support the printing process; as if it needs support for being built...

After exported the file in .stl format, I opened that in Ultimaker-Cura and slice it. Surprisingly, 3D printing process with filaments is easier than 3D printing process of clay. When we tried to print some water brick samples made of clay by 3D printing, we had to make 4-5 tests for nozzle distance and speed in order to get the best results. But, I guess as filaments are more stable material, it was fast and easy to get the results.

Furthermore, I wanted to print the model by the white filament to use it efficiently during the digital 3D scanning process, but as the white filament spool was heavy, I ended up using the black filament.

As I was expecting the black filament effected the process of the digital scanning in a negative way. I was not able to scan the shark with scanner. I tried to scan a asthma-spray pump. Unfortunately, there are some missing surfaces on it. I also tried to scan the bust as it is completely white and less surfaces towards the ground. The result was neither a success, nor a disaster. As long as it hasn't a complicated organic shape, I prefer to 3D model the object rather than 3D scanning.

<div style="position: relative; width: 100%; height: 0; padding-top: 56.2500%;
 padding-bottom: 0; box-shadow: 0 2px 8px 0 rgba(63,69,81,0.16); margin-top: 1.6em; margin-bottom: 0.9em; overflow: hidden;
 border-radius: 8px; will-change: transform;">
  <iframe loading="lazy" style="position: absolute; width: 100%; height: 100%; top: 0; left: 0; border: none; padding: 0;margin: 0;"
    src="https:&#x2F;&#x2F;www.canva.com&#x2F;design&#x2F;DAFbtvXtqlI&#x2F;view?embed" allowfullscreen="allowfullscreen" allow="fullscreen">
  </iframe>
</div>
<a href="https:&#x2F;&#x2F;www.canva.com&#x2F;design&#x2F;DAFbtvXtqlI&#x2F;view?utm_content=DAFbtvXtqlI&amp;utm_campaign=designshare&amp;utm_medium=embeds&amp;utm_source=link" target="_blank" rel="noopener">3D Shark with joints</a> by caglaralkan

##Class Task No:6##

Networking class with Victor was an introduction for creating network by using the Arduino software and local server. We worked within teams and try to connected to Victors computer by local server and Arduino software interface (especially serial monitor)

In order to connect to the Victors computer we need to change some specific parts of the code on Arduino. First of all, we needed to download PunSubClient library and we had to connect to the local network by changing the Wifi name and password on the code. Then, we also had to modify the mqttClientuser (Victor), topicToSub and mqttClientName(our team name). Actually, apart from those, Marielle changed some lines on the code but I couldn’t catch those parts. On the other hand, we were able to modify the message that we sent to Victors computer ( rather than saying “hello!”)

<div style="position: relative; width: 100%; height: 0; padding-top: 56.2500%;
 padding-bottom: 0; box-shadow: 0 2px 8px 0 rgba(63,69,81,0.16); margin-top: 1.6em; margin-bottom: 0.9em; overflow: hidden;
 border-radius: 8px; will-change: transform;">
  <iframe loading="lazy" style="position: absolute; width: 100%; height: 100%; top: 0; left: 0; border: none; padding: 0;margin: 0;"
    src="https:&#x2F;&#x2F;www.canva.com&#x2F;design&#x2F;DAFczTEsQDA&#x2F;view?embed" allowfullscreen="allowfullscreen" allow="fullscreen">
  </iframe>
</div>
<a href="https:&#x2F;&#x2F;www.canva.com&#x2F;design&#x2F;DAFczTEsQDA&#x2F;view?utm_content=DAFczTEsQDA&amp;utm_campaign=designshare&amp;utm_medium=embeds&amp;utm_source=link" target="_blank" rel="noopener">Coding for Network</a> by caglaralkan

##Class Task No:7##

Beyond blink-breathe-burn, todays class should be named as Coding Language-101. We started the session with “How hard can it be to turn on a LED?”and I can say that it would be so hard sometimes because of a misbehaved cable or disfunction LED or a wrong type of resistor.

I don’t know if its Oscars talent but somehow he was able to explain so many thing about the coding language. At least I was able to catch the steps during the class even some difficulties happened.

Oscar tried to move us forward in terms of networking through Arduino from the point that Victor started last week. Surprisingly, this was the best organized hands on learning session of the semester. We went through several steps; just by building a basic LED circuit we started with a “blink” command, and we tried to connected to a network and comment on a LED through an online dashboard.

Then, we discovered breathe and burn commands and some important shortcuts instead of repeating the lines in coding; (int I=0;i>5;i++) Also “defining functions” and “if, else if command lines in the loop” are the other meaningful discoveries for me. Even I am not able to figure it out completely this line.(int num_reps=3 int delay_time=500)I feel more comfortable and ready to work on coding more.

Another small but unexpected problem was even the code was correct because of so many people try to connect to the server at the same time, I was not able to connect the server. It took sometime for me to figure that out. I needed to reset the Arduino in order to connect to server and synchronize my Arduino and LED circuit with the others.

<div style="position: relative; width: 100%; height: 0; padding-top: 56.2500%;
 padding-bottom: 0; box-shadow: 0 2px 8px 0 rgba(63,69,81,0.16); margin-top: 1.6em; margin-bottom: 0.9em; overflow: hidden;
 border-radius: 8px; will-change: transform;">
  <iframe loading="lazy" style="position: absolute; width: 100%; height: 100%; top: 0; left: 0; border: none; padding: 0;margin: 0;"
    src="https:&#x2F;&#x2F;www.canva.com&#x2F;design&#x2F;DAFcE27a3hY&#x2F;view?embed" allowfullscreen="allowfullscreen" allow="fullscreen">
  </iframe>
</div>
<a href="https:&#x2F;&#x2F;www.canva.com&#x2F;design&#x2F;DAFcE27a3hY&#x2F;view?utm_content=DAFcE27a3hY&amp;utm_campaign=designshare&amp;utm_medium=embeds&amp;utm_source=link" target="_blank" rel="noopener">Coding Language-101</a> by caglaralkan

##Class Task No:8##

I started my CNC task by modeling a bed-side table on Rhinoceros. As I already knew the thickness of the plywood(15mm), I decided to build an interlocking bed-side table. After modeling the piece, I thought on the modifications on drawing which is necessary for the CNC cutting.

As I had decided to use 6mm end-mill, I modified the inner and outer corners of the pieces accordingly. It took more time than I expected. I booked the CNC machine for 11 a.m and arrived at 10 a.m in order to prepare the file for RhinoCam, but it took two and a half hours to start.

Beside the preparation of the drawings, there are a lot of parameters that we need to modify for cutting and pocketing. I worked with Josep and he suggested to use “pocketing” function to cut small holes for safety reason to prevent any accident. We also defined the screws as the first cut(work piece). I decided to use 2 different 6mm end-mills for cutting. (6mm ball for pocketing and 6mm flat for cutting)

Finishing up the work at Rhino-Cam, we located the 2440X1220mm plywood on the CNC machine. The next step was defining the x-y-z for the machine. For X and Y we used our eye and for Z we used the small button attached to the CNC. The first cut was for the screws. After, applying the screws manually, the pocketing started and we needed to change the end-mill to flat for the final cutting.

I made a mistake in the design and had to cut an extra piece. And during that process we made another mistake on the surface and location of the workpiece on Z coordinate. Fortunately, the work piece was over the surface and we did not had a big accident.

The following steps was sanding and assembling the pieces. Unexpectedly, sanding the edges and surfaces took so much time. But, at the end I felt satisfy with the result.

<div style="position: relative; width: 100%; height: 0; padding-top: 56.2500%;
 padding-bottom: 0; box-shadow: 0 2px 8px 0 rgba(63,69,81,0.16); margin-top: 1.6em; margin-bottom: 0.9em; overflow: hidden;
 border-radius: 8px; will-change: transform;">
  <iframe loading="lazy" style="position: absolute; width: 100%; height: 100%; top: 0; left: 0; border: none; padding: 0;margin: 0;"
    src="https:&#x2F;&#x2F;www.canva.com&#x2F;design&#x2F;DAFc__TayXc&#x2F;view?embed" allowfullscreen="allowfullscreen" allow="fullscreen">
  </iframe>
</div>
<a href="https:&#x2F;&#x2F;www.canva.com&#x2F;design&#x2F;DAFc__TayXc&#x2F;view?utm_content=DAFc__TayXc&amp;utm_campaign=designshare&amp;utm_medium=embeds&amp;utm_source=link" target="_blank" rel="noopener">Building a Bedside Table by CNC cutting</a> by caglaralkan

##Challenge No:2##

We decided to develop the tile decorating kit that we designed during the challenge-1. We mostly wanted to focus on digitalization process in order to make it as easy and meaningful as possible. Additionally, we wanted to convert it from 2D to 3D as one of the goal that we set before. In other words, it become a playground to discover 3d fabrication which is a bridge between a physical object and digital representative, more than a tile decorating kit.

We had some reference projects to help us: MIT's interactive shape-shifting table, and Reactivision Improvisation with MIDI (Reactable). At the end we had to simplify or goals because of the time limitation.

As it is a project connects the physical and digital, it has a lot of details that needs to be solved. This time, we took the base-grid as a playground and decided to let people to play, change, combine the cubes that attached to it and positioned by magnets in order to build their unique design on the grid rather than 2D geometric shapes.

We started with the digitalization process. We thought a lot on the process how to convert the physical items to digital representatives. We discovered a system called “fiducial id” works like QR codes(with more organic shapes drawings) through cameras. Fiducial IDs can be captured by any cameras and work with a plug-in program called “firefly” in Grasshopper-Rhinoceros. Each cube that we play-locate on the grid has a unique “Fiducial ID”on it, and this gives it a parameter on the Z axis to help to form a unique 3D design.

On the other hand, as camera detects the cubes on the grid and let the user to move them freely on it, we also needed to program the Grasshopper to detect the grid made of slots(6x6) in order to frame design area and make the post-digitalization process easier. Through that process we had lots of problems: we couldn’t solve the problem of the camera detecting the fiducials repeatedly. This process creates a lot of trash on the system and at the end we decided to reset the system as a solution to that problem.

Beside the digitalization, we also worked a lot on the physical object. Firstly, we 3D printed the cubes which made of two parts and use 6 magnets in it. But, this method was not appropriate because it took 3 hours for each cube. So we ended up with the idea to build the cubes made of wood and we had to insert the magnets on surfaces.

As we had sphere shape magnets, it was a real concern to be able to insert the magnets in the right magnetic directions. We designed a magnet insert (nest) for each magnet to eliminate that problem and we 3D printed them from raisin. Sphere shape magnets can move in the nest and find their magnetic direction easily. Furthermore, we tried to raster the fudicials on cubes with laser cutter but the camera didn’t detect it. Thus, we engraved the outlines and drew by hand at the end. We couldn’t use vinyl because vinyl does not stick on the wood properly.

Moreover, we had more trouble to cut the cubes out of the oak block. The block was 33 mm thick and we had to carve the surface 3mm to get 30mm thickness. We did that with the help of Adai and Edu. Through that process we discovered the facing function of the RhinoCam-CNC which provides the carving function with the end-mill has 30mm diameter. The other problem was to use the material efficiently: in order to eliminate material loss in CNC Adai made me to cut the cubes ( as we needed a lot of cubes) with the manual saw which needs a lot of attention and physical job.

After engraving the fiducials in laser cutter we cut the cubes with manual saw and we drilled each surfaces (again) manually in order to insert the magnets with their 3D printed nests.

Additionally, we used the CNC machine to build the grid out of plywood. We designed and laser cut acrylic in order to build a structure to hold camera above the grid. That structure was designed in order to be located in different positions on the grid to get the right frame and capture the cubes clearly.

Mostly we used the grasshopper for digitalization process. But, we also added the arduino in order to use the firefly plug-in and we also added a button to arduino in order to capture the desired design and to build that with the 3D printer.

**Personal note:**

As the challenges has to be done by groups, at a certain point projects become complicated and at that point most of the tasks has to be done by different colleagues. So normally, because of the need of using the time efficiently, each one ends up with working on the field that he/she has more experience. This ends with the lack of opportunity to improve some other skills. In short, I want to say that I prefer to have more classes on coding like the one that Oscar gave. During each challenge I was not able to improve my coding skills  because as I am a maker I had to work on the machines and 3d modeling. And also we didn’t have time to stay and worked-discover-learn from my classmates. To sum up, I have doubts about the efficiency of challenges. I cannot say that I didn’t discover or learn anything, but I really prefer to have more time and opportunity to have more confidence in coding. But, challenge weeks are so intense and do not let me to discover-learn the coding neither from instructors nor colleagues.

Link for the repo of challange#2:

https://github.com/paresmarc/pixelcubes
