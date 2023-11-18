# encoreToOml-seed

## Description
Welcome to our solution designed to streamline and standardize the use of Electronic Data Sheets (EDS) in the space industry. Our project focuses on enhancing the efficiency and accuracy of spacecraft design and integration by leveraging the power of EDS.

### Key Features
- **Standardized Data Sheets:** Implement a unified format for EDS, ensuring consistency and clarity across different systems and components.
- **Automated Documentation:** Facilitate the automatic generation of engineering artifacts from EDS, significantly reducing manual effort and the potential for human error.
- **Integration with Existing Systems:** Seamlessly integrate with current spacecraft design and development processes, supporting both SOIS (Spacecraft Onboard Interface Services) and SAVOIR (Space Avionics Open Interface Architecture) standards.
- **Compiler Applications:** Develop tools to interpret EDS and automatically generate corresponding engineering outputs, enhancing the design lifecycle of space missions.

### Background
The project was initiated to address the challenges faced in the space industry due to the lack of standardized documentation. By adopting a digital, machine-readable format for EDS, our project aims to significantly reduce errors and inefficiencies in spacecraft design and integration.

### Reference
To develop our project, we utilized the [*Recommendation for Space Data System Standards: Recommended Standard for Spacecraft Onboard Interface Services—XML Specification for Electronic Data Sheets*](https://public.ccsds.org/Pubs/876x0b1.pdf) authored by the Consultative Committee for Space Data Systems (CCSDS).

## Getting Start 
This project uses [Ontological Modeling Language (OML)](https://www.opencaesar.io/oml/) developed by the Jet Propulsion Laboratory (JPL), and provided by the openCAESAR project. 

### Requirement
Java : 17
Gradle : 7.4.2 or +

### Installation

```bash
git clone https://github.com/SophieCurinier/EncoreToOML-seed
cd EncoreToOML-seed
./gradlew build
```
### Functionality
#### Task to convert the OML catalog to OWL catalog
```bash
./gradlew omlToOwl
```
#### Task to generate documentation for the OWL catalog
```bash
./gradlew generateDocs
```
### Task to run a set of SPARQL queries on a Fuseki dataset endpoint
```bash
./gradlew owlQuery
```

## Contact

- Swendart : [Sophie Curinier](www.linkedin.com/in/sophie-curinier)
- CharlesdeMalefette : [Charles de Malefette](https://www.linkedin.com/in/charles-de-malefette-85586822a/)
