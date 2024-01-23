# Solar Powered Automatic College Bell System

## Overview

This project focuses on converting manual college bell systems into automatic ones using renewable energy sources. The Solar Powered Automatic College Bell System is implemented on an Arduino Uno board, integrating solar panels and a 12V battery for power backup during cloudy conditions. The system automates bell ringing based on a preset schedule, eliminating the need for manual intervention.

## Features

- **Renewable Energy:** Utilizes solar panels and a 12V battery for power, promoting sustainability and reducing reliance on traditional power sources.
- **Arduino Uno Control:** The system is controlled and programmed using an Arduino Uno board, allowing for easy customization and flexibility.
- **Real-Time Clock (RTC):** Incorporates an RTC module (DS1307) for accurate timekeeping and scheduling of bell ringing.
- **LCD Display:** Provides a user interface through a 16x2 LCD display to show the current day, time, and details of the ongoing or upcoming class period.
- **Push Buttons:** Allows users to set and adjust the schedule by pressing push buttons for easy configuration.
- **Buzzer/Relay:** Generates audible signals through a buzzer or relay to indicate the beginning and end of each class period or break.

## Working Principle

1. The system uses solar panels to harness solar energy, and a solar charge controller manages the charging of a 12V battery for power storage.
2. An Arduino Uno board controls the entire system, receiving inputs from push buttons to set the schedule and interacting with the RTC for accurate time tracking.
3. A 16x2 LCD display provides a visual interface, showing the current day, time, and details of the ongoing or upcoming class period.
4. The Arduino triggers a buzzer or relay to ring the bell at scheduled intervals, signaling the start and end of each class period or break.

## Usage

1. Connect the solar panels, battery, Arduino Uno, RTC module, LCD display, push buttons, and buzzer/relay following the provided circuit diagram.
2. Upload the Arduino code to the board using the Arduino IDE.
3. Adjust the schedule using the push buttons as needed.
4. The system will automatically ring the bell at the scheduled times, powered by solar energy.

## Results and Discussions

The Solar Powered Automatic College Bell System efficiently automates the bell ringing process, providing an accurate and sustainable solution for educational institutions. The use of renewable energy reduces dependence on conventional power sources, contributing to environmental conservation.

## Applications

- Educational Institutes: Colleges, universities, schools.
- Industries: Automated timekeeping and signaling.

## Advantages

- Efficient use of renewable resources.
- Manpower elimination for bell ringing.
- Stand-alone device with no need for additional hardware.

## Limitations

- Reduced energy production on cloudy days.

## Contributors

- Rahul Mydur (https://github.com/RAHULMYDUR/Solar-powered-Automatic-Bell-System-Embedded)
