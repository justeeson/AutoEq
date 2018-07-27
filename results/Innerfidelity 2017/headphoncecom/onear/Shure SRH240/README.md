# Shure SRH240
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 6.0; 52 6.0; 56 6.0; 59 6.0; 64 6.0; 68 6.0; 73 6.0; 78 6.0; 83 6.0; 89 6.0; 95 6.0; 102 6.0; 109 6.0; 117 6.0; 125 6.0; 134 5.7; 143 5.7; 153 6.0; 164 6.0; 175 6.0; 188 6.0; 201 6.0; 215 5.8; 230 5.4; 246 4.9; 263 4.3; 282 2.8; 301 1.3; 323 0.1; 345 -0.8; 369 -1.4; 395 -2.0; 423 -2.7; 452 -3.5; 484 -4.2; 518 -4.4; 554 -4.0; 593 -3.3; 635 -2.8; 679 -2.6; 726 -2.1; 777 -1.5; 832 -1.0; 890 -0.8; 952 -0.3; 1019 0.0; 1090 0.1; 1167 -0.3; 1248 -0.6; 1336 -1.0; 1429 -1.1; 1529 -1.2; 1636 -1.3; 1751 -1.3; 1873 -1.2; 2004 -1.2; 2145 -1.1; 2295 -1.1; 2455 -1.2; 2627 -1.4; 2811 -1.0; 3008 -0.1; 3219 0.2; 3444 0.3; 3685 1.0; 3943 2.4; 4219 3.6; 4514 4.2; 4830 3.9; 5168 3.8; 5530 4.1; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 -1.2; 8880 -2.4; 9502 -2.0; 10167 -1.5; 10879 -0.3; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 6.0; 52 6.0; 56 6.0; 59 6.0; 64 6.0; 68 6.0; 73 6.0; 78 6.0; 83 6.0; 89 6.0; 95 6.0; 102 6.0; 109 6.0; 117 6.0; 125 6.0; 134 5.7; 143 5.7; 153 6.0; 164 6.0; 175 6.0; 188 6.0; 201 6.0; 215 5.8; 230 5.4; 246 4.9; 263 4.3; 282 2.8; 301 1.3; 323 0.1; 345 -0.8; 369 -1.4; 395 -2.0; 423 -2.7; 452 -3.5; 484 -4.2; 518 -4.4; 554 -4.0; 593 -3.3; 635 -2.8; 679 -2.6; 726 -2.1; 777 -1.5; 832 -1.0; 890 -0.8; 952 -0.3; 1019 0.0; 1090 0.1; 1167 -0.3; 1248 -0.6; 1336 -1.0; 1429 -1.1; 1529 -1.2; 1636 -1.3; 1751 -1.3; 1873 -1.2; 2004 -1.2; 2145 -1.1; 2295 -1.1; 2455 -1.2; 2627 -1.4; 2811 -1.0; 3008 -0.1; 3219 0.2; 3444 0.3; 3685 1.0; 3943 2.4; 4219 3.6; 4514 4.2; 4830 3.9; 5168 3.8; 5530 4.1; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 -1.2; 8880 -2.4; 9502 -2.0; 10167 -1.5; 10879 -0.3; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Innerfidelity%202017/headphoncecom/onear/Shure%20SRH240/Shure%20SRH240.png)