# Klipsch Reference ONE
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 -8.3; 22 -8.6; 23 -8.7; 25 -9.0; 26 -9.0; 28 -9.2; 30 -9.2; 32 -9.3; 35 -9.4; 37 -9.4; 40 -9.4; 42 -9.4; 45 -9.3; 49 -9.2; 52 -9.2; 56 -9.1; 59 -9.0; 64 -8.9; 68 -8.8; 73 -8.7; 78 -8.6; 83 -8.4; 89 -8.5; 95 -8.6; 102 -8.5; 109 -8.4; 117 -8.1; 125 -8.0; 134 -8.4; 143 -8.7; 153 -8.8; 164 -8.4; 175 -8.1; 188 -8.0; 201 -7.5; 215 -7.4; 230 -7.4; 246 -7.1; 263 -6.9; 282 -6.5; 301 -5.9; 323 -5.3; 345 -4.5; 369 -3.7; 395 -2.8; 423 -1.7; 452 -0.9; 484 -0.4; 518 -0.0; 554 0.7; 593 1.4; 635 1.8; 679 1.7; 726 1.7; 777 1.9; 832 1.5; 890 1.0; 952 0.4; 1019 -0.2; 1090 -0.9; 1167 -1.0; 1248 -1.4; 1336 -2.4; 1429 -2.9; 1529 -3.7; 1636 -4.3; 1751 -4.9; 1873 -5.1; 2004 -5.1; 2145 -5.0; 2295 -5.0; 2455 -4.7; 2627 -4.5; 2811 -4.5; 3008 -3.8; 3219 -3.2; 3444 -2.1; 3685 -0.0; 3943 3.0; 4219 5.3; 4514 6.0; 4830 6.0; 5168 4.2; 5530 0.7; 5917 -0.2; 6331 2.5; 6775 3.8; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 -0.4; 10879 -1.5; 11640 -0.9; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 -8.3; 22 -8.6; 23 -8.7; 25 -9.0; 26 -9.0; 28 -9.2; 30 -9.2; 32 -9.3; 35 -9.4; 37 -9.4; 40 -9.4; 42 -9.4; 45 -9.3; 49 -9.2; 52 -9.2; 56 -9.1; 59 -9.0; 64 -8.9; 68 -8.8; 73 -8.7; 78 -8.6; 83 -8.4; 89 -8.5; 95 -8.6; 102 -8.5; 109 -8.4; 117 -8.1; 125 -8.0; 134 -8.4; 143 -8.7; 153 -8.8; 164 -8.4; 175 -8.1; 188 -8.0; 201 -7.5; 215 -7.4; 230 -7.4; 246 -7.1; 263 -6.9; 282 -6.5; 301 -5.9; 323 -5.3; 345 -4.5; 369 -3.7; 395 -2.8; 423 -1.7; 452 -0.9; 484 -0.4; 518 -0.0; 554 0.7; 593 1.4; 635 1.8; 679 1.7; 726 1.7; 777 1.9; 832 1.5; 890 1.0; 952 0.4; 1019 -0.2; 1090 -0.9; 1167 -1.0; 1248 -1.4; 1336 -2.4; 1429 -2.9; 1529 -3.7; 1636 -4.3; 1751 -4.9; 1873 -5.1; 2004 -5.1; 2145 -5.0; 2295 -5.0; 2455 -4.7; 2627 -4.5; 2811 -4.5; 3008 -3.8; 3219 -3.2; 3444 -2.1; 3685 -0.0; 3943 3.0; 4219 5.3; 4514 6.0; 4830 6.0; 5168 4.2; 5530 0.7; 5917 -0.2; 6331 2.5; 6775 3.8; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 -0.4; 10879 -1.5; 11640 -0.9; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Innerfidelity%202017/headphoncecom/onear/Klipsch%20Reference%20ONE/Klipsch%20Reference%20ONE.png)