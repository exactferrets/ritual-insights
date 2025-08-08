# ritual - personal breakdown

Been looking into Ritual. They position themselves as "AI infrastructure for crypto".  
Not an AI token, but an actual protocol setup for running machine learning inside a blockchain context.

## What it does

It lets you run ML inference directly from a smart contract.  
No calls to OpenAI from some hidden backend.  
You get a decentralized network that runs the model and gives back a proof it actually happened.

## The main parts

### spellbook  
A framework for connecting ML models. You can treat it like a library of "functions" that a smart contract can call. Just that here, the functions are AI models.

### cauldron  
Takes a model and turns it into a verifiable onchain task. Uses ZK or optimistic proofs so you can prove the inference happened for real.

### coven  
A decentralized GPU network that runs the models. It returns not just the output, but a proof of execution.

## How it works together

1. A contract calls a model through spellbook  
2. cauldron compiles it into a verifiable task  
3. coven executes it on GPUs  
4. The result + proof go back to the contract

## Why it’s different from the usual web3 + AI

Normally, a dApp just calls OpenAI or HuggingFace through some server you have to trust.  
Here it’s all tied into the contract, and the verification is built-in.  
You don’t rely on “we promise we ran it” — the system forces proof.

## Possible use cases

- Onchain NPCs or agents  
- Games that generate content onchain  
- ZK-verifiable AI outputs  
- AI-driven modules for DAOs or automation

## Backing

- Archetype  
- Robot Ventures  
- Accomplice  
Raised around $25M.

## My take

This feels like real architecture for ML in crypto, not just hype.  
Still early, so the dev experience will be the deciding factor.  
If they make it simple enough to use, it could power a lot of AI logic in dApps.
