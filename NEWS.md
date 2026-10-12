# idepGolem 2.4.2.1 (SalmonFlow fork)

* DEG tab: new "Full DESeq2 results" download (`Results_full_DESeq2.csv`). It
  keeps every column of `DESeq2::results()` per comparison
  (`<A>-<B>_log2FC`, `_lfcSE`, `_stat`, `_pvalue`, `_adjPval`), so genes can be
  ranked by the Wald statistic for GSEA. Shown only when DESeq2 is the DE
  method. The existing "Results" download is unchanged.
* Based on upstream `v240_deployed` (f442289, iDEP 2.4.2).
