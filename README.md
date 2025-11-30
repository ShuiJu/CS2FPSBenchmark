# CounterStrike 2 FPS Benchmark result
Collecting CS2 "FPS Benchmark" benchmark results for referencing.

For who kindly provided their graphics settings, I'll new a folder for listing their settings, naming as "Avg FPS+P1 FPS+Spec".

## Due to the update at 2024/10/04, 

Value finally deband shadow render distance with shadow rendering quality, which means now you will get player's shadow rendered within ~1500 units distance without requirement of setting shadow quality to high or above.

This change is clearly a good move from gameplay perspective, but it will decrease the accruacy of legacy benchmark runs befor the update. 

So I removed most of the pre-update results from the homepage of this project. 

Don't worry there is a "All results.md", every record i received is listed here. 

# Results: 
| CPU | GPU | RAM | Avg FPS | P1 FPS | Resolution + Overall Graphics Settings | Date of benchmark |
| :-- | :-- | --- | :------ | :------ | :------------------------------------ | :---------------- |
|   |  PRE 10/04 update results starts from here:  |   Please do not compare them directly to POST update results  |    |   |   |   |
| Intel 13600KF 6P12T | GeForce RTX4070Ti | DDR5 6400C36XMP | 373.6 | 185.8 | 1440P + Overall High | 2024/05/10 |
| Ryzen 5800H @ PL1=54W | GeForce RTX3070 Mobile | DDR4 3200 JEDEC | 190.3 | 104.9 | 2160P + Overall Low | 2024/05/10 |
| Ryzen 7800X3D PBO on, CO-40 | GeForce RTX4070 Super | DDR5 6000C30XMP | 497.8 | 279.7 | 1280x960 + Overall High | 2024/05/10 |
| Intel 12700KF 8P16T | GeForce RTX4070 Super | DDR5 6400C36XMP | 447.1 | 201.2 | 1440P + Overall Low | 2024/05/10 |
| Intel 12400F | Radeon RX 6700XT | DDR5 5200XMP | 268.6 | 129.9 | 1080P + Overall High | 2024/05/11 |
| Intel 11400F | GeForce GTX1060 6G | DDR4 3000XMP | 231.4 | 130.4 | 1080P + Overall Low | 2024/05/11 |
| Ryzen 5800X3D | GeForce RTX3070 LHR | DDR4 3600XMP | 365.5 | 193.9 | 1080P + Overall High | 2024/05/11 |
| Ryzen 5900X PBO on | GeForce RTX4090 @ 2800Mhz | DDR4 3600C16XMP | 445.3 | 173.1 | 1080P + All High + No AA | 2024/05/11 | 
| Intel 12400 6P12T | Radeon RX580 @ Vcore=0.99V/Mem=2100Mhz | DDR4 3333C16 | 241.4 | 124.4 | 1280x1024 + Overall Low  | 2024/05/20 |
|   |  POST 10/04 update results starts from here:  |   Please do not compare them directly to PRE update results  |    |   |   |   |
| Ryzen 7600 | GeForce RTX4070 Super | DDR5 6000C30 | 499.8 / 313 | 167.5 / 160.8 | 1080P + Overall low graphics settings / Maximum Preset | 2024/10/05 |
| Ryzen 5950X PBO On | GeForce RTX2080Ti | DDR4 3600XMP | 410.8 / 250.7 | 155.7 / 123.9 | 1080P + Low Preset no FSR / Maximum Preset | 2024/10/07 |
| Ryzen 5950X PBO On | GeForce RTX4070 Super | DDR4 3600XMP | 462.2 / 311.4 | 160.2 / 133.0 | 1080P + Low Preset no FSR / Maximum Preset | 2024/10/07 |
|   |  All aboard update results starts from here:  |   Please do not compare them directly to PRE update results  |    |   |   |   |
| Ultra 285K Heavily OC | GeForce RTX4090 | DDR5 8800C40 | 818.3 | 246.3 | 1080P Low Preset | 2024/11/19 |
| Ultra 285K Heavily OC | GeForce RTX4070Ti Super | DDR5 8800C38 | 599.3 | 215.3 | 1280x960 Overall medium | 2024/11/19 |
| Ryzen 7700 | GeForce RTX2080Ti 11G | DDR5 6000C32 | 333.6 | 141.7 | 1080P High Preset (failed to apply profile due to deviceID was not changed)  | 2025/01/01 |
| Ryzen 7700 | GeForce RTX2080Ti 11G | DDR5 6000C32 | 521.6 | 189.3 | 1280x1024 + Overall Medium  | 2025/01/01 |
| Ryzen 9700X | GeForce RTX4070Ti Super 16G | DDR5 6000C30 | 691.4 | 208.6 | 1080P Low Preset + FSRP | 2025/03/12 |
| Ryzen 9700X | GeForce RTX4070Ti Super 16G | DDR5 6000C30 | 597.5 | 190.4 | 1080P Overall medium | 2025/03/12 |
| Ryzen 5800X3D | GeForce RTX3080 10G @ 1815Mhz | DDR4 3600C14 | 449.7 / 574.3 / 575.0 | 227.5 / 221.0 / 216.0 | 1920x1280 / 1620x1080 / 1440x1080 Overall medium my settings | 2025/04/05 |
| Intel 13490F | GeForce RTX3060 12G | DDR4 3200C18 | 164.6 / 413.1 | 86.9 / 161.1 | 1080P Maximum Preset / 1080P Low Preset + FSRP. | 2025/04/05 |
| Intel 13600KF, affected, 4.7Ghz | GeForce RTX2080 Super 8G | DDR5 5300 | 237.9 / 555.7 | 121.7 / 208.1 | 1080P Maximum Preset / 1080P Low Preset + FSRP. | 2025/04/05 |
| Ryzen 7800X3D PBO On +0Mhz CO-0 | GeForce RTX4070Ti 12G @ Stock | DDR5 6000C30 | 914.6 | 314.7 | 1080P Low Preset + FSRP. | 2025/04/13 |
| Intel 13900HX PL1 Unlimited @ 80W | GeForce RTX4060 Mobile CTGP Enabled, DB2.0 Disabled | DDR5 5600 JEDEC | 530.9 | 185.3 | 640x480P Low Preset + FSRP | 2024/04/14 |
| Ryzen 9800X3D PBO On +150Mhz | Radeon RX9070XT @ -500Mhz -50mv, Full load 210W | DDR5 6000C36 | 403.6 / 922.8 | 240.2 / 318.9 | 1080P Maximum Preset / 1080P Low Preset + FSRP. | 2025/05/04 |
| Ryzen 5800X3D | GeForce RTX3080 10G @ 1815Mhz | DDR4 3600C14 | 318.3 / 530.8 / 703.5 | 176.6 / 231.5 / 242.1 | 1080P Maximum Preset / 1080P Medium Preset + Native / 1080P Low Preset + FSRP. | 2025/05/11 |
| Ryzen 9600X | Radeon RX6800XT | DDR5 6000C30 | 331.0 / 542.5 / 731.0 | 174.9 / 223.8 / 234.7 | 1080P Maximum Preset / 1080P Medium Preset + Native / 1080P Low Preset + FSRP. (Win10) | 2025/05/12 |
| Intel 10850K @ 4.8Ghz core, 4.5Ghz cache, 10C10T, PL=0 | GeForce RTX3060 12G @ 2100Mhz core, 2075Mhz VRAM | DDR4 4000C15 | 549.5 | 205.4 | 1024x768 Overall Low | 2025/08/04 |
| Intel 13650HX @ PL1=55W | GeForce RTX4060 8G @ TGP=80W | DDR5 5600C40 | 434.5 | 170.1 | 1080P Low Preset + FSRP. | 2025/09/04 |
| Ryzen 5800X3D | GeForce RTX3080 10G @ 1815Mhz | DDR4 3600C14 | 324.8 / 537.9 / 716.6 | 182.6 / 233.7 / 239.8 | 1080P Maximum Preset / 1080P Medium Preset + Native / 1080P Low Preset + FSRP. | 2025/10/11 |
| Ryzen 9950X PBO On CO-10 | GeForce RTX5080 16G | DDR5 6400C32 XMP | 728.4 | 227.0 | 1080P Low Preset + FSRP. | 2025/11/19 |
| Ryzen 5800X3D | GeForce RTX3080 10G @ 1815Mhz | DDR4 3600C14 | 309.4 / 516.3 / 659.7 | 111.8 / 209.2 / 230.7 | 1080P Maximum Preset / 1080P Medium Preset + Native / 1080P Low Preset + FSRP. SMT off | 2025/11/19 |
| Ryzen 5800X3D | GeForce RTX3080 10G @ 1815Mhz | DDR4 3600C14 | 314.2 / 520.6 / 680.2 | 165.0 / 215.5 / 259.5 | 1080P Maximum Preset / 1080P Medium Preset + Native / 1080P Low Preset + FSRP. SMT off Traditional CS2 shader recompile | 2025/11/20 |
| Ryzen 9950X PBO On CO-10 | GeForce RTX5080 16G | DDR5 6400C32 XMP | 922.7 | 267.0 | 1080P Low Preset + FSRP. | 2025/11/22 |
| CPU | GPU | RAM | Avg FPS | P1 FPS | Resolution + Overall Graphics Settings | Date of benchmark |


