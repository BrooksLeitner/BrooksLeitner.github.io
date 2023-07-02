---
layout: distill
title: What is the Perfect Biomarker?
description: This article provides a qualitative and quantitative framework in order to evaluate the utility of biomarkers for health and disease
giscus_comments: true
tags: metabolism, medicine
categories: blog-post
date: 2023-07-02 12:00:00

authors:
  - name: Brooks P. Leitner
    affiliations:
      name: Yale MD/PhD Program

# Optionally, you can add a table of contents to your post.
# NOTES:
#   - make sure that TOC names match the actual section names
#     for hyperlinks within the post to work correctly.
#   - we may want to automate TOC generation in the future using
#     jekyll-toc plugin (https://github.com/toshimaru/jekyll-toc).
toc:
  - name: Introduction
  - name: Context Matters
  - name: P-FRAME Criteria
  - name: Specific Indications

---

## Introduction

So you want to design the perfect biomarker. Or perhaps you’re wondering whether a hot new biomarker (in a top journal or from a biotech start-up) is actually going to be useful, or stand the test of time. The goal of this article is to provide a framework for how to evaluate the effectiveness of biomarkers for health, disease, or really any metric. I recommend you check out the <a href="https://www.ncbi.nlm.nih.gov/books/NBK326791/">NIH’s “BEST Resource”</a> for technical definitions. I will refer here to a biomarker as any characteristic that serves as an indicator of a biological function, state of health, or metric that reflects a health-related process. Biomarkers could be from a blood test (like serum glucose levels), imaging characteristics (from a Brain MRI or PET Scan), digital (personal history of Google queries that suggest anxiety), genetic variants (such as BRCA1 cancer risk gene), or anything you could imagine. 

The ultimate goal of a biomarker is to guide healthcare management, measure response to treatment, or provide an index of future risk. An ideal one will maximize benefits, make it clear to the person and healthcare team how to move forward with the individual’s life, be easy to measure and track, and be responsive to a specific intervention.

I will describe first the necessary context, then P-FRAME criteria, and finally touch on the specific indications.

***

## Context Matters

Clearly define the problem you are trying to solve- this concept that applies both to academic research and launching a startup. As for biomarkers, it is important to determine what problem your biomarker aims to solve. Will it help guide treatment for Alzheimer’s? Will it tell you the optimal diet to enhance sleep? Something as general as a “key health indicator” is nearly useless. This is because it does not provide any new knowledge to the individual. 

Key questions you should begin thinking about include:
<ul>
    <li>If I get this biomarker tested, will it tell me how to I change my behavior?</li>
    <li>Will I be faced with decisions that could change the course of my health? </li>
    <li>If the biomarker does correlate with disease risk, does a solution exist?</li>
</ul>

Bottom line is, you need to provide context along with the biomarker. A good example of a useful biomarker is VO2Max. It is the maximal rate of oxygen consumption and utilization during an exercise test, and is a gold standard biomarker for cardiorespiratory fitness. This may be a useful biomarker for an individual about to begin a new exercise program, or an Olympic Sports team member prior to a conditioning regimen. VO2max may be useful for the right person with the right resources (e.g. a coach or trainer), at the right time (prior to an intervention designed specifically to increase fitness), and with a particular goal in mind (e.g. as a trackable metric during a new conditioning program).

***

## P-FRAME Criteria

Several qualitative AND quantitative metrics can be useful for defining the purpose for, and utility of, nearly any biomarker. I’ve selected a few general features a good biomarker should have that I find useful: Predictive, Feasible, Responsive, Actionable, Minimally Invasive, and Explainable (P-FRAME).

<div class="l-page">
  <iframe src="{{ '/assets/img/Biomarker_Radial_Plot.html' | relative_url }}" frameborder='0' scrolling='no' height="600px" width="100%" style="border: 1px dashed grey;"></iframe>
</div>

#### Predictive

The essential component of a biomarker—does it predict a particular health/disease state? HbA1c (the amount of glycosylated hemoglobin—that is sugar-modified hemoglobin in your blood) is extremely predictive of future microvascular damage cause by excess blood sugar levels. As a biomarker that can predict diseases such as diabetes-associated peripheral neuropathy, diabetic eye disease (retinopathy), and diabetic kidney disease, HbA1c is the epitome of Predictive.

