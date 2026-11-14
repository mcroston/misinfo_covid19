# COVID-19 vaccine misinformation versus fact-checks on Twitter: the graphene oxide case

Code, data, and conference materials from a study of how a COVID-19 vaccine conspiracy theory (that the vaccines contain graphene oxide) and the fact-checks debunking it spread on Twitter. The study compares the retweet networks of misinformation and fact-check URLs using social network analysis.

**Authors:** Merriah A. Croston and Jenine K. Harris, Washington University in St. Louis.

## Outputs

- Croston M., Harris J. *The spread of fact-checks and the myths they debunk on Twitter: A case study of the graphene oxide myth during the COVID-19 pandemic.* JMIR Preprints, 2025; 73538. https://preprints.jmir.org/preprint/73538
- Croston M., Harris J. (2022, July). *Misinformation versus fact-checks: Comparative analysis of COVID-19 vaccine-related retweet networks.* INSNA 42nd Sunbelt Conference, Cairns, Australia. [Slides](SUBMIT_croston_sunbelt_conference_2022.pdf)
- Croston M., Harris J. (2022, June). *What's in a jab?: The spread of COVID-19 vaccine misinformation versus fact-checks on Twitter.* useR! Conference. [Poster](croston_useR_poster_2022.pdf)

## Data

Tweets containing a set of fact-check URLs, and the misinformation URLs those fact-checks addressed, were retrieved from the Twitter API on March 23, 2022. Tweets were posted between June 1 and November 30, 2021.

| File | Contents |
| --- | --- |
| `graphene_covid_misinfo_urls.csv` | The 69 URLs used to identify tweets, each labeled `fact check` or `misinformation`. |
| `graphene_covid_misinfo_tweetids.csv` | IDs of the 13,566 tweets retrieved. |

Tweet content is not shared, in line with X's developer terms. Tweets can be rehydrated from the IDs where API access allows; tweets since deleted or made private will not be returned.

## Citation

If you use these data, please cite the preprint above.
