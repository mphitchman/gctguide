These pages, still in development, and written by Michael P. Hitchman, provide activities to supplement the content in the text Geometry with an Introduction to Cosmic Topology, by Michael P. Hitchman, focusing on two tools: Sage cells and Geogebra.

COMPILING THE ACTIVITY BOOKLET

1. To process HTML for the GCTguide (publisher stuff gives the geogebra calc):

		xsltproc --xinclude xsl/gcta-html.xsl src/gct-guide.ptx

2. To process LATEX for the gct-guide

      		xsltproc --xinclude -o gct-guide.tex xsl/gcta-latex.xsl src/gct-guide.ptx
