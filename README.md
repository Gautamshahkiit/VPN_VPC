# VPN_VPC
A session on VPN and VPC done in Dheet Developers Team at Devsnest.


## VPN
- Virtual Private Network or client server architecture
- establishes a protected network connection between the client and the ISP.
- ecrypted in real time.

## VPN benefits
- Secure Encryption
  - would take millions of years for a computer to decipher the code via BFA.

## Types of VPN
- IPsec VPN or Site-to-Site VPN
- TLS or client-to-server VPN

## Site-to-Site VPN
- IPsec is a popular framework used to secure site-to-site communication over an IP network.
- always ON
- for site-to-site VPN network
- IPsec usually uses port 500.
- Goals:
  - integrity
  - confidentiality
  - authentication of data

## Remote Access VPN
- it is the same security protocol used to encrypt your web traffic while connection to https which requires an application host, site accepts the connection request
- requires a connection request to allow single device to a corporate network ex: laptop, desktop, tablet, phone
- for remote access VPN
- public networks might block site-to-site VPNs
- But TLS uses port: 443 which is usually allowed
  - Full tunnel = all to corporate servers
  - split tunnel = selected only to corporate servers, rest normal

## Encryption Algorithms
- Triple DES / 3DES = Data Encryption Standard
- AES = Advanced Encryption Standard
- RSA Security = Rivest-Shamir-Adleman
- Blowfish
- Twofish
- IDEA
- MD5
- HMAC

## Some terms to get used to: 

### HTTP
- HyperText Transfer Protocol
- for viewing web pages
- transfered over the public internet, sent in clear text
- so, there is vulnerabilty of data stealing
- only one key which can get leaked.

### HTTPS 
- Secure HyperText Transfer Protocol
- data ecrypted via private key
- alreaady done
- uses one of the two secure protocols out of SSL or TLS to ensure security

### SSL
- Secure Sockets Layer
- uses public key encryption
- requests verification from website / server.
- accepts SSL certificate
- then, encrypted data is transferred. 

### TLS
- Transport Layer Security
- authenticates both the server and client and then transfers the encrypted data.
- its the latest industry standard cryptographic protocol
- Diffie–Hellman key exchange may be seen as a complete cryptographic protocol in itself for other applications
- advanced TLS even has repudiation support

  Non-repudiation refers to a situation where a statement's author cannot successfully dispute its authorship or the validity of an associated contract.[1] The term is often seen in a legal setting when the authenticity of a signature is being challenged. In such an instance, the authenticity is being "repudiated".[citation needed]

    For example, Mallory buys a cell phone for $100 and writes a paper cheque as payment, and signs the cheque with a pen. Later, she finds that she can't afford it, and claims that the cheque is a forgery. The signature guarantees that only Mallory could have signed the cheque, and so Mallory's bank must pay the cheque. This is non-repudiation; Mallory cannot repudiate the cheque. In practice, pen-and-paper signatures aren't hard to forge, but digital signatures can be very hard to break.

      In digital security, non-repudiation means:
        - A service that provides proof of the integrity and origin of data.
        - An authentication that can be said to be genuine with high confidence.




https://blog.storagecraft.com/5-common-encryption-algorithms/#:~:text=RSA%20Security,data%20sent%20over%20the%20internet.&text=Unlike%20Triple%20DES%2C%20RSA%20is,private%20key%20to%20decrypt%20it.

https://www.getapp.com/resources/common-encryption-methods/

https://acodez.in/data-encryption-algorithms/

## Youtube Tutorials:
1. https://www.youtube.com/watch?v=CWy3x3Wux6o
2. https://www.youtube.com/watch?v=xGjGQ24cXAY
3. https://www.youtube.com/watch?v=hExRDVZHhig
   
![VPN](https://static.nc-img.com/uxteam/lc.simple-pages/vpn-content/img/how-vpn-works.40325059.png "VPN")
