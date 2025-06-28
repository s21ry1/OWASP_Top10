# OWASP Top 10: 4. XML External Entities (XXE)

XXE attacks occur when XML input containing a reference to an external entity is processed by a weakly configured XML parser. This can lead to internal file disclosure, internal port scanning, remote code execution, and denial of service.

## Example
- Malicious XML payloads referencing external entities

## Prevention
- Disable external entity processing in XML parsers
- Use less complex data formats (e.g., JSON)
