# The process of submitting an article to LiveCoMS

## Introduction

Submitting an article to LiveCoMS is substantially different from
submitting an article to most journals.  
In this article, we lay out the process by which authors create an article, submit it to LiveCoMS, and update it over time to create a living document.  

## General Article Guidelines

There are no explicit length limits on any manuscript. 
Articles do not need to contain original research, but may contain it.

## Types of Articles

**Best Practices Manuscripts**: The goal of best practices manuscripts are to improve the quality of simulation research by providing advice that can eliminate the most common errors. 
These documents consist of:

A. A succinct list of steps that people should follow when carrying out the task in question. This is effectively a "checklist", provided to ensure certain basic standards are followed and common but 
critical major errors are avoided.

B. A much more detailed section with the necessary rationale for the checklist, which would act as more complete "best practices" description, with significant detail as to the possible alternative ways to accomplish a given task, when one would be better than another, and significant literature documentation about reasons for choices.

The inspiration for Best Practices documents can be found in the Atul
Gawande article [The
Checklist](http://www.newyorker.com/magazine/2007/12/10/the-checklist),
later expanded in his bestseller [The Checklist
Manifesto](http://atulgawande.com/book/the-checklist-manifesto/). The
main goal of these documents is to reduce common errors by ensuring
appropriate choices are made throughout a difficult task. 

For our purposes, simulation checklists should help users avoid the
most common reasons for failure or incorrect results. Checklists will
typically also be accompanied by an explanation with sources, so the
rest of the document can go into more detail on best practices and
cover more possible failure modes and how to avoid them. One can
divide the types of errors that are made performing molecular
simulations into (a) mistakes experienced researchers often make, (b)
mistakes new users often make, even after having received solid
training in fundamentals of molecular simulation. Most checklists will
be focused on these types of failures.  A third type (c), would
involve preventing mistakes of naive users who do not understand the
basic principles of molecular simulation. These will usually require
special documents aimed at novice users which serve as prerequisites
for more detailed documents.

**Perpetual Reviews**: 
Perpetual reviews, like standard reviews, except that they can be
updated as information comes out, and can be responsive to community
input, and remain up to date on the current state of the field as it
evolves. 
An example of this process can be found in the [Mobley et
al. review](https://github.com/MobleyLab/benchmarksets), which was
originally an "Annual Reviews in Biophysics" article, but is now being
updated regularly on GitHub.

**Comparisons of Molecular Simulations**:
Simulation comparison papers describe attempts to perform the same
calculation with a range of different simulation programs.  
Such comparison should be updated periodically with different versions of
the same programs (or potentially additional programs).

**Tutorials**:
Tutorials are articles that come accompanied by web pages with walkthroughs and downloadable files to work with. 
These take users through specific tasks or sequences of tasks to help them learn how to do these tasks on their own for other applications or purposes. 
Tutorials should endeavor to not just cover the specific task at hand, but also highlight how the steps might need to be modified (or additional care might need to be taken at particular points) to handle more general cases. 
Tutorials for specific software packages must provide instructions and files for the current version of the software.  
The submission of existing tutorials, so long as they meet journal standards, is explicitly welcomed, to encourage the highest quality tutorials by providing some degree of academic credit for these important and time-consuming efforts.

# Before Submission

## Presubmission Letter

Authors should first send a presubmission letter to the lead an editor in the relevant area.  The letter should be no more than one page, and should:
* Outline the scope of their best practice document or review.
* Explain how the proposed manuscript is different than existing best practices articles or reviews. 
* Note whether it is adapted from a previous article (and identify the article if so).
* Explain the expertise that the proposed authors have on the subject.
* Describe the license that the authors will use that will enable the article to be released freely to the public.

Potential authors submitting a presubmission letter will typically receive an answer within two weeks with either encouragement for a full submission, suggestion to work with previous authors on existing articles, or discouragement.
Articles should be received within six months of a notification of encouragement.

## Preparation of Preprint Document

The authors should prepare the document using
[LaTeX](https://www.latex-project.org/) in a public repository owned
by one of the authors on [GitHub](http://wwww.github.com). 
LiveCoMS [provides template LaTex files to start from](http://www.github.com/livecoms/author_templates), and instructions for exactly how to structure the documents. 
We require that articles that are submitted to LiveCoMS use these templates for the articles so that the journal has a consistent visual presentation.

For an example of such an article, see [the following perpetual review](https://github.com/MobleyLab/benchmarksets). 
Questions, comments, or additions from the community would be filed as issues and then could be incorporated. 

One written, the authors post the resulting PDF document to a preprint server of their choice, which can be any one of:
* [ArXiv](https://arxiv.org)
* [BioRxiv](http://www.bioarxiv.org)
* [ChemRxiv](https://chemrxiv.org/)
* [Faculty of 1000 Research](https://f1000research.com)
* Any of the [Open Science Framework preprint servers](https://osf.io/preprints/) (engrXiv, etc.)

Posting to the preprint server can be done at any time before review. 

## The Review Process

After posting to the preprint server, the author will upload the final
PDF files (which have been created using the [LiveCoMS
templates](http://www.github.com/livecoms/author_templates) for
consistent formatting) and a link to the GitHub site of the articles.

The authors must also submit a cover letter with suggestions for 4--5
reviewers, and noting any deviations from the presubmission letter.

The editors will choose reviewers, which may include the editors themselves.  
Reviews will generally be anonymous, though reviewers will be allowed to become known if they desire, and can participate
directly in revisions through the GitHub website.

A key purpose of the articles is that they should be useful to a range of researchers, but
especially beginning researchers. 
Thus, all best practice and review articles will be reviewed by a member of the student review board, which consists of graduate students and postdocs invited by the editorial board.

Authors are also encouraged to have other researchers review their
content, with comments and responses done via the GitHub issue
tracker. 
A history of revisions in response to community issues will favorably
help the review.

Reviews will also consider the following factors according to manuscript category:

* Best practice guides
    * Would following the checklists help users avoid significant potential errors in simulation? Will the errors be profound and/or frequent? 
    * Are all assertions well sourced in published data (which may, in some cases, include data created for the document)?
    * Are the explanations clear enough for researchers with only moderate training in simulation?

* Perpetual reviews
    * Do the authors properly include information from the recent literature, including last 6 to 12 months?
    * Have the authors removed data that is out of date, and qualified information that has been disproven or contradicted?
    * Do the authors include data and viewpoints that are contradictory to their own?

* Comparisons of molecular simulation programs
    * Does the paper include developers or advanced users of all programs being compared to ensure that comparisons are fair?
    * Are best practices being used in the simulation comparisons?

* Tutorials:
    * Are files to run the simulations posted online in a permanent (or nearly so) way?
    * Are the tutorials helpful and educational?
    * Do they include enough information on how to generalize the approach to handle other cases, and highlight major issues to consider?
    * Do the tutorials use commonly agreed on best practices?

## Manuscript Revisions Process

If manuscript revision is requested, authors will be asked to re-submit within 14 days for minor revisions and 30 days for major revisions. 
After this time, a revised manuscript will be handled as a new submission.

### Versioning

A unique aspect of LiveCoMS is article versions. New versions of manuscripts can be submitted for peer review, to be treated as new publications, with new DOI’s.  Versioning should generally be done no more frequently than every 12 months.  

The review process for a revision to be listed as a new version of the document will be similar to the review process for the initial version.  Additional review criteria will include whether or not issues the community raised were responded to, and whether the revision includes sufficiently new material. 

* Best practice guides: These articles  may start with more frequent versions, as initial rounds of community input are solicited. Authors are encouraged to update their private GitHub versions as frequently as desired. 

* Perpetual Reviews: Authors will be asked to update reviews at least once every 36 months for reviews, and will be encouraged to change authors as needed so the review can be maintained, or else the review will be “made emeritus” and indicated as out of date on the site.  We recommend updating at least every 24 months.  However, Authors decide when it is time to re-version based on feedback they receive. 

* Tutorials: Authors should generally update reviews when the software used for the tutorial such that the tutorial description no longer gives substantially similar results.


## Authorship and Revisions

Authorship for a "living" document like those that LiveCoMS publishes
becomes complicated as the document evolves, and more people
contribute. 
A general principle that LiveCoMS has is that participants
(authors, people providing feedback and filing issues, etc.) should
get credit for their contributions. 
In general, changes which constitute writing a significant part of the article merit authorship,
but not those which do not constitute smaller portions.  These smaller changes, however, should still be acknowledged.

In order to acknowledge these contributors, people who offer comments/citations that are used in the paper should be listed listed on the relevant GitHub repository README markdown file, and should be listed in the acknowledgement section of the paper. 
However, if the current authors feel that the contributions rise to the level of authorship, they can add new authors when the next major version is submitted.


Exactly what constitutes a "significant" contribution is by necessity subjective, and authors should endeavor to be generous.In the process of reviewing revisions, editors will examine the history of the GitHub repository to ensure appropriate credit is being given. 
If contributors feel that they should be given authorship based on the number of accepted commits, the editors will help resolve any disputes. 
If contributors feel that their commits are not being accepted by the authors they should first strive to convince the authors and the community that are reviewing the document through better documented and more convincing arguments. 
If authors do not engage with substantial issues that have been raised, they may be asked to address these issues in the review process. 
If authors do not substantively engage in the discussions on issues that are raised, this may prevent new updates of the review from being accepted.

## Other Policies for Submitted Articles

### Funding Compliance
Authors are required to report funding sources and grant/award numbers relevant to the manuscript for ALL authors.

Authors should note whether any funding could be perceived as a conflict of interest, e.g., an article describing software in which an author has a financial interest.

### Licensing 

LiveCoMS does not require any copyright transfer to the journal.  
Instead, LiveCoMS requires some license that allows LiveCoMS to distribute the articles freely consistent with Open Access requirements. 
We recommend that all submissions to LiveCoMS be released by the author under a Creative Commons By Attribution license version 4.0.

### Policy on Prior Publication

Documents should not have been submitted in the current form to another journal, or be simultaneously under consideration for publication another journal. 
Preprints (previous to the one submitted to LiveCoMS) do not count as prior publication. 
Documents that are major revisions of previously published articles are welcomed. 
However, authors should ensure that material they develop for the journal does not have rights reserved by other journals from such previous publication that impede release under open licenses. 
Some journals, for example, “Annual Reviews” let the authors retain rights for derivative works, which could be exercised in preparing a review to be published in LiveCoMS. 

If an article is an adaptation of a previously published article, it must be noted in the cover letter, and major changes noted. 
Evaluating whether such changes constitute a significant revision will be part of the review process.

