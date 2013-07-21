---
layout: base
title: Scooch Module Examples
description:
    See examples of the Scooch module in action,
    including the sample code snippets.
---
<style>
    /* styling for this page */
    .m-scooch {
        padding-bottom: 30px;
    }

    .m-card-light {
        width: 200px;
        margin: 30px 10px 0 10px;
    }
    .m-card-dark h3 {
        margin-top: 0;
    }

    .m-item .m-card-dark img, .m-item .m-card-light img {
        width: 100%;
        max-width: 100%;
        height: auto;
    }

    .m-scooch-example-5 .m-caption {
        color: #ccc;
    }

    body {
        font-family: arial, sans-serif;
        line-height: 1.25em;
    }
</style>


## Previous / Next controls
<p>Carousel with Previous / Next controls to advance between items.</p>
<div class="m-scooch m-fluid m-scooch-photos" id="m-scooch-example-1">
  <div class="m-scooch-inner">
    <div class="m-item">
        <img src="http://lorempixel.com/300/300/animals/">
    </div>
    <div class="m-item">
        <img src="http://lorempixel.com/300/300/animals/">
    </div>
    <div class="m-item">
        <img src="http://lorempixel.com/300/300/animals/">
    </div>
    <div class="m-item">
        <img src="http://lorempixel.com/300/300/animals/">
    </div>
    <div class="m-item">
        <img src="http://lorempixel.com/300/300/animals/">
    </div>
  </div>
  <div class="m-scooch-controls">
    <a href="#" data-slide="prev">&lsaquo; Previous</a>
    <a href="#" data-slide="next">Next &rsaquo;</a>
  </div>
</div>

## Bulleted controls
<p>Bulleted indicators for number of items and currently-selected item. Click to advance between items.</p>
<div class="m-scooch m-fluid m-scooch-photos" id="m-scooch-example-2">
  <div class="m-scooch-inner">
    <div class="m-item">
        <img src="http://lorempixel.com/300/300/animals/">
    </div>
    <div class="m-item">
        <img src="http://lorempixel.com/300/300/animals/">
    </div>
    <div class="m-item">
        <img src="http://lorempixel.com/300/300/animals/">
    </div>
    <div class="m-item">
        <img src="http://lorempixel.com/300/300/animals/">
    </div>
    <div class="m-item">
        <img src="http://lorempixel.com/300/300/animals/">
    </div>
  </div>
  <div class="m-scooch-controls m-scooch-bulleted">
    <a href="#" data-slide="1">1</a>
    <a href="#" data-slide="2">2</a>
    <a href="#" data-slide="3">3</a>
    <a href="#" data-slide="4">4</a>
    <a href="#" data-slide="5">5</a>
  </div>
</div>

## Numbered pagination-style controls
<p>Numbered pagination controls for each item, with flanking Previous / Next controls.</p>
<div class="m-scooch m-fluid m-scooch-photos" id="m-scooch-example-3">
    <div class="m-scooch-inner">
        <div class="m-item">
            <img src="http://lorempixel.com/300/300/animals/">
        </div>
        <div class="m-item">
            <img src="http://lorempixel.com/300/300/animals/">
        </div>
        <div class="m-item">
            <img src="http://lorempixel.com/300/300/animals/">
        </div>
        <div class="m-item">
            <img src="http://lorempixel.com/300/300/animals/">
        </div>
        <div class="m-item">
            <img src="http://lorempixel.com/300/300/animals/">
        </div>
    </div>
    <div class="m-scooch-controls m-scooch-pagination">
        <a href="#" data-slide="prev">Previous</a>
        <a href="#" data-slide="1">1</a>
        <a href="#" data-slide="2">2</a>
        <a href="#" data-slide="3">3</a>
        <a href="#" data-slide="4">4</a>
        <a href="#" data-slide="5">5</a>
        <a href="#" data-slide="next">Next</a>
    </div>
</div>

## HUD-style Controls
<p>Previous and Next render as heads-up controls that display on hover events. Since hover events don't work on mobile, simply swipe to advance.</p>
<div class="m-scooch m-fluid m-scooch-photos" id="m-scooch-example-4">
    <div class="m-scooch-inner">
        <div class="m-item">
            <img src="http://lorempixel.com/300/300/animals/">
        </div>
        <div class="m-item">
            <img src="http://lorempixel.com/300/300/animals/">
        </div>
        <div class="m-item">
            <img src="http://lorempixel.com/300/300/animals/">
        </div>
        <div class="m-item">
            <img src="http://lorempixel.com/300/300/animals/">
        </div>
        <div class="m-item">
            <img src="http://lorempixel.com/300/300/animals/">
        </div>
    </div>
    <div class="m-scooch-controls m-scooch-hud">
        <a class="m-scooch-prev" href="#" data-slide="prev">Previous</a>
        <a class="m-scooch-next" href="#" data-slide="next">Next</a>
    </div>
</div>


## Image + Caption
<p>Image carousel containing textual captions with simple Previous / Next controls to advance between items.</p>
<div class="m-scooch m-fluid m-scooch-photos" id="m-scooch-example-5">
    <div class="m-scooch-inner">
        <div class="m-item">
            <img src="http://lorempixel.com/300/300/animals/">
            <p class="m-caption">How</p>
        </div>
        <div class="m-item">
            <img src="http://lorempixel.com/300/300/animals/">
            <p class="m-caption">many</p>
        </div>
        <div class="m-item">
            <img src="http://lorempixel.com/300/300/animals/">
            <p class="m-caption">roads</p>
        </div>
        <div class="m-item">
            <img src="http://lorempixel.com/300/300/animals/">
            <p class="m-caption">must</p>
        </div>
        <div class="m-item">
            <img src="http://lorempixel.com/300/300/animals/">
            <p class="m-caption">a</p>
        </div>
    </div>
    <div class="m-scooch-controls">
        <a href="#" data-slide="prev">&lsaquo; Previous</a>
        <a href="#" data-slide="next">Next &rsaquo;</a>
    </div>
