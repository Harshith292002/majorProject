# SDR-Based Marine VHF Scanner 🌊📡

**A cost-effective and innovative Software-Defined Radio (SDR)-based solution for real-time monitoring and analysis of maritime communications.**

---

## 📖 Overview
This project involves the **design and development of a Marine VHF Scanner** leveraging **GNU Radio**, **RTL-SDR hardware**, and **AIS-Catcher software**. The scanner monitors VHF communication channels, dynamically detects signals, and tracks vessels in real time using AIS data. It aims to enhance maritime navigation, safety, and communication through an affordable and accessible solution.

Key features:
- **Dynamic Frequency Scanning**: Monitors VHF spectrum (88–108 MHz).
- **Automatic Signal Detection**: Stops scanning upon signal detection using threshold detection.
- **AIS Integration**: Tracks vessel locations and retrieves Automatic Identification System (AIS) details.
- **Real-Time Visualization**: Displays detected frequencies and vessel information.

---

## 🛠️ Key Components
### Hardware
- **RTL-SDR Dongle (Version 3)**: Handles wide frequency reception.
- **Telescopic Dipole Antenna**: Provides robust and portable signal reception.

### Software
- **GNU Radio**: Open-source platform for signal processing.
- **AIS-Catcher**: Decodes AIS signals for vessel tracking.
- **Custom Python Module**: Automates scanning and threshold-based detection.

---

## ⚙️ System Architecture
The system architecture consists of:
1. **Signal Processing**: Utilizing Low Pass Filters, Rational Resamplers, and Wideband FM Receiver blocks in GNU Radio.
2. **AIS Decoding**: Integrating AIS-Catcher for real-time vessel tracking.
3. **Python Module**: Controlling scanning parameters and automating signal detection.

**Block Diagram**:
![Block Diagram](path_to_image_or_diagram)

---

## 🚀 Features & Functionality
- **Real-Time Vessel Tracking**: Tracks vessel movements with AIS data.
- **Distress Signal Detection**: Quickly identifies and alerts authorities in emergencies.
- **Wide Frequency Coverage**: Operates within the VHF band (88–108 MHz).
- **Cost-Effective Design**: Built using affordable RTL-SDR hardware.

---

## 🛳️ Use Cases
- **Maritime Navigation and Safety**: Enhances communication and reduces risks of collision.
- **Search and Rescue Operations**: Identifies distress signals for prompt response.
- **Regulatory Compliance**: Monitors communication for adherence to protocols.

---

## 📊 Results
- Successfully implemented the scanner with **real-time frequency monitoring** and **AIS-based vessel tracking**.
- Demonstrated efficiency in **signal detection** and **data visualization** within the VHF band.

---

## 🔮 Future Enhancements
- **Machine Learning**: Implement signal classification and anomaly detection.
- **Expanded Frequency Coverage**: Include additional radio bands and protocols.
- **Advanced Visualization**: Add spectrum waterfalls and enhanced graphical analysis.

---

## 📝 How to Run
1. Connect the **RTL-SDR dongle** and **antenna** to your system.
2. Clone this repository:
   ```bash
   git clone https://github.com/Harshith292002/marine-vhf-scanner.git
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Launch the GNU Radio flow graph:
   ```bash
   gnuradio-companion vhf_scanner.grc
   ```
5. Run the Python script for AIS decoding:
   ```bash
   python ais_catcher.py
   ```

---

## 📚 References
- [GNU Radio Documentation](https://www.gnuradio.org/)
- [RTL-SDR](https://www.rtl-sdr.com/)
- [AIS-Catcher GitHub](https://github.com/ais-catcher)

---

## 🏆 Acknowledgments
This project was developed as part of the **B.Tech Capstone Project** at SRM Institute of Science and Technology under the guidance of **Dr. T. Deepa**.

---

**License**: MIT  
