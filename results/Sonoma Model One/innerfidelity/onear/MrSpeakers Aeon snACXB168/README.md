# MrSpeakers Aeon snACXB168
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-47**.
```
GraphicEQ: 10 -84; 20 3.2; 22 3.1; 23 3.1; 25 3.1; 26 3.1; 28 3.1; 30 3.1; 32 3.0; 35 2.9; 37 2.8; 40 2.7; 42 2.6; 45 2.5; 49 2.2; 52 2.2; 56 2.3; 59 2.6; 64 3.2; 68 3.7; 73 4.0; 78 3.9; 83 3.5; 89 2.8; 95 2.1; 102 1.7; 109 1.6; 117 1.5; 125 1.0; 134 0.6; 143 0.4; 153 0.5; 164 0.4; 175 -0.7; 188 -0.7; 201 -0.8; 215 -1.0; 230 -1.1; 246 -1.3; 263 -1.4; 282 -1.4; 301 -1.4; 323 -1.5; 345 -1.5; 369 -1.4; 395 -1.3; 423 -1.3; 452 -1.1; 484 -1.3; 518 -1.5; 554 -1.6; 593 -1.6; 635 -1.5; 679 -1.2; 726 -0.7; 777 -0.5; 832 -0.5; 890 -0.5; 952 -0.5; 1019 0.3; 1090 0.5; 1167 0.6; 1248 1.0; 1336 1.3; 1429 1.4; 1529 1.5; 1636 1.2; 1751 0.6; 1873 0.4; 2004 1.2; 2145 2.2; 2295 2.8; 2455 3.3; 2627 2.1; 2811 3.4; 3008 4.7; 3219 3.7; 3444 2.4; 3685 2.0; 3943 1.9; 4219 -0.0; 4514 0.8; 4830 2.5; 5168 3.0; 5530 0.2; 5917 -1.6; 6331 -1.8; 6775 -2.4; 7249 -3.9; 7756 -4.6; 8299 -5.0; 8880 -4.9; 9502 -3.6; 10167 -0.9; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 3.2; 22 3.1; 23 3.1; 25 3.1; 26 3.1; 28 3.1; 30 3.1; 32 3.0; 35 2.9; 37 2.8; 40 2.7; 42 2.6; 45 2.5; 49 2.2; 52 2.2; 56 2.3; 59 2.6; 64 3.2; 68 3.7; 73 4.0; 78 3.9; 83 3.5; 89 2.8; 95 2.1; 102 1.7; 109 1.6; 117 1.5; 125 1.0; 134 0.6; 143 0.4; 153 0.5; 164 0.4; 175 -0.7; 188 -0.7; 201 -0.8; 215 -1.0; 230 -1.1; 246 -1.3; 263 -1.4; 282 -1.4; 301 -1.4; 323 -1.5; 345 -1.5; 369 -1.4; 395 -1.3; 423 -1.3; 452 -1.1; 484 -1.3; 518 -1.5; 554 -1.6; 593 -1.6; 635 -1.5; 679 -1.2; 726 -0.7; 777 -0.5; 832 -0.5; 890 -0.5; 952 -0.5; 1019 0.3; 1090 0.5; 1167 0.6; 1248 1.0; 1336 1.3; 1429 1.4; 1529 1.5; 1636 1.2; 1751 0.6; 1873 0.4; 2004 1.2; 2145 2.2; 2295 2.8; 2455 3.3; 2627 2.1; 2811 3.4; 3008 4.7; 3219 3.7; 3444 2.4; 3685 2.0; 3943 1.9; 4219 -0.0; 4514 0.8; 4830 2.5; 5168 3.0; 5530 0.2; 5917 -1.6; 6331 -1.8; 6775 -2.4; 7249 -3.9; 7756 -4.6; 8299 -5.0; 8880 -4.9; 9502 -3.6; 10167 -0.9; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-4.7dB*l, R=-4.7dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Sonoma%20Model%20One/innerfidelity/onear/MrSpeakers%20Aeon%20snACXB168/MrSpeakers%20Aeon%20snACXB168.png)