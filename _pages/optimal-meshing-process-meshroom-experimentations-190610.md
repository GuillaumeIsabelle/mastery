---
ID: 151
post_title: >
  Optimal Meshing Process-Meshroom
  experimentations 190610
author: gicomadmin
post_excerpt: ""
layout: page
permalink: >
  http://guillaumeisabelle.com/mastery/vfx/vfx-photogrammetry/optimal-meshing-process-meshroom-experimentations-190610/
published: true
post_date: 2019-06-10 12:38:55
---
<!-- wp:heading {"level":1,"align":"left"} -->

<h1 style="text-align:left">
  WARNING. This is a workin progress article and sections are not completed.
</h1>

<!-- /wp:heading -->

<!-- wp:heading -->

## @Decisions :

<!-- /wp:heading -->

<!-- wp:paragraph {"backgroundColor":"light-green-cyan"} -->

<p class="has-background has-light-green-cyan-background-color">
  <strong>Using LSCM as Unwrapping</strong>
</p>

<!-- /wp:paragraph -->

<!-- wp:paragraph {"backgroundColor":"luminous-vivid-amber"} -->

<p class="has-background has-luminous-vivid-amber-background-color">
  Draft are interestingly fast and acceptable for conceptualize
</p>

<!-- /wp:paragraph -->

<!-- wp:heading -->

## @Analysis

<!-- /wp:heading -->

<!-- wp:image {"id":153} --><figure class="wp-block-image">

<img src="http://guillaumeisabelle.com/mastery/wp-content/uploads/sites/8/2019/06/image-15-1024x368.png" alt="" class="wp-image-153" /><figcaption>Generating 3 Texturing of two types. Draft and High-Res  
(ref as : HMeshing and DMeshing)</figcaption></figure> <!-- /wp:image -->

<!-- wp:heading -->

## The variant being evaluated is the Unwrapping method

<!-- /wp:heading -->

<!-- wp:image {"id":155,"width":286,"height":209} --><figure class="wp-block-image is-resized">

<img src="http://guillaumeisabelle.com/mastery/wp-content/uploads/sites/8/2019/06/image-16.png" alt="" class="wp-image-155" width="286" height="209" /></figure> <!-- /wp:image -->

<!-- wp:image {"id":156,"width":236,"height":47} --><figure class="wp-block-image is-resized">

<img src="http://guillaumeisabelle.com/mastery/wp-content/uploads/sites/8/2019/06/image-17.png" alt="" class="wp-image-156" width="236" height="47" /><figcaption>LSCM</figcaption></figure> <!-- /wp:image -->

<!-- wp:image {"id":158} --><figure class="wp-block-image">

<img src="http://guillaumeisabelle.com/mastery/wp-content/uploads/sites/8/2019/06/image-18-1024x1024.png" alt="" class="wp-image-158" /><figcaption>DMesh Texturing - One LSCM was generated</figcaption></figure> <!-- /wp:image -->

<!-- wp:image {"id":168} --><figure class="wp-block-image">

<img src="http://guillaumeisabelle.com/mastery/wp-content/uploads/sites/8/2019/06/image-21-1024x616.png" alt="" class="wp-image-168" /><figcaption>   
DMesh Texturing Basic Unwrapping </figcaption></figure> <!-- /wp:image -->

<!-- wp:image {"id":160} --><figure class="wp-block-image">

<img src="http://guillaumeisabelle.com/mastery/wp-content/uploads/sites/8/2019/06/image-19-1024x330.png" alt="" class="wp-image-160" /><figcaption>**DMeshing** ***Basic ***generated two plus other unknown files</figcaption></figure> <!-- /wp:image -->

<!-- wp:heading {"level":1} -->

# **Generating ABF Unwrapping...** Interesting

<!-- /wp:heading -->

<!-- wp:image {"id":178} --><figure class="wp-block-image">

<img src="http://guillaumeisabelle.com/mastery/wp-content/uploads/sites/8/2019/06/image-23-1016x1024.png" alt="" class="wp-image-178" /><figcaption>ABF Unwrapping</figcaption></figure> <!-- /wp:image -->

<!-- wp:image {"id":180} --><figure class="wp-block-image">

<img src="http://guillaumeisabelle.com/mastery/wp-content/uploads/sites/8/2019/06/image-24-951x1024.png" alt="" class="wp-image-180" /><figcaption>DMesh ABF Unacceptable - Closer though the result are a bit blurry, lets try generating for the HMesh</figcaption></figure> <!-- /wp:image -->

<!-- wp:image {"id":175} --><figure class="wp-block-image">

