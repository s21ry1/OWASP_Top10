# OWASP Top 10: 8. Insecure Deserialization

Insecure deserialization often leads to remote code execution. Even if deserialization flaws do not result in remote code execution, they can be used to perform attacks, including replay attacks, injection attacks, and privilege escalation attacks.

## Example
- Manipulating serialized objects to change application logic

## Prevention
- Avoid accepting serialized objects from untrusted sources
- Implement integrity checks
- Use safe serialization formats
