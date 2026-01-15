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
![image alt](https://github.com/Kavyansh-kohar/SMART-DESK-CONSOLE/blob/a3b3513bbc0c09ff0a860b7f0fb3bfcbf17c862d/Screenshot%202026-01-16%20013450.png)

Wiring diagram
![image alt](https://github.com/Kavyansh-kohar/SMART-DESK-CONSOLE/blob/a3b3513bbc0c09ff0a860b7f0fb3bfcbf17c862d/wiring%20diagram.jpeg)

SORRY I DON'T KNOW HOW TO DESING A PCB SO I MADE A HAND DRAWN DIAGRAM


| Component        | Quantity | Price (INR) |
|------------------|----------|-------------|
| PAM 8403         | 1        | ₹161        |
| Step-up Module   | 1        | ₹217        |
| 12V DC Fan       | 1        | ₹132        |
| Heat Sink        | 1        | ₹145        |
| Black Paint      | 1        | ₹185        |
| Super Glue       | 2        | ₹198        |
