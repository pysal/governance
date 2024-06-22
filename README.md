PySAL Project Governance
========================

The purpose of this document is to formalize the governance process used
by the PySAL project in both ordinary and extraordinary situations, and
to clarify how decisions are made and how the various elements of our
community interact, including the relationship between open source
collaborative development and work that may be funded by for-profit or
non-profit entities.

The Project
------------

PySAL, the Python Spatial Analysis Library, is an open source
cross-platform project (hereinafter referred to as "The Project"). The
goal of The Project is to develop open source software for geospatial
data science in Python, in particular the PySAL library, containing the
pysal Meta-Package and its component Sub-Modules (hereinafter referred
to as "Packages"). The software developed by The Project is released
under the BSD (or similar) open source license, developed openly and
hosted on public GitHub repositories under the pysal GitHub
organization.

The Project is developed by a team of distributed developers
(hereinafter referred to as "Contributors"). Contributors are
individuals who have contributed code, documentation, designs or other
work to The Project. Anyone can be a Contributor. Contributors can be
affiliated with any legal entity or none. Contributors participate in
the project by submitting, reviewing and discussing GitHub Pull Requests
and Issues and participating in open and public Project discussions on
GitHub, Gitter, and other channels. The foundation of Project
participation is openness and transparency.

The Project Community consists of all Contributors and users of the
software developed by Contributers in The Project (hereinafter referred
to as "Users"). Contributors work on behalf of and are responsible to
the larger Project Community and we strive to keep the barrier between
Contributors and Users as low as possible.

The Project is not a legal entity, nor does it currently have any formal
relationships with legal entities.

Governance
----------

This section describes the governance and leadership model of The
Project.

The foundations of Project governance are:

-   Openness & Transparency
-   Active Contribution
-   Institutional Neutrality

Traditionally, Project leadership was provided by a Benevolent Dictator
for Life (BDFL: Sergio Rey) and a subset of Contributors and Package
Maintainers, called Core Developers, whose active and consistent
contributions have been recognized by their receiving “commit rights” to
the Project GitHub repositories. In general all Project decisions are
made through consensus among the Core Developers with input from the
Community.

While this approach has served us well, as the Project grows we see a
need for a more formal governance model. Moving forward The Project
leadership will consist of a BDFL and Steering Council, consisting of 3 elected Package Maintainers serving 3-year terms. We view this governance model as
the formalization of what we are already doing, rather than a change in
direction.

BDFL
----

The Project will have a BDFL, who is currently Sergio Rey. As Dictator,
the BDFL has the authority to make all final decisions for The Project.
As Benevolent, the BDFL, in practice chooses to defer that authority to
the consensus of the community discussion channels and the Steering
Council (see below). It is expected, and in the past has been the case,
that the BDFL will only rarely assert their final authority. Because
rarely used, we refer to BDFL’s final authority as a “special” or
“overriding” vote. When it does occur, the BDFL override typically
happens in situations where there is a deadlock in the Steering Council
or if the Steering Council asks the BDFL to make a decision on a
specific matter. To ensure the benevolence of the BDFL, The Project
encourages others to fork the project if they disagree with the overall
direction the BDFL is taking. The BDFL may delegate their authority on a
particular decision or set of decisions to any other Council Member at
their discretion.

The BDFL can appoint his/her successor, but it is expected that the
Steering Council would be consulted on this decision. If the BDFL is
unable to appoint a successor, the Steering Council will make this
decision - preferably by consensus, but if needed by a majority vote.

Note that the BDFL can step down at any time, and acting in good faith,
will also listen to serious calls to do so. Also note that the BDFL is
more a role for fallback decision making rather than that of a
director/CEO.

Package Maintainers
-------------------

The Project is an umbrella for numerous cross-platform Packages.
Packages are maintained, managed and bound by the guidelines of the
Sub-module contract.

Each Package is to be maintained by at least two Maintainers who are
Core Developers and have produced contributions to a Package that are
substantial in quality and quantity, sustained over at least one year.
Potential Maintainers are nominated by existing Maintainers and voted
upon by the existing Steering Council after asking if the potential
Member is interested and willing to serve in that capacity.

The Package Maintainers play a special role in certain situations. In
particular, the Maintainers are responsible for:

-   Proposing of and deciding on the timing of a release of their
    Package in accordance with the Steering Council.
-   Determining the content of a release in case there is no consensus
    on a particular change or feature in accordance with the Steering
    Council.
-   Creating the release and announcing it on the relevant public
    channels in accordance with the Steering Council.
-   Ensuring a summary of any relevant Package updates and issues to the
    Steering Council in developer meetings.
-   Ensuring the composition of Package Maintainers stays current.
-   Ensuring matters of importance discussed in private by Package
    Maintainers get addressed in developer meetings to keep the Steering
    Council and Community informed.
-   Ensuring other important Package documents (e.g. pysal.org presence,
    documentation) stay current after they are added.

Steering Council
----------------

