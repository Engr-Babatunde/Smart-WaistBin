****Smart Wastebin****

**📖 Introduction**

The Smart Wastebin is an IoT-enabled system designed to improve sanitation efficiency. It combines automatic lid control with waste-level monitoring and SMS alerts.

The lid opens automatically when a person approaches, making disposal hands-free and hygienic.

An ultrasonic sensor inside the bin continuously monitors the fill level.

When the waste reaches 80% capacity, a GSM module sends an SMS notification to the sanitary office, ensuring timely collection.

This project was originally developed as a National Diploma (ND) final year project.

**🛠️ Components Used**

Arduino Uno / Mega (microcontroller)

Ultrasonic Sensor (HC-SR04) x2

Sensor 1 → detects approaching hand/object (lid control)

Sensor 2 → monitors waste level inside bin

Servo Motor (SG90/MG90S) → for lid opening/closing

GSM Module (SIM800L / SIM900) → sends SMS alerts

Power supply unit (stable 5V, GSM may need separate 2A regulator)

Prototype wastebin enclosure

**⚙️ How It Works**

Automatic Lid

When someone approaches within ~15 cm of the bin, the ultrasonic sensor detects it.

The servo motor opens the lid automatically.

After 5 seconds, the lid closes again.

Waste-Level Monitoring

A second ultrasonic sensor inside the bin measures the fill level.

If the bin reaches 80% full, the Arduino triggers the GSM module.

SMS Alert

The GSM module sends an SMS notification:
