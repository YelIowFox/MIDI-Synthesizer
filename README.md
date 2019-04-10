# MIDI-Synthesizer
Transforming old synthesizer into MIDI device
---
**Version 1.0.0**

At this stage the MIDI device 5 din connector doesn't work therefore the Serial-MIDI bridge can't be done,  the solution for this problem at the moment is a virtual Serial-MIDI bridge. For this I included two simple applications.  One for the virtual MIDI In/Out Port and one for the virtual Serial-MIDI bridge.

---

Included Files:
---
```
MIDI_Keyboard //arduino project folder

hairless-midiserial // virtual Serial-MIDI bridge program

loopMIDISetup.exe // virtual MIDI In/Out Port program executable
```

---

**1. Virtual MIDI In/Out Port setup:**
---

Start the `loopMIDISetup.exe` and follow the steps through the installation. After the installation is finished  open the application and select the setup box. Create new virtual MIDI In/Out Port by clicking the '+' button.

![](images/loopMIDI.PNG)

---
**2. Virtual Serial-MIDI bridge setup:**
---

![](images/Hairless-MIDI_Serial.PNG)

---
