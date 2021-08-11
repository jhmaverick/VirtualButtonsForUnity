# Virtual Buttons for Unity

[Unity Asset Store](https://assetstore.unity.com/packages/tools/input-management/virtual-buttons-200159)


Prefabs to help create touch buttons with the new input system.

Prefabs:

- Fixed position joystick;
- Floating joystick with options to recenter and hide on release;
- Directional button that is activated by clicking on any position around the center and responds to being dragged from one direction to another;
- Directional button variations for moving vertically or horizontally;
- Button for actions with animation when pressing.


## UPM Package

Open Package Manager and select "Add package from git URL"

```
https://github.com/jhmaverick/VirtualButtonsForUnity.git?path=/VirtualButtonsForUnity/
```

or adding in /Packages/manifest.json

```
"com.cyberghostgames.virtualbuttons": "https://github.com/jhmaverick/VirtualButtonsForUnity.git?path=/VirtualButtonsForUnity/"
```

## Notes

There is a bug in the new input system version 1.0.x that keeps the stick pressed when pressing 2 buttons at the same time as can be seen in this [issue](https://issuetracker.unity3d.com/issues/android-onenddrag-not-being-called-when-there-are-at-least-2-touches-on-the-screen?_gl=1*fndk35*_ga*NDkzODQ0MDYuMTYxOTg3MTY1Nw..*_ga_1S78EFL1W5*MTYyNDkxNzYzNy4xMjIuMS4xNjI0OTE4NjcxLjM0&_ga=2.106429952.2030515878.1624194738-49384406.1619871657).

The bug has been fixed in version (1.1-preview.3), while version 1.1 is not officially released, you can check the latest [development version](https://docs.unity3d.com/Packages/com.unity.inputsystem@1.1/changelog/CHANGELOG.html#110-pre5---2021-05-11) and manually apply it to your project at (/Packages/manifest.json).
