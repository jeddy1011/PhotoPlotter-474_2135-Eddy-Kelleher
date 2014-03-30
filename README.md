PhotoPlotter-474_2135-Eddy-Kelleher
===================================

A tool to analyze photo(s) and print the location of them to STDOUT. It will also have an option to write the location of the photo(s) to an HTML file with links to the location on Google Maps.


Install necessary modules via CPAN
===================================

- Image::ExifTool
- Image::ExifTool:Location
- HTML::QuickTable
- Getopt::Long
- Geo::Coordinates::DecimalDegrees


Usage
==================================

- perl pp.pl <options> <image_file(s)>


Options
==================================

- h|help  Show help

-f        File(s) to extract info on

-m        Output location info to HTML file