# Why collecting benchmark result from player is useful?
I'm not criticizing but there are limitations for general reviewers who might play or not the game.
At the same time they simply can't using E-Sport settings for their reviews of product. 

It is also need to be considered that daily driving machine is not background application free. More cores might not effecting FPS in reviews, but will effect real life situation.

After the reviewers slowly adapted to CS2 benchmarking, the main object of this list has been finished.

But I'll keep recording new results submitted to me (or results I tested by my hands on my friends PC). Personally i'm now focusing on gather data of 1080P Maximum Preset and 1080P Low Preset + FSRP. Two seperate tests to give reference of if using different graphics setting, what will the upper and lower FPS will be expected. 

For example, RDNA4 cards are kind slower than expected at current driver. (2025/05/11) But when it trends to CPU bottlenecked, the performance will be better than what you imagined from a result of GPU bottlenecked test.





# How to benchmark?
Use this workshop map: https://steamcommunity.com/sharedfiles/filedetails/?id=3240880604

## How to submit result?
### You can..
New an issue, list your result in this way: (Recommended)

1 CPU

1-1 if Overclocked/Tweaked, what frequency or power setting you are running at? (which is optional, if not OC then do not include)

2 GPU

2-1 if Overclocked/Tweaked...

3 RAM Speed and primary timings, if XMP then just give freq.+XMP.

