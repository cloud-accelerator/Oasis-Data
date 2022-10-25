# OASIS Stix Data Sets

This repo contains all of the stix models from the publicly available OASIS documents.

There are five collections:
1. ```appendix_c``` - the data from Appendix C of the Stix 2.1 standard https://docs.oasis-open.org/cti/stix/v2.1/csprd01/stix-v2.1-csprd01.html#_Toc16070850
2. ```examples``` - the data from the Stix Documentation Examples page https://oasis-open.github.io/cti-documentation/stix/examples.html
3. ```standard``` - the data objects from the Stix 2.1 standard Chapters 4-7 https://docs.oasis-open.org/cti/stix/v2.1/csprd01/stix-v2.1-csprd01.html#_Toc16070617
4. ```stix_cert_data``` - the data objects from the Stix 2.1 Interoperability Document https://docs.oasis-open.org/cti/stix-2.1-interop/v1.0/stix-2.1-interop-v1.0.html, 
5. ```threat_reports``` - the APT1 and Poinson Ivy Threat Reports from the Stix 2.1 Examples page https://oasis-open.github.io/cti-documentation/stix/examples.html


Note that the Stix Interoperability Test Data includes a JSON (stix_cert_personna_dict.json) that provides Section 4. Personna Checklist in machine readable form. This enables the Personna tests to be performed automatically as an integration test

If you want to prove your are fully Stix compliant, then we encourage you to prove you can consume and produce avery single objects in each of the repo's, in addition to merely completing the Stix Personna Tests