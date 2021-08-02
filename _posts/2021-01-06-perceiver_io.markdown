---
layout: post
title:  "Perceiver IO: A General Architecture for Structured Inputs & Outputs"
date:   2021-01-06 00:00:00 +00:00
image: /images/perceiver_io_teaser.png
categories: research
author: "Andrew Jaegle"
authors: "<strong>Andrew Jaegle</strong>, <a href='https://www.linkedin.com/in/sebastian-borgeaud-8648a5aa'>Sebastian Borgeaud</a>, <a href='https://www.jbalayrac.com/'>Jean-Baptiste Alayrac</a>, <a href='http://www.carldoersch.com/'>Carl Doersch</a>, <a href='https://scholar.google.co.uk/citations?user=hOl-5zcAAAAJ&hl=en'>Catalin Ionescu</a>, <a href='https://www.linkedin.com/in/david-fengning-ding-053b1282/'>David Ding</a>,  <a href='https://skoppula.com/'>Skanda Koppula</a>, <a href='http://people.csail.mit.edu/danielzoran/'>Daniel Zoran</a>, <a href='https://scholar.google.co.uk/citations?user=NIxD36wAAAAJ&hl=en'>Andrew Brock</a>, <a href='http://imaginarynumber.net/'>Evan Shelhamer</a>, <a href='https://www.olivierhenaff.com/'>Olivier Hénaff</a>, <a href='https://scholar.google.com/citations?user=eM916YMAAAAJ&hl=en'>Matt Botvinick</a>, <a href='https://www.robots.ox.ac.uk/~az/'>Andrew Zisserman</a>, <a href='https://research.google/people/OriolVinyals/'>Oriol Vinyals</a>, <a href='https://scholar.google.com/citations?user=IUZ-7_cAAAAJ&hl=en'>João Carreira</a>"
venue: "arXiv"
paper: https://arxiv.org/abs/2107.14795
pdf: /pdfs/jaegle2021perceiver_io.pdf
code: https://github.com/deepmind/deepmind-research/tree/master/perceiver
---
A Perceiver architecture that handles arbitrary inputs and outputs: SoTA on Sintel optical flow, matches a strong BERT baseline but without tokenization, simultaneous multi-task GLUE fine-tuning, better/faster results on ImageNet without 2D assumptions, and strong results on StarCraft II & multimodal Kinetics autoencoding.