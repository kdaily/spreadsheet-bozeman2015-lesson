---
layout: lesson
root: .
lastupdated: August 18, 2015
contributors: ["Christie Bahlai", "Aleksandra Pawlik", "Jennifer Bryan", "Alexander Duryee", "Jeffrey Hollister", "Daisie Huang", "Owen Jones", "Ben Marwick", "Tracy Teal", "Kenneth Daily"]
maintainers: ["Aleksandra Pawlik", "Tracy Teal"]
domain: Biology - Bozeman 2015
topic: Spreadsheets
software: Spreadsheets
dataurl: https://www.synapse.org/#!Synapse:syn4951755
status: Teaching
---

<!-- USING THIS LESSON TEMPLATE -->
<!-- Lesson specific information is taken from the YAML header at the top of the page -->

<!-- THE LESSON INFORMATION -->


#Data Carpentry {{ page.topic }} for {{ page.domain }}
=======

Data Carpentry's aim is to teach researchers basic concepts, skills,
and tools for working with data so that they can get more done in less
time, and with less pain. The lessons below were designed for those interested
in working with {{page.domain %}} data in {{page.topic %}}.


**Content Contributors: {{page.contributors | join: ', ' %}}**


**Lesson Maintainers: {{page.maintainers | join: ', ' %}}**


**Lesson status: {{ page.status }}**

### Instructors
See [Instructor notes](http://datacarpentry.github.io/spreadsheet-ecology-lesson/instructor_notes.html) on how to teach this lesson.

<!--
  [Information on Lesson Status Categories]()
-->

<!-- ###### INDEX OF LESSONS ON THIS TOPIC ###### -->

## Lessons:

1. [Introduction](00-intro.html)
1. [Formatting data](01-format-data.html)
1. [Common formatting problems](02-common-mistakes.html)
1. [Dates as data](03-dates-as-data.html)
1. [Exporting data](05-exporting-data.html)
1. [Data Format Caveats](06-data-formats-caveats.html)
1. [Synapse for data storing and provenance](07-Synapse.html)


## Data

Data files for the lesson are available in Synapse here: [{{page.dataurl %}}]({{page.dataurl %}})

You can also get this file from the `R` client:

```
library(synapseClient)
synapseLogin()
obj <- synGet("syn4951755")
getFileLocation(obj)
```

Or the Synapse command line client:

```
#> synapse get syn4951755
```

### Requirements

Data Carpentry's teaching is hands-on, so participants are encouraged to use
their own computers to insure the proper setup of tools for an efficient workflow.
*These lessons assume no prior knowledge of the skills or tools*, but working
through this lesson requires working copies of the software described below.
To most effectively use these materials, please make sure to install everything
*before* working through this lesson.

In this version of the course, we are using an Amazon image. You can do this work there, but it will probably work just as well from your own laptop.


{% if page.software == "Python" %}
{% include pythonSetup.html %}
{% elsif page.software == "Spreadsheets" %}
{% include spreadsheetSetup.html %}
{% elsif page.software == "R" %}
{% include rSetup.html %}
{% else %}
{% include anySetup.html %}
{% endif %}

<p><strong>Twitter</strong>: @datacarpentry
