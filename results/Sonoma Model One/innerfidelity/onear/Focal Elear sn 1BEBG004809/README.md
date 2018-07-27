# Focal Elear sn 1BEBG004809
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 5.9; 26 5.9; 28 5.7; 30 5.5; 32 5.4; 35 5.1; 37 5.0; 40 4.8; 42 4.6; 45 4.4; 49 3.9; 52 3.6; 56 3.3; 59 3.2; 64 3.3; 68 3.6; 73 3.9; 78 4.0; 83 3.8; 89 3.1; 95 2.2; 102 1.4; 109 0.9; 117 0.4; 125 -0.3; 134 -0.9; 143 -1.2; 153 -1.5; 164 -1.7; 175 -1.7; 188 -1.8; 201 -1.8; 215 -1.8; 230 -1.8; 246 -1.7; 263 -1.7; 282 -1.5; 301 -1.4; 323 -1.3; 345 -1.1; 369 -1.1; 395 -1.0; 423 -0.8; 452 -0.5; 484 -0.4; 518 -0.3; 554 -0.2; 593 0.1; 635 0.6; 679 1.0; 726 1.4; 777 1.6; 832 1.3; 890 0.8; 952 0.3; 1019 0.0; 1090 0.2; 1167 0.7; 1248 1.3; 1336 1.7; 1429 1.8; 1529 1.4; 1636 0.4; 1751 -0.5; 1873 -1.0; 2004 -1.3; 2145 -1.2; 2295 -0.9; 2455 -0.9; 2627 -0.5; 2811 0.3; 3008 1.1; 3219 1.7; 3444 2.0; 3685 2.1; 3943 4.5; 4219 5.7; 4514 5.5; 4830 6.0; 5168 6.0; 5530 5.9; 5917 4.3; 6331 4.7; 6775 3.9; 7249 1.3; 7756 -0.6; 8299 -3.0; 8880 -3.6; 9502 -3.0; 10167 -1.9; 10879 -0.6; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 -0.2; 17469 -2.7; 18692 -3.5; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 5.9; 26 5.9; 28 5.7; 30 5.5; 32 5.4; 35 5.1; 37 5.0; 40 4.8; 42 4.6; 45 4.4; 49 3.9; 52 3.6; 56 3.3; 59 3.2; 64 3.3; 68 3.6; 73 3.9; 78 4.0; 83 3.8; 89 3.1; 95 2.2; 102 1.4; 109 0.9; 117 0.4; 125 -0.3; 134 -0.9; 143 -1.2; 153 -1.5; 164 -1.7; 175 -1.7; 188 -1.8; 201 -1.8; 215 -1.8; 230 -1.8; 246 -1.7; 263 -1.7; 282 -1.5; 301 -1.4; 323 -1.3; 345 -1.1; 369 -1.1; 395 -1.0; 423 -0.8; 452 -0.5; 484 -0.4; 518 -0.3; 554 -0.2; 593 0.1; 635 0.6; 679 1.0; 726 1.4; 777 1.6; 832 1.3; 890 0.8; 952 0.3; 1019 0.0; 1090 0.2; 1167 0.7; 1248 1.3; 1336 1.7; 1429 1.8; 1529 1.4; 1636 0.4; 1751 -0.5; 1873 -1.0; 2004 -1.3; 2145 -1.2; 2295 -0.9; 2455 -0.9; 2627 -0.5; 2811 0.3; 3008 1.1; 3219 1.7; 3444 2.0; 3685 2.1; 3943 4.5; 4219 5.7; 4514 5.5; 4830 6.0; 5168 6.0; 5530 5.9; 5917 4.3; 6331 4.7; 6775 3.9; 7249 1.3; 7756 -0.6; 8299 -3.0; 8880 -3.6; 9502 -3.0; 10167 -1.9; 10879 -0.6; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 -0.2; 17469 -2.7; 18692 -3.5; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Sonoma%20Model%20One/innerfidelity/onear/Focal%20Elear%20sn%201BEBG004809/Focal%20Elear%20sn%201BEBG004809.png)