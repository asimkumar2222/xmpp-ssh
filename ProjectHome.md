XMPP-SSH invokes a remote shell from remote entities securely. It is entirely C++.

This software is based on the XMPP extension XIBB and XMPP-SSH.
Two of them are drafts. take a look on http://www.xmpp.org/extensions/

The remote shell is authenticated using RSA signature and the session is encrypted End-To-End  using an hybride algorithm: AES-256 (stream encryption) and RSA (session key negotiation).