The Project will have a Steering Council that consists of 3 Core
Developers and Package Maintainers who are nominated and elected to 3-year terms. The overall role of the Council is
to ensure, through working with the BDFL and taking input from the
Community, the long-term well-being of the Project, both technically and
as a community.

The Council will appoint a Release Manager for the
Project, who has final responsibility for one or more releases.

During the everyday project activities, Council Members participate in
all discussions, code review and other project activities as peers with
all other Contributors and the Community. In these everyday activities,
Council Members do not have any special power or privilege through their
membership on the Council. However, it is expected that because of the
quality and quantity of their contributions and their expert knowledge
of the Project Software and Services that Council Members will provide
useful guidance, both technical and in terms of project direction, to
potentially less experienced Contributors.

The Steering Council and its members play a special role in certain
situations. In particular, the Council may:

-   Make decisions about the overall scope, vision and direction of the
    Project, Meta-Package and Packages.
-   Make decisions about strategic collaborations with other
    organizations or individuals.
-   Make decisions about specific technical issues, features, bugs and
    pull requests. They are the primary mechanism of guiding the code
    review process and merging pull requests.
-   Make decisions about the Services that are run by The Project and
    manage those Services for the benefit of the Project and Community.
-   Make decisions when regular community discussion does not produce
    consensus on an issue in a reasonable time frame. Update policy
    documents such as this one.

In addition to the duties described above, the Steering Council shall also
have maintenance permissions on all repositories within the PySAL ecosystem,
and reserves the right to commit and merge code across all subpackages. The
reservation of these rights does not imply maintenance responsibility or 
editorial authority over any subpackage  in the ecosystem (save those for which 
the Council members serve as maintainers). Rather, the steering committee is permitted to
exercise judgment in the adoption of community standards across PySAL, and
may initiate and merge any commit related to package infrastructure,
documentation, continuous-integration scaffolding, etc. In certain circumstances,
the council may also initiate and merge pull requests and/or generate a 
package release. These responsibilities are intended to provide a vehicle for
community standardization, not subvert the authority of any package maintainers.


### Current Council Members
- Martin Fleischmann @martinfleis
- James Gaboardi @jGaboardi
- Eli Knaap @knaaptime

### Council Membership

To become eligible for being a Steering Council Member an individual
must be a Package Maintainer or are Core Developers who have produced
contributions that are substantial in quality and quantity, and
sustained over at least one year. Potential Council Members are
nominated by existing Council Members and voted upon by the existing
Council after asking if the potential Member is interested and willing
to serve in that capacity. The Council was be initially formed from the
set of existing Core Developers who, as of January 2018, have been
active as Package Maintainers. This model was adjusted in:
* March 2022 to consist of 3 nominated and elected Council members that serve 1-year terms.
* July 2024 to consist of 3 nominated and elected Council members that serve 3-year terms.

When considering potential Members, the Council will look at candidates
with a comprehensive view of their contributions. This will include but
is not limited to code, code review, infrastructure work, mailing list
and chat participation, community help/building, education and outreach,
design work, etc. We are deliberately not setting arbitrary quantitative
metrics (like “100 commits in this repo”) to avoid encouraging behavior
that plays to the metrics rather than The Project’s overall well-being.
We want to encourage a diverse array of backgrounds, viewpoints and
talents in our team, which is why we explicitly do not define code as
the sole metric on which Council membership will be evaluated.

If a Council Member becomes inactive in the project for a period of one
year, they will be considered for removal from the Council. Before
removal, the inactive Member will be approached to see if they plan on
returning to active participation. If not they will be removed
immediately upon a Council vote. If they plan on returning to active
participation soon, they will be given a grace period of one year. If
they don’t return to active participation within that time period they
will be removed by vote of the Council without further grace period. All
former Council Members can be considered for membership again at any
time in the future, like any other Project Contributor. Retired Council
Members will be listed on the Project website, acknowledging the period
during which they were active in the Council.

The Council reserves the right to eject current Members, other than the
BDFL, if they are deemed to be actively harmful to the project’s
well-being, and attempts at communication and conflict resolution have
failed.

### Release Manager

The Release Manager has final responsibility for making a Project,
Meta-Package or Package release. This includes:

-   Proposing of and deciding on the timing of a release.
-   Determining the content of a release in case there is no consensus
    on a particular change or feature.
-   Creating the release and announcing it on the relevant public
    channels.

The responsibility of all Package releases stays with the respective
Package Maintainers. For more details on what those responsibilities
look like in practice, see the Sub-Module Contract. As described above,
the Steering Council also has authority generate a package release in
some circumstances (e.g. to esure the timely inclusion of a critical
bugfix), however, it is not the Council's responsibility to do so.

### Conflict of Interest

It is expected that the BDFL and Council Members will be employed at a
wide range of companies, universities and non-profit organizations.
Because of this, it is possible that Members will have conflict of
interests. Such conflict of interests include, but are not limited to:

-   Financial interests, such as investments, employment or contracting
    work, outside of The Project that may influence their work on The
    Project.
