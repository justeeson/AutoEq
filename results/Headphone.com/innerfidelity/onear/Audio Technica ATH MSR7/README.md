# Audio Technica ATH MSR7
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 5.9; 25 5.6; 26 5.5; 28 5.2; 30 4.9; 32 4.6; 35 4.3; 37 4.1; 40 3.8; 42 3.7; 45 3.6; 49 3.4; 52 3.3; 56 3.2; 59 3.1; 64 2.9; 68 2.8; 73 2.6; 78 2.4; 83 2.2; 89 1.8; 95 1.4; 102 0.9; 109 0.5; 117 0.0; 125 -0.4; 134 -0.6; 143 -0.8; 153 -1.0; 164 -1.3; 175 -0.8; 188 -0.6; 201 -0.8; 215 -0.8; 230 -0.8; 246 -0.8; 263 -0.7; 282 -0.4; 301 -0.1; 323 0.2; 345 0.7; 369 1.1; 395 1.7; 423 2.2; 452 2.6; 484 2.8; 518 3.0; 554 3.1; 593 2.9; 635 2.6; 679 2.1; 726 1.7; 777 1.3; 832 0.9; 890 0.5; 952 0.2; 1019 0.0; 1090 0.0; 1167 0.1; 1248 0.3; 1336 0.6; 1429 0.8; 1529 0.9; 1636 0.8; 1751 0.8; 1873 0.9; 2004 1.5; 2145 2.7; 2295 4.0; 2455 5.0; 2627 5.9; 2811 6.0; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 6.0; 4219 5.8; 4514 5.7; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 5.9; 25 5.6; 26 5.5; 28 5.2; 30 4.9; 32 4.6; 35 4.3; 37 4.1; 40 3.8; 42 3.7; 45 3.6; 49 3.4; 52 3.3; 56 3.2; 59 3.1; 64 2.9; 68 2.8; 73 2.6; 78 2.4; 83 2.2; 89 1.8; 95 1.4; 102 0.9; 109 0.5; 117 0.0; 125 -0.4; 134 -0.6; 143 -0.8; 153 -1.0; 164 -1.3; 175 -0.8; 188 -0.6; 201 -0.8; 215 -0.8; 230 -0.8; 246 -0.8; 263 -0.7; 282 -0.4; 301 -0.1; 323 0.2; 345 0.7; 369 1.1; 395 1.7; 423 2.2; 452 2.6; 484 2.8; 518 3.0; 554 3.1; 593 2.9; 635 2.6; 679 2.1; 726 1.7; 777 1.3; 832 0.9; 890 0.5; 952 0.2; 1019 0.0; 1090 0.0; 1167 0.1; 1248 0.3; 1336 0.6; 1429 0.8; 1529 0.9; 1636 0.8; 1751 0.8; 1873 0.9; 2004 1.5; 2145 2.7; 2295 4.0; 2455 5.0; 2627 5.9; 2811 6.0; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 6.0; 4219 5.8; 4514 5.7; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Headphone.com/innerfidelity/onear/Audio%20Technica%20ATH%20MSR7/Audio%20Technica%20ATH%20MSR7.png)