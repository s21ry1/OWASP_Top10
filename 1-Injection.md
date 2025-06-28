# OWASP Top 10: 1. Injection

Injection flaws, such as SQL, NoSQL, OS, and LDAP injection, occur when untrusted data is sent to an interpreter as part of a command or query. The attacker's hostile data can trick the interpreter into executing unintended commands or accessing data without proper authorization.

## Example
- SQL Injection: `SELECT * FROM users WHERE username = 'admin' AND password = '' OR '1'='1';`

## Prevention
- Use parameterized queries
- Employ ORM frameworks
- Validate and sanitize all user inputs
