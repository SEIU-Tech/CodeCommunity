# SEIU Union-Wide Technology Sharing Resource

2025-10-17

## Purpose

This repository is intended as a means for SEIU technologists, both at the
International Union and within our locals to share narratives of our
experiences implementing solutions to union technology issues, and to share
code that we used in those implementations.

This repository is public and as liberally licenced as is possible.  However,
this specific repository is predominantly a navigational aid rather than the
direct host for much substantative.  The organization this repository belongs
to, [SEIU-tech](https://github.com/SEIU-Tech), may host additional
repositories itself.  The main focus, however, will be to include submodules
and links to repositories maintained by other organizations.  Those other
organization will include [SEIU](https://github.com/SEIU), but will mostly
include those of various SEIU locals (please contribute links or content). 

## Security Concerns

No confidential information will exist anywhere in this organization’s
repositories—nor in referenced submodules—but much of the content may be
restricted as each local finds appropriate to their needs and culture.
Specifically, [David Mertz, Ph.D.](mailto:david.mertz@seiu.org), Principal
Engineer of SEIU, will audit the SEIU-tech organization itself, and will offer
assistance to locals in auditing any content they expose via links and
submodules.

Using [git submodules](https://git-scm.com/book/en/v2/Git-Tools-Submodules) is
a good structure for contributors from varying organizations.  Specifically,
the git history of a submodule included in a project is separate from that of
the module that includes it.  This requires a bit of explanation.

Within a git repository, the entire history of changes is retained.  With
effort, it is possible to rewrite that history to exclude information that is
confidential or proprietary, but in general such information should never be
committed at all.  This is, of course, especially true of PII or access
tokens/passwords.

David Mertz will assume responsibility for monitoring any content placed in
SEIU-tech repositories; and will advise locals on how to maintain the same
level of data hygiene within their repositories.  Commits to SEIU-tech
repositories will require pull requests from "feature branches" and approval
by moderators.

## Linked Resources

As a first pass at this README, this union-wide resource could have something
like the following organization, using submodules

* GitHub:SEIU-tech/CodeCommunity
  - submodule GitHub:Local999/MemberCanvasing (private code and documents created by local 999)
  - submodule GitHub:Local888/DataCleaning (public code shared by local 888 for open re-use)
  - submodule GitHub:SEIU/ContractBot (public repository for standing up secure internal LLMs)

In the example provided, Local999 and Local888 have complete control over
content and access permissions to their linked submodules.  The SEIU-tech
organization, in essence, does nothing more than link to those other
resources.  A specific person (from anywhere) might be able to access some,
but not all, such linked submodules.

Including a submodule within a project or repository is equivalent to
including a hyperlink, as one might on a web page. The International Union
would not, and could not, control what exists in a submodule that we do not
ourselves own—although some we will, such as the actual open source
ContractBot code project we’ve made public. 

Once we get this rolling, we'll substitute the actual links to wondeful
projects and narratives by locals for the hypothetical example shown above.

## Directly Included Resources

### Documents and presentations

* [Unicode: When nothing is anything else](docs/Unicode-matching.pdf)

### Sample source code
