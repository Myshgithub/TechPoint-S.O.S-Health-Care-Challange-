# TechPoint-S.O.S-Health-Care-Challange
Health Care-Team5
# Goal: Provide Better Health Care guidance to Patients as core of the System using Blockchain Technology
Provide better Health care service and data management to patients using Blockchain Technology 
(Considered 3 related Scenarios)

# Scenarios of using blockchain in different healthcare settings: 

All different but related scenarios can be as follow: 
Related Link: https://www.figma.com/file/doKioN0IL9tyGDgFUQgt29/All-Scenarios-of-using-blockchain-in-healthcare-system?node-id=0%3A1

- Scenario 1: Primary patient care.
- Scenario 2: Data aggregation for the research purposes and incentive the patient for sharing the data.
- Scenario 3: Connecting different healthcare players for better patient care.
Better means: By employing blockchain technology, our solution allows to facilitate the consent management and speed up data transfer. We developed a chaincode that allows a - - patient to easily impose fine-grained access control policy for his data and enables efficient data sharing among clinicians/ Health care providers.

- Senario 4: Remote Health System for Patient Monitoring.

- Senario 5: Digital Passport as response to Covid-19.


# Name of Proposed Product:  Provide better Health care guidance to patients

# Some Product Goals:
Provide better Health care guidance to patients- including Scenario 1: Primary patient care
What Better means in our Product/ Application are as follows:
-providing accountability of access, maintaining the complete and updated information with a verifiable record of the provenance, including all accesses/sharing/usages of the data.
-It supports privacy-preserving data sharing and management
-Motivate users/patients to be part of the research by building up incentives for users to share their profile data, in terms of rewards (micro-payments or credits). In this way, users become owners of their data and can decide how their data is collected and used, as well as shared.

# Product Specification:

- A blockchain-based records system would empower patients to retain full control over their data, choosing when, and to whom, to grant permission to access their information.

- Capable of storing and managing patient information in a verifiable manner, publicly accessible in real-time by anyone in the healthcare service provider chain (if authorized by the patient).

- Provide an up-to-date, comprehensive picture of patient health, enabling physicians, pharmacies and other providers to provide better health care guidance to patients.

# Architecture: 
https://www.figma.com/file/Xq9vSSCZp5yZ303mYhMMfv/Figure02-User-controlled-privacy-preserving-data-sharing-platform-in-the-Hospital-Admission-domain?node-id=0%3A1

https://www.figma.com/file/XRrj3TeJt190CcnaAplniT/Fig01-User-controlled-privacy-preserving-data-sharing-architecture


# Methdology and Tools:
combining blockchains and off-blockchain repository to create a data sharing and management model focused on security and privacy.

We base our system on the Ethereum service, a decentralized platform that allows developers to run applications on a custom-built blockchain (Ethereum Foundation, 2018). Since many times, blockchains do not innately offer sufficient storage, we store the actual medical records on a decentralized cloud storage such as Ethereum Swarm, a native base layer service of the Ethereum web3 stack that functions as a distributed storage platform (Swarm, 2018). 
The machine running MultiChain serves as one of the nodes, that collects patient’s/customers' data with proper validation. The public Ethereum blockchain stores and executes smart contracts. All the registered customers/patients and data consumers have Ethereum addresses, which are used to transfer the ether while sharing the data as per the smart contracts.
The data stored in the repository is converted into an open data JSON format, which is published via stream in the MultiChain. The stream in MultiChain is used for general data storage and retrieval.

# Design and prototyping links:

-Membership service web site:  to register users with different roles(currently Doctor and Patient). The roles define the functionality of the chaincode that is available to the user: https://rooppatel175.wixsite.com/blockchain
-Chain Code Prototyping: chaincode is deployed on every Node that acts as a Hyperledger validating peer. Nodes receive all transactions submitted by the users through a role-based APIs. https://www.figma.com/file/CcBKCBw9U7Pf6jggA1SmML/Provide-Better-Health-care-Guidance-to-Patients-on-Blockchain-(chainCode)-side?node-id=0%3A1

https://www.figma.com/proto/CcBKCBw9U7Pf6jggA1SmML/Provide-Better-Health-care-Guidance-to-Patients-on-Blockchain-(chainCode)-side?node-id=16%3A2&scaling=contain&page-id=0%3A1&starting-point-node-id=2%3A4&show-proto-sidebar=1

-Nodes and Permissions(Smart Contract): https://www.figma.com/file/7Zn2f4jY6U4R4hYOMH63Kf/Nodes-and-Current-Permissions?node-id=0%3A1





