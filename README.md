# PowerGists
Some PERSONAL CHEATSHEETS for elevator pitch/dialogue to spark interest for value that tech-supported ways of cooperation can deliver. Tech jargon, examples, implementation details are for later. The content is NOT SUPER SELF-EXPLAINING, as they are core ingredients WRITTEN FOR ONLY MYSELF, that I tend to explain in actual communication often in some specific contexts. Some people still found it useful as such, so I shared it here.

![](https://steenschledermann.files.wordpress.com/2014/05/no-thanks-were-too-busy1.jpg)

Organisational first steps towards (data/content) quality and speed:
====================================================================
- Tiny errors make big errors (elsewhere, later, seemingly unrelated, often even unnoticed). Therefore preventing and finding errors should be close, early and relations made visible.
- Fresh high-quality data should be rewarded by minimizing (other) disturbances. Wonder for a moment what analysis comes from 'just another thing to fill in for management'.
- People working/living in immediate context of the data usually know best what values/patterns make sense. Help them configure immediate validation, sharing and loosely coupled visualization and also analysis elsewhere will improve.
- Start by turning on spelling checkers, especially because our digital assistents (starting with search) are easily 'confused'. The more data is combined, the more sensitive it is to data imperfections.
- Let everybody learn a few basic rules to [avoid Excel pitfalls](https://github.com/steltenpower/avoid-Excel-pitfalls), towards 'tidy data'.
- Instead of some of the alternation between group discussion and lone work, PAIRING: More immediate-feedback hands-on working with 2 people, lowering the risk of errors. Can be together at 1 desk making good use of richness of In-Real-Life communication with gestures, physical objects, etc., or remote with audio connection and simultaneously working in the same application context. As this is a different social construct, it allows for more personalized communication and concrete learning, passed on to sessions with others where applicable.

Fully unlock your (data) cooperation potential:
===============================================
- [data-centric (manifesto)](http://datacentricmanifesto.org/): Not apps, but YOU as an organisation decide what your terminology means exactly, where to store your data, in what open format, and how and where is defined what roles/groups/people have what access (full/no/structural/privacy-improved/synthetic, remote/read/write/reshare). You may want applications that are open source with active communities too. You most likely need data-cleaning tools like OpenRefine.
- [Linked Data](https://en.wikipedia.org/wiki/Linked_data): associative as brains and communities. [Links](https://dvcs.w3.org/hg/rdf/raw-file/tip/rdf-primer/example-graph.jpg) databases and [documents](https://rdfa.info/), internal and external, [open](https://lod-cloud.net/clouds/lod-cloud.svg) and closed, including late integration systems like ESBs, by early chosen standard [vocabularies](https://lov.linkeddata.es/dataset/lov/). Enables querying any combination of sources, as if one virtual dataset. Also known as "semantic web". Most Linked Data is 'hidden under the hood' by programmers. I wonder if end users can productively be more directly involved with 'triples' in [multi-user knowledge-based mindmapping/dialogue](https://github.com/steltenpower/Train-Of-Thought).
- [FAIR data](#fair-data-principles): Findable-Accessible-INTEROPERABLE-Reusable; enabling faster research with earlier, wider, AI-assisted cooperation. Everybody in research data management is working on this. Training by [carpentries.org](carpentries.org) (I'm a certified instructor) and others, gets researchers on board.
- <a name="KG">[Knowledge Graphs](https://open.hpi.de/courses/knowledgegraphs2020) (link is to course I did)</a>: Organizations organized, learning from (content from) each other while doing. [Gartner short video "Top Trends in Data and Analytics for 2021: Graph Relates Everything"](https://cfvod.kaltura.com/pd/p/585951/sp/58595100/serveFlavor/entryId/1_2dmwcmmz/v/1/ev/5/flavorId/1_tgmjrzqe/name/a.mp4) and (paywalled) [the full article](https://www.gartner.com/document/3996989).
- SoLiD? (Social Linked Data): users of applications have fine-grained control of their data, hosted outside the applications, together in a so-called personal dataPOD. Less scattered data, more standardized therefore more re-used fields, less monopoly power.
- Data Management Plans and both data and everything else IT on the balance sheet, for value and against vulnerability.
- Project results may need assistance and dynamic infrastructure to enable (later) moving it to a different project or standing organisation.
- Clearly there are different types of IT (office IT, research IT, factory IT, etc.) that need different people. If you haven't yet figured out what type of IT I think about the most, I do find surf.nl and esciencecenter.nl interesting to read, among many others.

Electronic Notebooks:
=====================
Shared on-line documents in which writers and 'programming analysts' can cooperate effectively and reproducibly through:
- Tighter feedback loop between people with different focus: tech-savvy and not, researchers and supporters (both of the dedicated official and technical community type), codecheckers/reviewers and communicators. A web in which I'd love to be adding value, helping, connecting.
- Less manual copy-paste between different applications. 
- No, or less, install (differences).
- Possible within security context of data. Make sure early that people you (might) need in that security context, are ready to be added, as non-disclosure paperwork can take long, or make things near impossible.
- Backend can run on High Performance Computing (HPC) too.
- [Jupyter](https://www.youtube.com/watch?v=eJDxcR1V7Qg) is probably the most popular and has many derivatives. Others are Rnotebook(Rstudio) and ObservableHQ.
- For different contexts it is possible to view a conversion to a different format: static Word/PDF, stand-alone interactive HTML, data-linked but non-editable notebook.
- Properly explained in (paywalled) ["Using Jupyter for Reproducible Scientific Workflows"](https://doi.org/10.1109/mcse.2021.3052101)
- Notebooks became much friendlier especially to non-techies since, but see [some basic principles shown in short video](https://www.youtube.com/watch?v=HW29067qVWk).
- There are Jupyter kernels for dozens of languages (R,Python,JavaScript seem most popular) and Wikipedia Abstract will soon make language choice 'less relevant'.

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
- Licenses make data REUSABLE: allowing using input data in result data. Licenses, possibly more than one, are found in metadata, the file itself, or both.
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
- When you're building on or using, the work of others, you have to mention that.
- For findability and consistency, which also helps readability, several styles for such reference/citation have been designed.
- Scientific articles must use a specific style, demanded by journals, even though most are digital-only nowadays ([shift choice to read-time?](https://github.com/steltenpower/CitationStyleOnReading)).
- Generating in that style (APA, Vancouver, others) is usually done by reference managers (Zotero, Endnote, others) based on data in exchange formats (BibTeX, RIS, others).
- Before you start storing your references somewhere, make sure you can export them in common formats.
- The global network of citations between works is used to find more related work, people to cooperate with and to do impact analysis. Use DOIs and ORCIDs (unique identifiers for works and researchers) and see [OpenCitations](http://opencitations.net/about), Scopus, Web Of Science, Google Scholar and others, but also [alt(ernative) metrics](https://en.wikipedia.org/wiki/Altmetrics)

Containers:
===
Rather well-explained in https://www.youtube.com/watch?v=HelrQnm3v4g

Artificial Intelligence (AI):
========================
I might translate the following dutch bit for this:
<pre>
De term AI schrikt mensen af (ondoorgrondbare magie denken sommigen),
ik begin vaak met te zeggen: patroonherkenning.
En dat expliciete algoritmes (code tikken of genereren)
en impliciete (de patroonherkenning dus) ook samen kunnen werken.
Wat ik zelf een fantastisch voorbeeld vind is de dataset van handgeschreven cijfers
van de Amerikaanse post. Daarover kan iedereen redeneren:
Als je AI vraagt dat op te delen in 10 bakjes, waar zal het dan ongeveer in opgedeeld worden? 
Hoezo ongeveer?
En als je om minder bakjes vraagt? 
En om meer?
Hoe zou iemand met verstand van postcodes zo'n postsysteem kunnen verbeteren?
En als die ook verstand van statistiek heeft?
En wat zou je kunnen doen met gevallen waar algoritme erg onzeker over is?
Wat doe je om te testen of studenten aardig met materie over weg kunnen,
ipv alleen exact wat je je ze eerder hebt voorgelegd?
En dan vervolgens allerlei mooie krachtige voorbeelden noemen van wat AI kan
en ook hoe het al in onze dagelijkse software wordt gebruikt (volgens mij zelfs in Paint).
Misschien nog XAI (eXplainable AI) aanstippen.
Sowieso aanstippen dat AI fouten herhaalt die je in de data hebt, zo is er o.a. racistische AI.
En AI kan aardig interpoleren, maar slecht extrapoleren.
</pre>

HAVE A SUBJECT TO ADD?
========
Just let me know what you have/want

WHICH TO TURN INTO A VIDEO (SCRIPT)?
===
eNotebooks maybe? Let me try ...<br><br>
_ wikipedia article on Electronic_lab_notebook as title screen_
_fuzz and fade out everything but the title and then slam a question on 4 times: "WHAT?", "WHY?", "WHERE?", "HOW?"_

PAPER, HISTORY?, _scrolling horizontally through time_:
- "how it all started ..." ; _cavemen chiseling tablets_ , somewhat similar to https://s3.amazonaws.com/lowres.cartoonstock.com/technology-backup-backed_up-spare-history-caves-shr1435_low.jpg
- "be where the readers are, one thought" ; _trebucheting_ , somewhat similar to https://www.toonpool.com/user/3107/files/send_email_380405.jpg
- "Luckily lighter materials were found" ; _after chiseling something paperthin, it is folded into an airplane and thrown_ , somewhat similar to https://www.pngitem.com/pimgs/m/31-317183_painted-paper-plane-hand-png-download-free-clipart.png
- "Easily stained however" ;  _hit by bird droppings mid flight_, somewhat similar to https://www.nicepng.com/png/detail/147-1472116_royalty-free-collection-of-high-quality-free-cliparts.png
- "Later found to be a feature too" ; _heavy tablet hits bird in air, losing a feather , scratching same light tablet on landing_ , somewhat similar to https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQF8SI83PV8vXV1DoUtGe4-wt_IT3Bq7BGJ6RVZlUnh64Azp9eGOwRd7vzZUaIzrqte6Ik&usqp=CAU
- "To shield these documents from stains, all sorts of envelopes were created" ; _show paper envelope and floppy disk being passed on_
- "Projection Chambers (PCs) made those popular" ; _a glass plate, a lamp and a disk station half way_ , very slightly related to https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSETUf_O7IuBBsC1My4v6Hunpvqd05x4_YvSA&usqp=CAU
- "For untalented scribblers, an internal stamp contraption operated by external rows of keys was offered" ; _connecting a keyboard_
- "For knowing where the next stamp was aimed at, a sort of crosshair named CURSOR was part of the system" ; _show cursor_
- "Nowadays documents can be edited by multiple PCs at the same time, resulting in multiple cursors shown, though technological explanations remain foggy" ; _add antennas to PCs, throw a wad of paper into a cloud, add some sparks to both_

As you may be confused now by this strange intro, I have some questions:
- "What, that our narratives nowadays are often heavily based on, was not mentioned at all? ...."
- "Aren't many documents much like a sheet of paper behind a glass plate? How not?"
- "How do you get non-text into documents? Do you see risks for non-reproducibility? Can these be limited?"
- _.... becomes DATA_

COPY-PASTING, IS WASTING: _show document surrounded by some popular applications like SPPS, Excel, etc._
- Just as with typos, manual copy-paste errors might never get found, let alone fixed ; __
- That what gets pasted in, doesn't show what happened before, how a thought process iterated it. Though the paster might not have logged it either.
- The version pasted in doesn't just come with a unambiguous recipe (interpretable by people or algorithms) for reproducibility.
- After it's pasted it can't be experimented with. No trying, discussing, learning, improving.
- If what is copied is updated later, the copy will be out-of-date.

WEDDING BY EMBEDDING:
- 'general web embeds'; _show photo, video, interactive whiteboard, iframe, any web content from elsewhere_
- "and notebook specific code cells" ; _animation of external programs turning into internal editable cells_

CONVERT OR NOT?:
- "you can convert notebooks into many common formats" _docx PDF dashboards view-only-notebooks etc_
- "or invite people into using them directly _notebooks for training, testing, reviewing, publishing" ; _show logos for carpentries, codecheck, etc_
- "Try Jupyter, Rnotebook, observableHQ, and take a peek at what extensions are available" ; _show logos for Jupyter, Rnotebook, ObservableHQ, nbconvert, fast_ai?_

NOW INTERESTED IN SEEING SOME ACTUAL ACTION?:
===
I'll be helping on collecting/configuring data playgrounds where you can try and experience possibilities on easy to grasp subjects, with no or minimized setup and coding.
*If that or anything else I mentioned here makes you want to talk with me, you'll figure out how.*<br>
<br>
On the subject of playgrounds ...
<br>
Scientific 'papers' are a narrative part in increasingly richer publications: Already data is demanded almost everywhere and some journals/platforms want eNotebooks to ease (code)review, but not too far in the future expect interactive models that anybody can turn the knobs on, helping them understand[.](https://doi.org/10.1016/j.patter.2020.100103)

STILL DON'T THINK I'M CRAZY?:
===
I do have [crazy ideas](https://github.com/topics/steltenrepo?o=desc&s=updated) though, that I write down to clear my mind. But I have hardly time to further research or implement them, but maybe you can help in some way ...

WHAT ABOUT JARGON?:
===
If you insist, have some:<br>
AJB,BOM,CSS,D3,ELN,FUN,GIS,HTML,i18n,JS,K-means,LOVE,md,N3,OWL,P-value,QA,RE,SVG,TSV,UX,VRE,WWW,XR,YAML,ZZZ
