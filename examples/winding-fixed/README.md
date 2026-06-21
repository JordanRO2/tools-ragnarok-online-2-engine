# Winding-fixed NIF models

Real output of `tools/fix_nif_winding.py` on RO2 client models that rendered
inside-out (reversed triangle winding). These are the already-corrected models,
ready to repack into the client's VDK:

- `Female_Odinguitar_Back_01.nif`, `Noel_*_Odinguitar_Back_*.nif` — Odinguitar instrument (back)
- `TWOHANDSWORD_09.nif` — two-handed sword

Regenerable from the original model with `python tools/fix_nif_winding.py <model.nif>`.
Kept here as reference outputs of the tool.
