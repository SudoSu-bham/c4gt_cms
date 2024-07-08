## README.md

### Description
The project aims to understand different UI applications provided by Swasth for claim processing and outlines the design process for creating a core UI component library and integrating it into multiple applications. This approach promotes code reusability and maintainability across multiple projects. The common components library will be hosted on npm with comprehensive documentation.

### Goals
- [ ]  Create machine readable insurance plans as per the FHIR standards :  
- [ ]  Data Extraction & parsing : Extract and interpret data from health insurance product documents (primarily pdf or docs), including policy details and coverage information.
- [ ]  Data Standardization and coding : Standardise and code extracted data into structured formats compatible with FHIR standards as prescribed by Open HCX platform, ensuring consistency for interoperability across insurance systems.
- [ ]  Data Quality Enhancement : Identify and rectify discrepancies in digitised insurance plans, filling missing information and resolving ambiguities for completeness.
- [ ]  Testing and validation harness for the coded insurance plans :
- [ ]  Develop the testing and insurance plan validation harness for the digitised insurance plans created by other ecosystem participants.


### Weekly Goals
**Week 1**
- [x]  Understanding the HCX protocol

**Week 2**
- [x]  Researching and testing the FHIR API

**Week 3**
- [x]  Examining FHIR bundles and analyzing their various components and resources

**Week 4**
- [x]  Understanding about the insurancePlans profile
- [x]  Testing various PDF libraries for extracting the data from Health Insurance

**Week 5**
- [ ]  Study insurance plan of PMJAY and one private companies. 
- [ ]  Extracting valuable information from the PMJAY pdf.
### Expected Outcome
Backend required to extract, process, and encode insurance product data.  
The tool should generate standardised insurance plans with FHIR codes, enabling machine-readable formats for processes like auto adjudication.  
Test & validate insurance plans against the finalised format.

### Acceptance Criteria
Any human readable format such as PDF etc. are converted into FHIR Insurance profiles   https://ig.hcxprotocol.io/v0.7.1/StructureDefinition-HCXInsurancePlan.html

### Implementation Details

1. Project requires a detail understanding of JAVA or Python and APIs  
2. Setup HAPI FHIR server in local machine  
3. Understand FHIR profiles https://ig.hcxprotocol.io/v0.7.1/StructureDefinition-HCXInsurancePlan.html  
4. Use programming concepts to convert available insurance plans in PDF format into FHIR structures


### Mockups / Wireframes
- Not applicable (NA)

### Product Name
Digitizing Insurance Plans

### Project Name
Digitizing Insurance Plans: Encoding health insurance products for machine readability

### Organization Name
Swasth Alliance

### Domain
Healthcare

### Tech Skills Needed
- JAVA
- HAPI FHIR
- PYTHON

### Mentor(s)
- @saurabh-singh-17

### Complexity
High

### Category
- Performance Improvement
- Feature
- PoC

### Sub Category
- API
- Accessibility
- Backend
- Research
