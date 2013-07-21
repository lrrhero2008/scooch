---
layout: base
title: Responsive, Mobile first accordion UI module
description:
    Learn about the Bellows module, an expanding bellows menu for
    two-level navigation systems.
---

# Bellows

A responsive, mobile-first accordion UI module for progressive disclosure on the web.

<ul class="m-bellows">
    <li class="m-item">
        <h3 class="m-header">
            <a>Tab1</a>
        </h3>
        <div class="m-content">
            <div class="m-inner-content">
                <h2>Content 1</h2>
                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui icia deserunt mollit anim id est laborum.</p>
            </div>
        </div>
    </li>
    <li class="m-item">
        <h3 class="m-header">
            <a>Tab2</a>
        </h3>
        <div class="m-content">
            <div class="m-inner-content">
                <h2>Content 2</h2>
                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
            </div>
        </div>
    </li>
    <li class="m-item">
        <h3 class="m-header">
            <a>Tab3</a>
        </h3>
        <div class="m-content">
            <div class="m-inner-content">
                <h2>Content 3</h2>
                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui icia deserunt mollit anim id est laborum.</p>
                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui icia deserunt mollit anim id est laborum.</p>
            </div>
        </div>
    </li>
</ul>

<div class="btn-container actions">
	<a href="http://cdn.mobify.com/modules/bellows/0.3.0/bellows.zip" class="btn btn-primary">Download Bellows</a>
	<ul>
        <li><a href="{{ site.baseurl }}examples">See more examples</a></li>
	    <li><a href="https://github.com/mobify/bellows">View the Github repo</a></li>
    </ul>
    <p>This module is also hosted on Mobify's CDN:</p>
    <p><u>CSS</u></p>
    <pre><code class="xml">&lt;link rel="stylesheet" href="http://cdn.mobify.com/modules/bellows/0.2.0/bellows.min.css">
&lt;link rel="stylesheet" href="http://cdn.mobify.com/modules/bellows/0.3.0/bellows-style.min.css"></code></pre>
    <p><u>JavaScript</u></p>
    <pre><code class="xml">&lt;script src="http://cdn.mobify.com/modules/bellows/0.3.0/bellows.min.js"></script></code></pre>
</div>


## Usage<a id="usage"></a>

    <!-- include bellows.css -->
    <link rel="stylesheet" href="http://cdn.mobify.com/modules/bellows/0.3.0/bellows.min.css">
    <link rel="stylesheet" href="http://cdn.mobify.com/modules/bellows/0.3.0/bellows-style.min.css">

    <!-- the markup -->
	<ul class="m-bellows">
	  <!-- the items -->
	  <li class="m-item">
	    <h3 class="m-header">
	      <!-- header title -->
	      <a>Tab1</a>
	    </h3>
        <div class="m-content">
          <div class="m-inner-content">
            <!-- content for item -->
            <h2>Content 1</h2>
            <h2>Lorem Ipsum</h2>
          </div>
        </div>
	  </li>
      <li class="m-item">
        <h3 class="m-header">
          <a>Tab2</a>
        </h3>
        <div class="m-content">
          <div class="m-inner-content">
            <h2>Content 2</h2>
            <p>Lorem Ipsum</p>
          </div>
        </div>
      </li>
	  <li class="m-item">
	    <h3 class="m-header">
	      <a>Tab3</a>
	    </h3>
	    <div class="m-content">
	      <div class="m-inner-content">
	        <h2>Content 3</h2>
	        <p>Lorem Ipsum</p>
	      </div>
	    </div>
	  </li>
	</ul>

    <!-- include zepto.js or jquery.js -->
    <script src="http://code.jquery.com/jquery-1.10.1.min.js"></script>
    <!-- include bellows.js -->
    <script src="http://cdn.mobify.com/modules/bellows/0.3.0/bellows.min.js"></script>
    <!-- construct the bellows -->
    <script>$('.m-bellows').bellows()</script>

## Methods<a id="methods"></a>

### bellows()

Initializes the bellows.

    $('.m-bellows').bellows();

### bellows(options)

Initialize with options.

    $('.m-bellows').bellows({
      {
        ...
        options (refer below)
        ...
      }
    });

### Storing bellows object for future use

    var $bellows = $(".m-bellows"); // A Zepto element array is returned
    var bellows = $bellows[0].bellows; // We access the appropriate bellows from the above array

### unbind()

Removes any tap, mouse, and other event handlers from the bellows.

    bellows.unbind();

### bind()

Restores the tap, mouse, and other event handlers for the bellows.

    bellows.bind();

### destroy()

Unbinds the events from the bellows, and removes it from the DOM.

    bellows.destroy(); // destroys the DOM element and the jQuery bindings
    bellows = null; // destroys the Mobify bellows object as well

### open($item)

Open the selected bellows item

    bellows.open($(".m-item").eq(2));

### close($item)
    
Close the selected bellows item

    bellows.close($("#some-item"));

### recalculateItemHeight($item)

Recalculate the heights of bellows item elements. This is used when the heights of the content have changed after creation of the bellows.

    bellows.recalculateItemHeight($(".m-item"));

## Class names<a id="class-names"></a>

Set the class names for the different elements, if deviating from the defaults.
  
    $(".m-bellows").bellows({
      closedClass: 'm-closed',
      openedClass: 'm-opened',
      activeClass: 'm-active',
      contentClass: 'm-content',
      innerContentClass: 'm-inner-content',
      headerClass: 'm-header',
      itemClass: 'm-item'
    });

## Event hooks<a id="event-hooks"></a>

### onTransitionDone: functionName

Execute this function every time the selected bellows item is opened or closed.

    $(".m-bellows").bellows({
        onTransitionDone: function() { console.log("Animation done"); }
    });

### onOpened: functionName

Execute this function every time the selected bellows item is opened.

    $(".m-bellows").bellows({
        onOpened: function() { console.log("Opened"); }
    });

### onClosed: functionName

Execute this function every time an bellows item is closed
    
    $(".m-bellows").bellows({
        onClosed: function() { console.log("Closed"); }
    });

## Browser Support<a id="browser-support"></a>


| Browser           | Version | Support                    |
|-------------------|---------|----------------------------|
| Safari            | 4.0+    | Supported.                 
| Firefox           | 3.5-3.6 | Degraded. No transitions.  
| Firefox           | 4.0+    | Supported                  
| Chrome            | 9.0+    | Supported                  
| Opera             | 12.0+   | Supported.                 
| Internet Explorer | 6-7.0   | Not Supported              
| Internet Explorer | 8.0     | Degraded. No transitions.  
| Internet Explorer | 9.0     | Degraded. No transitions.  
| Internet Explorer | 10.0    | Supported                  
| Mobile Safari     | 3.1.*   | Degraded. No transitions   
| Mobile Safari     | 4.0+    | Supported                  
| Android Browser   | 2.1+    | Supported                  
| Chrome (Android)  | 1.0+    | Supported                  
| Firefox (Android) | 1.0+    | Supported                  
| Windows Phone     | 7.5     | Degraded. No transitions.  
