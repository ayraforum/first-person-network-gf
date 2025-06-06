---
description: Primary Document for the First Person Network Governance Framework
---

# Primary Document

## Introduction

This is the primary document for the ecosystem governance framework for the First Person Network. It defines the governing and administering authorities; the overall purpose and scope of the framework; the stakeholders and their objectives in developing this framework; and how it will be extended and revised as needed over time. It includes a schedule of the additional controlled documents that define more specialized business, governance, and technical policies for the First Person Network.

## Terminology & Notation

All terms used in this document that apply generally to decentralized digital identity and trust infrastructure are defined in the [ToIP Glossary](https://glossary.trustoverip.org/).

All terms specific to this governance framework are specified in the Glossary—see the [Schedule of Controlled Documents](https://docs.google.com/document/d/1db3fk7vJzd8uHlcsM6zVKpY3zVks34MZf1sKlXaOL3k/edit?tab=t.0#heading=h.gfdof476ws4i).&#x20;

Specific terms used to specify conformance criteria are defined in the next section.

## Localization

1. The official language of the First Person Network Governance Framework SHALL be American English.
2. The First Person Network Association SHALL make localized versions of the First Person Network Governance Framework available in the languages of First Person Network members once available resources permit.

## Governing Authority

The governing authority for the First Person Network SHALL be the First Person Network Association (FPNA).

## Administering Authority

The First Person Network does not have a separate administering authority; the FPNA shall also serve as the administering authority.

## Purpose

The primary purpose of the First Person Network is to empower natural persons to establish and maintain strong, private personal trust relationships with any other party: people, groups, communities, organizations, and governments. These trust relationships form a decentralized trust graph that enables members to issue, hold, and verify First Person credentials, including privacy-preserving proof of personhood, without the need to rely on a third-party platform, social network, or blockchain. The secondary purpose of the First Person Network is to enable members to engage in trusted communications, data sharing, digital signatures, and other trust tasks in which members can be confident that their security, privacy, and sovereignty is being respected.

## Principles

The first principle of First Person infrastructure is that the interests of individual natural persons must always be put first.

The second principle is that every design decision should be measured by how much it empowers: 1) individuals to make personal trust decisions and  establish and maintain personal trust relationships, and 2) trust communities to make group trust decisions and establish and maintain group trust relationships.&#x20;

The following additional principles are inherited and adapted from the Ayra Principles.

<table data-header-hidden><thead><tr><th width="212.84375"></th><th></th></tr></thead><tbody><tr><td><strong>Transparent by Default</strong></td><td>The FPNA shall follow transparent processes whenever possible, communicating the “who”, "when", "why" of how decisions are reached, in order to engender trust both among members and with the larger community.</td></tr><tr><td><strong>Equitable Participation</strong></td><td>The FPNA shall be open to all parties who have a direct stake in its mission; it shall give equitable representation to all such stakeholders; and it shall not give preference to any single stakeholder or group of stakeholders.</td></tr><tr><td><strong>Nonprofit</strong> </td><td>The FPNA shall be a nonprofit steward of First Person infrastructure that will provide services at cost to its members and the broader community. It will be self-sustaining through revenue streams that are consistent with these Principles.</td></tr><tr><td><strong>Non-competitive</strong></td><td>The purpose of the FPNA is to solve problems and provide infrastructure that no member can adequately or fairly provide alone. If a member or a group of members can provide a function consistent with the policies of the First Person Network Governance Framework as or more efficiently and effectively as the FPNA, that function should be left to the members.</td></tr><tr><td><strong>Inclusive &#x26; Diverse</strong></td><td>Membership in the FPNA shall be open to all parties in the defined member classes. Governance of the FPNA shall foster inclusivity and seek to serve a highly diverse membership of individuals and organizations of all sizes, locations, industries, and use cases.</td></tr><tr><td><strong>Independent &#x26; neutral</strong></td><td>As an organization and as an infrastructure, the FPNA shall serve as a neutral independent party serving all members equally and showing favor towards none.</td></tr><tr><td><strong>Respect sovereignty</strong></td><td>The FPNA shall respect the sovereignty of all members.</td></tr><tr><td><strong>Ensures individual sovereignty and solidarity</strong></td><td>Design, governance, and operation of First Person Infrastructure shall ensure that individuals are first-class peers with all other stakeholders and that their rights to security, privacy, portability, and agency over their personal data and digital assets are always protected.</td></tr><tr><td><strong>Protects security and privacy</strong></td><td>The design and operation of First Person infrastructure shall protect and promote the security and privacy of member data.</td></tr><tr><td><strong>Decentralized</strong></td><td>First Person infrastructure shall facilitate direct peer-to-peer relationships between members and enable the private permissioned exchange of verifiable data only between <a href="https://www.identityblog.com/?p=352">justifiable parties</a>. </td></tr><tr><td><strong>Agile and chaordic</strong></td><td>As a governing body, the FPNA shall be as lean, simple, and decentralized as possible—following Dee Hock’s <a href="https://chaordic.io/blog/what-is-in-a-name/">principles for chaordic organizations</a>.</td></tr><tr><td><strong>Standards-based</strong></td><td>The FPNA infrastructure will be based on open standards and conformance profiles for maximum interoperability. <a href="https://open-stand.org/infographic-the-5-core-principles-of-openstand/">See the Open Stand Principles</a>.</td></tr></tbody></table>

## Scope

The First Person Network is a digital trust ecosystem-of-ecosystems that encompasses the business, governance, and technical policies necessary for members to design, develop, test, deploy, and maintain First Person digital wallets, digital agents, digital credentials, digital services and other First Person infrastructure necessary to achieve its purpose.

