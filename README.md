## Supplementary material to the article "Revisiting Bayesian Optimization in the light of the COCO benchmark"
by Rodolphe Le Riche and Victor Picheny

This git project contains the supplementary material of the article "Revisiting Bayesian Optimization in the light of the COCO benchmark" (link to be added upon publication).
The following subdirectories contain all the results of a COCO postprocessing of optimization algorithms benchmarks. In each subdirectory, index.html is a handy way to navigate through the plots and tables. 
The easiest way to look at the results is to download the entire project (`code` button and download zip) and open the index.html files in each directory with a browser.

### List of subdirectories with content summary
* [InitialDoEsize](https://github.com/rleriche/supplement_BO_COCO/tree/main/InitialDoEsize) : tests on the initial size of the DoE (S / M / L versions of the algorithms)
* [Kernel](https://github.com/rleriche/supplement_BO_COCO/tree/main/Kernel) : exponential versus Matérn kernel (ExpS/ExpM/ExpL vs S/M)
* [Trend](https://github.com/rleriche/supplement_BO_COCO/tree/main/Trend) : constant (M) vs. linear (LinM) vs. quadratic (QuadM) trend. LinIn means linear with interactions (i.e., <img src="https://render.githubusercontent.com/render/math?math=x_i \times x_j \quad , \quad i \ne j,"> terms
* [Scaling](https://github.com/rleriche/supplement_BO_COCO/tree/main/Scaling) : scaling of the inputs with small/medium/large initial DoE (ScalS,ScalM,ScalL, respectively), versus S/M/L (no scaling, small/medium/large initial DoE).
* [Warping](https://github.com/rleriche/supplement_BO_COCO/tree/main/Warping) : warping of the outputs with small/medium/large initial DoE (WarpS,WarpM,WarpL, respectively), versus S/M/L (no warping, small/medium/large initial DoE).
* [GPmean](https://github.com/rleriche/supplement_BO_COCO/tree/main/GPmean) : effect of periodical GP mean acquisition with small/medium initial DoE (MeanS, MeanM respectively), versus S/M (no GP mean trick, small/medium initial DoE).
* [EiOpt](https://github.com/rleriche/supplement_BO_COCO/tree/main/EiOpt) : Effect of EI optimization mode, local (Eiloc), random (EIrandM) or restarted BFGS (M).
* [Compare](https://github.com/rleriche/supplement_BO_COCO/tree/main/Compare) : Comparison with other state-of-the-art optimizers, BFGS, SMAC, DTS-CMA-ES, NEWUOA, random. QuadMean is EGO with a quadratic trend and the GP mean periodical acquisition.

