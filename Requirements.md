# Requirements

This document defines all requirements for the product. It will be used as a basis for creating development tasks and the development phase will be graded against completion of these requirements.

There are two types of requirements: core (those the team commits to meeting during development) and stretch (those the team would like to complete, but cannot commit to). Stretch goals are clearly labeled.

## General

Every page in the site will include a navigation bar with links to all pages: Home, Learn (*stretch*), and Idea Generator.

## Home Page

1. Contains a title
1. Contains text about the problem of textile waste
1. Contains text about the value of textile reuse
1. Contains a call to action (with link to the page) to try the Idea Generator
1. Contains an embedded YouTube video on a mending technique
    1. There are several possible videos that might be displayed, so user should rarely see the same video twice

## Learn Page (*stretch*)

1. The page is divided into three sections: Repair, Remix, and Create
1. The names of the three sections are displayed in a way that is selectable (e.g. tabs or buttons)
1. On arrival to the page, Repair is selected
1. The content in the body of the page changes dynamically when a different section name is selected
1. The content for each section includes one highlighted technique, including an image and some text about it
1. The content for each section includes a list of links to resources for other techniques
1. The Repair section includes topics like "darning knit goods" and "replacing a zipper"
1. The Remix section includes topics like "DIY: T-Shirt into High Neck Tank Top" and "Thrift flip Hawaiian shirt into crop top and shorts"
1. The Create section includes topics like "using a pattern" and "how to select fabric"

## Idea Generator Page

1. There are three select type form fields at the top of the page and a submit button.
1. The three fields are "garment type", "vibe", and "skill level." (Labels may be slightly different in final product)
1. Each field is optional, but at least one must have input for the form to submit successfully
1. If the user clicks the submit button without selecting any options, an error message will appear at the top of the form
1. The options for "garment type" field will be 4 types of garment, e.g. "t-shirt" or "skirt"
1. The options for "vibe" field will be 3 styles, e.g. "cottagecore" or "dad"
1. The options for "skill level" will reflect how complex a project is, e.g. "high skill" or "low difficulty"
1. When the form is submitted successfully, the application will display a remix idea from its data store that meets all of the requirements
1. There is no combination of options that will not have at least one matching remix idea
1. When the form is submitted, a cute animation is briefly displayed to the user (*stretch goal*)
1. When the result is displayed, the form disappears and is replaced by a "try again" button
1. The result displayed includes an image, some introductory text, and a link to an external tutorial
1. If the "try again" button is clicked
    1. the result disappears
    2. the form reappears with all previous selections cleared
