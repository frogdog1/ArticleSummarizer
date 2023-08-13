# Finding Nasa

**_The implementation of the ML models can be found in myapp/day_cntrl.py_**

## Project Summary

Using both extractive and abstractive NLP text summarization, one is able to decompose what could be a 100-page research paper into a single sentence. Provided with keywords that are relevant to your article, subject matter, and field. you can sort through multiple research papers in the time that it would take to go through only one. We set out to use data and artificial intelligence to save the user time, and make the research process more efficient and user-friendly. This is important as it opens up the possibilities of what a researcher can do. Regardless of a user's field of proficiency or expertise, they're able to branch out and widen the scope of their research.

## Problem Identified

The problem with abstractive text summarization is that due to the way that NLP models encode and decode bodies of text, the model can not take in anything longer than a short paragraph.

## How We Adressed it

There are two intuitive solutions to this. The first is to recursively repeat the encode-decode process until it is of the desired length. The complication arises with the fact that this is both computationally expensive and time-consuming.

## Our Solution

Our solution to this problem was to use both extractive and abstractive text summarization. Using a neural network, the inputted text is narrowed down into only the most important sentences. From this, an abstract summary is created using Google's NLP model: Pegasus, narrowing down what could have originally been a 100-page research paper into a single sentence. Keeping things short and concise, one is able to more efficiently navigate through the endless supply of academic papers. Upon running the program, you will also receive multiple keywords that are relevant to your article, subject matter, and field.

## What we used

This is all available on a website we created using HTML, CSS, and Javascript and hosted on a server using Django and AWS Lightsail, all for the purpose of making the process as simple as possible for the user.

## Reflection

What was inspired by a weekend of sifting through overly-technical research papers and realizing that the current system is flawed, this tool is meant to save precious time and make the research process more efficient.
