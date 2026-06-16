# Software health check

This health check is meant to quickly scan a research software repository. It is not meant as an exhaustive audit report or evaluation tool, 
but it may serve as the basis for a conversation about various aspects of software sustainability.

**Name of the software**: ___________

## 1. Findability & identity

_Can people find, understand, and cite this software?_

**What does this software do, and where can people find it?**
_Suggestions: repository URL, project website, README summary_

&nbsp;

&nbsp;

**How should this software be cited, and is the metadata accurate?**
_Suggestions: DOI via Zenodo or 4TU, SWHID, CITATION.cff, CodeMeta_

&nbsp;

&nbsp;

**Where is this software discoverable beyond its own repository?**
_Suggestions: Research Software Directory, bio.tools, package index, paper reference; for mature software: community registries, package managers_

&nbsp;

&nbsp;

## 2. Usability

_Can someone use this software without help from the authors?_

**How does a new user get started?**
_Suggestions: installation guide, README, worked example_

&nbsp;

&nbsp;

**Who is the intended audience, and is the documentation written for them?**
_Suggestions: user guide, tutorial, assumed prior knowledge stated_

&nbsp;

&nbsp;

**How do users get help when they are stuck, and how is that scaled as the user base grows?**
_Suggestions: issue tracker; for more advanced software: forum, mailing list, community channel, documented response expectations_

&nbsp;

&nbsp;

## 3. Correctness & reliability

_How do we know the software does what it claims, and keeps doing so?_

**How do you know the software does what it claims?**
_Suggestions: test suite, reference outputs, validation against known results, domain-specific benchmarks_

&nbsp;

&nbsp;

**How is correctness maintained as the software evolves?**
_Suggestions: changelog, version tags; for more active development: CI pipeline, automated tests on every commit, branch protection_

&nbsp;

&nbsp;

**Are there security or safety considerations, and how are they handled?**
_Suggestions: no leaked credentials in history; for software with external exposure: vulnerability scanning, security policy (SECURITY.md)_

&nbsp;

&nbsp;

## 4. Maintainability

_Can someone other than the original author understand and modify this code?_

**Could a new contributor navigate this codebase without asking the authors?**
_Suggestions: logical file structure, meaningful naming, code comments where reasoning is non-obvious, architecture notes_

&nbsp;

&nbsp;

**What does this software depend on, and how are those dependencies managed?**
_Suggestions: requirements file or package manager, pinned versions, documented dependencies on external APIs, services, or special hardware_

&nbsp;

&nbsp;

**How is the codebase structured for collaborative development?**
_More relevant as teams and contributor bases grow. Suggestions: module boundaries, API documentation, contribution guide, code review practice_

&nbsp;

&nbsp;

## 5. Stewardship

_Who is responsible for this software, under what terms, and what happens when circumstances change?_

**Under what terms can this software be used, modified, and built upon?**
_Suggestions: OSI-approved licence file, dependency licence compatibility_

&nbsp;

&nbsp;

**Who maintains this software, and how can others get involved?**
_Suggestions: named maintainers; for software seeking contributors: CONTRIBUTING.md, code of conduct, open governance model_

&nbsp;

&nbsp;

**What happens to this software when the current project or grant ends?**
_Most relevant for software with an established user base. Suggestions: institutional backing, roadmap, handover plan, bus factor assessment_

&nbsp;

&nbsp;
