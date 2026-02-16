# UK TRE Glossary: principles, editorial process and code of conduct

[![Build](https://github.com/manics/uktre-glossary/actions/workflows/workflow.yml/badge.svg)](https://github.com/manics/uktre-glossary/actions/workflows/workflow.yml)
[![readthedocs](https://app.readthedocs.org/projects/uktre-glossary/badge/?version=latest)](https://uktre-glossary.readthedocs.io/)

## Purpose

To create an overarching glossary capturing terminology across secure data and trusted research environments in the UK that will contribute to an interoperable, federated data landscape.

AND

To formalise an editorial process for updating and revising the UK TRE Glossary.


## Principles

_Most of these principles can be found in the WG Charter. _

We include:
 * terms related to infrastructure and architecture, data processing, ingress and egress;
 * terms related to legal, governance and sensitive data management. 

We exclude:
 * discipline-specific data terminology (e.g. health, administrative, social services or financial);
 * “proper names”, explicitly named TREs, services, sites or software tools such as WorkflowHub or IBM DB2.

We aim for:
 * Brevity and succinctness in definitions.
 * Accessibility and comprehensibility for multiple audiences.
   * We will use plain language and keep jargon to a minimum.
   * We will hyperlink jargon terms to their definitions.
   * We will illustrate with examples where they add clarity.
   * We will point to external, in-depth sources where appropriate.


## Glossary elements

The UK TRE Glossary is composed of three elements: schema; category vocabulary; and content. The editorial process described below can be applied to changes to any of these elements.

### Glossary schema

The current (v1.x) schema is:

| Term | Tags | Definition |
| :--- | :--- | :--- |

 * Term: the term to be defined.
 * Tags: the category under which the term sits
 * Definition: the definition of the term (as concise as possible!). A minimal structure for Definition was agreed at the 19/08/2024 meeting (see also “Glossary content” below).

### Category vocabulary

Currently (v1.x) the Glossary uses manually applied free-text tags which the Working Group Chairs try to keep neat and tidy.

At a later stage, an information classification system (i.e. ‘category vocabulary’) will be considered by the Working Group. The purpose of a category vocabulary would be to classify Glossary terms to a category, or categories where relevant. A formal classification scheme may be useful in enabling federation and interoperability, particularly where data sharing or data querying across TREs requires an ontology to facilitate coding or machine learning to (semi-)automate processes.  


### Glossary content

The term definitions themselves.

We adopt the following structure for Definitions:
 * Definition text (text; a few sentences maximum).
   * Aim for brevity; keep public-friendliness in mind.
   * Use British English (en_GB).
   * If the definition uses a term from elsewhere in the Glossary, [bracket it] like this so it can be hyperlinked later.
 * Examples (text; optional, but if examples of usage add clarity, add them here)
 * See also (URLs; links to both glossary-internal and external terms, sources etc.)
   * \[Bracket references\](url) in Markdown link format for later hyperlinking
   * Do not repeat links already embedded in the Definition (see above).



## Editorial process

### Glossary management

The source of the TRE Glossary is maintained at [GitHub](https://github.com/uk-tre/glossary). Proposed changes are recorded as GitHub _issues_ 
and managed through the [UK TRE Glossary WG tracker](https://github.com/orgs/uk-tre/projects/2).


### Proposing changes

There will be a formal, quarterly amendment meeting to review any new definitions and any amendments to existing definitions (or possibly removing definitions if they are no longer relevant). Amendments can be proposed:
 * via the mailing list;
 * via GitHub issues;
 * via a form linked to the Glossary, which allows any interested party to suggest a change. 

Likewise, any new glossaries identified would also be reviewed for terms and definitions to be included.

The change process will be the same, vis:

Items requiring discussion will be tabled for the next member group meeting. Such items in question could be: reviews of proposed definitions; suggestions or amendments; agreements on a standard definition where multiple options exist; etc.

Resolution of items in question will be by an informal consensus vote at the meeting.

Where the meeting cannot achieve consensus, the item in question will be put to a formal yes / no vote. 

If there is a majority yes, the item in question is resolved.

If there is a ‘no’ then the item in question must go back to a group meeting for further discussion and the reason for no must be addressed by the members so that a consensus can be reached.

### Consensus

For the purposes of this WG, 'consensus' is defined as a ‘general agreement amongst a group of people’. Consensus is not ‘full agreement’ -- we aim to achieve an agreement on term definition that WG members can ‘live with’ without significant objection. Following processes in place within the TRE Community (see: Consensus, Review and Objection Management - Google Docs), the Glossary WG will work to the same principle of ‘lazy consensus’, that is, unless objections are raised within the community to the initiative in question within a defined time period, it will be approved.

Where objections or questions have been raised regarding term definitions, etc., Glossary WG members will have discussions via the glossary mailing List. Issues will also be tabled for the next member group meeting. Such items in question could be: reviews of proposed definitions; suggestions or amendments; agreements on a standard definition where multiple options exist; etc.
 
Resolution of items in question will be by consensus at the meeting. There is no quorum per se, but where subject matter experts are required but cannot attend, it may be the case that the discussion will be tabled to a subsequent meeting.

Where a subsequent meeting (or meetings) cannot achieve outright consensus, it falls to the co-chairs to make a final determination of rough consensus: the positions have been debated and while we do not have complete agreement, we have enough to move forward with a resolution that everyone can live with.

NB. One possible determination in the case of competing definitions is that both definitions are valid in different contexts, and that both should be present in the glossary with notes explaining the different contexts. While not ideal in a glossary, this may be where consensus can be found.

### Role of WG Chairs

The role of the WG Chairs is not a decision-making role (or a ‘tie breaker’ role). The Chairs' responsibilities are to ensure all WG members' views are heard and to act as mediators where there are outlying members that are unable to come to consensus. The Chairs will facilitate discussions and suggestions to resolve any objections that mean that consensus cannot be met.

The Chairs’ approach is inspired by the IETF approach to consensus (RFC 7282, https://datatracker.ietf.org/doc/html/rfc7282).

### Versioning

All changes to the TRE Glossary will be documented via version control.

For additional glossary inclusion after the first pass Glossary is created, a survey to the UK TRE Community could be sent asking members to provide a URL of any organisational glossaries (excluding data dictionaries and discipline-specific common data models, such as OMOP). If organisations maintain an internal glossary not published, we will request that they send these to the Glossary Working Group email for collation by the Discovery workstream. The Discovery workstream could also undertake additional desk research to identify any further glossaries made publicly available not supplied by TRE Community members.

Collated glossaries will be reviewed initially via the Discovery workstream for suitability to be considered (e.g. that they sit within the scope defined within the Glossary Working Group Charter). If appropriate for inclusion, the Discovery workstream will follow the Editorial process above.
