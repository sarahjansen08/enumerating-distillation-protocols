# enumerating-distillation-protocols

Enumerating all bilocal Clifford distillation protocols through symmetry reduction.

MAIN FILES <br>
<b>Transversal.ipynb</b>: Given an input (n > 1), this file creates a transversal of right cosets of the subgroup that preserves distillation statistics in the Clifford group. 
This is done in the binary picture. <br>
<b>Distillation_statistics.ipynb</b>: Given a transversal and the corresponding n > 1, this file calculates the distillation statistics (success probability and fidelity).
The function sucprob_fid_lists returns all possible combinations of success probability and fidelity that can be obtained. <br>
<b>dejmps_optimality.ipynb</b>: Checks analytically that DEJMPS achieves the highest fidelity for a double tensor product of the same bell-diagonal state. <br>

DATA <br>
<b>2_transversal_inv.sobj</b>: Transversal for n = 2. The inverse symplectic matrices are saved here. <br>
<b>3_transversal_inv.sobj</b>: Transversal for n = 3. <br>
<b>4_transversal_inv.sobj</b>: Transversal for n = 4. <br>
