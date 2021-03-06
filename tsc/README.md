# TSC Materials for SOGNO

This directory contains the meeting notes, process documentations, and other materials related to this project.

## Project Intake checklist

This is a checklist for TSC's to review as part of the intake process. The TSC should review this entire list during the kickoff meeting. For anything outstanding, create an [issue](../issues) to track and link to it in the list

- Codebase
  - [x] Project license identified and exists in root directory of all repos ( named LICENSE )
  - [x] Code scan completed and any recommendations remedyed.
- TSC Record Keeping
  - [x] Location for TSC documents and meeting notes ( recommendation is ```tsc``` directory in main repo, and then ```meetings``` under the ```tsc``` directory )
  - [x] Copy this checklist to the above location for tracking
- Existing Project Governance
  - [x] README.md file exists ( template started at [README.md](../README.md) )
  - [ ] Any third-party components/dependencies included are listed along with thier licenses ( example template at [THIRD_PARTY.md](../THIRD_PARTY.md) )
  - [x] Governance defined, outlining community roles and how decsions are made ( starting point at [GOVERNANCE.md](../GOVERNANCE.md) if needed ).
  - [x] Contribution Policy defined ( CONTRIBUTING.md )
  - [x] Code of Conduct defined ( default is at [CODE_OF_CONDUCT.md](../CODE_OF_CONDUCT.md) - if using a different code of conduct please contact [LFE Staff](mailto:operations@lfenergy.org) ).
  - [ ] Release methodology defined ( [RELEASE.md](../RELEASE.md) )
- New Project Governance
  - [ ] TSC members identified, added to [GOVERNANCE.md](../GOVERNANCE.md).
  - [x] First TSC meeting held ( [agenda](meetings) )
  - [ ] TSC meeting cadence set and added to project calendar (https://lists.lfenergy.org/calendar)
- Infrastructure
  - [x] Source Control (Github, GitLab, something else ) and LFE Staff is an administrator.	
    - [x] Developer Certificate of Origin past commit signoff done and DCO Probot enabled.
  - [x] Issue/feature tracker (JIRA, GitHub issues)	and LFE Staff is an administrator.
  - Collaboration tools 
    - [x] Mailing lists - one of: 
      - [x] Create new list(s) ( default is -discussion@ and -private@ - create [service desk request] to provision ) 
      - [ ] Move to groups.io ( create [service desk request] to setup/transfer )
    - [ ] Establish project calendar on groups.io ( refer to [tac guidelines])
    - [x] Slack or IRC ( create [service desk request] to setup Slack project channel )
  - [x] Website ( refer to [tac guidelines] )
  - [ ] CI/build environment	
 	- [ ] Add project to [Dev Anayltics](https://lfanalytics.io/projects/lf-energy) ( create [service desk request] to trigger )
- Project assets
  - [ ] Domain name	( create [service desk request] to setup/transfer )
	- [ ] Social media accounts	( create [service desk request] to setup/transfer )
	- [x] Logo(s)	( create [service desk request] to create]; will be added to [artwork repo](https://artwork.lfenergy.org) in SVG and PNG format and color/black/white )
	- [ ] Trademarks/mark ownership rights ( complete [LF Projects - Form of Trademark and Account Assignment](lf_projects_trademark_assignment.md) )
- Outreach
  - [ ] New project annoucement done ( create [service desk request] to trigger )
  - [ ] Project added to LF Energy website and LF Energy landscape
- Early Adoption requirements  
  - [ ] CII Badge achieved ( apply at https://bestpractices.coreinfrastructure.org/en )
  - [x] Elect TSC Chairperson
  - [x] Regular cadence of TSC meetings being held.
  - [x] Governance defined at [GOVERNANCE.md](../GOVERNANCE.md).
  - [ ] Used in production by 2 organizations ( identify in [ADOPTERS.csv](../ADOPTERS.csv) )
  - Growth plan
    - [ ] Growth plan created ( put in [growth-plan.md](growth-plan.md))
    - [ ] Growth plan submitted to TAC ( create [tac issue] to request - link to [growth-plan.md](growth-plan.md)
    - [ ] Growth plan approved by TAC ( link to meeting minutes or email thread )
	- [ ] Commit/Contribution growth during incubation
  - [ ] Schedule presentation to TAC
  - [ ] TAC approval (2/3 required)
- Graduated Project requirements	
  - [ ] TSC established with 5+ members, with no more than 1/2 of members at the same organization.
  - [ ] Release/Testing process defined ( [RELEASE.md](../RELEASE.md) )ocumented zCommitters defined in the project	( [COMMITTERS.csv](COMMITTERS.csv) or [COMMITTERS.yml](COMMITTERS.yml) )
  - [ ] Maintainers/committers from at least 2 organizations.
  - [ ] Schedule presentation to TAC
  - [ ] TAC approval (2/3 required)

[service desk request]: https://github.com/lf-energy/foundation/issues/new/choose
[tac guidelines]: https://github.com/lf-energy/tac 
