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
  Hypers are overall used far more often than supers, but occasionally supers are useful in resolving a vertical bottleneck that still needs to cover some horizontal ground. These are frequently followed by a precise updash, which are easier to time with a super thanks to the reduced horizontal speed. <br>
  <img src="https://github.com/kwan22/habits/blob/main/images/lv4/1a_crossing6_super.webp" width="480">
  <img src="https://github.com/kwan22/habits/blob/main/images/lv4/7a_flag21_super.webp" width="480"> <br>
  In both of these cases, a hyper would require an extra climbjump.
</details>

<details>
  <summary>Dashes, wallbounces and walljumps </summary>
  When wallbouncing for upwards movement, dash upwards for as much of the dash state as possible to maximize use of dash speed. One way to think of this is perform an "extended hyper" timing, but upwards. The extension timing can be biased to be on the later side of the window. Jumping slightly late on the "extension timing" is still allowed thanks to dash-attack leniency. Jumping should be minimized as much as possible compared to dashing and wallbouncing. <br>
   <img src="https://github.com/kwan22/habits/blob/main/images/lv4/wb_vertical_compilation.png" width="960"> <br>
  These spots are some of the most common movement mistakes by beginners. In all cases, 0 ground or walljumps are required: an updash and late wallbounce is sufficient and optimal.

  Conversly, when the height of the wallbounce (or walljump) is needed but the bottleneck is horizontal, then an early jump as possible is desired. Many transition wallbounces fall under this category, where vertical speed is reset to jump speed upon transition, but the horizontal speed from the wallbounce is also helpful. <br>
   <img src="https://github.com/kwan22/habits/blob/main/images/lv4/1a_crossing_3_wb.webp" width="480"> 
   <img src="https://github.com/kwan22/habits/blob/main/images/lv4/7a_1k_trans_wb_2.webp" width="480"> <br>

  In general though, most optimal wallbounce positions are arbitrarily dependent on the exact geometry of the room. Updemo wallbounces add another option to control the wallbounce height. Updemo _approximately_ shifts the lowest possible wallbounce position higher by half a tile, enabling some buffer setups that minimize vertical bottlenecks and removing possible low wallbounce positions. <br>
   <img src="https://github.com/kwan22/habits/blob/main/images/lv4/1a_start_5_updemo.webp" width="480"> 
   <img src="https://github.com/kwan22/habits/blob/main/images/lv4/4a_start_updemo.webp" width="480">   
   <img src="https://github.com/kwan22/habits/blob/main/images/lv4/5b_ttm2_updemo.webp" width="480">   

   Diagonal dashes still have faster vertical speed the jumping. When diagonal dashing upwards to get over a wall, try to reach the wall at the end of the dash. Minimize time spent sliding along the wall while dashing: this usually means you could have dashed earlier. <br>
  <img src="https://github.com/kwan22/habits/blob/main/images/lv4/7a_2500m_diagdash.png" width="960">  <br>
</details>

<details>
  <summary>Downwards movement</summary>
<blockquote>
<details>
  <summary>Downwards collisions</summary>
  A frequent pattern to look out for is colliding with the ground when trying to move downwards. This commonly happens shortly after a transition. Different problems call for different movement options: hypering or supering shortly before or on transition, releasing jump during transition, and holding downdiagonal are common patterns. Be aware of which setup works best for each problem. By avoiding collision, we can clear the ground with some vertical speed to resolve the downwards bottleneck. <br>
  Instant hyper or super before transition <br>
  <img src="https://github.com/kwan22/habits/blob/main/images/lv4/1a_crossing_6_exit.webp" width="480"> 
  <img src="https://github.com/kwan22/habits/blob/main/images/lv4/7a_1500m_dog_exit.webp" width="480"> <br>
  Some transition hypers are guaranteed to avoid collisions no matter how small the jump height. <br>
  <img src="https://github.com/kwan22/habits/blob/main/images/lv4/2a_intervention_top_exit.webp" width="480"> 
  <img src="https://github.com/kwan22/habits/blob/main/images/lv4/7a_1500m_neutral_trans_hyper.webp" width="480"> 
