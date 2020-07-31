---
layout: page
permalink: /study-aids/
title: Study Aids

---

# Outlines

{% for outline in site.outlines %}
<p><a href="{{ site.baseurl }}{{ outline.url }}">{{ outline.title }}</a></p>
{% endfor %}

# Review Problems

{% for problem in site.problems %}
<p><a href="{{ site.baseurl }}{{ problem.url }}">{{ problem.subtitle }}</a></p>
{% endfor %}

# Visuals

## Introduction

[Civil Action Flowchart]({{ site.baseurl }}/assets/img/introduction/CivilAction.png)

[Federal Courts]({{ site.baseurl }}/assets/img/introduction/FedCourts.png)

[Federal District Courts in North Carolina]({{ site.baseurl }}/assets/img/introduction/NC_FedCourts.png)

## Joinder

[Counterclaims]({{ site.baseurl }}/assets/img/joinder/Counterclaims.png)

[Third Party Claims]({{ site.baseurl }}/assets/img/joinder/Rule14.png)

[Sample Motion to Intervene]()

[Joinder Review Problem]({{ site.baseurl }}/assets/img/joinder/NightAtTheOpera.png)

## Subject Matter Jurisdiction

[Joinder & Subject Matter Jurisdiction]({{ site.baseurl }}/assets/img/joinder/Joinder-SMJ.png)

[Supplemental Jurisdiction under § 1367]({{ site.baseurl }}/assets/img/subject-matter-jurisdiction/1367.png)

[§ 1367(b) Illustration]({{ site.baseurl }}/assets/img/subject-matter-jurisdiction/1367b_Illustration.png)

## Personal Jurisdiction

[World Wide Volkswagen]({{ site.baseurl }}/assets/img/personal-jurisdiction/WWVW.png)

[Asahi Metal]({{ site.baseurl }}/assets/img/personal-jurisdiction/Asahi.png)

[Personal Jurisdiction Flowchart]({{ site.baseurl }}/assets/img/personal-jurisdiction/PersonalJurisdictionFlowchart.png)

[Personal Jurisdiction Review Problem]({{ site.baseurl }}/assets/img/personal-jurisdiction/GreedyHeir.png)

[Finding an Appropriate Forum: Personal Jurisdiction, Subject Matter Jurisdiction, & Venue]({{ site.baseurl }}/assets/img/personal-jurisdiction/PJ-SMJ-Venue.png)

## Preclusion

[Claim & Issue Preclusion]({{ site.baseurl }}/assets/img/preclusion/PreclusionSummaryChart.png)

## Pleadings 

[Sample Complaint 1]()

[Sample Complaint 2]()

[Sample 12(b)(6) Motion]()

[Sample Answer]()

## Erie Doctrine

[Erie-Hanna Decision Tree]({{ site.baseurl }}/assets/img/choice-of-law/ErieHanna.png)

## Summary Judgment 

[Sample Motion for Summary Judgment]()

# Practice Exam Questions

{% for exam in site.exams %}
<p><a href="{{ site.baseurl }}{{ exam.url }}">{{ exam.title }}</a></p>
{% endfor %}
