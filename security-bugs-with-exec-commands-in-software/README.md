# A Quick Story Of Security Pitfalls With Exec Commands In Software Integrations

## Description

When building software integrations, developers face important decisions that are influenced by time, budget, and the technologies they know and sometimes these decisions can lead to security vulnerabilities. This talk will look into the reasons developers might choose to run other programs directly from their code, rather than using libraries, SDKs or external APIs, and the security risks this choice can bring.

We will explore command injection attacks, a well-known security issue that remains a major threat. These attacks happen when our code directly runs other programs, leading to potential security breaches. Our discussion will cover the basic principles of how programs interact with each other and the tools we can use to understand these interactions.

By examining a real case of command injection vulnerability I found (CVE-2023-39059) in a popular open-source project. We will learn the methods, tools and techniques for finding and exploiting such vulnerabilities.

Finally, we will talk about ways to detect and prevent these kinds of attacks. We’ll discuss how to spot these vulnerabilities and the steps we can take to protect our software.

## Notes

This talk is based mainly on my original research documented here: <https://www.alevsk.com/2023/07/a-quick-story-of-security-pitfalls-with-execcommand-in-software-integrations/>

## Technical requirements

- basic knowledge of Linux and Operating Systems
- basic knowledge programming

## Who should attend

While there’s no minimum required experience to attend, this talk will best suited for:

- Software Engineers
- Security Engineers
- Cloud Engineers
- DevOps Engineers
- Incident response / penetration testers / hackers
- Any person that wants to learn more about vulnerabilities in source code