-   Access to proprietary information of their employer that could
    potentially leak into their work with the Project.

All members of the Council, BDFL included, shall disclose to the rest of
the Council any conflict of interest they may have. Members with a
conflict of interest in a particular issue may participate in Council
discussions on that issue, but must recuse themselves from voting on the
issue. If the BDFL has recused his/herself for a particular decision,
the Council will appoint a substitute BDFL for that decision.

### Private Communications of the Council

Unless specifically required, all Council discussions and activities
will be public and done in collaboration and discussion with the Project
Contributors and Community. The Council can have a private meeting which
will be conducted sparingly and only when a specific matter requires
privacy. When private communications and decisions are needed, the
Council will do its best to summarize those to the Community after
removing personal/private/sensitive information that should not be
posted to the public internet.

### Council Decision Making

If it becomes necessary for the Steering Council to produce a formal
decision, then they will use a form of the Apache Foundation voting
process. This is a formalized version of consensus, in which +1 votes
indicate agreement, -1 votes are vetoes (and must be accompanied with a
rationale, as above), and one can also vote fractionally (e.g. -0.5,
+0.5) if one wishes to express an opinion without registering a full
veto. These numeric votes are also often used informally as a way of
getting a general sense of people’s feelings on some issue, and should
not normally be taken as formal votes. A formal vote only occurs if
explicitly declared, and if this does occur then the vote should be held
open for long enough to give all interested Council Members a chance to
respond – at least one week. In practice, we anticipate that for most Steering Council decisions
(e.g., voting in new members) a more informal process will suffice.

The Council will also be responsible for:

-   Ensuring a summary of any relevant organisational updates and issues yearly.
-   Ensuring the composition of the Steering Council stays current.
-   Ensuring matters discussed in private by the Steering Council get summarized as meeting minutes ([GitHub Discussions](https://github.com/orgs/pysal/discussions/1278)) to keep the Community informed.
-   Ensuring other important organisational documents (e.g. Code of Conduct, Fiscal Sponsorship Agreement) stay current after they are added.


Institutional Partners and Funding
----------------------------------

The Steering Council is the primary leadership for the project. No
outside institution, individual or legal entity has the ability to own,
control, usurp or influence the project other than by participating in
the Project as Contributors and Council Members. However, because
institutions can be an important funding mechanism for the project, it
is important to formally acknowledge institutional participation in the
project. These are Institutional Partners.

An Institutional Contributor is any individual Project Contributor who
contributes to the project as part of their official duties at an
Institutional Partner. Likewise, an Institutional Council Member is any
Project Steering Council Member who contributes to the project as part
of their official duties at an Institutional Partner.

With these definitions, an Institutional Partner is any recognized legal
entity in any country that employs at least 1 Institutional Contributor
or Institutional Council Member. Institutional Partners can be
for-profit or non-profit entities.

Institutions become eligible to become an Institutional Partner by
employing individuals who actively contribute to The Project as part of
their official duties. To state this another way, the only way for a
Partner to influence the project is by actively contributing to the open
development of the project, in equal terms to any other member of the
community of Contributors and Council Members. Merely using Project
Software in institutional context does not allow an entity to become an
Institutional Partner. Financial gifts do not enable an entity to become
an Institutional Partner. Once an institution becomes eligible for
Institutional Partnership, the Steering Council must nominate and
approve the Partnership.

If at some point an existing Institutional Partner stops having any
contributing employees, then a one year grace period commences. If at
the end of this one year period they continue not to have any
contributing employees, then their Institutional Partnership will lapse,
and resuming it will require going through the normal process for new
Partnerships.

An Institutional Partner is free to pursue funding for their work on The
Project through any legal means. This could involve a non-profit
organization raising money from private foundations and donors or a
for-profit company building proprietary products and services that
leverage Project Software and Services. Funding acquired by
Institutional Partners to work on The Project is called Institutional
Funding. However, no funding obtained by an Institutional Partner can
override the Steering Council. If a Partner has funding to do PySAL work
and the Council decides to not pursue that work as a project, the
Partner is free to pursue it on their own. However in this situation,
that part of the Partner’s work will not be under the PySAL umbrella and
cannot use the Project trademarks in a way that suggests a formal
relationship.

Institutional Partner benefits are:

-   Acknowledgement on the PySAL website and in talks.
-   Ability to acknowledge their own funding sources on the PySAL
    website and in talks.
-   Ability to influence the project through the participation of their
    Council Member.
-   Council Members invited to PySAL Developer Meetings.

A list of current and former Institutional Partners is maintained at the
landing page.

Document history
----------------

<https://github.com/pysal/governance/commits/main/README.md>

Acknowledgments
----------------

Substantial portions of this document were adapted from the
Jupyter/IPython/SciPy project’s governance document and NumPy’s
governance document.

License
-------

To the extent possible under law, the authors have waived all copyright
and related or neighboring rights to the PySAL project governance
document, as per the CC-0 public domain dedication / license.
