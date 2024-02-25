# CODEGUARD

![Cactus by Zilvinas Kliucius](assets/zilvinas_kliucius_cactus.png)
Source: [Zilvinas Kliucius on fotocommunity](https://www.fotocommunity.com/photo/frame-8060-zilvinas-k/46334379)

The classical approach to software security outlined by Gary McGraw, John Viega, and Greg Hoglund in their seminal Software Security Series mandates the integration of all necessary security tasks into the software development process. According to this school of thought, software security rests on three pillars: applied risk management, software security touchpoints, and knowledge.

Software security touchpoints is a set of best practices adopted by leading software companies like Microsoft and government agencies like the U.S. Department of Homeland Security. These best practices are applied to various software artefacts during the software development lifecycle. Importantly, security touchpoints can be applied regardless of which base software process &mdash; waterfall, spiral development, agile &mdash; is being followed by the developers. 

Software artefacts which the security touchpoints focus on include system requirements and use case descriptions, software architecture, software design documents, test plans, code, various types of tests, and metrics collected in the field. The main idea of security touchpoints is to analyse these artefacts during the software development process. In the order of effectiveness, the touchpoints with their corresponding artefacts are:

1. Code review (code)
2. Architectural risk analysis (design and specification)
3. Penetration testing ( system with its environment)
4. Risk-based security tests (units and system)
5. Abuse cases (requirements and use cases)
6. Security requirements (requirements)
7. Security operations (fielded system)

Generative AI and, in particular, Large Language Models (LLMs) have the potential to revolutionise cybersecurity tasks across the software development lifecycle. Because LLMs are capable of analysing various software development artefacts like requirements and code, they can be used to increase the automation level of security touchpoints and, ultimately, maybe even fully automate some of them.

**CODEGUARD** is an open-source project aiming to build a collection of LLM-based tools for supporting and automating software security touchpoints. The tools should be easy to install, easy to use, and well-documented. Moreover, they should lend themselves for integration into CI/CD pipelines &mdash; in particular, integration into GitHub Actions &mdash; and be either self-contained (e.g., by using an open-source LLM provided together with the tool) or use popular LLMs like ChatGPT available via public APIs. 

## Sources

* John Viega, Gary McGraw "Building Secure Software", Addison-Wesley Software Security Series, 2002
* Greg Hoglund, Gary McGraw "Exploiting Software", Addison-Wesley Software Security Series, 2004
* Gary McGraw "Software Security", Addison-Wesley Software Security Series, 2006
