# Operations & Management Area Open Meeting (opsarea) Agenda - IETF 126

* ADs: Mohamed Boucadair & Mahesh Jethanandani

## Compact Agenda

|Slot      | Topic                                               | Presenters   |
|:--------:|:---------------------------------------------------:|:-------------|
| 5        | Agenda Bashing & Introduction                       | ADs          |
| 20       | State of OPS Nation                                 | TBC          |
| 15       | IP Address Geolocation                              | Tommy        |
| 20       | foo over QUIC: Operational Motivations & Challenges | Per   |
|          |                                                     |   |
|          |                                                     |    |
|          |                                                     |   |


## Detailed Agenda

### Introduction (ADs, 5 min)

### State of OPS Nation (WG Chairs, 20 min)

### IAB Workshop on IP Address Geolocation: Issues and Perspectives (15 min)

### foo over QUIC: Operational Motivations & Challenges (Per Andersson, 20 min)

Several proposals are being developped to add support for QUIC. The purpose is to understand what are the operational benifits and also the challanges (e.g., troubelshooting, diagnostic, etc.). Some of these deployments rely on stable/long sessions, where the use 0-RTT/1-RTT QUIC features may not bring much value.

Putting aside whether there are transport services specific for each of a protocol, there is a value to have a common understanding of the benefits, explore whether there is common operational guidance that can inform most of these extensions (and simialr), but also to understand the underlying challenges that can be inherited (e.g., troubleshooting, diagnostic, etc.) especially when the connection endpoints are not adjacent to each others.

   + draft-ietf-regext-epp-quic: Extensible Provisioning Protocol (EPP) Transport over QUIC
   + draft-ietf-netconf-over-quic: NETCONF over QUIC
   + draft-liu-grow-bmp-over-quic: Using BMP over QUIC connection
   + draft-liu-sidrops-rpki-rtr-over-quic: RPKI to Router Protocol over QUIC
   + draft-llg-opsawg-ipfix-over-quic: IPFIX Protocol over QUIC
   + draft-retana-idr-bgp-quic: BGP over QUIC
   + draft-yl-radext-quic-transport: RADIUS over QUIC
   + draft-yang-pce-pcep-over-quic: PCEP over QUIC
   + draft-cel-nfsv4-rpc-over-quicv1: Remote Procedure Call over QUIC Version 1

## Tentative

### AINETOPS Follow-up (20 min)

### NMRG/IETF OPS Transfer: Status, Exploring collaboration (15 min)

### NMOP 3535 refresh: Focus on implementation Guidance (20 min)

### Updates on Recent ICMP Extensions: Operational Motivations & Rationale (15 min)

* Reading material:
   + draft-ietf-intarea-rfc8335bis
   + draft-ietf-intarea-icmp-exten-hdr-len
   + draft-ietf-intarea-extended-icmp-nodeid
   + draft-ietf-6man-icmpv6-reflection
   + draft-ietf-6man-icmpv6-ioam-conf-state 
   + draft-bonica-intarea-icmp-exten-hdr-len
   + draft-jags-intarea-icmp-ext-underlay-info
   + draft-pignataro-icmp-enviro-info
   + draft-varhal-6man-icmp-srv6-vpn
   + draft-mitchell-intarea-rfc5837bis
   + draft-many-intarea-icmp-mp
   + draft-yl-savnet-icmp-extension
   + draft-xbm-intarea-icmp-query
   + draft-liu-6man-icmp-verification
   + draft-ali-6man-srv6-vpn-icmp-error-handling
   + draft-xu-intarea-challenge-icmpv6
   + draft-xu-intarea-vulnerabilities-forged-icmp
   + draft-xu-intarea-challenge-icmpv4




