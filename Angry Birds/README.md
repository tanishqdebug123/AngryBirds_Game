# Angry Birds Game 

A [libGDX](https://libgdx.com/) project generated with [gdx-liftoff](https://github.com/libgdx/gdx-liftoff).

## Screens (Static GUI)
- Main Menu (on start when project is run)
  - ![mainmenuscreen](https://github.com/user-attachments/assets/b3ff25b9-0c6b-4bc2-a0c2-bf8223ee68dd)



- Select Level Screen
  - ![selectlevelscreen](https://github.com/user-attachments/assets/c03c74bb-4332-466c-93c3-1ed58d5d5e05)

    

- Level1
  - ![level1screen](https://github.com/user-attachments/assets/1e615f9e-1c37-41ee-843d-154f6d68bfbf)
 


- Level2
  - ![level2](https://github.com/user-attachments/assets/771ec1c5-a594-450e-8723-6fa70128a44a)


 

- Level3
  - ![level3](https://github.com/user-attachments/assets/72249b87-02ac-42cc-9a9a-22bfe077fad3)

 


- Settings
  - ![settingsscreen](https://github.com/user-attachments/assets/6658c7bf-399c-4b65-a294-1842c15a8dd3)



## Screens (Final Game)
- Note: while capturing screens for READme, we kept the debug renderer active for level 1 and 2 in order to show the box shapes of the
materials, birds and pigs. And, we have handled the collision between every objects (birds, pigs, material) with each other and itself but
when birds and pigs collide then only a pig gets destroyed. Collision between material and birds with each other and among themselves does not lead to
destruction of any of them.


- Main Menu (first screen when we start)
  - ![startscreen](https://github.com/user-attachments/assets/7c1e9a20-279a-4119-8dae-c3b241ec09c2)
 
  - We have 3 clickable buttons on this screen: PLAY, QUIT, SETTINGS.
  - On clicking play, we reach to the select level screen.
  - On clicking settings, a settings page opens up.
  - On clicking quit, the game exits.
 
    

- Select Level Screen
  - ![levelscreen](https://github.com/user-attachments/assets/f667341a-fa6c-47d2-be48-b55853617c7b)
    
  - We have made 3 playable levels in the game, each with more difficulty than the previous one.


 
- Level 1
   - ![level1_running](https://github.com/user-attachments/assets/1e946aa7-a9a4-4186-8267-47d1795011f1)
 
  - For level 1, we have kept aa very simple structure to beat containing of 3 pigs (2 small, 1 medium) and 2 types of material (Vertical Block, Thick Wooden Rectangular Block).
  - At start, red bird is placed in the slingshot and is launched.


    - Bird Launched
      - ![bird launched](https://github.com/user-attachments/assets/dc4655cf-480d-4313-90e1-610f5a225709)
   
      - Bird got launched, the moment it gets launched next bird in the line gets in the slingshot.



    - Bird colliding with Objects
      - ![collision](https://github.com/user-attachments/assets/c62457fe-9fad-4b6a-a1e3-52674981546d)


  
    - Result of collision
      - ![result of collision](https://github.com/user-attachments/assets/87e82d91-9eb7-4b2b-afa5-068b36091429)

      - Red bird hit the medium pig, it takes two hits to finish the medium one and one to small. Bird bounced over medium pig making it two hits.
      Then yellow bird was launched in the same manner and it collided with the small pig on right
      leading to destroy both of them.
      - Same way black bird was launched to collide with the first small pig leading to level completion.


     
- Level Completed Screen
  - ![level completed](https://github.com/user-attachments/assets/598419ab-2293-41dc-ba91-e67542096bcb)

  - We completed level 1 and this screen comes up (comes up whenever a level is completed), consists of 3 buttons (Replay, Select Level Screen, Next Level)
  - On clicking Next Level button, we move to the next level.
  - On clicking Select Level button, we move the select levels screen.
  - On clicking Replay button, we can restart the level or play the level again.


 
- Level 2
  - ![level2](https://github.com/user-attachments/assets/8c7329ac-5d5c-4dfa-a046-ca3a4f7b5794)



  - Level 2 after playing it
    - ![level2 played](https://github.com/user-attachments/assets/3f5befaa-c063-4533-8c4f-c1579bb8172e)

- Level 3
   - ![level3](https://github.com/user-attachments/assets/e2c4356f-6671-4e69-8431-2a770543141f)



  - Level 3 after playing it
    - ![level3 played](https://github.com/user-attachments/assets/741e0c76-d6ff-41b2-98e0-6d7c573f26d7)



- Settings
  - ![settings](https://github.com/user-attachments/assets/af122360-e2a3-4b54-b3a6-b4bdbbe6279f)

  - On Settings screen, we have 3 buttons (Volume Down, Volume Up, and Quit).
  - On clicking Volume Down button, the volume is disabled.
  - On clicking Volume Up button, the volume is enabled.
  - On clicking Quit button, the game exits.


## Resources
- Referred to libGDX official documentation (https://libgdx.com/wiki/start/a-simple-game)
- Shapes for objects (Polygonshape classes etc) were referred from (https://box2d.org/documentation/group__shape.html)
- Collision between objects (category and mask bits) referred from (https://box2d.org/documentation/group__shape.html) and (https://stackoverflow.com/questions/32681200/box2d-filter-maskbits-and-categorybits)
- Credits for PNGs (https://www.pngitem.com/middle/ibiiRow_abpc-button-sheet-angry-birds-birds-sprites-hd/#google_vignette), (https://www.deviantart.com/yoshibowserfanatic/art/Angry-Birds-Poached-Eggs-Theme-I-Background-406945305), (https://www.freeiconspng.com/img/46175) this is for red bird, all other birds and pigs also taken from same site, (https://www.researchgate.net/figure/The-twelve-different-block-shapes-available_fig2_326363789), (https://www.semanticscholar.org/paper/Procedural-Content-Generation-of-Angry-Birds-Levels-Caramanis-Nagarajan/4739eaf3e8ec26079cfa4c7f37072e5d23f81d0e/figure/5)
- Levels were designed by ourselves in Figma first and then were created in the program (https://www.figma.com/design/aVEnvnioShEfwAMXc9xMn0/Screens-for-Angry-Birds-Project?node-id=0-1&t=ixZ2GP3ezEuGNea1-1).


### Project made by Raghav Syal (2023416, CSSS, IIIT Delhi) and Tanishq Goyal (2023549, CSAI, IIIT Delhi).
### GitHub link (https://github.com/raghavsyal/2023416_2023549_FinalGame)

### Contributions
  Raghav Syal  : Designed level screens, made all the icons such as level 1, 2, 3 buttons, play, quit, volume up, down, back etc. Handles the launching of
  birds, one bird gets launched other comes in the slingshot using arrays, made level struct for level 1, 2, 3. Dynamic bodies of Red Bird, Small and Medium pigs and Wooden Block, Vertical Slabs. Made the polygon shapes for red bird and small, medium pigs and some material.

  Tanishq Goyal  : Collision Handling between pigs, birds and materials. Handled physics for materials, pigs (world). Made the static gui screens transition, added music (different for main screen and different for levels). Made Dynamic bodies for Black and Yellow Bird, vertical glass, block ice. Made the polygon shapes for materials. Handled the transition between screens. 
