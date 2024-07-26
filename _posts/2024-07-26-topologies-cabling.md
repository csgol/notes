---
title: "Topologies & Cables"
layout: post
categories:
 - cybersecurity
 - tech
---

# Network Topologies

- A description of how a network is laid out
- Physical topologies: the actual layout of devices
- Logical Topologies: how the data flows from host to host
---
### Bus Topology

- All host are connected together by one centralized cable
- All host share same bandwidth
- Gets slower as you add more host to the topology
- Can have issues if the main cable is compromised

---
### Ring Topology

- Frames travel along a ring of host
- Only has issues if there is a break between host
- Not used very often

---
### Star Topology (Hub-And-Spoke)

- Multiple host connected to a centralized "box" (Ex. Hub, switch, etc.)
- Box determines where to send data in the network
- Pretty common topology

---
### Star-Bus Topology (Hybrid Topology)

- Main "box" houses a bus 
- If the bus goes down the whole network goes with it

---
### Mesh Topology

- Every host is connected to all the other host
- Creates a mess of cables if it is wired
-  Very good for wireless networks
- Is very fault tolerant 

---

# Cabling

- Coaxial cable has two conductors; one center point, and a tubular conducting layer
- Radio grade (RG) specifies the thickness of the conductors, insulation, and shielding
- RG-6 has a 75-Ohm rating, is commonly used for cable networking, and uses a threaded F-type connector

---

### Coaxial Cable

1. **Construction**:
    
    - **Core**: Single central conductor (usually copper).
    - **Insulation**: Surrounds the central conductor.
    - **Shielding**: Braided or solid metallic shield (typically aluminum or copper) around the insulation.
    - **Outer Insulation**: Plastic or rubber outer jacket.
2. **Signal Transmission**:
    
    - Primarily used for high-frequency signals.
    - Suitable for radio frequencies (RF), television signals, and internet connections.
    - Transmits signals with high bandwidth over long distances with minimal loss.
3. **Applications**:
    
    - Cable television (CATV).
    - Internet and broadband connections.
    - Radio transmitters and receivers.
    - Closed-circuit television (CCTV).
4. **Impedance**:
    
    - Common impedances are 50 ohms (for radio transmitters) and 75 ohms (for television and internet).

### Twin-axial Cable

1. **Construction**:
    
    - **Core**: Two central conductors (usually twisted together) inside a single shield.
    - **Insulation**: Each conductor is individually insulated.
    - **Shielding**: Common shield around both conductors (can be braided or foil).
    - **Outer Insulation**: Plastic or rubber outer jacket.
2. **Signal Transmission**:
    
    - Suitable for differential signal transmission, where signals are sent over two wires to improve noise immunity.
    - Commonly used for high-speed digital data transfer.
    - Less signal loss over shorter distances compared to coaxial cables.
3. **Applications**:
    
    - Data storage systems.
    - High-speed networking environments.
    - IBM mainframe computers (historically).
    - Modern data centers for certain high-speed connections (e.g., Infiniband).
4. **Impedance**:
    
    - Common impedance for twin-axial cables is typically around 100 ohms, which matches the impedance of many digital data transmission systems.

### Key Differences

- **Number of Conductors**: Coaxial has a single central conductor, while twin-axial has two.
- **Signal Transmission**: Coaxial is often used for analog and RF signals, while twin-axial is used for high-speed digital signals.
- **Noise Immunity**: Twin-axial cables have better noise immunity due to differential signaling.
- **Distance and Bandwidth**: Coaxial cables can transmit signals over longer distances with less loss, but twin-axial cables are better suited for shorter distances with high-speed data transfer.

- Coaxial cable has two conductors; one center point, and a tubular conducting layer
- Radio grade (RG) specifies the thickness of the conductors, insulation, and shielding
- RG-6 has a 75-Ohm rating, is commonly used for cable networking, and uses a threaded F-type connector

---

### Twisted Pair Cable

- Very common cable
- Twisted cables reduce electromagnetic interference (FMI) and crosstalk

#### Unshielded Twisted Pair

- Only has a sheath, no protection for exposed cables
- Max distance of 100 meters (325 feet)
- Has 4 Pairs
- Uses RJ-45 connector
- Has a single Solid Core that carries the signal
- Comes in Two Standards
	1. TIA/FIA-568A 
	2. TIA/EIA-568B

#### Shielded Twisted Pair

- Has a grounded outer copper shield around the bundle of twisted pairs for protection
- Not as common as unshielded, needed for added protection for the cables

---

### Fiber Optic Cabling

- The cable is made up of the following:
	1. Fiber optic core that carries the light
	2. Cladding that reflect the light 
	3. Cable Jacket that protects the core

- Two types of fiber optic cable
	1. Multimode 
		- Carry LED signals
		- Cable is usually Orange
	1. Single-mode
		- Carry laser signals
		- Cable is usually Yellow

- Fiber Optic is a Duplex Cable

#### Connector Types for Fiber Optic

- ST Connectors
- SC Connectors
- FC Connector
- LC Connector
- MT-RJ Connector

---

### Fire Ratings

- Plenum-Rated: rated for being in area between ceilings, highest fire rating, expensive
- Riser-Rated: made for going through building floors, fire resistant
- PVC: no fire protection for the cables