</details>

  <details>
    <summary>Downwards dashes</summary>
    Downdashes and downdiagonal dashes can be deceptively slow and may exacerbate a vertical bottleneck. When clearing a pillar, a horizontal dash is often preferred as it can be started earlier than a downdiagonal dash and enter fastfall state sooner. <br>
  <img src="https://github.com/kwan22/habits/blob/main/images/lv4/horiz_dashes.png" width="960"> <br>
  Downwards dashes (e.g. extended hyper into downright) interrupt fastfalling and may be outright slower than not dashing at all against vertical bottlenecks. One of the most common mistakes is to try to extended hyper into downright into the springs just before the last Badeline hit in 6a, when a simple short hyper is faster. Another is to dash diagonally downwards twice towards the 2500m door, when one is optimal because of the vertical bottleneck. <br>
  <img src="https://github.com/kwan22/habits/blob/main/images/lv4/6a_rb_hyper.webp" width="480">
  <img src="https://github.com/kwan22/habits/blob/main/images/lv4/7a_2500m_keydoor.webp" width="480">    
  </details>
</blockquote>
</details>

<details>
  <summary>Activating entities</summary>
  Some entities are optimal to activate by grabbing. The key takeaway is that grabbing can only happen when Madeline is not moving upwards. Make sure she is not moving upwards by releasing jump well before reaching a block you are trying to activate by grabbing.
  <img src="https://github.com/kwan22/habits/blob/main/images/lv4/7a_500m_coin_exit.webp" width="480">
  <img src="https://github.com/kwan22/habits/blob/main/images/lv4/7a_2k_vert.webp" width="480"> <br>
  Extended hypers/wavedashes happen to work very well for getting crumble blocks to disappear quickly and consistently.
  <img src="https://github.com/kwan22/habits/blob/main/images/lv4/2a_intervention_crumble.webp" width="480">
  <img src="https://github.com/kwan22/habits/blob/main/images/lv4/5b_cc_crumbles.webp" width="480">
</details>

<details>
  <summary>Case study: Central Chamber cornerglide</summary>
  The details that make this cornerglide consistent are
  
  - Jump late on the wallbounce in the previous room.
  - Aim to line up the midair demohyper from the center of the transition jumpthrough.
  - Demohyper and upright around the middle of the seeker statue.

  <img src="https://github.com/kwan22/habits/blob/main/images/lv4/5b_cc1_cg.webp" width="480">

  The late wallbounce on the previous room follows good vertical movement principles, but also helps Madeline not move too far right. In the hub room, we purposely do not move to the right but aim to be above the middle of the transition jumpthrough. Rightward motion is irrelevant (and even detrimental) since the bottleneck for this movement becomes vertical. Staying in the middle creates space to gain height for the demohyper-upright to cornerglide into the next room. The upright dash needs to be timed so that the dash hits the end wall with minimal (<5f) sliding.
</details>

#### DashCD control 
Awareness of DashCD and movement to intentionally avoid or retain DashCD for setups. Selection of instant hyper, hyper bhop, vs ext-hyper. Buffering dashes out of DashCD, related to grounded ultra timing. Managing DashCD from vertical transitions (canceling vertical momentum, 3a-suite cutscene delay) and developing intuition for buffering out of vertical DashCD.

<details>
  <summary>Grounded ultra timing</summary>
  Adjacent to extension timing, the timing for buffering a dash (e.g. downdiagonal) out of a dash (e.g. extended hyper) becomes important. This is useful for maximizing the speed out of ultras and makes some setups faster and more consistent. <br>
  <img src="https://github.com/kwan22/habits/blob/main/images/lv4/3a_start_ultras.webp" width="480">
  <img src="https://github.com/kwan22/habits/blob/main/images/lv4/4a_shrine_ultra.webp" width="480">
  <img src="https://github.com/kwan22/habits/blob/main/images/lv4/6a_hollows_2.webp" width="480">
  <img src="https://github.com/kwan22/habits/blob/main/images/lv4/7a_2500m_cg.webp" width="480"> <br>
</details>

<details>
  <summary>Avoiding DashCD</summary>
  Sometimes, we need to slow down before we can speed up. DashCD is preserved through horizontal screen transitions: sometimes we need to start a dash immediately upon crossing such a transition with the maximum amount of speed. A common pattern is to late extended hyper just before entering a room, and then getting a fast grounded ultra when starting the next room. Whether we actually extend or not is irrelevant; we just want to enter the next room with 0 DashCD and near-max speed from the hyper. 
  <img src="https://github.com/kwan22/habits/blob/main/images/lv4/2a_start_gultra.webp" width="480">
  <img src="https://github.com/kwan22/habits/blob/main/images/lv4/5a_start_fastkey.webp" width="480">
  <img src="https://github.com/kwan22/habits/blob/main/images/lv4/5b_ttm_pillars_cut1.webp" width="480">
  <img src="https://github.com/kwan22/habits/blob/main/images/lv4/7a_2500m_orb_entry.webp" width="480">
