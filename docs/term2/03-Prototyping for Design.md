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