3-1 if...

4 Avg FPS/P1 FPS

### Or
Send email title started with CS2 Benchmark result + *Date of benchmark* to uubxar7dl@mozmail.com

### Why not Google Docs?
Because Google is completely banned in some countries... And also you can check the history. 

## What graphics setting and resolution should I use?
### Submit one of the choices, but MORE is BETTERRRR
1. Result of your own combination favor, such as 4:3 1280x960 with your own graphics settings. You do not need to specify your settings but you can. **BUT if you uses FSR, you MUST list in your description.** (This will be a "optimized situation" performance showcase of your hardware.)
2. Native 16:9 1080P/1440P/2160P with Maximum Preset (1080P is better, this will be a GPU limited benchmark for average random player.)
3. 16:9 1080P your settings with Fidelity FX SuperResolution set to Performance (this will be a CPU limited benchmark for average random player.)



## Example for submitting result:
1 Ryzen 5 7600

1-1 PBO on

2 RTX3080

2-1 Undervolted, GPU gaming frequency at 1800Mhz

3 DDR5 5600XMP

4 

4-1 1080P + Overall low graphics settings: 458.1/182.5

4-2 1080P + Overall low graphics settings + FSR Performance: 472.5/197.6

4-3 1080P Maximum: 336.8/151.2

5

Date of benchmark (default to be issue/email sending date)