#### Feasible

A more practical point; can any laboratory or individual measure the biomarker themselves? Biomarkers that have at home test kits (In fact, startup Simple HealthKit just signed a <a href="https://www.fiercehealthcare.com/retail/simple-healthkit-inks-deal-walmart-rollback-prices-increase-access-home-test">deal with Walmart</a> to allow for HbA1c home testing!) are quite feasible. Performing a PET/CT scan, which requires injection of a radioisotope and simultaneously imaging of a part of or the whole body in order to see progression of metastatic cancer, is on the opposite end of feasible.

#### Responsive

Does the biomarker respond well to intervention? VO2max is an interesting example. The fitter you are, the higher it is. Rigorous aerobic training in general can increase VO2max quite predictably. In fact, read  <a href="https://brooksleitner.medium.com/the-1977-exercise-protocol-that-increased-fitness-more-than-any-other-8557efa6d929">my previous post</a> dissecting the magnitude of change from the most intense aerobic exercise study I have seen to date. The reason I don’t give it a 5/5 is because it is extremely hard to increase VO2max, particularly without regular measurement and/or with a coach. 

#### Actionable

Does a particular biomarker score prompt you with a clear set of actions? Heart rate variability (HRV), which is statistically associated with a beneficial state of recovery, is a very general marker of a health state. Because we don’t fully yet understand the scientific underpinnings, it is hard to have a clear set of actions to take when you receive “74 milliseconds” as your last night’s HRV from your wearable. However, HRV is GENERALLY actionable. That is, a person may adopt generally healthy behaviors, and hope that their HRV responds in a beneficial direction. And maybe that’s enough out of a biomarker! Just not perfect…

#### Minimally Invasive

The three examples in the graph above demonstrate a decent part of the spectrum here. A completely non-invasive wearable wrist monitor to obtain HRV scores a 5/5. HbA1c requires a small amount of blood which is not horrible, but you may not want to do daily blood draws or needle sticks, and thus scores a 4/5. VO2max requires (in a laboratory setting) attachment to a 10-lead EKG, an extremely strenuous exercise test, all while wearing a facemask that captures your oxygen exchange. Though you don’t need a blood draw, I score it a 3/5 because of how involved it is. Depending on how insightful the biomarker is, you may strike a balance between invasiveness and insight gleaned from the result.

#### Explainable

Explainability is a bonus trait, yet I think being able to explain how the biomarker is causally (or mechanistically) associated with a particular disease/health state is important if the biomarker will stand the test of time. For example, we know that HbA1c reflects glycemic control over the last 90-120 days because the amount of sugar in the serum directly reflects how much glucose binds to hemoglobin in red blood cells, and the red blood cell lifespan is 90-120 days. We know then, about how long it will take to change HbA1c, and that control of blood sugar each day will impact its result. However, using procalcitonin to guide treatment of a bacterial infection is useful, but it is way less clear WHY it is helpful. Being able to explain WHY a biomarker is useful, gives a lot more credibility and better helps guide management.

The P-FRAME framework is more subjective and qualitative, as metrics such as sensitivity, specificity, positive predictive value, and negative predictive value are important statistical and quantifiable metrics that are used at a population level. P-FRAME is intended to help an individual (you) assess how a biomarker may be useful, particularly on a per-individual basis.


***

## Specific Indications

For the sake of space, I will direct you again to the <a href="https://www.ncbi.nlm.nih.gov/books/NBK326791/">NIH’s “BEST Resource”</a> to examine the numerous indications for biomarkers. In general, you can create a biomarker for any purpose, but clearly defined purposes include for:

<ul>
    <li>Diagnosis</li>
    <li>Disease/Risk Prediction</li>
    <li>Safety</li>
    <li>Monitoring</li>
    <li>Treatment Response</li>
    <li>Prognosis</li>    
</ul>

There are criteria, along with evidence, that must be met in order for biomarkers to be adopted widely in clinical practice. Typically, the evidence and metrics should be obtained in the context of one or more of the above indications.

Look out for more analyses related to existing, and up and coming biomarkers, and try the P-FRAME framework as you come across new biomarkers. I particularly challenge you to understand the predictability and explainability of them!

***

