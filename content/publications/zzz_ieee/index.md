---
title: "PULSE-A: Polarization-Modulated Optical Communications at the CubeSat Form Factor"
authors:
- Logan Hanssler
- Juan Ignacio Prieto Asbun
- Seth Knights
- Sofia Mansilla
- Everette Spencer Shelton
- Catherine Todd
- Elizabeth Rosario
- Graydon Schulze-Kalt
- Leah Vashevko
- Daniel Lee
- Robert Pitu
- Rodrigo Spinola e Castro
- Aidan Etterer
- Akash Piya
- Brian Yu
- Vidya Suri
- Lauren Ayala
- admin
- Mason McCormack
- Vincent Redwine
- Danielle Zumi Riekse
- Tian Zhong
- Michael Lembeck

# Schedule page publish date (NOT publication's date).
publishDate: "2025-12-04T00:00:00Z"

weight: 3

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["conference-proceedings"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Aerospace Conference Proceedings (Accepted)"
publication_short: ""

abstract: Recent advancements in sensing and observation technology have created an unprecedented need for space-to-ground bandwidth. While traditional radio frequency (RF) technology has innovated to meet this increasing requirement, most available options present significant size, weight, power, and cost (SWaP+C) restrictions, often forming a bottleneck for mission and science operations. Optical communication provides a promising alternative, capable of meeting many of the same SWaP+C requirements while providing orders of magnitude improvement in available bandwidth. The Polarization-modUlated Laser Satellite Experiment (PULSE-A) is a CubeSat mission currently under development at the University of Chicago aiming to demonstrate space-to-ground optical downlink at a data rate of up to 10 Mbps. Along with meeting the intense SWaP+C requirements of a university CubeSat mission, PULSE-A’s optical payload is designed to use circular polarization shift keying (CPolSK), making it the first demonstration of polarization modulation for space-to-ground optical communication. In addition to probing the viability and possible advantages of CPolSK for optical downlink, PULSE-A works to make optical communication technology more accessible. The project is entirely open-source and relies heavily on hardware designed and built by students to support both its technical and educational mission. The PULSE-A team is developing the mission’s 1U optical payload, 3U CubeSat bus, portable optical ground station (OGS), and RF ground station (RFGS) almost entirely in-house, making use of commercial off-the-shelf components alongside student-designed hardware to reduce cost and development overhead. The optical payload functions as a CPolSK-based, transmit-only optical communications terminal. Two lasers emitting orthogonal linearly polarized light at 1550 nm are driven in alternation, producing a linear polarization-modulated beam when combined. The beam is then amplified and converted to CPolSK states in free-space, where the data beam is then transmitted out of the spacecraft and toward the OGS. To meet the stringent pointing requirements of optical communications, PULSE-A makes additional use of a fine-steering mechanism informed by a 1064 nm ground-to-space beacon laser to account for body pointing error from a COTS Attitude Determination and Control System. The transmission beam is collected via an 11” amateur telescope at the OGS and then separated by polarization state. Detection is accomplished with high gain avalanche photodiodes, and a field programmable gate array (FPGA) demodulates and decodes the received data. In this paper, we will provide an overview of the design and expected operations for PULSE-A’s payload, bus, OGS, and RFGS. We will highlight design considerations and analyses made to support polarization modulation of the optical downlink as well as pointing, acquisition, and tracking.

tags:
- Optical Communications

---
