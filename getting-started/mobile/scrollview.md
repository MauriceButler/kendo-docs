---
title: ScrollView
slug: gs-mobile-scrollview
tags: getting-started,mobile
publish: true
---

# ScrollView

The Kendo Mobile ScrollView widget is used to scroll content wider than the device screen.

## Getting Started

The Kendo Mobile Application automatically initializes the Mobile ScrollView for every element with `role` data attribute set to `scrollview` present in the views' markup.
Alternatively, it can be initialized using jQuery plugin syntax in the containing mobile View **init event handler**.

### Initialize mobile ScrollView using a role data attribute.

    <div data-role="scrollview">
        Foo
    </div>

### Initialize mobile ScrollView using jQuery plugin syntax.

    <div data-role="view" data-init="initScrollView">
        <div id="scrollView">
            <div data-role="page">Foo</div>
            <div data-role="page">Bar</div>
        </div>
    </div>

    <script>
        function initScrollView(e) {
            e.view.element.find("#scrollView").kendoMobileScrollView();
        }
    </script>

## Pages

Content pages may be defined in order to display exactly one item per page. Pages are automatically resized
when the device is rotated. To define a page, wrap the content in a div with `data-role="page"` attribute set.

### ScrollView with pages

    <div data-role="scrollView">
        <div data-role="page">Foo</div>
        <div data-role="page">Bar</div>
    </div>

### Clearing the whitespaces

Whitespaces between page elements in the mark-up causes the ScrollView pager to display an extra page. In order to fix this any whitespace between page elements should be removed.

    <div data-role="page">
        <!--page content-->
    </div><div data-role="page">
        <!--page content-->
    </div><div data-role="page">
        <!--page content-->
    </div>

If a Kendo template is used to generate the pages the whitespace gaps can be avoided in the following way.

    <script type="text/x-kendo-template" id="tmp"><div data-role="page" >
        <!-- page content -->
    </div></script>