<img src="http://guillaumeisabelle.com/mastery/wp-content/uploads/sites/8/2019/06/image-22-1024x123.png" alt="" class="wp-image-175" /><figcaption>DMesh texturing ABF Unwrapping</figcaption></figure> <!-- /wp:image -->

<!-- wp:table -->

<table class="wp-block-table">
  <tbody>
    <tr>
      <td>
        Textures
      </td>
      
      <td>
        One Texture
      </td>
    </tr>
    
    <tr>
      <td>
        Mesh
      </td>
      
      <td>
        Similar size than others<br />24min...
      </td>
    </tr>
  </tbody>
</table>

<!-- /wp:table -->

<!-- wp:heading -->

## Generating the ABF for the HMesh   
Start mesh atlasing (using Geogram ABF).  
atlasing : Interesting term... can you clarify atlasing?

<!-- /wp:heading -->

<!-- wp:paragraph {"backgroundColor":"luminous-vivid-orange"} -->

<p class="has-background has-luminous-vivid-orange-background-color">
  Canceled the ABF, way too long...
</p>

<!-- /wp:paragraph -->

<!-- wp:quote -->

<blockquote class="wp-block-quote">
  <p>
    <br />In realtime computer graphics, a texture <strong>atlas</strong> (also called a sprite sheet or an image sprite) is an image containing a collection of smaller images, usually packed together to reduce the <strong>atlas</strong> size. <strong>Atlases</strong> can consist of uniformly-sized sub-images, or they can consist of images of varying dimensions.
  </p>
  
  <cite> <br /><a href="https://en.wikipedia.org/wiki/Texture_atlas">https://en.wikipedia.org/wiki/Texture_atlas</a> </cite>
</blockquote>

<!-- /wp:quote -->

<!-- wp:heading -->

## More experimentation on the tree were done.

<!-- /wp:heading -->

<!-- wp:heading -->

## Feature Matching

<!-- /wp:heading -->

<!-- wp:paragraph -->

@q What is the optimal parametering for Feature matching?  
In this experimentation, SIFT + AKAZE + Guided Matching was used

<!-- /wp:paragraph -->

<!-- wp:image {"id":194} --><figure class="wp-block-image">

<img src="http://guillaumeisabelle.com/mastery/wp-content/uploads/sites/8/2019/06/image-28.png" alt="" class="wp-image-194" /></figure> <!-- /wp:image -->

<!-- wp:heading -->

## Texturing...

<!-- /wp:heading -->

<!-- wp:paragraph -->

In conclusion. The Texturing LSCM is the best I have found to use.  


<!-- /wp:paragraph -->

<!-- wp:image {"id":188} --><figure class="wp-block-image">

<img src="http://guillaumeisabelle.com/mastery/wp-content/uploads/sites/8/2019/06/image-25.png" alt="" class="wp-image-188" /><figcaption>16k Texture, EXR format, Unwrapping using method LSCM  
Later, the 16k can be reduce to 8k, 4k according to desired resolution.</figcaption></figure> <!-- /wp:image -->

<!-- wp:paragraph -->



<!-- /wp:paragraph -->

<!-- wp:heading -->

## Meshing

<!-- /wp:heading -->

<!-- wp:image {"id":190} --><figure class="wp-block-image">

<img src="http://guillaumeisabelle.com/mastery/wp-content/uploads/sites/8/2019/06/image-26.png" alt="" class="wp-image-190" /><figcaption>Lower the triangle reduce a bit the generated model  
Keep only the largest Mesh, well should keep only the largest mesh and get rid of all junk around</figcaption></figure> <!-- /wp:image -->

<!-- wp:heading -->

## SfM - Structure from Motion

<!-- /wp:heading -->

<!-- wp:image {"id":192} --><figure class="wp-block-image">

<img src="http://guillaumeisabelle.com/mastery/wp-content/uploads/sites/8/2019/06/image-27.png" alt="" class="wp-image-192" /><figcaption>Increased   
`minInputTrackLength` set to 4 to keep only the most robust matches ([ref][1])</figcaption></figure> <!-- /wp:image -->

<!-- wp:heading -->

## Error Memory Exausted :(

<!-- /wp:heading -->

<!-- wp:paragraph -->

It does not like High feature extraction for some of my models

<!-- /wp:paragraph -->

<!-- wp:ultimate-faqs/ewd-ufaq-search-block {"include_category":"VFX-Photogrammetry"} /-->

 [1]: https://github.com/alicevision/meshroom/wiki/Reconstruction-parameters