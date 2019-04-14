Then, you need to find a place to host your issuer profile. What is issuer profile? From Open Badges, a Profile is a collection of information that describes the entity or organization using Open Badges. The main usage is to verify the cert is issued from proved person. Since we are using our owned public key, we need to host the profile file by ourselves.

Blockcerts itself provides two samples, one is issuer profile and another one is revocation list. First we need to download the two files.

https://www.blockcerts.org/samples/2.0/issuer-testnet.json
https://www.blockcerts.org/samples/2.0/revocation-list-testnet.json

Then, open the two files, and you will see a compressed json. What you need to do is first replace "msBCHdwaQ7N2ypBYupkp6uNxtr9Pg76imj" with your public key in issuer-testnet.json file, and upload it to somewhere, like GitHub, where you need to get a stable link for direct download. Then, replace the links in the two json files with the correct one.
