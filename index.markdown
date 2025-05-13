---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
title: "main"
permalink: /
---
In recent years, tourism in Spain has surged bringing economic benefits, but also raising critical questions about housing, regulation, and urban life. Cities like Barcelona and Madrid, as well as regions such as the island of Mallorca, have seen an explosion of short-term tourist rentals, especially through platforms like Airbnb. But **how many of these apartments are actually legal**? And **what does this mean for the people who live there**?

In this project, we combine public government records on registered tourist accommodations with Airbnb listing data to uncover the gap between regulation and reality. We also explore how this growth may be influencing housing prices, and whether some Airbnb hosts operate at a scale that resembles a commercial business, rather than casual home-sharing.

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

To get a sense of how many tourist apartments might be flying under the radar, we compared official government records with Airbnb listings, using data from Inside Airbnb. Across Barcelona, Madrid, and the island of Mallorca, we found over 30,000 registered apartments. However, Airbnb shows almost 8,000 more listings. This gap points to a potentially large number of rentals operating without a license.

To better understand where these unregistered apartments are located, we visualized the Airbnb data on interactive maps for each city. <span style="color:green">**Green**</span> dots represent listings that matched an official license, while <span style="color:red">**red**</span> dots show those without one. Although the maps are based only on the Airbnb data, since it includes the highest number of entries, they still offer a clear picture of how widespread the issue might be.

<figure style="text-align: center;">
  <iframe src="/plots/bcn_map.html" width="100%" height="600px" frameborder="0"></iframe>
  <figcaption style="margin-top: 8px; margin-bottom: 20px; font-style: italic; color: #555;">
    Figure 1: Interactive map showing licensed and unlicensed Airbnb listings in Barcelona.
  </figcaption>
</figure>


<figure style="text-align: center;">
  <iframe src="/plots/mad_map.html" width="100%" height="600px" frameborder="0"></iframe>
  <figcaption style="margin-top: 8px; margin-bottom: 20px;font-style: italic; color: #555;">
    Figure 2: Interactive map showing licensed and unlicensed Airbnb listings in Madrid.
  </figcaption>
</figure>


<figure style="text-align: center;">
  <iframe src="/plots/mall_map.html" width="100%" height="600px" frameborder="0"></iframe>
  <figcaption style="margin-top: 8px; margin-bottom: 10px; margin-bottom: 20px; font-style: italic; color: #555;">
    Figure 3: Interactive map showing licensed and unlicensed Airbnb listings in Mallorca.
  </figcaption>
</figure>


