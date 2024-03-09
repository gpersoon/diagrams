# Diagrams for Solidity contracts

## Why Diagrams

Effective way to get information into brain
- Use more senses
- Reduce load on short term memory
- Remember the protocol when revisiting it later
- Reduce initial information overload

Overview of protocol
- See complexity 
- Recognize patterns 
- Spot inconsistencies

Flexible
- Start with incomplete code
- Print and write on paper
- Develop top down

## How to use

Start by downloading and opening the [template](DiagramTemplate%20V1.0.pptx) in Powerpoint.
- copy a (blue) box for each smart contract;
- in multi chain protocols (e.g. bridges) copy purple boxes for each chain;
- add nested blue boxed, with increasingly darker blue for inherited contracts and used libraries;
- copy yellow boxes for each external (dark yellow) / internal (dotted line) / view (light yellow ) function;
- draw arrows from each function to all contracts/functions it calls;
- use yellow/transparant boxes to cluster/group functions, for example with the same modifier;
- simplify and reduce crossing lines by connecting arrows to clusters and by rearranging boxes;
- optionally add dark purple boxes for storage variables;
- optionally add fat dotted lines for token flows;
- create as many pages as useful.

## Template image

![DiagramTemplate V1 0](https://github.com/gpersoon/diagrams/assets/5469459/90e54796-2bed-494c-8131-5181d337a7c4)
