# Phonon SMB2
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 5.9; 28 5.6; 30 5.2; 32 4.7; 35 4.0; 37 3.5; 40 3.0; 42 2.7; 45 2.2; 49 1.7; 52 1.4; 56 1.1; 59 1.0; 64 1.2; 68 1.5; 73 2.1; 78 2.3; 83 2.2; 89 1.7; 95 1.1; 102 0.3; 109 0.0; 117 -0.3; 125 -0.9; 134 -1.5; 143 -2.0; 153 -2.3; 164 -2.3; 175 -2.2; 188 -2.3; 201 -2.2; 215 -2.3; 230 -2.3; 246 -2.5; 263 -2.6; 282 -2.3; 301 -2.0; 323 -1.7; 345 -1.2; 369 -0.7; 395 -0.2; 423 0.7; 452 1.1; 484 1.4; 518 1.7; 554 2.0; 593 2.4; 635 2.5; 679 2.6; 726 2.5; 777 2.3; 832 1.7; 890 1.0; 952 0.3; 1019 0.0; 1090 0.4; 1167 1.1; 1248 1.8; 1336 1.9; 1429 1.7; 1529 1.2; 1636 0.3; 1751 -0.6; 1873 -0.9; 2004 -0.6; 2145 0.3; 2295 1.5; 2455 3.3; 2627 4.4; 2811 5.6; 3008 6.0; 3219 6.0; 3444 6.0; 3685 5.0; 3943 5.8; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 5.2; 5917 2.9; 6331 3.0; 6775 3.3; 7249 1.3; 7756 0.3; 8299 0.0; 8880 -0.9; 9502 -2.2; 10167 -2.2; 10879 -1.2; 11640 -0.1; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 5.9; 28 5.6; 30 5.2; 32 4.7; 35 4.0; 37 3.5; 40 3.0; 42 2.7; 45 2.2; 49 1.7; 52 1.4; 56 1.1; 59 1.0; 64 1.2; 68 1.5; 73 2.1; 78 2.3; 83 2.2; 89 1.7; 95 1.1; 102 0.3; 109 0.0; 117 -0.3; 125 -0.9; 134 -1.5; 143 -2.0; 153 -2.3; 164 -2.3; 175 -2.2; 188 -2.3; 201 -2.2; 215 -2.3; 230 -2.3; 246 -2.5; 263 -2.6; 282 -2.3; 301 -2.0; 323 -1.7; 345 -1.2; 369 -0.7; 395 -0.2; 423 0.7; 452 1.1; 484 1.4; 518 1.7; 554 2.0; 593 2.4; 635 2.5; 679 2.6; 726 2.5; 777 2.3; 832 1.7; 890 1.0; 952 0.3; 1019 0.0; 1090 0.4; 1167 1.1; 1248 1.8; 1336 1.9; 1429 1.7; 1529 1.2; 1636 0.3; 1751 -0.6; 1873 -0.9; 2004 -0.6; 2145 0.3; 2295 1.5; 2455 3.3; 2627 4.4; 2811 5.6; 3008 6.0; 3219 6.0; 3444 6.0; 3685 5.0; 3943 5.8; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 5.2; 5917 2.9; 6331 3.0; 6775 3.3; 7249 1.3; 7756 0.3; 8299 0.0; 8880 -0.9; 9502 -2.2; 10167 -2.2; 10879 -1.2; 11640 -0.1; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Sonoma%20Model%20One/innerfidelity/onear/Phonon%20SMB2/Phonon%20SMB2.png)