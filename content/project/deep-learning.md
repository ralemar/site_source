+++
# Date this page was created.
date = "2016-04-27"

# Project title.
title = "Learning Lagrange Interpolation"

# Project summary to display on homepage.
summary = "In this project we use Tensorflow and Machine Learning to solve the Lagrange Interpolation problem."

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "bubbles.jpg"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["deep-learning"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = true

# Optional featured image (relative to `static/img/` folder).
[header]
image = "headers/bubbles-wide.jpg"
caption = "My caption :smile:"

+++

# Introduction

The Lagrange Interpolation problem bla bla bla.
<div>
$$\small
\text{pow}
\left(
  \left[
    \begin{array}{cccc}
      x_0    & x_0    & \ldots & x_0\\\\\\
      x_1    & x_1    & \ldots & x_1\\\\\\
      \vdots & \vdots & \ddots & \vdots \\\\\\
      x_N    & x_N    & \ldots & x_N
    \end{array}
  \right],
  \left[
    \begin{array}{cccc}
      0      & 1      & \ldots & N\\\\\\
      0      & 1      & \ldots & N\\\\\\
      \vdots & \vdots & \ddots & \vdots \\\\\\
      0      & 1      & \ldots & N
    \end{array}
  \right]
\right)=
\left[
  \begin{array}{cccc}
    1    & x_0    & \ldots & x_0^{N}\\\\\\
    1    & x_1    & \ldots & x_1^{N}\\\\\\
    \vdots & \vdots & \ddots & \vdots \\\\\\
    1    & x_N    & \ldots & x_N^{N}
  \end{array}
\right]
$$
</div>

bla blackfriday

<div>
<video width="100%" controls loop autoplay>
  <source src="/img/joint_animation.mp4" type="video/mp4">
Your browser does not support the video tag.
</video>
</div>
