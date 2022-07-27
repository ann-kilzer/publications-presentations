# Airavat: Security and Privacy for MapReduce


Indrajit Roy, Srinath T.V. Setty, Ann Kilzer, Vitaly Shmatikov, Emmett Witchel
The University of Texas at Austin

In Proceedings of the 7th Usenix Symposium on Networked Systems Design and Implementation
NSDI 2010, San Jose, USA.

## Abstract

We present Airavat, a MapReduce-based system which
provides strong security and privacy guarantees for distributed computations on sensitive data. Airavat is a
novel integration of mandatory access control and differential privacy. Data providers control the security policy
for their sensitive data, including a mathematical bound
on potential privacy violations. Users without security
expertise can perform computations on the data, but Airavat confines these computations, preventing information
leakage beyond the data provider’s policy.
Our prototype implementation demonstrates the flexibility of Airavat on several case studies. The prototype is
efficient, with run times on Amazon’s cloud computing
infrastructure within 32% of a MapReduce system with
no security


https://www.cs.utexas.edu/~shmat/shmat_nsdi10.pdf

http://z.cs.utexas.edu/users/osa/airavat/
