Welcome! I'm Ronnie (WØrdm - [rdm@rdm.io](mailto:rdm@rdm.io) - [https://rdm.io](https://rdm.io)), I have been the Missouri 44Net Coordinator since July of 2020. As the IP address coordinator for Missouri, I am reponsible for assigning IP addresses in the `44.46.0.0 /16` IP space and offering technical tips as needed. This space will serve as a simple reference point for Missouri Amateur Radio Operators interested in leveraging the 44Net IP space for their radio projects.

This website was created to help simplify the onboarding process between a potential Missouri radio operator and me, the AMPRnet Coordinator. This website will never replace the [AMPRNet Wiki](https://wiki.ampr.org/), only supplement.

## Overview of onboarding

- Missouri Amateur Radio Operator Submitting Allocation Request
- Allocation Request is reviewed by me, the Coordinator
  - Block Size Reviewed against my [IP Addressing Methodology](guideline.MD)
- Approved or Denied
  - This workflow is now handled by the new portal. All communications from me or any ticket handler will happen via the ticket.
  - Rejection Email Sent, explination will be sent. The only time this happens is if I'm unable to validate information given or I need clarification.
- CIDR Blocks smaller than a `/24` are generally available to the requestor after I mark my approval.
- `/24` BGP routed blocks follow a different workflow.
  - After my approval, the request is routed to the BGP Coordinator for additional processing. Until the BGP Coordinator has granted approval and issued the LOR for your BGP setup, this process requires more processing time compared to non-BGP routed CIDR blocks.
  - The BGP Coordinator must issue the LOR before you will be able to move forward with your BGP routing setup.
  - BGP Routing is more complex than the IPIP tunnel.
- IPIP Tunnel allocations **will not work** until DNS Records have been added in the new portal.
  - IPIP mesh gateways update in 24-hour batch cycles. Thus, your newly minted DNS entry will not grant real-time acceptance. So, roughly 24-48 hours after the newly minted DNS entries are accepted, your IPIP tunnel should be routable over the mesh.

## Helpful Links

- [AMPRNet Wiki](https://wiki.ampr.org/)
- [Requesting a Block](https://wiki.ampr.org/wiki/Requesting_a_block)
- [AMPRNet Portal](https://portal.ampr.org/)

## Currently Allocated Space

| Network             | Description / Overview of Use       | Allocated To |
| ------------------- | ----------------------------------- | ------------ |
| 44.46.0.11 /32      | AC0G                                | AC0G         |
| 44.46.0.12 /32      | WE0DX                               | WE0DX        |
| 44.46.0.16 /30      | SEMO Packet Net                     | AB9S         |
| 44.46.1.0 /29       | KB0WLF in the woods                 | KB0WLF       |
| 44.46.1.24 /29      | KD0BQS                              | KD0BQS       |
| 44.46.1.32 /29      | KE6GAE                              | KE6GAE       |
| ~~44.46.1.40 /29~~  | ~~K0SNP experimental~~              | ~~K0SNP~~    |
| 44.46.1.48 /29      | KE0WDI                              | KE0WDI       |
| ~~44.46.1.56 /29~~  | ~~KC4UPR experiments~~              | ~~KC4UPR~~   |
| 44.46.2.16 /28      | W0KAH                               | W0KAH        |
| ~~44.46.2.32 /28~~  | ~~K0JAA experimental~~              | ~~K0JAA~~    |
| 44.46.2.48 /28      | Experimental                        | AB0DK        |
| 44.46.2.64 /28      | KD0WCV Exp                          | KD0WCV       |
| ~~44.46.2.80 /28~~  | ~~KC0EZE~~                          | ~~KC0EZE~~   |
| 44.46.2.96 /28      | Platte County Amateur Radio Group   | NR0AD        |
| 44.46.2.112 /28     | Mesh and Packet testing             | K0DEZ        |
| ~~44.46.2.128 /28~~ | ~~WZ9W Node~~                       | ~~WZ9W~~     |
| 44.46.2.144 /28     | N0ODV                               | N0ODV        |
| 44.46.2.160 /28     | AE0JE Experimental                  | AE0JE        |
| 44.46.2.176 /28     | W0GR Experimental                   | W0GR         |
| 44.46.15.0 /24      | NR0Q                                | NR0Q         |
| 44.46.16.0 /24      | Kansas City Metro BYRG AMPR Network | W0NQX        |
| 44.46.17.0 /24      | N0RJC - Various Services            | N0RJC        |
| 44.46.18.0 /24      | KY0LE Experimental                  | KY0LE        |
| 44.46.19.0 /24      | Mesh Network Testing                | W0RDM        |
| 44.46.20.0 /24      | AA0RC Networking                    | AA0RC        |
| 44.46.21.0 /24      | KC0UDT Home Net                     | KC0UDT       |
| 44.46.23.0 /24      | n0uuu                               | N0UUU        |
| 44.46.24.0 /24      | KD0VNN Mesh Testing                 | KD0VNN       |
| 44.46.32.0 /24      | DIGITAL NETWORK                     | NM5PB        |
| 44.46.96.0 /24      | KD0EAG amateur-experimental         | KD0EAG       |
| 44.46.128.0 /24     | Blue Springs, Missouri              | N0VEP        |

This table was last manually updated on, `16 February 2025`. You can view the most up to date information via the [Missouri AMPRNet Portal](https://portal.ampr.org/networks.php?a=region&id=879).
