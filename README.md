
## Project: Navigating the multiverse of technological innovation


## What is the challenge?

Multi billion dollar investments are channelled to a myriad of tech companies every year.

Global venture investment totaled $363 billion in 2021; source: Crunchbase [1].

These companies are hoping to create innovation breakthroughs that can benefit society as well as being commercially viable. 

The astronomical level of investment and the unpredictability for business growth, makes innovation a very risky and costly endeavour.  It has been reported that up to 75 percent of venture-backed startups fail and never return cash to their investors; source: Wall Street Journal [2].

The rate of failure and financial losses has been managed using a 'Blockbuster' and 'Unicorn' paradigm. This paradigm is characterised by a small fraction of startups succeeding at climbing the growth ladder, while the majority of companies fail at realising market impact and financial gains. 
 
Large investment groups and governments trying to boost technological innovation urgently need better decision-making tools to assess potential opportunities and risks, while trying to ensure a more level playing field that supports economic growth more widely and evenly. Peripheral regions tend to be at a disadvantage compared to companies located within large metropolitan areas for example.

Current commercial data-rich services provide useful but still limited uni-dimensional snapshots of these complex technological innovation networks.

The current metaverse graph analytical approach, takes an important step further by navigating through the above complexity, using multiple data sources, enabled by user-friendly visual interfaces, that are also powered by graph, machine learning and NLP algorithms. 

## Project Story

This project navigates through technology landscapes using multiple data sources to unveil a complex multiverse of network structures and dynamics.

To illustrate the multiverse approach, this project uses multiple data sources, including company, equity investment, acquisitions and patent data.
For instance, tech startups operating in a technology field (e.g., AI + Health) may have specific patterns of investment flows and relationships with business angel groups and venture capital firms. In contrast, patent data could uncover other forms of relationships in terms of R&D innovation and collaboration. 

## Inspiration

Due to its huge potential to understand complex patterns of innovation, I have been intrigued by how to effectively apply multi-layer graph theory and big data analysis for many years. 

A co-authored research paper spells out the underlying vision. https://ssrn.com/abstract=3964723

In a nutshell, you can think of ‘Minority Report’ style metaverse analysis and prediction. Multi-layer graphs can be used to analyse the behaviour and performance of  complex business networks.

Early graph analysis libraries, however,  have several limitations and are difficult to use compared to next generation databases such as TigerGraph. 

I got hooked into TigerGraph as it offers cost-effective development and deployment into production, besides an increasing range of advanced analytical features, and integration to a growing ecosystem of allied technologies.

## What it does

This project navigates through technological innovation landscapes using multiple data sources to unveil a complex multiverse of network structures and dynamics.

For instance, startups operating in a technology field, such as AI and Health, may have specific patterns of investment flows and relationships with business angel groups and venture capital firms. In contrast, patent data can also signal additional value creation and can als uncover other forms of relationships in terms of R&D innovation and collaboration. 


## How I built it

To illustrate the multiverse approach, this project uses multiple data sources, including company, equity investment and patent data. More specifically, the data includes:

- Company information such as company name,  headquarters’ location and founders/ directors; 
- The investment secured and the timing of those investments; 
- Company acquisitions; and 
- Their products and IP protection activities through patents. 

The above data was acquired for a single sector, namely health technology. 

The data was then ingested into TigerGraph, using a bespoke data schema designed to model the main entities in the sample data, i.e., organization, funding, acquirer, patent.

Graph queries using GSQL were written to retrieve specific patterns from the data, including:
Companies with investment from the time period available in the sample dataset..
Patent applications and approved patents for the specified period.

More specific queries included:
Companies which had approved patents AND investment in the specified period.

Machine learning and graph algorithms were used to analyse structural network properties, including:
Co-occurence analysis to determine the cross-over between (a) investment and (b) patents.
Community detection algorithm using both (a) investment and (b) patent.
  

## Challenges I ran into

A challenge that affects any disruptive analytics project is accessing the right type of data, as it can be costly to acquire if not readily publicly available in a combined format.

Given the limited financial resources to purchase separate commercial databases at this proof-of-concept stage, a conscious decision was to procure a minimum sample dataset that spanned the various domains of interest of the multiverse of tech startups. That is, not all startups that raise investment apply for a patent, and vice versa.  

Patent data was procured directly from national patent offices such as USPTO, that offers downloading patent data in bulk or using their search dashboard.

 
 ## What's next for Navigating the multiverse of technological innovation

I would like to open up the project, inviting the open data community, to procure additional sources of data covering a much larger number of companies, and extend the initial analysis and visualizations to be able to paint a more complete and reliable picture of technological innovation networks. 

For instance, patent citations from previous inventions can be considered a proxy measure of technology 'closenesses' (i.e., centrality and neighbour analysis), as well as potentially competitive intentions (e.g., wanting to concentrate competition in one narrow tech area).



## Sources:
- [1] https://news.crunchbase.com/news/global-vc-funding-unicorns-2021-monthly-recap/
and  https://news.crunchbase.com/news/europe-vc-funding-unicorns-2021-monthly-recap/
- [2] https://www.wsj.com/articles/risk-rewards-of-angel-investing-11635957307?reflink=desktopwebshare_permalink  

  
