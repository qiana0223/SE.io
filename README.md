## Repositories
#### [Approach Implementation](https://github.com/Qiana0223/wqp_app_1)
This is the repository hosting the code that implements an approach to making symbolic execution on Ethereum smart contracts more scalable.  The code is built on top of [Mythril](https://github.com/ConsenSys/mythril) and [Slither](https://github.com/crytic/slither)

#### [Experiment Related Code](https://github.com/Qiana0223/DataPreparation)
This is the repository containing the code to prepare for data for Singularity containerization based experiments and the code to extract experiment results.


## Papers
#### [Papers on Security and Testing of Ethereum Smart Contracts](https://github.com/Qiana0223/bibliography_security_testing_smart_contracts)
A bibliography of papers on security and testing of Ethereum smart contracts.


#### [Symbolic Execution Papers](https://github.com/XMUsuny/symbolic-execution-papers)
This repository is for collecting and grouping the symbolic execution papers and open source tools in recent years.

## Vulnerability Classifications
#### [Smart Contract Weakness Classification Registry (SWC)](https://github.com/SmartContractSecurity/SWC-registry)
The Smart Contract Weakness Classification Registry (SWC Registry) is an implementation of the weakness classification scheme proposed in [EIP-1470](https://github.com/ethereum/EIPs/issues/1469). It is loosely aligned to the terminologies and structure used in the Common Weakness Enumeration ([CWE](https://cwe.mitre.org/)) while overlaying a wide range of weakness variants that are specific to smart contracts.

The goals of this project are as follows:

Provide a straightforward way to classify security issues in smart contract systems.
Define a common language for describing security issues in smart contract systems' architecture, design, or code.
Serve as a way to train and increase performance for smart contract security analysis tools.


#### [Decentralized Application Security Project (DASP)](https://dasp.co/#item-9)
This is the very first iteration of the  Decentralized Application Security Project (or DASP) Top 10 of 2018

This project is an initiative of [NCC Group](https://www.nccgroup.trust/). It is an open and collaborative project to join efforts in discovering smart contract vulnerabilities within the security community. To get involved, join the [Github](https://github.com/CryptoServices/dasp) page.

## Benchmarks
#### [sGuard benchmark](https://github.com/duytai/sGuard/issues/22)
This is the benchmark used in the paper [SGUARD: Towards Fixing Vulnerable Smart Contracts Automatically](https://ieeexplore-ieee-org.ezproxy.uta.edu/stamp/stamp.jsp?tp=&arnumber=9519444). It contains 5000 contracts whose verified source
code are collected from EtherScan. The dataset can be downloaded from this [link]( https://drive.google.com/file/d/1xMa_9n4uf5Ssl3RDsXR6opN_wfRPEhdM/view?usp=sharing).

#### [SB Curated: A Curated Dataset of Vulnerable Solidity Smart Contracts](https://github.com/smartbugs/smartbugs/tree/master/dataset)
SB Curated is a dataset for research in automated reasoning and testing of smart contracts written in Solidity, the primary language used in Ethereum. It is part of the executional framework SmartBugs, which allows the possibility to integrate tools easily, so that they can be automatically compared (and their results reproduced). To the best of our knowledge, SmartBugs is the largest dataset of its kind.

#### [SmartBugs Wild Dataset](https://github.com/smartbugs/smartbugs-wild)
This repository contains 47,398 smart contracts extracted from the Ethereum network.
[SmartBugs](https://github.com/smartbugs/smartbugs) was used to analyze this dataset. The [results](https://github.com/smartbugs/smartbugs-results) are available, please see the ICSE 2020 paper.
#### [SolidiFI Benchmark](https://github.com/smartbugs/SolidiFI-benchmark)
SolidiFI-benchmark repository contains a dataset of buggy contracts injected by 9369 bugs from 7 different bug types, namely, reentrancy, timestamp dependency, uhnadeled exceptions, unchecked send, TOD, integer overflow/underflow, and use of tx.origin. The bugs have been injected in the contracts using SolidiFI.

#### [Smartian Benchmarks](https://github.com/SoftSec-KAIST/Smartian-Artifact/tree/main/benchmarks)
<hr>

#### [An Efficient and Trustworthy Theory Solver for Bit-vectors in Satisfiability Modulo Theories](https://cs.nyu.edu/media/publications/hadarean_liana.pdf)
 The predominant approach to deciding the bit-vector theory
is via eager reduction to propositional logic. While this often works well in practice, it
does not scale well as the bit-width and number of operations increase. The first part of
this thesis seeks to fill this gap, by exploring efficient techniques of solving bit-vector
constraints that leverage the word-level structure. We propose two complementary approaches: an eager approach that takes full advantage of the solving power of off the
shelf propositional logic solvers, and a lazy approach that combines on-the-fly algebraic
reasoning with efficient propositional logic solvers. In the second part of the thesis, we
propose a proof system for encoding automatically checkable refutation proofs in the
theory of bit-vectors. These proofs can be automatically generated by the SMT solver,
and act as a certificate for the correctness of the result.