</details>

<details>
  <summary>Retaining DashCD</summary>
  Some setups and movement intentionally retain DashCD to make a dash in the next room more lenient by allowing to be bufferable. These require precise positioning at the end of the previous room where the dash starts. Keep in mind that the dash in the next room is buffered out of DashCD, which is slightly after the transition ends. <br>
  <img src="https://github.com/kwan22/habits/blob/main/images/lv4/5b_mm_final.webp" width="480">
  <img src="https://github.com/kwan22/habits/blob/main/images/lv4/6a_hollows_kevinslide.webp" width="480">
</details>

<details>
  <summary>Vertical transitions</summary>
  Upwards trajectory and DashCD is fixed upon vertical transitions. While we must wait for DashCD to expire before dashing, we can cancel upwards trajectory if we are next to a wall by climbjumping. A small climbjump pairs well with a jumpthrough for cornercorrection leniency to line up midair supers and demohypers.<br>
  <img src="https://github.com/kwan22/habits/blob/main/images/lv4/1a_chasm_2_super.webp" width="480">
  <img src="https://github.com/kwan22/habits/blob/main/images/lv4/3a_start_post-triplat_super.webp" width="480">
</details>

#### Cornerkick setups
Adding to the repertoire of strats that rely on buffering from Level 3. A rule of thumb is to aim to dash to the corner from 3.5 tiles away horizontally. These are frequently easier with an updiagonal demo if height is not an issue, but dealing with the crouch state can lead to the cornerkick timing feeling awkward, as sometimes you need to wait for Madeline to uncrouch before getting the cornerkick.

<details>
  <summary>Forward cornerkicks</summary>
  <img src="https://github.com/kwan22/habits/blob/main/images/lv4/5b_ttm_3_ck.webp" width="480">
  <img src="https://github.com/kwan22/habits/blob/main/images/lv4/5b_ttm_pillars_ck.webp" width="480">
  <img src="https://github.com/kwan22/habits/blob/main/images/lv4/7a_500m_ck.webp" width="480">
  <img src="https://github.com/kwan22/habits/blob/main/images/lv4/7a_flag17_ck.webp" width="480">
</details>

<details>
  <summary>Neutral and turnarounds</summary>
  These require slightly more technical precision with having to go neutral or turnaround grab before the jump input. 5b spikejump is included here as well despite not being out of a dash due to the strict requirement of being a neutral cornerkick.
  <img src="https://github.com/kwan22/habits/blob/main/images/lv4/1a_chasm_ck.webp" width="480">
  <img src="https://github.com/kwan22/habits/blob/main/images/lv4/2a_intervention_tcj.webp" width="480">
  <img src="https://github.com/kwan22/habits/blob/main/images/lv4/5b_cc_spikejump.webp" width="480">
</details>

#### Option-selecting movement  
Making decisions to cover multiple possible outcomes to reduce risk at little/no cost.

<details>
  <summary>Hold towards the wall for wallbounces and wallkicks</summary>
  Hold towards the wall and release grab to keep dash-attack leniency for wallbounces or to get ForceMove from wallkicks. This makes the window to hit the wallbounce slightly larger, and reduces the risk of moving away from the wall before getting the wallkick. <br>
  <img src="https://github.com/kwan22/habits/blob/main/images/lv4/wallbounce_kick_leniency.png" width="960">
</details>

<details>
  <summary>Press extra buttons for safety</summary>
  Hold grab to cover overly aggressive movement, such as a missed clean landing to prevent accidental wallkick or otherwise unwanted results.
  <img src="https://github.com/kwan22/habits/blob/main/images/lv4/holdgrab.png" width="960">  
</details>

#### Simple pausebuffer timing  
Learning to buffer the pause at the start of 2a-Intervention and 3a-Suite segways into learning bubsdrop. This will be the only pausebuffer strat learned in the habits, but also acts as a gateway for learning more complicated pausebuffer strats for those who wish to go further.

[&#8593; Main page](https://github.com/kwan22/habits/blob/main/README.md)

[&#8592; Level 3](https://github.com/kwan22/habits/blob/main/level3.md) 

[Conclusions &#8594;](https://github.com/kwan22/habits/blob/main/conclusions-faq.md)
