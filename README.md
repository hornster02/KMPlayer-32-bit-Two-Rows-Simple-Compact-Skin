***[📥 skin - for up to 150% system DPI](https://github.com/hornster02/KMPlayer-32-bit-Two-Rows-Simple-Compact-Skin/raw/main/skin.rar)
<br/>
[📥 script - Autohotkey v1.1 (KMP 4.2.2.51 - 2021 + Win7 + English QWERTY keyboard layout + CZ QWERTZ)](https://github.com/hornster02/KMPlayer-32-bit-Two-Rows-Simple-Compact-Skin/raw/main/script.rar)
<br/>
[📥 script - Autohotkey v1.1 (KMP64X 2021.04.27.54 + Win7 + English QWERTY keyboard layout + CZ QWERTZ)](https://github.com/hornster02/KMPlayer-32-bit-Two-Rows-Simple-Compact-Skin/raw/main/script64x.rar)
<br/>
[📥 config - KMP 4.2.2.51 - 2021 (skin, hotkeys, disabled 3D Audio, volume normalizer, orange/black subtitles, open video files with hidden GUI in fullscreen+restore window when finished/closed, audio files in "Two Rows" height)](https://github.com/hornster02/KMPlayer-32-bit-Two-Rows-Simple-Compact-Skin/raw/main/config-4.2.2.51.rar)***

Default KMP problems with loss of focus when you must use ALT+TAB or mouse are fixed with script. Some of the hotkeys listed below are not supported by KMP at all and you have to painfully click through the context/menu

Multimedia keys (🟧*00) ,🟩 KMP64X doesn't support global hotkeys
<br/>
***Media Play Pause*** starts/pauses playback,                     ```hold``` to close KMP
<br/>
***Volume Down*** reduces the volume,                             ```hold``` to open previous file
<br/>
***Volume Up*** increase the volume,                                ```hold``` to open next file

***MButton*** show taskbar,                                               ```hold``` Always On Top (toggle)
<br/>
***ALT+SHIFT*** reduce the active window to half the screen and align it right or left or maximize it - global hotkey
<br/>
***LButton+MButton*** dragging the window (no need to ```hold``` down the MButton) - global hotkey

***Numpad4*** subtitle -0,5s ,🟩 KMP64X "Options / Subtitles / delay step"
<br/>
***Numpad5*** subtitle +0,5s
<br/>
***Numpad6*** open "Adjust Subtitle Sync" ,🟩 KMP64X doesn't support,                                                               ```hold``` show/hide subtitle
<br/>
***Enter*** if "Adjust Subtitle Sync" is active then the written numbers are set,        ```hold``` closes "Adjust Subtitle Sync"

***Numpad1*** audio -0,05s (🟧*01) ,🟩 KMP64X -0,01s
<br/>
***Numpad2*** audio +0,05s
<br/>
***Numpad3*** list of audio streams (the default one is marked first),                        ```hold``` list of subtitles (the default one is marked first), unfortunately ***NumpadDot*** (32-bit only) illogically works as a down arrow, because as written below, the up/down arrow is pressed 5 times (32-bit only) for volume

***B*** add bookmark,                                                                                                       ```hold``` open "bookmark editor"
<br/>
***Enter*** if "bookmark editor" is active then "Enter" opens the selected (arrows) bookmark and closes "bookmark editor"
<br/>
***Del*** if "bookmark editor" is active then "Del" remove selected (arrows) bookmark, ```hold``` closes "bookmark editor"
<br/>
***P*** playlist (arrows-select, p/esc close, enter-open/close)

***Left*** previous file
<br/>
***Right*** next file
<br/>
***Down*** volume -5%
<br/>
***Up*** volume +5%

***Z*** zoom- (letterbox)
<br/>
***X*** zoom+ (letterbox)
<br/>
***C*** zoom/acpect ratio reset ,🟩 KMP64X zoom reset
<br/>
***PgUp*** acpect ratio cycle,                                                                                              ```hold``` zoom/acpect ratio reset
<br/>
🟩 KMP64X - create new "end" hotkey in "Options / Keys / Next AR preset" (or 🟦*02),                                                                 ```hold``` acpect ratio reset

***ESC*** pause+minimize,                                                                                               ```hold``` close file
<br/>
***1234*** window size
<br/>
***Enter*** Maximize/Restore Window
<br/>
🟩 KMP64X - to keep the same behavior you need to change the default "Enter" hotkey to "Ins" (or 🟦*02)
<br/>
<br/>
<img width="359" alt="AUDIO - BIG" src="https://github.com/hornster02/KMPlayer-32-bit-Two-Rows-Simple-Compact-Skin/assets/127822397/c5e2f4e4-5fc0-429a-bb34-22e16ba263c4">
<img width="128" alt="AUDIO - COMPACT" src="https://github.com/hornster02/KMPlayer-32-bit-Two-Rows-Simple-Compact-Skin/assets/127822397/4fb9edd4-a916-40b6-a826-24b43583c162">
<img width="64" alt="AUDIO - COMPACT SUPER" src="https://github.com/hornster02/KMPlayer-32-bit-Two-Rows-Simple-Compact-Skin/assets/127822397/6846e787-d9de-4403-b418-f879d75d3003">
<br/>
<img width="356" alt="AUDIO - BIG-DEF" src="https://github.com/hornster02/KMPlayer-32-bit-Two-Rows-Simple-Compact-Skin/assets/127822397/9126875b-991f-4f0d-b0b5-151e1b6d6ab4">

Just reducing the gamma in the system makes the original skin quite unusable. Combined with the brightness and contrast reduction, it is almost invisible
<br/>
<img width="356" alt="AUDIO - BIG-DEF-GAMMA" src="https://github.com/hornster02/KMPlayer-32-bit-Two-Rows-Simple-Compact-Skin/assets/127822397/7b168bc9-4096-4c8c-a725-c9d2734efa42">
<img width="359" alt="AUDIO - BIG-GAMMA" src="https://github.com/hornster02/KMPlayer-32-bit-Two-Rows-Simple-Compact-Skin/assets/127822397/a666afef-4a1b-4986-a04c-5e3a682501b5">

<img width="1280" alt="VIDEO3" src="https://github.com/hornster02/KMPlayer-32-bit-Two-Rows-Simple-Compact-Skin/assets/127822397/fda73216-321e-4424-a3af-b7bb4568815a">

<img width="1280" alt="VIDEO-DEF" src="https://github.com/hornster02/KMPlayer-32-bit-Two-Rows-Simple-Compact-Skin/assets/127822397/fe0a3872-6b27-4861-bc64-9034a05d11e6">
<br/>
<br/>
<br/>

***KMPCfg.ini*** (enable - preferences / general / store settings to...). ***Watch out for the sections***
<br/>
The best volume balance (increasing quiet passages and decreasing loud ones)
```
[\Software\KMPlayer\KMP3.0\OptionArea]
AudioUseAutoGain_2=int:1
AudioAutoGainType=int:2
```

<br/>
<br/>

Automatically switch to fullscreen (autohide) mode when you open a video file
```
FulledWindow=int:0
PlayScreenSize=int:7
```

<br/>
<br/>

White blue color theme
```
ColorThemeName=str:White Blue
```

<br/>
<br/>

Enable+create multimedia hotkeys 🟧*00
```
UseGlobalHotkey=int:1
ConfigKeyForm=int:0
[\Software\KMPlayer\KMP3.0\OptionArea\GlobalHotkeyList]
N36=int:57425
N39=int:57431
N40=int:57413
N23=int:57417
```

<br/>
<br/>

Permanent hiding the annoying "Album Art" that makes the player UI several times bigger
```
[\Software\KMPlayer\KMP3.0]
AudioHeight=int:1
[\Software\KMPlayer\KMP3.0\OptionArea]
UserDefPosHeight0=int:1
HeightLen=int:1
WindowHeight=int:1
```

<br/>
<br/>

***KMPKey.ini***
<br/>
Create hotkeys 🟧*01
```
[KMPKey]
N516=K
N501=L
```

<br/>
<br/>

***KMPlayer64.ini*** (enable - options / player / store settings in...)
<br/>
Change+create hotkeys 🟦*02
<br/>
```
[Commands2]
CommandMod0=830 1 2d "" 5 4 0 4
CommandMod1=859 1 23 "" 5 0 0 0
```
