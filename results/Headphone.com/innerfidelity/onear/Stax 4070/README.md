# Stax 4070
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-38**.
```
GraphicEQ: 10 -84; 20 2.6; 22 1.1; 23 0.5; 25 -0.4; 26 -0.7; 28 -1.0; 30 -1.1; 32 -1.0; 35 -0.8; 37 -0.6; 40 -0.3; 42 -0.1; 45 0.2; 49 0.5; 52 0.7; 56 0.9; 59 1.0; 64 1.1; 68 1.1; 73 1.0; 78 0.9; 83 0.8; 89 0.5; 95 0.3; 102 -0.2; 109 -0.4; 117 -0.9; 125 -1.3; 134 -1.5; 143 -1.7; 153 -1.9; 164 -2.0; 175 -2.0; 188 -2.1; 201 -2.2; 215 -2.2; 230 -2.2; 246 -2.3; 263 -2.3; 282 -2.4; 301 -2.4; 323 -2.5; 345 -2.2; 369 -1.3; 395 0.0; 423 0.9; 452 0.9; 484 0.6; 518 0.8; 554 1.1; 593 1.4; 635 1.7; 679 1.6; 726 1.4; 777 1.1; 832 0.7; 890 0.3; 952 0.1; 1019 -0.1; 1090 -0.3; 1167 -0.3; 1248 -0.3; 1336 -0.0; 1429 -0.1; 1529 -0.5; 1636 -0.9; 1751 -1.1; 1873 -1.1; 2004 -0.6; 2145 -0.0; 2295 0.6; 2455 0.9; 2627 0.7; 2811 -0.0; 3008 -1.3; 3219 -1.7; 3444 -2.3; 3685 -3.5; 3943 -4.0; 4219 -3.4; 4514 -1.6; 4830 1.3; 5168 3.5; 5530 3.6; 5917 2.0; 6331 1.4; 6775 3.3; 7249 1.3; 7756 0.3; 8299 0.0; 8880 -0.9; 9502 -0.3; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 2.6; 22 1.1; 23 0.5; 25 -0.4; 26 -0.7; 28 -1.0; 30 -1.1; 32 -1.0; 35 -0.8; 37 -0.6; 40 -0.3; 42 -0.1; 45 0.2; 49 0.5; 52 0.7; 56 0.9; 59 1.0; 64 1.1; 68 1.1; 73 1.0; 78 0.9; 83 0.8; 89 0.5; 95 0.3; 102 -0.2; 109 -0.4; 117 -0.9; 125 -1.3; 134 -1.5; 143 -1.7; 153 -1.9; 164 -2.0; 175 -2.0; 188 -2.1; 201 -2.2; 215 -2.2; 230 -2.2; 246 -2.3; 263 -2.3; 282 -2.4; 301 -2.4; 323 -2.5; 345 -2.2; 369 -1.3; 395 0.0; 423 0.9; 452 0.9; 484 0.6; 518 0.8; 554 1.1; 593 1.4; 635 1.7; 679 1.6; 726 1.4; 777 1.1; 832 0.7; 890 0.3; 952 0.1; 1019 -0.1; 1090 -0.3; 1167 -0.3; 1248 -0.3; 1336 -0.0; 1429 -0.1; 1529 -0.5; 1636 -0.9; 1751 -1.1; 1873 -1.1; 2004 -0.6; 2145 -0.0; 2295 0.6; 2455 0.9; 2627 0.7; 2811 -0.0; 3008 -1.3; 3219 -1.7; 3444 -2.3; 3685 -3.5; 3943 -4.0; 4219 -3.4; 4514 -1.6; 4830 1.3; 5168 3.5; 5530 3.6; 5917 2.0; 6331 1.4; 6775 3.3; 7249 1.3; 7756 0.3; 8299 0.0; 8880 -0.9; 9502 -0.3; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-3.8dB*l, R=-3.8dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Headphone.com/innerfidelity/onear/Stax%204070/Stax%204070.png)