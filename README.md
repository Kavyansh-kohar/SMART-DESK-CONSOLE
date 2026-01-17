SMART DESK CONSOLE

Description Smart Desk Console is smart desk-side device acting as an AI voice assistant – powered console with certain daily-use functions and characteristics. It's made from reused and recycled e-waste parts, showing that useful smart devices can be built by reusing old hardware rather than buying new devices and contributing more to the electronic waste mountain.

Powered by Google Assistant, this is a 24×7 desk clock, alarm system and Bluetooth speaker with your DIY patent(tweaked) smart home control device which is also named as CCTV camera made from an old smartphone with some electronic components.

The main objective of this project was to recycle some old electronics that were laying around in my house and experiment how much functionality can I get without coding, rooting, or using custom software, but simply by understanding the way the electronics work & utilize built-in system features.
Key Features

* Google Assistant–based voice control

* 24×7 digital clock & alarm

* Bluetooth speaker (stereo output)

* CCTV / monitoring system

* Built completely using reused e-waste

* Designed for 24×7 operation

* Fan & heat management with active cooling

* No code, no root access, and no custom firmware.

Components Used

* Old Android smartphone

* Stereo speakers

* Old phone charging adapter

* Used old Bluetooth neck band (As a Bluetooth audio module)

* PAM8403 stereo amplifier module

* DC CPU cooling fan

* Step-up voltage module

* Capacitors (2200µF, 220µF, 10µF)

* pieces of sheeting (I had some PVC sheets leftover from a recent renovation)

Project Development Process

First, I began by installing Google Assistant on an old phone and checked whether it would work reliably if left to run continuously. Now after it worked out, I did some research on speaker ratings, audio power requirements and amplifier types so I went with the PAM8403 stereo amplifier because of its simplicity and efficiency.

I plugged in an old dual-port phone adapter to power the system: one port for continuous charging of the phone and the other to supply voltage to the amplifier and modules.

Problems Faced
Audio Distortion

Audio was getting distorted due to the excessive length of wire and voltage drops. Solution:

Learned something about capacitors, and signal filtering.

Added:

* 2200µF cap on main power line

* capacitor at input to step-up module 220µF

* Bluetooth module input has a 10µF capacitor

* Pulled VCA ports and soldered sound lines directly to the amp.

With these alterations, the distortion dropped to near zero.
Body & Design

The enclosure is constructed from PVC sheets that remained are left over from home maintenance, providing good airflow for cooling and allowing access to the buttons controlling power and volume on the phone.

During this time, I also discovered:

* Spray painting techniques

* Number of coats required

* Paint types and finishing

I’ve just made the broken Phone screen hidden behind a piece of X-ray sheet, which not only covers up the crack but also allows you to use the phone.

Final Setup

* Added 3 push buttons:

* Left speaker control

* Right speaker control

* Amplifier/Fan/Module Master On/Off Switch

Installed apps:

* Flip Clock with Animated 24 Hour time display

* Alfred Camera for CCTV functionality

Known Limitations & Future Improvements

The Smart Desk Console is a dependable console for every day use, however there are some caveats that we discovered during long term testing. They are not design flaws, but rather aspects to be improved in subsequent iterations of the project.

 1.Display Brightness Limitation

An X-ray sheet diffuser was added to cover the breaks on the reused phone screen. This would cover the physical damage, but it dims the screen as well and even at max brightness makes it look quite dim.

Future Improvement:

Substitute X-ray with better diffuser/tinted film, which conceals the cracks and allows even more light through.

Try some automotive glass tint or display-grade diffuser films for better clarity

2. Microphone Sensitivity in Noisy Environments

The Google Assistant voice commands on the phone work okay when it is quiet.. When it is loud the phones microphone has a hard time hearing the Google Assistant voice commands. This is because the phone is using its built-in microphone for the Google Assistant voice commands.

Future Improvement:

* Integrate an external or higher-sensitivity microphone closer to the user

* Use directional mic placement to improve voice pickup and reduce background noise

The Smart Desk Console shows that you do not need new equipment to be innovative. You can use the devices you already have. This will help reduce waste from old electronics. The Smart Desk Console can still give you good results even when you are using old devices. This is what the Smart Desk Console is, about.

This project really helped me:

* Learn practical electronics and power management

* Understand real-world audio issues and solutions

* Reuse and recycle electronic waste

* Build a fully functional smart device without coding

3D model screenshot

# this 3d model is only for refrence desing of project because phone sizes and other component saze may vary

![image alt](https://github.com/Kavyansh-kohar/SMART-DESK-CONSOLE/blob/458d89f7fb9cb98d3e00b8e0f29b9695d28ad009/3d%20model%20screenshots/full%20structure.png)

FRONT VIEW

![image alt](https://github.com/Kavyansh-kohar/SMART-DESK-CONSOLE/blob/458d89f7fb9cb98d3e00b8e0f29b9695d28ad009/3d%20model%20screenshots/front%20view.png)

BACK VIEW

![image alt](https://github.com/Kavyansh-kohar/SMART-DESK-CONSOLE/blob/458d89f7fb9cb98d3e00b8e0f29b9695d28ad009/3d%20model%20screenshots/back%20view.png)

TOP VIEW

![image alt](https://github.com/Kavyansh-kohar/SMART-DESK-CONSOLE/blob/b132ec5f6bae46bc5c8c7a6f02b6519e9b1897c7/3d%20model%20screenshots/top%20view.png)

SIDE VIEW

![image alt](https://github.com/Kavyansh-kohar/SMART-DESK-CONSOLE/blob/b132ec5f6bae46bc5c8c7a6f02b6519e9b1897c7/3d%20model%20screenshots/side%20view.png)
Wiring diagram
![image alt](https://github.com/Kavyansh-kohar/SMART-DESK-CONSOLE/blob/a3b3513bbc0c09ff0a860b7f0fb3bfcbf17c862d/wiring%20diagram.jpeg)

SORRY I DON'T KNOW HOW TO DESING A PCB SO I MADE A HAND DRAWN DIAGRAM


| Component           | Quantity | Description                                          | Price (₹) | Source                     |
|--------------------|----------|------------------------------------------------------|-----------|----------------------------|
| PAM8403            | 1        | Audio Amplifier Board                                 | 120.00    | Local market               |
| Step-up Module     | 1        | XL6009 DC-DC Adjustable Booster Module                | 180.00    | Amazon (online)            |
| 12V DC Fan         | 1        |  Cooling Fan                                          | 120.00    | Local market               |
| Heat Sink          | 1        | Aluminum Heat Sink                                    | 150.00    | Amazon (online)            |
| Black Paint        | 1        | Black spray/paint                                    | 200.00    | Local store                |
| Super Glue         | 2        | Cyanoacrylate adhesive                                | 150.00    | Local store                |
| PVC Sheets         | 5        | for making body structure                             | 0.00      | Reused material            |
| Smartphone         | 1        | main controling unit                                    | 0.00      | Reused e-waste             |
| Bluetooth Module   | 1        | from old wireless earphones                            | 0.00      | Reused e-waste             |
| Solder Wire        | 1        |  solder wire                                           | 90.00     | Local market               |
| **TOTAL**          |          |                                                      | **$11.12**|                            |
