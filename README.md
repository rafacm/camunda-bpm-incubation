# camunda BPM incubation

camunda BPM incubation is a space for camunda BPM platform extensions and other projects around open source BPM. 
camunda BPM incubation projects are distributed under the [Apache License 2.0](http://www.apache.org/licenses/LICENSE-2.0).

## List of current Incubation Projects

None :)

## What is an Incubation Project?

At camunda, we want to support individuals and organizations that seek to contribute quality extensions to 
[camunda BPM platform](https://github.com/camunda/camunda-bpm-platform) or want to experiment with crazy new ideas around
BPM (Business Process Management). 

We provide
* guidance & support through a Sponsor, 
* Visibility inside the BPM community,
* Continuous integration through our Jenkins-based QA infrastructure,
* Publicly available snapshot builds through Maven / Nexus.

### What is a Sponsor?
A Sponsor is a [camunda BPM team member](http://www.camunda.org/community/team.html) who takes 
interest in the incubation project and provides guidance and assistance to the incubation project developer(s). 
The sponsor makes sure that the incubation project is heading in a direction in accordance with camunda's interests.

### What Technical Requirements do apply?
Each incubation project must fulfill a set of technical requirements: 
* Each incubation project has it's own folder inside the `camunda-bpm-incubation` repository.
* Each incubation project is a Maven project. The maven coordinates of the parent project are as follows:
  * Group ID: org.camunda.bpm.incubation
  * Artifact ID: camunda-incubation-root
  * Version: 7.0.0-SNAPSHOT
* Each incubation project has a README file that explains the scope and aim of the project.
* [Commit Message Conventions](https://github.com/camunda/camunda.org/blob/master/COMMIT_MESSAGES.md) must be respected.
* [Contribution Guidelines](https://github.com/camunda/camunda.org/blob/master/CONTRIBUTION_GUIDELINES.md) must be respected.


## How can I participate?

* Develop a crazy new Idea :)
* Build the smallest possible increment that illustrates your idea.
* *Propose* your project
  * Tell us about it on the mailing list: camunda-bpm-dev@googlegroups.com
  * Find a sponsor.
* *Incubate* your project
  * TODO: committer agreement??   
  * Submit a pull request to [camunda.org](https://github.com/camunda/camunda.org), providing 
    your picture and profile for the [Community / Team Page](http://www.camunda.org/community/team.html).
  * You get commit (push) privileges to the `camunda-bpm-incubation` repository.
  * Integrate your project (see [Technical Requirements](#what-technical-requirements-do-apply)).
* *Maintain* your project & collect feedback from the community.

Incubation projects that are well-received by the community and fit into the core BPM platform may eventually 
graduate into the top-level project.



