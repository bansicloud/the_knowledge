# the_knowldege

Proof of concept code to exploit quirk in how google renders knowledge panels.
Concept from https://wietzebeukema.nl/blog/spoofing-google-search-results

##### Example run:

![](md_photos/demo_run.png)

Dependencies are listed in requirements.txt.
Program needs gecko driver for selenium too.

##### Reasons it's breaking
1. No knowledge panel for second entry
1. The wrong kind of knowledge panel for the second entry
1. Your search entry contains non-letter characters, as more url handeling is still being developed
1. looking at it funny
1. Longer than usual page load times, as this does not utilize such features in selenium  