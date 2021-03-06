# Invalidation Process


Once a compromise has been found in an artifact and the link in the chain that introduced the artifact has been identified.   A request with SBOM ID and related data is sent to the consortium managing the Global SBOM Registry ([GSR](https://github.com/fahad-oss/sig-security-sbom/blob/master/Ecosystem/Services.md)).   The signoff will require three partners to review the request and send an invalidation request to the GSR.  


#### Warning (Code errors or such)

For warning requests, after GSR has been updated and invalidation has been processed, the identified [functionary](https://github.com/fahad-oss/sig-security-sbom/blob/master/Ecosystem/Pedigree.md) / chain will be flagged and marked.  Notification will be sent to the identified functionary.  This will also lower a chains pedigree going forward as the functionary is no longer at the same level.



#### Critical (Malicious)


For critical requests, after GSR has been updated and invalidation has been processed, the identified functionary / chain will not be allowed to push writes to GSR.   GCR will also be updated and future access will be blocked for functionaries.   Notification will be sent to the identified functionary, and functionaries that have ever participated in the chain and end consumers.  
