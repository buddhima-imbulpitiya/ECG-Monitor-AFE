# 🩺 Analog Heart ECG Monitor

## ✨ **Overview**
This project involves the design and implementation of a real-time, **3-lead ECG monitor**. The core of the device is an analog front end (AFE) that acquires weak electrical signals from the human heart. The AFE processes these signals, amplifying them and filtering out noise to produce a clear ECG waveform. A microcontroller is used solely for displaying this waveform on an appropriate screen.

## ⚙️ **Specifications**
- **Leads:** 3-lead ECG acquisition.
- **Amplification:** At least one stage of amplification using analog electronics (op-amps, resistors, capcitors etc).
- **Filtering:** Use of first-order active filters to remove unwanted noise.
- **Display:** A microcontroller is used for signal display on a screen (e.g., OLED).
- **Enclosure:** A custom-designed enclosure compatible with market-available ECG electrodes.

## 📁 **Repository Structure**
- `schematics/`: Circuit schematics and diagrams.
- `simulations/`: Circuit simulation files (LTspice, Multisim, etc.).
- `pcb_design/`: PCB layout, Gerber files, and Bill of Materials (BoM).
- `enclosure_design/`: 3D models and manufacturing files for the enclosure.
- `documentation/`: Project reports, datasheets, and other relevant documents.

## 🚀 **Getting Started**
1. **Clone the repository:** `git clone [repository_url]`
2. **Navigate to a specific directory** to work on a task (e.g., `cd schematics`).
3. **Contribute:** Create a new branch, make your changes, commit, and push. Then, submit a pull request for review.
   
## 👥 Team

- [Buddhima Imbulpitiya](https://github.com/buddhima-imbulpitiya)
- [Oshan Imaduwage](https://github.com/oshan-imaduwage)
- [Malinda Illankoon](https://github.com/malindailankoon)
- [Manitha Ayanaja](https://github.com/ManiiAya)
