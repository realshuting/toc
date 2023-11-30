# Kyverno Graduation Proposal

_**Insert introduction. See previous proposals for examples. This section should address from a broad perspective why the project feels they are ready to graduation and can state any major accomplishments or milestones.**_

Kyverno, an open-source project that was accepted as a CNCF Sandbox project in November 2020, and became Incubation in July 2022. Kyverno itself has 4,600+ [GitHub stars](https://github.com/kyverno/kyverno) and 358 [contributors](https://kyverno.devstats.cncf.io/d/52/new-contributors-table?orgId=1&from=now-5y&to=now&var-repogroup_name=kyverno) and 2,500+ members registered for the [Kyverno community Slack](https://main.kyverno.io/community/#slack-channel).

## Introduction

[Kyverno](https://kyverno.io/) is a Kubernetes policy engine that was created to validate, mutate, generate, and cleanup Kubernetes resources, and verify image signatures and artifacts to help secure the software supply chain. Kyverno policies are managed as Kubernetes resources and no new language is required to write policies.

## Graduation State Criteria

### * Have committers from at least two organizations.

Kyverno has maintainers from 4 different companies, see [maintainers.md](https://github.com/kyverno/kyverno/blob/main/MAINTAINERS.md).

1. Nirmata
2. Stackwatch (Kubecost)
3. Giant Swarm GmbH
4. Ohio Supercomputer Center

### * Have achieved and maintained a [Core Infrastructure Initiative Best Practices Badge](https://bestpractices.coreinfrastructure.org/).

Kyverno has achieved an [OpenSSF Best Practices Badge](https://www.bestpractices.dev/en/projects/5327).

### * Have completed an independent and third party security audit with results published of similar scope and quality as [this example](https://github.com/envoyproxy/envoy#security-audit) which includes all critical vulnerabilities and all critical vulnerabilities need to be addressed before graduation.


Kyverno completed a [fuzzing security audit](https://kyverno.io/blog/2023/09/06/kyverno-completes-fuzzing-security-audit/) and a thorough [third-party security review](https://main.kyverno.io/blog/2023/11/28/kyverno-completes-third-party-security-audit/). The security review is being conducted in collaboration with the [CNCF](https://www.cncf.io/), [Ada Logics](https://adalogics.com/) and [OSTIF](https://ostif.org/). 


### * Explicitly define a project governance and committer process. The committer process should cover the full committer lifecycle including onboarding and offboarding or emeritus criteria. This preferably is laid out in a GOVERNANCE.md file and references an OWNERS.md file showing the current and emeritus committers.

The Kyverno project governance policies are documented in [GOVERNANCE.md](https://github.com/kyverno/kyverno/blob/main/GOVERNANCE.md).

The committer process in Kyverno is defined in project roles [Contributors](https://main.kyverno.io/community/#contributors) and [Code Owners](https://main.kyverno.io/community/#code-owners) documents, which includes the full committer lifecycle, onboarding, offboarding, and emeritus criteria. The committers are listed in [OWNERS.md](https://github.com/kyverno/kyverno/blob/main/OWNERS.md).


### * Explicitly define the criteria, process and offboarding or emeritus conditions for project maintainers; or those who may interact with the CNCF on behalf of the project. The list of maintainers should be preferably be stored in a MAINTAINERS.md file and audited at a minimum of an annual cadence.

The project role [maintainers](https://main.kyverno.io/community/#maintainers) covers the criteria, process, offboarding and emeritus conditions. Maintainers may be removed if they made less than 30 contributions over a span of 6 months, those removed will be moved to an emeritus status.

The current maintainers list can be found in [MAINTAINERS.md](https://github.com/kyverno/kyverno/blob/main/MAINTAINERS.md).

### * Have a public list of Project adopters for at least the primary repo (e.g., ADOPTERS.md or logos on the Project website). For a specification, have a list of adopters for the implementation(s) of the spec. Refer to [FAQs](https://github.com/cncf/toc/blob/main/FAQ.md#what-is-the-definition-of-an-adopter) for guidelines on identifying adopters.

There is a list of organizations and users that have publicly shared how they are using Kyverno, see [ADOPTERS.md](https://github.com/kyverno/kyverno/blob/main/ADOPTERS.md).

## Incubation Details

### * Link to Incubation Due Diligence(DD) Document

* [Incubation proposal](https://github.com/cncf/toc/pull/784)
* [Incubation Due Diligence](https://docs.google.com/document/d/18dWgOd2MUQz3RXI1R9vKntL3ULyZhOD1HEtijGOeaWg/edit#heading=h.amgfsmvtn6jy)

### * Address any concerns or recommendations from the TAG and/or TOC sponsor(s) from the DD Document