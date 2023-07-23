# 2023_07_23_MemoryRamGetPixelAndScreens
Access screen monitor information from a C# app with UDP and memory file on Unity or Third app.


I used the library of someone that broke with window 11...
I can't modifiy it because it is his dll and I don't understand how to do it.

So I need my own tool.

What is the aim.

The aim is to have a image in memory file that can be accessed by Unity.
And if not possible without losing to much.
the aim would be to be able to read 1 - nxn pixel from a "udp log" application.

Like:
- Listen to the color change of this pixel on screen
- Stream the pixel color through UDP to this listener at this frequence.
- Stream the pixel color through UDP if there is significative change.
- Stream this grid of pixel with this frequence on this target.
- ...

The idea is to make a tool that help understanding the screen of the user without Unity.
It will only work on Window because I will use memory file principle for heavy communication when required.
