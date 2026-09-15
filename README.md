Computer Networks

About This Project:

This repository contains my work on computer networking concepts and a practical `ping` test.

The presentation explains the basics of how devices communicate over a network, how data moves through routers, and how different protocols help the Internet work.

Topics Covered:

- Network basics
- Network edge and network core
- End devices, routers, and links
- Packet switching
- Network protocols
- TCP/IP
- DNS and HTTP/HTTPS
- Bandwidth, latency, and throughput
- Packet loss
- Basic network security
- Network troubleshooting

Ping Test:

I used the macOS Terminal to test the connection to Google:

```bash
ping -c 4 google.com
```

Results:

| Metric | Result |
| Packets sent | 4 |
| Packets received | 4 |
| Packet loss | 0.0% |
| Minimum time | 7.630 ms |
| Average time | 32.840 ms |
| Maximum time | 74.686 ms |
| Standard deviation | 25.863 ms |

All four packets were received, so the test completed successfully. The response time was different for each packet, which shows that latency can change while data is being sent across a network.

Project Files:

- PowerPoint presentation: Covers the main computer networking concepts.
- Speaking script: Contains the explanation for each presentation slide.
- Ping command file: Shows the command used for the connectivity test.
- Ping screenshot: Shows the results of the ping test.
- References: Lists the learning materials used for the project.

What I Learned:

This project helped me understand how devices communicate over networks, how routers forward packets, and how protocols organize communication. The ping test also helped me understand packet loss and response time in a practical way.

Tools Used:

- macOS Terminal
- `ping`
- Microsoft PowerPoint
- Microsoft Word
- GitHub

Author:

Arya Desai

Computer Science Student
