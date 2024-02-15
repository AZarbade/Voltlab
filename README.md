
# Voltlab - Lab Power Management System

**Description**: Voltlab is a lab power management system powered by ESP32 technology. Its functionality is straightforward: users can access specific lab equipment by scanning a QR code affixed to a smart relay that controls power to that specific machine. Upon scanning the QR code, users gain access to the designated equipment, with all usage data meticulously logged and attributed to the respective user.
**Technical Specifications**: Voltlab operates with multiple ESP32 devices connected to the same WiFi network. These devices are seamlessly integrated into a home assistance system, providing administrators with comprehensive insights into the lab's network and usage details through a dedicated plugin.
#Doing

Detailed plan of action with checkboxes:

1. **Define Requirements**:
   - [ ] Desired functionalities:
        - QR code generation
        - User access control 
        - Data logging
   - [ ] User interface for administrators and users.

2. **Hardware Selection**:
   - [ ] ESP32 microcontrollers, relays, current / voltage sensors.
   - [ ] Purchase necessary hardware components.

3. **Software Development**:
   - **ESP32 Programming**:
     - [ ] Develop firmware for ESP32 to handle QR code generation.
     - [ ] Implement relay control functionality.
     - [ ] Integrate data logging capabilities.
     - [ ] Establish communication protocols for home assistance integration.
   - **Home Assistance Integration**:
     - [ ] Research APIs or protocols for integrating ESP32 with home assistance systems.
     - [ ] Develop a plugin or integration to collect data and provide insights.
     - [ ] Test integration with the ESP32 devices.

4. **Networking Setup**:
   - [ ] Configure WiFi network for ESP32 communication.
   NOTE: not really familiar with networking stuff, will figure out later :p.

5. **User Interface Development**:
  NOTE: Not thinking about this now.
   <!-- - [ ] Design user interface for administrators to view usage data and manage permissions. -->
   <!-- - [ ] Develop a user-friendly interface for users to access equipment via QR code scanning. -->
   <!-- - [ ] Implement functionality for generating billing reports. -->

<!-- 6. **Testing and Iteration**: -->
<!--    - [ ] Conduct thorough testing of the entire system. -->
<!--    - [ ] Identify and address any bugs or issues. -->
<!--    - [ ] Gather feedback from users and administrators for improvements. -->
<!--    - [ ] Iterate on software and hardware as needed. -->
<!---->
<!-- 7. **Deployment**: -->
<!--    - [ ] Install hardware components in designated locations within the lab premises. -->
<!--    - [ ] Configure software settings and perform initial setup. -->
<!--    - [ ] Train users and administrators on system usage and maintenance. -->
<!---->
<!-- 8. **Maintenance and Updates**: -->
<!--    - [ ] Monitor system performance and usage data regularly. -->
<!--    - [ ] Address any technical issues or hardware failures promptly. -->
<!--    - [ ] Implement software updates and improvements based on user feedback and emerging needs. -->


