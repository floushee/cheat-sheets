**Covnert p12 to pem**
```
openssl pkcs12 -in source.pfx -clcerts -nokeys -out certificate.pem
openssl pkcs12 -in source.pfx -nocerts -out keyfile.key
```