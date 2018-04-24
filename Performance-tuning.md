Due to issues with some hardware, hardware acceleration is disabled by default on RuneLite because it causes artifacts with some graphic cards.

If you are experiencing sloppy camera or getting lower FPS, you can enable the hardware acceleration manually. You can choose between `OPENGL` and `DIRECTDRAW` mode. OpenGL mode is cross-platform, and DirectDraw works only on Windows. On Windows DirectDraw should have larger impact than OpenGL, but you can experiment with both.

## .bat script to enable ddraw

If you are on Windows using the official installer, download and run this:

[Runelite-DDraw.bat](files/runelite-ddraw.bat)

## Enabling hardware acceleration on Windows manually

You can enable DirectDraw acceleration by adding ` --mode=DIRECTDRAW` to the end of `Target:` in the RuneLite shortcut properties:

![](https://cdn.discordapp.com/attachments/359016743802503178/437801849752387593/unknown.png)

![](https://cdn.discordapp.com/attachments/301497432909414422/437800238921809932/unknown.png)

## Enabling hardware acceleration on other platforms

If you downloaded the `.jar` version of the launcher, simply running

```
java -jar RuneLite.jar --mode=OPENGL
```

will enable the OpenGL hardware acceleration.