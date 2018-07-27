# Ultrasone HFI-780
### EqualizerAPO GraphicEQ
If you are using [HeSuVi](https://sourceforge.net/projects/hesuvi/), replace contents of HeSuVi's eq file `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` with this line and set global volume for both channels from HeSuVi UI to **-60**.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 6.0; 52 6.0; 56 6.0; 59 6.0; 64 6.0; 68 6.0; 73 6.0; 78 6.0; 83 6.0; 89 6.0; 95 6.0; 102 6.0; 109 6.0; 117 6.0; 125 6.0; 134 5.6; 143 5.4; 153 5.3; 164 5.6; 175 5.8; 188 5.8; 201 5.8; 215 5.5; 230 4.9; 246 3.5; 263 2.6; 282 1.7; 301 0.6; 323 -0.4; 345 -1.0; 369 -1.6; 395 -1.8; 423 -1.5; 452 -1.0; 484 -0.6; 518 -0.4; 554 -0.1; 593 0.3; 635 0.8; 679 1.3; 726 1.6; 777 1.8; 832 1.4; 890 0.8; 952 0.2; 1019 0.1; 1090 0.9; 1167 1.3; 1248 1.8; 1336 1.9; 1429 1.5; 1529 0.8; 1636 -0.2; 1751 -1.1; 1873 -1.9; 2004 -1.0; 2145 1.8; 2295 5.7; 2455 6.0; 2627 5.0; 2811 4.9; 3008 4.7; 3219 3.2; 3444 2.1; 3685 1.7; 3943 2.3; 4219 2.4; 4514 2.0; 4830 1.9; 5168 2.6; 5530 1.9; 5917 5.6; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 -1.3; 9502 -4.1; 10167 -5.7; 10879 -5.8; 11640 -5.1; 12455 -4.3; 13327 -3.3; 14260 -1.7; 15258 -0.1; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```
If you are not using HeSuVi, copy this to the end of EqualizerAPO configuration file `C:\Program Files\EqualizerAPO\config\config.txt`.
```
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 6.0; 52 6.0; 56 6.0; 59 6.0; 64 6.0; 68 6.0; 73 6.0; 78 6.0; 83 6.0; 89 6.0; 95 6.0; 102 6.0; 109 6.0; 117 6.0; 125 6.0; 134 5.6; 143 5.4; 153 5.3; 164 5.6; 175 5.8; 188 5.8; 201 5.8; 215 5.5; 230 4.9; 246 3.5; 263 2.6; 282 1.7; 301 0.6; 323 -0.4; 345 -1.0; 369 -1.6; 395 -1.8; 423 -1.5; 452 -1.0; 484 -0.6; 518 -0.4; 554 -0.1; 593 0.3; 635 0.8; 679 1.3; 726 1.6; 777 1.8; 832 1.4; 890 0.8; 952 0.2; 1019 0.1; 1090 0.9; 1167 1.3; 1248 1.8; 1336 1.9; 1429 1.5; 1529 0.8; 1636 -0.2; 1751 -1.1; 1873 -1.9; 2004 -1.0; 2145 1.8; 2295 5.7; 2455 6.0; 2627 5.0; 2811 4.9; 3008 4.7; 3219 3.2; 3444 2.1; 3685 1.7; 3943 2.3; 4219 2.4; 4514 2.0; 4830 1.9; 5168 2.6; 5530 1.9; 5917 5.6; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 -1.3; 9502 -4.1; 10167 -5.7; 10879 -5.8; 11640 -5.1; 12455 -4.3; 13327 -3.3; 14260 -1.7; 15258 -0.1; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
Copy: L=-6.0dB*l, R=-6.0dB*R
```
EqualizerAPO Peace GUI does not work with GraphicEQ so you have to disable parametric equalization configured by Peace if you are already using it.
![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/Sonoma%20Model%20One/innerfidelity/onear/Ultrasone%20HFI-780/Ultrasone%20HFI-780.png)