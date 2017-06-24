# Hy-SAIL
Cloud computing has gained increasing attention from the industry and research communities.
Despite the crucial benets provided by this new paradigm, some numerous
challenges arise. The concern about data stored in the cloud computing enviroment
has been widely discussed, in according to recents events shown in the international
media. Among these challenges, there is the problem of ensuring the integrity and
retrievability of users' data stored in the cloud. Many definitions has been proposed:
PDP (Proof of Data Possession), PoR (Proof of Retrievability), PoW (Proof of Ownership).
The difference among them reside in the guarantee to retrieve the data stored
remotely.
In this paper, we propose a novel cryptographic system: Hy-SAIL (Hyper-Scalability,
Availability and Integrity Layer). In the proposed protocol, a new PoR scheme is built
using an Online Codes, a special case of Fountain Codes, as building blocks which adds
a higher degree of availability of stored data. To perform integrity checks, properties
in Galois Field, GF(2n), is used to build a MAC with XOR homomorphic property. It
is demonstrated that Hy-SAIL leads to an eficient and scalable cryptographic system
that meets near-optimal bounds in the communication, storage and time complexities.
Finally, the Bounded Corruption Model, a new adversarial model that aggregates the
main functionalities of a realistic adversary in cloud computing environments is proposed.
It is proved that Hy-SAIL has provable security in this new approach. It is also
shown the results collected of an unoptimized implementation.
