---

layout: page
title: Housing 

---
California recently passed fifteen bills addressing the state’s housing crisis. This is a good first step toward improving access to housing for millions of Californians, but the housing crisis will not be solved in one legislative term. The Policy Club analyzed key parts of the housing package and produced estimates on what Californians can expect from these bills, as well as recommended additional steps to keep the momentum moving forward. 

**Policy Club analysis on housing bills:**

<ul>
    {% for post in site.categories.housing %}
    	{% if post.url %}
	      <li>
					<a class="post-link" href="{{ post.url | relative_url }}">{{ post.title | escape }}</a>
					{% assign date_format = site.minima.date_format | default: "%b %-d, %Y" %}
        	<span class="post-meta">| Posted {{ post.date | date: date_format }}</span>
	      </li>
      {% endif %}
    {% endfor %}
  </ul>

**Recommendations**

1. We encourage the development of a standardized rent reporting registry with the goal of developing real-time costs of housing in every zip code in California.

2. We recommend standardized data collection of new construction and regular reporting of revenue collected and expenditures from all Enhanced Infrastructure Financing Districts, as well as for every county in California.

3. We support the free and open sharing of public parcel files so that communities can determine the boundaries of an Enhanced Infrastructure Financing District.

4. We recommend the development of a consolidated database of all zoning areas by zip code in California.

5. We encourage new legislation to remove parking minimums for affordable housing through incentives or changes in existing law.

6. We request that all required reporting of housing production, changes in zoning, or other related information or data be made available online in a machine-readable format. 

**Related Links**

[http://sd11.senate.ca.gov/sites/sd11.senate.ca.gov/files/SB%2035%20Fact%20Sheet_1.pdf](http://sd11.senate.ca.gov/sites/sd11.senate.ca.gov/files/SB%2035%20Fact%20Sheet_1.pdf)

[https://abag.ca.gov/planning/housing/datasets.html](https://abag.ca.gov/planning/housing/datasets.html)

[https://abag.ca.gov/planning/housingneeds/pdfs/RHNAProgress_with_deed_restricted_units-1.25.2017.pdf](https://abag.ca.gov/planning/housingneeds/pdfs/RHNAProgress_with_deed_restricted_units-1.25.2017.pdf)

