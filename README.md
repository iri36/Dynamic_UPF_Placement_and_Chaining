# Dynamic_UPF_Placement_and_Chaining
This repository releases the source code of the solutions for the dynamic UPF placement and chaining reconfiguration (UPCR) problem, proposed in the article "Dynamic UPF placement and chaining reconfiguration in 5G networks"[1] and published as open access in the Computer Networks journal. These solutions address the 5G UPF placement problem considering the possibility of splitting UPF functionalities into smaller microservices (Virtual Network Functions, VNFs) and chaining them together as required by service requests (PDU sessions). To this aim, PDU sessions are modeled as SFC requests (SFCRs). Their main goal is optimizing multiple cost components involved in the UPCR procedure and improving the system's quality of service.

The solutions take into account several aspects of the system such as UPF-specific considerations, SFC topology (single and multiple branches), VNF order constraints, service demands, and physical network capacities. Specifically, an integer linear programming (ILP) model and a heuristic algorithm called dynamic priority and cautious UPCR (DPC-UPCR) are provided. 
Article link:https://www.sciencedirect.com/science/article/pii/S1389128622002900

This repository contains two folders (one for each solution):
- ILP: Code of the exact solution.
- DPC-UPCR: Heuristic algorithm (PENDING)

If you use this software in your work, please cite it as [1] (see CITATION.cff).

References:
[1] Leyva-Pupo I, Cervelló-Pastor C, Anagnostopoulos C, Pezaros DP. Dynamic UPF placement and chaining reconfiguration in 5G networks. Computer Networks. 2022 Oct 9;215:109200.
