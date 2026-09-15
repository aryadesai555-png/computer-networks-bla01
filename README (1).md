# Computer Networks: Foundations and Practical Demonstration

A structured study and practical demonstration of how computer networks work, how devices communicate, and how network performance can be observed using basic networking tools.

## Overview

This project explores the fundamental concepts behind computer networks, from end devices and access networks to routers, packet switching, protocols, performance, and security.

It also includes a practical connectivity test using the macOS Terminal `ping` command. The test demonstrates how to check whether a host is reachable and how to interpret packet loss and round-trip latency.

## Topics Covered

- Computer network foundations
- Network edge and network core
- End systems, clients, servers, and access networks
- Routers, links, and packet forwarding
- Packet switching and routing
- Common network protocols
- TCP/IP concepts
- DNS, HTTP/HTTPS, and Internet communication
- Bandwidth, throughput, delay, and latency
- Packet loss and network reliability
- Basic network troubleshooting
- Network security fundamentals

## Practical Demonstration: Ping Test

The connectivity test was performed on macOS using:

```bash
ping -c 4 google.com
```

### Test Results

| Metric | Result |
|---|---:|
| Packets transmitted | 4 |
| Packets received | 4 |
| Packet loss | 0.0% |
| Minimum round-trip time | 7.630 ms |
| Average round-trip time | 32.840 ms |
| Maximum round-trip time | 74.686 ms |
| Standard deviation | 25.863 ms |

### Interpretation

The test was successful because all four packets were received and there was no packet loss. The response times were different for each packet, which shows that network latency can change during communication.

The average round-trip time was approximately **32.840 milliseconds**.

## Repository Contents

```text
computer-networks-bla01/
├── README.md
├── presentation/
│   └── Computer_Networks_Presentation_With_Screenshot.pptx
├── script/
│   └── Speaking_Script.docx
├── demonstrations/
│   ├── ping-command.txt
│   └── ping-results-screenshot.png
├── diagrams/
│   └── Network_Diagram.png
└── references/
    └── References.txt
```

## File Descriptions

| Folder/File | Description |
|---|---|
| `README.md` | Project overview, topics, results, and repository guide |
| `presentation/` | PowerPoint presentation explaining the networking concepts |
| `script/` | Slide-by-slide speaking script |
| `demonstrations/` | Ping command, output summary, and screenshot evidence |
| `diagrams/` | Network diagrams used to explain the concepts |
| `references/` | Learning materials and references used for the project |

## Learning Outcomes

After completing this project, I developed a stronger understanding of:

1. The basic structure and purpose of computer networks.
2. The difference between the network edge and the network core.
3. How packets move between devices through routers and links.
4. The role of protocols in communication between systems.
5. The difference between bandwidth, throughput, latency, and packet loss.
6. How to use the `ping` command for basic connectivity testing.
7. Why reliability, performance, and security are important in networking.

## Technologies and Tools

- macOS Terminal
- `ping` networking command
- Microsoft PowerPoint
- Microsoft Word
- GitHub
- Computer networking course materials

## How to View the Project

1. Open the PowerPoint file in the `presentation/` folder.
2. Use the speaking script in the `script/` folder to follow the presentation.
3. Open the `ping-command.txt` file to view the command used.
4. Review the screenshot in the `demonstrations/` folder.
5. Check the `references/` folder for the learning materials used.

## Author

**Arya Desai**  
Computer Science Student

---

This repository was created to document my understanding of computer networking concepts and connect theoretical learning with a practical terminal-based demonstration.
