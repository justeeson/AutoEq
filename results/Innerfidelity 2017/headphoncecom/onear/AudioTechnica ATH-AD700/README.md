# AudioTechnica ATH-AD700
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 6.0; 52 6.0; 56 6.0; 59 6.0; 64 6.0; 68 6.0; 73 6.0; 78 6.0; 83 5.6; 89 4.9; 95 4.3; 102 3.9; 109 3.5; 117 3.0; 125 2.4; 134 1.9; 143 1.5; 153 1.2; 164 1.3; 175 1.0; 188 0.7; 201 0.5; 215 0.4; 230 0.3; 246 0.1; 263 0.1; 282 -0.1; 301 -0.1; 323 -0.1; 345 -0.1; 369 -0.0; 395 -0.0; 423 -0.2; 452 -0.3; 484 -0.4; 518 -0.5; 554 -0.1; 593 0.5; 635 0.6; 679 0.6; 726 0.5; 777 0.6; 832 0.3; 890 0.2; 952 0.2; 1019 -0.1; 1090 -0.2; 1167 -0.3; 1248 -0.3; 1336 -0.1; 1429 0.2; 1529 0.5; 1636 0.9; 1751 1.0; 1873 0.8; 2004 0.6; 2145 0.2; 2295 0.6; 2455 0.2; 2627 -0.3; 2811 -0.6; 3008 -0.6; 3219 -0.7; 3444 1.6; 3685 5.0; 3943 6.0; 4219 4.5; 4514 4.0; 4830 5.0; 5168 5.9; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 0.7; 7756 -2.2; 8299 -4.0; 8880 -5.1; 9502 -5.3; 10167 -3.4; 10879 -0.3; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 -0.4
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 6.0; 52 6.0; 56 6.0; 59 6.0; 64 6.0; 68 6.0; 73 6.0; 78 6.0; 83 5.6; 89 4.9; 95 4.3; 102 3.9; 109 3.5; 117 3.0; 125 2.4; 134 1.9; 143 1.5; 153 1.2; 164 1.3; 175 1.0; 188 0.7; 201 0.5; 215 0.4; 230 0.3; 246 0.1; 263 0.1; 282 -0.1; 301 -0.1; 323 -0.1; 345 -0.1; 369 -0.0; 395 -0.0; 423 -0.2; 452 -0.3; 484 -0.4; 518 -0.5; 554 -0.1; 593 0.5; 635 0.6; 679 0.6; 726 0.5; 777 0.6; 832 0.3; 890 0.2; 952 0.2; 1019 -0.1; 1090 -0.2; 1167 -0.3; 1248 -0.3; 1336 -0.1; 1429 0.2; 1529 0.5; 1636 0.9; 1751 1.0; 1873 0.8; 2004 0.6; 2145 0.2; 2295 0.6; 2455 0.2; 2627 -0.3; 2811 -0.6; 3008 -0.6; 3219 -0.7; 3444 1.6; 3685 5.0; 3943 6.0; 4219 4.5; 4514 4.0; 4830 5.0; 5168 5.9; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 0.7; 7756 -2.2; 8299 -4.0; 8880 -5.1; 9502 -5.3; 10167 -3.4; 10879 -0.3; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 -0.4
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Innerfidelity%202017/headphoncecom/onear/AudioTechnica%20ATH-AD700/AudioTechnica%20ATH-AD700.png)