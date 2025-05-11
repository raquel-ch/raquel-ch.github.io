---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
title: "main"
permalink: /
---
In recent years, tourism in Spain has surged bringing economic benefits, but also raising critical questions about housing, regulation, and urban life. Cities like Barcelona, Madrid, and Palma de Mallorca have seen an explosion of short-term tourist rentals, especially through platforms like Airbnb. But **how many of these apartments are actually legal**? And **what does this mean for the people who live there**?

In this project, we combine official government records on registered tourist accommodations with Airbnb listing data to uncover the gap between regulation and reality. We also explore how this growth may be influencing housing prices, and whether some Airbnb hosts operate at a scale that resembles a commercial business, rather than casual home-sharing.

Through maps, charts, and analysis, we aim to shed light on how tourism and digital platforms are reshaping urban housing and to ask: **Who are cities really for?**

In the sections below, you’ll be able to dive deeper into the key questions around short-term rentals in Spain and explore the data visualizations that shed light on these issues:
- [**How big is the problem?**](#how-big-is-the-problem)  
  Explore the scale of illegal rentals and their distribution across cities.
- [**Have rental prices been affected?**](#have-rental-prices-been-affected)  
  See how short-term rentals may be influencing local housing markets.
- [**Can we call this a business?**](#can-we-call-this-a-business)  
  Investigate the number of listings per host and whether many hosts are operating at a commercial scale.

Go to each section to uncover the insights and get a clearer picture of how tourism is reshaping urban housing and what that means for local residents.

# How big is the problem?

To get a sense of how many tourist apartments might be flying under the radar, we compared official government records with Airbnb listings, using data from Inside Airbnb. Across Barcelona, Madrid, and Mallorca, we found over 30,000 registered apartments. However, Airbnb shows almost 8,000 more listings. This gap points to a potentially large number of rentals operating without a license.

To better understand where these unregistered apartments are located, we visualized the Airbnb data on interactive maps for each city. <span style="color:green">**Green**</span> dots represent listings that matched an official license, while <span style="color:red">**red**</span> dots show those without one. Although the maps are based only on the Airbnb data, since it includes the highest number of entries, they still offer a clear picture of how widespread the issue might be.

<figure style="text-align: center;">
  <iframe src="/plots/bcn_map.html" width="100%" height="600px" frameborder="0"></iframe>
  <figcaption style="margin-top: 8px; font-style: italic; color: #555;">
    Figure 1: Interactive map showing licensed and unlicensed Airbnb listings in Barcelona.
  </figcaption>
</figure>


<figure style="text-align: center;">
  <iframe src="/plots/mad_map.html" width="100%" height="600px" frameborder="0"></iframe>
  <figcaption style="margin-top: 8px; font-style: italic; color: #555;">
    Figure 2: Interactive map showing licensed and unlicensed Airbnb listings in Madrid.
  </figcaption>
</figure>


<figure style="text-align: center;">
  <iframe src="/plots/mall_map.html" width="100%" height="600px" frameborder="0"></iframe>
  <figcaption style="margin-top: 8px; font-style: italic; color: #555;">
    Figure 3: Interactive map showing licensed and unlicensed Airbnb listings in Mallorca.
  </figcaption>
</figure>



In Barcelona and Mallorca, around 75% of Airbnb listings are licensed, reflecting strict local regulations and active enforcement. For example, in Mallorca, the local government is actively combating illegal rentals, and in Barcelona, the city has introduced laws to restrict tourist apartments by 2029. Moreover, in Barcelona the government has created a webpage to help detect unlicensed tourist accommodations. You can visit the page [here](https://meet.barcelona.cat/habitatgesturistics/es). In contrast, only about 15% of listings in Madrid are licensed. This discrepancy likely stems from weaker enforcement, as Madrid has only recently introduced stricter measures, such as suspending new license applications and reinforcing inspection efforts. The absence of similar comprehensive controls in Madrid has led to many unlicensed apartments continuing to operate [[1]](https://www.atlanticohoy.com/politica/regulacion-viviendas-turisticas-diferencias-entre-comunidades-autonomas_1533956_102.html).

# Have rental prices been affected?

With the sharp rise in short-term rentals, many locals worry that platforms like Airbnb are driving up housing costs. To explore this, we looked at how the price per square meter has changed over time in relation to the number of active Airbnb listings in each city. By comparing trends across Barcelona, Madrid, and Mallorca, we aim to understand whether there’s a visible connection between the growth of tourist apartments and the increase in rental prices.

<figure style="text-align: center;">
  <iframe src="/plots/prices_graph.html" width="100%" height="600px" frameborder="0"></iframe>
  <figcaption style="margin-top: 8px; font-style: italic; color: #555;">
    Figure 4: Interactive map showing the evolution of rental prices and Airbnb listings in Barcelona, Madrid and Mallorca
  </figcaption>
</figure>

# Can we call this a business?

As Airbnb listings continue to grow, a key question arises: Are we seeing casual hosts renting out a spare room, or is this becoming a full-fledged business? To investigate, we analyzed the number of properties owned by individual hosts across Barcelona, Madrid, and Palma de Mallorca. By identifying hosts with multiple listings, we can determine whether professional operators dominate the market, turning short-term rentals into a profitable business model.

The analysis of the number of listings per host reveals that, across all regions analyzed, the median number of listings per host is 3. This means that half of the hosts manage three or more properties, which is notably higher than what we initially expected, assuming that most hosts would rent out only one or two properties, as part of the typical “sharing economy” model.

This finding suggests that a significant portion of Airbnb activity is driven by professional or semi-professional hosts, rather than occasional or private individuals. The presence of hosts with even more than 10 listings (grouped as “11+”) further reinforces the idea that short-term rentals are often used as a commercial business model, rather than for temporary subletting or shared accommodation.

This has important implications when interpreting the platform’s local impact, particularly in urban areas where housing availability and affordability are pressing issues. It may also be relevant when considering regulation and licensing practices, as the platform’s user base may not align with the originally intended peer-to-peer nature of home sharing.

Additionally, the dominance of entire home/apartment listings across all host categories suggests that Airbnb is often used not just to share space, but to operate full rental units, reinforcing its role as a business model in many cases.

<figure style="text-align: center;">
  <iframe src="/plots/distribution_host_bcn.html" width="100%" height="600px" frameborder="0"></iframe>
  <figcaption style="margin-top: 8px; font-style: italic; color: #555;">
    Figure 5: Interactive map showing the distribution of hosts and room types in Barcelona
  </figcaption>
</figure>

<figure style="text-align: center;">
  <iframe src="/plots/distribution_host_mad.html" width="100%" height="600px" frameborder="0"></iframe>
  <figcaption style="margin-top: 8px; font-style: italic; color: #555;">
    Figure 5: Interactive map showing the distribution of hosts and room types in Madrid
  </figcaption>
</figure>

<figure style="text-align: center;">
  <iframe src="/plots/distribution_host_malla.html" width="100%" height="600px" frameborder="0"></iframe>
  <figcaption style="margin-top: 8px; font-style: italic; color: #555;">
    Figure 5: Interactive map showing the distribution of hosts and room types in Mallorca
  </figcaption>
</figure>