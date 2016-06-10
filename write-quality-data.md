## Lesson 8: How to write quality metadata

Tutorials on Data Management


![](images/quality-metadata/DataONE_LOGO.jpg)



## Lesson topics:
	1. Preparing to write metadata
	2. Tips for writing a quality metadata record






<section>
  <aside class="notes">
    The topics in this module will illustrate steps for preparation and writing of quality metadata. 

  </aside>
</section>





## Learning Objectives

After completing this lesson, participants will be able to:

	> List preparatory steps for writing metadata
	> Explain how and why to write quality metadata


## The DataONE Data Life Cycle


![](images/quality-metadata/datalifecycle.jpg)


<section>
  <aside class="notes">
    Metadata creation is a part of the “Describe” step in the data lifecycle. 


  </aside>
</section>



##  6 Steps to Creating Quality Metadata
1. Organize your information.
	-Did you write a project abstract to obtain funding for your proposal? Re-use it in your metadata! 
	-Did you use a lab notebook or other notes during the data development process that define measurements and other parameters? 
	-Do you have the contact information for colleagues you worked with?
	-What about citations for other data sources you used in your project?



## 
2. Write your metadata using a metadata tool
3. Review the record for accuracy and completeness
4. Have someone else read & review your record
5. Revise the record based on comments from reviewer
6. Review the record and then publish!



## Tips for writing quality metadata
1. Do not use jargon
2. Define technical terms and acronyms
3. Clearly state data limitations (eg. completeness, omissions) and considerations for data reuse
4. Use "none" or "unknown" meaningfully
	-"None" usually means that you knew about data and nothing existed (e.g., a “0” cubic feet per second discharge value)
	-"Unknown" means that you don’t know whether that data existed or not (e.g., a null value)

## 
5. Titles are critical for helping others find your data
	-Complete titles include: What, When, Where, Who, and Scale.
	-Informative titles include: topic, timeliness of the data, specific information about place and geography

## Example: Which is better?

A: Rivers

B: Greater Yellowstone Rivers from 1:126,700 U.S.Forest Service Visitor Maps (1961-1983)


## More Tips for Writing Quality Metadata
6. Be specific! Quantify when you can.
	Example: 
	"We checked our work using a random sample of 5 monitoring sites, reviewed by 2 people. We determined our work to be 95% complete based on these inspections."


## More Tips for Writing Quality Metadata
7. Select keywords wisely
8. Use descriptive & clear writing
9. Fully qualify geographic locations
10. Use standard domain thesauri for keywords when possible (eg. USGS Biocomplexity Thesaurus)


## More Tips for Writing Quality Metadata
11. Remember: a computer will read your metadata
12. Do not use symbols that could be misinterpreted 
13. Do not use tabs, indents, or line feeds
14. When copying and pasting from other sources, use a text editor to eliminate hidden characters 


## Summary

Review your final product to make sure that the documentation represents all of the information necessary to use or reuse the data.

Remember: a well-written title and good keywords are critical to data discovery!

## 
The full slide deck may be downloaded from: http://www.dataone.org/education-modules
Suggested citation:
DataONE Education Module: How to Write Good Quality Metadata. DataONE. Retrieved Nov12, 2012. From http://www.dataone.org/sites/all/documents/L08_WriteQualityMetadata.pptx 

Copyright license information: No rights reserved; you may enhance and reuse for your own purposes.  We ask that you provide appropriate citation and attribution to DataONE.







## Four Facets of Reproducibility


_Over the next week, we will focus on the tools and skills associated with these facets._

1. Organization
2. Automation
3. Documentation
4. Dissemination



## 1. Organization

The more self explanatory the better:

* Consider overall structure of folders and files.
* Use informative file names.

## 1. Organization Pro-Tip

> A variable name that describes the object is more useful than a random variable name.

##

![](images/intro-rr/basmati-rice.png)

##

