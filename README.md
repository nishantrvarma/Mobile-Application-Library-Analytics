# Mobile-Application-Library-Analytics
Today, Mobile Money applications provide one of the main openings into financial
self-dependence which is desperately required by a large population of the world's
developing economies. Yet even with this critical role played by these services, one
can progressively find an inexplicable increase in the risks and ill-informed security
practices taken by them. In particular, a host of these applications are observed to be
using numerous third party analytical modules. Although these modules provide
much desired functionality, it is alarming that user-critical data is being handled by
several third-party modules whose security facets have not yet been scrutinized. A thorough analysis of a large number of third-party libraries is performed and a holistic classification of the same based on their security is presented.

# Methodology
Mobile Money applications from the sample space are reverse engineered and the
third party libraries being used by them are established. The primary aid in this regard
was APKTool. To confirm the observations, another service, LibRadar was utilized.
This was followed by a comprehensive analysis of the security features of these
libraries. This analysis required the usage of Mallodroid. However, as the possibility
of false positives are prevalent when using Mallodroid, a manual assessment was
required for certain libraries.

# Sample Space
The analysis was performed on the 10 most popular Mobile Money applications
available on the Google Play Store. These applications cater to a wide variety of
countries spread across the globe including Philippines, Kenya and India. While older
versions of these applications have potentially a much weaker security model, this
particular study focuses only on the latest iterations of these products.

# Results
A number of vulnerabilities were successfully located among the libraries being used
by premiere Mobile Money applications including but not limited to inappropriate
manipulation of TLS, faulty or non-existent encryption, inadequate randomization
and patch integrity issues which could potentially allow an adversary to compromise
the entire system. These findings exhibit a huge flaw in the Mobile Money sector and portray the
mediocre security practices followed by them. Until the libraries being used are
rendered vulnerability free, the services offered by the Mobile Money sector cannot
be trusted in its entirety. Current results imply a latent yet dangerous scenario where
the exploitation of these vulnerabilities by any plausible attacker can cause the entire
Mobile Money system to crumble and fall.

