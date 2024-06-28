# Port_Scanner.1-1023

Multi-Threaded Port Scanner
This Python script performs a port scan on a specified target host to determine which ports are open within a given range. The script utilizes multi-threading to enhance performance by scanning multiple ports concurrently.

Key Features:
Socket Programming: Utilizes the socket library to create network connections and check if a specific port on the target host is open.
Threading: Employs the threading module to create multiple threads, enabling concurrent scanning of ports and improving the overall scanning speed.
Queue Management: Uses the Queue module to manage the list of ports to be scanned, ensuring thread-safe operations and efficient task distribution among threads.
