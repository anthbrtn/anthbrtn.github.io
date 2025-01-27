---
layout: page
title: Curriculum Vitae
permalink: cv
---

<style>

/* who cares */


@import url('https://fonts.googleapis.com/css2?family=Shippori+Mincho&display=swap');
body {
  color: black;
  background-color: white;
  font-family: Shippori Mincho, helvetica, sans-serif;
  font-size: 18px;  /* Enables font size scaling in MSIE */
  margin-left: auto;
  margin-right: auto;
  width: 600px;
  padding: 0;
}

#content {
	padding: 10px;
  width: 400px;
	margin-left: auto;
    	margin-right: auto;
	line-height: 2em;
}

/* # Header # */
.h1 {
	font-family: 'Dosis';
  color: black;
  background-color: white;
  height: 1.6em;
  margin-top: 1.5em;
}

.h1 img {
  vertical-align: bottom;
}

.h1 a {
  color: blue;
  background-color: transparent;
  text-decoration: none;
  font-size: 91%;
  margin: 0;
  padding: 0 0.5ex 0 0.25ex;
}
.h1 a:hover {
  text-decoration: none;
  color: purple;
  background-color: white;
}

.h1 div {
  position: absolute;
  top: 0.40ex;
}

.h1 .left { left: 0.4em; }
.h1 .right { right: 0.4em; }


/* # Side # */
#side-bar {
  width: 16em;
  float: left;
  clear: left;
  border-right: 1px solid white;
}

#side-bar div {
  border-bottom: 1px solid white;
}

.sideBarTitle {
  color: black;
  font-weight: bold;
  margin: 0 0 0.5em 2mm;
  padding: 1em 0 0 0;
}

#side-bar ul {
  list-style-type: none;
  list-style-position: outside;
  margin: 0;
  padding: 0 0 0.3em 0;
}

li ul {
  padding-left: 1.0em !important;
}

#side-bar li {
  margin: 0;
  padding: 0.1ex 0;  /* Circumvents a rendering bug (?) in MSIE 6.0  XXX should move to iehacks.css, this causes an ugly gap */
}

#side-bar a {
  color: blue;
  background-color: transparent;
  text-decoration: none;
  text-transform: none;
  margin: 0;
  padding: 0.35em 1ex 0.35em 2mm;
  display: block;
  font-weight: bold!important;
  font-size: 104%;
  border-left: black solid 0.2em;
}

.page a {
  color: black!important;
  background-color: #D8DFEA;
  padding-left: 5mm;
}

#side-bar a:hover {
  color: purple;
  background-color: white;
  border-left: black solid 0.2em;
  text-decoration: none;
}

.sideBarText {
  line-height: 1.5em;
  margin: 0 0 1em 0;
  padding: 0 1.5ex 0 2.5mm;
  display: block;
}

#side-bar .sideBarText a {
  margin: 0;
  padding: 0;
  display: inline;
}

#side-bar .sideBarText a:hover {
  color: purple;
  background-color: transparent;
  text-decoration: none;
}

.lighterBackground {
  color: inherit;
  background-color: white;
}



#main-copy p {
  margin: 1em 1ex 1em 1ex !important; /* Need !important so troff-generated pages don't look totally squezed */
  padding: 0;
}

#main-copy a {
  color: black;
  background-color: transparent;
  font-weight: bold;
  text-decoration: none;
}

#main-copy a:hover {
  text-decoration: none;
  color: purple;
  background-color: white;
}

#main-copy h1, #main-copy h2 {
  color: black;
  background-color: transparent;
  font-size: 145.5%;
  font-weight: bold;
  margin: 2em 0 0 0;
  padding: 0.5ex 0 0.5ex 0.6ex;
  border-bottom: 2px solid black;
}

#main-copy h2 {
  font-size: 115.5%;
  border-bottom: 1px solid black;
}

