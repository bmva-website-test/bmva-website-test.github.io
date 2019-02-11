---
layout: submission
title: Call for Submissions
excerpt: "Submit your work to Expressive 2018"
year: 2018
---

Being at the forefront of expressive rendering research since 2012, [Expressive 2018](http://expressive.graphics/2018) will take place in Victoria, British Columbia, Canada, August 17–19, 2018 --- shortly after [SIGGRAPH 2018](http://s2018.siggraph.org/) in Vancouver. A single registration for Expressive 2018 will include all three workshops.
Invited talks and artists talks will be shared among the workshops and sessions will be mixed. The submission, review, and publication process for the event will be handled jointly across the three conferences.

---

## Call for Papers
{: .top2}

[<span class="glyphicon glyphicon-file"></span> Call for Papers (PDF)](/docs/expressive-2018-call-for-papers-v04.pdf)

{::options parse_block_html="true" /}

<div class="panel panel-warning">
#### Important dates
{: .panel-heading}
<div class="panel-body">

{% capture nowtime %}{{'now' | date: '%s'}}{% endcapture %}{% capture nowtime %}{{'now' | date: '%s'}}{% endcapture %}
{% capture abstractduetime %}{{site.symposium[page.year].abstract | date: '%s'}}{% endcapture %}
{% capture paperduetime %}{{site.symposium[page.year].paper | date: '%s'}}{% endcapture %}
{% capture extensionduetime %}{{site.symposium[page.year].extension | date: '%s'}}{% endcapture %}
{% capture acceptanceduetime %}{{site.symposium[page.year].acceptance | date: '%s'}}{% endcapture %}
{% capture camerareadyduetime %}{{site.symposium[page.year].camera-ready | date: '%s'}}{% endcapture %}

| __Abstract due:__ {% if abstractduetime < nowtime %}~~{% endif %}{{ site.symposium[page.year].abstract }}{% if abstractduetime < nowtime %}~~{% endif %} |
| __Paper submission deadline:__ {% if paperduetime < nowtime %}~~{% endif %}{{ site.symposium[page.year].paper }}{% if paperduetime < nowtime %}~~{% endif %} |
{% if site.symposium[page.year] contains 'extension' %}| __Extended deadline:__ {% if extensionduetime < nowtime %}~~{% endif %}{{ site.symposium[page.year].extension }}{% if extensionduetime < nowtime %}~~{% endif %} |{% endif %}
| __Acceptance notification:__ {% if acceptanceduetime < nowtime %}~~{% endif %}{{ site.symposium[page.year].acceptance }}{% if acceptanceduetime < nowtime %}~~{% endif %} |
{% if site.symposium[page.year] contains 'camera-ready' %}| __Camera-ready submission:__ {% if camerareadyduetime < nowtime %}~~{% endif %}{{ site.symposium[page.year].camera-ready }}{% if camerareadyduetime < nowtime %}~~{% endif %} |{% endif %}
| |
| All deadlines are at 23:59:59 UTC/GMT |

</div>
</div>

{::options parse_block_html="false" /}

Expressive is a joint Symposium featuring the following workshops:

* **Computational Aesthetics (CAe)**
* **Non-photorealistic Animation and Rendering (NPAR)**
* **Sketch-based Interfaces and Modelling (SBIM)**

Each paper submission should be designated as belonging to one of the three tracks.

{::options parse_block_html="true" /}

<div class="panel panel-default">
#### Computational Aesthetics (CAe)
{: .panel-heading}
<div class="panel-body">

Computational Aesthetics integrates the bridging aspects of computer science, philosophy, psychology, and the fine, applied & performing arts. CAe investigates both tools to enhance the expressiveness of fine and applied arts, as well as theoretical approaches that further our understanding of aesthetic evaluation, perception and meaning.

</div>
</div>

{::options parse_block_html="false" /}

{::options parse_block_html="true" /}

<div class="panel panel-default">
#### Non-Photorealistic Animation and Rendering (NPAR)
{: .panel-heading}
<div class="panel-body">

Non-Photorealistic Animation and Rendering investigates computational techniques for visual communication. Such techniques usually focuses on imagery and motion which is expressive, rather than photorealistic, although they may incorporate realistic elements.

</div>
</div>

{::options parse_block_html="false" /}

{::options parse_block_html="true" /}

<div class="panel panel-default">
#### Sketch-Based Interfaces and Modeling (SBIM)
{: .panel-heading}
<div class="panel-body">

Sketch-Based Interfaces and Modeling focuses on the exploration of models, algorithms, and technologies for efficient sketch-based interfaces. It investigates the classification and recognition of hand-drawn shapes, and ways of using these techniques for creating or editing digital models, text, mathematics or 3D shapes.

</div>
</div>

{::options parse_block_html="false" /}

### Submission Types
{: .top1}

Paper submissions are invited across the broad range of areas covered by Expressive. We welcome papers in several categories:

* __Research:__ new algorithms, scientific studies, analysis, or data (i.e., traditional academic papers). These must contain novel results that make a substantive contribution to the field.
* __Production:__ candid discussion of the process of creating a work (e.g., film, image, game) or art tool (e.g., paint or CAD program, software library). We are equally interested in papers on the use of existing techniques combined in novel ways, or applying them in a new or unusual context.
* __Meta:__ statements about research that do not contain new results, e.g.: grand challenges, position papers, evaluation standards, surveys, and primers on art / aesthetics / psychophysics for a computer science audience. We welcome papers that discuss the challenges of bridging computational expression across disciplines.

Accepted papers will be published as a single conference proceedings by the ACM and will be available online via the [ACM Digital Library](http://dl.acm.org/). Papers will also be archived in the [Eurographics Digital Library](https://diglib.eg.org/).

**Authors of selected papers will be invited to submit extended versions of their manuscripts to be considered for publication in a special section of [Computers & Graphics](https://www.journals.elsevier.com/computers-and-graphics/) journal (Elsevier) via a fast-track review process.**

{::options parse_block_html="true" /}

<div class="panel panel-default">
#### Topics include, but are not limited to:
{: .panel-heading}
<div class="panel-body">

* Analysis and modeling of creative behavior (AI, A-life)
* Simulation of natural media, traditional styles, and novel artistic styles
* Analysis of image style and saliency (paintings, photographs, others)
* Visualization techniques
* Simplification and abstraction techniques (e.g. sketching, indication)
* Empirically-based metrics of aesthetic attributes
* Applied visual perception
* Interaction techniques (e.g. sketch, gestural, multi-touch, multi-modal)
* Sketch-parsing, classification and recognition
* Novel interfaces for art creation, modeling, control, sketch input, etc.
* Study designs and methodologies for evaluating and validating sketch-based systems, aesthetic metrics, visual communication systems, etc.
* Advanced rendering techniques (e.g. volumetric, GPU, mobile, multi-modal)
* Applications in special domains: Medicine, Geology, Biology, Sociology, etc.
* Sketch-based information retrieval
* Stylistic or aesthetic aspects of character animation and simulated physics
* Accounts of real productions (e.g., animated films, digital art) or applications in software products (e.g., modeling, visualization, presentation software)
* Visual composition
* Design, rendering, and evaluation of layouts for text and presentation graphics
* Example-based style transfer
* Temporal and spatial coherence
* Aesthetic evaluation and stylistic rendering of visual effects such as motion blur, depth of field, and lighting
* Non-traditional camera models


</div>
</div>

{::options parse_block_html="false" /}

### Submission Information
{: .top1}

All work must be previously unpublished. Production and Meta papers need not contain original research or results, but must make a substantive contribution to the knowledge in the field. Papers should be 8–10 pages in length (excluding citations). Papers longer than 10 pages must make a very significant contribution.

Paper submission is electronic using the [EasyChair system]({{site.symposium[2018].submission}}).

For detailed instructions to submit papers, posters, videos and other materials, please view the [submission instructions](http://expressive.graphics/2018/instructions/).

---

## Call for General Submissions
{: .top2}

[<span class="glyphicon glyphicon-file"></span> Call for General Submissions (PDF)](/docs/expressive-2018-call-for-general-submissions-v02.pdf)

{::options parse_block_html="true" /}

<div class="panel panel-warning">
#### Important dates
{: .panel-heading}
<div class="panel-body">

{% capture nowtime %}{{'now' | date: '%s'}}{% endcapture %}{% capture nowtime %}{{'now' | date: '%s'}}{% endcapture %}
{% capture generalsubmissionduetime %}{{site.symposium[page.year].general-submission | date: '%s'}}{% endcapture %}

| __Artwork submission deadline:__ Rolling notification, closes {% if generalsubmissionduetime < nowtime %}~~{% endif %}{{ site.symposium[page.year].general-submission }}{% if generalsubmissionduetime < nowtime %}~~{% endif %} |
| __Poster/Demos submission deadline:__ Rolling notification, closes {% if generalsubmissionduetime < nowtime %}~~{% endif %}{{ site.symposium[page.year].general-submission }}{% if generalsubmissionduetime < nowtime %}~~{% endif %} |
| |
| All deadlines are at 23:59:59 UTC/GMT |

</div>
</div>

{::options parse_block_html="false" /}

Expressive 2018 will continue to host a gallery for 2D and 3D artworks, sculptures, animations, posters and demonstration projects, where artist installations and computational demonstrations will be featured side-by-side. In this category, we focus on recent research and creative activities at the intersection of arts and sciences. We are open to any work that is related to topics of the Expressive 2018 conferences (Computational Aesthetics, Sketch-Based Interfaces and Modeling, and Non-Photorealistic Animation and Rendering). The authors of accepted works will be invited to present their work through a panel discussion or short oral presentation within the main Expressive 2018 conference. Accepted works will be archived through the ACM Digital Library.

### Topics

General Submissions seeks for submissions for posters, demos and art exhibition in the three main tracks of Expressive Conference. We are interested in a wide variety of works that bridge arts and sciences. We are particularly interested in techniques for visually communicating ideas and information and for sketch based interaction and modeling integration through integration of computer science, mathematics, philosophy, psychology, and the fine, applied & performing arts.

Expressive solicits extended abstracts for poster, demo and art exhibition proposals. Accepted works will be demonstrated and exhibited during the conference. We expect these works will pose new questions and motivate further research in three main areas of Expressive Conference: (1) Computational Aesthetics; (2) Sketch Based Interfaces and Modeling; and (3) Non-Photorealistic Animation and Rendering.

Accepted general submissions (posters/demos/artworks) will be published together with the accepted papers as a single conference proceedings by the ACM and will be available online via the [ACM Digital Library](http://dl.acm.org/). Accepted submissions will also be archived in the [Eurographics Digital Library](https://diglib.eg.org/).

### Guidelines

We seek poster, demo and art exhibition submissions that show work that pertains to all three tracks of Expressive 2018. All submissions should be in the form of a two-page or longer abstract, written in English, and should follow the SIGGRAPH formatting instructions, including a title page with an abstract, keywords, and a bibliography. Submissions should provide a clear description of the work and the process. Posters, demos and artworks will be demonstrated and/or displayed at the conference venue. Authors of accepted works in all areas of submitted work are encouraged to bring a demonstration of their work as well; it is not necessary to create a separate submission for a poster and a demo if they refer to the same project.

General submission are in electronic form. Please directly email your submission to the conference email: [expressive2018@uvic.ca](mailto:expressive2018@uvic.ca). Please include the following information, and attach your submission materials in the email::

**Title: <br/>
Author(s) Name:<br/>
Authors' Institution(s):<br/>
Primary Contact's Email (if not the same as the communicating address):<br/>
Project Website (if applicable):<br/>
Intended Printing Size (width/height):**


For detailed instructions to submit papers, posters, videos and other materials, please view the [submission instructions](http://expressive.graphics/2018/instructions/).


---

## Call for Journal Presentations
{: .top2}

[<span class="glyphicon glyphicon-file"></span> Call for Journal Presentations (PDF)](/docs/expressive-2018-call-for-journal-presentations-v02.pdf)

{::options parse_block_html="true" /}

<div class="panel panel-warning">
#### Important dates
{: .panel-heading}
<div class="panel-body">

{% capture nowtime %}{{'now' | date: '%s'}}{% endcapture %}{% capture nowtime %}{{'now' | date: '%s'}}{% endcapture %}
{% capture journalsubmissionduetime %}{{site.symposium[page.year].journal-submission | date: '%s'}}{% endcapture %}

| __Presentation of work previously published in a journal:__ Rolling notification, closes {% if journalsubmissionduetime < nowtime %}~~{% endif %}{{ site.symposium[page.year].journal-submission }}{% if journalsubmissionduetime < nowtime %}~~{% endif %} |
| |
| All deadlines are at 23:59:59 UTC/GMT |

</div>
</div>

{::options parse_block_html="false" /}

As at previous events, we will include a submission category for the presentation of work previously published in a journal. The intent of this category is to allow authors of journal papers the opportunity to present their research at Expressive. These papers will not appear in the Expressive proceedings.

### Guidelines

The work should be published in the July 2017 – July 2018 time-frame, and not have been previously presented at a conference or symposium. A copy of the paper abstract and a link to the published paper or preprint should be submitted via email to the program chairs. Submissions will be reviewed by the program committee. Note that accepted presentations are subject to the same rules as regular papers, namely that at least one author must register for the conference.

---
{::options parse_block_html="true" /}

<div class="panel panel-default">

#### Conference Chairs
{: .panel-heading .top2}
<div class="panel-body">

| __General Chairs:__ || {{ site.chairs2018.general }}, _{{ site.chairs2018.generalAff }}_
|                     || {{ site.chairs2018.general2 }}, _{{ site.chairs2018.general2Aff }}_
| __Paper chairs:__   || {{ site.chairs2018.paper }}, _{{ site.chairs2018.paperAff }}_
|                     || {{ site.chairs2018.paper2 }}, _{{ site.chairs2018.paper2Aff }}_
| __Art chair:__      || {{ site.chairs2018.art }}, _{{ site.chairs2018.artAff }}_
| __Publicity chairs:__      || {{ site.chairs2018.publicity }}, _{{ site.chairs2018.publicityAff }}_
|                     || {{ site.chairs2018.publicity2 }}, _{{ site.chairs2018.publicity2Aff }}_ ||

</div>
</div>

{::options parse_block_html="false" /}
