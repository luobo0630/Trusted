What is a Trusted Setup?
Many zero-knowledge proof systems, including Groth16, the proof system that Nocturne V1 uses, require a layer of entropy (randomness) to be applied to circuits in order for the proofs to be secure. The catch, however, is that nobody can know that randomness. For this reason, said randomness is often referred to as “toxic waste” - we must ensure that no one person holds onto the randomness, otherwise the zero-knowledge proof scheme will be broken.

In practice, we can more or less guarantee this by using multi-party computation (MPC). The main idea is that we get as many people as possible to generate their own randomness and apply it to the circuit, layering it on one-by-one in a manner reminiscent of a “summoning ceremony" or a “ritual of randomness”. As long as just one participant actually discards their “toxic waste”, the proof system will be secure.

Since you’re reading this, we hope that you, too, can contribute your randomness and be an important part of ensuring the security of the Nocturne protocol.