### Don't worry, I'll update the form when I can't play CS2... So no updates on weekends XD


And I don't have relay premium so no replies sorry.


# What's next?
Share, subscribe, click that bell button... Just joking.

But share this project to your friends, maybe they can also submit results of their machine. I believe this will be a better reference book than checking reviewers buying guide...

Man the graphics cards are way too expensive nowadays...



# My Current video setting: (I start upload the cs2_video.txt again...)

Before you try my settings directly by download cs2_video.txt, please beware to change "VendorID" and "DeviceID" to your specific ones. Otherwise it wont work and go back to default.

Boost player contrast: on (This is a free official vacless cheat given by valve let you see people much clear when smoke is around. If you have any choices left for performance, dont disable it.)

V-Sync: off

Reflex: Enable

Anti aliasing: 2xMSAA + CMAA2 (A GPU perf sucker. For my 58X3D+3080 at 1080P, 4x:493 2x:515 CMAA2:523 Disabled:538. At 1440P for more GPU bottleneck, 4x:363 2x:399 CMAA2:412 Disabled:436.) (You can actually manually set MSAA with CMAA2, just edit your cs2_video.txt.)

Global Shadow Quality: Low (After another shadow rendering distance update, now I feel medium is kinda strange for sudden quality changing in sight. I felt it's annoying)

Dynamic Shadows: All (Why, tell me why baby.mp4)

Model/Texture detail: High (After previous update, this no longer kills FPS with molotov no matter High or Low, but the skin looks just better.)

Texture filtering: Ani16x (Basically no performance impact on my machine, Bi:543/225 Ani4x:538/230 Ani16x: 534/234. And, for any choices lower than 4x, watch closer to your deagle skin on barrel. IT BLURS. For example Desert Eagle | Starcade.)

Shader detail: Low (Just do Low, for visual clearity issue.)

Particle detail: Low (Just do Low, for visual clearity issue.)

Ambient occlusion: Disabled (After lots of comparision made, I choose to disable not only just for performance.)

HDR: Quality (No performance impact on my machine in FPS Benchmark, 543vs546. In Ancient empty map 650vs620 Quality eliminates visual noise. When using Performance and at a lower resolution, is noticable when trying to align utility throws.)

FSR: Disable


# Some investigation to Anti-Aliasing impact to CPU performance
Due to my 3080 is lacking of performance (that compares to my 5800X3D), for today's test, i'll use 640x480 to try to avoid GPU bottleneck happening.

I'll underclock my 58X3D for scientific purpose (xD) some day later to try maybe 4:3 960P or if possible 4:3 1080P.

At this time, the conclusion for FSR is it is not magic. It will give you more FPS when your GPU sucks, but it will cost a fraction of your CPU performance. It is not completely free magic.

When enabling MSAA, 8xMSAA will not cost significantly more performance on your CPU comparing to 2xMSAA. 

CMAA2 is almost a completely CPU cost free AA. CMAA2 cost little to GPU performance.

| Ryzen 5800X3D + GeForce RTX3080 10G @ 1800Mhz + DDR4 3600C14, at 2024/11/19 | Resolution | Graphics Settings |
| :----- | :----- | :----- |
| 704.9/230.0 | 640x480 | Min + FSR P, no AA |
| 701.8/223.5 | 640x480 | Min + FSR P, CMAA2 |
| 687.0/230.9 | 640x480 | Min + FSR P, 2xMSAA |
| 684.0/225.6 | 640x480 | Min + FSR P, 4xMSAA |
| 681.5/225.1 | 640x480 | Min + FSR P, 8xMSAA |
| 712.8/233.8 | 640x480 | Min + noFSR, no AA |
| 689.3/232.3(max 90% GPU Util observed) | 640x480 | Min + noFSR, 8xMSAA |
| 386.8/197.5 | 1920x1080 | Max, no AA |
| 375.7/180.7 | 1920x1080 | Max, CMAA2 |


# Troubleshooting related links:

Shader recompile:

https://steamcommunity.com/app/730/discussions/0/3821922030307688567/