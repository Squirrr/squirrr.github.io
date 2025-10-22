---
defaults:
  # _pages
  - scope:
      path: ""
      type: pages
    values:
      layout: single
      author_profile: true
title: 2025 FRC
permalink: /first/reefscape/
---
In this season of the FIRST® Robotics Competition (FRC), our team was tasked with precisely aligning to a designated scoring location (the "reef") and automatically depositing the object with a ±2" tolerance. To start, I programmed the swerve drive using kinematics to enable us to maneuver quickly yet accurately across the field. After programming the drivetrain, I tested multiple different methods of alignment to the reef, utilizing vision powered by Limelight cameras and interfacing with the API to create a consistent and quick solution. We also utilizes our vision measurements for global pose estimation, allowing our robot to calculate its position on the field with a precision of ±2cm, allowing for impressive demonstrations and consistent autonomous routines.
{% include video id="L1V84d7_JFg" provider="youtube" width="240px" height="427px"  float="left" margin="10px"%}
{% include video id="-kJR3vjQXNA" provider="youtube" width="576px" height="324px" float="left" margin="10px"%}
{% include video id="VhTi7fsXEAQ" provider="youtube" width="240px" height="427px" float="left" margin="10px"%}
<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>
In addition, we utilized Finite State Machine (FSM) logic to control the robot, diagramming out the possible state transition and using a time-weighted graph with Dijkstra's algorithm to determine the fastest possible transition between two states.
<br><br>
We also utilized logging extensively to identity various issues we had during our robot, making debugging much easier than it was before. We also stored various information about the robot, including the desired scoring location, to alleviate the pressure of the drivers and automate as many of the robot's actions as possible.
<br><br>
Ultimately, we were able to win the Autonomous award at one of our events, win another event, and compete in the playoffs in the FRC State Championship against 89 other teams!
<br><br>
[GitHub Code](https://github.com/itkan-robotics/FRC_REEFSCAPE2025_V2){: .btn .btn--purple .btn--large}
[Onshape CAD](https://cad.onshape.com/documents/9aad57d3cb5d2be899be5aa7/w/f997cc794f7a12ee163b0551/e/a7a9a0e959e36dfcddccf823?renderMode=0&uiState=68e7261632f8214a01eab67d
){: .btn .btn--success .btn--large}
[Match Video](https://youtu.be/r74ML7_qcHM){: .btn .btn--danger .btn--large}