#main-copy .topOfPage {
  color: black;
  background-color: transparent;
  font-size: 91%;
  font-weight: bold;
  text-decoration: none;
  margin: 3ex 1ex 0 0;
  padding: 0;
  float: right;
}

dl {
  margin: 1em 1ex 2em 1ex;
  padding: 0;
}

dt {
  font-weight: bold;
  margin: 0 0 0 0;
  padding: 0;
}

dd {
  margin: 0 0 2em 2em;
  padding: 0;
}


/* # Footer # */
#footer {
  color: black;
  background: white;
  font-size: 91%;
  margin: 0;
  padding: 1em 2.5mm .15em 2.5mm;
  clear: both;
  border: solid 0 white;
  border-width: 1px 0 1px 0;
}

#footer .left {
  text-align: left;
  line-height: 1.45em;
  float: left;
  clear: left;
}

#footer .right {
  text-align: right;
  line-height: 1.45em;
}

#footer a {
  color: blue;
  background-color: transparent;
  text-decoration: none;
}

#footer a:hover {
  text-decoration: none;
  color: purple;
  background-color: white;
}


/* GENERAL */

table {
  background-color: none;
  border-collapse: collapse;
  width: 100%;
}

th {
  padding-top: 12px;
  padding-bottom: 12px;
  text-align: left;
  background-color: #4CAF50;
  color: white;
  font-size: 10px;
}

td {
  background-color: none;
  font-size: 10px;
}

