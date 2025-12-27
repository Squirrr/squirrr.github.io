---
defaults:
  # _pages
  - scope:
      path: ""
      type: pages
    values:
      layout: single
      author_profile: true
title: Watchfall - Samsung Solve for Tomorrow
permalink: /personal/watchfall/
---
In some assisted living facilities, caretakers struggle to monitor their patients around the clock. However, despite their importance in preventing injuries, existing devices meant to monitor senior movements and detect falls are exorbitantly expensive. I am designing a device for the Samsung Solve for Tomorrow contest that performs the same function at a fraction of the cost. By utilizing commercial parts and 3D printing, I created a camera with multiple degrees of freedom, enabling a full view of the room. The camera then analyzes data using TensorFlow to identify who is in the room, detect movements that indicate a fall, and alert caretakers.