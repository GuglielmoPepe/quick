# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).


## [Unreleased]



## 2.2.0 - 2022-12-06

### Added

 - Add '--qk--anchor-color--active' variable
 - Add '--qk--anchor-color--hover' variable
 - Add '--qk--anchor-color--link' variable
 - Add '--qk--anchor-color--visited' variable
 - Add '--qk--font-family--body' variable
 - Add '--qk--font-family--heading' variable
 - Add '--qk--font-family--inline' variable
 - Add neutral color palette


### Changed

 - Change examples in docs
 - Change background-color in 'kbd' selector's rules
 - Change color in 'kbd' selector's rules
 - Change background-color in 'mark' selector's rules
 - Change color in 'mark' selector's rules
 - Change background-color in 'code' selector's rules
 - Change color in 'code' selector's rules
 - Change background-color in 'pre' selector's rules
 - Change color in 'pre' selector's rules


### Fixed
 - Fix url of resources in example.html


### Removed
 - Remove margins in 'article' selector's rules
 - Remove margins in 'aside' selector's rules
 - Remove margins in 'footer' selector's rules
 - Remove margins in 'h1' selector's rules
 - Remove margins in 'h2' selector's rules
 - Remove margins in 'h3' selector's rules
 - Remove margins in 'h4' selector's rules
 - Remove margins in 'h5' selector's rules
 - Remove margins in 'h6' selector's rules
 - Remove margins in 'header' selector's rules
 - Remove margins in 'nav' selector's rules
 - Remove margins in 'section' selector's rules



## 2.1.1 - 2021-03-14
 - Change examples page in docs
 - Fix stylesheet url in docs
 - Fix CHANGELOG.md heading



## 2.1.0 - 2021-03-13

### Added

 - Add 'id' attribute for heading sections in docs/example.html
 - Add text-size-adjust to prevent adjustments of font size after orientation changes
 - Add float property to nav li::before 


### Changed

 - Change css variables
 - Change font-size rules according a typographic scale
 - Change measures according a grid scale
 - Change font-family for readibility


### Removed

 - Remove the '[aria-hidden = "true"]' attribute from elements that contain focusable descendants
 - Remove 'hgroup' rules: the 'hgroup' element has been removed from the HTML5 (W3C) specification
 - Remove display='block' property for 'table' selector
 - Remove 'nav ol' selector
 - Remove 'nav ul' selector
 - Remove select background styling when multiple attribute is also present 
 - Remove resize=block attribute to textarea selector


### Fixed

 - Fix stylesheet URL in docs
 - Fix version in package.json
 - Fix unclosed tag 'img' in docs/example.html



## 2.0.0 - 2020-04-14

### Added

 - Add meta description in docs/example.html file
 - Add meta description in docs/download.html file
 - Add meta description in docs/index.html file
 - Add 'max-width' property for 'body' selector
 - Add 'padding' property for 'body' selector
 - Add 'height' and 'width' attribute for 'img' tag in docs/example.html
 - Add ':root' pseudo-class and some variables
 - Add 'small' tag in 'body > footer' in docs/example.html


