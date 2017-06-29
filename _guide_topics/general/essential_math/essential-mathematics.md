---
title: Essential Mathematics for Computational Design
description: Introduces to design professionals the foundation mathematical concepts for effective development of computational 3D models.
authors: ['Rajaa Issa']
author_contacts: ['rajaa']
sdk: ['General']
languages: ['C#', 'Python', 'VB']
platforms: ['Windows', 'Mac']
categories: ['General']
layout: fullwidth-page
order: 1
TODO: This needs to be shimmed for Mac Platform.
---

# Essential Mathematics for Computational Design

*Essential Mathematics for Computational Design* introduces to design professionals the foundation mathematical concepts that are necessary for effective development of computational methods for 3D modeling and computer graphics. This is not meant to be a complete and comprehensive resource, but rather an overview of the basic and most commonly used concepts. The material is directed towards designers who have little or no background in mathematics beyond high school. All concepts are explained visually using [Grasshopper® (GH)](www.grasshopper3d.com), the generative modeling environment for [Rhinoceros® (Rhino)](www.rhino3d.com).  

The content is divided into three chapters. [Chapter 1]({{ site.baseurl }}/guides/general/essential_math/vector-mathematics/) discusses vector math including vector representation, vector operation, and line and plane equations. [Chapter 2]({{ site.baseurl }}/guides/general/essential_math/matrices-transformations/) reviews matrix operations and transformations. [Chapter 3]({{ site.baseurl }}/guides/general/essential_math/parametric-curves-surfaces/) includes an in-depth review of parametric curves with special focus on NURBS curves and the concepts of continuity and curvature.  It also reviews NURBS surfaces and polysurfaces.

