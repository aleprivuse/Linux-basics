# Installing a Virtual Machine Environment

## Goal
Set up a virtual machine environment for learning Linux and networking.

---

## Why I chose VirtualBox
I am using Windows Home, so I decided to use VirtualBox as my virtualization software.

---

## Step-by-Step Guide

### 1. Open Windows Features
Press:

Windows + R

Then type:

appwiz.cpl
Press Enter.

---

### 2. Enable Virtual Machine Platform
On the left side, click:

"Turn Windows features on or off"

Then enable:

"Virtual Machine Platform"

(German: "Plattform für virtuelle Computer")

---

### 3. Restart the Computer
After enabling the feature, restart your PC.

---

### 4. Install VirtualBox

Go to:
https://www.virtualbox.org/

go to your left side under <strong>VirtualBox Platform Packages</strong>  and select your version

Then download and install it.

---

### 4.1 Download Ubuntu (Linux)

Search for:
Ubuntu Linux LTS

Or use this link:
https://ubuntu.com/download/server

Then download it.

---

### 5. Setting up the VM

Open VirtualBox, then click the blue icon (called "New").

Follow the instructions and select your ISO file (the Ubuntu Linux file you downloaded).

---

### 5.1 VM Specifications (Recommended)

Recommended settings:

1. **RAM:** 4 GB minimum (more than 4 GB if you want to open more tabs or use heavy software)

2. **CPU:** At least 1 core (2 cores recommended for better performance)

3. **Storage:** 40 GB minimum (more if you want to install more software)

---

## What I learned

- Windows needs virtualization support enabled
- Virtual machines require system-level features
- VirtualBox is compatible with Windows Home
- You can only use Hyper-V if you have Windows Pro
