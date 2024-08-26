\

# Lab 1: Introduction to Raspberry Pi (Part 1)

**GUIDE:** Go through the Lab files from PPT first, then follow through the read me files starting with "Memory Swapping"->"Example for MasterPi_PC Software"

## Contents
- Raspberry Pi OS: [Installation using Imager](https://1sfu-my.sharepoint.com/:v:/g/personal/mnariman_sfu_ca/EctjCUgi0TNBnjfljyBOzlIBlQFRnIUxZRQWd5di8wQJpQ?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=wlEJSO)
- Raspberry Pi Setup: [Wifi-hotspot](https://1sfu-my.sharepoint.com/:v:/g/personal/mnariman_sfu_ca/ETjXQJLWK7ZFph6CpkjX0O8Bb6LBijeFyOjoxx6raX7Wqg?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=mjI107),
- Remote Desktop Connection: [ssh using VNC and Smartty](https://1sfu-my.sharepoint.com/:v:/g/personal/mnariman_sfu_ca/EWjp16yWOzBJtykEqafDoiUBe8ml6vaUaFsHeEQw683xIg?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=44aw7J), [ssh using VScode](https://1sfu-my.sharepoint.com/:v:/g/personal/mnariman_sfu_ca/EVNvlAtQ2h1Ktzt_zGm9MGcBjrVhZLAdORSbY-kf6bj68w?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=vUw4w4)
- File Transfer: [Watch tutorial](https://1sfu-my.sharepoint.com/:v:/g/personal/mnariman_sfu_ca/ESfGQ3MnePpKiL16B70OFYQB8BDpufgs5jwaqA16z_fqng?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=0EZOhR)
- Basic Linux Commands

### Lab Files:
- **Lab Presentation:** [View PPT](https://1sfu-my.sharepoint.com/:p:/g/personal/mnariman_sfu_ca/ER7Ka5JNgEJEoHxdtXBOtIEBoXrseEaAk7MyCYmsVwL05w?e=tSZa9A)

### Additional Resources:
- **Lab Files:** [Download Files](https://1sfu-my.sharepoint.com/:f:/g/personal/mhakizim_sfu_ca/EsqILDf2CF9Nkj5EvpWbk68BhWfN5ra50C7CpnQFA_7zrA?e=DYATYx)
- **Linux Commands Cheatsheet 1:** [Access Cheatsheet](https://1sfu-my.sharepoint.com/:b:/g/personal/mnariman_sfu_ca/ERHFC5jv901FlEH2YozQtLABVmCSBqaPGf5LsoQ_Rcm5sQ?e=8Cor6a)
- **Linux Commands Cheatsheet 2:** [Access Cheatsheet](https://oit.ua.edu/wp-content/uploads/2020/12/Linux_bash_cheat_sheet-1.pdf)

---

## Memory Swapping

After setting up the OS, please follow these instructions on memory swapping:

- **Memory Swapping Instructions:** [View Instructions](https://1sfu-my.sharepoint.com/:w:/g/personal/mnariman_sfu_ca/EUos1qf73eBGkV8BOaB4mlIBtdVHH4ZglPt9n-vcetGK6A?e=pnFyUm)
- **Memory Swapping Video:** [Watch Video](https://1sfu-my.sharepoint.com/:v:/g/personal/mnariman_sfu_ca/ESH11031VfNHs_g-TYmImi0BKvxZxWVKrCWHgdwZ9jf4Cw?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=QqoB9x)

---

## MSE112 Workspace Setup

Clone the public repository (excludes solutions for Projects):

```bash
cd /home/pi && git clone https://github.com/hmarthens1/RPi5-ws.git
```

Navigate to the cloned repository:

```bash
cd ~/RPi5-ws
```

Follow the package installation procedures below:

---

## Required Packages

Install the following packages:

1. **PyYAML** (YAML handler)
   ```bash
   sudo pip install pyyaml

---

## Example from MasterPi

After installing the required packages, test an example:

Navigate to the directory:

```bash
cd /home/pi/RPi5-ws/MasterPi/board_demo

```

Run the example for Servo control:

```bash
sudo python control_by_servo.py
```

If the servos move, the setup is successful.

---
<!--
### Before OpenCV Installation: Follow Instructions for Gstreamer

- **Gstreamer Setup:** [View Instructions](https://1sfu-my.sharepoint.com/:w:/g/personal/mnariman_sfu_ca/EX1mgtM3SRdLh1aE_tTZubQBF2nU7zVNEx3l3PxnkfOUQA?e=8RW3Nw)
-->
## Overclocking

- **Video Demo:** [Watch Demo](https://1sfu-my.sharepoint.com/:v:/g/personal/mnariman_sfu_ca/EXVSrKCz_8lFioCxkZRBGs8BvZU0JVhMVvBFuD1F56JryQ?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=C65Pw5)
- **References:** [Read More](https://qengineering.eu/overclocking-the-raspberry-pi-4.html)

## OpenCV Installation Using Script

**Note:** Do not install OpenCV using pip; follow the instructions to install from source. This will prevent issues with future machine learning packages in the course.
  
If OpenCV is not installed, carefully follow the instructions [here](https://1sfu-my.sharepoint.com/:w:/g/personal/mnariman_sfu_ca/ESDZQjP6HpBGr9JAoZ9tghAB2_iqPQz7TrmJdBu3EzBYCw?e=CTIEz1).

**Installation Time:** Approx. 1.5 hours. After installation, you can retry the previous example.

---

## MasterPi_PC Software

Install the required software:

```bash
sudo apt-get install python3-pyqt5.qtsql
```

### Example for MasterPi_PC Software

Navigate to the directory:

```bash
cd ~/workspacename/MasterPi_PC_Software
```

Run the following command:

```bash
python Arm.py
```

---