I would like to acknowledge the excellent and thorough technical review by [Dr. Dale Lear](https://discourse.mcneel.com/u/dalelear/activity) of Robert McNeel & Associates. His valuable comments were instrumental in producing this edition. I would also like to acknowledge Ms. [Margaret Becker](https://discourse.mcneel.com/u/margaret/activity) of Robert McNeel & Associates for reviewing the technical writing and formatting.

***[Rajaa Issa](https://discourse.mcneel.com/users/rajaa/activity)***

Robert McNeel & Associates

Download the <a href="{{ site.baseurl }}/files/math-samplesandtutorials.zip.zip"><span class="glyphicon glyphicon-download"></span></a> [math-samplesandtutorials.zip]({{ site.baseurl }}/files/math-samplesandtutorials.zip) archive, containing all the example Grasshopper and code files in this guide.

### Table of Contents

<table id="math_table">  
<tbody>  
<tr>  
<td width="30%">  
  1. <a href="{{ site.baseurl }}/guides/general/essential_math/vector-mathematics/">Vector Mathematics</a>  
    <ol><li>1.1 <a href="{{ site.baseurl }}/guides/general/essential_math/vector-mathematics/#vector-representation">Vector representation</a></li>   
        <ul> <li>Position vector</li>  
        <li>Vectors vs. points</li>  
        <li>Vector length</li>  
        <li>Unit vector</li></ul>   
    <li>1.2 <a href="{{ site.baseurl }}/guides/general/essential_math/vector-mathematics/#vector-operations">Vector operations</a></li>   
        <ul><li>Vector scalar operation</li>  
      	<li>Vector addition</li>   
        <li>Vector subtraction</li>  
        <li>Vector properties</li>
        <li>Vector dot product</li>  
        <li>Vector dot product, lengths, and angles</li>   
        <li>Dot product properties</li>   
        <li>Vector cross product</li>  
        <li>Cross product and angle between vectors</li>   
        <li>Cross product properties</li></ul>  
   <li>1.3 <a href="{{ site.baseurl }}/guides/general/essential_math/vector-mathematics/#vector-equation-of-line">Vector equation of line</a></li>
   <li>1.4 <a href="{{ site.baseurl }}/guides/general/essential_math/vector-mathematics/#vector-equation-of-a-plane">Vector equation of a plane</a></li>  
   <li>1.5 <a href="{{ site.baseurl }}/guides/general/essential_math/vector-mathematics/#tutorials">Tutorials</a></li>  
      <ul><li>Face direction</li>  
        <li>Exploded box</li>
        <li>Tangent spheres</li></ul>  
    </ol>
</td>
<td width="30%">
      2. <a href="{{ site.baseurl }}/guides/general/essential_math/matrices-transformations/"> Matrices and Transformations</a>
    <ol><li>2.1 <a href="{{ site.baseurl }}/guides/general/essential_math/matrices-transformations/#matrix-operations">Matrix operations</a></li>
        <ul><li>Matrix multiplication</li>  
            <li>Identity matrix</li></ul>
    <li>2.2 <a href="{{ site.baseurl }}/guides/general/essential_math/matrices-transformations/#transformation-operations"> Transformation operations</a></li>
        <ul><li>Translation (move) transformation </li>  
            <li>Rotation transformation</li>   
            <li>Scale transformation</li>   
            <li>Shear transformation</li>   
            <li>Mirror or reflection transformation</li>   
            <li>Planar Projection transformation</li></ul>
    </ol>			
</td>
<td>
      3. <a href="{{ site.baseurl }}/guides/general/essential_math/parametric-curves-surfaces/"> Parametric Curves and Surfaces</a>
    <ol><li>3.1 <a href="{{ site.baseurl }}/guides/general/essential_math/parametric-curves-surfaces/#parametric-curves">Parametric curves</a></li>    
        <ul><li>Curve parameter</li>    
            <li>Curve domain or interval</li>    
            <li>Curve evaluation</li>    
            <li>Tangent vector to a curve</li>    
            <li>Cubic polynomial curves</li>    
            <li>Evaluating cubic Bézier curves</li></ul>    
    <li>3.2 <a href="{{ site.baseurl }}/guides/general/essential_math/parametric-curves-surfaces/#nurbs-curves">NURBS curves</a></li>
        <ul><li>Degree</li>  
            <li>Control points</li>  
            <li>Weights of control points</li>  
            <li>Knots</li>  
            <li>Knots are parameter values</li>  
            <li>Evaluation rule</li>  
            <li>Characteristics of NURBS curves</li>  
            <li>Evaluating NURBS curves</li></ul>  
    <li>3.3 <a href="{{ site.baseurl }}/guides/general/essential_math/parametric-curves-surfaces/#curve-geometric-continuity">Curve geometric continuity</a></li>   
    <li>3.4 <a href="{{ site.baseurl }}/guides/general/essential_math/parametric-curves-surfaces/#curve-curvature">Curve curvature</a></li>   
    <li>3.5 <a href="{{ site.baseurl }}/guides/general/essential_math/parametric-curves-surfaces/#parametric-surfaces">Parametric surfaces</a></li>   
        <ul><li>Surface parameters</li>   
            <li>Surface domain</li>   
            <li>Surface evaluation</li>   
            <li>Tangent plane of a surface</li></ul>  
    <li>3.6 <a href="{{ site.baseurl }}/guides/general/essential_math/parametric-curves-surfaces/#surface-geometric-continuity">Surface geometric continuity</a></li>     
    <li>3.7 <a href="{{ site.baseurl }}/guides/general/essential_math/parametric-curves-surfaces/#surface-curvature">Surface curvature</a></li>     
        <ul><li>Principal curvatures</li>   
            <li>Gaussian curvature</li>   
            <li>Mean curvature</li></ul>   
    <li>3.8 <a href="{{ site.baseurl }}/guides/general/essential_math/parametric-curves-surfaces/#nurbs-surfaces">NURBS surfaces</a></li>     
        <ul><li>Characteristics of NURBS surfaces</li>   
            <li>Singularity in NURBS surfaces</li>   
            <li>Trimmed NURBS surfaces</li></ul>   
    <li>3.9 <a href="{{ site.baseurl }}/guides/general/essential_math/parametric-curves-surfaces/#polysurfaces">Polysurfaces</a></li>     
    <li>3.10 <a href="{{ site.baseurl }}/guides/general/essential_math/parametric-curves-surfaces/#tutorials">Tutorials</a></li>     
        <ul><li>Continuity between curves</li>   
            <li>Surfaces with singularity</li></ul>
    </ol>			
</td>
</tr>
</tbody>
</table>