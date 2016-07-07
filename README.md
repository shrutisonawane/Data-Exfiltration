# Data-Exfiltration
The code helps to exfiltrate the data provided in the command line using an IP packet.The text is converted to its 8-bit ASCII equivalent, and passed as the higher 8 bits of the  ID field of the IP header. The lower 8 bits of the ID field contains a randomly generated value between 0 to 127 (considering signed ints, else unsigned range from 0 to 2^8-1 can be considered).
