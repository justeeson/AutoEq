# Shure SRH440
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 6.0; 52 6.0; 56 6.0; 59 6.0; 64 6.0; 68 6.0; 73 6.0; 78 6.0; 83 5.6; 89 4.5; 95 3.6; 102 2.8; 109 2.3; 117 2.1; 125 1.6; 134 1.2; 143 1.2; 153 0.8; 164 1.3; 175 1.4; 188 1.3; 201 1.3; 215 1.6; 230 1.7; 246 1.5; 263 1.2; 282 0.9; 301 0.6; 323 0.3; 345 0.1; 369 -0.7; 395 -0.7; 423 -0.4; 452 -0.4; 484 -0.5; 518 -0.6; 554 -0.4; 593 -0.3; 635 -0.4; 679 -0.4; 726 -0.5; 777 -0.2; 832 -0.4; 890 -0.4; 952 -0.2; 1019 0.3; 1090 0.9; 1167 -0.0; 1248 -0.3; 1336 -0.7; 1429 -1.3; 1529 -2.0; 1636 -2.5; 1751 -2.7; 1873 -2.4; 2004 -1.5; 2145 -0.7; 2295 0.4; 2455 1.4; 2627 1.7; 2811 1.9; 3008 2.4; 3219 2.1; 3444 1.4; 3685 1.1; 3943 2.0; 4219 1.1; 4514 0.3; 4830 1.9; 5168 5.6; 5530 2.8; 5917 3.2; 6331 5.4; 6775 3.9; 7249 1.3; 7756 0.3; 8299 -0.9; 8880 -4.0; 9502 -6.3; 10167 -6.5; 10879 -3.4; 11640 -0.1; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 6.0; 52 6.0; 56 6.0; 59 6.0; 64 6.0; 68 6.0; 73 6.0; 78 6.0; 83 5.6; 89 4.5; 95 3.6; 102 2.8; 109 2.3; 117 2.1; 125 1.6; 134 1.2; 143 1.2; 153 0.8; 164 1.3; 175 1.4; 188 1.3; 201 1.3; 215 1.6; 230 1.7; 246 1.5; 263 1.2; 282 0.9; 301 0.6; 323 0.3; 345 0.1; 369 -0.7; 395 -0.7; 423 -0.4; 452 -0.4; 484 -0.5; 518 -0.6; 554 -0.4; 593 -0.3; 635 -0.4; 679 -0.4; 726 -0.5; 777 -0.2; 832 -0.4; 890 -0.4; 952 -0.2; 1019 0.3; 1090 0.9; 1167 -0.0; 1248 -0.3; 1336 -0.7; 1429 -1.3; 1529 -2.0; 1636 -2.5; 1751 -2.7; 1873 -2.4; 2004 -1.5; 2145 -0.7; 2295 0.4; 2455 1.4; 2627 1.7; 2811 1.9; 3008 2.4; 3219 2.1; 3444 1.4; 3685 1.1; 3943 2.0; 4219 1.1; 4514 0.3; 4830 1.9; 5168 5.6; 5530 2.8; 5917 3.2; 6331 5.4; 6775 3.9; 7249 1.3; 7756 0.3; 8299 -0.9; 8880 -4.0; 9502 -6.3; 10167 -6.5; 10879 -3.4; 11640 -0.1; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/SBAF-Serious/headphoncecom/onear/Shure%20SRH440/Shure%20SRH440.png)