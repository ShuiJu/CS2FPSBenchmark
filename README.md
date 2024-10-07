# CounterStrike 2 FPS Benchmark result
Collecting CS2 "FPS Benchmark" benchmark results for referencing.

For who kindly provided their graphics settings, I'll new a folder for listing their settings, naming as "Avg FPS+P1 FPS+Spec".

I created another file for backup all of the benchmark, and removed some of the benchmark that is less useful to general player.

## Due to the update at 2024/10/04, 

Value finally deband shadow render distance with shadow rendering quality, which means now you will get player's shadow rendered within 1400 units distance without requirement of setting shadow quality to high or above.

This change is clearly a good move from gameplay perspective, but it will decrease the accruacy of legacy benchmark runs befor the update. 

So I removed most of the pre-update results from the homepage of this project. 

Don't worry there is a "All results.md", every record i received is listed here. 

# Results: 
| CPU | GPU | RAM | Avg FPS | P1 FPS | Resolution + Overall Graphics Settings | Date of benchmark |
| :-- | :-- | --- | :------ | :------ | :------------------------------------ | :---------------- |
|   |  PRE 10/04 update results starts from here:  |   Please do not compare them directly to POST update results  |    |   |   |   |
| Intel 13900HX @ PL1=80w | GeForce RTX4060 Mobile DB2.0 Disabled | DDR5 5600 JEDEC | 357.8 | 181.2 | 1080P + Overall low | 2024/05/10 |
| Intel 13600KF 6P12T | GeForce RTX4070Ti | DDR5 6400C36XMP | 373.6 | 185.8 | 1440P + Overall High | 2024/05/10 |
| Ryzen 5800H @ PL1=54W | GeForce RTX3070 Mobile | DDR4 3200 JEDEC | 190.3 | 104.9 | 2160P + Overall Low | 2024/05/10 |
| Ryzen 7800X3D PBO on, CO-40 | GeForce RTX4070 Super | DDR5 6000C30XMP | 497.8 | 279.7 | 1280x960 + Overall High | 2024/05/10 |
| Intel 12700KF 8P16T | GeForce RTX4070 Super | DDR5 6400C36XMP | 447.1 | 201.2 | 1440P + Overall Low | 2024/05/10 |
| Intel 12400F | Radeon RX 6700XT | DDR5 5200XMP | 268.6 | 129.9 | 1080P + Overall High | 2024/05/11 |
| Intel 11400F | GeForce GTX1060 6G | DDR4 3000XMP | 231.4 | 130.4 | 1080P + Overall Low | 2024/05/11 |
| Ryzen 5800X3D | GeForce RTX3070 LHR | DDR4 3600XMP | 365.5 | 193.9 | 1080P + Overall High | 2024/05/11 |
| Ryzen 5900X PBO on | GeForce RTX4090 @ 2800Mhz | DDR4 3600C16XMP | 445.3 | 173.1 | 1080P + All High + No AA | 2024/05/11 | 
| Intel 12400 6P12T | Radeon RX580 @ Vcore=0.99V/Mem=2100Mhz | DDR4 3333C16 | 241.4 | 124.4 | 1280x1024 + Overall Low  | 2024/05/20 |
| Ryzen 5800X3D | GeForce RTX3080 10G @ 1800Mhz | DDR4 3600C14 | 535.4 | 223.3 | 1080P + Overall low | 2024/09/01 |
|   |  POST 10/04 update results starts from here:  |   Please do not compare them directly to PRE update results  |    |   |   |   |
| Ryzen 5800X3D | GeForce RTX3080 10G @ 1725Mhz | DDR4 3600C14 | 282.5 / 469.8 / 585.2 | 149.3 / 177 / 191.0 | 1080P Maximum Preset / 1080P Medium Preset + Native / 1080P Low Preset + FSRP | 2024/10/04 |
| Ryzen 7600 | GeForce RTX4070 Super | DDR5 6000C30 | 499.8 / 313 | 167.5 / 160.8 | 1080P + Overall low graphics settings / Maximum Preset | 2024/10/05 |
| Ryzen 5950X PBO On | GeForce RTX2080Ti | DDR4 3600XMP | 410.8 / 250.7 | 155.7 / 123.9 | 1080P + Low Preset no FSR / Maximum Preset | 2024/10/07 |
| Ryzen 5950X PBO On | GeForce RTX4070 Super | DDR4 3600XMP | 462.2 / 311.4 | 160.2 / 133.0 | 1080P + Low Preset no FSR / Maximum Preset | 2024/10/07 |
| CPU | GPU | RAM | Avg FPS | P1 FPS | Resolution + Overall Graphics Settings | Date of benchmark |


## Why collecting benchmark result from player is useful?
I'm not criticizing but there are limitations for general reviewers who might play or not the game.
At the same time they simply can't using E-Sport settings for their reviews of product. Or they have not transfer their reviews to CS2 version of the game yet. 
> Also, if they are getting started benchmarking new component using CS2, they are going to choose whether test huge amount of data for old hardware, or just pick some iconic ones, which is less useful for general player who don't upgrade their PC yearly. 

> An example, TechPowerUp still use CSGO FPS Benchmark for their 14th gen review:

> https://www.techpowerup.com/review/intel-core-i5-14600k/17.html

> It is also need to be considered that daily driving machine is not background application free. More cores might not effecting FPS in reviews, but will effect real life situation.





## How to benchmark?
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
3. Native 16:9 1080P your settings with Fidelity FX SuperResolution set to Performance (this will be a CPU limited benchmark for average random player.)



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


### What's next?
Share, subscribe, click that bell button... Just joking.

But share this project to your friends, maybe they can also submit results of their machine. I believe this will be a better reference book than checking reviewers buying guide...

Man the graphics cards are way too expensive nowadays...



### My Current video setting:
Boost player contrast: off

V-Sync: off

Reflex: Enable+Boost

Anti aliasing: 2xMSAA (A GPU perf sucker. For my 58X3D+3080 at 1080P, 4x:493 2x:515 CMAA2:523 Disabled:538. At 1440P for more GPU bottleneck, 4x:363 2x:399 CMAA2:412 Disabled:436.)

Global Shadow Quality: High (You are going to choose either Low or High. Medium and Very High makes no sense.)

Dynamic Shadows: All 

Model/Texture detail: Low (Molotov kills my FPS, I will keep using low before setting.r_csgo_mboit_force_mixed_resolution can be tweaked again.)

Texture filtering: Ani16x (Basically no performance impact on my machine, Bi:543/225 Ani4x:538/230 Ani16x: 534/234.)

Shader detail: Low 

Particle detail: Low

Ambient occlusion: Disabled (Disabaled:511/233 Mid:493/222 High:490/208)

HDR: Quality (No performance impact on my machine in FPS Benchmark, 543vs546. In Ancient empty map 650vs620 Quality eliminates visual noise. When using Performance and at a lower resolution, is noticable when trying to align utility throws.)

FSR: Disable