This Community Review version of the FPNGF is the starting point of a community-governed process that will culminate in the approval of the FPNGF V1. The Community Review version explicitly limits the scope to the immediate time frame, intentionally leaving some topics and policies for future versions.

### Stakeholders

1. **People.** Individual natural persons are the primary stakeholders at the heart of the First Person Network.
2. **Trust communities of any kind.** This category includes:
   1. Informal groups and communities.
   2. Nonprofit legal organizations.
   3. For-profit legal organizations.
   4. Governmental organizations.
3. **First Person infrastructure providers.** This category includes developers, open source projects, NGOs, companies, or governments that offer software or services to First Person Network Members that implement First Person infrastructure according to the requirements in this governance framework. It specifically includes providers of First Person agents or First Person services (see Roles).

### Roles

1. **PHC issuer:** A trust community that issues a personhood credential (PHC) in accordance with this governance framework.
2. **PHC oracle:** A system that consumes and verifies verifiable data in order to generate and issue a PHC in accordance with this governance framework. For example, a system may consume a government-issued mDL or other identity verification credential and generate a PHC at a given level of assurance.&#x20;
3. **PHC holder:** An individual FPN Member who has been issued a PHC.
4. **VRC issuer:** An individual or trust community that issues a verifiable relationship credential (VRC) in accordance with this governance framework.
5. **VRC holder:** A FPN Member who has been issued a VRC.
6. **FPC oracle:** A system that consumes and verifies PHCs and VRCs in order to generate a First Person credential (FPC). Note that an FPC oracle is only needed if a First Person agent is not able to directly generate a zero-knowledge  FPC proof in accordance with this governance framework.
7. **FPC holder:** An individual FPN Member who has been issued a FPC or whose First Person agent is able to generate an FPC proof..
8. **FPC verifier:** A verifier that requests an FPC proof as defined in this governance framework.
9. **First Person agent provider:** A First Person infrastructure provider who provides agent and wallet technology in accordance with this governance framework. First Person agents may run at the network edge (mobile device) or cloud (server) level.&#x20;
10. **First Person service provider:** A First Person infrastructure provider who provides communications, data storage, recovery, and other services to FPN Members in accordance with this governance framework.  This includes mediators, intermediaries, notification services, wallet-attached storage providers, etc.

### Future Work and Out of Scope

This Community Review version of the First Person Network Governance Framework is intended to lay the foundation for the eventual V1 production version. As such, it leaves a number of topic and policy areas out of the initial scope.&#x20;

Topics where additional work in scope for V1 are marked like this:

| <mark style="background-color:yellow;">TODO FOR V1: \<comment here></mark> |
| -------------------------------------------------------------------------- |

Topics where future work is needed beyond V1 are marked like this:

| <mark style="background-color:green;">FUTURE WORK (BEYOND V1): \<comment here></mark> |
| ------------------------------------------------------------------------------------- |

The following topics are explicitly out of scope for V1:

1. Vouching.
2. Community-relative trust scores.

Additional discussion of future work will continue on Gitbook[^1].

## Objectives

1. **Trust relationships.** The primary objective of the First Person Network is to empower all FPN Members to establish and maintain trust relationships and to confidently make trust decisions about their interactions with other FPN Members.
2. **Privacy-preserving proof of personhood.** The First Person Network should enable any FPN individual member to provide proof of personhood at an assurance level defined in this governance framework without sharing unnecessary personal data.
3. **Privacy-preserving verifiable credentials.** The First Person Network should enable individual members to share privacy-preserving proofs of other verifiable credentials as needed in a particular trust relationship.&#x20;
4. **Private data sharing.** The First Person Network should enable FPN members to share data with confidence about its authenticity and confidentiality.
5. **Private communications.** The First Person Network should enable FPN members to communicate privately.
6. **Other trust tasks.** The First Person Network should enable FPN members to perform other trust tasks, such as [the examples listed in the ToIP Technical Architecture Specification](https://trustoverip.github.io/TechArch/#example-use-cases), that meet the needs of members, either within a specific trust community or across trust communities..

## General Requirements

1. **Publication.** The First Person Network Association MUST publish the First Person Network Governance Framework at [https://fpngf.ayra.forum](https://fpngf.ayra.forum) and follow the policies in the Revisions section for all revisions of this governance framework. If the primary location of the FPNGF changes, the location referenced SHALL be updated.
2. **Regulatory compliance.** FPN Members operating under this governance framework SHALL comply with applicable legal regulations.
3. **Code of Conduct.** The First Person Network Association SHALL create, maintain and enforce a Code of Conduct.
4. **Privacy and data minimization.** All parties to a First Person trust relationship SHALL respect the other party’s privacy rights and will follow best practices for data minimization.&#x20;
5. **Sovereign control.** Either party to a trust relationship may sever it at any time.

## Revisions

1. At minimum, the FPNGF SHALL be reviewed annually.
2. Revisions to the Primary Document are subject to the following policies:
   1. All revisions to the Primary Document MUST be identified with a revision number that is a sequential integer.
   2. Revisions to the Primary Document SHALL be subject to public review at the Ayra Foundation, by members of the First Person Network and Ayra communities, for at least 30 days.
   3. Any substantive inputs received during the review period SHALL be dispositioned in a public record.&#x20;
   4. Inputs received will be dispositioned and receive a disposition status of:
      1. Accepted - the comment is incorporated into the standard
      2. Rejected - the comment is not accepted, with reasons provided
      3. Accepted in principle - the underlying concern is addressed, but perhaps in a different way than suggested
      4. Partially accepted - some aspects of the comment are incorporated
      5. Editorial - minor changes for clarity or consistency

[^1]: DECISION - move discussions (and issues) to github? Consider basic comments here - that are pushed to Discussion or Issue as appropriate.&#x20;
