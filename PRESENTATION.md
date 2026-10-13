# 2–3 minute talk script

**Slide/figure 1: biplot (`figures/05_biplot.png`), ~30 s**
"We used 10 UN indicators for 191 countries. We dropped the education variables (63% missing), filled small gaps with regional medians, log-transformed GDP and standardised everything. PCA shows one dominant axis: PC1 alone explains 65% of the variance, and health, fertility, literacy and income all load on it together. So development is a bundle. PC2, 12%, is almost entirely women's economic activity. Four components keep 91% of the information, so we clustered on those."

**Figure 2: choosing k (`figures/07_choosing_k.png`), ~40 s**
"We started with k = 2. To be honest, the silhouette score is highest at 2. But look at what k = 2 actually is (`figures/09_pca_k2_vs_k4.png`, left): 58 high-mortality countries against 133 others. The 'developed' group includes Norway *and* Tajikistan, a 350× income range. It cuts off a tail; it doesn't find two worlds. The elbow is at 4–5, R² rises from 55% to 71% going from 2 to 4 clusters, and stability holds up to 4 then drops. So we chose four."

**Figure 3: four worlds (`figures/11_four_worlds_representatives.png`), ~60 s**
"One country per cluster:
- **Nigeria**: about 6 children per woman, infant mortality around 80, under $2 a day. Mostly sub-Saharan Africa, but Haiti, Nepal and Bangladesh are here too.
- **India**: the transition. Fertility around 3, high infant mortality, and low female literacy and participation. Surprise: Saudi Arabia is here, rich but with C2's demographics.
- **Mexico**: the big middle. Fertility near replacement and mid incomes, together with China, Brazil and Russia. Surprise: Qatar and China share a cluster.
- **Portugal**: low fertility, long lives, high income. Surprise: Cuba is here because its health indicators match the rich world."

**Close, ~20 s**
"So the data say the world isn't two groups. It's a continuum where most countries sit in the middle, and four levels describe it well, just as Rosling argues in *Factfulness*. One caveat: on a continuum, exactly where you draw the lines depends on the method."
