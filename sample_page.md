# AutoZap Project

## Overview 
AutoZap is a project designed to automate the process of sending WhatsApp messages using the WhatsApp web interface. This tool simplifies the task of sending bulk messages by leveraging web automation technologies and providing an easy-to-use graphical interface.

## Key Features
* **Effortless Message Sending**: AutoZap allows users to send messages to multiple contacts without manual intervention, streamlining the communication process.

* **QR Code Authentication**: The tool handles QR code authentication, ensuring a seamless connection between the user's device and the WhatsApp web interface.

* **Error Handling**: Robust error handling mechanisms provide users with clear notifications in case of any issues during the message-sending process.

* **User-Friendly GUI**: The graphical user interface, built using Tkinter, offers a straightforward experience, guiding users through the necessary steps.

## System Design
For detailed insights into the AutoZap system design, refer to the System Design Documentation.

## How It Works
1. **Configuration**: Users can customize settings through a configuration file, defining parameters such as the CSV file with contact details and the location of the message to be sent.
2. **QR Code Authentication**: AutoZap opens the WhatsApp web page, waits for the user to scan the QR code, and handles the authentication process. AutoZap stores the WhatsApp web profile locally, reducing the need for repeated scans in future sessions
3. **Message Sending**: The tool utilizes Selenium WebDriver to send messages to specified phone numbers, handling various scenarios such as invalid numbers and button availability.
4. **User Interface:** The graphical user interface provides a seamless experience, with frames guiding users through the process and displaying progress and results.

   
### 2. Assess assumptions on which statistical inference will be based

```javascript
if (isAwesome){
  return true
}
```

### 3. Support the selection of appropriate statistical tools and techniques

<img src="images/dummy_thumbnail.jpg?raw=true"/>

### 4. Provide a basis for further data collection through surveys or experiments

Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo. 

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).
