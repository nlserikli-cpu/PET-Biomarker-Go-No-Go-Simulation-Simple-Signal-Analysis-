# PET-Biomarker-Go-No-Go-Simulation-Simple-Signal-Analysis-
## PET Biomarker Go/No-Go Simulation

### Overview  
This project is a small exploratory simulation of how PET-derived biomarker signals might be interpreted in early-stage drug development, particularly in the context of go/no-go decision-making.

Rather than aiming for a full analytical pipeline, the focus here is on illustrating how differences in imaging signals between experimental conditions could be translated into a simple decision making framework.

### Method  
Two simplified groups were generated:
- A control group representing baseline PET signal levels  
- A treatment group representing a potential drug-induced effect  

Signal distributions were simulated and compared using basic statistics.

### Decision Framework  
A simple threshold-based approach was used to approximate early decision logic:
- If the observed difference in signal exceeds a predefined threshold → GO  
- Otherwise → NO-GO  

### Relevance  
In early drug development, imaging biomarkers such as PET can provide early readouts of biological response before clinical outcomes are available. Understanding how these signals are interpreted is a key part of early-stage decision-making.

### Note  
This is a conceptual simulation intended for educational and exploratory purposes. It does not use real PET datasets or represent a validated clinical model.
