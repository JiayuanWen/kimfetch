
<h1 align="center">Kimfetch</h1>
<p align="center">Hardcoded fetch script for Red Star OS 2.0 &amp; 3.0.</p>
<p align="center">
    <img width="1080" src="https://github.com/JiayuanWen/kimfetch/blob/main/screenshots/screenshot1.png" alt="kimfetch screenshot 1">
</p>

Normal neofetch or screenfetch script won't execute on Red Star OS due to multiple essencial commands and parameters, as well as the ability to define functions in scripts being removed from the distro. It is also not possible to install neofetch or screenfetch to begin with due to the lack of any conventional package manager pre-installed in the distro. I wrote my own fetch script to work around these limitations. 

## Install
Installation instructions can be found in the [[Wiki](https://github.com/JiayuanWen/kimfetch/wiki)].

## Dev
Clone this repository to edit the kimfetch script. To pack the script into an iso, copy it to an dedicated folder outside of the repo, then find a program that can turn that folder into an iso file, similar to how you can compress folders to archives. In my case, I use ImgBurn on Windows 10 to do the job.  
#### Warnings for devs:
* Since Red Star OS removed the ability to implement functions in custom scripts, please avoid using functions when modifying the script.
* Red Star OS is developed by the DPRK, it is highly adviced not to install the system on your machine due to privacy risk and for personal safity. If you must use the OS, please install in a virtual environment with no access to internet granted. 
