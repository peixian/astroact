- [Astroact - Web interface for keeping up to date on ADS (astrophysics data system) - <http://astroact.org>](#sec-1)
    - [Differences from [arxiv-sanity-preserver](https://github.com/karpathy/arxiv-sanity-preserver):](#sec-1-0-1)
    - [Code Layout:](#sec-1-0-2)
    - [Dependencies:](#sec-1-0-3)
    - [Processing pipeline:](#sec-1-0-4)
    - [Pushing to production:](#sec-1-0-5)
    - [Workflow:](#sec-1-0-6)
    - [References:](#sec-1-0-7)

# Astroact - Web interface for keeping up to date on ADS (astrophysics data system) - <http://astroact.org><a id="orgheadline16"></a>

Forked from the wonderful [arxiv-sanity-preserver](https://github.com/karpathy/arxiv-sanity-preserver), astroact seeks to accomplish the same goal as arxiv-sanity-preserver: find papers you actually care about, but in astrophysics. 

### Differences from [arxiv-sanity-preserver](https://github.com/karpathy/arxiv-sanity-preserver):<a id="orgheadline4"></a>

1.  1. Integration with [ascl.net](http://ascl.net/):

    If there's code for the paper, astroact will link the code.

2.  2. ADS integration:

    Search for similar papers on ADS, using the topic/author/affiliation

3.  3. Citation count:

    Find how many times and who's cited a paper.

### Code Layout:<a id="orgheadline5"></a>

### Dependencies:<a id="orgheadline6"></a>

### Processing pipeline:<a id="orgheadline7"></a>

### Pushing to production:<a id="orgheadline8"></a>

### Workflow:<a id="orgheadline9"></a>

### References:<a id="orgheadline15"></a>

1.  <http://api.altmetric.com/>

2.  <https://github.com/andycasey/ads>

3.  <https://github.com/adsabs/adsabs-dev-api>

4.  <http://ascl.net/>

5.  <https://github.com/karpathy/arxiv-sanity-preserver> (duh)
