# OutRun  
  
Remake developed in C++ from scratch using the SFML library.  
  
### How to install
Download from https://github.com/agavinm/OutRun/releases  
  
**Windows version**: [OutRun Windows x64](https://github.com/agavinm/OutRun/releases/download/v1.0/outrun-1.0-W64.zip)
<pre><code>**1.** Extract all files from outrun-1.0-W64.zip
**2.** Run Outrun.exe
</code></pre>
**Debian based version**: [OutRun Debian amd64](https://github.com/agavinm/OutRun/releases/download/v1.0/outrun-1.0-amd64.deb)
<pre><code>**$~** sudo apt install ./outrun-1.0-amd64.deb
**$~** outrun
</code></pre>
  
### Gameplay
[![Watch the video](https://img.youtube.com/vi/C8RGWKqoxEc/hqdefault.jpg)](https://www.youtube.com/watch?v=C8RGWKqoxEc)  
https://www.youtube.com/watch?v=C8RGWKqoxEc  
  
### Controls
In the main menu, select with ENTER and move with the ARROWS.  
  
In-game controls are those set in control options. By default the controls are:  
* Accelerate: Ctrl Left  
* Brake: Alt Left  
* Rotate: Arrows  
* Pause: Esc  
  
### Options
**Difficulty:** (ARROWS)  
* Peaceful: No enemy vehicles and time to spare.  
* Easy: With 5 simultaneous enemy vehicles and with enough time.  
* Normal: With 10 simultaneous enemy vehicles and with a set time.  
* Hard: With 15 simultaneous enemy vehicles and with a very tight time.  
  
**Enemies AI:** (ARROWS)  
 Enable or disable the AI ​​of the enemies, whose difficulty will depend on the difficulty of the game.  
* Sound menu: (C to enter and ENTER to confirm)  
* Music volume (ARROWS).  
* Volume of the effects (ARROWS).  
  
**Graphics menu:** (C to enter and ENTER to confirm)  
* Screen resolution (ARROWS).  
* Pixel art (ARROWS). If disabled at very high resolutions, you need a fairly powerful CPU.  
    
**Controls menu:** (C to enter and ENTER to confirm)  
 To change the control highlighted in yellow, you must keep SPACE and without releasing it, press the desired key, then release space to confirm.  
  
### How to remove
**Windows version** (OutRun Windows x64):
<pre><code>Delete all extracted files
</code></pre>
**Debian based version** (OutRun Debian amd64):
<pre><code>**$~** sudo apt remove outrun
</code></pre>  
  
### How to compile
**Windows version**:
<pre><code>**1.** Download SFML: https://www.sfml-dev.org/files/SFML-2.5.1-windows-gcc-7.3.0-mingw-64-bit.zip
**2.** Download MinGW-W64 GCC-7.3.0: https://sourceforge.net/projects/mingw-w64/files/mingw-w64/mingw-w64-release/
**3.** Copy all .hpp and .cpp files to src/ folder
**$~** g++ -I\<SFMLinclude> -O3 -std=c++14 -mwindows -static -L\<SFMLlib> -o Outrun.exe src/* -lsfml-system -lsfml-window -lsfml-graphics -lsfml-audio
</code></pre>
**Debian based version**:
<pre><code>**1.** Copy all .hpp and .cpp files to src/ folder
**$~** sudo apt install libsfml-dev
**$~** g++ -O3 -std=c++14 src/* -o OutRun -lsfml-graphics -lsfml-audio -lsfml-window -lsfml-system
</code></pre>  
  
### Documentation
[Report](https://github.com/agavinm/OutRun/blob/master/doc/Informe.pdf) (in Spanish)
  
### Game images
![1](https://user-images.githubusercontent.com/37375662/83307715-a1203480-a205-11ea-9fc7-a1c30307a542.jpeg)
![2](https://user-images.githubusercontent.com/37375662/83307720-a1b8cb00-a205-11ea-9adb-58e7302b70d8.jpeg)
![3](https://user-images.githubusercontent.com/37375662/83307723-a2516180-a205-11ea-8697-027be4912447.jpeg)
![4](https://user-images.githubusercontent.com/37375662/83307724-a2516180-a205-11ea-95d1-e3e8315b03e8.jpeg)
![5](https://user-images.githubusercontent.com/37375662/83307725-a2e9f800-a205-11ea-9644-305d283fcc6a.jpeg)
![6](https://user-images.githubusercontent.com/37375662/83307727-a2e9f800-a205-11ea-8f7b-8252082f395c.jpeg)
![7](https://user-images.githubusercontent.com/37375662/83307728-a3828e80-a205-11ea-9990-2dc063a153c8.jpeg)
![8](https://user-images.githubusercontent.com/37375662/83307730-a3828e80-a205-11ea-95a1-edb1313abe11.jpeg)
![9](https://user-images.githubusercontent.com/37375662/83307734-a41b2500-a205-11ea-8a19-ec47d84c3cc1.jpeg)
![10](https://user-images.githubusercontent.com/37375662/83307735-a41b2500-a205-11ea-8f69-6dd03be5dd00.jpeg)
![11](https://user-images.githubusercontent.com/37375662/83307737-a41b2500-a205-11ea-9bcc-a1171b6d7a27.jpeg)
![12](https://user-images.githubusercontent.com/37375662/83307739-a4b3bb80-a205-11ea-96bb-bf8223d20d42.jpeg)
![13](https://user-images.githubusercontent.com/37375662/83307740-a4b3bb80-a205-11ea-885b-02d400b3d8e7.jpeg)
![14](https://user-images.githubusercontent.com/37375662/83307742-a54c5200-a205-11ea-85d4-1be52be0c8c5.jpeg)
![15](https://user-images.githubusercontent.com/37375662/83307744-a54c5200-a205-11ea-8d19-a018d90020a4.jpeg)
![16](https://user-images.githubusercontent.com/37375662/83307745-a5e4e880-a205-11ea-9b31-b21433530d0b.jpeg)
![17](https://user-images.githubusercontent.com/37375662/83307747-a5e4e880-a205-11ea-9fcf-521de82f52be.jpeg)
![18](https://user-images.githubusercontent.com/37375662/83307750-a67d7f00-a205-11ea-88e3-aa5d31887d05.jpeg)
![19](https://user-images.githubusercontent.com/37375662/83307752-a67d7f00-a205-11ea-8615-04b3ea1120d2.jpeg)
![20](https://user-images.githubusercontent.com/37375662/83307753-a7161580-a205-11ea-806e-35ec63ddde56.jpeg)
![21](https://user-images.githubusercontent.com/37375662/83307754-a7161580-a205-11ea-9d6e-d8a50189ae52.jpeg)
![22](https://user-images.githubusercontent.com/37375662/83307756-a7aeac00-a205-11ea-9a00-c39b774d0102.jpeg)
![23](https://user-images.githubusercontent.com/37375662/83307757-a7aeac00-a205-11ea-8bae-a4521fbd71de.jpeg)
  
### Authors
* [Andrés Gavín](https://github.com/agavinm)
* [Rubén Rodríguez](https://github.com/ZgzInfinity)