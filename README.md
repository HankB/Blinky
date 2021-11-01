# Blinky

My first PlatformIO ESP8266 example.

Working!

For the benefit of anyone who might be following, 

* Running on Debian Bullseye
* Target is an NodeMcu Lua ESP8266 CH340G connected to my desktop PC via USB.
* I already had VS Code installed (From the MS web site.)
* Had previously installed Arduino toolchain (using `apt install arduino` which pulled in 40 packages.) I don't know if this is needed.
* Installed PlatformIO from the VS Code Extensions menu. (Need to restart VS Code to get it working.)
* Created the PlatformIO project and copied C source from an Arduino sketch to `src/main.cpp`.

* Created this Github repo with README and license files (.gitignore kindly provided by PlatformIO)
* Copied the files from the original PlatformIO project into the Git project directory. (Next time I'll create the git project (on Github or my private Gitea server) and create the project within local clone of the git repo.

Program built and ran with no more effort than clicking the buttons.

I highly recommend following the instructions linked from [Get Started](https://docs.platformio.org/en/latest//integration/ide/pioide.html?utm_source=platformio&utm_medium=piohome) on the PlatformIO page in VS Code.
