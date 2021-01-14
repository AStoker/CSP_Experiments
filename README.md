# CSP Experiments

To test CSP violations where a script loads an external script, put this script tag in your html:  
``` html
<script type="module" src="https://ghcdn.rawgit.org/AStoker/CSP_Experiments/main/nefarious.js"></script>
```

To add a domain to the CSP violation allowed list, add this domain: `https://cdnjs.cloudflare.com`
