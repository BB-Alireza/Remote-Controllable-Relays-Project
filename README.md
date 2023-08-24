# Remote-Controllable-Relays-Project

Building an Array of Remote Controllable Switches

In 2014, during the second year of high school, Alavi High School Research Center challenged students to apply the knowledge they had acquired by addressing a real-world problem or need.

The project of remotely controlled relays using sms was aimed at meeting the needs of farmers who needed non-attendance as well as scheduled irrigation of their agricultural lands. Due to the inappropriateness of internet coverage in most places related to agricultural land at that time, it was decided to implement this project using sms. In this device, a timer called Shiva Amwaj is also used as backup. This device consists of 6 relays and a special 12V port for the solenoid valve. In the following, tips for using this device are mentioned.

Tips for using the GSM board are as follows:

- The SIM card used for the board should not have a PIN.

- At the beginning of turning on the board, you should wait for about 15 seconds for the red LED to flash with shorter intervals. This means that the SIM card is connected to the network by the GSM board. In this mode, the green LED turns off and on twice, and then the GSM board is ready to work.

- In order to save the SIM card number, the following command code is used:

    *MKE09xxxxxxxxx*

- The command code for commanding the relays is as follows, if x is one, it means it is on, and if x is zero, it means that the corresponding relay is off.

    *MKExxxxxx*

- When a message is received by the system, the green LED will flash once.


![My Remote Image](https://www.dropbox.com/scl/fi/67f7kk85pme1cgy7x72bk/Relays-One.JPG?rlkey=qgjuc3jb2kajy6wuo3384oujl&dl=0)

