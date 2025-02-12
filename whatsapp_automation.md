# Whatsapp Web Selenium Automation Project

## Overview 
This is a project designed to automate the process of sending WhatsApp messages using the WhatsApp web interface. This tool simplifies the task of sending bulk messages by leveraging web automation technologies and providing an easy-to-use graphical interface.

<iframe width="613,5" height="336" src="https://www.youtube.com/embed/3Zou1ojfTqI" title="AutoZap: Automate Your WhatsApp Messaging with Ease" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
<br/><br/>

## Key Features
* **Effortless Message Sending**: It allows users to send messages to multiple contacts without manual intervention, streamlining the communication process.

* **QR Code Authentication**: The tool handles QR code authentication, ensuring a seamless connection between the user's device and the WhatsApp web interface.

* **Error Handling**: Robust error handling mechanisms provide users with clear notifications in case of any issues during the message-sending process.

* **User-Friendly GUI**: The graphical user interface, built using Tkinter, offers a straightforward experience, guiding users through the necessary steps.

## System Design
For detailed insights into the system design, refer to the [System Design Documentation](https://drive.google.com/file/d/17_XRvcto_26EMLW0p-_2sfwJSHYWKTWv/view?usp=sharing "https://drive.google.com/file/d/17_XRvcto_26EMLW0p-_2sfwJSHYWKTWv/view?usp=sharing").

## How It Works
1. **Configuration**: Users can customize settings through a configuration file, defining parameters such as the CSV file with contact details and the location of the message to be sent.
2. **QR Code Authentication**: The program opens the WhatsApp web page, waits for the user to scan the QR code, and handles the authentication process. It stores the WhatsApp web profile locally, reducing the need for repeated scans in future sessions
3. **Message Sending**: The tool utilizes Selenium WebDriver to send messages to specified phone numbers, handling various scenarios such as invalid numbers and button availability.
4. **User Interface:** The graphical user interface provides a seamless experience, with frames guiding users through the process and displaying progress and results.

## Project Screenshots
Frame 1: Start sending messages
 
<img src="images/Frame1.jpg?raw=true"/>
 
Frame 2: Scan new QR code or continue

<img src="images/Frame2.jpg?raw=true"/>

Frame 3: Progress and results

<img src="images/Frame3.jpg?raw=true"/>

## Future Improvements
This is an evolving project, and future improvements may include:
* The app needs a name.
* Enhanced error logging and reporting.
* Support for additional messaging platforms.
* Improved user interface and customization options.
* Integration with cloud services for better scalability.


## Get Started
To get started with the script, download the project from  [GitHub](http://www.github.com/otavio-coding/whatsappweb-automation/ "http://www.github.com/otavio-coding/whatsappweb-automation/") and follow the instructions in the README file.

## Contribution
The app welcomes contributions from the open-source community. If you have ideas for improvements or bug fixes, feel free to submit a pull request on GitHub.

## Contact
For inquiries or feedback, you can contact the project maintainer at [otavio.a.f.97@gmail.com].

*This program is not affiliated with or endorsed by WhatsApp.*
