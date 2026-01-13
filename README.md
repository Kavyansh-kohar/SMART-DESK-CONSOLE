SMART DESK CONSOLE

Smart Desk Console is a basic desk-type smart device that works as a voice assistant–powered console with multiple daily-use features. It is designed using reused and recycled e-waste components, proving that useful smart devices can be built without buying new hardware or generating more electronic waste.

This project is powered by Google Assistant and functions as a 24×7 desk clock, alarm system, Bluetooth speaker, and CCTV camera — all built using an old smartphone and basic electronic modules.

The main goal of this project was to reuse unused electronics from my home and explore how much functionality can be achieved without coding, rooting, or custom software, only by understanding electronics and using built-in system features.

Key Features

* 🎙️ Google Assistant–based voice control

* ⏰ 24×7 digital clock & alarm

* 🔊 Bluetooth speaker (stereo output)

* 📷 CCTV / monitoring system

* ♻️ Built completely using reused e-waste

* 🔌 Designed for 24×7 operation

* ❄️ Active cooling with fan & heat management

* 🛠️ No coding, no rooting, no custom firmware


Components Used

* Old Android smartphone

* Stereo speakers

* Old phone charging adapters

* Old Bluetooth neckband (used as Bluetooth audio module)

* PAM8403 stereo amplifier module

* DC CPU cooling fan

* Step-up voltage module

* Capacitors (2200µF, 220µF, 10µF)

* PVC sheet pieces (leftover from home renovation)



Project Development Process

I started by setting up Google Assistant on an old phone and testing its reliability for continuous operation. Once it worked properly, I began studying speaker ratings, audio power requirements, and amplifier options, and finally selected the PAM8403 stereo amplifier due to its simplicity and efficiency.

Initially, I planned to connect the phone directly using AUX input, but later I decided to reuse an old Bluetooth neckband module so the system could also work as a Bluetooth speaker with any external device.

To power the system, I used an old dual-port phone adapter — one port dedicated to charging the phone continuously, and the other powering the amplifier and modules.

Problems Faced & Solutions
🔥 Heating Issue

The amplifier module started heating during long usage.
Solution:

* Added a heatsink

* Installed a DC CPU cooling fan

* Used a step-up module to boost voltage from 5V to 12V for the fan


🔊 Audio Distortion

Audio distortion occurred due to long wires and voltage drops.
Solution:

Learned about capacitors and signal filtering

Added:

* 2200µF capacitor on main power line

* 220µF capacitor on step-up module input

* 10µF capacitor on Bluetooth module input

* Removed VCA ports and soldered audio lines directly to the amplifier

* After these changes, distortion became negligible.


Body & Design

* The enclosure was built using PVC sheet pieces left after home renovation, ensuring proper airflow for cooling while allowing access to the phone’s power and volume buttons.

During this phase, I also learned:

* Spray painting techniques

* Number of coats required

 *Paint types and finishing


To hide the cracked phone screen, I used a cut X-ray sheet, which masked the damage while keeping the display functional.


Final Setup

All components were mounted securely inside the enclosure

Added 3 push buttons:

Left speaker control

Right speaker control

Master switch for amplifier, fan, and modules

Installed apps:

Flip Clock for 24×7 time display

Alfred Camera for CCTV functionality

Known Limitations & Future Improvements

While the Smart Desk Console works reliably for daily use, there are a few limitations that were identified during long-term testing. These are not design failures, but areas for improvement in future iterations of the project.

1️⃣ Display Brightness Limitation

To hide cracks on the reused phone display, an X-ray sheet was used as a diffuser. While this successfully hides physical damage, it also reduces screen brightness, making the display appear slightly dull even at maximum brightness.

Future Improvement:

Replace the X-ray sheet with a better-quality diffusion or tinted film that hides cracks while allowing more light to pass through

Explore automotive glass tint or display-grade diffuser films for improved clarity

2️⃣ Microphone Sensitivity in Noisy Environments

The system currently relies on the phone’s built-in microphone for Google Assistant voice commands. In quiet environments, voice detection works well, but in noisy surroundings, the microphone struggles to pick up commands clearly.

Future Improvement:

Integrate an external or higher-sensitivity microphone closer to the user

Use directional mic placement to improve voice pickup and reduce background noise

The Smart Desk Console proves that innovation does not always require new hardware — reusing existing devices can reduce e-waste and still deliver powerful results.



Conclusion

* This project helped me:

* Learn practical electronics and power management

* Understand real-world audio issues and solutions

* Reuse and recycle electronic waste

* Build a fully functional smart device without coding