<div style="width:85%">
![](http://journals.plos.org/ploscompbiol/article/figure/image?size=large&id=info:doi/10.1371/journal.pcbi.1000424.g001)
</div>

<a href="http://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1000424" target="_blank">
  Noble, William Stafford, 2009. A quick guide to organizing computational biology projects. </a>


## 1. Organization

File Organization should:

* Reflect inputs, outputs and information flow.
* Preserve raw data so it's not modified.
* Carefully document & store intermediate & end outputs.
* Carefully document & store data processing scripts.


## Organization

![](images/intro-rr/fileOrganization.png)

## 1. Organization -- File Names

File / Folder Names should be:

* Machine readable.
* Human readable.
* Support sorting.

## Which set of file names are most self-explanatory?
![](images/intro-rr/human-readable-jenny.png)


##
<a href="http://reproducible-science-curriculum.github.io/2015-09-24-reproducible-science-duml/naming-slides/assets/player/KeynoteDHTMLPlayer.html" target="_blank">More on file naming & organization</a>
 
-- from the Reproducible Science Curriculum.

## 1. Organization - Benefits

* Your future self will be able to quickly find files.
* Colleagues will be able to more quickly understand your workflow.
* Machine readable names can be quickly and easily sorted and parsed.


## 2. Automation Pro-Tip

Scripting vs. Point and click

>  Script = more time spent up front, but will save time in the long run.


## 2. Automation Pro-Tip
Time Savings:

* More efficient to modify and repeat an analysis down the road.
* Easier for reviewers and colleagues to see even aspect of your methods.
* Self documenting methods - your future self will likely forget small steps.

## 2. Automation

DRY -- Don't Repeat Yourself

> If your analysis is composed of scripts, with repeated code throughout, it will be more time consuming to maintain and update.

<a href="http://reproducible-science-curriculum.github.io/2015-09-24-reproducible-science-duml/slides/01-automation-slides.html#9" target="_blank">Reproducible Science Curriculum - Automation</a>


## Automation Tips

Modularity -- use functions to write code in reusable chunks.

* Variables created within a function are temporary.
* Code with functions can be easier to read / cleaner.
* Allows for better documentation.
* Supports testing.
* Allows for re-use of code on other data.

##

![](images/intro-rr/index.jpg)

## 2. Documentation

Document all workflow steps:

* You can remind your future self of your workflow.
* Others can see and understand your work.
* Future "re-analysis" of your data is more efficient.


## Documentation

Code should be easy to understand with clear goals

> Document your code even if you think it's clear and simple. Your collaborators
> & your future self will inevitably have an easier time working with it down the road.

## Documentation Pro-Tip 1

> Add comments around functions that describe purpose, inputs and outputs.


## Documentation Pro-Tip 2
>  Avoid proprietary formats: Use text files (.txt, .md) that don't require special tools to open.

## Documentation Pro-Tip 3
>  Markdown to style documentation = machine readable, small file size, low overhead.

## Documentation Pro-Tip 4

Use coding approaches that connect data cleaning, analysis & results

> R Markdown and IPython / Jupyter notebooks allow you to publish code and results
in one (or more) output files.



## Dissemination

> Publishing is not the end of your analysis, rather it is a way towards
> your future research and the future research of others.

## Dissemination - Why

* Funding agency / journal requirement.
* Community expects it.
* Increased visibility / citation.
* More efficient, less redundant science.





## Dissemination workflow



Example Workflow / Tools (R focused):



* Document workflow: **R Markdown / Jupiter Notebooks**

* Collaborate with Colleagues / Version Control : **GitHub**

* Publish Data Snapshot: **FigShare, Dryad, etc**

* Share workflow: ** RPubs , IPython Notebook Viewer**





## Four Facets of Reproducibility



_An overview of some of the topics, tools and skills that we will cover during 
the Data Institute_



1. Documentation - RMarkdown, GitHub

2. Organization - File naming / directory structure best practices.

3. Automation - Efficient Coding Practices (in R)

4. Dissemination - GitHub



## Questions?



Email: neondataskills@neoninc.org

