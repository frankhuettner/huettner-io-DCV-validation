# huettner-io-DCV-validation

How did I do this:

1. Create the certificate with open ssl in the commandline
2. Upload it and set the certification to HTTP 
3. I made a file in my github repo in `/.well-known/pki-validation/` with name `6482D3DD2836F2E4F110824DD30B42B3.txt`

`/.well-known/pki-validation/6482D3DD2836F2E4F110824DD30B42B3.txt`

and entered the text

`072FC31160D6A115EA3141C41ADF7686E11C5DC1D2B05E482551E80C5155F033 comodoca.com 620f4ce2a4bb0`


4. redirect the website, i.e., `www.huettner.io` and `huettner.io`
to
`https://raw.githubusercontent.com/frankhuettner/huettner-io-DCV-validation/main`
