# Reid and Heath Acoustics SA-850
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 5.9; 32 5.6; 35 5.0; 37 4.6; 40 4.1; 42 3.8; 45 3.5; 49 3.1; 52 2.9; 56 2.9; 59 2.9; 64 3.3; 68 3.7; 73 4.2; 78 4.5; 83 4.4; 89 3.8; 95 3.2; 102 2.8; 109 2.4; 117 1.7; 125 0.9; 134 0.2; 143 -0.4; 153 -0.9; 164 -1.1; 175 -1.3; 188 -1.6; 201 -1.9; 215 -2.5; 230 -3.2; 246 -3.6; 263 -3.8; 282 -3.9; 301 -3.7; 323 -3.5; 345 -3.4; 369 -3.6; 395 -4.0; 423 -4.2; 452 -4.2; 484 -4.5; 518 -4.8; 554 -5.0; 593 -4.7; 635 -4.2; 679 -3.5; 726 -2.3; 777 -1.1; 832 -0.3; 890 0.3; 952 0.4; 1019 -0.1; 1090 -0.6; 1167 -0.9; 1248 -0.6; 1336 -0.3; 1429 -1.3; 1529 -1.6; 1636 -1.5; 1751 -1.1; 1873 -0.6; 2004 0.6; 2145 1.7; 2295 3.0; 2455 4.8; 2627 5.9; 2811 6.0; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 6.0; 4219 6.0; 4514 5.9; 4830 0.4; 5168 -2.9; 5530 -4.5; 5917 -5.0; 6331 -4.6; 6775 -3.8; 7249 -3.6; 7756 -2.0; 8299 -0.3; 8880 0.0; 9502 -0.1; 10167 -0.3; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 5.9; 32 5.6; 35 5.0; 37 4.6; 40 4.1; 42 3.8; 45 3.5; 49 3.1; 52 2.9; 56 2.9; 59 2.9; 64 3.3; 68 3.7; 73 4.2; 78 4.5; 83 4.4; 89 3.8; 95 3.2; 102 2.8; 109 2.4; 117 1.7; 125 0.9; 134 0.2; 143 -0.4; 153 -0.9; 164 -1.1; 175 -1.3; 188 -1.6; 201 -1.9; 215 -2.5; 230 -3.2; 246 -3.6; 263 -3.8; 282 -3.9; 301 -3.7; 323 -3.5; 345 -3.4; 369 -3.6; 395 -4.0; 423 -4.2; 452 -4.2; 484 -4.5; 518 -4.8; 554 -5.0; 593 -4.7; 635 -4.2; 679 -3.5; 726 -2.3; 777 -1.1; 832 -0.3; 890 0.3; 952 0.4; 1019 -0.1; 1090 -0.6; 1167 -0.9; 1248 -0.6; 1336 -0.3; 1429 -1.3; 1529 -1.6; 1636 -1.5; 1751 -1.1; 1873 -0.6; 2004 0.6; 2145 1.7; 2295 3.0; 2455 4.8; 2627 5.9; 2811 6.0; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 6.0; 4219 6.0; 4514 5.9; 4830 0.4; 5168 -2.9; 5530 -4.5; 5917 -5.0; 6331 -4.6; 6775 -3.8; 7249 -3.6; 7756 -2.0; 8299 -0.3; 8880 0.0; 9502 -0.1; 10167 -0.3; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Sonoma%20Model%20One/innerfidelity/onear/Reid%20and%20Heath%20Acoustics%20SA-850/Reid%20and%20Heath%20Acoustics%20SA-850.png)