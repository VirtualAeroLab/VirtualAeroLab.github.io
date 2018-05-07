---
layout: post
title: My CFD Setup
date: 2018-5-7
excerpt_separator: "A general breakdown of the tools that will be used at all stages for CFD workflow."
tags:
  - CFD
  - Tools
last_modified_at: 2018-05-07T12:43:31-05:00
---

<p>The general workflow for CFD and to an extension problem solving. 
This starts with defining the problem that is going to be analyzed, how to approach the problem,
 physics and simplications that need to be made, and finally the problem is solved with appropriate 
sanity checks. In terms of CFD this starts with defining the control volume (Geometry) with associated 
geometric cleanup, discretization, apply boundary and initial conditions, solve step, then check if the approach was 
satisfactory. Adjustments are then made to the workflow to address the errors or shortcomings of the approach.</p>
{: style="text-align: justify;"}

<p>For most commercial software, the entire workflow is an all-in-one approach or close to it where everything is readily 
available within the packages. I have access to a few commercial tools at my University, but at this time I have selected 
a few opensource tools for personal use on my personal computers.</p>
{: style="text-align: justify;"}

<p>The following tools address all the CFD steps:</p>
{: style="text-align: justify;"}

<p>1. For geometry FreeCAD and NaroCAD will be used. There is currently no preference, but both will be examined until one is selected as the primary geometry tool.</p>
{: style="text-align: justify;"}

<p>2. Gmesh will be used for the meshing step and some basic preprocessing. Have not investigated entirely so not what it offers.</p>
{: style="text-align: justify;"}

<p>3. Preprocessing in terms of problem definition and solving will be handled by SU2.</p>{: style="text-align: justify;"}

<p>4. ParaView will be used for post-processing and external tools like Python for data-processing.</p>
{: style="text-align: justify;"}