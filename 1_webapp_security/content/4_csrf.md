# Cross-Site Request Forgery (CSRF)

This attack method works by including malicious code or a link in a page that accesses a web application that the user is believed to have authenticated. If the session for that web application has not timed out, an attacker may execute unauthorized commands.

[CSRF](https://guides.rubyonrails.org/security.html#cross-site-request-forgery-csrf)
[Video](https://www.youtube.com/watch?v=vRBihr41JTo)

## Countermeasures

- Use GET only for read requests
- Use POST for requests that change data (also PATCH, PUT, DELETE)
- Use CSRF tokens
