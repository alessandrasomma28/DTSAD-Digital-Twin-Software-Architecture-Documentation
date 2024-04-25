# DTSAD: Digital Twin Software Architecture Documentation

The **Digital Twin Software Architecture Documentation** (**DTSAD**) aims to cope with Digital Twins (DTs) software architectures limitations identified in literature analysis. In fact, despite the incresing interest in DTs and the growing number of publications related to the definition of a Software Architecture (SAs) for Digital Twins design and development, literature still struggles to adhere to Software Engineering Institute (SEI) guidelines [1,2]. According to SEI, SAs should produce a tangible product, *i.e.*, a *Software Architecture Documentation* structured in multiple architectural views. However, such structured documentation is still a challenging activity in DT design. 

Following the SEI guidelines for documenting software architectures [1,2] and the *4+1 Architectural view model* proposed by Krutchen [3], the DTSAD is the first attempt in literature that presents a *unified set of views made of multiple models*, describing Digital Twins systems from differen perspective. More in detail, it comprises a documentation template consisting of: 
* **Requirement View** containing the set of requirements a DT should fulfill;
* **Logical View** containing the models describing the *Digital Twin Domain Entities* (DTDE);
* **Development View** containing the models describing the *Digital Twin Components* (DTCo);
* **Process View** containing the models describing the interactions among DTDE/DTCo;
* **Impact Analysis** containing the traceability matrices between model elements and requirements.
The DTSAD has been implemented in the Visual Paradigm modelling tool to depict models in *UML* or *SysML*. The DTSAD completeness, usefulness and perceived usability has been validated by 14 Digital Twin domain experts by means of a validation survey. 

## Repository structure


### References
[1] Bass, L., Clements, P., Kazman, R.: Software Architecture in Practice. SEI series in software engineering, Addison-Wesley, 3rd edn. (2012)

[2] Clements, P., Bachmann, F., Bass, L., Garlan, D., Ivers, J., Little, R., Merson, P., Nord, R., Stafford, J.: Documenting Software Architectures: Views and Beyond. SEI Series in Software Engineering, Addison-Wesley (2010)

[3] Kruchten, P.: The 4+1 view model of architecture. IEEE Software 12, 45–50 (11,1995)
