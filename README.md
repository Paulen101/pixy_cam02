# Pixy2 Vision Sensor

Pixy2 is an advanced vision sensor designed for robotics applications, capable of detecting lines, intersections, small barcodes, and color-based objects. It offers improved performance, a higher frame rate of 60 frames-per-second, and enhanced tracking algorithms for various controllers. 

## Key Features

- **Line Tracking and Following:**
  - Pixy2 can detect and track lines, making it ideal for line-following robots.
  - Improved algorithms for line detection on light or dark backgrounds.
  - Ability to filter lines based on specified width ranges.

- **Color Connected Components (CCC) Algorithm:**
  - Robust color-based filtering for object detection.
  - Supports up to 7 color signatures, allowing for the identification of multiple unique objects.
  - Detects hundreds of objects simultaneously using connected components algorithms.

- **Teaching Functionality:**
  - Unique ability to teach Pixy2 by physically presenting objects and pressing a button.
  - Learns up to seven color signatures for object recognition.

- **Controller Support:**
  - Compatible with Arduino, Raspberry Pi, BeagleBone, LEGO Mindstorms EV3, and more.
  - Offers support for multiple interfaces: UART, SPI, I2C, USB, analog/digital output.

- **High Frame Rate:**
  - Processes a complete image frame every 1/60th of a second (60 Hz).
  - Enables fast and accurate tracking of moving objects, suitable for dynamic robotic applications.

- **Integrated Light Source:**
  - Equipped with a built-in light source (20 lumens) for consistent performance in varying lighting conditions.
  - Reduces motion blur during line-following tasks.

- **Line Tracking API:**
  - Provides a dedicated API for line tracking functionality.

- **Color Code (CC) Support:**
  - Recognizes and decodes color codes for enhanced object identification.
  - Offers accurate angle estimates for objects with CCs.

## How to Use

1. **Connecting Pixy2:**
   - Utilize UART, SPI, I2C, USB, or analog/digital output to connect Pixy2 to your microcontroller.

2. **Teaching Pixy2:**
   - Hold objects in front of Pixy2, press the button, and let Pixy2 learn the color signatures.

3. **Programming Line Following:**
   - Utilize the line tracking API for line-following robots.
   - Detect intersections, branches, and barcodes to enhance robot navigation.

4. **Using Color Codes:**
   - Employ color codes for precise object identification and angle estimation.

5. **PixyMon Application:**
   - Debug and configure Pixy2 using the PixyMon application on Windows, MacOS, or Linux.

## Technical Specifications

- **Processor:** NXP LPC4330, 204 MHz, dual-core
- **Image Sensor:** Aptina MT9M114, 1296×976 resolution
- **Lens Field-of-View:** 60 degrees horizontal, 40 degrees vertical
- **Power Consumption:** 140 mA typical
- **Power Input:** USB (5V) or unregulated (6V to 10V)
- **RAM:** 264K bytes, **Flash:** 2M bytes
- **Data Outputs:** UART serial, SPI, I2C, USB, digital, analog
- **Dimensions:** 1.5” x 1.65” x 0.6”
- **Weight:** 10 grams

For detailed information, refer to the [Pixy2 Documentation](link-to-documentation).

---

*Pixy2 is a product of the partnership between the Carnegie Mellon Robotics Institute and Charmed Labs. It started as a Kickstarter campaign and has become the most popular vision system in history, funded exclusively through sales.*
