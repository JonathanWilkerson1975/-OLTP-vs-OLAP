Why are OLAP queries easier to write and understand?

OLAP queries are simpler to work with because they use a star schema design that's naturally intuitive. In my experience with this lab, the OLAP queries felt much more straightforward—I could easily connect facts with clear dimension tables like DimCustomer and DimDate. On the other hand, the OLTP queries required complicated joins across multiple normalized tables and manual date calculations using YEAR() functions. The beauty of OLAP is that it opens up business reporting to more people across an organization, not just those with deep technical skills.

What risks would come from executives relying only on OLTP queries?

If executives depended solely on OLTP queries, they'd face several serious challenges. Query performance would slow down significantly with larger datasets, the complex SQL would be more error-prone, and historical analysis would be much more limited. The fundamental difference in schema design directly affects business reporting—while normalized OLTP schemas protect data integrity, they create hurdles for reporting. Meanwhile, OLAP's star schema prioritizes query speed and business intelligence, which ultimately supports quicker decisions and better trend spotting.
