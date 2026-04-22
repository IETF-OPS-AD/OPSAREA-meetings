# Operations & Management Area Open Meeting (opsarea) Agenda - IETF 126

* ADs: Mohamed Boucadair & Mahesh Jethanandani

## Compact Agenda

|Slot      | Topic                                               | Presenters   |
|:--------:|:---------------------------------------------------:|:-------------|
| 5        | Agenda Bashing & Introduction                       | ADs          |
| 20       | State of OPS Nation                                 | TBC          |
| 15       | IP Address Geolocation                              | Tommy        |
| 20       | foo over QUIC: Operational Motivations & Challenges | Per   |
| 15       | Proposals for ICMP Extensions: Operational Motivations & Rationale | Ron  |
| 15       | Raven: Opensource BGP Routing Validation            | Ritesh       |
|          |                                                     |   |


## Detailed Agenda

### Introduction (ADs, 5 min)

### State of OPS Nation (WG Chairs, 20 min)

### IAB Workshop on IP Address Geolocation: Issues and Perspectives (15 min)

### foo over QUIC: Operational Motivations & Challenges (Per Andersson, 20 min)

Many proposals are being promoted in several IETF WGs to port protocols widely used in operator networks to be transported over QUIC. There might be technical arguments that motivate such extensions, however, porting protocols used within operator networks to support QUIC would have some impacts on fault isolation, troubleshooting, etc. Because of the lack of the visibility on the transport headers, providing feature parity may be challenging without tools upgrade and also logistic (e.g., synchronize keys to decode messages, etc.).

There is a need to (1) have a common understanding of the operational benefits, (2) understand the underlying challenges that can be inherited especially when the connection endpoints are not adjacent to each others, and (3) identify deployment incentives especially when there are alternate mechanisms to achieve similar objectives (TLS, etc.), (4) identify whether there are specific missing QUIC features that would ease use in operators network , and (5) explore whether there is common operational guidance that can inform most of these extensions (and similar).

   + draft-ietf-regext-epp-quic: Extensible Provisioning Protocol (EPP) Transport over QUIC
   + draft-ietf-netconf-over-quic: NETCONF over QUIC
   + draft-liu-grow-bmp-over-quic: Using BMP over QUIC connection
   + draft-liu-sidrops-rpki-rtr-over-quic: RPKI to Router Protocol over QUIC
   + draft-llg-opsawg-ipfix-over-quic: IPFIX Protocol over QUIC
   + draft-retana-idr-bgp-quic: BGP over QUIC
   + draft-yl-radext-quic-transport: RADIUS over QUIC
   + draft-yang-pce-pcep-over-quic: PCEP over QUIC
   + draft-cel-nfsv4-rpc-over-quicv1: Remote Procedure Call over QUIC Version 1

### Proposals for ICMP Extensions: Operational Motivations & Rationale (15 min)

There are many proposals to extend ICMP/ICMPv6 with a new feature. This slot is meant to expose ICMP-related work to the OPS community by providing a bi picture of various extensions, highlight the operational issues, and discuss deployability challenges of some of these extensions. This can also be an opportunity to seek for feedback from operators. Some guidance about extending ICMP/ICMPv6 while taking into account deployment matters may be considered.

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

### Raven, an Opensource BGP Routing Validation Tool

RAVEN is an open-source, lightweight, single-binary routing security observability tool. It connects directly to your routers via BMP, validates every route against RPKI ROV and ASPA path validation in real time, and exposes the results through a CLI, Prometheus metrics, and Grafana dashboards.

## Tentative

### AINETOPS Follow-up (15 min)

### NMRG/IETF OPS Transfer: Status, Exploring collaboration (15 min)

### NMOP 3535 refresh: Focus on implementation Guidance (15 min)






