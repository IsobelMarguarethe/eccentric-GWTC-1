# Eccentric GWTC-1
We construct eccentricity posteriors for GWTC-1 events using `SEOBNRE` ([Zhoujian Cao and Wen-Biao Han, 2017](https://journals.aps.org/prd/abstract/10.1103/PhysRevD.96.044028)) waveforms with spin and eccentricity. We use them to reweight PE ([Ethan Payne et al, 2019](https://arxiv.org/abs/1905.05477)) performed with non-eccentric IMRPhenomD ([Sebastian Khan et al, 2015](https://arxiv.org/abs/1508.07253)) waveforms. We construct eccentricity-marginalised likelihoods to use in the weights calculation, and use the full cumulative likelihood to reconstruct eccentricity posteriors.

## Reweighting efficiency

Calculated following [Kish 1995](https://books.google.com.au/books/about/Survey_sampling.html?id=xiZmAAAAIAAJ&redir_esc=y), the reweighting efficiency determines how well-sampled the posteriors are after reweighting.

|   *Event*  | *reweighting efficiency* |
|:----------:|:------------------------:|
| *GW150914* |           0.05           |
| *GW151012* |           0.73           |
| *GW151226* |           0.30           |
| *GW170104* |           0.39           |
| *GW170608* |           0.68           |
| *GW170729* |           0.56           |
| *GW170809* |           0.39           |
| *GW170814* |           0.01           |
| *GW170818* |           0.39           |
| *GW170823* |           0.61           |
|------------|--------------------------|
| *Injection* |           0.20           |

