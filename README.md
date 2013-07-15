Charm
=====
Charm is a framework for rapidly prototyping advanced cryptosystems.  Based on the Python language, it was designed from the ground up to minimize development time and code complexity while promoting the reuse of components.

Charm uses a hybrid design: performance intensive mathematical operations are implemented in native C modules, while cryptosystems themselves are written in a readable, high-level language.  Charm additionally provides a number of new components to facilitate the rapid development of new schemes and protocols.

Features of Charm include:
* Support for various mathematical settings, including integer rings/fields, bilinear and non-bilinear Elliptic Curve groups
* Base crypto library, including symmetric encryption schemes, hash functions, PRNGs   
* Standard APIs for constructions such as digital signature, encryption, commitments
* A “protocol engine” to simplify the process of implementing multi-party protocols
* An integrated compiler for interactive and non-interactive ZK proofs
* Integrated benchmarking capability

Documentation
=============
For complete install, see our [documentation](http://jhuisi.github.com/charm/install_source.html). 

Schemes
=======
We have provided several cryptographic scheme [examples](http://jhuisi.github.com/charm/schemes.html) to get you going. If this doesn't help, then feel free to reach us for questions and/or comments at support@charm-crypto.com.

If you're using Charm to implement schemes, we want to know what your experience is with our framework. Your feedback is very valuable to us! 


