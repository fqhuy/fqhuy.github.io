---
layout: default
title: "FlexyFont: Learning Transferring Rules for Flexible Typeface Synthesis"
authors: "H. Q. Phan, A. B. Chan and H. Fu"
image: "images/flexyfont.png"
doi: "http://dx.doi.org/10.1111/cgf.12763" 
abstract: "Maintaining consistent styles across glyphs is an arduous task in typeface design. In this work we introduce Flexy-
Font, a flexible tool for synthesizing a complete typeface that has a consistent style with a given small set of glyphs.
Motivated by a key fact that typeface designers often maintain a library of glyph parts to achieve a consistent typeface,
we intend to learn part consistency between glyphs of different characters across typefaces. We take a part assembling approach by firstly decomposing the given glyphs into semantic parts and then assembling them according to learned sets of transferring rules to reconstruct the missing glyphs. To maintain style consistency, we represent the style of a font as a vector of pairwise part similarities. By learning a distribution over these feature vectors, we are able to predict the style of a novel typeface given only a few examples. We utilize a popular machine learning method as well as retrieval-based methods to quantitatively assess the performance of our feature vector, resulting in favorable results. We also present an intuitive interface that allows users to interactively create novel typefaces with ease. The synthesized fonts can be directly used in real-world design."
---

# FlexyFont: Learning Transferring Rules for Flexible Typeface Synthesis