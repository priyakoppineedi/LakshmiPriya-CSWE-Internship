🚁 Drone Telemetry System
📌 Project Overview
This project is a simulated Drone Telemetry Dashboard developed as part of the CSWE Software Internship task.
The system visually represents real-time drone telemetry data including flight parameters, system health metrics, and mission status. The dashboard updates dynamically every second for 30 seconds to simulate live drone operation.

🎯 Objective
- To design and implement a telemetry window that displays
- Altitude
- Speed
- Battery Percentage
- GPS Coordinates
- Additional system-level telemetry features have been integrated to simulate a professional ground control interface.

🖥️ Dashboard Architecture

The dashboard is divided into three primary panels.
Left Panel – Mission Overview
- Battery percentage with visual progress bar
- Flight status indicator
- Mission timer
- Distance travelled
- GPS coordinates

Center Panel – Visualization and System Metrics
- Real-time Altitude line chart
- Real-time Speed line chart
- System health indicators
- Signal strength
- Motor temperature
- Heading direction
- Satellite count
- CPU load
- Scrollable live flight log

Right Panel – Instrument Gauges
- Semi-circular Altitude gauge
- Semi-circular Speed gauge

⚙️ Features
- Real-time telemetry updates every 1 second
- 30-second mission simulation lifecycle
- Dynamic battery drain simulation
- GPS coordinate drift simulation
- Distance accumulation logic
- Conditional system warnings
- Mission state transitions
- Initializing
- Taking Off
- Cruising
- Returning Home
- Mission Completed
- Live system logging

🛠️ Technologies Used
- HTML5
- CSS3 using Grid and Flexbox layout
- JavaScript ES6
- Chart.js for data visualization\

📸 Output
- The system generates a professional telemetry dashboard with
- Dynamic charts
- Real-time instrument gauges
- Mission lifecycle tracking
- System health monitoring
- Flight log display
