# Cardano Foundation iCC rationale files

This folder contains all rationalemetadata.jsonld files we use in our votes, 
as well as their "pretty" versions in pdf.

Both files are uploaded to ipfs - we will never link to this repo in onchain metadata. 


## Structure of CF rationales

We follow [CIP-136](https://github.com/cardano-foundation/CIPs/tree/master/CIP-0136) and use the References section for linking to the relevant sections in the Constitution for each Governance Action rationale, as well as linking to additionanl documentation, where applicable. 
In addition, we use the "other" type in the references to link the pdf version of the rationale for easier reading: 
```json
  {
      "@type": "Other",
      "label": "Rationale pdf",
      "uri": "ipfs://QmVxWwYv4AHRAZGddM9svPeLZ1putUsD36fbh1vKyhFPFg"
  }
```

At the moment we are not signing the rationale, as foreseen in the "authors" section of the rationale, but just mention "Cardano Foundation". 
