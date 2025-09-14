Wildfires are a seasonal problem typically faced during summer. Whether natural or man-made, forest fires have dramatic consequences, not only because of the loss of vegetation, but also due to the economic and social impact on the population living in the affected areas. During a wildfire, those involved in extinguishing the flames need real-time information about the status and evolution of the fire.

In order to contribute to solving this issue, the Communications Engineering Group at IDeTIC-ULPGC developed a lightweight surveillance system to monitor and gather useful information about wildfires. This project aimed to develop an alternative communication system for this monitoring platform based on the SX1272 LoRa module. This module operates at 868 MHz, a frequency that is severely affected by vegetation and rugged terrain. Therefore, the idea of the project was to lower the operating frequency to the VHF band, as lower frequencies are less affected by such environments.

The positive aspects that LoRa offer are:
- Long-distance communications under free space conditions.
- Low power consumption.
- Robustness.

By combining these characteristics with propagation conditions of VHF, which are better compared to 868 MHz in rural environments, the communication system is expected to be improved significantly.

A basic block diagram of the system as a whole is shown below:

![fullsignal_blockdiagram](https://github.com/user-attachments/assets/82daa8d6-4046-4b7b-aa99-6488fb578dda)

*Figure 1. Basic block diagram of the VHF-based wildfire communication system.*

Three elements are shown in the picture above:
- **Antenna**: device used to transmit and receive electromagnetic waves. It takes the output signal from the VHF Header (RF_O) and transmits it to the medium. Furthermore, it receives the input signal (RF_I) and passes it to the VHF Header. 
- **VHF Header**: electronic circuit that processes the signals it receives. It takes RF_I and converts it into FI_I. Conversely, it converts the signal FI_O from LoRa module into RF_O  
- **SX1271 module**: communication circuit that generates the signals to be transmitted, and recovers the information from the signal received.

The project followed a structured design process, consisting of the stages described below:
- **System specifications**: define the parameters the system must have. These are the RF and IF frequencies, bandwith, input power, output power, etc.
- **Proposed topologies**: evaluate possible component distributions to meet the system specifications.
- **Topology selection**: choose the suitable topology based on efficiency and complexity criteria.
- **Frequency planning**: perform the calculation of the local oscilator and the parameters of the filters defined in the topology.
- **Components proposal**: among the possible options availables in the market, to look for the best candidates for each component.
- **Power budget calculation**: based on the characteristics of the components proposed, calculate
- **Final components selection**:
