# icfemproofs-downset

This contains the Isabelle proofs for the paper "Order Ideals are Ideal Orders"

The directory rg-algebra contains the pre-existing Isabelle formalisation of CRA.

Ordered_Semigroups.thy contains the models of magmas and semigroups used in the paper.

Downsets.thy contains the formalisation of order ideals and helper lemmas.

Conj_Obs.thy, Par_Obs.thy, Seq_Obs.thy contains the axiomatisation and proofs of the various operators for our model of observations.

CRA_Obs.thy brings those theories together and relates them with exchange laws.

Seq_Atomic.thy adds the notion of atomic steps and how they relate to sequential composition.

CRA_Atomic.thy brings together all the theories for how they pertain to atomic steps.