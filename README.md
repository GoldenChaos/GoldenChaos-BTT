# GoldenChaos-BTT

![](https://goldenchaos.net/images/goldenchaos-btt-full.jpg) 
<br/>

I _love_ the Touch Bar. That's why I was so upset that Apple just sat on its useless user interface. So, inspired by Vas3k's popular [blog post](http://vas3k.com/blog/touchbar/) on the subject, and determined to make good on the promise that Apple broke, I've spent a (ridiculous) amount of time reworking the foundations of the Touch Bar into **GoldenChaos-BTT**: a true general purpose Touch Bar UI with support for tons of apps that's intuitive enough to make you love your Touch Bar again - or, more likely, for the first time.

_Want to buy me a coffee? You can donate here: https://paypal.me/GoldenChaos_

_Thinking about buying BetterTouchTool because of this preset? [Use this link and I'll get 25%. :)](https://a.paddle.com/v2/click/30842/34667?link=1061)_

> # Latest stable version: [GoldenChaos-BTT 2.641](https://share.folivora.ai/sharedPreset/aa7a2d21-4fc4-414f-ad7f-e31dd0f00cc1)
> **(Sep 25 2018 - [Release Notes](https://community.folivora.ai/t/goldenchaos-btt-a-complete-touch-bar-ui-replacement-preset/1281/1043?u=goldenchaos))** No longer requires High Sierra Media Key Enabler! Plus: Settings menu with customization options for esc key, Home Strip keys, Menu Bar icons, Dock badges, Date/Time formatting with 24-Hour Time, and default calendar app selection; Seamless upgrades with just a tap using the "Reapply Settings" button; Fully scriptable, with a simple preset format so you can have multiple GC-BTT's for different occasions; Native Now Playing widget with dramatic CPU usage improvements; Collapsible Menu Bar with three sizes; New Connectivity Actions menu; New Current Language and Language Picker widgets with flags for 47 different languages
> 
> # Latest experimental version: None!
> Don't worry, that won't last long.

> # How to install
> 1. Make sure you're using the latest stable version of BetterTouchTool.
>    - Feeling brave? Install the latest **alpha** BetterTouchTool to use the experimental versions.
> 2. **[One time only]** Install [icalBuddy](http://hasseg.org/icalBuddy/).
> 3. **[One time only]** [Configure BTT's General Touch Bar settings properly](#heading--touch-bar-settings).
> 4. **Upgrading?** [Follow these steps](#heading--upgrading).
> 5. Follow one of the two release links at the top of this post and click "**Direct import to BTT**". BTT will automatically launch and ask to import the preset - say yes to everything.
> 7. You're all set! Press ⌘⌥⇧P to access the GC-BTT settings menu where you can customize GC-BTT to your liking.

# Screenshots

## Home Strip
![00%20AM](https://community.folivora.ai/uploads/default/original/2X/d/d728b43605de56b07a485806ceaf8c4f9685db97.png) 
<sub>The default key set when nothing is open. Fullscreen doubles as escape key; tap for escape, long-press for fullscreen.</sub>

![50%20AM](https://community.folivora.ai/uploads/default/original/2X/4/4e5bd48b854e51480aee9905bb2c8f842423deb7.png) 
<sub>Open a browser, and browser controls appear in the Home Strip.</sub>

![12%20AM](https://community.folivora.ai/uploads/default/original/2X/c/ced6b67da49c9f35bf6801218855b0e61ae06c0c.jpeg) 
<sub>Open more apps to reveal a wide range of dynamic controls and widgets. Close apps to dismiss their controls.</sub>

## Modifier Menus
<small>Hold command, option, or control to access the app switcher, control strip, or window snapping controls.</small>

![21%20AM](upload://qAFP9X0dvSlWlQBoCpHMQPoigZ2.png) 
![11%20AM](upload://6mxIdGxNiqKROzVBOGZBnqW02B6.png) 
![03%20PM](upload://d0yzDovqh37GeelrbI4VnpjbeFM.png) 

## Dynamic Menu Bar
<small>Dynamic Menu Bar with three size options lets you dedicate as much or as little space to widgets as you like.</small>

![18%20PM](upload://idWknlfJOcglGzcUB9IavqXGc0J.jpeg) ![46%20PM](upload://5IXwi10WwjkcdzY32AONqTuYW4R.png) ![15%20PM](upload://c8EGb5b7TaWNvBXHS2r1tdEaFuF.png) 

 ![37%20PM](upload://em3116SuTtiUE4Yc3JgrsWj84wC.png) 
![46%20PM](upload://e5jqdJHQH8RnZ8MQHJRlpnlav8n.png)
 ![30%20PM](upload://qJJ4bqVyYbKHQqHyjzEipX0cfbi.png) 

![30%20PM](upload://yfx7sZf4Ol13H6v0cb4oZcHV0Pt.png) 
![38%20PM](upload://fk3pC9rQzJU9Pm5aNqjTPeL3FmP.png) 
![19%20PM](upload://3QkBKOdKR52sur460i8FEs21DXh.png) 

## Widget Groups
<sub>**Widget Groups** like Emoji Picker, Browser Tabs, and Language Switcher replace the Home Strip, but not the Menu Bar.</sub>

![42%20AM](upload://djPVUYUoAOq36RP3rwc07evP88l.png) 
![34%20AM](upload://Av44BhxE67ZAMYCRlwBIFb92GwN.png) 
![34%20PM](upload://r9LnkPORJE66IbgF7SBTbJ9geEx.png) 

## Modal Widgets
<small>Access expanded-view **Modal Widgets** by long-pressing on Weather, Now Playing, Reminders, Calendar, Volume, and more.</small>

![48%20AM](upload://49KdNX82RXPNwD6YGEZohcQ7JWp.png)
![32%20AM](upload://49qnQLW5Ung8A2cmA55r2zLXwcS.png)
![40%20PM](upload://nKGHN53cfDuBTdvbcCsFMDKbuMx.png) 

## Dock Badges
![01%20PM](upload://jGLVCjjYgBgcM69yLOV7aEjGX0n.png)
![08%20PM](upload://ua21HD9IoexqXFmhMjFJbWpXtjt.png) 
<sub>Dock Badges appear on the left side of the Touch Bar and remain sticky.</sub>

![42%20PM](upload://5AQIiWINmWQDrtSdyGO3Wctf0K2.png)
<sub>Built-in Dock Badge support for all of your favorite third party apps; enable or disable them in the GC-BTT Settings menu.</sub>

![46%20PM](upload://lBX2OSPi3ztHtq5Qg6rFVGF2P9H.png)
<sub>Dock Badges also support handoff!</sub>

## Settings with Seamless Upgrading
<small>The straightforward GC-BTT Settings panel (⌘⌥⇧P) makes it easy to deeply customize your Touch Bar. Settings transfer seamlessly to new versions of GC-BTT with "Reapply All Settings".</small>

![47%20AM](upload://10uBZE4tKYF5B4USgbliZHh818F.png) 

![07%20AM](upload://mpIxK258jpjA50KtziKlBzD4kP1.png)

![29%20AM](upload://cgfI7HROBdK7ntxubEOJ2CT13J6.png)

![35%20AM](upload://7JbO0IQOCkvRwzaRybxWRW9yr9h.png)

![45%20AM](upload://h6vdPRrO0Xgfs0TSyWwfKG8aapZ.png) 

![00%20AM](upload://xrapFLKjzJ2sLOsDGqggNkB2eI8.png)

![08%20AM](upload://AamOfp9kVDsVEeCyNpfZTBywejE.png)

<h1 id="heading--touch-bar-settings">General Touch Bar Settings</h1>

GoldenChaos-BTT is designed to completely take over the Touch Bar, escape key and all. Since BetterTouchTool isn't set up this way by default, make sure to match BetterTouchTool's General Touch Bar Settings to the configuration shown below before importing - if you don't, things probably won't look right.

![1|690x470](upload://qN44IjO6cLcZmdeoUZ3oFoztAGP.png) 

![2|690x470](upload://1gLKu8YqDFHRh2d4oSICKZtqVva.png) 

<h1 id="heading--upgrading">Upgrading GoldenChaos-BTT</h1>

GoldenChaos-BTT has a seamless upgrade system that allows your customized settings to transfer from one version to the next by storing your settings inside BTT itself. For it to work, you'll first need to _completely remove_ any existing installations of GoldenChaos-BTT - if you don't, the settings menu won't work.

To remove existing GC-BTT installations and safely upgrade to a new version, follow these steps:

1. Click "Manage Presets" inside of BetterTouchTool
2. Select and delete _all_ installations of GoldenChaos-BTT. **If you do not remove all GC-BTT installations before upgrading, the settings menu won’t work!**
3. Navigate to one of the two latest release links at the top of this post and click "Direct import to BTT" to automatically launch BetterTouchTool and import the latest preset.
3. Open the GC-BTT Settings menu by pressing ⌘⌥⇧P.
4. Tap “Reapply All Settings” and watch the pretty progress bar.
5. After it's done running, your previous setup should be restored! I guess that's not really a step. ¯\_(ツ)_/¯ 

# Previous Versions
Only install the latest version unless you have a specific troubleshooting reason. If you do need to install an older version for whatever reason, make sure the version of BetterTouchTool you're running is greater than or equal to the GoldenChaos-BTT version you're installing.

> **Notes:**
> * <sup>Versions **2.543 and earlier** require the Python Requests module (`pip install requests`) and Locateme (`brew install locateme`) for the weather widget to work.
> * <sup>Versions **2.531 and earlier** require the calendar widget to first be edited to include the names of the calendars that you wish to display.</sup>
> * <sup>Versions **2.516 and earlier** require [Location Helper](http://www.mousedown.net/mouseware/LocationHelper.html) and [JSON Helper](http://www.mousedown.net/mouseware/JSONHelper.html) for the weather widget to work. **Not compatible with macOS Mojave.**</sup>

### Version History:
* **[Verified]** [Stable] [2.641](https://share.folivora.ai/sharedPreset/aa7a2d21-4fc4-414f-ad7f-e31dd0f00cc1) ([Sep 25 2018](https://community.folivora.ai/t/goldenchaos-btt-a-complete-touch-bar-ui-replacement-preset/1281/1043?u=goldenchaos))
* [Experimental] [2.639-4](https://share.folivora.ai/sharedPreset/5f37ad3a-486a-4e62-9641-bd486238f7cd) ([Sep 23 2018](https://community.folivora.ai/t/goldenchaos-btt-a-complete-touch-bar-ui-replacement-preset/1281/1025?u=goldenchaos))
* [Experimental] [2.639-3](https://share.folivora.ai/sharedPreset/02a6d126-99f0-4faf-ab38-2661f74d080b) ([Sep 23 2018](https://community.folivora.ai/t/goldenchaos-btt-a-complete-touch-bar-ui-replacement-preset/1281/1018?u=goldenchaos))
* [Experimental] [2.639-2](https://share.folivora.ai/sharedPreset/d4247e6e-5155-4b5b-bfc5-8752109d4560) ([Sep 22 2018](https://community.folivora.ai/t/goldenchaos-btt-a-complete-touch-bar-ui-replacement-preset/1281/1013?u=goldenchaos))
* [Experimental] [2.639](https://share.folivora.ai/sharedPreset/9146b830-a9c3-49e8-899f-2a434d31e678) ([Sep 22 2018](https://community.folivora.ai/t/goldenchaos-btt-a-complete-touch-bar-ui-replacement-preset/1281/1012?u=goldenchaos))
* [Experimental] [2.638](https://share.folivora.ai/sharedPreset/7550c7af-31a4-430d-addd-d84d0ef3d1c8) ([Sep 12 2018](https://community.folivora.ai/t/goldenchaos-btt-a-complete-touch-bar-ui-replacement-preset/1281/960?u=goldenchaos))
* [Experimental] [2.636-3](https://share.folivora.ai/sharedPreset/e4f0054d-ffb5-4a2f-be11-a846732f3c0d) ([Sep 10 2018](https://community.folivora.ai/t/goldenchaos-btt-a-complete-touch-bar-ui-replacement-preset/1281/943?u=goldenchaos))
* [Experimental] [2.636-2](https://share.folivora.ai/sharedPreset/bda3c8c0-0966-4500-a041-5362e6057d76) ([Sep 10 2018](https://community.folivora.ai/t/goldenchaos-btt-a-complete-touch-bar-ui-replacement-preset/1281/941?u=goldenchaos))
* [Experimental] [2.636](https://share.folivora.ai/sharedPreset/559e421d-e197-432f-9217-50408ae35280) ([Sep 9 2018](https://community.folivora.ai/t/goldenchaos-btt-a-complete-touch-bar-ui-replacement-preset/1281/928?u=goldenchaos))
* [Experimental] [2.635](https://share.folivora.ai/sharedPreset/13221121-6869-4629-b778-0c76b20cdd18) ([Sep 7 2018](https://community.folivora.ai/t/goldenchaos-btt-a-complete-touch-bar-ui-replacement-preset/1281/903?u=goldenchaos))
* [Experimental] [2.634](https://share.folivora.ai/sharedPreset/293c9dc0-3193-46bb-b8ff-0d9eea6cd452) ([Sep 6 2018](https://community.folivora.ai/t/goldenchaos-btt-a-complete-touch-bar-ui-replacement-preset/1281/877?u=goldenchaos))
* [Experimental] [2.628](https://share.folivora.ai/sharedPreset/128e29ea-6aa4-4afb-9d82-721bac88847d) ([Sep 4 2018](https://community.folivora.ai/t/goldenchaos-btt-a-complete-touch-bar-ui-replacement-preset/1281/819?u=goldenchaos))
* [Experimental] [2.627-2](https://share.folivora.ai/sharedPreset/49b10933-b7b4-4bee-ab0e-bebb0c868268) ([Sep 3 2018](https://community.folivora.ai/t/goldenchaos-btt-a-complete-touch-bar-ui-replacement-preset/1281/802?u=goldenchaos))
* [Experimental] [2.627](https://share.folivora.ai/sharedPreset/179910ae-3cf6-4c05-8e62-91c40a4eac88) ([Sep 3 2018](https://community.folivora.ai/t/goldenchaos-btt-a-complete-touch-bar-ui-replacement-preset/1281/786?u=goldenchaos))
* [Experimental] [2.626 "Stitch"](https://share.folivora.ai/sharedPreset/c1120150-ab1c-4464-88b7-743f21075e0b) ([Sep 2 2018](https://community.folivora.ai/t/goldenchaos-btt-a-complete-touch-bar-ui-replacement-preset/1281/766?u=goldenchaos))
* [Experimental] [2.625](https://share.folivora.ai/sharedPreset/2ae8e2d6-acc1-4052-83f9-26d3d0d7ed9b) ([Sep 1 2018](https://community.folivora.ai/t/goldenchaos-btt-a-complete-touch-bar-ui-replacement-preset/1281/756?u=goldenchaos))
* [Experimental] [2.624](https://share.folivora.ai/sharedPreset/8103d6ef-8ed5-47f7-9401-9a1260e82118) ([Aug 31 2018](https://community.folivora.ai/t/goldenchaos-btt-a-complete-touch-bar-ui-replacement-preset/1281/737?u=goldenchaos))
* [Experimental] [2.620-3](https://share.folivora.ai/sharedPreset/4aa1da77-374d-4cb0-9f34-35036b6b885d) ([Aug 31 2018](https://community.folivora.ai/t/goldenchaos-btt-a-complete-touch-bar-ui-replacement-preset/1281/727?u=goldenchaos))
* [Experimental] [2.620-2](https://share.folivora.ai/sharedPreset/9028229c-4e8d-48e0-8ad1-841d254c11b2) ([Aug 30 2018](https://community.folivora.ai/t/goldenchaos-btt-a-complete-touch-bar-ui-replacement-preset/1281/722?u=goldenchaos))
* [Experimental] [2.620](https://share.folivora.ai/sharedPreset/a59225c4-1146-49bb-bba9-eb44c0bd30ec) ([Aug 30 2018](https://community.folivora.ai/t/goldenchaos-btt-a-complete-touch-bar-ui-replacement-preset/1281/706?u=goldenchaos))
* [Experimental] [2.610](https://share.folivora.ai/sharedPreset/6445665d-577f-4e45-87e0-df1100433ddc) ([Aug 28 2018](https://community.folivora.ai/t/goldenchaos-btt-a-complete-touch-bar-ui-replacement-preset/1281/679?u=goldenchaos))
* [Experimental] [2.608-2](https://share.folivora.ai/sharedPreset/2f7e9bea-002e-4ccc-bdd9-b4a0dd3decf2) ([Aug 27 2018](https://community.folivora.ai/t/goldenchaos-btt-a-complete-touch-bar-ui-replacement-preset/1281/647?u=goldenchaos))
* [Experimental] [2.608](https://share.folivora.ai/sharedPreset/12f6a88a-015c-4b2c-9792-00a0a75888f4) ([Aug 27 2018](https://community.folivora.ai/t/goldenchaos-btt-a-complete-touch-bar-ui-replacement-preset/1281/645?u=goldenchaos))
* [Experimental] [2.605-2](https://share.folivora.ai/sharedPreset/96a47646-c038-4c3e-93e2-30efd8885978) ([Aug 26 2018](https://community.folivora.ai/t/goldenchaos-btt-a-complete-touch-bar-ui-replacement-preset/1281/632?u=goldenchaos))
* [Experimental] [2.605](https://share.folivora.ai/sharedPreset/d872de6d-129c-4746-b52b-636d808a63a3) ([Aug 25 2018](https://community.folivora.ai/t/goldenchaos-btt-a-complete-touch-bar-ui-replacement-preset/1281/630?u=goldenchaos))
* **[Verified]** [Stable] [2.600](https://share.folivora.ai/sharedPreset/caf61247-ebc0-4a87-a202-36206aded4e3) ([Aug 23 2018](https://community.folivora.ai/t/goldenchaos-btt-a-complete-touch-bar-ui-replacement-preset/1281/582?u=goldenchaos))
* [Experimental] [2.566-4](https://share.folivora.ai/sharedPreset/158d961c-5ccd-4937-8a39-f11538d346f6) ([Aug 23 2018](https://community.folivora.ai/t/goldenchaos-btt-a-complete-touch-bar-ui-replacement-preset/1281/579?u=goldenchaos))
* [Experimental] [2.566-3](https://share.folivora.ai/sharedPreset/07c58702-52ee-42a5-b80e-cf514d7446ab) ([Aug 22 2018](https://community.folivora.ai/t/goldenchaos-btt-a-complete-touch-bar-ui-replacement-preset/1281/575?u=goldenchaos))
* [Experimental] [2.566-2](https://share.folivora.ai/sharedPreset/86891c5b-3daa-441f-8105-38b0e9f775fc) ([Aug 22 2018](https://community.folivora.ai/t/goldenchaos-btt-a-complete-touch-bar-ui-replacement-preset/1281/574?u=goldenchaos))
* [Experimental] [2.566](https://share.folivora.ai/sharedPreset/26a43ff6-ac50-4513-8872-7b7be1cc3874) ([Aug 22 2018](https://community.folivora.ai/t/goldenchaos-btt-a-complete-touch-bar-ui-replacement-preset/1281/572?u=goldenchaos))
* [Experimental] [2.563-6](https://share.folivora.ai/sharedPreset/26ab6f7c-cbdb-4718-bef9-55eb42cf4bdf) ([Aug 17 2018](https://community.folivora.ai/t/goldenchaos-btt-a-complete-touch-bar-ui-replacement-preset/1281/520?u=goldenchaos))
* [Experimental] [2.563-5](https://share.folivora.ai/sharedPreset/17ca2c5c-7c5b-47ce-9a59-f0d84f631645) ([Aug 17 2018](https://community.folivora.ai/t/goldenchaos-btt-a-complete-touch-bar-ui-replacement-preset/1281/508?u=goldenchaos))
* [Experimental] [2.563-4](https://share.folivora.ai/sharedPreset/6e0a813e-757a-42c7-b15c-f90d959333b6) ([Aug 16 2018](https://community.folivora.ai/t/goldenchaos-btt-a-complete-touch-bar-ui-replacement-preset/1281/486?u=goldenchaos))
* [Experimental] [2.563-3](https://share.folivora.ai/sharedPreset/5e513fe0-fc49-43da-b29e-37ac9c0c438a) ([Aug 16 2018](https://community.folivora.ai/t/goldenchaos-btt-a-complete-touch-bar-ui-replacement-preset/1281/486?u=goldenchaos))
* [Experimental] [2.563-2](https://share.folivora.ai/sharedPreset/7a2c2361-ad4a-475d-94cd-4d7505d96eea) ([Aug 16 2018](https://community.folivora.ai/t/goldenchaos-btt-a-complete-touch-bar-ui-replacement-preset/1281/477?u=goldenchaos))
* [Experimental] [2.563](https://share.folivora.ai/sharedPreset/1e0154b3-d54d-49b0-8b39-9f98148695a1) ([Aug 16 2018](https://community.folivora.ai/t/goldenchaos-btt-a-complete-touch-bar-ui-replacement-preset/1281/469?u=goldenchaos))
* [Experimental] [2.561-5](https://share.folivora.ai/sharedPreset/f4f43887-f1de-43f5-8969-0cc4d2a2a4d6) ([Aug 15 2018](https://community.folivora.ai/t/goldenchaos-btt-a-complete-touch-bar-ui-replacement-preset/1281/459?u=goldenchaos))
* [Experimental] [2.561-4](https://share.folivora.ai/sharedPreset/71943ad6-5546-4d9b-8d57-29afc5adf98f) ([Aug 15 2018](https://community.folivora.ai/t/goldenchaos-btt-a-complete-touch-bar-ui-replacement-preset/1281/452?u=goldenchaos))
* [Experimental] [2.561-3](https://share.folivora.ai/sharedPreset/5dcb4ca6-1cd3-4892-a8a1-e1a2bc237e86) ([Aug 15 2018](https://community.folivora.ai/t/goldenchaos-btt-a-complete-touch-bar-ui-replacement-preset/1281/439?u=goldenchaos))
* [Experimental] [2.561-2](https://share.folivora.ai/sharedPreset/555e2a89-3490-4a71-9977-d45ea960f296) ([Aug 15 2018](https://community.folivora.ai/t/goldenchaos-btt-a-complete-touch-bar-ui-replacement-preset/1281/422?u=goldenchaos))
* [Experimental] [2.561](https://share.folivora.ai/sharedPreset/793cda1f-3ee8-4eeb-aa35-5a19b4042c4f) ([Aug 15 2018](https://community.folivora.ai/t/goldenchaos-btt-a-complete-touch-bar-ui-replacement-preset/1281/422?u=goldenchaos))
* [Experimental] [2.557-4](https://share.folivora.ai/sharedPreset/0653bf00-61ba-4310-ab2d-ad8b51603e63) ([Aug 14 2018](https://community.folivora.ai/t/goldenchaos-btt-a-complete-touch-bar-ui-replacement-preset/1281/395?u=goldenchaos))
* [Experimental] [2.557-3](https://share.folivora.ai/sharedPreset/50e45395-bf7f-4a6c-8259-60879e46c934) ([Aug 14 2018](https://community.folivora.ai/t/goldenchaos-btt-a-complete-touch-bar-ui-replacement-preset/1281/387?u=goldenchaos))
* [Experimental] [2.557-2](https://share.folivora.ai/sharedPreset/395e9310-a788-4b55-a995-cb6ba77bdd81) ([Aug 14 2018](https://community.folivora.ai/t/goldenchaos-btt-a-complete-touch-bar-ui-replacement-preset/1281/380?u=goldenchaos))
* [Experimental] [2.557](https://share.folivora.ai/sharedPreset/e1012f50-0944-458c-90e9-d33fd06db674) ([Aug 14 2018](https://community.folivora.ai/t/goldenchaos-btt-a-complete-touch-bar-ui-replacement-preset/1281/370?u=goldenchaos))
* [Experimental] [2.555](https://share.folivora.ai/sharedPreset/777a81e0-3d7b-4776-9a49-1721b318d1cc) ([Aug 13 2018](https://community.folivora.ai/t/goldenchaos-btt-a-complete-touch-bar-ui-replacement-preset/1281/360?u=goldenchaos))
* [Experimental] [2.553-2](https://share.folivora.ai/sharedPreset/4da264bd-a2ee-4813-b04f-e8bd6a95a14f) ([Aug 13 2018](https://community.folivora.ai/t/goldenchaos-btt-a-complete-touch-bar-ui-replacement-preset/1281/338?u=goldenchaos))
* [Experimental] [2.553](https://share.folivora.ai/sharedPreset/53a728a8-36e6-4047-846f-3ba0f17dc884) ([Aug 12 2018](https://community.folivora.ai/t/goldenchaos-btt-a-complete-touch-bar-ui-replacement-preset/1281/318?u=goldenchaos))
* [Experimental] [2.551-2](https://share.folivora.ai/sharedPreset/3cfbcdd5-f57a-47fe-8d1e-62989c452af8) ([Aug 11 2018](https://community.folivora.ai/t/goldenchaos-btt-a-complete-touch-bar-ui-replacement-preset/1281/299?u=goldenchaos))
* [Experimental] [2.551](https://share.folivora.ai/sharedPreset/e975248f-49e4-485f-9100-c0f8bf039a39) ([Aug 11 2018](https://community.folivora.ai/t/goldenchaos-btt-a-complete-touch-bar-ui-replacement-preset/1281/294?u=goldenchaos))
* [Experimental] [2.550](https://share.folivora.ai/sharedPreset/13c914f9-98ca-40a0-8e18-a248f19e3c86) ([Aug 10 2018](https://community.folivora.ai/t/goldenchaos-btt-a-complete-touch-bar-ui-replacement-preset/1281/291?u=goldenchaos))
* [Experimental] [2.543](https://share.folivora.ai/sharedPreset/bbcb00a7-7934-40bb-8eff-66ea380eafe6) ([Aug 7 2018](https://community.folivora.ai/t/goldenchaos-btt-a-complete-touch-bar-ui-replacement-preset/1281/253?u=goldenchaos))
* **[Verified]** [Experimental] [2.536-5](https://share.folivora.ai/sharedPreset/3bc3e084-64dd-4aa0-9187-dc7c7774db3e) ([Aug 2 2018](https://community.folivora.ai/t/goldenchaos-btt-a-complete-touch-bar-ui-replacement-preset/1281/189?u=goldenchaos))
* **[Verified]** [Stable] [2.536-4](https://share.folivora.ai/sharedPreset/64d0242f-ddd8-4745-991a-f7c8f220211d) ([Aug 1 2018](https://community.folivora.ai/t/goldenchaos-btt-a-complete-touch-bar-ui-replacement-preset/1281/179?u=goldenchaos))
*  **[Verified]** [Stable] [2.536-3](https://share.folivora.ai/sharedPreset/96df1486-847e-471e-a588-fb924221ad8f) ([Jul 30 2018](https://community.folivora.ai/t/goldenchaos-btt-a-complete-touch-bar-ui-replacement-preset/1281/164?u=goldenchaos))
* [Experimental] [2.536-2](https://share.folivora.ai/sharedPreset/12064a3a-7bd2-4d44-a997-7451f9bf6a93) ([Jul 27 2018](https://community.folivora.ai/t/goldenchaos-btt-a-complete-touch-bar-ui-replacement-preset/1281/155?u=goldenchaos))
* [Experimental] [2.536](https://share.folivora.ai/sharedPreset/6fe03dd3-5ec6-47be-8919-3d4af731d804) ([Jul 27 2018](https://community.folivora.ai/t/goldenchaos-btt-a-complete-touch-bar-ui-replacement-preset/1281/151?u=goldenchaos))
* [Experimental] [2.532](https://share.folivora.ai/sharedPreset/10f16d6d-aa23-4102-8867-19eda845a1d1) ([Jul 24 2018](https://community.folivora.ai/t/goldenchaos-btt-a-complete-touch-bar-ui-replacement-preset/1281/120?u=goldenchaos))
* [Experimental] [2.531-3](https://share.folivora.ai/sharedPreset/7d804a90-e42c-437b-9a9c-e12a5d968dcf) ([Jul 24 2018](https://community.folivora.ai/t/goldenchaos-btt-a-complete-touch-bar-ui-replacement-preset/1281/110?u=goldenchaos))
* [Experimental] [2.531-2](https://share.folivora.ai/sharedPreset/754bafa8-8503-4a6c-98af-bd817cd9d160) ([Jul 24 2018](https://community.folivora.ai/t/goldenchaos-btt-a-complete-touch-bar-ui-replacement-preset/1281/92?u=goldenchaos))
* [Experimental] [2.531](https://share.folivora.ai/sharedPreset/a6a7a966-9e0c-49b2-add8-1563771a4a2a) ([Jul 24 2018](https://community.folivora.ai/t/goldenchaos-btt-a-complete-touch-bar-ui-replacement-preset/1281/88?u=goldenchaos))
* [Experimental] [2.530-2](https://share.folivora.ai/sharedPreset/7f4c3c26-7d1d-45fe-8d6f-05f9e0d6dc69) ([Jul 12 2018](https://community.folivora.ai/t/goldenchaos-btt-a-complete-touch-bar-ui-replacement-preset/1281/64?u=goldenchaos))
* [Experimental] [2.530](https://share.folivora.ai/sharedPreset/5c011f73-1fc5-4b8d-98e6-bbbfd4274d21) ([Jul 10 2018](https://community.folivora.ai/t/goldenchaos-btt-a-complete-touch-bar-ui-replacement-preset/1281/61?u=goldenchaos))
* [Experimental] [2.526](https://share.folivora.ai/sharedPreset/e7946192-b164-43d9-b158-ec4f690d8d8d) ([Jun 27 2018](https://community.folivora.ai/t/goldenchaos-btt-a-complete-touch-bar-ui-replacement-preset/1281/40?u=goldenchaos))
* [Experimental] [2.525-2](https://share.folivora.ai/sharedPreset/7edf3f74-07d1-4019-ab2a-615119692b65) ([Jun 23 2018](https://community.folivora.ai/t/goldenchaos-btt-a-complete-touch-bar-ui-replacement-preset/1281/40?u=goldenchaos))
* [Experimental] [2.525](https://share.folivora.ai/sharedPreset/60a1cf01-c8f8-40f8-b0b2-485015f3eb29) ([Jun 21 2018](https://community.folivora.ai/t/goldenchaos-btt-a-complete-touch-bar-ui-replacement-preset/1281/39?u=goldenchaos))
* [Experimental] [2.518-3](https://share.folivora.ai/sharedPreset/f6db5d05-236a-4814-b83d-2de174294e6b) ([Jun 15 2018](https://community.folivora.ai/t/goldenchaos-btt-a-complete-touch-bar-ui-replacement-preset/1281/31?u=goldenchaos))
* [Experimental] [2.518-2](https://share.folivora.ai/sharedPreset/e38094fc-e6a2-4b26-aaed-2fc3c7c68cea) ([Jun 14 2018](https://community.folivora.ai/t/goldenchaos-btt-a-complete-touch-bar-ui-replacement-preset/1281/26?u=goldenchaos))
* [Experimental] 2.518 ([Jun 13 2018](https://community.folivora.ai/t/goldenchaos-btt-a-complete-touch-bar-ui-replacement-preset/1281/24?u=goldenchaos), download unavailable)
* [Experimental] [2.516](https://share.folivora.ai/sharedPreset/9e625ac1-cc19-446d-8545-734a04c3875d) ([Jun 6 2018](https://community.folivora.ai/t/goldenchaos-btt-a-complete-touch-bar-ui-replacement-preset/1281/14?u=goldenchaos))
* **[Verified]** [Stable] [2.513](https://share.folivora.ai/sharedPreset/97da12ef-3e78-4a6a-a831-87e707f5e043) (Jun 1 2018, initial public release)

#  
> ### I make other cool stuff, too, like [Zelda Maps for Breath of the Wild](https://zeldamaps.com)! Check out all my other projects at https://goldenchaos.net. And thank you for trying out GoldenChaos-BTT! 🙂