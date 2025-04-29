# cs2261-lab09--complex-movement-solved
**TO GET THIS SOLUTION VISIT:** [CS2261 Lab09- Complex Movement Solved](https://www.ankitcodinghub.com/product/cs-2261-solved-2/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;109934&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS2261 Lab09- Complex Movement Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
Lab09: Complex Movement

Provided Files

● main.c

● myLib.c

● myLib.h

● game.c

● game.h

● house.bmp

● house.c

● house.h

● spritesheet.bmp

● spritesheet.c

● spritesheet.h

● collisionmap.bmp

Files to Edit/Add

● game.c

● collisionmap.c

● collisionmap.h

● Your Makefile

● Your tasks.json

Instructions

TODO 1 – Complex Camera Movement We want our pikachu to walk only on the screen, and have the camera follow it without showing something outside of the world.

● TODO 1.0: In game.c, in the updatePlayer() function, add in the sprite and camera movement.

Your pikachu should now be able to walk around and see the entire map, but not off of the edge. The pikachu should always be in the middle of the screen unless at the edge of the map (see the example.gba).

TODO 2 – Collision Map Now we want our pikachu to treat the visuals of the map as if they were actual barriers to movement.

● TODO 2.0: The collision map has been created for you. Open collisionmap.bmp in Usenti and export it. Remember that we want to check the colors of each pixel, so take that into account when choosing export settings. As such, export the collision map as bitmap(GBA) and select 16 bpp. Uncheck the Pal box.

● TODO 2.1: Include collisionmap.h in game.c.

● TODO 2.2: Update your movement code to only allow pikachu to move if the collision map allows it (is white) in the areas that you need to check. Your pikachu should not be able to walk over the house or the bushes. The pikachu should be able to walk between the house and the bushes on the right and top, in both directions.

Submission Instructions Zip up your entire project folder, including all source files, the Makefile, the tasks.json, and everything produced during compilation (including the .gba file). Submit this zip on Canvas. Name your submission

Lab09_FirstameLastname, for example:“Lab09_DarthVader.zip”.
