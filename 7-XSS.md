# OWASP Top 10: 7. Cross-Site Scripting (XSS)

XSS flaws occur whenever an application includes untrusted data in a new web page without proper validation or escaping, or updates an existing web page with user-supplied data using a browser API that can create HTML or JavaScript.

## Example
- `<script>alert('XSS')</script>` injected into a comment field

## Prevention
- Escape user input
- Use Content Security Policy (CSP)
- Sanitize HTML
