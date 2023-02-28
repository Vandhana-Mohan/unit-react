# Intro to Bootstrap CSS with React

## Introduction

Often, developers find that they have the same problems in many projects.

When it comes to CSS, several problems happen over and over again. For example:

- Consistency across browsers
- Making reliable responsive/mobile and desktop versions
- Styling forms to look more modern and user friendly

Rather than each developer coding their solution and using it repeatedly, developers get together and make a code library or framework.

One popular CSS framework is called Bootstrap. It was initially developed at Twitter and was made open source in 2011. As an open-source project, anyone can use these code solutions for free, and they can also contribute to improving the project.

## Learning Objectives

- Adding Bootstrap CSS to a project
- Adding classes to HTML elements to style with Bootstrap CSS

## How to get Bootstrap

When using Create React App, all you need to do is grab the CDN (Content Delivery Network) link.

Search for `bootstrap css cdn`. A top link should be the [Quick start page of Bootstrap's official](https://getbootstrap.com/docs/4.3/getting-started/introduction/) documentation.

> **Note**: You will be using Bootstrap version 5.x for this lesson.

> **Note**: You will only be using the CSS link for this lesson (not installing with npm or any other means to add Bootstrap).

In your Create React App, go to `public/index.html` and inside the `head` tag, add the link tag that you copied from the Bootstrap documentation.

## How to use Bootstrap

On the [main docs page](https://getbootstrap.com/docs/5.3/examples/) of Bootstrap's documentation, you'll notice a lot of different options. The focus of today's lesson will be styling only.

Return to [the docs tab](https://getbootstrap.com/docs/5.3/getting-started/introduction/), along the left side is a menu broken up into a few sections. Scroll down to `Content` and select `Tables`.

> **Note**: Check the url to be sure you are looking at the correct version of the documentation for the version of Bootstrap you are working with. The CDN link that you copied was for version `5.3.0` - so check the URL to be sure you are looking at the correct documentation. It should be: https://getbootstrap.com/docs/5.3/getting-started/introduction/ . You can always change the version by going to the top of the nav bar and selecting a version with the pull-down menu.

The general style of the documentation is to show a demonstration of the styling and then have the example code below.

Here is the page for [Tables](https://getbootstrap.com/docs/5.3/content/tables/). You can use Create React App to create a new app, add the CDN to the `public/index.html` and copy paste the demo code into `src/App.js` to see Bootstrap CSS in action.

Some good first ones to check out are:

- Layout/Overview
- Content/Typography
- Content/Images
- Content/Tables
- Components/Buttons
- Components/Card
- Component/Forms

**Note**: Many components have functionality that require JavaScript. For example Components/Carousel. While these are great features to have on a website, they are beyond the scope of today's lesson and incorporating this functionality into a React app would be done a bit differently.

**Note**: There are also many customization options using Sass (Semantically Awesome Style Sheets). Learning to use Sass is beyond the scope of today's lesson as well.
