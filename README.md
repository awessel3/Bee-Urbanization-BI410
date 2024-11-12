Creating our Readme file

I. Literature review
We expect the literature review will be around 5 well-cited paragraphs that do the following:

Introduce the problem and explain why --
Set the stage for the problem
Put the concept and question into context
Lots of big-picture citations (such as reviews) in the first paragraph

Past work and data available ---
Who has addressed this problem (perhaps with a different dataset/region), and what did they do it?
What are the data available to address this problem (in addition to the OBA dataset)?

Bumble bees (Bombus spp.) and other bee species play an important ecological role as pollinators for various wildflowers and agricultural crops (Ahrné et al. 2009; McCabe et al. 2022). Despite their ecological importance, pollinators face numerous threats from habitat loss, pesticide exposure, climate change, and disease, with many bee populations declining worldwide (Goulson et al. 2008). Habitat loss and fragmentation caused by urbanization emerges as a growing concern due to its rapid expansion and transformation of landscapes that were once natural habitats into fragmented urban environments. Urbanization can have a large effect on Bombus spp. flower visitation rates and pollination success through changes in foraging behavior (Glaum et al. 2017; Harrison & Winfree 2015). Urban heat islands, or the increased temperatures often observed in cities due to concrete and reduced green spaces, further complicate the challenges faced by pollinators (Harrison & Winfree 2015). Together, these pressures can lead to declines in Oregon bee populations, leading to cascading effects impacting the numerous ecosystem services offered. Understanding how urbanization impacts emergence patterns of Bombus spp. is crucial, as these factors are closely tied to their ability to effectively pollinate and maintain stable populations. 

Recent research has found that climate change, often resulting from urbanization, is altering phenology, with spring events generally occurring earlier (Stemkovski et al. 2020). For Bombus spp., increased (spring) temperatures have been shown to directly lead to advanced phenology, prompting earlier emergence and activity periods (Prestele et al. 2021). Harrison & Winfree (2015) observed that urban habitats support a greater abundance of late-season bees compared to forest habitats, likely due to the presence of late-blooming plants. They also suggest that urban warming may act as an "ecological filter," reducing species diversity and resulting in a more homogenized bee community in cities. Similarly, Blasi et al. (2023) found that over the past 20 years, a citizen-science dataset has shown that Bombus spp. emergence across Sweden has advanced significantly, though responses varied based on species traits. As in Harrison & Winfree’s findings, warmer temperatures substantially advanced the flight period for early-emerging species, while late-emerging species exhibited no consistent trend. This variability in response among Bombus spp. may contribute to shifts in community composition, favoring species that can better synchronize their life cycles with the altered urban floral availability. Little is known about how these phenological changes impact pollination success across diverse urban ecosystems, especially in areas like Oregon where agricultural productivity and biodiversity heavily depend on stable bee populations.

Understanding these emergence patterns and phenological shifts is crucial for pollinator diversity conservation efforts. Using the Oregon Bee Atlas (OBA), census population block data, and monthly temperature reading from the PRISM group, we are able to develop a more comprehensive analysis of how urbanization and temperature variability affect Bombus spp. Li et al. (2020) demonstrated that human population density can serve as a reliable indicator of urbanization, allowing us to use census data as a proxy for assessing the intensity of urban development and its impacts on bee populations. By combining monthly temperature data and population density, we are able to assess the response of Bombus spp. Across various levels of urbanization, allowing us to identify species-specific emergence patterns and population trends among different bee species. 

Purpose of the study--
Further refine your approach (e.g., what data will you combine, how will you address the question)
Justify why this is needed now (e.g., visualization to test a new dimension of the question or better convey an old one)

Hypotheses/questions --
List these clearly and in a logical order
Make hypotheses directionally using predictions (e.g. “I predict urbanization will reduce plant diversity” rather than “I predict urbanization will change plant diversity”)




References: 
Ahrné, K., Bengtsson, J., & Elmqvist, T. (2009). Bumble Bees (Bombus spp) along a Gradient of Increasing Urbanization. PLoS ONE, 4(5), e5574. https://doi.org/10.1371/journal.pone.0005574

McCabe, L. M., Aslan, C. E., & Cobb, N. S. (2022). Decreased bee emergence along an elevation gradient: Implications for climate change revealed by a transplant experiment. Ecology, 103(2), e03598. https://doi.org/10.1002/ecy.3598

Harrison, T., & Winfree, R. (2015). Urban drivers of plant‐pollinator interactions. Functional Ecology, 29(7), 879–888. https://doi.org/10.1111/1365-2435.12486

Glaum, P., Simao, M.-C., Vaidya, C., Fitch, G., & Iulinao, B. (2017). Big city Bombus : using natural history and land-use history to find significant environmental drivers in bumble-bee declines in urban development. Royal Society Open Science, 4(5), 170156. https://doi.org/10.1098/rsos.170156

Goulson, D., Lye, G. C., & Darvill, B. (2008). Decline and Conservation of Bumble Bees. Annual Review of Entomology, 53(1), 191–208. https://doi.org/10.1146/annurev.ento.53.103106.093454

Stemkovski, M., Pearse, W. D., Griffin, S. R., Pardee, G. L., Gibbs, J., Griswold, T., Neff, J. L., Oram, R., Rightmyer, M. G., Sheffield, C. S., Wright, K., Inouye, B. D., Inouye, D. W., & Irwin, R. E. (2020). Bee phenology is predicted by climatic variation and functional traits. Ecology Letters, 23(11), 1589–1598. https://doi.org/10.1111/ele.13583

Blasi, M., Carrié, R., Fägerström, C., Svensson, E., & Persson, A. S. (2023). Historical and citizen-reported data show shifts in bumblebee phenology over the last century in Sweden. Biodiversity and Conservation, 32(5), 1523–1547. https://doi.org/10.1007/s10531-023-02563-5

Prestele, R., Brown, C., Polce, C., Maes, J., & Whitehorn, P. (2021). Large variability in response to projected climate and land‐use changes among European bumblebee species. Global Change Biology, 27(19), 4530–4545. https://doi.org/10.1111/gcb.15780

Li, D., Barve, N., Brenskelle, L., Earl, K., Barve, V., Belitz, M. W., Doby, J., Hantak, M. M., Oswald, J. A., Stucky, B. J., Walters, M., & Guralnick, R. P. (2021). Climate, urbanization, and species traits interactively drive flowering duration. Global Change Biology, 27(4), 892–903. https://doi.org/10.1111/gcb.15461




II. Dataset identification
Please identify the additional datasets you will be using to address your question. * Provide the data source (including web url) * Describe sufficient metadata to convey who collected the data, how it was collected, and what each column contains.

III. Workflow plan
In pros, please describe the workflow you will use tidy your raw data, manipulate and summarize it in relevant ways, test you hypothesis, and visualize it.The goal here is to develop a logic to your workflow before you code. * Include any needed cleaning steps (e.g., “remove non-species such as ‘fly’ from the species column”) * Include any aggregation steps (e.g., “count the number of entries by region and year to calculate species richness”). * Include descriptions of any functions/for loops you will write.
* Include a description the the statistical test you will use, and how you will apply it programatically (i.e., I will simulate the null hypothesis by shuffling the labels…“)

IV. Partner contributions
Each person will turn in a separate document, though the above content will be the same. Here, summarize how each partner contributed. Ex: "We met and discussed the workflow plan together and wrote it together. We both made an annotated bibliography of the available studies, and then I summarized them. My partner reviewed what I wrote and edited it. My partner drafted the purpose of the study, and I gave edits."