</div>

## Fixed Width Items
<p>Items can be stretched to fit the viewport, or they can be sized individually like in this example.
In this example, we've used the included <code>.m-card-light</code> class to give the element a background and border.
You will have to to size the element or it's content yourself.
</p>

<div class="m-scooch m-center m-fade-out" id="m-scooch-example-6">
    <div class="m-scooch-inner">
        <div class="m-item">
            <div class="m-card-light">
                <img src="http://lorempixel.com/300/300/animals/">
                <p class="m-caption">Blossoms</p>
            </div>
        </div>
        <div class="m-item">
            <div class="m-card-light">
                <img src="http://lorempixel.com/300/300/animals/">
                <p class="m-caption">Glacier</p>
            </div>
        </div>
        <div class="m-item">
            <div class="m-card-light">
                <img src="http://lorempixel.com/300/300/animals/">
                <p class="m-caption">Helmets</p>
            </div>
        </div>
        <div class="m-item">
            <div class="m-card-light">
                <img src="http://lorempixel.com/300/300/animals/">
                <p class="m-caption">Parliament</p>
            </div>
        </div>
        <div class="m-item">
            <div class="m-card-light">
                <img src="http://lorempixel.com/300/300/animals/">
                <p class="m-caption">Pods</p>
            </div>
        </div>
    </div>
    <div class="m-scooch-controls">
        <a href="#" data-slide="prev">&lsaquo; Previous</a>
        <a href="#" data-slide="next">Next &rsaquo;</a>
    </div>
</div>

## Scaled Transitions
<p>Display the current item larger than the rest, and animate the transition between each with the <code>.m-scaled</code> class.</p>

<div class="m-scooch m-center m-scaled m-fade-out" id="m-scooch-example-7">
    <div class="m-scooch-inner">
        <div class="m-item">
            <div class="m-card-light">
                <img src="http://lorempixel.com/300/300/animals/">
                <p class="m-caption">Blossoms</p>
            </div>
        </div>
        <div class="m-item">
            <div class="m-card-light">
                <img src="http://lorempixel.com/300/300/animals/">
                <p class="m-caption">Fox Glacier</p>
            </div>
        </div>
        <div class="m-item">
            <div class="m-card-light">
                <img src="http://lorempixel.com/300/300/animals/">
                <p class="m-caption">Helmets</p>
            </div>
        </div>
        <div class="m-item">
            <div class="m-card-light">
                <img src="http://lorempixel.com/300/300/animals/">
                <p class="m-caption">Parliament</p>
            </div>
        </div>
        <div class="m-item">
            <div class="m-card-light">
                <img src="http://lorempixel.com/300/300/animals/">
                <p class="m-caption">Pods</p>
            </div>
        </div>
    </div>
    <div class="m-scooch-controls">
        <a href="#" data-slide="prev">&lsaquo; Previous</a>
        <a href="#" data-slide="next">Next &rsaquo;</a>
    </div>
</div>

## Arbitrary Content
<p>Arbitrary content carousel with simple Previous / Next controls to advance between items.
We used the included class <code>.m-card-dark</code> to give each element a background.
These elements are automatically sized by the <code>.m-fluid</code> class to be full width.</p>

<div class="m-scooch m-fluid" id="m-scooch-example-8">
    <div class="m-scooch-inner">
        <div class="m-item">
            <div class="m-card-dark">
                <h3>Slipsum</h3>
                <!-- start slipsum code -->

                Like you, I used to think the world was this great place where everybody lived by the same standards I did, then some kid with a nail showed me I was living in his world, a world where chaos rules not order, a world where righteousness is not rewarded. That's Cesar's world, and if you're not willing to play by his rules, then you're gonna have to pay the price.

                <!-- please do not remove this line -->

                <div style="display:none;">
                <a href="http://slipsum.com">lorem ipsum</a></div>

                <!-- end slipsum code -->

            </div>
        </div>
        <div class="m-item">
            <div class="m-card-dark">
                <h3>More Slipsum</h3>
                <!-- start slipsum code -->

                The path of the righteous man is beset on all sides by the iniquities of the selfish and the tyranny of evil men. Blessed is he who, in the name of charity and good will, shepherds the weak through the valley of darkness, for he is truly his brother's keeper and the finder of lost children. And I will strike down upon thee with great vengeance and furious anger those who would attempt to poison and destroy My brothers. And you will know My name is the Lord when I lay My vengeance upon thee.

                <!-- please do not remove this line -->

                <div style="display:none;">
                <a href="http://slipsum.com">lorem ipsum</a></div>

                <!-- end slipsum code -->

            </div>
        </div>
    </div>
    <div class="m-scooch-controls">
        <a href="#" data-slide="prev">&lsaquo; Previous</a>
        <a href="#" data-slide="next">Next &rsaquo;</a>
    </div>
</div>

<!-- <script src="http://zeptojs.com/zepto.js"></script> -->
<script src="http://code.jquery.com/jquery-1.10.1.js"></script>
<script src="//cdn.mobify.com/modules/scooch/0.3.0/scooch.min.js"></script>
<script>$('.m-scooch').scooch();</script>