tr:nth-child(even) {background-color: #f2f2f2;} 
tr:hover {background-color: #ddd;}
th, td {
  padding: 10px;
  text-align: left;
}

hr {
  border-width: 0px 0px 0.1em 0px;
  border-color: black;
}

acronym, .titleTip {
  border-bottom: 1px solid black;
  cursor: help;
  margin: 0;
  padding: 0 0 0.4px 0;
}

pre {
  margin-left: 2em; 
  font-size: 1.2em;
}

blockquote {
  border-left: 1px solid black;
  font-style: italic;
}

.smallCaps {
  font-size: 110%;
  font-variant: small-caps;
}

.doNotDisplay { display: none; }


.notify_errors,
.notify_notes,
.notify_success { padding: .8em; margin-bottom: 1em; border: 2px solid black; }
 
.notify_errors { background: #FBE3E4; color: #8a1f11; border-color: #FBC2C4; }
.notify_notes { background: #FFF6BF; color: #514721; border-color: #FFD324; }
.notify_success { background: #E6EFC2; color: #264409; border-color: #C6D880; }
.notify_errors a { color: #8a1f11; }
.notify_notes a { color: #514721; }
.notify_success a { color: #264409; }


/* # Page/Handler specific # */
h1.dir-list-head, ul.dir-list {
  text-transform: none;
  font-weight: bold;
}
ul.sitemap-list a {
}
</style>
<!-- markdown-toc start - Don't edit this section. Run M-x markdown-toc-refresh-toc -->
**Table of Contents**

- [General information](#general-information)
- [Education](#education)
- [Professional Contributions](#professional-contributions)
    - [Publications](#publications)
        - [Refereed Publications](#refereed-publications)
        - [Book Reviews](#book-reviews)
        - [Reports](#reports)
        - [Other Publications](#other-publications)
        - [Presentations (**R** indicates refereed)](#presentations-r-indicates-refereed)
        - [Invited talks](#invited-talks)
        - [Datasets](#datasets)
- [Research and Teaching Appointments](#research-and-teaching-appointments)
    - [Research Appointments](#research-appointments)
    - [Project Leadership](#project-leadership)
    - [Teaching Assistantships](#teaching-assistantships)
    - [Extracurricular Teaching](#extracurricular-teaching)
- [Software Development](#software-development)
- [Media Interviews](#media-interviews)
- [Research Support](#research-support)
    - [External Research Grants](#external-research-grants)
- [Awards and Honours](#awards-and-honours)
- [Contributions to the Profession](#contributions-to-the-profession)
    - [Service to Research](#service-to-research)
    - [Service to the University](#service-to-the-university)

<!-- markdown-toc end -->


# General information

**Citizenship**: Canadian

**Languages**: English, French, Python, Javascript

<!-- **Tel**: +1 (647) 234 8639 -->

**Email**: ab {at} anthbrtn.com

**ORCID iD**: <https://orcid.org/0000-0001-6474-0313>

# Education


Currently: **Doctor of Philosophy, Communications.** Simon Fraser University.

Supervisor: Dr. Wendy Hui Kyong Chun
Committee: Dr. Sun-ha Hong and Dr. Alberto Toscano

Entrance with Provost\'s Prize of Distinction and Joseph Armand Bombardier SSHRC CGS Doctoral
Scholarship.

**Master of Arts, Communication & Culture**. Toronto Metropolitan University & York
University. 2020.

*Thesis title*: \"'I would do anything to not call this place home': The
black pill, involuntary celibacy, and the neoliberal male grasp in
digital incel communities.\"

Award for Outstanding Thesis, nominated.

**Graduate Professional Development in Teaching Program**, Level 1.

The Chang School of Continuing Education. 2019.

**Honours Bachelor of Arts, Literature & Philosophy**.

High Distinction (*summa cum laude*).

Victoria College in the University of Toronto. 2017

## Writing

### Book Reviews

Burton, Anthony Glyn. 2023. Book Review: Code: From Information Theory to French Theory. *New Media & Society*, May. https://doi.org/10.1177/14614448231173132.

Burton, Anthony G. 2020. Review: Technologies of Speculation: The Limits
of Knowledge in a Data-Driven Society. *International Journal of
Communication*, November.

Burton, Anthony G. 2018. [Review: Getting a Life: The Social Worlds of
Geek
Culture](https://quillandquire.com/review/getting-a-life-the-social-worlds-of-geek-culture/).
*Quill & Quire*, March.

### Reports

Bridgman, Aengus, Mathieu Lavigne, Melissa Baker, Thomas Bergeron,
Danielle Bohonos, Anthony Burton, Katharine McCoy, Mackenzie Hart,
Mathieu Lavault, Rupinder Liddar, Pangying Peng, Adelina Petit-Vouriot,
Christopher Ross, Phaedra de Saint-rome, Jaclyn Victor, Taylor Owen,
Peter John Loewen. "Mis- and Disinformation in the 2021 Canadian Federal
Election." OSF Preprints. June 8. doi:10.31219/osf.io/ubfmx.

de Keulenaar, Emillie, Ivan Kisjes. Anthony G. Burton, Jasper van der
Heide, Dieuwertje Luitse, Eleonora Cappuccio, Guilherme Appolinário,
Narzanin Massoumi, Tom Mills, Amy Harris, Jörn Preuß. 2020. "Demoting,
deplatforming and replatforming COVID-19 misinformation\". *Digital
Methods Institute Summer School* Project Report. University of
Amsterdam, July 30.

Elmer, Greg, Ganaele Langlois, Marc Tuters, Melody Devries, Steven J.
Neville, Anthony G. Burton & Sabrina Ward-Kimola. 2020. \"Fringe
Politics: The Deep Web's Impact on the Canadian Election\", Report for
Digital Ecosystem, Research Project, Heritage Canada.

Burton, Anthony G., Ivana Škoro, Henri Mütschele, Myrthe Reuver, and
Shenglang Qing. 2019. [\'Streams of the Deep Web: Mapping Rebel Media on
YouTube\'](https://wiki.digitalmethods.net/Dmi/SummerSchool2019StreamsoftheDeepWeb).
*Digital Methods Institute Summer School* Project Report. University of
Amsterdam, July 21.

### Other Publications

Burton, Anthony Glyn. 2022. "Jonathan Beller – Poetry Against Calamity: Decolonial Ecography and Post-Capitalist Economic Media." Digital Democracies Institute blog. June 28. <https://digitaldemocracies.org/jonathan-beller-poetry-against-calamity-decolonial-ecography-and-post-capitalist-economic-media/>. 

Elmer, Greg, Anthony G. Burton, and Stephen J. Neville. 2020. "These
researchers tracked down how hackers are disrupting Zoom chats." Global
News. June 15. <https://globalnews.ca/news/7048850/zoom-hacking/>.

Elmer, Greg, Anthony G. Burton, and Stephen J. Neville. 2020.
"Zoom-Bombings Disrupt Online Events with Racist and Misogynist
Attacks." The Conversation. June 9, 2020.
<http://theconversation.com/zoom-bombings-disrupt-online-events-with-racist-and-misogynist-attacks-138389>.

Burton, Anthony G. and Jack Wilson. *Zygotian Solipsism: An
Epistemic-Ontological Limit Case and Those Who Want to Live It.*
Raleigh, USA: Non-Press, 2019.

Hagen, Sal, Anthony Glyn Burton, Jack Wilson and Marc Tuters. 2019.
[\'Infinity\'s Abyss: An Overview of
8chan\'](https://oilab.eu/infinitys-abyss-an-overview-of-8chan/.).
*OILab*, August 8.

Burton, Anthony Glyn. 2018. [\'X.
Why?\'](https://theoutline.com/post/4919/x-why-does-tech-love-the-letter-x).
*The Outline*, June 13.


### Invited talks

---. Moderated by Barry Truax.
2024. "Communication as technocritique". *Simon Fraser University 50th Anniversary Symposium | Communication as Critique*.
December 2.

---, Supriya Dwivedi, and Jane Lytvynenko. Moderated by Asmaa Malik.
2021. "Viral Threats to Journalists: From Talk Radio to Social Media to
Zoombombing". *Toronto Metropolitan University School of Journalism Research Centre*.
November 9.

---. 2021. Workshop on methods teaching. CC9000 Advanced Research
Methodologies, Toronto Metropolitan University. 10 February.

---. 2020. Workshop on construction of digital research persona for
investigative journalism. *Canadian Centre for Free Expression*. 17
November.

---. 2019. \"How to Study the Internet." Guest lecture presented in
SOC482 Media Methods, March 21.

---. 2019. \"A Narrative Analysis Case Study: Gab.ai.\" Guest lecture
presented in SOC482 Media Methods, March 7.

### Datasets

---. 2020. Rebel Media contributors timeline (Version 0.1.0). \[Data
set\]. Zenodo. doi.org/10.5281/zenodo.3634817

---. 2020. #cdnpoli and the Twittersphere: User mentions during the 2019
Federal Election (Version 1.0.0) \[Data set\]. Zenodo.
doi.org/10.5281/zenodo.3634154

# Research and Teaching Appointments

## Research Appointments

**Invited Participant.** STS Summer School at Harvard. August 2023.

**Visiting researcher**. Chair of Digital Cultures, Technische Universitat Dresden. 2023.

**Invited Participant.** Stanford-Leuphana Summer Academy, "Scale". June 2022.

**Graduate Fellow, *Data Fluencies***. The Andrew F. Mellon Foundation and the Digital Democracies Institute, Simon Fraser University. 2022-

**Project Lead, *Beyond Verification***. Digital Democracies Institute,
Simon Fraser University. 2020-.

**Co-founder**. Digital Citizenship Cultures Initiative, Toronto Metropolitan
University. With Drs. Greg Elmer and Ganaele Langlois. 2019-.

**Research Associate**. Infoscape Research Lab, Toronto Metropolitan University.
2019-.

**Research Associate**. Open Intelligence Lab, University of Amsterdam.
2019-.

**Visiting Researcher**. Departement van Media & Cultuur, University of
Amsterdam. 2019.

**Graduate Assistant**. Department of Politics & Public Administration,
Toronto Metropolitan University. 2019.

**Research Assistant**. Department of Political Science, University of
Toronto. 2017.

## Project Leadership

**The Post-Trump Information Ecology: Political news on Reddit and 4chan
*pol* and the 2020 American election.** University of Amsterdam Digital
Methods Initiative Winter School. January 2021.

**Post-propaganda pipeline: Junk American political news on Reddit and
4chan *pol*.** University of Amsterdam Digital Methods Initiative Spring
Data Sprint. March 2020.

**Streams of the Deep Web: Mapping YouTube's Alt-Right in the context of
the Canadian Federal Election.** University of Amsterdam Digital Methods
Initiative Summer School. July 2019.

## Teaching Assistantships

**CMNS202 Design and Method in Qualitative Communication Research**. School of Communication, Simon Fraser University. 2024.

**CC8849 Selected Topics in PinP: Digital Methods**. Joint Program in
Communication & Culture, Toronto Metropolitan & York University. 2019.

**SOC482 Media Methods**. Sociology Department, Toronto Metropolitan University.
2019.

## Extracurricular Teaching

**Founder & Program Lead**. Editorial Assistant Education Program. The
Strand, Victoria College\'s Student Newspaper. 2016.

# Software Development

**kofi**. A web application for editing markdown files hosted on a
server's native filesystem. Built with React and Node.js. Source code
available at <https://github.com/anthbrtn/kofi>.

**gofindme**. A python-based web scraper for gofundme.com campaigns.
Tracks campaign information, donations, and comments. Source code
available at <https://gitlab.com/anthbrtn/gofindme>.

**company-zetteltags**. Allows for the automatic completion of tags when
using the
[Zettelkasten](https://writingcooperative.com/zettelkasten-how-one-german-scholar-was-so-freakishly-productive-997e4e0ca125)
knowledge capture method. Specifically, `company-zetteltags` is built as
a backend to the `company-mode` autocompletion framework and plugs into
the [zetteldeft](https://github.com/EFLS/zetteldeft) software library
for `GNU-Emacs`. Source code available at
<https://gitlab.com/anthbrtn/company-zetteltags/>.

**PyWarcSer**. Tool to download all publicly-accessible pages of
webforums built using the XenForo webforum software, convert into a
`.warc`-formatted website archive file, and insert into a SQL database
for statistical analysis. Written in Python. Source code availability
pending.

**Digital Methods Toolkit**. An evolving list of resources to perform
digital methods research. Available at
<https://anthbrtn.com/digital-methods.html>.

**fzf-menus**. A set of small menu widgets to connect to wifi and
bluetooth using junegunn's [fuzzy file
finder](https://github.com/junegunn/fzf). Source code available at
<https://gitlab.com/anthbrtn/fzf-menus>.

**Digital Citizenship Cultures Initiative website**. Website
accompanying the Digital Citizenship Cultures research group at Toronto Metropolitan
University\'s Infoscape Lab. Founded initiative with Drs. Greg Elmer and
Ganaele Langlois. Website available at <https://dcc.infoscapelab.ca>.

**"The Hall of Boomer Nihilism"**. Three-monitor installation, live feed
of images from the PatriotsSoapBox Discord server coded in Python using
the Discord API. Source code available at
<https://gitlab.com/anthbrtn/boomer-hall-of-nihilism>.

**Commentariat colour scheme**. A colour scheme for text editing in
Markdown. Originally designed for
[Atom](https://atom.io/themes/commentariat), it is easily portable to
other apps such as the terminal emulator
[Tilix](https://github.com/anthbrtn/commentariat-tilix). The repository
also contains a detailed tutorial on how to set up a markdown-based
writing workflow in Atom. Source code available at
<https://gitlab.com/anthbrtn/commentariat>.

# Media Interviews

Interview about resurgence of racist Zoombombing instance at Queen's
University. Krause, Kraig. February 4 2021. Queen's University lecture
hacked by 'Zoom bombers'. *Global News*.
<https://globalnews.ca/news/7621278/queens-university-lecture-zoom-bombers/>

Interview about misinformation news in Canadian "new right new media".
Do Couto, Sarah. August 2 2020. 'Fullish Disclosure.' *Toronto Metropolitan Review of
Journalism*. <https://rrj.ca/fullish-disclosure/>

Interview about the proliferation of Zoombombing during COVID-19
self-quarantine. Sobocan, Cathy. 29 June 2020. 106.5 ELMNT FM.

Consultation about COVID-related misinformation and alternative digital
platforms. Bellemare, Andrea, Katie Nicholson, and Jason Ho. 21 May
2020. 'How a debunked COVID-19 video kept spreading after Facebook and
YouTube took it down.' *CBC News*.
<https://www.cbc.ca/news/technology/alt-tech-platforms-resurface-plandemic-1.5577013>

Discussion about fake news and Canada's new right new media on the
Toronto Metropolitan Review of Journalism's *Pull Quotes* podcast. Fraser, Ashley,
and Tanja Saric. 7 November 2019. 'Pull Quotes Season Three, Episode
Two: How Media Professionals Adapt to Challenging Misinformation'. *Pull
Quotes*. <https://rrj.ca/pull-quotes-season-three-episode-1-2/>.

# Research Support

## External Research Grants

*Digital Disinformation and Citizenship Network.* 2020-2021. Budget:
\$350,000. Collaborator. Heritage Department, Government of Canada.
Principal Investigator: Greg Elmer (Toronto Metropolitan University). Co-PIs: Wendy Chun (SFU),
Fenwick McKelvey (Concordia), Ahmed Al-Rawi (SFU), and Ganaele Langlois
(York).

*The Dark Web's impact on the 2019 Canadian Federal Election*.
2019-2020. Budget: \$50,000. Co-Principal Investigator. Heritage
Department, Government of Canada. Principal Investigator: Greg Elmer
(Toronto Metropolitan University). Co-Principal Investigator: Marc Tuters (University of
Amsterdam).

# Awards and Honours

**Provost\'s Prize of Distinction**. Simon Fraser University. 2020-2023.

**Social Sciences and Humanites Research Council of Canada Joseph
Armand-Bombardier Doctoral Fellowship.** Federal. 2020-2023.

**Toronto Metropolitan University Thesis Gold Medal, Nomination**. Toronto Metropolitan Unviersity
Faculty of Arts. 2020.

**Social Sciences and Humanities Research Council of Canada Graduate
Masters Scholarship**. Federal. 2019-2020.

**Public Scholar**. Toronto Metropolitan University Faculty of Arts. 2019-2020.

**Ontario Graduate Scholarship**. Provincial. 2019-2020. (Declined).

**Toronto Metropolitan Graduate Fellowship**. Program. 2018-2020. (Declined for
2019-2020).

**Mitacs Globalink Research Award**. Project: \"Streams of the deep web:
Mapping YouTube\'s alt-right in the Canadian Election\". 2019.

**Silver V Award for Outstanding Campus Contribution**. Victoria College
in the University of Toronto. 2017.

**Secor Essay Prize in Renaissance Studies**. "Veronica Franco's
Epistolary Self-Construction". 2016.

# Contributions to the Profession

## Service to Research

Co-organizer, Mis/disinformation and the artifices of 
authenticity and authentication. International Communication Association Pre-Conference, Toronto, Canada. May 24 2023.

Reviewer, New Media & Society; Canadian Journal of Communication

Co-organizer, 3TRG (Technics, Techne and Technology Reading Group).
Digital Democracies Institute, Vancouver, Canada and Associação de
Panel chair, *Future Communications* Graduate Conference, York
University. December 13 2019.

Panel chair, *Intersections/Cross-Sections* Graduate Conference,
Toronto Metropolitan & York University. February 4 2019.

## Service to the University

Admissions committee gaduate representative. Simon Fraser University Department of Communications. 2023.

MA Executive Representative. Communication & Culture Graduate Students\'
Association. 2018-2020.
