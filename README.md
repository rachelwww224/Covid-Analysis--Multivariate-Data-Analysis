# Covid Analysis- Multivariate Data Analysis

**COVID-19 has quickly become a global health emergency with profound impacts on worldwide politics and economic activity. As such, a large number of multidisciplinary research efforts are underway to understand, treat, and prevent the spread of the disease. Using information from current research, it may be possible to cluster or categorize COVID-19 among other diseases. Specifically, we pose the following two-fold research question: Based on different epidemiological characteristics, how does COVID-19 cluster with or relate to other diseases, especially those known to cause severe human outbreaks? How consistent are those clusters across different cluster analyses?**

#### README FOR DISEASE DATA ####

The file disease_data.csv includes 181 diseases and 26 variables. Data for the first 180 listed diseases were scraped from the supplemental material of Hay et al  (2013). The last disease, Covid-19, includes data taken from a variety of reputable sources (Achaiah et al., 2020; Chowdhury and Oommen, 2020, CDC 2021). Due to the evolving nature of diseases, and particularly so for Covid-19, we do not guarantee that the information provided is accurate.

#### VARIABLES ####

Although there are 26 variables in the dataset, not all are unique. Below, we explain the variables by category:

(1) Variables 1-8 are binary indicators of transmission type, meaning how the disease is capable of spreading.

(2) Variables 9-11 are binary indicators of biological agent, meaning the type of the disease organism.

(3) Variables 12-16 are binary indicators of disease reservoir, meaning in what animals or species the disease is capable of surviving.

(4) Variables 17-18 correspond to incubation length. Variable 17 is the average incubation in days, while variable 18 is a binary variable indicating if the incubation length is between 0 and 7 days.

(5) Variable 19 is a binary variable indicating if a vaccine exists for the disease

(6) Variables 20-24 correspond to the maximum reproductive number (R0), meaning the expected number of cases caused by a single case in a population not previously exposed to the disease. Variable 20 is the raw estimate, while Variables 21-24 bin the R0 into four categories.

(7) Variables 25-26 correspond to the number of endemic countries. Variable 25 corresponds to the raw number, while Variable 26 is a binary variable indicating if the disease is endemic to all countries.


#### REFERENCES ####

Achaiah NC, Subbarajasetty SB, Shetty RM. R0 and Re of COVID-19: Can We Predict When the Pandemic Outbreak will be Contained?. Indian J Crit Care Med. 2020;24(11):1125-1127. doi:10.5005/jp-journals-10071-23649

Dhar Chowdhury S, Oommen AM. Epidemiology of COVID-19. Journal of Digestive Endoscopy. 2020;11(1):3-7. doi:10.1055/s-0040-1712187

Hay, SI, KE Battle, DM Pigott, DL Smith, CL Moyes, S Bhatt, JS Brownstein, N Collier, M F. Myers, DB George, et al., “Global mapping of infectious disease.” Philosophical Transactions of the Royal Society B: Biological Sciences, vol. 368, no. 1614, p. 20120250, 2013.

"Scientific Brief: SARS-CoV-2 Transmission." Centers for Disease Control and Prevention (2021). https://www.cdc.gov/coronavirus/2019-ncov/science/science-briefs/sars-cov-2-transmission.html
 
