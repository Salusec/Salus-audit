# Salus-audit
![Image text](/pic/back.png)
Salus tackles the most complex security challenges through fundamental scientific research and pushing the boundaries of Web3 security.

## Audit Report
Report query portal:
[2024](/2024) | [2023](/2023) | [2022](/2022)

[Official website query entrance](https://salusec.io/audit-report)
## Speech

[Analysis-and-Auditing-of-ZKP-Vulnerabilities](https://ethcc.io/archive/Analysis-and-Auditing-of-ZKP-Vulnerabilities)

[Research on EIP Security Specifications](https://www.youtube.com/watch?v=iud7Kjl-11g&list=PLhM7rBgpVV-KN8mM17IRSFIGsL0EaGA_m)

## Research 

[EIP Security Analysis Application Program Standards Attack](https://dl.acm.org/doi/pdf/10.1145/3650400.3650609)

[Zero-Knowledge Proof Vulnerability Analysis and Security Auditing](https://eprint.iacr.org/2024/514)

[Security Analysis of Smart Contract Migration from Ethereum to Arbitrum](https://arxiv.org/pdf/2307.14773.pdf)

[Deep learning-based solution for smart contract vulnerabilities detection](https://www.nature.com/articles/s41598-023-47219-0)

[Important Security Checks Before Cancun Upgrade](https://salusec.io/blog/21_important-security-checks-before-cancun-upgrade)

## CTF
[Paradigm CTF 2023 No.9](https://ctf.paradigm.xyz/scoreboard) | [Ethernaut CTF 2024 No.5](https://github.com/OpenZeppelin/ctf-2024)

## Public Work
[Account Abstract Code Security Library](https://github.com/Mirror-Tang/Account-abstraction-coding-security-library) | [ZK Security Framework](https://github.com/Salusec/zksecurity-framework) | [Türkiye Earthquake DAO Charity Audit](https://github.com/connext/xDonations/blob/main/audits/SalusAudit.pdf)

##Risk Assessment Criteria
| Risk level  | Description |
| --- | --- |
| 🔴 High | The issue puts a large number of users’ sensitive information at risk, or is reasonably likely to lead to catastrophic impact for clients’ reputations or serious financial implications for clients and users. |
|🟡Medium | The issue puts a subset of users’ sensitive information at risk, would be detrimental to the client’s reputation if exploited, or is reasonably likely to lead to a moderate financial impact. |
| 🔵 Low | The risk is relatively small and could not be exploited on a recurring basis, or is a risk that the client has indicated is low impact in view of the client’s business circumstances. |
| ⚫ Info | The issue does not pose an immediate risk, but is relevant to security best practices or defense in depth. |

## Audit Scope
During the process of auditing smart contracts, we have identified the following common types of vulnerabilities. However, our auditing work is not limited to these types.

#### Common Vulnerabilities
| Category  | Description |
| --- | --- |
| Business Logic | Reviewing the logic to ensure that the code implements the expected functionality as specified in the documents. |
| Access Control | Assessing and managing the mechanisms in place to regulate and restrict user access to resources, systems, or information based on predefined permissions and privileges. |
| Data Validation | Evaluating the mechanisms of the smart contract for validating and verifying the integrity and correctness of the data it relies on. |
| Numerics | Handling and processing numerical values and calculations accurately and efficiently, considering potential limitations, precision issues, and rounding errors associated with different data types and arithmetic operations. |
| Reentrancy | Addressing vulnerabilities that could allow an attacker to reenter a function or contract before the previous execution has completed, potentially leading to unintended consequences or malicious action. |
| Cryptography | Implementing secure cryptographic algorithms and protocols to protect sensitive data, ensuring confidentiality, integrity, and authentication in various applications and systems. |
| Denial of Service | Identifying and mitigating vulnerabilities that could lead to a Denial of Service attack, which aims to disrupt or incapacitate a system, network, or service, rendering it unavailable to legitimate users. |
| Upgradeable | When using the proxy pattern in upgradable contracts, there may be security risks. Ensure that appropriate security measures are taken when implementing the proxy pattern to prevent malicious attacks or contract takeover. |
| Inconsistency | Inconsistency focuses on identifying and resolving inconsistencies, disparities, or discrepancies between documented specifications, guidelines, or instructions and the actual implementation of a system, software, or process. |
| Front-running | Identifying and addressing vulnerabilities that allow malicious actors to exploit privileged information, typically in decentralized financial applications, to gain unfair advantages in transactions or trades. |
| Weak Randomness | Identifying and addressing vulnerabilities that depend on the randomness of deterministic variables. |
| Centralization | Assessing and mitigating risks associated with centralization of data, control, or authority in systems or organizations, considering potential single points of failure or vulnerabilities. |
| Configuration | Managing and maintaining the configuration settings and parameters of a system or application, including customization options, environmental variables, and external dependencies, to ensure optimal performance and functionality. |
| Variable Shadowing | Using the same name for variables in different functions or inherited contracts can lead to conflicts and hidden variables, resulting in unexpected execution behavior. |
| Compiler | Identifying and addressing vulnerabilities that depend on compiler version. |
| Logging | Implementing a system that captures and records relevant events, actions, and errors occurring within an application or system, facilitating troubleshooting, auditing, and analysis of system behavior |
| Gas Optimization | Suggestions for reducing gas costs. |
| Code Quality | Assessing and improving the overall quality, readability, maintainability, and efficiency of the software codebase through practices like code reviews, adherence to coding standards, and the use of automated analysis tools. |














