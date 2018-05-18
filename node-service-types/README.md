# NMOS Node Service Types

This Node Service Types parameter repository contains values that may be used to identify a service 'type', used in the 'services' property of the node resource defined in the [AMWA NMOS Discovery and Registration Specification (IS-04)](https://github.com/AMWA-TV/nmos-discovery-registration). Note: the 'services' property was introduced in IS-04 v1.1.

## Criteria

- Values used for the service 'type' property are not required to be included in this repository.
- Each entry MUST define a unique service type name (which is a URN).
- Each entry MUST have a short description and include contact information for the proponent(s).
- Each entry SHOULD provide a link to a specification for the service type, as well as identifying the IS-04 API Versions for which the entry is applicable.
- In the case of substantial revision to the service specification, a new service type name MUST be defined. Using versioned names is therefore RECOMMENDED.
- Additions and updates to this parameter repository are to be submitted via a Pull Request (PR) according to the [General Procedures and Criteria](../README.md#general-procedures-and-criteria).

## Values

- **Name:** urn:x-manufacturer:service:status
  - **Description:** Used purely as an example in IS-04 (see [nodeapi-v1.1-self-get-200.json](https://github.com/AMWA-TV/nmos-discovery-registration/blob/v1.1/examples/nodeapi-v1.1-self-get-200.json)).
  - **Proponent:** [AMWA-TV](https://github.com/AMWA-TV)
- **Name:** urn:x-ipstudio:service:mdnsbridge/v1.0
  - **Description:** This API provides a zeroconf/HTTP bridge for NMOS service types.
  - **Proponent:** [BBC](https://github.com/bbc) (contact @simonrankine)
  - **Specification:** [NMOS MDNS Bridge](https://github.com/bbc/nmos-mdns-bridge)