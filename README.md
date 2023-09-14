# To run the Drone code, follow the instructions:
-clone px4Autopilot : https://github.com/PX4/PX4-Autopilot
- clone qgc master version : https://github.com/mavlink/qgroundcontrol.git
- modify the necessary files under qml:
  1. MainToolBar.qml under resource-> qml folder->QgroundControl->controls
  2. MainRootWindow.qml under resource-> qml folder->QgroundControl->controls->ScreenTools
  3. FlyView.qml under resource-> qml folder->QgroundControl->controls->FlightDisplay
  4. GuidedActionsController.qml under resource-> qml folder->QgroundControl->controls->FlightDisplay
-To view the graphical simulation install Gazebo: https://github.com/gazebosim
