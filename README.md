# PowerGists
Some PERSONAL cheatsheets for elevator pitch/dialogue to spark interest for value that tech-supported ways of cooperation can deliver. Tech jargon, examples, implementation details are for later. The content is NOT VERY SELF-EXPLAINING, as they are core ingredients written for only ME, that I tend to explain in actual communication often in some specific contexts. Some people still found it useful as such, so I shared it here.

Organisational first steps towards (data/content) quality and speed:
====================================================================
- Tiny errors make big errors (elsewhere, later, seemingly unrelated, often even unnoticed). Therefore preventing and finding errors should be close, early and relations made visible.
- Fresh high-quality data should be rewarded by minimizing (other) disturbances. Wonder for a moment what analysis comes from 'just another thing to fill in for management'.
- People working/living in immediate context of the data usually know best what values/patterns make sense. Help them configure immediate validation, sharing and loosely coupled visualization and also analysis elsewhere will improve immediately.
- Start by turning on spelling checkers, especially because our digital assistents (starting with search) are easily 'confused'. The more data is combined, the more sensitive it is to data imperfections.
- Let everybody learn a few basic rules to [avoid Excel pitfalls](https://github.com/steltenpower/avoid-Excel-pitfalls), towards 'tidy data'.
- Pairing, instead of some of the alternation between group discussion and lone work: More immediate-feedback hands-on working with 2 people. Both at 1 desk making good use of richness of In-Real-Life communication with gestures, physical objects, etc., And remote with audio connection and simultaneously working in the same application context. As this is a different social construct, it allows for more personalized communication and concrete learning, passed on to sessions with others where applicable.

Fully unlock your (data) cooperation potential:
===============================================
- [data-centric (manifesto)](http://datacentricmanifesto.org/): Not apps, but YOU as an organisation decide what you mean exactly, where to store it, in what open format, and how and where is defined what roles/groups/people have what access (full/no/structural/privacy-improved/synthetic, remote/read/write/reshare). You may want applications that are open source with active communities too. You most likely need data-cleaning tools like OpenRefine.
- [Linked Data](https://en.wikipedia.org/wiki/Linked_data): associative as brains and communities. [Links](https://dvcs.w3.org/hg/rdf/raw-file/tip/rdf-primer/example-graph.jpg) databases and [documents](https://rdfa.info/), internal and external, [open](https://lod-cloud.net/clouds/lod-cloud.svg) and closed, including late integration systems like ESBs, by early chosen standard [vocabularies](https://lov.linkeddata.es/dataset/lov/). Enables querying any combination of sources, as if one virtual dataset. Also known as "semantic web". Most Linked Data is 'hidden under the hood' by programmers, I wondered if end users could be more directly involved with the concepts which resulted in a rough draft for [multi-user knowledge-based mindmapping/dialogue](https://github.com/steltenpower/Train-Of-Thought).
- [FAIR data](#fair-data-principles): Findable-Accessible-INTEROPERABLE-Reusable; enabling faster research with earlier, wider, AI-assisted cooperation. Everybody in research data management is working on this. Training by [carpentries.org](carpentries.org) and others gets researchers on board.
- <a name="KG">[Knowledge Graphs](https://open.hpi.de/courses/knowledgegraphs2020) (link is to course I did)</a>: Organizations organized, learning from (content from) each other while doing. [Gartner short video "Top Trends in Data and Analytics for 2021: Graph Relates Everything"](https://cfvod.kaltura.com/pd/p/585951/sp/58595100/serveFlavor/entryId/1_2dmwcmmz/v/1/ev/5/flavorId/1_tgmjrzqe/name/a.mp4) and (paywalled) [the full article](https://www.gartner.com/document/3996989).
- SoLiD? (Social Linked Data): users of applications have fine-grained control of their data, hosted outside the applications, together in a so-called personal dataPOD. Less scattered data, more standardized therefore less repeated fields, less monopoly power.
- Data Management Plans and both data and everything else IT on the balance sheet, for value and against vulnerability.
- Project results may need assistance and dynamic infrastructure to enable (later) moving it to a different project or standing organisation.
- Clearly there are different types of IT (office IT, research IT, factory IT, etc.) that need different people. If you haven't yet figured out what type of IT I think about the most, I do find surf.nl and esciencecenter.nl interesting to read, among many others.

Electronic Notebooks:
=====================
Shared on-line documents in which writers and 'programming analysts' can cooperate effectively and reproducibly through:
- Tighter feedback loop between people with different focus: tech-savvy and not, researchers and supporters (both of the dedicated official and technical community type), codecheckers/reviewers and communicators. A web in which I'd love to be adding value, helping, connecting.
- Less manual copy-paste between different applications. 
- No, or less, install (differences). Possible within security context of data. Make sure early that people you (might) need in that security context, are allowed. Paperwork can take long, or make things near impossible. Actually technically activating access takes just seconds.
- Backend can run on High Performance Computing (HPC) too.
- [Jupyter](https://www.youtube.com/watch?v=eJDxcR1V7Qg) is probably the most popular and has many derivatives. Others are Rnotebook(Rstudio) and ObservableHQ.
- For different contexts it is possible to view a conversion to a different format: static Word/PDF, stand-alone interactive HTML, data-linked but non-editable notebook.
- Properly explained in (paywalled) ["Using Jupyter for Reproducible Scientific Workflows"](https://doi.org/10.1109/mcse.2021.3052101)
- Notebooks became much friendlier to non-techies, since this was shot, but [some basic principles shown in short video](https://www.youtube.com/watch?v=HW29067qVWk).

Git(Hub/Lab/etc):
=========
De facto standard for managing changes in file sets:
- Simultaneously working on the same file with multiple apps/users is no problem.
- Related files can be kept consistent within 1 change.
- Asks to comment changes for readable history to navigate.
- Many (related) workflow/project tools

Open data:
==========
- Open licenses, e.g. [Creative Commons](https://creativecommons.org/)
- No logins, cookies, or custom apps needed
- Open specifications and open vocabularies to validate against.
- Next to legally open, also easy to process
- Beware: Not all advertised as open data really is. Example: House of Representatives of The Netherlands 'open data'. Scraping :-(

[FAIR (data) principles](https://www.go-fair.org/fair-principles/):
======================
- Rich domain-specific metadata 'tagging' and archiving make something FINDABLE (via general and domain-specific search engines): keyword can give web address
- Persistent identifiers and (machine-readable) prerequisites for visitors make and keep something ACCESSIBLE: web address can give file. Persistent identifiers (DOI, ORCID, etc.) are not only infrastructure less vulnerable to common changes, but usually also demand standardized metadata, wich helps Findable.
- Common open file formats and vocabulaires make something INTEROPERABLE: file can give compatible data (including formats commonly referred to as content).
Helps findable too.
- Allowing different things with different licenses makes something REUSABLE: using input data in output data. Licenses are found in metadata, the file itself, or both.
- For maximum effect the above should be as EARLY as possible, within the primary workflow. For example: [A suggestion for FAIR filesViewing](https://github.com/steltenpower/FAIRfilesViewing)

Accessibility:
==============
- Giving people freedom to pick their methods of interaction.
- Devices are different, people and their preferences are different, circumstances are different and all interact and keep changing.
- Laws demand certain levels of accessibility, also to minimize limitations brought by handicaps.
- Accessibility for people (also a11y), gives (some) accessibility for their (digital) assistants too
- Being data-centric, you might have APIs to allow (custom) User Interfaces that fit productivity and creativity. It's about the result after all, speaking the same language. Of course there's efficiency in having a strong default for tools, but you're not enforcing absolutely all different people to use the same hammer for every nail, or even screw, are you? 

SVG:
====
- static/generated/interactive VISUALS consisting of objects that are intrinsically structured/layered/relatable, making it a common (often 'under the hood') format for visualizing anything expressed in some regular data format or domain-specific language.
- searchable text in any shape, filters, styling, animating, infinite sharp zoom
- part of the (open, modular and semantic) web and (specifically) composable HTML; anything in the browser and loads of apps too.
- abbreviation of Scalable Vector Graphics
- Give me a time limit up-front when you ask me about this: On invitation I've written some technical articles on how to code/create things with SVG, given some presentations, but most importantly I've brought people together on SVG and other graphical web technologies from all around the world, being the main organisor twice: University of Twente (2005) and Google HeadQuarters (2009)

Literature references, citation styles, APA, reference managers, citation/reference exchange data formats:
===
When you're building on, or using the work of others, you have to mention that.
For consistency and findability several styles for such reference/citation are designed.
Scientific journals demand articles to use a specific one.
To help automation of using such a style Citation Style Language (CSL) 

BIBTEX

Endnote, Zotero


paper-era thing.


Artificial Intelligence (AI):
========================
Is advanced pattern recognition applied. Might elaborate later.

HAVE A SUBJECT TO ADD?
========
Just let me know what you have/want

WHICH TO TURN INTO A VIDEO (SCRIPT)?
===
eNotebooks maybe?
*For the title shot: zoom in on (Wikipedia) page for the title, a draft if necessary*

NOW INTERESTED IN SEEING SOME ACTUAL ACTION?:
===
I'll be helping on collecting/configuring data playgrounds where you can try and experience possibilities, with no or minimized setup and coding.
*If that or anything else I mentioned here makes you want to talk with me, you'll figure out how.*<br>
<br>
On the subject of playgrounds ...
<br>
Scientific 'papers' are a narrative part in increasingly richer publications: Already data is demanded almost everywhere and some journals/platforms want eNotebooks to ease (code)review, but not too far in the future expect interactive models that anybody can turn the knobs on, helping them understand[.](https://doi.org/10.1016/j.patter.2020.100103)

STILL DON'T THINK I'M CRAZY?:
===
I do have [crazy ideas](https://github.com/topics/steltenrepo?o=desc&s=updated) though, that I write down to clear my mind. But I have no time to further research or implement them, but maybe you can help in some way ...

WHAT ABOUT JARGON?:
===
If you insist, have some:<br>
AJB,BOM,CSS,D3,ELN,FUN,GIS,HTML,i18n,JS,K-means,LOVE,md,N3,OWL,P-value,QA,RE,SVG,TSV,UX,VRE,WWW,XR,YAML,ZZZ
