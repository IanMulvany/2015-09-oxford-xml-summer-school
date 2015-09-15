
---
class: title, center, middle
template: xml-summer-school

title: Revolutions in publishing

# Revolutions in publishing

.slide_nav[.blue[introduction]]


???

# revolutions in publishing
Scientific publishing has been a going concern since the 1660’s, and yet since then some aspects  of publishing has changed remarkably little, both in terms of the business models (subscription publishing) and core formats of discourse (static documents,
initially in paper, now in PDF).

(That the entire scholarly record is effectively now online, and discoverable is an amazing achievement, and the importance of this should not be overlooked or it’s significance ignored).

This course will look at some of the current key changes that are happening in the industry from both business and technological perspectives.

We are going to step through some example innovations that are happening. I have clustered these into trends that are having an immediate and important effect, trends that look like they have the potential to be game changes in the next five years, and then finally I’ll spend a small amount of time talking about highly speculative trends.

These trends have implications for publishers, researchers and the general public, and I’ll highlight those as we go through this course.

If there is any unifying theme to all of these trends, it is that they are all driven by opportunities created by the internet, and the new capabilities that it provides around processing and tracking information, and the potential decrease in costs that are associated with manipulating purely digital objects.

TODO: show the mind map here



---
.slide_nav[.blue[introduction]]

## Caveats

Before going into these topics I want to set out my stall and be very clear about my biases:

--

### advocate for open access

--

### no formal background in XML

--

### a fan of the open web

--

### some experience of building publishing workflows from scratch

--

### some experience in building some tools for researchers

- connotea
- nature network
- mendeley
- eLife



---
background-image: url(http://localhost:8000/oss-revolutions-in-publishing.png)

.slide_nav[.blue[introduction]]

---
template: xml-summer-school
class: inverse


.headline[
* .green[Open Access]
* .green[Research Data]
* .green[Object level/Alt Metrics]


* .orange[Reproducibility]
* .orange[Webkit and the browser]
* .orange[HTML5/Markdown/JSON]


* .red[Computational papers]
* .red[Living papers]
* .red[The blockchain]
]

.slide_nav[.blue[introduction]]


---
## dominant trends

- Open Access
- Research Data
- AltMetrics

---
.slide_nav[.green[open access]]
# Open Access

???

From the business point of view we will look at the rise of open access, discuss the different flavors of open access, and discuss the how creative commons licenses can support the goals of open access. We will look at how commercial and non-commerical publishers have adopted open access. We will look at growing number of government and funder open access mandates, and ask whether this means that open access is a lock in as the only viable publishing model in the future.


---

TODO: Insert OA slides here!


---
.slide_nav[.green[open access]]

## Subscription Benefits

- reader/librarian pays  
Can be argued that this fairly places the burden of the costs of production on the target market, however IMO the bundling that happens in big deals makes this argument less watertight.
- low risk for the publisher
- very low barriers for the author
- usually no fees  
/var/folders/fc/_q9f5y4n51bb7kjf_tv7l9xw0000gn/T/com.skitch.skitch/DMD332FA184-B1D6-4A87-81AA-F2E84A294264/Academics_are_being_hoodwinked_into_writing_books_nobody_can_buy**_Higher_Education*Network***The_Guardian.png

---
.slide_nav[.green[open access]]
## Open Access History

- Budapest declaration  
  - February 2012. Came out of a
  - Meeting funded by the Soros foundation .footnote[](George Soros was a student of Karl Popper, and later a merchant banker)]
  - 13 original signatories
- definition of open access  
	 - Free to Read
	 - Free to Reuse
	 - Free to Modify

At that time no specific license was mentioned.

---
.slide_nav[.green[open access]]
###  colors of open access
- Green  
authors can deposit their content into a repository, some restrictions may apply around format and rights for re-use.  
  - simplest to implement  
  - good support for institutional repositories
  - has the backing of CAS
  - does not provide long term financial sustainability
  - under legal threat from Elsevier
