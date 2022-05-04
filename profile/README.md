# dBio

## About
`dBio` is a decentralized application (dApp) empowering patients to take control of their healthcare data. The project was initially developed at Harvard University by master's program students in the Software Engineering program.

## System Components
* [dbio-demo](https://github.com/HES-Capstone-dBio/dbio-demo) -- A full system representation in `docker-compose` format. Start here to get a feeling for what this dApp does!
* [dbio-protocol](https://github.com/HES-Capstone-dBio/dbio-protocol) -- Protocol control server encompassing numerous API endpoints for interacting with encrypted patient data and facilitating proxy re-encryption of stored resources.
* [dbio-fhir-proxy](https://github.com/HES-Capstone-dBio/dbio-fhir-proxy) -- Custom FHIR server implementation for use in healthcare IT infrastructure. Interacts with `dbio-protocol` for access control and data read/write for patients.
* [dbio-client](https://github.com/HES-Capstone-dBio/dbio-client) -- Frontend UI application comprising the dBio patient portal.
* [dbio-smartcontract](https://github.com/HES-Capstone-dBio/dbio-smartcontract) -- Ethereum smart contract supporting Lazy Minting of vouchers for NFTs corresponding to patient data.
