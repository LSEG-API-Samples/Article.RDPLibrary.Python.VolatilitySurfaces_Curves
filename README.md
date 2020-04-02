# Instrument Pricing Analytics - Volatility Surfaces

In one of my <a href="https://developers.refinitiv.com/article/discover-our-refinitiv-data-platform-library-part-2" target="_blank">earlier articles</a> on our new Refinitiv Data Platform Library, I briefly covered our Instrument Pricing Analytics (IPA) data content.

As it was meant to be an overview of the RDP Library, I only covered a fraction of the currently available IPA content. I also only highlighted a subset of the types of output that Samuel Schwam  (Director, Enterprise Pricing Analytics), demoed during the <a href="https://developers.refinitiv.com/pages/london-developer-day-agenda" target="_blank">London Developer Day event</a>. 

In this Jupyter Notebook I would like to cover one of these content types - the Volatility Surface offering - in more detail.
 
#### Acknowledgements
Although I modified the code for the plots in this article (to improve their look and format), the starting point was Samuel Schwalm's (Director, Enterprise Pricing Analytics) Surfaces and Curves notebook - for which I thank him.


### References
<a href="https://developers.refinitiv.com/article/discover-our-refinitiv-data-platform-library-part-1" target="_blank">Discover our new Refinitiv Data Platform Library</a> - Part 1 of RDP intro article

<a href="http://api.refinitiv.com/" target="_blank">API Playground</a> - Interactive Documentation for Refinitiv Data Platform APIs.

RDP EAP library on <a href="http://pypi.org/project/refinitiv-dataplatform/" target="_blank">PyPi</a> - install by executing 'pip install refinitiv-dataplatform' - in your Python environment

<a href="https://developers.refinitiv.com/refinitiv-data-platform/refinitiv-data-platform-apis" target="_blank"> Refinitiv Data Platform APIs</a> - our existing REST-based interface to the cloud Platform.

<a href="https://community.developers.refinitiv.com/spaces/321/index.html" target="_blank">Q&A Forum</a> for the Refinitiv Data Platform Library 

**Disclaimer**  
As this article is based on Beta versions, the method signatures, data formats etc are subject to change.
