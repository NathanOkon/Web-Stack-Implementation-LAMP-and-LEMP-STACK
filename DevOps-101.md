# What is Software Development life cycle.

This is a process used by software development teams to design, develop, test, and deploy software applications.<br>
It typically consists of stages such as planning, analysis, design, implementation, testing, deployment, and maintenance. Each stage has its own objectives, tasks and deliverables, contributing to the overall success of the software project.
# LAMP
Lamp stack is a popular open-source software bundle used for web development. it consist of four main components:<br>
-**Linux**: The operating system where the web sewrver runs<br>
-**Apache**: The web server software that serves web pages to users.
-**MySQL**: The relational database management system(RDBMS) used to store and manage data.
--**PHP**: The server-side scripting language used to generate dynamic web content.

# CHMOD
This stands for **change mode** and is a command in Linux used to change the permissions of file and directories. it allows users to specify who can read, write and execute a file or directory.
# CHOWN
This stands for **change owner** and is a command in Linux used to change the change ownership of file and directories. This commmand is typically used by system administrators to transfer ownership of file or to assign ownership to a different user or group.
# WHAT TCP AND UPD MEANS AND HOW THEY ARE DIFFERENT

TCP (Transmission Control Protocol) and UDP (User Datagram Protocol) are two widely used transport layer protocols in computer networking. They are both used for sending data across networks but have different characteristics.<br>

## TCP (Transmission Control Protocol):<br>

-TCP is a connection-oriented protocol, meaning it establishes a reliable connection between two devices before data transfer begins.<br>

-It ensures that data is delivered in the correct order and without errors through mechanisms like acknowledgments, retransmissions, and flow control.<br>

-TCP provides error checking and error recovery, making it suitable for applications where data integrity is crucial, such as web browsing, email, file transfer (FTP), and remote login (SSH).<br>

-TCP is slower compared to UDP due to the overhead of managing connections and ensuring reliability.<br>

## UDP (User Datagram Protocol):<br>

-UDP is a connectionless protocol, meaning it does not establish a dedicated connection before sending data.<br>

-It is a simpler and faster protocol compared to TCP, as it does not have the overhead of connection setup, acknowledgment, and error recovery mechanisms.<br>

-UDP provides no guarantee of delivery, ordering, or error checking. It simply sends packets of data, known as datagrams, to the destination without any assurance that they will arrive or arrive in order.<br>

-UDP is commonly used in applications where speed and efficiency are more important than reliability, such as real-time streaming media (e.g., VoIP, video conferencing), online gaming, and DNS (Domain Name System) lookups.