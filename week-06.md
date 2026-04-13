[<](README.md)

# DevLog 06

> Flash Raspberry Pi OS onto an SD card, SSH into your Pi, and set it up.


## Outcomes 

<!-- 
Using the backslash preserves the list number 
https://stackoverflow.com/a/50916345/441878 
-->


1\. Follow the [Command Line tutorial](https://omundy.github.io/learn-computing/slides/command-line.html). Watch [
Basic Terminal Usage](https://www.youtube.com/watch?v=jDINUSK7rXE). Describe in your own words what each of the following commands will do ✏️ 

```python
cd ~/
mkdir test && cd test
touch hello.py
echo "print(Hello World)" > hello.py
python hello.py
```

Change to home folder
Creates a new folder called test and get into that folder
Writes the text print(Hello World) into hello.py
Runs the hello.py file using Python


2\. Share 3 differences between the Raspberry Pi and Raspberry Pi Pico ✏️

1. Raspberry Pi runs a full Linux OS (Raspberry Pi OS), while the Pico has no OS
2. The Raspberry Pi has WiFi, Bluetooth, Ethernet, HDMI, and USB ports. The Pico has none
3. Different processor


3\. Why shouldn't you power your Raspberry Pi from your computer USB? ✏️
 
A computer USB port only supplies 500mA of current, but the Raspberry Pi needs up to 2.5A (for the RPi3). Insufficient current causes random reboots, crashes, and keyboard problems. You should use a dedicated power adapter.


4\. Of the ways to destroy a Raspberry Pi, which are you most likely to do? How will you keep from doing it? ✏️

Unplugging power instead of using software shutdown. avoid it by always running sudo shutdown -h now before unplugging.


5\. Raspberry Pi OS is based on what Linux distribution? What does that even mean? ✏️

Raspberry Pi OS is based on Debian. It inherits Debian's file structure, package manager (APT), software libraries, and conventions, but is customized and optimized for the Raspberry Pi


6\. What does it mean to "Flash" your SD Card? ✏️

Copying a disk image onto your SD card and making it bootable so the Raspberry Pi knows which files to load when it starts up


7\. What does it mean if you see a red light and a flashing green light on your powered Raspberry Pi? ✏️

Red means power is connected. Green means erorr.


8\. What does a package manager do? ✏️

Automates the installing, upgrading, and configuring of software packages


9\. Describe how you might use Git with a Raspberry Pi? ✏️

Manage your projects and adding code to it.


10\. What are two things your personal computer and a linux OS like Raspberry Pi have in common?

1.  Both use a hierarchical file system
2. Both can run Python







## Other experiments

<!-- 
Share other electronic experiments from this week?
-->

- 



## Questions to bring up in class

<!-- 
Share questions you would like to bring up in class.
-->

- 
