## Virtual Research Environment

The Virtual Research Environment is an analysis platform developed at CERN serving the needs of scientific communities involved in European Projects. Its scope is to facilitate the development of end-to-end physics workflows, providing researchers with access to an infrastructure and to the digital content necessary to produce and preserve a scientific result in compliance with FAIR principles. The platform’s development is aimed at demonstrating how sciences spanning from :collision: High Energy Physics :sparkles: to :satellite: Astrophysics :telescope: could benefit from the usage of common technologies, initially born to satisfy CERN’s exabyte-scale data management needs.

```mermaid
---
title: VRE Hub Structure
---
graph TD;
    id1([vre-hub])-->id2(vre<br>Infrastructure Code);
    id1([vre-hub])-->id3(environments<br>Notebook Profiles);
    id1([vre-hub])-->id4(science-projects<br>Example Science Projects);
    id1([vre-hub])-->id5(vre-hub.github.io<br>Documentation);
    id1([vre-hub])-->id6(vre-dev<br>Dev Cluster);
    id1([vre-hub])-->id7(status<br>Service Status Page);    
```

👩‍💻 Find the VRE documentation and overview [here](https://vre-hub.github.io/).  
🌈 Any contribution is welcome! Feel free to create issues and start discussions! Find our wiki [here](https://github.com/vre-hub/vre/wiki).  

*The platform development effort is part of the [EOSC Future Project](https://eoscfuture.eu), an EU-funded H2020 project implementing the European Open Science Cloud (EOSC).*