- Gold  
  -  An article processing fee is paid for the article to be published.
  -  Scales with submissions  
  - Proven to work
  - Can lead to charges of predatory publishing
    - this argument is baseless
  - Applied without waivers and it becomes a barrier
  - The natural price is not yet known
- Hybrid  
  - A journal supports a mixture of subscription based articles and gold open access
  - can transision an existing journal gradually  
  - has tended to be a bit of a clusterfuck
  - leads to charges of "double dipping"
  - tracking license through metadata is hard
- Diamond  
  - Content goes through the normal publishing process, but
  - fees are supported though public or charitable funds,
  - authors experience no need to arrange payment
  - large question over long term sustainability of this model


---
.slide_nav[.green[open access]]
## Creative common licenses

- CC0
- CC-BY
- CC-BY-NC
- CC-BY-NC-ND

???
  Listed from most permissive to least permissive.
  note that CC0 is not technically a licence.
  - mention conversation with publiser of Sciecne

---
.slide_nav[.green[open access]]

## Funders and Funder mandates

- (2013) Wellcome Trust
- (2013) White House Memo
  - (1991) ArXiV
  - (2000) PubMedCommons
  - (2013) BioArXiV
  - (2014) CHORUS Launched 2014
- (2014) HEFCE
- (2014) Bill &amp; Melinda Gates Policy
- (2015) NRO

# 2014 over 500 OA policies, growing at 16% y/y

???

