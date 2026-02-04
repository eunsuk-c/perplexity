# Perplexity

This notebook contains the code used for the analysis presented in the paper:

**"Human writing and machine patterns: analyzing a decade of convergence"** by Eunsuk Chang

*Published in: Scientometrics*

The data used in this project is located in the `data` folder, which contains over 111K documents extracted from PubMed, Wikipedia, and Stack Exchange published in the 2014-2024 period.

\begin{table}[]
\begin{tabular}{lllllll}
Data source    & Year & Date of publication in each year (MM/DD) & Number of documents & Number of tokens & Average \# tokens per document & Average \# tokens per sentence \\
PubMed         & 2014 & 6/15, 12/15                              & 6715                & 1278807          & 190.44                         & 21.94                          \\
               & 2016 & 6/15, 12/15                              & 8905                & 1802933          & 202.46                         & 21.92                          \\
               & 2018 & 6/15, 12/15                              & 6886                & 1442383          & 209.47                         & 22.08                          \\
               & 2020 & 6/15, 12/15                              & 11875               & 2503297          & 210.8                          & 22.05                          \\
               & 2022 & 6/15, 12/15                              & 12957               & 2798766          & 216                            & 22.16                          \\
               & 2024 & 6/15, 12/15                              & 8672                & 1949696          & 224.83                         & 22.09                          \\
Wikipedia      & 2014 & 6/15, 6/30, 12/15, 12/30                 & 4000                & 1645471          & 411.37                         & 21.44                          \\
               & 2016 & 6/15, 6/30, 12/15, 12/30                 & 4000                & 1645482          & 411.37                         & 21.3                           \\
               & 2018 & 6/15, 6/30, 12/15, 12/30                 & 4000                & 1688916          & 422.23                         & 21.77                          \\
               & 2020 & 6/15, 6/30, 12/15, 12/30                 & 4000                & 1674229          & 418.56                         & 21.93                          \\
               & 2022 & 6/15, 6/30, 12/15, 12/30                 & 4000                & 1903732          & 475.93                         & 21.98                          \\
               & 2024 & 6/15, 6/30, 12/15, 12/30                 & 4000                & 1855208          & 463.8                          & 21.55                          \\
Stack Exchange & 2014 & 6/1, 6/15, 6/30, 12/1, 12/15, 12/30      & 5730                & 1013554          & 176.89                         & 21.55                          \\
               & 2016 & 6/15, 6/30, 12/15, 12/30                 & 6334                & 1250378          & 197.41                         & 23.03                          \\
               & 2018 & 6/15, 6/30, 12/15, 12/30                 & 5451                & 1098875          & 201.59                         & 23.59                          \\
               & 2020 & 6/15, 6/30, 12/15, 12/30                 & 5767                & 1264329          & 219.24                         & 23.37                          \\
               & 2022 & 6/15, 6/30, 12/15, 12/30                 & 4480                & 1039479          & 232.03                         & 24.81                          \\
               & 2024 & 6/15, 6/30, 12/15, 12/30                 & 3364                & 1166535          & 346.77                         & 28.12                         
\end{tabular}
\end{table}