### Changed

 - Change url absolute in url relative in documentation
 - Change target="_blank" with rel="external" to any external links in docs to improve performance and prevent security vulnerabilities
 - Change CSS style rules
 - Change CSS url in docs: now link local stylesheet
 - Change comment language in docs
 - Change html of forms section in docs/example.html file to improve performance
 - Change border-left-width property for 'blockquote' selector
 - Change individual margin properties with shortand property for 'address' selector
 - Change individual margin properties with shortand property for 'article' selector
 - Change individual margin properties with shortand property for 'aside' selector
 - Change individual margin properties with shortand property for 'audio' selector
 - Change individual margin properties with shortand property for 'body' selector
 - Change individual margin properties with shortand property for 'details' selector
 - Change individual margin properties with shortand property for 'header' selector
 - Change individual margin properties with shortand property for 'hgroup' selector
 - Change individual margin properties with shortand property for 'nav' selector
 - Change individual margin properties with shortand property for 'section' selector
 - Change individual margin properties with shortand property for 'nav > ul' selector
 - Change individual margin properties with shortand property for 'div' selector
 - Change individual margin properties with shortand property for 'dl' selector
 - Change individual margin properties with shortand property for 'dl dl' selector
 - Change individual margin properties with shortand property for 'ol dl' selector
 - Change individual margin properties with shortand property for 'ul dl' selector
 - Change individual margin properties with shortand property for 'ol' selector
 - Change individual margin properties with shortand property for 'dl ol' selector
 - Change individual margin properties with shortand property for 'ol ol' selector
 - Change individual margin properties with shortand property for 'ul ol' selector
 - Change individual margin properties with shortand property for 'ul' selector
 - Change individual margin properties with shortand property for 'dl ul' selector
 - Change individual margin properties with shortand property for 'ol ul' selector
 - Change individual margin properties with shortand property for 'ul ul' selector
 - Change individual margin properties with shortand property for 'hr' selector
 - Change individual margin properties with shortand property for 'main' selector
 - Change individual margin properties with shortand property for 'p' selector
 - Change individual margin properties with shortand property for 'pre' selector
 - Change individual margin properties with shortand property for 'blockquote' selector
 - Change individual margin properties with shortand property for 'figure' selector
 - Change individual margin properties with shortand property for 'li' selector
 - Change individual margin properties with shortand property for 'img' selector
 - Change individual margin properties with shortand property for 'picture' selector
 - Change individual margin properties with shortand property for 'video' selector
 - Change individual margin properties with shortand property for 'table' selector
 - Change individual margin properties with shortand property for 'form' selector
 - Change individual margin properties with shortand property for 'legend' selector
 - Change individual margin properties with shortand property for 'optgroup' selector
 - Change individual margin properties with shortand property for 'select' selector
 - Change individual margin properties with shortand property for 'textarea' selector
 - Change individual margin properties with shortand property for 'footer' selector
 - Change individual margin properties with shortand property for 'h1' selector
 - Change individual margin properties with shortand property for 'hgroup > h1' selector
 - Change individual margin properties with shortand property for 'h2' selector
 - Change individual margin properties with shortand property for 'hgroup > h2' selector
 - Change individual margin properties with shortand property for 'h3' selector
 - Change individual margin properties with shortand property for 'hgroup > h3' selector
 - Change individual margin properties with shortand property for 'h4' selector
 - Change individual margin properties with shortand property for 'hgroup > h4' selector
 - Change individual margin properties with shortand property for 'h5' selector
 - Change individual margin properties with shortand property for 'hgroup > h5' selector
 - Change individual margin properties with shortand property for 'h6' selector
 - Change individual margin properties with shortand property for 'hgroup > h6' selector
 - Change individual margin properties with shortand property for 'button' selector
 - Change individual margin properties with shortand property for 'fieldset' selector
 - Change individual border properties with shortand property for 'fieldset' selector
 - Change individual padding properties with shortand property for 'blockquote' selector
 - Change individual padding properties with shortand property for 'figure' selector
 - Change individual padding properties with shortand property for 'nav > ul' selector
 - Change individual padding properties with shortand property for 'pre' selector
 - Change individual padding properties with shortand property for 'code' selector
 - Change individual padding properties with shortand property for 'kbd' selector
 - Change individual padding properties with shortand property for 'mark' selector
 - Change individual padding properties with shortand property for 'var' selector
 - Change individual padding properties with shortand property for 'td' selector
 - Change individual padding properties with shortand property for 'th' selector
 - Change individual padding properties with shortand property for 'button' selector
 - Change individual padding properties with shortand property for 'button::-moz-focus-inner' selector
 - Change individual padding properties with shortand property for 'input' selector
 - Change individual padding properties with shortand property for 'textarea' selector
 - Change individual padding properties with shortand property for '[type="button"]::-moz-focus-inner' selector
 - Change individual padding properties with shortand property for 'details[open]' selector
 - Change individual padding properties with shortand property for 'dialog' selector
 - Change individual padding properties with shortand property for '[type="submit"]::-moz-focus-inner' selector
 - Change individual padding properties with shortand property for '[type="reset"]::-moz-focus-inner' selector
 - Change individual padding properties with shortand property for '[type="radio"]' selector
 - Change individual padding properties with shortand property for '[type="checkbox"]' selector
 - Change individual padding properties with shortand property for 'fieldset' selector
 - Change margins and paddings for 'body' selector
 - Change margins for 'h1' selector
 - Change margins for 'h2' selector
 - Change margins for 'h3' selector
 - Change margins for 'h4' selector
 - Change margins for 'h5' selector
 - Change margins for 'h6' selector
 - Change margins for 'hgroup' selector
 - Change margin-top for 'body > footer' selector


### Removed

 - Remove input with datetime attribute
 - Remove display='block' property for 'fieldset label' selector
 - Remove display='inline-block' property for 'label' selector
 - Remove display='inline-block' property for 'input' selector
 - Remove margin-bottom='1.5em' property for 'fieldset button' selector
 - Remove margin-bottom='1.5em' property for 'fieldset input' selector
 - Remove margin-bottom='1.5em' property for 'fieldset select' selector
 - Remove margin-bottom='1.5em' property for 'fieldset textarea' selector
 - Remove margin-bottom='1.5em' property for 'fieldset [type="checkbox"]' selector
 - Remove margin-bottom='1.5em' property for 'fieldset [type="radio"]' selector
 - Remove 'body article' selector
 - Remove 'body aside' selector
 - Remove 'body footer' selector
 - Remove 'body header' selector
 - Remove 'body main' selector
 - Remove 'body nav' selector
 - Remove 'body section' selector
 - Remove font-size='0.875em' property for 'footer' selector
 - Remove line-height='1.714em' property for 'footer' selector


### Fixed

 - Fix margins for 'blockquote' selector
 - Fix margins for 'dd' selector
 - Fix margins for 'figure' selector
 - Fix margins for 'input' selector
 - Fix margins for 'ol' selector
 - Fix margins for 'ul' selector
 - Fix margins for 'p' selector
 - Fix paddings for 'blockquote' selector docs/example.html file
 - Fix id and name attributes of radio input in docs/example.html file
 - Fix value attribute of input with type="url" in docs/example.html file
 - Fix for attribute of label of password input tag in docs/example.html file
 - Fix id and name attributes of text input inline in docs/example.html file
 - Fix margins and paddings for 'nav > ul' selector



## 1.0.2 - 2020-10-05
 - Fix bug select multiple in Chrome
 - Fix url of changelog file in readme



## 1.0.1 - 2020-03-31
- Fix margins for mobile
- Fix font-size unit for small element 



## 1.0.0 - 2020-03-28