[OSTP memo]([https://www.whitehouse.gov/blog/2013/02/22/expanding-public-access-results-federally-funded-research](https://www.whitehouse.gov/blog/2013/02/22/expanding-public-access-results-federally-funded-research)) was released in February 2013
No funds were set aside for achieving compliance of the memo, and that has led to adoption probably being somewhat slow.


---
.slide_nav[.green[open access]]

## publishers

 - BMC
 - PLOS
 - eLife
 - PeerJ
 - University Presses

--

 - Elsevier
 - SpringerNature

---
.slide_nav[.green[open access]]

# has OA been a success?

---
.slide_nav[.green[open access]]

# YES

---
.slide_nav[.green[open access]]

- more content is available free to read
	- from 2003 to 2013 OA PubMed content grew from 1% to 15%
- most funders have accepted that OA is in line with their mission
- many new journal launched today are OA journals

---
.slide_nav[.green[open access]]

## if so, why?
- commerical publishers have discovered that it can be profitable
- it appeals to our better angels
- it strongly aligns with ideas of the public good
- the idea of creating a well functioning marketplace is also an appealing one


---
.slide_nav[.green[open access]]

 # NO
 ---
 .slide_nav[.green[open access]]

- global costs in the industry have continued to rise, and not been checked
- commerical publishers have retained an almost monopoly position in the market
- most authors today remain uninterested in OA for it's own sake
- it's only captured about 2% of the revenue in the market

---
.slide_nav[.green[open access]]

## if not, why not?
- there remains a collective action problem
- publishing infrastructure is baroque (including XML workflows)
  - .footnote[cost of transition to a more efficient system is high]
- direct to web solutions have not disrupted the existing scholarly publishing infrastructure
- journals remain a collection of micro-monopolies

---
.slide_nav[.green[open access]]
## meaning

---
.slide_nav[.green[open access]]

OA publishing is a service based model, the capturing the

- Service Model
  - APCs the main customer is the author/funder
    - .footnote[considered a cost of the research process]
 - membership model
 - direct support model (diamond)
 - making the cost of production disappear

--
Subscription publishing is a content based model

## subscription is a content based model
 - access: the main customer is the institutional librarian
 - sponsorship
 - advertising
 - reprints

---
.slide_nav[.green[open access]]

# As long as you are creating more value then you are capturing, then you are doing good for your community.

---
.slide_nav[.green[open access]]

# What services does the customer want?

 - the main customer is the author

author needs can still be served by XML workflows, but the rest of the stack is not serving them well.  

they want:
 - fair and balanced peer review
 - rapid publication times
 - a “good publication”
 - a discoverable publication  
  - indexing in google scholar  
  - coverage in scopus/web of science  
  - discipline specific archiving    
- software that is respectful of their time  

---
.slide_nav[.green[research data]]


# Research Data

???

Research data is currently one of the hot topics in scientific discourse, working out how to handle it, how to support good creation of data, how to give appropriate credit for activities that surround data. We will look at a few aspects of data, and why it’s such an important trend in the STM sector.


---
.slide_nav[.green[research data]]

#### Why care about data?

It’s obvious to say this, but the data that research is built on is an integral part of the scientific process.

---
.slide_nav[.green[research data]]

#### What’s the relationship between the paper, and data?

A fair criticism of current publishing workflows is that publishers force authors to reduce much of their raw data into the form of graphics or images, and then to compress these images into low resolution versions for inclusion in a manuscript. The reader wants to get the underlying data, but has to go through a lot of hoops to get it.

???

TODO: insert data / paper patterns slide

---
.slide_nav[.green[research data]]

- It’s one component of a research object!
 - Article
 - Data
 - Code
- It’s one component of a story from the author
 - Preprints
 - Posters
- It’s an evolution of a narrative
 - versioning and changing research objects
  - github inspired publishing platforms
   - overleaf
   - astro journal thing?
   - giving a DOI to each revision of an article?
    - giving a DOI to each item of a dataset?
- The relationship between different components can be signalled.

---
.slide_nav[.green[research data]]

## Scales of data

- BIG DATA
- small data
- data that is starting to get out of control

---
.slide_nav[.green[research data]]

## Flavours of data

- Well structured
- semi-structured
- totally unstructured

???

TODO: insert slide showing a set of diverse locations for placing data here .

---
.slide_nav[.green[research data]]

## Getting credit for data


---
.slide_nav[.green[research data]]

### How to handle data?

- We don’t really know  
- some data journals coming to market  
- now exists a way to cite data, but not widely used yet  
- Funders increasingly looking to bring in open data policies  

???

TODO: insert slide from data slides showing some journals that are starting to do
something about this.


---
.slide_nav[.green[altmetrics]]

# AltMetrics

---
.slide_nav[.green[altmetrics]]

## what are they?

???
TODO: show “the slide!”

---
.slide_nav[.green[altmetrics]]
#### what’s their history?
Manifesto was written in 2005

---
.slide_nav[.green[altmetrics]]
## what’s the current state of the art?

- altmetric.com
 - Nature
 - Springer
 - Wiley
- lagotto  - the open source tool
 - PLOS
 - copernicus
 - eLife
- plumb analytics
- publishers creating or running their own platforms
 - frontiers
- repositories adding UIDs
 - figshare
 - datadryad
 - zenodo

---
.slide_nav[.green[altmetrics]]  
## what’s next for ALMs?

- They provide a variety of different kinds of value to different actors in the space, but there has not yet been a “killer app”
- They allow researchers to create narratives of their work and impact (impactstory).

---
.slide_nav[.green[altmetrics]]   
## but what are they really about?

- They are really about problems in the assessment and rewards system in academia.  
 - see DORA - the declaration on research assessment

---
.slide_nav[.green[altmetrics]]   

## What have they got to do with XML, markup and structure?

- data citation
- well identified objects help
- objects that show their interrelationship help
- the fuller a digital life that an object has, the easier it is to automate the gathering of information about that object, that can then facilitate the creation of stories around that object.



---
class: center, middle, title

# emerging trends

* .orange[Reproducibility]
* .orange[Webkit and the browser]
* .orange[HTML5/Markdown/JSON]


---
# Reproducibility

.slide_nav[.orange[reproducibility]]

---

.slide_nav[.orange[reproducibility]]

#### What’s the issue with reproducibility

[2011 - 80% of studies could not be replicated]([http://www.nature.com/nrd/journal/v10/n5/full/nrd3439.html)](http://www.nature.com/nrd/journal/v10/n5/full/nrd3439.html)

[AMGEN result - 88% could not be replicated]([http://www.reuters.com/article/2012/03/28/us-science-cancer-idUSBRE82R12P20120328)](http://www.reuters.com/article/2012/03/28/us-science-cancer-idUSBRE82R12P20120328)

[nature editorial on the topic]
([http://www.nature.com/nature/journal/v483/n7391/full/483531a.html)](http://www.nature.com/nature/journal/v483/n7391/full/483531a.html)

---
.slide_nav[.orange[reproducibility]]

### Efforts to address this problem

- computable papers
- [retraction watch](http://retractionwatch.com)
- [centre for open science - Reproducibility project](https://osf.io/ezcuj/wiki/home/)

---
.slide_nav[.orange[reproducibility]]

### Reproducibility Project Cancer Biology

- RPCB
 - our process
  - paper selection
  - registered reports
  - peer reviewed replication studies

---
.slide_nav[.orange[reproducibility]]

##  criticisms
 - expense
 - negative connotations of failing to get your paper replicated
 - waste of effort, more effort should be put into novel research

---
.slide_nav[.orange[reproducibility]]


## why can’t papers get replicated?
- lack of sharing of data
- poorly described protocols
- the experiment is just really hard


---
# The browser

.slide_nav[.orange[the browser]]

- Safari
- Electron

---
- Atom
- Slack
- avocode (http://www.theguardian.com/sport/2015/)
- other

---

## Classic Steps In Publishing
Most of these steps can now be implemented in the browser, or in a browser based app.

- Authoring
- Submission
- Peer review
- Document conversion
- Content enhancement
- Annotation
- Corrections cycle
- Pdf / print / pagination
- Downstream applications
- Search

--

- Authoring
	- Manuscripts.app
	- substance writer
- Submission  
	- Overleaf extension
- Peer review
- Document conversion
	- see lens demo in next session
- Content enhancement
- Annotation
	- hypothesis
- Corrections cycle
	- screenshot of tool from Ravi
- Pdf / print / pagination
	- vivlio style demo
- Downstream applications
	- HTTP / FTP
- Search
	- elasticsearch demo

---
.slide_nav[.orange[markup/markdown/html5]]

# Markup Markdown/ HTML5


This will go into more detail on some document conversion steps that might
be interesting to this group.

- http://scholdoc.scholarlymarkdown.com
-
- lens
- substance writer
- paged media standard

---
.slide_nav[.orange[markup/markdown]]

###  (vivliostyle demo)(http://www.vivliostyle.com/en/sample/)

- [http://blog.martinfenner.org/2015/04/23/introducing-scholarly-markdown-bundle/ ](http://blog.martinfenner.org/2015/04/23/introducing-scholarly-markdown-bundle/)
- http://scholarlymarkdown.com/Scholarly-Markdown-HTML-Schema.html


???
this is about the different options we have nowadays for transforming content from one kind into another, these include form mind maps to markdown to xml to JSON, and probably back around again.

---
.slide_nav[.orange[markup/markdown/html5]]
# Lens Demo

---
.slide_nav[.orange[markup/markdown/html5]]
# Slides Demo  


---
class: center, middle, title

# Speculative Trends

---
## Computational papers

.slide_nav[.red[computational papers]]

- encode project
- iPython/Project Jupityr
- nbviewer
- Bio.JS
- FigShare


???
describe the production process involved in creating
 the encode project, it was a bit of a mess.

---

## Living Papers

.slide_nav[.red[living papers]]

- wikipedia
- eLife research advances
- http://theoj.org
- https://github.com/ReScience/ReScience/wiki
- f1000 research

---
.slide_nav[.red[living papers]]

# Advances demo

---
.slide_nav[.red[living papers]]

# ReScience demo

- https://github.com/ReScience/ReScience/wiki


---
## The Blockchain & Science

.slide_nav[.red[the block chain and science]]

TODO: show data growth slides!!
