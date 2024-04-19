# SMT-based-Formal-Verification-for-Smart-Contracts
A SoK student paper on SMT based formal verification of smart contracts

This paper represents the state of October 2023. 

## Abstract
Smart Contracts are programs that run on a blockchain. One of their main purposes on public blockchains like Ethereum is asset management. Since their byte code, if not their source code, is public their correctness is of uttermost importance. To formally prove their correctness, while keeping the workload as low as possible, SMT-based formal verification tools came up in recent years, that prove given specifications automatically with SMT-solvers. Although these tools differ in their capabilities and limitations, no resource points out and categorizes these differences. This paper attempts to picture the state-of-the-art by categorizing and comparing all existing tools. The tools are compared with regard to completeness, in the sense of limits and the complexity of specifications that can be proved, and with regard to optimization, in the sense of preprocessing of specifications and smart contract code to allow for faster verification through SMT-solvers. Thus giving an overview of how formal verification with certain tools is to judge, which tool to use to formally verify one’s project and most importantly which research challenges remain open.

## Details
We take a look at tools that follow a complete approach (i.e. no overestimating as in e.g. Static Analysis). These tools are best to our knowledge: the SMT-Checker, solc-verify, the Certora prover, and the Move Prover. 
the tools are evaluated and later compared with regard to completeness, in the sense of completeness-limits of the tools(e.g. loop-verification) and expressiveness of specifications they allow, and optimizations they implement to facilitate faster and better results.
