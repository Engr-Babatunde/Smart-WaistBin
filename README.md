📖 **Introduction**

The Smart Wastebin is an IoT-based system designed to monitor the fill level of a waste container and send an alert to the sanitary office when the bin reaches 80% capacity. This project was originally developed as a National Diploma (ND) final year project.

By automating waste monitoring, this system helps:

Reduce manual inspection efforts

Improve sanitation efficiency

Prevent overflow and maintain cleaner environments

🛠️ **Components Used**

Arduino microcontroller (or ESP8266/ESP32 if used for communication)

Ultrasonic sensor (for level detection)

GSM module (SIM800L or similar) for SMS alert

Power supply unit

Prototype wastebin enclosure

⚙️ **How It Works**

Ultrasonic sensor monitors the waste level inside the bin.

Once the fill level reaches 80%, the system triggers an alert.

The GSM module sends an SMS notification to the designated sanitary office phone number.

The bin can then be emptied promptly to avoid overflow.
