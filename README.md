# Broadcast Bully

This was written in Python 3.7.5.
Pydoc was used to generate readable documentation.

## How to Run on CORE

This program will make the most sense if run on the [CORE network emulator](https://coreemu.github.io/core/) or on different computers that are on the same broadcast network. If you run it only on your own computer, you could only run it on one node as it will have only one IP address. 

## Installation
If you don't have CORE installed, please follow the installation steps:
[Install CORE](https://coreemu.github.io/core/install.html)

## Run on CORE

To run on CORE, first use the command in your terminal:

>`sudo core-daemon`

Then use the command to run the Python GUI:
>`sudo core-pygui`


More information on core-pygui (Python GUI) can be found here: [Python GUI](https://coreemu.github.io/core/pygui.html#overview)


After CORE is started, you will need to build your network before running the program: 

1. Click on the **CORE Nodes** icon from the left toolbar

![toolbar](https://github.com/binaery-a/broadcast_bully/blob/f9d3e2b445eb581ba26e76d14d7f3049065fbd57/toolbar.png)

2. Then, insert the desired number of **PC's** (pictured below) from the tab on the left.

![PC](https://coreemu.github.io/core/static/pygui/pc.png)

3. Click on the **Network Nodes** icon from the tab on the left.

4. Add a single hub (pictured below).

![hub](https://coreemu.github.io/core/static/pygui/hub.png)

5. Link all the PC's to the hub using the **Link** tool on the left (pictured below).

![Link](https://coreemu.github.io/core/static/pygui/link.png)

An example structure is pictured below.

![structure](https://github.com/binaery-a/broadcast_bully/blob/7e986e7765eb6a19ecbfbaf8bdad8ac50e7f0943/network%20strucuture.png)

6. Once linked, press the **Start Button** on the left.
7. Double click on each PC to open its terminal window. 
8. Run the program with the command on each node:
```python3 broadcast_bully.py 'integer'``` where `'integer'` represents the node's timeout period. So if you write `20`, the node will terminate after 20 seconds. Ideally, you would want to run each node with different timeout periods to test election coordination.

## Demo Video

Here is a [demo video](https://www.dropbox.com/sh/hq5ketykplzrdfq/AAC7BKlQy6MRC36TutnP1RnKa?dl=0&preview=cast.mp4) showing the distributed program in action. 

Note that in the demo, the code is run using an alias to save time.

## Poster

![poster presentation](https://github.com/ANRGUSC/Broadcast_Bully/blob/eef3faffa39350f4c08a1b855dd4351b79166b1e/Broadcast%20Bully%20Poster.png)

 



























|Contact Name    |Contact email  |
|----------------|----------------|
|Angelica Escobar|escobara@usc.edu|
