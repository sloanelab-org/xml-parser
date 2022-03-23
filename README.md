# Sloane Lab XML Parser

This repository contains the parser that is used to import data from the [Enlightenment Architectures](https://enlightenmentarchitectures.reconstructingsloane.org/) XML files into the [Sloane Lab](http://sloanelab.org/) knowledge base.

The code of the parser is in the Jupyter notebook [Sloane_XML_Parser.ipynb](https://github.com/sloanelab-org/xml-parser/blob/main/Sloane_XML_Parser.ipynb). The following libraries are required:

* [Beautiful Soup](https://www.crummy.com/software/BeautifulSoup/), to parse the XML
* [Pandas](https://pandas.pydata.org/), to manipulate and analyse the data
* [Matplotlib](https://matplotlib.org/), to create charts
* [Mapbox](https://pypi.org/project/mapbox/), to create maps
* [Viapy](https://pypi.org/project/viapy/), to query the VIAF API

The XML catalogues are stored in the [data](https://github.com/sloanelab-org/xml-parser/tree/main/data) directory.
