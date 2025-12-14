# SIMFORIA

SIMFORIA is a constrained decision-integrity simulator.  
It does not teach, advise, or optimize.  
It enforces ambiguity, refusal, and hard limits under authority and pressure.  
This public release demonstrates the boundary only.
<details>
<summary>Verification</summary>

### SIMFORIA Boundary Proof (v1)

**Domain**
- simforia.com

**Artifact**
- `proof/simforia-boundary-v1.txt`

**Signature**
- `proof/simforia-boundary-v1.sig`

**Public Key**
- `proof/simforia_ed25519_public.key`

**Verification**
```bash
openssl pkeyutl -verify \
  -pubin -inkey simforia_ed25519_public.key \
  -rawin -in simforia-boundary-v1.txt \
  -sigfile simforia-boundary-v1.sig
