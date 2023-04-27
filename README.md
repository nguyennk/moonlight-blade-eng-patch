# English patch for Moonlight Blade Game

Currently only work for Taiwan version, will prob die when new version come out, will try to keep up with it while I still playing :D

Update: Currently not playing the game anymore so I don't think I will keep this update, the player base just not worth the effort to keep this up :D

# How did I translate it?

There are a lot of what I called "restriction" got put in place since this is Unoffical translation.

1. First I unpack the file from the client (TableBin.sfc and UI-TW.sfc)
2. TableBin is responsible for all the translation copy while UI-TW is for the font file
3. Because there a size restriction from the file checking from the game client, here are the restriction that I figured:
- Each of the file's size in TableBin.sfc need to be the same after the translation
- Each of the string length (in bytes) in those file need to be the same after translation
- The location of variable (%s, %d, {0}, {1}) in those file need to be the same (in bytes index) after the translation
4. Due to those restriction, I cannot just "translate" and done, need to manipulate a lot of stuff (size, bytes, font) to make this happen
5. The result is not perfect, but at least "usable" I guess, unless I can get some green light from the publisher / game dev and lift the size restriction, this is what we need to live on atm :D

# How to install?

Download the latest patch from [Release](https://github.com/nguyennk/moonlight-blade-eng-patch/releases) section

Make copy of TableBin.sfc and UI-TW.sfc for restore purpose later

Override them with the content of the patch

Done

# Screenshots

![image](https://user-images.githubusercontent.com/1538969/220077213-0d9342b4-464e-4dfd-8454-f3c80b689a47.png)
![image](https://user-images.githubusercontent.com/1538969/220077287-176a0291-a471-4925-a79b-726e5536ba68.png)
![image](https://user-images.githubusercontent.com/1538969/220077403-e08ab137-5c34-427d-a1c5-1b99d862b7d0.png)
![image](https://user-images.githubusercontent.com/1538969/220077556-416ea4b4-31d2-43b9-a37e-8d3f3e652b6d.png)
![image](https://user-images.githubusercontent.com/1538969/220077590-c8345aaa-bc00-459b-8f0d-e85adaca1b07.png)

# Known bugs

This is still WIP so there will be a lot of translation error, let me know if you spot something that doesn't sound right. Feel free to suggest translation text change in issue ticket

Some translation got cut off, so it might not mean anything, report/feedback if you encounter something you need to understand to proceed, will try to include in the next patch when I have time

# Feedbacks

There are still a lot of things need to be translate, this is WIP
Please submit issue ticket if you think something need to be translate to help with understanding the game better

