# Modifying Radish34

The Radish34 functional proof-of-concept \(POC\) demonstrates only a few key steps in a procurement process. The UI shows the setup of a [Workgroup](../baseline-basics/glossary.md#workgroup) and a [Workflow](../baseline-basics/glossary.md#workflow) that includes an RFP, Bids, a signed MSA, and POs to be calculated against the terms of the MSA. Each of these is called a Workflow Step, and the current version of Radish34 focuses heavily on the MSA and PO steps to demonstrate the full capability of on-chain and off-chain components of the Baseline Protocol.

But what if you wanted to add tokenized inventory, shipping & logistics, invoicing, or trade finance functions like invoice factoring? 

As a POC, it is certianly true that the [code](https://github.com/ethereum-oasis/baseline) of Radish34 still needs to add a layer of abstraction to take it to the next level as production-capable code for supply chain applications. This would be a good place for community members to chip in, irrespective of the additional generalization effort of going from [POC to Protocol](poc-to-protocol.md). 

An example of this is the code for the MSA, which you can find in the repo \[ here \]. Strictly speaking, the MSA is an 

