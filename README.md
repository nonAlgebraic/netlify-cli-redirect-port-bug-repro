To reproduce:

1. run `yarn install`
2. run `yarn netlify dev -e`
3. Browse to http://localhost:9090/

**Expected behvior:** The user is 301 redirected to https://www.example.com/ as stipulated by the redirection rule.

**Observed behavior:** The user is 301 redirected to https://www.example.com:9090/.
