## Table of Contents
- [Introduction](https://github.com/kwan22/habits/blob/main/README.md)
- [Level 1](https://github.com/kwan22/habits/blob/main/level1.md)
- [Level 2](https://github.com/kwan22/habits/blob/main/level2.md)
- [Level 3](https://github.com/kwan22/habits/blob/main/level3.md)
- [Level 4](https://github.com/kwan22/habits/blob/main/level4.md)
- [Closing thoughts and FAQ](https://github.com/kwan22/habits/blob/main/conclusions-faq.md)

## Level 4

Level 4 begins a deeper dive into some of the fundamentals of movement as well as more detailed inner workings of game mechanics and niche situations in which these arise. Situations become more specific and technical: understanding the inner workings is not required to execute the strats, but the details are not obviously available to a player without researching game mechanics and physics. Concepts start to become increasingly complicated, so several examples are provided for illustration. Use of speedrun tool is highly useful for timing movement options. Use of TAS tools can be useful for those interested in diving into the science.

#### Know the speed hierarchy  
Know some of the nuanced properties of dashes, wallbounces, jumps, etc. to understand how to resolve bottlenecks.

#### Conscious of bottlenecks  
A general understanding of what bottlenecks are and how they influence all of movement. This is usually divided between resolving a horizontal vs vertical bottleneck, but can also be dictated by other factors such as activating an entity. The goal is to be conscious of these: some are difficult to greed and optimize well and may compromise consistency, but having awareness of these provides us with guidance on what the limits are.

<details>
  <summary>Supers and hypers</summary>
  Hypers are overall used far more often than supers, but occasionally supers are useful in resolving a vertical bottleneck that still needs to cover some horizontal ground. <br>
  <img src="https://github.com/kwan22/habits/blob/main/images/lv4/1a_crossing6_super.webp" width="480">
  <img src="https://github.com/kwan22/habits/blob/main/images/lv4/3a_start_post-triplat_super.webp" width="480"> <br>
  In both of these cases, a hyper would require an extra climbjump.
</details>

<details>
  <summary>Dashes, wallbounces and walljumps </summary>
  When wallbouncing for upwards movement, dash upwards for as much of the dash state as possible to maximize use of dash speed. One way to think of this is perform an "extended hyper" timing, but upwards. The extension timing can be biased to be on the later side of the window. Jumping slightly late on the "extension timing" is still allowed thanks to dash-attack leniency. Jumping should be minimized as much as possible compared to dashing and wallbouncing. <br>
   <img src="https://github.com/kwan22/habits/blob/main/images/lv4/wb_vertical_compilation.png" width="960"> <br>
  These spots are some of the most common movement mistakes by beginners. In all cases, 0 groud or walljumps are required: an updash and late wallbounce is sufficient and optimal.

  Conversly, when the height of the wallbounce (or walljump) is needed but the bottleneck is horizontal, then an early jump as possible is desired. Many transition wallbounces fall under this category, where vertical speed is reset to jump speed upon transition, but the horizontal speed from the wallbounce is also helpful. <br>
   <img src="https://github.com/kwan22/habits/blob/main/images/lv4/1a_crossing_3_wb.webp" width="480"> 
   <img src="https://github.com/kwan22/habits/blob/main/images/lv4/7a_1k_trans_wb_2.webp" width="480"> <br>

  Updemo wallbounces add another option to control the wallbounce height. Updemo _approximately_ shifts the lowest possible wallbounce position higher by half a tile, enabling some buffer setups that minimize vertical bottlenecks and removing possible low wallbounce positions. <br>
   <img src="https://github.com/kwan22/habits/blob/main/images/lv4/1a_start_5_updemo.webp" width="480"> 
   <img src="https://github.com/kwan22/habits/blob/main/images/lv4/4a_start_updemo.webp" width="480">   

   Diagonal dashes still have faster vertical speed the jumping. When diagonal dashing upwards to get over a wall, try to reach the wall at the end of the dash. Minimize time spent sliding along the wall while dashing: this usually means you could have dashed earlier. <br>
  <img src="https://github.com/kwan22/habits/blob/main/images/lv4/7a_2500m_diagdash.png" width="960">   
</details>

<details>
  <summary>Downwards movement</summary>
<blockquote>
<details>
  <summary>Avoiding downwards collisions</summary>
  A frequent pattern to look out for is colliding with the ground when trying to move downwards. This commonly happens shortly after a transition. Different problems call for different movement options: hypering or supering shortly before or on transition, releasing jump during transition, and holding downdiagonal are common patterns. Be aware of which setup works best for each problem. By avoiding collision, we can clear the ground with some vertical speed to resolve the downwards bottleneck. <br>
  Instant hyper or super before transition <br>
  <img src="https://github.com/kwan22/habits/blob/main/images/lv4/1a_crossing_6_exit.webp" width="480"> 
  <img src="https://github.com/kwan22/habits/blob/main/images/lv4/7a_1500m_dog_exit.webp" width="480"> <br>
  Some transition hypers are guaranteed to avoid collisions no matter how small the jump height. <br>
  <img src="https://github.com/kwan22/habits/blob/main/images/lv4/2a_intervention_top_exit.webp" width="480"> 
  <img src="https://github.com/kwan22/habits/blob/main/images/lv4/7a_1500m_neutral_trans_hyper.webp" width="480"> 
</details>

  <details>
    <summary>Avoiding downwards dashes</summary>
    Downdashes and downdiagonal dashes can be deceptively slow may exacerbate a vertical bottleneck. <br>
    When clearing a pillar, a horizontal dash is often preferred as it can be started earlier than a downdiagonal dash and enter fastfall state sooner. <br>
  <img src="https://github.com/kwan22/habits/blob/main/images/lv4/horiz_dashes.png" width="960"> <br>
  Downwards dashes (e.g. extended hyper into downright) interrupt fastfalling and may be outright slower than not dashing at all against vertical bottlenecks. <br>
  One of the most common mistakes from beginners is to try to extended hyper into downright into the last Badeline hit in 6a, when a simple short hyper is faster. <br>
  <img src="https://github.com/kwan22/habits/blob/main/images/lv4/6a_rb_hyper.webp" width="480"> 
  </details>
</blockquote>



</details>


  
##### Minimizing speed bumps in the bottlenecked direction  
- 2a awake: hyper bhop instead of transition hyper cb (into downright hyper for 1.2x multiplier instead of demohyper)
- 5a depths 2nd button: upright demo under the block be able to dash earlier, avoid bonk, and land earlier

##### Activating entities asap (zippers, swapblocks, crumbles)
- in general, can only grab while moving downwards to activate blocks (e.g. 4a trail pre 2nd blockless, 500m coin exit, 7a 2k vertical)
- 5a dcb, early dash setup to initiate block movement
- Removing crumbles fast+consistently with ext hyper/wave: 2a intervention 5b cc pre spikejump, 7a 2500m fast key

#### Know the speed hierarchy  
This goes hand in hand with being conscious of bottlenecks. Know some of the nuanced properties of dashes, wallbounces, jumps, etc. Emphasis that dashing downwards, especially diagdown, can be deceptively slow for vertical bottleneck.  
If you updash near a wall, prefer wallbounce over climbjumping unless absolutely necessary (e.g., 5a tape room).

- 1a crossing-3, 7a 500m-2 right dash 
- 1a chasm2 ending
- 2a start downright for 1.2x into blockbreak
- 2a start near-end wallbounce
- 3a boxes final wallbounce
- 3a suite-2 ending downright for 1.2x
- 4a trail/cliff face wallbounces
- 5b cc-1 cornerglide
- 6a rb last badeline: instant hyper over ext hyper ultra
- 7a 1000m-2: dj upright, transition wallbounce (ties into dashcd)
- 7a 0m orb early left dash, fast fall
- 7a 2500m-3 avoid upright along the wall
- 7a 2500m key door: only 1 downright

#### DashCD control  
Awareness of DashCD and movement to intentionally avoid or retain DashCD for setups. Selection of instant hyper, hyper bhop, vs ext-hyper. Buffering dashes out of DashCD, related to grounded ultra timing. Managing DashCD from vertical transitions (canceling vertical momentum, 3a-suite cutscene delay) and developing intuition for buffering out of vertical DashCD.

- 1a chasm-2, 3a start post triplat transition cj for ext super
- 2a start before mirror: ext hyper
- 4a 1st block ultra
- 5a start fast cycle
- 5b pillarful: ext hyper
- 6a hollows kevin slide
- 7a 1500m entering 1-coin room
- 7a 2500m cornerglide
- 7a 2500m orb entry springskip

#### Option-selecting movement  
Making decisions to cover multiple possible outcomes to reduce risk at little/no cost.

##### Holding into the wall for wallkicks for forcemove  
- 3a start post triplat, 7a 3k flag14: hold left for wallkick

##### Using dash-attack leniency on wallbounces to hold toward a wall  
- 3a suite-1
- 4a start final
- 7a 500m-1

##### Pressing extra buttons to cover unexpected scenarios  
General cornerkicks: 2 jump inputs to cover weird timing  
Holding grab to cover aggressive movement, e.g. missed clean landing, missed wave on a corner
- 2a awake exiting checkpoint room
- 3a shaft 1st berry room ending
- 7a 2000m pre-orb

#### Simple pausebuffer timing  
Learning to buffer the pause at the start of 2a-Intervention and 3a-Suite segways into learning bubsdrop. This will be the only pausebuffer strat learned in the habits, but also acts as a gateway for learning more complicated pausebuffer strats for those who wish to go further.

[&#8593; Main page](https://github.com/kwan22/habits/blob/main/README.md)

[&#8592; Level 3](https://github.com/kwan22/habits/blob/main/level3.md) 

[Conclusions &#8594;](https://github.com/kwan22/habits/blob/main/conclusions-faq.md)
