# OKRIA Marketing Site Source
Source and documentation for okria.io the marketing website for the OKRIA model, associated services, and resources including the OKRIA Canvas.

## Table of Contents
- [Features](#features)
- [Appendix](#appendix)

## Features
1. [Globals](#1-globals)
2. [Home page](#2-home-page)
3. [Canvas landing page](#3-canvas-landing-page)
4. [Canvas download page](#4-canvas-download-page)
5. [Blog](#5-blog)
   1. OKR Anatomy 101
   2. OKR Workshop How To

## 1. Globals
As a director or manager I need to navigate the OKRIA website in order to learn about the model and offering.

### Scenarios
1. Home menu item
2. Canvas menu item
3. Contact menu item
4. Footer content
5. Privacy policy

```
Feature 1. Globals
  In order to learn about OKRIA
  As a director or manager
  I need to navigate the site

  Scenario 1. Home menu item
    Given I am on okria.io
    When I click OKRIA in the navigation bar
    Then I navigate to the home page

  Scenario 2. Canvas menu item
    Given I am on okria.io
    When I click Canvas in the navigation bar
    Then I navigate to the Canvas landing page

  Scenario 3. Contact menu item
    Given I am on OKRIA.io
    When I click Contact in the navigation bar
    Then I navigate to the Contact form on the home page

  Scenario 4. Footer content
    Given I am on okria.io
    When I scroll to the bottom of the page
    Then I find additional information in the footer

  Scenario 5. Privacy Policy
    Given I am interested in signing up or downloading a resource
    And I need to determine how my information will be used
    When I click Privacy Policy in the footer
    Then I download a PDF of the Privacy Policy
```

## 2. Home Page
As a director or manager I need to learn about OKR coaching in order to facilitate workshops

### Scenarios
1. Awareness
2. Introduction
3. What is it?
4. How does it work?
5. Canvas CTA
6. Contact

### Acceptance
```
Feature 2. Home Page
  In order to facilitate running OKR planning workshops
  As a director or manager
  I need to learn about OKR coaching models

  Scenario 1. Awareness
    Given I am searching for how to run an OKR workshop
    When I find OKRIA in my search results
    And I click the search result
    Then I am directed to the OKRIA home page
    And I am able to read an introduction to the model

  Scenario 2. Introduction
    Given I am on the homepage
    When I navigate to the Introduction section
    Then I find content introducing OKRIA

  Scenario 3. What is it?
    Given I am on the homepage
    When I navigate to learn what OKRIA is
    Then I find content describing the model
    And it's 2 core features

  Scenario 4. How does it work?
    Given I am on the homepage
    When I navigate to learn how OKRIA works
    Then I find content describing the offering
    And a featured resource I can use to apply the model

  Scenario 5. Canvas Call To Action
    Given I am on the homepage
    When I have navigated to learn how OKRIA works
    Then I find a call to action to download
    And and a call to action to learn more
    When I click to download
    Then I am directed to a download form
    When I click to Learn more
    Then I am directed to more information about the resource

  Scenario 6. Contact
    Given I am on the home page
    When I navigate to contact
    Then I am directed to a contact form
    When I complete the form fields
    And submit the form
    Then an email is sent
    And I receive confirmation
```

## 3. Canvas Landing Page
As a director or manager I need to find a canvas toolkit to facilitate running practical OKR workshops

### Scenarios
1. Introduction
2. Features and Benefits
3. Download Webform
4. Subscription

```
Feature 3. Canvas Landing Page
  In order to facilitate running practical OKR workshops
  As a director or manager
  I need a canvas workshop toolkit

  Scenario 1. Introduction
    Given I have navigated to the canvas landing page
    When I navigate to the introduction
    Then I find information about the canvas
    And an image of the kit
    And a call to action to download
    When I click download
    Then I navigate to the download webform

  Scenario 2. Features and Benefits
    Given I have navigated to the canvas landing page
    When I am interested in learning more
    Then I find additional information about the features and benefits

  Scenario 3. Download Form
    Given I have navigated to the canvas landing page
    When I have learned about the canvas
    And I am interested
    Then I find a download form
    When I complete the form
    And it's required fields
    And I submit the form
    Then I am directed to a download page

  Scenario 4. Subscription
    Given I have completed the download form
    When I agree to receive other communication from OKRIA
    And submit the form
    Then I am subscribed

Backlog
-------
  Scenario 5. How-To
    Given I have navigated to the Canvas landing page
    When I am unclear on how to use the canvas
    Then I find how-to content


```

## 4. Canvas download Page
As a director or manager I need to download the canvas toolkit in order to print it for use in my workshops

### Scenarios
1. Details
2. Download link

```
Feature 4. Canvas download page
  In order to print it for my workshop
  As a director or manager
  I need to download the OKRIA canvas toolkit

  Scenario 1. Details
    Given I have completed the download form
    When I am directed to the download page
    Then I find additional information about the download
    And a download button

  Scenario 2. Download link
    Given I am on the download page
    When I click the download button
    Then the PDF file is downloaded

Backlog
-------
  Scenario 4. Download Options
    Given I am on the download page
    When I click to download the tabloid sized canvas
    Then I get a 11" x 17" PDF
    When I click to download the letter sized canvas
    Then I get an 8.5" x 11" PDF
```

## 5. Blog
As a manager I need continuous learning about how to implement OKR at my organization so I can become a thought leader

### Scenarios

```
Feature 5. Blog
  In order to become a thought leader
  As a director or manager
  I need continuous learning about how to implement OKR

  Scenario 1. Blog index
    Given I am a visitor to okria.io
    When I click the Blog link in the navigation bar
    Then I am directed to a blog index
    And I find a list blog list item

  Scenario 2. Blog article
    Given I have navigated to the blog index
    When I click on a blog list item
    Then I navigate to the article
    And I am able to read it's contents

  Scenario 3. Canvas call to action
    Given I have navigated to a blog article
    When I complete reading it's contents
    Then I find a call to action to download the canvas
    And to learn more
    When I click the download call to action
    Then I navigate to the canvas download form
    When I click the learn more call to action
    Then I navigate to canvas landing page
```

## Stories
### 5.1 OKR Anatomy 101
As a director or manager I need guidelines for strong OKRs in order to ensure goals that are motivational, achievable, and meaningful to my team

#### Scenarios
1. Introduction
2. Objectives
3. Key Results
4. Initiatives and Activities
5. Canvas call to action

### 5.2 OKR Workshops How To
As a director or manager I need a step by step guide to running OKR workshops in order to help run a successful OKR workshop

### Scenarios
1. Introduction
2. Preparation
2. Workshopping Objectives
3. Workshopping Key Results
4. Synthesis and share-out

```

```

## 5.3 1 A Year OKR Plan
1. Introduction
1. Annual Objectives and Key Results
2. Quarterly initiatives and activities
3. Quarterly review
4. Annual review
5. Looping around

## Appendix

### Jekyll Instructions

To install for local development in the command line enter the following command in the project root directory:

```
bundle install
```

To run a local server for development:

```
bundle exec jekyll serve
```

To run a build to the project `_site` folder:

```
bundle exec jekyll build
```
