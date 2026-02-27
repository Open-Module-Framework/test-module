# Introduction

In India, [climate change](https://www.learngala.com) is threatening farmers' livelihoods. As temperatures rise and wheat yields drop, they must decide how to adapt. Learn about potential strategies with regards to both rice and wheat cropping as well as irrigation, and explore a simulation model of agricultural yield in India to better understand the decision-making process. Keep in mind that what works in one situation might not work in another.

<aside data-type="consider">
When reading about adaptation strategies, weigh trade-offs: short-term yield versus long-term resilience, cost of new seeds or irrigation versus risk of crop failure, and local knowledge versus introduced practices.
</aside>

# An uncertain future for Indian farmers

For nearly 60 years, India has seen sustained growth in agricultural production. Thanks to remarkable advancements in crop genetics, fertilizer production, irrigation technologies, and pesticide treatments, many farmers have been able to increase production year after year. These gains have played a crucial role in meeting food demand for India’s growing population, which has surged from 0.4 to 1.4 billion since 1950. However, changes in climate threaten to stifle agricultural growth. As farmers in northern India prepare their fields for the sowing of the annual wheat crop, there remains little doubt that they will have to contend with the challenges posed by a changing climate.

From 1981 to 2009, wheat yields in India dropped by 5.2%, despite adaptation efforts. For many farmers, it is difficult to determine the best path forward. Maximum daily temperatures continue to rise, and with them, the stress on crops increases. How will farmers be able to keep up with increased food demand given these patterns? To make matters worse, losses in yield are likely to increase over the coming decades.

<aside data-type="warning">
Yield projections depend on emission scenarios and regional models. Always treat aggregate estimates (e.g. 6–23% by 2050) as indicative, not as guarantees for any single region.
</aside>

Estimates from the Indian Agricultural Research Institute predict anywhere from 6% to 23% yield declines by 2050 given current trends in warming.

[When the British established colonial rule in India](https://www.environmentandsociety.org/exhibitions/famines-india/changing-land-ownership-agricultural-and-economic-systems), they imposed a radically different approach to agriculture from what many of the traditional farmers had been practicing. Instead of farming for subsistence, the colonial government was concerned with farming for greater economic profit. Much of the land that had until then remained as forests, woodlands, or grasslands was cleared and plowed. Some estimates suggest that between 1880 and 1920, around six million hectares of land were converted into agricultural areas.This pattern continued after Indian independence and well into the 20th century. Estimates indicate that another 35 million hectares of land were converted to cultivated area by 1980. During this time, another set of sweeping changes took place in the Indian agricultural sector.

<aside data-type="reflect">
How might the shift from subsistence to profit-oriented agriculture have affected not only land use but also community structure and vulnerability to famine? Take a moment to reflect on this before moving to the next section.
</aside>

[Agriculture in India](https://www.youtube.com/watch?v=9Yk80UiegCw)

# Historical changes in the Indo-Gangetic Plains of India

The Indo-Gangetic Plains (IGP) are one of the main food-producing regions of India.
Encompassing the northern part of the Indian subcontinent, the IGP region includes the Indian states of Punjab, Haryana, Uttar Pradesh, Bihar, and West Bengal. The region is characterized by mostly flat topography and includes the adjacent fluvial plains of the Indus and Ganges river systems. To the north of the IGP are the Himalayan Mountains, which over millennia have deposited silt and alluvium onto the plains, forming a deep and nutrient-rich layer of highly productive soil. Prior to human agriculture, the area was largely covered by forest, but much of the forest has since been cleared in order to make use of the highly productive soil for agriculture. For many centuries the IGP has been occupied by humans who have cultivated the land.

Traditionally, farmers in the IGP practiced various forms of subsistence agriculture, growing mainly what they needed to survive. Farming practices changed, however, with the arrival of British colonial rule during the mid-nineteenth century.

<aside>
The term <em>Indo-Gangetic Plains</em> is used in both geography and agriculture to refer to the fertile belt stretching from Pakistan through northern India into Bangladesh. Different studies may use slightly different boundaries.
</aside>

<figure>
  <img src="assets/plains.jpg" alt="Map of the plains.">
  <figcaption>Map of the Indo-Gangetic Plains</figcaption>
</figure>

To embed a YouTube video, put the link as the only content of a paragraph (e.g. on its own line):

[Agriculture in India](https://www.youtube.com/watch?v=dQw4w9WgXcQ)

### Producers

Primary producers capture energy from the sun. The relationship between biomass and growth rate is often modeled with the logistic equation:

$$
\frac{dN}{dt} = rN\left(1 - \frac{N}{K}\right)
$$

where $N$ is population size, $r$ is the intrinsic growth rate, and $K$ is carrying capacity.

### Consumers and Decomposers

| Trophic level   | Role              | Example        |
|-----------------|-------------------|----------------|
| Primary consumer| Herbivore         | Rabbit         |
| Secondary consumer | Carnivore      | Fox            |
| Decomposer      | Recycles matter   | Earthworm      |

## Example Diagram

<figure>
  <img src="assets/diagram.svg" alt="Simplified food web showing producer, herbivore, and carnivore links.">
  <figcaption>Figure 1: Simplified food web.</figcaption>
</figure>

<aside data-type="note">
You can also use the class-based convention: <code>&lt;aside class="admonition note"&gt;</code> for compatibility with existing tooling. Renderers treat <code>data-type</code> as the primary convention (OMF-RP §6.2.3).
</aside>

<details>
  <summary>Why use a simplified food web?</summary>
  Simplified models help isolate key relationships (e.g. producer–consumer links) before adding complexity such as multiple species per level or detrital pathways.
</details>

Renderers MUST preserve this semantic structure (OMF-RP §5.1).

## Code and Task Lists

A minimal simulation in pseudocode:

```python
def growth_rate(N, r, K):
    return r * N * (1 - N / K)
```

Checklist for remixing this module:

- [ ] Update content and metadata
- [ ] Set `derived_from` to this module's canonical ID
- [ ] Recompute `content_hash` and `canonical_id`
- [ ] Declare any new external resources

## References

Energy flows through ecosystems [Odum 1971](https://doi.org/10.2307/1942251).

# References

- Odum, E. P. (1971). *Fundamentals of Ecology*. Saunders.
