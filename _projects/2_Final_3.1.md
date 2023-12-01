---
name: Does Your Professor Really Matter?
tools: [Python, Altair, vega-lite]
image: assets/jpegs/siebel-center-computer-science.jpg
description: Final Project Part 3.1 - IS445
custom_js:
  - vega.min
  - vega-lite.min
  - vega-embed.min
  - justcharts
---


# **Does your Professor Really Matter?**
### Authors: Jackson Clark, Evan Chen

---
In university settings, students face a significant shift from their grade school experiences. Unlike the smaller, more intimate classes of their earlier education, they now select their majors and attend lectures alongside hundreds of peers. This transition from a personalized learning environment to one that is more impersonal and vast raises a crucial question: **In the realm of higher education, where choice and large-scale teaching are prevalent, how influential is the role of the professor?** While many individuals attribute their passion for a subject to inspiring teachers, or their aversion to it due to less favorable experiences, the impact of university professors in large lecture settings remains an intriguing aspect to explore.

One of the best measurements of academic performance is the **Average GPA** (grade point average) of a course. At the University of Illinois Urbana-Champaign, each student completing a course attains a letter grade that [converts to a particular GPA value](https://registrar.illinois.edu/courses-grades/explanation-of-grades/) - considering all students in a course section, we can find that section's Average GPA. To investigate our question, we've taken a [dataset containing UIUC GPA information](https://raw.githubusercontent.com/wadefagen/datasets/master/gpa/uiuc-gpa-dataset.csv) and created an **interactive visualization** of some of the most popular Computer Science (CS) courses at Illinois. Below, you'll find a bar chart displaying the specific sections of a CS course alongside that section's Average GPA - **colored by the professor** teaching said course. This way, we're able to identify any student performance differences from different professors for the same course. 

Hovering over any bars in the chart below will display a custom tooltip containing information being depicted by said bar: the **detailed section information** and the **Average GPA**. We've generated this detailed section information in the following format:

```
DetailedSection: <professor name> - <year-term> - <course number> - <section number>
```

Here, 
- `<professor name>` is the last name, first name of the primary professor of the section
- `<year-term>` is the combination of year and term of the section - possible terms include Fall (fa), Spring (sp), Summer (su), and Winter (wi)
- `<course number>` is the course number of the CS class
- `<section number>` is the unique section number for that professor, year, and term because some professors teach multiple sections in a single semester!

As an example, the detailed section `Evan, Graham C - 2023-sp - 225 - 1` describes the first section of CS 225 taught by Prof. G. Carl Evans in Spring 2023.

By default, the visualization displays a breakdown of Average GPA by section and instructor for CS 225: Data Structures. We've chosen to show you this course first due to its strong variety in teaching staff, but we **encourage exploration** of other CS courses by selecting them from the `Course` **dropdown below the chart**. To use the dropdown, click the box containing `CS 225` and select a course from the dropdown list to visualize.

<br>
<br>

<vegachart schema-url="{{ site.baseurl }}/assets/json/final-proj-3.1-main.json" style="width: 100%"></vegachart>

<br>

Our `Course` dropdown immediately above this text supports the following courses for selection: 
- CS 105 - Intro Computing: Non-Tech
- CS 173 - Discrete Structures
- CS 225 - Data Structures
- CS 374 - Introduction to Algorithms & Models of Computation
- CS 446 - Machine Learning

We've chosen these courses due to a combination of their popularity in the Computer Science program and them having multiple different primary instructors.

---

## Contextual Data: UIUC's Graybook
Investigation of a professors' role in course quality and student performance inherently raises tangential questions about the distribution of professors at a program. Because we've looked into the distribution of Average GPAs across particular sections and professors in **CS courses** above, it is fitting to visualize the professors in the **CS department** at the University of Illinois Urbana-Champaign. 

Using a [dataset of Spring 2023 faculty appointment information](https://raw.githubusercontent.com/zuyouchen/107_datasets/main/graybook/graybook-clean-sp23.csv) previously scraped by Evan and originating from the public [UIUC Graybook](https://www.bot.uillinois.edu/resources/gray_book), we generated contextual visualizations of Spring 2023 UIUC **CS professor demographics**.

### Faculty Titles
The professors of UIUC's CS department hold various different titles depending on their **work experience and responsibilities**. Naturally, these titles may influence and/or indicate their effort, performance, and quality of instruction. We've generated a bar chart depicting the number of Spring 2023 CS professors holding particular job titles below. For additional context:
- The [progression of titles](https://humanresources.illinois.edu/employees/current-employees/faculty/Tenure-System/index.html) generally follows Assistant Professor -> Associate Professor -> Professor, with tenured faculty holding the latter two titles and faculty working towards tenure holding the former 
- Titles prefixed by "Research" indicate faculty focused primarily on research
- Titles prefixed by "Teacing" indicate faculty focused primary on teaching 

<br>

<vegachart schema-url="{{ site.baseurl }}/assets/json/final-proj-3.1-contextual-job-titles.json" style="width: 100%"></vegachart>

---

### CS Professor Tenure
An implication of the faculty titles above that can be more directly visualized is the tenure status of UIUC's CS professors. Tenure refers to a status granted to experienced faculty after years of evaluation, serving as the primary form of **job security** for professors. With the same [graybook dataset](https://raw.githubusercontent.com/zuyouchen/107_datasets/main/graybook/graybook-clean-sp23.csv) of Spring 2023 UIUC faculty, we've generated a bar chart displaying the distribution of UIUC CS professors in specific tenure status - including those whose status are unknown.

<br>
<br>

<vegachart schema-url="{{ site.baseurl }}/assets/json/final-proj-3.1-contextual-tenure.json" style="width: 100%"></vegachart>

---
## The Data & Methods

Below, we provide links to both datasets and the analysis code used to generate all visualizations as buttons.

The UIUC GPA Dataset powered the first visualization. The SP23 Graybook Dataset powered the following two contextual visualizations. The analysis code linked was used to generate **all three visualizations** on this page.

The image used for this page's thumbnail is of [UIUC's Siebel Center for Computer Science](https://cs.illinois.edu/about/contact-us#page-gallery-1). 

<!-- these are written in a combo of html and liquid --> 

<div class="left">
{% include elements/button.html link="https://raw.githubusercontent.com/wadefagen/datasets/master/gpa/uiuc-gpa-dataset.csv" text="The UIUC GPA Dataset"%}
</div>


<div class="right">
{% include elements/button.html link="https://github.com/zuyouchen/zuyouchen.github.io/blob/main/python_notebooks/Final-3.1-analysis.ipynb" text="The Analysis Code" %}
</div>

<br>

<div class="left">
{% include elements/button.html link="https://raw.githubusercontent.com/zuyouchen/107_datasets/main/graybook/graybook-clean-sp23.csv" text="The SP23 Graybook Dataset"%}
</div>
