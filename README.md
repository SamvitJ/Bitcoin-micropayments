**Monetization on the Modern Web: Automated Micropayments from Bitcoin Enabled Browsers**

This repository links to the four software components of a prototypical Bitcoin micropayments-based revenue system for online content publishers:
- [Monetized webpage](https://github.com/SamvitJ/micropayments-webpage) - a prototype webpage supported by two independent monetization schemes - 1) Google AdSense advertising and 2) a backing payments server that renders an ad-free version of the page if a visitor pays the requested Bitcoin fee. We implemented the [page](http://www.micropayments.tech/) as a single-page Node.js webapp hosted on Heroku.
- [Payments server](https://github.com/SamvitJ/21BC-server) - a backend process that handles billing and payments for the monetized page or resource. Our implementation is built with Python and Flask, and uses the [21 Bitcoin Library](https://21.co/features).
- [Client payment module](https://github.com/SamvitJ/21BC-client) - a software module with access to a client's Bitcoin wallet that issues payment transactions and generates proof-of-payment.
- [Client browser extension](https://github.com/SamvitJ/Faucet) - a browser plugin installed by the user that funds her usage of payable web services, by adding proof-of-payment to the headers of outgoing HTTP requests.

![Client-Server Setup](https://github.com/SamvitJ/Bitcoin-micropayments/blob/master/http-402-setup.png)

Authors: Samvit Jain, Arvind Narayanan  
Institution: Department of Computer Science, Princeton University  