In Barcelona and Mallorca, approximately 75% of Airbnb listings are licensed, reflecting the effects of stricter regulations and active enforcement. For example, the Mallorcan government has launched dedicated inspections to combat illegal rentals [[1]](https://www.economiademallorca.com/articulo/turismo-y-hosteleria/mas-mano-dura-oferta-turistica-ilegal-como-via-combatir-saturacion/20250411132246106313.html), and Barcelona has introduced laws to restrict tourist apartments by 2029 [[2]](https://forbes.es/turismo/485697/barcelona-preve-reforzar-inspecciones-para-combatir-los-pisos-turisticos-ilegales-a-partir-de-2029/). Moreover, in Barcelona, the government has created a webpage to help detect unlicensed tourist accommodations. You can visit the page [here](https://meet.barcelona.cat/habitatgesturistics/es).

Madrid, in contrast, shows a starkly different picture: only around 15% of listings are licensed. This low rate is likely due to historically weak regulation and enforcement mechanisms. Although the city has recently suspended new license applications and begun reinforcing inspections, many unlicensed listings continue to operate without consequence [[3]](https://www.atlanticohoy.com/politica/regulacion-viviendas-turisticas-diferencias-entre-comunidades-autonomas_1533956_102.html).

Additionally, when examining the location of unlicensed listings, it can be seen that they are not concentrated solely in central or tourist-heavy neighborhoods, but rather scattered across the entire urban area. This suggests that the issue of illegal rentals is widespread and not confined to traditional tourist zones, making detection and enforcement even more challenging for local authorities.

This spatial and regulatory comparison underscores that the issue is not just about the number of listings, but also about how differently cities choose to regulate them, and how effective those measures are in practice. Unlicensed rentals, which continue to operate despite varying enforcement efforts, contribute to housing shortages, inflate rents, and often sidestep crucial safety and tax requirements. Their persistence underscores the urgent need for stricter and more consistent policies to protect local communities and ensure fair housing access.


# Have rental prices been affected?

With the sharp rise in short-term rentals, many locals worry that platforms like Airbnb are driving up housing costs. To explore this, we looked at how the price per square meter has changed over time in relation to the number of active Airbnb listings in each city. By comparing trends across Barcelona, Madrid, and Mallorca, we aim to understand whether there’s a visible connection between the growth of tourist apartments and the increase in rental prices.

<figure style="display: flex; flex-direction: column; align-items: center;">
  <div style="transform: scale(0.8); transform-origin: top center;">
    <iframe 
      src="/plots/prices_graph.html" 
      style="width: 900px; height: 500px; border: none;">
    </iframe>
  </div>
  <figcaption style="margin-top: -100px; margin-bottom: 10px; font-style: italic; color: #555; text-align: center; max-width: 900px;">
    Figure 4: Interactive plot showing the evolution of rental prices (€/$m²$) and Airbnb listings in Barcelona, Madrid and Mallorca
  </figcaption>
</figure>


As observed across all three locations, both the price per square meter and the number of active Airbnb listings have increased over time, although housing prices have experienced some fluctuations. This parallel growth suggests a potential link between the expansion of tourist-oriented rentals and the upward pressure on local housing markets.

While our analysis cannot establish direct causation, the temporal alignment between rising prices and Airbnb activity reinforces findings from previous studies. For example, a 2023 report by the Bank of Spain highlighted that short-term rentals can reduce the availability of housing stock for long-term residents, particularly in high-demand urban areas, thereby contributing to price inflation [[4]](https://www.bde.es/f/webbe/SES/Secciones/Publicaciones/PublicacionesAnuales/InformesAnuales/23/Files/InfAnual_2023_Cap4_En.pdf). Supporting this observation, a 2020 study by researchers from the Universitat de Barcelona assessed the impact of Airbnb on housing rents and prices in Barcelona. The study found that, on average, Airbnb activity led to a 1.9% increase in rents and a 4.6% rise in home prices. In neighborhoods with even more Airbnb activity, the effect was stronger, rents went up by about 7%, and the cost of buying a home rose by as much as 17% [[5]](https://www.sciencedirect.com/science/article/pii/S0094119020300498?via%3Dihub). 

These findings show that short-term rentals like those on Airbnb can have a real impact on housing costs. While tourism brings in money and supports local businesses, it can also make it harder for people to find affordable places to live, especially in popular cities. This puts pressure on governments to find a balance between welcoming tourists and protecting housing for residents.


# Can we call this a business?

As we’ve seen, short-term rentals can shape housing markets in significant ways. But to fully understand their impact, we also need to look at who is behind these listings. Are they mostly individuals occasionally renting out a spare room? Or is this turning into something much bigger, like a professional business?

To dig into this, we analyzed the number of properties listed by each host in Barcelona, Madrid, and Mallorca. By identifying how many listings each person manages, we can get a clearer picture of whether short-term rentals are still part of the “sharing economy” or if they’ve become a profitable business for larger players.

<figure style="display: flex; flex-direction: column; align-items: center;">
  <div style="transform: scale(0.8); transform-origin: top center;">
    <iframe 
      src="/plots/host_bcn.html" 
      style="width: 900px; height: 500px; border: none;">
    </iframe>
  </div>
  <figcaption style="margin-top: -100px; margin-bottom: 20px; font-style: italic; color: #555; text-align: center; max-width: 900px;">
    Figure 5: Interactive plot showing the distribution of hosts and room types in Barcelona
  </figcaption>
</figure>

<figure style="display: flex; flex-direction: column; align-items: center;">
  <div style="transform: scale(0.8); transform-origin: top center;">
    <iframe 
      src="/plots/host_mad.html" 
      style="width: 900px; height: 500px; border: none;">
    </iframe>
  </div>
  <figcaption style="margin-top: -100px; margin-bottom: 20px; font-style: italic; color: #555; text-align: center; max-width: 900px;">
    Figure 6: Interactive plot showing the distribution of hosts and room types in Madrid
  </figcaption>
</figure>

<figure style="display: flex; flex-direction: column; align-items: center;">
  <div style="transform: scale(0.8); transform-origin: top center;">
    <iframe 
      src="/plots/host_mall.html" 
      style="width: 900px; height: 500px; border: none;">
    </iframe>
  </div>
  <figcaption style="margin-top: -100px; margin-bottom: 20px; font-style: italic; color: #555; text-align: center; max-width: 900px;">
    Figure 7: Interactive plot showing the distribution of hosts and room types in Mallorca
  </figcaption>
</figure>


The analysis of the number of listings per host reveals that, across all regions analyzed, the median number of listings per host is 3. This means that half of the hosts manage three or more properties, which is notably higher than what we initially expected, assuming that most hosts would rent out only one or two properties, as part of the typical “sharing economy” model.

This finding suggests that a significant portion of Airbnb activity is driven by professional or semi-professional hosts, rather than occasional or private individuals. The presence of hosts with even more than 10 listings (grouped as “11+”) further reinforces the idea that short-term rentals are often used as a commercial business model, rather than for temporary subletting or shared accommodation.

This has important implications when interpreting the platform’s local impact, particularly in urban areas where housing availability and affordability are pressing issues. It may also be relevant when considering regulation and licensing practices, as the platform’s user base may not align with the originally intended peer-to-peer nature of home sharing [[6]](https://en.wikipedia.org/wiki/Airbnb).

Additionally, the dominance of entire home/apartment listings across all host categories suggests that Airbnb is often used not just to share space, but to operate full rental units, reinforcing its role as a business model in many cases.


# Summary of Findings

Spain’s tourism boom has brought economic growth, but also growing tension around housing. In this project, we examine how platforms like Airbnb are transforming the Spanish cities of Barcelona and Madrid, and the island of Mallorca.

We uncover a significant number of unlicensed rentals, especially in Madrid, and show that these listings are spread throughout the cities, not just in tourist hotspots. At the same time, we observe a strong rise in both housing prices and Airbnb activity since 2022, supported by research linking short-term rentals to increased rents, particularly in areas with many listings. The data also reveals that many Airbnb hosts manage multiple properties, suggesting the platform is often used for business purposes rather than casual home-sharing.

Together, these findings show that platforms like Airbnb are not just changing how people travel, they’re also affecting who can afford to live in cities, and how urban spaces are used. As Spain continues to debate housing policy and tourism regulation, **this data helps clarify what’s really at stake:** not just housing availability, but **the very identity of our cities.**
