# RFID
Stock management and monitoring system with ESP WROOM 32

This project demonstrates making changes on a MySQL database
according to the reading data by an RFID module with an
ESP variation i.e. ESP WROOM 32.

==========================================================================

In connect.php file,
* Make sure you changed the Hostname, Username, Password and Schema.

==========================================================================

In rfid_dbse.ino file,
* Change the WIFI SSID and password.
* Replace the IP address of the code with the server IP address.

==========================================================================

Instructions

1. Start the MySQL server by running XAMPP or WAMPP server.
2. Import the esp32.sql file in the localhost or any server. It creates required database and table.
2. Place the connect.php file in the xampp/htdocs folder.
3. Connect and upload the rfid_dbse.ino to the ESP WROOM 32 board.
