
![](https://img.shields.io/badge/Author-Pranjal_Bhardwaj-green)![](https://img.shields.io/badge/Language-Swift-orange)

# AR-Ruler
An Augmented Reality Ruler that measures distance between two points and displays it in 3D text

# How it works
The application uses ARKit and calculates the co-ordinates of the points in 3D that the user taps in 2D on the screen.

Then using simple algebra the distance between the two 3D co-ordinates is calculated.

A plane is detected in the vertical and horizontal orientation to display the distance between the two co-ordinates.

And the result is displayed in the vertical orientation near the last selected point.

# Repository Structure

    ├── AR Ruler
    │   ├── AppDelegate.swift
    │   ├── Assets.xcassets
    │   │   ├── AppIcon.appiconset
    │   │   │   └── Contents.json
    │   │   └── Contents.json
    │   ├── Base.lproj
    │   │   ├── LaunchScreen.storyboard
    │   │   └── Main.storyboard
    │   ├── Info.plist
    │   ├── ViewController.swift
    │   └── art.scnassets
    │       ├── ship.scn
    │       └── texture.png
    ├── AR Ruler.xcodeproj
    │   ├── project.pbxproj
    │   ├── project.xcworkspace
    │   │   ├── contents.xcworkspacedata
    │   │   ├── xcshareddata
    │   │   │   └── IDEWorkspaceChecks.plist
    │   │   └── xcuserdata
    │   │       └── pranjalbhardwaj.xcuserdatad
    │   │           └── UserInterfaceState.xcuserstate
    │   └── xcuserdata
    │       └── pranjalbhardwaj.xcuserdatad
    │           └── xcschemes
    │               └── xcschememanagement.plist
    └── README.md

