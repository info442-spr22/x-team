# Delivery Schedule

Two development sprints:
 - April 26 - May 8
 - May 9 - May 17

To minimize risk, tasks that will be more challenging or time consuming will be scheduled for the first sprint.

All changes will be deployed to production as they are completed.

## Milestones

### Sprint 1

1. Home Page deployed April 28
  Build unstyled home page and deploy to Netlify. Should include static content only (placeholder text about problem and value of reuse, call to action with disabled link).
1. YouTube embed on home page May 1
  On page load, dynamically determine which video to display so user rarely sees the same one repeatedly. Ideally, videos will be fetched via searches using the YouTube API. Fallback method is to maintain a static list in the code of relevant videos and choose psuedo-randomly from the list.
1. Data store live May 4
  All data for Idea items is created and loaded into a MongoDB data store on mLab. (Repair, Remix, and Create items will be loaded at a later time, if Learn Page stretch goal is acheived)
1. Idea generator page forms May 8
  Create HTML for the form on idea generator. Fields are "garment type", "vibe", and "skill level."

### Sprint 2

1. First set of styles applied May 10
  Page layouts and color palette. All pages will be usable on viewports wider than 400px.
1. Dynamic idea generation May 14
  Code form submit handler for Idea Generator page. Perform validation and processing to select an Idea item from data store. Display the Idea item, hide the form, display "try again" button. Click handler for "try again" button that removes Idea and shows form again.
1. Real text content May 15
  Create real text content about problem and solution for the home page. Insert into the HTML. Review labels and values for Idea Generator form, improve as necessary.
1. Second set of styles May 17
  Add fonts, improve colors. Add decorative items as necessary. Test on more real devices.
