# svglite-affinity-designer

Testing the svglite R package with Mac Affinity Designer (v1.4.1)

# Problem

When combining multiple plots (using cowplot), the resultant svg comes out with two black boxes. 

> It appears as though Affinity is not able to read the embedded stylesheet used in the SVG (where it defines objects to have no fill unless specified). Instead it treats this as having a black fill which is where you are getting the two black rectangles from. I also got the same behaviour with your ggplot2_test-1.svg file.
