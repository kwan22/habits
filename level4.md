[Back to main page](https://github.com/kwan22/habits/blob/main/README.md)

# Level 4

<img src = "https://github.com/kwan22/habits/blob/main/images/lv4.png" width = "960">

Level 4 begins a deeper dive into some of the fundamentals of movement as well as more detailed inner workings of game mechanics and niche situations in which these arise. Situations become more specific and technical: understanding the inner workings is not required to execute the strats, but the details are not obviously available to a player without researching game mechanics and physics. Concepts start to become increasingly complicated, so several examples are provided for illustration. We also switch to the 5b route as the concepts used here make 5b viable and instructive. Use of speedrun tool is highly useful for timing movement options. Use of TAS tools can be useful for those interested in diving into the science.

## Table of Contents
- [Speed hierarchy](#speed-hierarchy)
- [Bottlenecks](#bottlenecks)
- [DashCD](#dashcd)
- [Applied buffering](#applied-buffering)
- [Option-selecting](#option-selecting)
  
## Speed hierarchy  
Know the key properties of the speed tech and how they compare to each other.

Without going into too much detail, a rough ordering of speed tech, from fastest to slowest, is as follows:

Horizontal:
- Hyper
- Super
- Horizontal dash
- Diagonal dash
- Wallbounce
- Jump
- Walk

Vertical (upwards):
- Up dash
- Diagonal dash
- Wallbounce
- Jump
- Hyper

Jumps give a small speed boost and ultras give a 1.2x multiplier. Air friction is weaker than ground friction, which is weaker than crouchsliding friction. All jumps have a short duration at the beginning where they ignore gravity while jump is held. Dashes ignore friction, wind, and retain horizontal speed when sufficiently fast.

[TAS documentation](https://docs.google.com/document/d/1RVXyO7AZB-r7X3FxkxrBob775qWdhfOyBEOGGbnTgws) provides much more details.

<details>
  <summary>1.2x multiplier</summary>
  At high speed, a grounded downright dash becomes faster than a right dash. Here are a couple of examples where it is less visually obvious that performing a downdiagonal for the multiplier is faster than a horizontal dash/demo. <br>
  <img src="https://github.com/kwan22/habits/blob/main/images/lv4/2a_start_1,2x.webp" width="480">
  <img src="https://github.com/kwan22/habits/blob/main/images/lv4/3a_suite2_1,2x.webp" width="480"> <br>  
</details>

<details>
  <summary>Delayed transition tech</summary>
  It can be better to not buffer the transition hyper or wallbounce if the dash is coming in with high speed, e.g. a grounded ultra, or to reach higher heights for the wallbounce. <br>
  <img src="https://github.com/kwan22/habits/blob/main/images/lv4/4a_shrine_wb.webp" width="480">
  <img src="https://github.com/kwan22/habits/blob/main/images/lv4/4a_cf_2.webp" width="480"> <br>
  See how late the wallbounce and hypers can be after transition. For this transition wallbounce in Shrine, it makes lining up the next wallbounce easier and enables enough height to get the left-side exit. For the grounded ultra in Cliff Face, not only does it carry more speed naturally but it's also better at cutting through the strong wind. <br>
  <img src="https://github.com/kwan22/habits/blob/main/images/lv4/4a_shrine_wb.png" width="480">
  <img src="https://github.com/kwan22/habits/blob/main/images/lv4/4a_cf_2.png" width="480"> <br>
</details>

## Bottlenecks  
A general understanding of what bottlenecks are and how they influence all of movement. This is usually divided between resolving a horizontal vs vertical bottleneck, but can also be dictated by other factors such as activating an entity. The goal is to be conscious of these: some are difficult to greed and optimize well and may compromise consistency, but having awareness of these provides us with guidance on what the limits are.

<details>
  <summary>Supers and hypers</summary>
  Hypers are overall used far more often than supers, but occasionally supers are useful in resolving a vertical bottleneck that still needs to cover some horizontal ground. These are frequently followed by a precise updash, which are easier to time with a super thanks to the reduced horizontal speed. <br>
  <img src="https://github.com/kwan22/habits/blob/main/images/lv4/1a_crossing_6_super.webp" width="480">
  <img src="https://github.com/kwan22/habits/blob/main/images/lv4/7a_flag21_super.webp" width="480"> <br>
</details>

<details>
  <summary>Dashes, wallbounces and walljumps </summary>
  In general, most optimal wallbounce positions are arbitrarily dependent on the exact geometry of the room. However, when wallbouncing purely for vertical movement, it's best to dash upwards for as much of the dash state as possible to maximize use of dash speed. One way to think of this is perform an "extended hyper" timing, but upwards. The extension timing can be biased to be on the later side of the window. Jumping slightly late on the "extension timing" is still allowed thanks to dash-attack leniency. Jumping should be minimized as much as possible compared to dashing and wallbouncing. Look for 2 or 3 dash silhouettes as an indicator of a late wallbounce. <br>
   <img src="https://github.com/kwan22/habits/blob/main/images/lv4/wb_vertical_compilation.png" width="960"> <br>
  These spots are some of the most common movement mistakes by beginners. In all cases, 0 ground or walljumps are required: an updash and late wallbounce is sufficient and optimal.

  Conversely, when the height of the wallbounce (or walljump) is needed but the bottleneck is horizontal, then an early jump as possible is desired. Many transition wallbounces fall under this category. Vertical speed is reset to jump speed upon a vertical transition, so the advantage of having vertical dash speed is not retained through transitions. The horizontal speed from the wallbounce might be more useful. <br>
   <img src="https://github.com/kwan22/habits/blob/main/images/lv4/1a_crossing_3_wb.webp" width="480"> 
   <img src="https://github.com/kwan22/habits/blob/main/images/lv4/7a_1k_trans_wb_2.webp" width="480"> <br>

  Updemo wallbounces add another option to control the wallbounce position. Updemo _approximately_ shifts the lowest possible wallbounce position higher by half a tile, enabling some buffer setups by removing possible low wallbounce positions. <br>
   <img src="https://github.com/kwan22/habits/blob/main/images/lv4/1a_start_5_updemo.webp" width="480"> 
   <img src="https://github.com/kwan22/habits/blob/main/images/lv4/4a_start_updemo.webp" width="480">   
   <img src="https://github.com/kwan22/habits/blob/main/images/lv4/5b_ttm2_updemo.webp" width="480">   

   Diagonal dashes still have faster vertical speed than jumping. When diagonal dashing upwards to get over a wall, try to reach the wall at or near the end of the dash. Minimize time spent sliding along the wall while dashing: time spent sliding usually means the dash could have been earlier to start gaining height sooner. The dash ends when the 3rd silhouette appears. <br>
  <img src="https://github.com/kwan22/habits/blob/main/images/lv4/7a_2500m_diagdash.png" width="960">  
</details>

<details>
  <summary>Crossover</summary>
  The bottleneck depends on the route your strat takes and can rapidly switch between horizontal and vertical. Be conscious of when/where crossovers happen. For example, on the final climb on Flag 7, the bottleneck changes from vertical to horizontal at the lowest possible position where a wallkick can reach the Badeline orb. <br>
  <img src="https://github.com/kwan22/habits/blob/main/images/lv4/7a_flag30.webp" width="480"> 
  <img src="https://github.com/kwan22/habits/blob/main/images/lv4/7a_flag7.webp" width="480"> 
</details>

<details>
  <summary>Downwards movement</summary>
<blockquote>
<details>
  <summary>Downwards collisions</summary>
  A frequent pattern to look out for is colliding with the ground when trying to move downwards. This commonly happens shortly after a transition. Different problems call for different movement options: hypering or supering shortly before transition, releasing jump during transition, and holding downdiagonal are common patterns. Be aware of which setup works best for each problem. By avoiding collision, we can clear the ground with some vertical speed to resolve the downwards bottleneck. <br>
  Examples of an instant hyper or super before transition <br>
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
  Some entities are best activated by grabbing. The key takeaway is that grabbing can only happen when Madeline is not moving upwards. Make sure she is not moving upwards by releasing jump well before reaching a block you are trying to activate by grabbing.
  <img src="https://github.com/kwan22/habits/blob/main/images/lv4/7a_500m_coin_exit.webp" width="480">
  <img src="https://github.com/kwan22/habits/blob/main/images/lv4/7a_2k_vert.webp" width="480"> <br>
  Extended hypers/wavedashes happen to work very well for getting crumble blocks to disappear quickly and consistently.
  <img src="https://github.com/kwan22/habits/blob/main/images/lv4/2a_intervention_crumble.webp" width="480">
  <img src="https://github.com/kwan22/habits/blob/main/images/lv4/5b_cc_crumbles.webp" width="480">
</details>

## DashCD 
Be aware of DashCD and movement to intentionally avoid or retain DashCD for setups. Learn to buffer consecutive dashes or dashes out of a hyper for grounded ultra timing. Use setups that rely on buffering a dash out of DashCD. Manage DashCD from vertical transitions and develop intuition for buffering out of vertical DashCD.

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
  Sometimes, we need to slow down before we can speed up. DashCD is preserved through horizontal screen transitions: many situations call for a dash immediately upon crossing such a transition with as much speed as possible. A common pattern is to late extended hyper just before entering a room. Jumping late on the extension lets us wait out DashCD before entering the next room, and firing the hyper off closer to the transition means less frictional losses when entering the next room. Whether we actually extend or not in the previous room is irrelevant since we are crossing a transition. We just want to enter the next room with 0 DashCD and near-max speed from the hyper. <br>
  <img src="https://github.com/kwan22/habits/blob/main/images/lv4/2a_start_gultra.webp" width="480">
  <img src="https://github.com/kwan22/habits/blob/main/images/lv4/5a_start_fastkey.webp" width="480">
  <img src="https://github.com/kwan22/habits/blob/main/images/lv4/5b_ttm_pillars_cut1.webp" width="480">
  <img src="https://github.com/kwan22/habits/blob/main/images/lv4/7a_2500m_orb_entry.webp" width="480"> <br>
  <br>

<blockquote>
  <details>
    <summary>Creating space</summary>
    Sometimes it is awkward or difficult to execute a forward extended hyper into a room. A reverse hyper may sometimes be used as a substitute. The difference in grounded ultra distance is small and often negligible.<br>
    <img src="https://github.com/kwan22/habits/blob/main/images/lv4/7a_1500m_long2_wave.webp" width="480">
    <img src="https://github.com/kwan22/habits/blob/main/images/lv4/7a_1500m_long2_wave.png" width="480">
    <img src="https://github.com/kwan22/habits/blob/main/images/lv4/7a_1500m_long2_rev.webp" width="480">
    <img src="https://github.com/kwan22/habits/blob/main/images/lv4/7a_1500m_long2_rev.png" width="480">
  </details>
</blockquote>
</details>

<details>
  <summary>DashCD setups</summary>
  Some setups intentionally use DashCD to make a dash in the next room more lenient by allowing to be bufferable. These often require precise positioning at the end of the previous room where the dash starts. Keep in mind that the dash in the next room is buffered out of DashCD in these cases, which is slightly after the transition ends as defined by the setup. <br>
  <img src="https://github.com/kwan22/habits/blob/main/images/lv4/5b_mm_final.webp" width="480">
  <img src="https://github.com/kwan22/habits/blob/main/images/lv4/6a_hollows_kevinslide.webp" width="480">
</details>

<details>
  <summary>Vertical transitions</summary>
  Upwards trajectory and DashCD is fixed upon vertical transitions.  While we must wait for DashCD to expire before dashing, we can cancel upwards trajectory if we are next to a wall by climbjumping. A small climbjump pairs well with a jumpthrough for cornercorrection leniency to line up midair supers and demohypers.<br>
  <img src="https://github.com/kwan22/habits/blob/main/images/lv4/1a_chasm_2_super.webp" width="480">
  <img src="https://github.com/kwan22/habits/blob/main/images/lv4/3a_start_post-triplat_super.webp" width="480">
</details>

## Applied buffering
Expanding upon the repertoire of concepts that rely on buffering from Level 3.

<details>
  <summary>Buffering instant or extended hyper</summary>
  Buffering movement in general can be applied basically everywhere but is quite difficult to perform consistently, in part due to the inherently variable timing. When landing without a dash to buffering a dash, say, to begin an instant or extended hyper, the abuse of the buffer window means the jump timing is influenced by how early the dash was buffered. A buffered action (dash) does not happen at the same time as the button press, meaning our muscle memory for extension timing can be thrown off. The setup for the 3a start winged room serves as a good starting point for evaluating ability to buffer extended hypers on landing. <br>
    <img src="https://github.com/kwan22/habits/blob/main/images/lv4/3a_start_winged.webp" width="480">
</details>

<details>
  <summary>Cornerkick setups</summary>
  For diagonal dashes at normal speed, a rule of thumb is to aim to dash to the corner from 3.5 tiles away horizontally. These are frequently easier with an updiagonal demo if height is not an issue, but dealing with the crouch state can lead to the cornerkick timing feeling awkward, as sometimes you need to wait for Madeline to uncrouch before getting the cornerkick.

  <blockquote>

<details>
  <summary>Forward cornerkicks</summary>
  <img src="https://github.com/kwan22/habits/blob/main/images/lv4/5b_ttm_3_ck.webp" width="480">
  <img src="https://github.com/kwan22/habits/blob/main/images/lv4/5b_ttm_pillars_ck.webp" width="480">
  <img src="https://github.com/kwan22/habits/blob/main/images/lv4/7a_500m_ck.webp" width="480">
  <img src="https://github.com/kwan22/habits/blob/main/images/lv4/7a_flag17_ck.webp" width="480">
</details>

<details>
  <summary>Neutral and turnarounds</summary>
  These require slightly more technical precision with having to go neutral or turnaround grab before the jump input, though the window is quite forgiving compared to extension timing. In some cases, the movement to set up the cornerkick is more difficult than the actual cornerkick. <br>
  <img src="https://github.com/kwan22/habits/blob/main/images/lv4/1a_chasm_ck.webp" width="480">
  <img src="https://github.com/kwan22/habits/blob/main/images/lv4/2a_intervention_tcj.webp" width="480">
  <img src="https://github.com/kwan22/habits/blob/main/images/lv4/5a_depths_dcb_setup.webp" width="480">
  <img src="https://github.com/kwan22/habits/blob/main/images/lv4/5b_cc_spikejump.webp" width="480"> 
</details>
</blockquote>
</details>

<details>
  <summary>Theo regrabs</summary>
  Dash shortly before releasing grab to use the buffer window to instantly regrab Theo with a diagonal dashing after throwing. Pressing dash before the grab release means the dash will come out as soon as you release grab and Theo is thrown.<br>
  <img src="https://github.com/kwan22/habits/blob/main/images/lv4/5b_mm2_regrab.webp" width="480"> 
  <img src="https://github.com/kwan22/habits/blob/main/images/lv4/5b_mm3_regrab.webp" width="480">
</details>

<details>
  <summary>Pausebuffering</summary>
From Level 3, we developed a feel for buffering a pause out of transition. Paused bubsdrop will be the only pausebuffer strat learned in the habits, but also acts as a gateway for learning more complicated pausebuffer strats for those who wish to go further. <br>
  <img src="https://github.com/kwan22/habits/blob/main/images/lv4/5b_cc_bubsdrop.webp" width="480">
</details>

## Option-selecting  
Making decisions to cover multiple possible outcomes to reduce risk at little/no cost.

<details>
  <summary>Hold towards the wall for wallbounces and wallkicks</summary>
  Hold towards the wall and release grab to keep dash-attack leniency for wallbounces or to get ForceMove from wallkicks. This makes the window to hit the wallbounce slightly larger, and reduces the risk of moving away from the wall before getting the wallkick. <br>
  <img src="https://github.com/kwan22/habits/blob/main/images/lv4/wallbounce_kick_leniency.png" width="960">
</details>

<details>
  <summary>Press extra buttons for safety</summary>
  Hold grab to cover overly aggressive movement, such as a missed clean landing, to prevent accidental wallkicks. <br>
  <img src="https://github.com/kwan22/habits/blob/main/images/lv4/holdgrab.png" width="960">  <br>

  Staggering jump presses can be useful for padding the timing for diagonal demo cornerkicks, as the jump timing can vary significantly depending on the starting dash position. <br>
  <img src="https://github.com/kwan22/habits/blob/main/images/lv4/jump_stagger.png" width="960">  <br>
</details>


[&#8593; Back to top](#level-4)

[&#8592; Level 3](https://github.com/kwan22/habits/blob/main/level3.md) 

[Conclusions &#8594;](https://github.com/kwan22/habits/blob/main/conclusions-faq.md)
