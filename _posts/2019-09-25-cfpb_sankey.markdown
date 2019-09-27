---
layout: post
title:  CFPB Sankey
date:   2019-09-25 10:32:20 +0300
description: Analysis and visualizations of Consumer Financial Protection Bureau complaint data
img: posts/2019-09-25-cfpb_sankey/sankey_cover.png
tags: [Politics, CFPB]
---

The Consumer Financial Protection Bureau (CFPB) has a dataset of all 1.3 million complaints it's received since its inception in 2011.
These complaints document instances of corporate malfeasance against consumers, including improper threats made by debt collectors, incorrect information on credit reports, and simply people struggling to pay their mortgages.
You can download the dataset [here][dataset].

I made a few interactive visualizations of the data.
The first is a series of Sankey diagrams of the most complained-about companies by sector.

{% include interactive/cfpb_sankey_dashboard.html %}

[dataset]: https://www.consumerfinance.gov/data-research/consumer-complaints/search/?from=0&searchField=all&searchText=&size=25&sort=created_date_desc