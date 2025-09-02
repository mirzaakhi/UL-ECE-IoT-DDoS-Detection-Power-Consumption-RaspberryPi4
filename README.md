# UL-ECE-IoT DDoS Detection Power Consumption Recordings on Raspberry Pi 4

This repository provides the **USB power meter video recordings** and the corresponding **time–power data tables** collected during **DDoS detection experiments** on a Raspberry Pi 4. 
The evaluation was conducted by executing our TCN TFLite model on two datasets:

- *UL-ECE-MQTT-DDoS-H-IoT2025*  
- *UL-ECE-UDP-DDoS-H-IoT2025*  
---

## Repository structure
```
├── MQTT_power_data__time.csv
├── UDP_power_data_time.csv
├── videos/
│ ├── mqtt_power_recording.mp4
│ └── udp_power_recording.mp4
└── README.md
```

- **Root** – CSV files with discrete time–power measurements extracted from the USB power meter recordings.  
- **/videos** – Full video recordings of the USB power meter during inference on each dataset.  

---

## Measurement setup

- **Device:** Raspberry Pi 4 (32-bit Raspberry Pi OS, Debian Bullseye)  
- **Model:** TCN TFLite executed for inference on each dataset  
- **Datasets:**
  - *UL-ECE-MQTT-DDoS-H-IoT2025*  
  - *UL-ECE-UDP-DDoS-H-IoT2025*  

---

## Data dictionary

Each CSV file contains two columns:

- `time (s)` – Elapsed time in seconds aligned with the video timeline  
- `power (w)` – Instantaneous power (Watts) measured from the USB power meter  

---

## License

- **Data and videos:** CC BY 4.0 License (Creative Commons Attribution 4.0)  

This allows reuse with proper citation of the original authors.

---

## Support

If you encounter any issues with the datasets or video recordings, please open an **issue** in this repository.

