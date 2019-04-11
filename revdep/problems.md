# adapr

Version: 2.0.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘plotly’ ‘shinydashboard’
      All declared Imports should be used.
    Missing or unexported object: ‘devtools::clean_source’
    ```

# adegenet

Version: 2.1.1

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  5.7Mb
      sub-directories of 1Mb or more:
        R       2.1Mb
        data    1.3Mb
        files   1.7Mb
    ```

# AdhereR

Version: 0.4.1

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  5.2Mb
      sub-directories of 1Mb or more:
        doc   3.2Mb
    ```

# analysisPipelines

Version: 1.0.0

## In both

*   checking package dependencies ... NOTE
    ```
    Packages which this enhances but not available for checking:
      ‘SparkR’ ‘reticulate’
    ```

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘devtools’
      All declared Imports should be used.
    ```

# appreci8R

Version: 1.0.0

## In both

*   checking package dependencies ... ERROR
    ```
    Packages required but not available:
      ‘BSgenome.Hsapiens.UCSC.hg19’ ‘Homo.sapiens’
      ‘SNPlocs.Hsapiens.dbSNP144.GRCh37’
      ‘XtraSNPlocs.Hsapiens.dbSNP144.GRCh37’
      ‘MafDb.1Kgenomes.phase3.hs37d5’ ‘MafDb.ExAC.r1.0.hs37d5’
      ‘MafDb.ESP6500SI.V2.SSA137.hs37d5’ ‘MafDb.gnomADex.r2.0.1.hs37d5’
      ‘COSMIC.67’ ‘PolyPhen.Hsapiens.dbSNP131’ ‘SIFT.Hsapiens.dbSNP137’
    
    Packages suggested but not available for checking: ‘GO.db’ ‘org.Hs.eg.db’
    
    See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
    manual.
    ```

# ArchaeoPhases

Version: 1.4

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘DT’
      All declared Imports should be used.
    ```

# archivist

Version: 2.3.2

## In both

*   checking Rd cross-references ... NOTE
    ```
    Package unavailable to check Rd xrefs: ‘archivist.github’
    ```

# arena2r

Version: 1.0.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘purrr’ ‘shinyBS’ ‘shinydashboard’ ‘shinyjs’
      All declared Imports should be used.
    ```

# AUCell

Version: 1.4.1

## In both

*   checking package dependencies ... NOTE
    ```
    Packages which this enhances but not available for checking: ‘doMC’ ‘doRNG’
    ```

*   checking dependencies in R code ... NOTE
    ```
    'library' or 'require' call to ‘rbokeh’ in package code.
      Please use :: or requireNamespace() instead.
      See section 'Suggested packages' in the 'Writing R Extensions' manual.
    ```

*   checking R code for possible problems ... NOTE
    ```
    .cellProps_plotTsne: warning in adjustcolor(colorPal(10), alpha = 0.8):
      partial argument match of 'alpha' to 'alpha.f'
    AUCell_createViewerApp : <anonymous>: no visible global function
      definition for ‘%>%’
    AUCell_createViewerApp : <anonymous>: no visible binding for global
      variable ‘tsne1’
    AUCell_createViewerApp : <anonymous>: no visible binding for global
      variable ‘tsne2’
    AUCell_createViewerApp : <anonymous>: no visible binding for global
      variable ‘cell’
    Undefined global functions or variables:
      %>% cell tsne1 tsne2
    ```

*   checking Rd cross-references ... NOTE
    ```
    Package unavailable to check Rd xrefs: ‘SingleCellExperiment’
    ```

*   checking for unstated dependencies in vignettes ... NOTE
    ```
    '::' or ':::' import not declared from: ‘reshape2’
    ```

# BatchQC

Version: 1.10.1

## In both

*   checking R code for possible problems ... NOTE
    ```
    gene_plot: no visible global function definition for ‘boxplot’
    gene_plot: no visible binding for global variable ‘batch’
    gls.series.C: no visible global function definition for ‘lm.fit’
    sample_plot: no visible global function definition for ‘boxplot’
    sample_plot: no visible binding for global variable ‘batch’
    Undefined global functions or variables:
      batch boxplot lm.fit
    Consider adding
      importFrom("graphics", "boxplot")
      importFrom("stats", "lm.fit")
    to your NAMESPACE file.
    ```

# BayesBD

Version: 1.2

## In both

*   checking package dependencies ... ERROR
    ```
    Package required but not available: ‘mritc’
    
    See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
    manual.
    ```

# BayesianNetwork

Version: 0.1.5

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘shinytest’ ‘testthat’
      All declared Imports should be used.
    ```

# BCEA

Version: 2.2-6

## In both

*   checking package dependencies ... NOTE
    ```
    Package suggested but not available for checking: ‘INLA’
    ```

# bdchecks

Version: 0.1.7

## In both

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 72 marked UTF-8 strings
    ```

# bde

Version: 1.0.1

## In both

*   checking R code for possible problems ... NOTE
    ```
    ...
    rsample,BoundedDensity: no visible global function definition for
      ‘runif’
    setNormalizationConst,MacroBetaChen99Kernel: no visible global function
      definition for ‘integrate’
    setNormalizationConst,MacroBetaHirukawaTSKernel: no visible global
      function definition for ‘integrate’
    setNormalizationConstant,MacroBetaHirukawaJLNKernel: no visible global
      function definition for ‘integrate’
    setNormalizationConstants,MicroBetaChen99Kernel :
      density.kernelFunction: no visible global function definition for
      ‘dbeta’
    setNormalizationConstants,MicroBetaChen99Kernel : <anonymous>: no
      visible global function definition for ‘integrate’
    show,BoundedDensity: no visible global function definition for ‘str’
    show,KernelDensity: no visible global function definition for ‘str’
    Undefined global functions or variables:
      dbeta integrate runif str
    Consider adding
      importFrom("stats", "dbeta", "integrate", "runif")
      importFrom("utils", "str")
    to your NAMESPACE file.
    ```

# bea.R

Version: 1.0.6

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘Rcpp’ ‘chron’ ‘colorspace’ ‘gtable’ ‘htmltools’ ‘htmlwidgets’
      ‘httpuv’ ‘magrittr’ ‘munsell’ ‘plyr’ ‘scales’ ‘stringi’ ‘xtable’
      ‘yaml’
      All declared Imports should be used.
    ```

# beanz

Version: 2.4

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  8.5Mb
      sub-directories of 1Mb or more:
        libs   7.1Mb
    ```

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘rstantools’
      All declared Imports should be used.
    ```

*   checking for GNU extensions in Makefiles ... NOTE
    ```
    GNU make is a SystemRequirements.
    ```

# bigQueryR

Version: 0.4.0

## In both

*   checking Rd cross-references ... NOTE
    ```
    Package unavailable to check Rd xrefs: ‘bigrquery’
    ```

# bioCancer

Version: 1.10.11

## In both

*   checking package dependencies ... ERROR
    ```
    Packages required but not available: ‘org.Hs.eg.db’ ‘reactome.db’
    
    See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
    manual.
    ```

# BiocOncoTK

Version: 1.2.1

## In both

*   checking tests ...
    ```
     ERROR
    Running the tests in ‘tests/testthat.R’ failed.
    Last 13 lines of output:
      Loading required package: BiocParallel
      
      Attaching package: 'DelayedArray'
      
      The following objects are masked from 'package:matrixStats':
      
          colMaxs, colMins, colRanges, rowMaxs, rowMins, rowRanges
      
      The following objects are masked from 'package:base':
      
          aperm, apply
      
      Error: package or namespace load failed for 'restfulSE' in loadNamespace(i, c(lib.loc, .libPaths()), versionCheck = vI[[i]]):
       there is no package called 'GO.db'
      Execution halted
    ```

*   checking re-building of vignette outputs ... WARNING
    ```
    Error in re-building vignettes:
      ...
    Quitting from lines 18-30 (BiocOncoTK.Rmd) 
    Error: processing vignette 'BiocOncoTK.Rmd' failed with diagnostics:
    there is no package called 'org.Hs.eg.db'
    Execution halted
    ```

*   checking package dependencies ... NOTE
    ```
    Packages suggested but not available for checking:
      ‘org.Hs.eg.db’ ‘TxDb.Hsapiens.UCSC.hg18.knownGene’
      ‘EnsDb.Hsapiens.v75’
    ```

*   checking installed package size ... NOTE
    ```
      installed size is  6.2Mb
      sub-directories of 1Mb or more:
        data   4.0Mb
        doc    1.9Mb
    ```

*   checking DESCRIPTION meta-information ... NOTE
    ```
    Package listed in more than one of Depends, Imports, Suggests, Enhances:
      ‘DBI’
    A package should be listed in only one of these fields.
    ```

*   checking R code for possible problems ... NOTE
    ```
    ...
    .rainfall.maeGRL.df: no visible global function definition for
      ‘seqlengths’
    checkCache_patel: no visible global function definition for
      ‘BiocFileCache’
    chrbounds_basic: no visible global function definition for ‘seqlengths’
    ggFeatDens : <anonymous>: no visible binding for global variable
      ‘Consequence’
    ggFeatDens: no visible binding for global variable ‘tfstart’
    ggFeatureSegs: no visible global function definition for ‘genes’
    ggFeatureSegs: no visible binding for global variable ‘symbol’
    ggMutDens : <anonymous>: no visible binding for global variable
      ‘Consequence’
    ggMutDens: no visible binding for global variable ‘project_short_name’
    mc3toGR : <anonymous>: no visible binding for global variable
      ‘Consequence’
    rainfall: no visible global function definition for ‘genome’
    tumNorSet : <anonymous>: no visible global function definition for
      ‘pancan_SE’
    Undefined global functions or variables:
      BiocFileCache Consequence genes genome pancan_SE project_short_name
      seqlengths symbol tfstart
    ```

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 46 marked UTF-8 strings
    ```

# BioInstaller

Version: 0.3.7

## In both

*   checking installed package size ... NOTE
    ```
      installed size is 11.1Mb
      sub-directories of 1Mb or more:
        doc       2.5Mb
        extdata   8.1Mb
    ```

# BioNetStat

Version: 1.2.2

## In both

*   checking examples ... ERROR
    ```
    ...
    all             4      134       12.80382             0.5     0.5 27.01668
        Factor 2 Factor 1 Factor 3
    all 25.30742 20.89907 26.77683
    > # The numPermutations number is 1 to do a faster example, but we advise to use unless 1000 permutations in real analysis
    >   
    > # Random data
    > set.seed(1)
    > varFile <- as.data.frame(matrix(rnorm(120),40,30))
    > labels<-rep(0:3,10)
    > adjacencyMatrix1 <- adjacencyMatrix(method="spearman", association="pvalue", threshold="fdr",
    +  thr.value=0.05, weighted=FALSE)
    > diffNetAnalysis(method=degreeCentralityTest, varFile=varFile, labels=labels, varSets=NULL,
    +  adjacencyMatrix=adjacencyMatrix1, numPermutations=10, print=TRUE, resultsFile=NULL,
    +   seed=NULL, min.vert=5, option=NULL)
    Testing all (1 of 1)
    Warning in socketConnection(host, port, TRUE, TRUE, "a+b", timeout = timeout) :
      port 11266 cannot be opened
    Error in socketConnection(host, port, TRUE, TRUE, "a+b", timeout = timeout) : 
      cannot open the connection
    Calls: diffNetAnalysis ... .local -> .bpfork -> .bpforkConnect -> socketConnection
    Execution halted
    ```

*   checking installed package size ... NOTE
    ```
      installed size is  5.1Mb
      sub-directories of 1Mb or more:
        extdata   1.9Mb
        shiny     1.6Mb
    ```

# biva

Version: 0.1.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘corrgram’ ‘rpivotTable’ ‘shinyAce’
      All declared Imports should be used.
    ```

# blkbox

Version: 1.0

## In both

*   checking package dependencies ... NOTE
    ```
    Package suggested but not available for checking: ‘bigrf’
    ```

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘glmnet’ ‘gtools’ ‘knitr’ ‘nnet’ ‘parallel’ ‘rJava’ ‘reshape’
      ‘rmarkdown’ ‘shinyjs’
      All declared Imports should be used.
    Missing or unexported object: ‘xgboost::predict’
    ```

# blockseg

Version: 0.5.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘shiny’
      All declared Imports should be used.
    ```

# bpbounds

Version: 0.1.3

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘methods’
      All declared Imports should be used.
    ```

# bsplus

Version: 0.1.1

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘methods’
      All declared Imports should be used.
    ```

# caffsim

Version: 0.2.2

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘markdown’
      All declared Imports should be used.
    ```

# cartools

Version: 0.1.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘animation’ ‘devtools’ ‘gapminder’ ‘knitr’ ‘rlist’ ‘rmarkdown’
      ‘roxygen2’ ‘sde’ ‘shiny’ ‘tidyverse’ ‘usethis’ ‘utils’
      All declared Imports should be used.
    ```

# CATALYST

Version: 1.6.7

## In both

*   checking for hidden files and directories ... NOTE
    ```
    Found the following hidden files and directories:
      .travis.yml
    These were most likely included in error. See section ‘Package
    structure’ in the ‘Writing R Extensions’ manual.
    ```

*   checking installed package size ... NOTE
    ```
      installed size is  9.5Mb
      sub-directories of 1Mb or more:
        data   3.3Mb
        doc    5.2Mb
    ```

# ChAMP

Version: 2.12.4

## In both

*   checking package dependencies ... ERROR
    ```
    Packages required but not available:
      ‘ChAMPdata’ ‘IlluminaHumanMethylationEPICmanifest’
      ‘IlluminaHumanMethylation450kmanifest’
      ‘IlluminaHumanMethylationEPICanno.ilm10b2.hg19’
    
    Depends: includes the non-default packages:
      ‘minfi’ ‘ChAMPdata’ ‘FEM’ ‘DMRcate’ ‘Illumina450ProbeVariants.db’
      ‘IlluminaHumanMethylationEPICmanifest’
    Adding so many packages to the search path is excessive and importing
    selectively is preferable.
    
    See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
    manual.
    ```

# ChannelAttributionApp

Version: 1.1

## In both

*   checking DESCRIPTION meta-information ... NOTE
    ```
    Checking should be performed on sources prepared by ‘R CMD build’.
    ```

# chipPCR

Version: 0.0.8-10

## In both

*   checking R code for possible problems ... NOTE
    ```
    ...
    plot,refMFI-refMFI: no visible global function definition for ‘mtext’
    plot,refMFI-refMFI: no visible global function definition for ‘abline’
    plot,refMFI-refMFI: no visible global function definition for ‘legend’
    plot,refMFI-refMFI: no visible global function definition for ‘lines’
    qqline,refMFI: no visible binding for global variable ‘qnorm’
    Undefined global functions or variables:
      abline adjustcolor arrows axis coef cor head layout legend lines lm
      mad matplot median mtext na.omit par points polygon predict
      predict.lm qnorm quantile rect rnorm rstudent rug sd shapiro.test
      smooth.spline tail text wilcox.test
    Consider adding
      importFrom("grDevices", "adjustcolor")
      importFrom("graphics", "abline", "arrows", "axis", "layout", "legend",
                 "lines", "matplot", "mtext", "par", "points", "polygon",
                 "rect", "rug", "text")
      importFrom("stats", "coef", "cor", "lm", "mad", "median", "na.omit",
                 "predict", "predict.lm", "qnorm", "quantile", "rnorm",
                 "rstudent", "sd", "shapiro.test", "smooth.spline",
                 "wilcox.test")
      importFrom("utils", "head", "tail")
    to your NAMESPACE file.
    ```

# chromVAR

Version: 1.4.1

## In both

*   checking examples ... ERROR
    ```
    Running examples in ‘chromVAR-Ex.R’ failed
    The error most likely occurred in:
    
    > ### Name: addGCBias
    > ### Title: addGCBias
    > ### Aliases: addGCBias addGCBias,RangedSummarizedExperiment-method
    > ###   addGCBias,SummarizedExperiment-method
    > 
    > ### ** Examples
    > 
    > 
    > data(example_counts, package = "chromVAR")
    > # show example on small part of data 
    > subset_counts <- example_counts[1:500,]
    > library(BSgenome.Hsapiens.UCSC.hg19)
    Error in library(BSgenome.Hsapiens.UCSC.hg19) : 
      there is no package called ‘BSgenome.Hsapiens.UCSC.hg19’
    Execution halted
    ```

*   checking re-building of vignette outputs ... WARNING
    ```
    ...
    
    The following objects are masked from 'package:Biobase':
    
        anyMissing, rowMedians
    
    Loading required package: BiocParallel
    
    Attaching package: 'DelayedArray'
    
    The following objects are masked from 'package:matrixStats':
    
        colMaxs, colMins, colRanges, rowMaxs, rowMins, rowRanges
    
    The following objects are masked from 'package:base':
    
        aperm, apply
    
    Quitting from lines 107-111 (Introduction.Rmd) 
    Error: processing vignette 'Introduction.Rmd' failed with diagnostics:
    there is no package called 'BSgenome.Hsapiens.UCSC.hg19'
    Execution halted
    ```

*   checking package dependencies ... NOTE
    ```
    Package suggested but not available for checking: ‘BSgenome.Hsapiens.UCSC.hg19’
    ```

# citr

Version: 0.3.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘bibtex’
      All declared Imports should be used.
    ```

# cjoint

Version: 2.1.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘shinyBS’
      All declared Imports should be used.
    ```

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 29 marked UTF-8 strings
    ```

# clustDRM

Version: 0.1-0

## In both

*   checking package dependencies ... ERROR
    ```
    Package required but not available: ‘IsoGene’
    
    See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
    manual.
    ```

# CNVPanelizer

Version: 1.14.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Unexported object imported by a ':::' call: ‘utils:::format.object_size’
      See the note in ?`:::` about the use of this operator.
    ```

# CNVScope

Version: 1.9.7

## In both

*   checking package dependencies ... ERROR
    ```
    Package required but not available: ‘BSgenome.Hsapiens.UCSC.hg19’
    
    See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
    manual.
    ```

# cocktailApp

Version: 0.2.0

## In both

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 14661 marked UTF-8 strings
    ```

# codebook

Version: 0.8.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘graphics’ ‘jsonlite’ ‘pander’ ‘rlang’
      All declared Imports should be used.
    ```

*   checking Rd cross-references ... NOTE
    ```
    Package unavailable to check Rd xrefs: ‘mice’
    ```

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 65 marked UTF-8 strings
    ```

# compareGroups

Version: 4.0.0

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  7.0Mb
      sub-directories of 1Mb or more:
        app   2.7Mb
        doc   2.3Mb
    ```

# COMPASS

Version: 1.20.1

## In both

*   checking for hidden files and directories ... NOTE
    ```
    Found the following hidden files and directories:
      .github
    These were most likely included in error. See section ‘Package
    structure’ in the ‘Writing R Extensions’ manual.
    ```

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘BiocStyle’ ‘rmarkdown’
      All declared Imports should be used.
    ':::' call which should be '::': ‘flowWorkspace:::.getNodeInd’
      See the note in ?`:::` about the use of this operator.
    ```

*   checking R code for possible problems ... NOTE
    ```
    .CellCounts: no visible binding for global variable
      ‘_COMPASS_CellCounts’
    COMPASSfitToCountsTable: no visible binding for global variable
      ‘population’
    COMPASSfitToCountsTable: no visible binding for global variable ‘Count’
    COMPASSfitToCountsTable: no visible binding for global variable ‘id’
    CellCounts_character: no visible binding for global variable
      ‘_COMPASS_CellCounts_character’
    Undefined global functions or variables:
      Count _COMPASS_CellCounts _COMPASS_CellCounts_character id population
    ```

*   checking for unstated dependencies in vignettes ... NOTE
    ```
    'library' or 'require' calls not declared from:
      ‘ggplot2’ ‘readxl’
    ```

# condformat

Version: 0.8.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘graphics’
      All declared Imports should be used.
    ```

# CoRegNet

Version: 1.20.0

## In both

*   checking tests ...
    ```
     ERROR
    Running the tests in ‘tests/runTests.R’ failed.
    Last 13 lines of output:
      Loading required package: shiny
      Loading required package: arules
      Loading required package: Matrix
      
      Attaching package: 'arules'
      
      The following objects are masked from 'package:base':
      
          abbreviate, write
      
      [1] TRUE
      > BiocGenerics:::testPackage('CoRegNet')
      Error in loadNamespace(name) : there is no package called 'BiocGenerics'
      Calls: ::: ... tryCatch -> tryCatchList -> tryCatchOne -> <Anonymous>
      Execution halted
    ```

*   checking for unstated dependencies in ‘tests’ ... WARNING
    ```
    '::' or ':::' import not declared from: ‘BiocGenerics’
    ```

*   checking dependencies in R code ... NOTE
    ```
    'library' or 'require' calls in package code:
      ‘RColorBrewer’ ‘gplots’
      Please use :: or requireNamespace() instead.
      See section 'Suggested packages' in the 'Writing R Extensions' manual.
    ```

*   checking R code for possible problems ... NOTE
    ```
    ...
    refine,coregnet: no visible global function definition for ‘abline’
    regulatorInfluence,coregnet : <anonymous> : <anonymous>: no visible
      global function definition for ‘t.test’
    regulators,coregnet: no visible global function definition for
      ‘na.omit’
    repressors,coregnet: no visible global function definition for
      ‘na.omit’
    targets,coregnet: no visible global function definition for ‘na.omit’
    Undefined global functions or variables:
      abline arrows as.dist axis coef colorRampPalette cor fisher.test glm
      hclust heatmap.2 lines lm mtext na.omit p.adjust par pchisq plot
      pnorm quantile rainbow sd segments symbols t.test text vcount
      wilcox.test
    Consider adding
      importFrom("grDevices", "colorRampPalette", "rainbow")
      importFrom("graphics", "abline", "arrows", "axis", "lines", "mtext",
                 "par", "plot", "segments", "symbols", "text")
      importFrom("stats", "as.dist", "coef", "cor", "fisher.test", "glm",
                 "hclust", "lm", "na.omit", "p.adjust", "pchisq", "pnorm",
                 "quantile", "sd", "t.test", "wilcox.test")
    to your NAMESPACE file.
    ```

# cosinor

Version: 1.1

## In both

*   checking R code for possible problems ... NOTE
    ```
    ...
    cosinor_analyzer : <anonymous>: no visible global function definition
      for ‘as.formula’
    ggplot.cosinor.lm: no visible global function definition for ‘predict’
    predict.cosinor.lm: no visible global function definition for ‘fitted’
    predict.cosinor.lm: no visible global function definition for ‘predict’
    simulate_cosinor: no visible global function definition for ‘runif’
    simulate_cosinor: no visible global function definition for ‘rbinom’
    simulate_cosinor: no visible global function definition for ‘rnorm’
    summary.cosinor.lm: no visible global function definition for ‘vcov’
    summary.cosinor.lm: no visible global function definition for ‘qnorm’
    summary.cosinor.lm: no visible global function definition for ‘pnorm’
    test_cosinor: no visible global function definition for ‘pchisq’
    test_cosinor: no visible global function definition for ‘pnorm’
    Undefined global functions or variables:
      as.formula fitted lm na.omit pchisq pnorm predict qnorm rbinom rnorm
      runif terms vcov vitamind
    Consider adding
      importFrom("stats", "as.formula", "fitted", "lm", "na.omit", "pchisq",
                 "pnorm", "predict", "qnorm", "rbinom", "rnorm", "runif",
                 "terms", "vcov")
    to your NAMESPACE file.
    ```

# coveffectsplot

Version: 0.0.3

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘colourpicker’ ‘dplyr’ ‘markdown’ ‘shinyjs’ ‘tidyr’
      All declared Imports should be used.
    ```

# CRANsearcher

Version: 1.0.0

## In both

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 11 marked Latin-1 strings
      Note: found 57 marked UTF-8 strings
    ```

# crawl

Version: 2.2.1

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘gdistance’ ‘raster’
      All declared Imports should be used.
    ```

# crisprseekplus

Version: 1.8.0

## In both

*   checking re-building of vignette outputs ... WARNING
    ```
    Error in re-building vignettes:
      ...
    Error: processing vignette 'crisprseekplus.Rmd' failed with diagnostics:
    there is no package called ‘BiocStyle’
    Execution halted
    ```

*   checking R code for possible problems ... NOTE
    ```
    installpack: no visible global function definition for
      'install.packages'
    Undefined global functions or variables:
      install.packages
    Consider adding
      importFrom("utils", "install.packages")
    to your NAMESPACE file.
    ```

# crossmeta

Version: 1.8.0

## In both

*   checking for code/documentation mismatches ... WARNING
    ```
    Data with usage in documentation object 'gs.names' but not in code:
      gs.names
    
    Data with usage in documentation object 'gslist' but not in code:
      gslist
    ```

*   checking package dependencies ... NOTE
    ```
    Package suggested but not available for checking: ‘org.Hs.eg.db’
    ```

*   checking dependencies in R code ... NOTE
    ```
    Missing or unexported objects:
      ‘crossmeta::gs.names’ ‘crossmeta::gslist’
    ```

*   checking R code for possible problems ... NOTE
    ```
    explore_paths : server: no visible binding for global variable ‘gslist’
    explore_paths : server: no visible binding for global variable
      ‘gs.names’
    Undefined global functions or variables:
      gs.names gslist
    ```

*   checking Rd cross-references ... NOTE
    ```
    Packages unavailable to check Rd xrefs: ‘PADOG’, ‘GeneMeta’
    ```

# CTRE

Version: 0.1.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘tea’
      All declared Imports should be used.
    ```

# ctsem

Version: 2.8.2

## In both

*   checking installed package size ... NOTE
    ```
      installed size is 10.5Mb
      sub-directories of 1Mb or more:
        data   1.8Mb
        libs   6.8Mb
    ```

*   checking for GNU extensions in Makefiles ... NOTE
    ```
    GNU make is a SystemRequirements.
    ```

# CVE

Version: 1.8.0

## In both

*   checking data for ASCII and uncompressed saves ... WARNING
    ```
      
      Note: significantly better compression could be obtained
            by using R CMD build --resave-data
                                    old_size new_size compress
      WGCNAmelanoma_extension.RData    2.4Mb    2.1Mb       xz
      crcCase.RData                    1.1Mb    677Kb       xz
      melanomaCase.RData               654Kb    472Kb       xz
    ```

*   checking installed package size ... NOTE
    ```
      installed size is  5.8Mb
      sub-directories of 1Mb or more:
        data   4.1Mb
        doc    1.5Mb
    ```

*   checking dependencies in R code ... NOTE
    ```
    Package in Depends field not imported from: ‘tidyverse’
      These packages need to be imported from (in the NAMESPACE file)
      for when this namespace is loaded but not attached.
    ```

# cydar

Version: 1.6.1

## In both

*   checking re-building of vignette outputs ... WARNING
    ```
    ...
    write Sample5 to empty cdf slot...
    write Sample6 to empty cdf slot...
    Loading required package: limma
    
    Attaching package: 'limma'
    
    The following object is masked from 'package:BiocGenerics':
    
        plotMA
    
    
    Attaching package: 'edgeR'
    
    The following object is masked from 'package:SingleCellExperiment':
    
        cpm
    
    Quitting from lines 231-235 (cydar.Rmd) 
    Error: processing vignette 'cydar.Rmd' failed with diagnostics:
    statmod package required but is not installed
    Execution halted
    ```

*   checking dependencies in R code ... NOTE
    ```
    Unexported object imported by a ':::' call: ‘S4Vectors:::selectSome’
      See the note in ?`:::` about the use of this operator.
    ```

# cytofkit

Version: 1.12.0

## In both

*   checking examples ... ERROR
    ```
    ...
    > m1 <- c(rnorm(300, 10, 2), rnorm(400, 4, 2), rnorm(300, 7))
    > m2 <- c(rnorm(300, 4), rnorm(400, 16), rnorm(300, 10, 3))
    > m3 <- c(rnorm(300, 16), rnorm(400, 40, 3), rnorm(300, 10))
    > m4 <- c(rnorm(300, 7, 3), rnorm(400, 30, 2), rnorm(300, 10))
    > m5 <- c(rnorm(300, 27), rnorm(400, 40, 1),rnorm(300, 10))
    > c <- c(rep(1,300), rep(2,400), rep(3,300))
    > rnames <- paste(paste('sample_', c('A','B','C','D'), sep = ''), 
    + rep(1:250,each = 4), sep='_') 
    > exprs_cluster <- data.frame(cluster = c, m1 = m1, m2 = m2, m3 = m3, m4 = m4, isomap_1 = m5)
    > row.names(exprs_cluster) <- sample(rnames, 1000)
    > cytof_progressionPlot(exprs_cluster, markers = c("m1","m2","m3","m4"))
    [1] "Error!"
    <simpleError in eval(call[[1L]]): object 'sm.ns' not found>
    [1] "Error!"
    <simpleError in eval(call[[1L]]): object 'sm.ns' not found>
    [1] "Error!"
    <simpleError in eval(call[[1L]]): object 'sm.ns' not found>
    [1] "Error!"
    <simpleError in eval(call[[1L]]): object 'sm.ns' not found>
    Error: Discrete value supplied to continuous scale
    Execution halted
    ```

*   checking re-building of vignette outputs ... WARNING
    ```
    Error in re-building vignettes:
      ...
    Error: processing vignette 'cytofkit_example.Rmd' failed with diagnostics:
    there is no package called ‘BiocStyle’
    Execution halted
    ```

*   checking installed package size ... NOTE
    ```
      installed size is  8.5Mb
      sub-directories of 1Mb or more:
        doc       4.3Mb
        extdata   3.6Mb
    ```

*   checking R code for possible problems ... NOTE
    ```
    cytof_clusterPlot: no visible global function definition for
      ‘geom_text’
    cytof_progressionPlot: no visible global function definition for ‘aes’
    cytof_progressionPlot: no visible binding for global variable
      ‘Pseudotime’
    cytof_progressionPlot: no visible binding for global variable ‘cluster’
    cytofkitShinyAPP : <anonymous> : C_ScatterPlotInput: no visible global
      function definition for ‘scatterPlot’
    cytofkitShinyAPP : <anonymous>: no visible global function definition
      for ‘heatMap’
    cytofkitShinyAPP : <anonymous> : M_markerExpressionPlotInput: no
      visible global function definition for ‘scatterPlot’
    cytofkitShinyAPP : <anonymous> : M_stackDensityPlotInput: no visible
      global function definition for ‘stackDenistyPlot’
    cytofkitShinyAPP : <anonymous> : P_markerPlotInput: no visible global
      function definition for ‘cytof_expressionTrends’
    Undefined global functions or variables:
      Pseudotime aes cluster cytof_expressionTrends geom_text heatMap
      scatterPlot stackDenistyPlot
    ```

# d3heatmap

Version: 0.6.1.2

## In both

*   checking Rd cross-references ... NOTE
    ```
    Package unavailable to check Rd xrefs: ‘gplots’
    ```

# d3Tree

Version: 0.2.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘magrittr’
      All declared Imports should be used.
    ```

# datacheck

Version: 1.2.2

## In both

*   checking R code for possible problems ... NOTE
    ```
    ...
    is_one_of: no visible global function definition for ‘read.csv’
    pkg.version: no visible global function definition for ‘citation’
    pkg_version: no visible global function definition for ‘citation’
    ruleCoverage: no visible global function definition for ‘dotchart’
    ruleCoverage: no visible global function definition for ‘abline’
    rule_coverage: no visible global function definition for ‘dotchart’
    rule_coverage: no visible global function definition for ‘abline’
    scoreSum: no visible global function definition for ‘plot’
    score_sum: no visible global function definition for ‘plot’
    shortSummary: no visible global function definition for ‘sd’
    short_summary: no visible global function definition for ‘sd’
    Undefined global functions or variables:
      abline citation colorRampPalette dotchart heatmap plot read.csv sd
      setTxtProgressBar txtProgressBar
    Consider adding
      importFrom("grDevices", "colorRampPalette")
      importFrom("graphics", "abline", "dotchart", "plot")
      importFrom("stats", "heatmap", "sd")
      importFrom("utils", "citation", "read.csv", "setTxtProgressBar",
                 "txtProgressBar")
    to your NAMESPACE file.
    ```

*   checking files in ‘vignettes’ ... NOTE
    ```
    Package has no Sweave vignette sources and no VignetteBuilder field.
    ```

# datadigest

Version: 1.0.2

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘miniUI’
      All declared Imports should be used.
    ```

# debrowser

Version: 1.10.9

## In both

*   checking package dependencies ... ERROR
    ```
    Packages required but not available: ‘org.Hs.eg.db’ ‘org.Mm.eg.db’
    
    See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
    manual.
    ```

# DEP

Version: 1.4.1

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  5.6Mb
      sub-directories of 1Mb or more:
        data   1.4Mb
        doc    3.1Mb
    ```

# detzrcr

Version: 0.2.5

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘utils’
      All declared Imports should be used.
    ```

# dextergui

Version: 0.1.6

## In both

*   checking dependencies in R code ... NOTE
    ```
    Unexported objects imported by ':::' calls:
      ‘dexter:::get_resp_data’ ‘dexter:::qcolors’
      See the note in ?`:::` about the use of this operator.
    ```

# DLMtool

Version: 5.3

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  5.5Mb
      sub-directories of 1Mb or more:
        R      2.0Mb
        data   2.1Mb
    ```

# Doscheda

Version: 1.4.1

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  6.0Mb
      sub-directories of 1Mb or more:
        data             2.1Mb
        doc              1.6Mb
        shiny-examples   2.0Mb
    ```

# dplyrAssist

Version: 0.1.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘tidyr’ ‘tidyverse’
      All declared Imports should be used.
    ```

# dropR

Version: 0.1

## In both

*   checking R code for possible problems ... NOTE
    ```
    compute_xsq: no visible global function definition for ‘chisq.test’
    Undefined global functions or variables:
      chisq.test
    Consider adding
      importFrom("stats", "chisq.test")
    to your NAMESPACE file.
    ```

# dtwclust

Version: 5.5.2

## In both

*   checking for GNU extensions in Makefiles ... NOTE
    ```
    GNU make is a SystemRequirements.
    ```

# dynamichazard

Version: 0.6.5

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  9.8Mb
      sub-directories of 1Mb or more:
        data   5.1Mb
        doc    1.6Mb
        libs   2.6Mb
    ```

# EBImage

Version: 4.24.0

## In both

*   checking installed package size ... NOTE
    ```
      installed size is 16.4Mb
      sub-directories of 1Mb or more:
        doc     14.0Mb
        images   1.7Mb
    ```

# eechidna

Version: 1.3.0

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  5.3Mb
      sub-directories of 1Mb or more:
        data   4.4Mb
    ```

# effectR

Version: 1.0.2

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘rmarkdown’
      All declared Imports should be used.
    ```

# EHRtemporalVariability

Version: 1.0

## In both

*   checking installed package size ... NOTE
    ```
      installed size is 10.2Mb
      sub-directories of 1Mb or more:
        doc       4.9Mb
        extdata   5.1Mb
    ```

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘devtools’ ‘shiny’
      All declared Imports should be used.
    ```

# elementR

Version: 1.3.6

## In both

*   checking examples ... ERROR
    ```
    Running examples in ‘elementR-Ex.R’ failed
    The error most likely occurred in:
    
    > ### Name: elementR_project
    > ### Title: Object elementR_project
    > ### Aliases: elementR_project
    > 
    > ### ** Examples
    > 
    > ## create a new elementR_repStandard object based on the "filePath" 
    > ## from a folder containing sample replicate
    > 
    > filePath <- system.file("Example_Session", package="elementR")
    > 
    > exampleProject <- elementR_project$new(filePath)
    Error in structure(.External(.C_dotTclObjv, objv), class = "tclObj") : 
      [tcl] invalid command name "toplevel".
    Calls: <Anonymous> ... tktoplevel -> tkwidget -> tcl -> .Tcl.objv -> structure
    Execution halted
    ```

# embryogrowth

Version: 7.4.1

## In both

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 5 marked UTF-8 strings
    ```

# EmiStatR

Version: 1.2.1.2

## In both

*   checking examples ... ERROR
    ```
    ...
    The following objects are masked from ‘package:base’:
    
        as.Date, as.Date.numeric
    
    > 
    > data("Esch_Sure2010")
    > 
    > cinp            <- 150 # water consumption [m3/h]
    > prec            <- Esch_Sure2010[1:1000,] # selecting just the first 1,000 rows
    > cinp.daily.dir  <- system.file("shiny/EmiStatR_inputCSO/inputCSO", package = "EmiStatR")
    > cinp.daily.file <- paste(cinp.daily.dir, "/qs_factor.csv", sep="")
    > cinp.weekly     <- list(mon=1, tue=.83, wed=.83, thu=.83, fri=1, sat=1.25, sun=1.25)  
    > # factors average to 1
    > cinp.seasonal   <- list(jan=.79, feb=.79, mar=1.15, apr=1.15, may=1.15, jun=1.15,
    +                         jul=1.15, aug=1.15, sep=1.15, oct=1.15, nov=.79, dec=.79) 
    > # factors average to 1
    > 
    > ts1 <- CInp2TS(cinp, prec, cinp.daily.file, cinp.weekly, cinp.seasonal)
    Error in `[.xts`(cinp.ts.deltap, 1:nrow(P1), ) : subscript out of bounds
    Calls: CInp2TS -> [ -> [.xts
    Execution halted
    ```

# emuR

Version: 1.1.2

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘git2r’ ‘servr’
      All declared Imports should be used.
    ```

# ENCODExplorer

Version: 2.8.0

## In both

*   checking installed package size ... NOTE
    ```
      installed size is 73.8Mb
      sub-directories of 1Mb or more:
        data     24.1Mb
        doc       1.5Mb
        extdata  48.0Mb
    ```

*   checking R code for possible problems ... NOTE
    ```
    ...
      ‘biosample_type’
    step6_control: no visible binding for global variable ‘controls’
    step6_date_released: no visible binding for global variable
      ‘date_released’
    step6_status: no visible binding for global variable ‘status’
    step6_target: no visible binding for global variable ‘target’
    step7: no visible binding for global variable ‘organism’
    step8: no visible binding for global variable ‘investigated_as’
    step8: no visible binding for global variable ‘target’
    step9: no visible binding for global variable ‘organism’
    Undefined global functions or variables:
      . Experiment Value accession antibody_caption
      antibody_characterization antibody_target assay
      biological_replicate_number biosample_name biosample_type col_name
      controls data date_released download.file encode_df file_accession
      file_format href investigated_as lab nucleic_acid_term organism
      platform project replicate_antibody replicate_library server status
      submitted_by target technical_replicate_number treatment ui value
    Consider adding
      importFrom("utils", "data", "download.file")
    to your NAMESPACE file.
    ```

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 771 marked UTF-8 strings
    ```

# enviGCMS

Version: 0.5.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘BiocParallel’ ‘broom’ ‘reshape2’ ‘rmarkdown’
      All declared Imports should be used.
    ```

# epicontacts

Version: 1.1.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘colorspace’
      All declared Imports should be used.
    ```

# EpiSignalDetection

Version: 0.1.1

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘DT’ ‘ggplot2’ ‘knitr’ ‘pander’
      All declared Imports should be used.
    ```

# epivizrChart

Version: 1.4.0

## In both

*   checking examples ... ERROR
    ```
    Running examples in ‘epivizrChart-Ex.R’ failed
    The error most likely occurred in:
    
    > ### Name: plot,EpivizEnvironment,ANY-method
    > ### Title: Generic methods to plot charts and add navigation regions
    > ### Aliases: plot,EpivizEnvironment,ANY-method
    > 
    > ### ** Examples
    > 
    > library(epivizrChart)
    > library(Homo.sapiens)
    Error in library(Homo.sapiens) : 
      there is no package called 'Homo.sapiens'
    Execution halted
    ```

*   checking tests ...
    ```
     ERROR
    Running the tests in ‘tests/testthat.R’ failed.
    Last 13 lines of output:
      3: head(keys(hgu133plus2.db, keytype = "PROBEID"), nprobeids) at /Users/barret/odrive/AmazonCloudDrive/git/rstudio/shiny/shiny/revdep/checks.noindex/epivizrChart/new/epivizrChart.Rcheck/tests/testthat/helper-makeData.R:20
      
      ══ testthat results  ═══════════════════════════════════════════════════════════
      OK: 8 SKIPPED: 0 FAILED: 8
      1. Error: initializing charts works with data objects (@test-chart.R#5) 
      2. Error: initializing charts works with measurements (@test-chart.R#63) 
      3. Error: revisualizing charts as a different chart type works (@test-chart.R#80) 
      4. Error: navigating chart to different region works (@test-chart.R#91) 
      5. Error: initializing charts within an environment works (@test-env.R#5) 
      6. Error: removing charts from an environment works (@test-env.R#32) 
      7. Error: initializing charts within a navigation works (@test-nav.R#5) 
      8. Error: navigating charts within a navigation works (@test-nav.R#31) 
      
      Error: testthat unit tests failed
      Execution halted
    ```

*   checking re-building of vignette outputs ... WARNING
    ```
    Error in re-building vignettes:
      ...
    Quitting from lines 16-18 (IntegrationWithIGVjs.Rmd) 
    Error: processing vignette 'IntegrationWithIGVjs.Rmd' failed with diagnostics:
    there is no package called 'Homo.sapiens'
    Execution halted
    ```

*   checking package dependencies ... NOTE
    ```
    Packages suggested but not available for checking:
      ‘antiProfilesData’ ‘hgu133plus2.db’ ‘Mus.musculus’ ‘Homo.sapiens’
    ```

*   checking installed package size ... NOTE
    ```
      installed size is 25.1Mb
      sub-directories of 1Mb or more:
        data   3.3Mb
        doc   17.3Mb
        www    3.8Mb
    ```

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: 'epivizrServer'
      All declared Imports should be used.
    ```

# erma

Version: 0.14.0

## In both

*   checking package dependencies ... ERROR
    ```
    Package required but not available: ‘Homo.sapiens’
    
    Package suggested but not available for checking: ‘GO.db’
    
    See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
    manual.
    ```

# EventStudy

Version: 0.36

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  5.9Mb
      sub-directories of 1Mb or more:
        doc   5.0Mb
    ```

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘curl’ ‘openxlsx’ ‘stringr’
      All declared Imports should be used.
    ```

# fanplot

Version: 3.4.1

## In both

*   checking package dependencies ... NOTE
    ```
    Package suggested but not available for checking: ‘tsbugs’
    ```

# FastqCleaner

Version: 1.0.0

## In both

*   checking DESCRIPTION meta-information ... NOTE
    ```
    Package listed in more than one of Depends, Imports, Suggests, Enhances:
      ‘methods’
    A package should be listed in only one of these fields.
    ```

# FELLA

Version: 1.2.0

## In both

*   checking running R code from vignettes ...
    ```
       ‘musmusculus.Rmd’ using ‘UTF-8’ ... OK
       ‘quickstart.Rmd’ using ‘UTF-8’ ... OK
       ‘zebrafish.Rmd’ using ‘UTF-8’ ... OK
       ‘FELLA.Rnw’ ... failed
     ERROR
    Errors in running code in vignettes:
    when running code in ‘FELLA.Rnw’
      ...
    [19] M00075  --2.4.1.68  hsa00512--2.4.99.3  hsa05231--2.7.1.32 
    + ... omitted several edges
    
    > g.go <- addGOToGraph(graph = g, GOterm = "GO:0005739", 
    +     godata.options = list(OrgDb = "org.Hs.eg.db", ont = "CC"), 
    +     mart.options = list( .... [TRUNCATED] 
    
      When sourcing ‘FELLA.R’:
    Error: Package GOSemSim must be installed to add GO semantic similarity
    Execution halted
    ```

*   checking package dependencies ... NOTE
    ```
    Packages suggested but not available for checking:
      ‘org.Hs.eg.db’ ‘org.Mm.eg.db’
    ```

*   checking re-building of vignette outputs ... NOTE
    ```
    Error in re-building vignettes:
      ...
    Quitting from lines 42-67 (musmusculus.Rmd) 
    Error: processing vignette 'musmusculus.Rmd' failed with diagnostics:
    there is no package called 'org.Mm.eg.db'
    Execution halted
    ```

# fingertipsR

Version: 0.2.2

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘purrr’
      All declared Imports should be used.
    ```

# fitteR

Version: 0.1.0

## In both

*   checking package dependencies ... NOTE
    ```
    Package suggested but not available for checking: ‘ExtDist’
    ```

# fitur

Version: 0.6.1

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘rstudioapi’
      All declared Imports should be used.
    ```

# flora

Version: 0.3.0

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  7.2Mb
      sub-directories of 1Mb or more:
        R   7.1Mb
    ```

# flowAI

Version: 1.12.7

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  5.5Mb
      sub-directories of 1Mb or more:
        data   5.1Mb
    ```

# flowcatchR

Version: 1.16.0

## In both

*   checking installed package size ... NOTE
    ```
      installed size is 11.6Mb
      sub-directories of 1Mb or more:
        data   1.9Mb
        doc    9.2Mb
    ```

*   checking dependencies in R code ... NOTE
    ```
    'library' or 'require' call to ‘EBImage’ which was already attached by Depends.
      Please remove these calls from your code.
    ```

# FunChIP

Version: 1.8.0

## In both

*   checking data for ASCII and uncompressed saves ... WARNING
    ```
      
      Note: significantly better compression could be obtained
            by using R CMD build --resave-data
                old_size new_size compress
      peaks.rda    638Kb    112Kb       xz
    ```

*   checking running R code from vignettes ...
    ```
       ‘FunChIP.Rnw’ ... failed
     WARNING
    Errors in running code in vignettes:
    when running code in ‘FunChIP.Rnw’
      ...
    
    > BiocStyle::latex()
    
      When sourcing ‘FunChIP.R’:
    Error: there is no package called ‘BiocStyle’
    Execution halted
    ```

*   checking installed package size ... NOTE
    ```
      installed size is 24.4Mb
      sub-directories of 1Mb or more:
        doc       1.9Mb
        extdata  21.5Mb
    ```

*   checking for unstated dependencies in vignettes ... NOTE
    ```
    '::' or ':::' import not declared from: ‘BiocStyle’
    ```

*   checking re-building of vignette outputs ... NOTE
    ```
    Error in re-building vignettes:
      ...
    
    Error: processing vignette 'FunChIP.Rnw' failed with diagnostics:
     chunk 1 (label = style) 
    Error in loadNamespace(name) : there is no package called ‘BiocStyle’
    Execution halted
    ```

# g3viz

Version: 1.0.4

## In both

*   checking installed package size ... NOTE
    ```
      installed size is 10.4Mb
      sub-directories of 1Mb or more:
        doc   9.3Mb
    ```

# GA4GHshiny

Version: 1.4.0

## In both

*   checking tests ...
    ```
     ERROR
    Running the tests in ‘tests/testthat.R’ failed.
    Last 13 lines of output:
      2: stop(txt, domain = NA)
      
      ══ testthat results  ═══════════════════════════════════════════════════════════
      OK: 2 SKIPPED: 0 FAILED: 8
      1. Error: app works (@test-app.R#5) 
      2. Error: getGene works (@test-getGene.R#4) 
      3. Error: getGeneSymbols works (@test-getGeneSymbols.R#4) 
      4. Error: initializeReferences works (@test-initializeReferences.R#6) 
      5. Error: initializeVariantSet works (@test-initializeVariantSet.R#6) 
      6. Error: (unknown) (@test-searchVariantsByGeneSymbol.R#3) 
      7. Error: tidyVariants works with searchVariants output (@test-tidyVariants.R#6) 
      8. Error: tidyVariants works with searchVariantsByGeneSymbol output (@test-tidyVariants.R#16) 
      
      Error: testthat unit tests failed
      Execution halted
    ```

*   checking package dependencies ... NOTE
    ```
    Package suggested but not available for checking: ‘org.Hs.eg.db’
    ```

*   checking for hidden files and directories ... NOTE
    ```
    Found the following hidden files and directories:
      .travis.yml
    These were most likely included in error. See section ‘Package
    structure’ in the ‘Writing R Extensions’ manual.
    ```

# gamesGA

Version: 1.1.3.6

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘grDevices’
      All declared Imports should be used.
    ```

# gastempt

Version: 0.4.4

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  7.8Mb
      sub-directories of 1Mb or more:
        libs   7.4Mb
    ```

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘methods’ ‘rstantools’
      All declared Imports should be used.
    ```

*   checking for GNU extensions in Makefiles ... NOTE
    ```
    GNU make is a SystemRequirements.
    ```

# GDCRNATools

Version: 1.2.1

## In both

*   checking package dependencies ... ERROR
    ```
    Package required but not available: ‘org.Hs.eg.db’
    
    See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
    manual.
    ```

# genBart

Version: 1.0.1

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘NMF’ ‘RColorBrewer’ ‘VennDiagram’ ‘clValid’ ‘data.table’ ‘grid’
      ‘gtools’ ‘pca3d’ ‘rmarkdown’ ‘scales’ ‘shinydashboard’ ‘shinyjs’
      ‘statmod’ ‘stringr’
      All declared Imports should be used.
    ```

# GeneNetworkBuilder

Version: 1.24.1

## In both

*   checking re-building of vignette outputs ... WARNING
    ```
    Error in re-building vignettes:
      ...
    Error: processing vignette 'GeneNetworkBuilder_vignettes.Rmd' failed with diagnostics:
    there is no package called ‘BiocStyle’
    Execution halted
    ```

*   checking installed package size ... NOTE
    ```
      installed size is 13.4Mb
      sub-directories of 1Mb or more:
        data          2.8Mb
        doc           8.4Mb
        htmlwidgets   1.8Mb
    ```

# GerminaR

Version: 1.2

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘DT’ ‘shinydashboard’
      All declared Imports should be used.
    ```

# ggedit

Version: 0.3.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘magrittr’
      All declared Imports should be used.
    ```

# ggExtra

Version: 0.8

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘grDevices’
      All declared Imports should be used.
    ```

# ggplotAssist

Version: 0.1.3

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘gcookbook’ ‘ggthemes’ ‘moonBook’ ‘tidyverse’
      All declared Imports should be used.
    ```

# ggquickeda

Version: 0.1.3

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘DT’ ‘Formula’ ‘GGally’ ‘Hmisc’ ‘colourpicker’ ‘dplyr’ ‘ggpmisc’
      ‘ggpubr’ ‘ggrepel’ ‘ggstance’ ‘grDevices’ ‘gridExtra’ ‘lazyeval’
      ‘markdown’ ‘plotly’ ‘quantreg’ ‘rlang’ ‘shinyjs’ ‘survminer’ ‘table1’
      ‘tidyr’
      All declared Imports should be used.
    ```

# googleAuthR

Version: 0.7.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘R6’
      All declared Imports should be used.
    ```

# gQTLstats

Version: 1.14.1

## In both

*   checking package dependencies ... ERROR
    ```
    Package required but not available: ‘Homo.sapiens’
    
    Packages suggested but not available for checking:
      ‘geuvPack’ ‘geuvStore2’ ‘org.Hs.eg.db’
    
    See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
    manual.
    ```

# gridsampler

Version: 0.6

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘BiasedUrn’
      All declared Imports should be used.
    ```

# GSCA

Version: 2.12.0

## In both

*   checking package dependencies ... NOTE
    ```
    Depends: includes the non-default packages:
      ‘shiny’ ‘sp’ ‘gplots’ ‘ggplot2’ ‘reshape2’ ‘RColorBrewer’ ‘rhdf5’
    Adding so many packages to the search path is excessive and importing
    selectively is preferable.
    ```

*   checking dependencies in R code ... NOTE
    ```
    'library' or 'require' calls in package code:
      ‘Affyhgu133A2Expr’ ‘Affyhgu133Plus2Expr’ ‘Affyhgu133aExpr’
      ‘Affymoe4302Expr’
      Please use :: or requireNamespace() instead.
      See section 'Suggested packages' in the 'Writing R Extensions' manual.
    ```

*   checking R code for possible problems ... NOTE
    ```
    ...
    GSCAplot: no visible global function definition for ‘title’
    GSCAplot: no visible global function definition for ‘dev.off’
    annotatePeaks: no visible binding for global variable ‘allreffile’
    tabSearch: no visible global function definition for ‘data’
    tabSearch: no visible binding for global variable ‘Affyhgu133aExprtab’
    tabSearch: no visible binding for global variable ‘Affymoe4302Exprtab’
    tabSearch: no visible binding for global variable ‘Affyhgu133A2Exprtab’
    tabSearch: no visible binding for global variable
      ‘Affyhgu133Plus2Exprtab’
    Undefined global functions or variables:
      Affyhgu133A2Exprtab Affyhgu133Plus2Exprtab Affyhgu133aExprtab
      Affymoe4302Exprtab P.value SampleType Var1 Var2 allreffile
      colorRampPalette data dev.off fisher.test geneid hist par pdf qnorm
      quantile sd str t.stat t.test title value variable write.csv
      write.table
    Consider adding
      importFrom("grDevices", "colorRampPalette", "dev.off", "pdf")
      importFrom("graphics", "hist", "par", "title")
      importFrom("stats", "fisher.test", "qnorm", "quantile", "sd", "t.test")
      importFrom("utils", "data", "str", "write.csv", "write.table")
    to your NAMESPACE file.
    ```

# GSVA

Version: 1.30.0

## In both

*   checking running R code from vignettes ...
    ```
       ‘GSVA.Rnw’ using ‘latin1’ ... failed
     WARNING
    Errors in running code in vignettes:
    when running code in ‘GSVA.Rnw’
      ...
    The following object is masked from ‘package:XML’:
    
        addNode
    
    
    > library(GSVAdata)
    
      When sourcing ‘GSVA.R’:
    Error: there is no package called ‘GSVAdata’
    Execution halted
    ```

*   checking package dependencies ... NOTE
    ```
    Package suggested but not available for checking: ‘GSVAdata’
    ```

*   checking re-building of vignette outputs ... NOTE
    ```
    ...
    Loading required package: XML
    
    Attaching package: ‘XML’
    
    The following object is masked from ‘package:tools’:
    
        toHTML
    
    Loading required package: graph
    
    Attaching package: ‘graph’
    
    The following object is masked from ‘package:XML’:
    
        addNode
    
    
    Error: processing vignette 'GSVA.Rnw' failed with diagnostics:
     chunk 4 
    Error in library(GSVAdata) : there is no package called ‘GSVAdata’
    Execution halted
    ```

# highcharter

Version: 0.7.0

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  8.8Mb
      sub-directories of 1Mb or more:
        doc           3.7Mb
        htmlwidgets   4.0Mb
    ```

# ideal

Version: 1.6.1

## In both

*   checking package dependencies ... ERROR
    ```
    Package required but not available: ‘GO.db’
    
    Packages suggested but not available for checking:
      ‘airway’ ‘org.Hs.eg.db’ ‘TxDb.Hsapiens.UCSC.hg38.knownGene’
    
    See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
    manual.
    ```

# idefix

Version: 0.3.3

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘MASS’ ‘gtools’ ‘maxLik’
      All declared Imports should be used.
    ```

*   checking Rd cross-references ... NOTE
    ```
    Packages unavailable to check Rd xrefs: ‘bayesm’, ‘ChoiceModelR’, ‘RSGHB’, ‘Rchoice’
    ```

# idem

Version: 4.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘rstantools’
      All declared Imports should be used.
    ```

*   checking for GNU extensions in Makefiles ... NOTE
    ```
    GNU make is a SystemRequirements.
    ```

# IMWatson

Version: 0.5.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘R6’ ‘V8’ ‘assertive’ ‘shinydashboard’
      All declared Imports should be used.
    ```

# INDperform

Version: 0.2.0

## Newly fixed

*   checking installed package size ... NOTE
    ```
      installed size is  5.0Mb
      sub-directories of 1Mb or more:
        data   3.5Mb
        help   1.1Mb
    ```

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘lazyeval’
      All declared Imports should be used.
    ```

# inlabru

Version: 2.1.9

## In both

*   checking package dependencies ... NOTE
    ```
    Package suggested but not available for checking: ‘INLA’
    ```

*   checking Rd cross-references ... NOTE
    ```
    Package unavailable to check Rd xrefs: ‘INLA’
    ```

# INSPEcT

Version: 1.12.2

## In both

*   checking package dependencies ... ERROR
    ```
    Package required but not available: ‘TxDb.Mmusculus.UCSC.mm9.knownGene’
    
    See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
    manual.
    ```

# interactiveDisplay

Version: 1.20.0

## In both

*   checking dependencies in R code ... WARNING
    ```
    '::' or ':::' import not declared from: ‘.interactiveDisplayBase’
    ```

*   checking package dependencies ... NOTE
    ```
    Packages suggested but not available for checking: ‘hgu95av2.db’ ‘GO.db’
    
    Package which this enhances but not available for checking: ‘rstudio’
    ```

*   checking R code for possible problems ... NOTE
    ```
    ...
      for global variable ‘Var1’
    display,RangedSummarizedExperiment : <anonymous>: no visible binding
      for global variable ‘Var2’
    display,RangedSummarizedExperiment : <anonymous>: no visible binding
      for global variable ‘value’
    Undefined global functions or variables:
      AnnotationTrack GO.db GRanges GRangesList GenomeAxisTrack IRanges
      IdeogramTrack MRcounts Var1 Var2 as.dendrogram assays cim
      colorRampPalette coord_flip cutree dendrapply dev.off dist
      elementMetadata experimentData exprs fData hclust installed.packages
      is.leaf layout_circle legend libSize mcols pData plot plotFeature
      plotOrd plotTracks png rainbow ranges rowRanges seqlengths
      seqlengths<- seqlevels<- seqnames ucscGenomes value
    Consider adding
      importFrom("grDevices", "colorRampPalette", "dev.off", "png",
                 "rainbow")
      importFrom("graphics", "legend", "plot")
      importFrom("stats", "as.dendrogram", "cutree", "dendrapply", "dist",
                 "hclust", "is.leaf")
      importFrom("utils", "installed.packages")
    to your NAMESPACE file.
    ```

# interactiveDisplayBase

Version: 1.20.0

## In both

*   checking dependencies in R code ... WARNING
    ```
    'loadNamespace' or 'requireNamespace' call not declared from: ‘BiocManager’
    ```

*   checking R code for possible problems ... NOTE
    ```
    .usePackage: no visible global function definition for
      ‘install.packages’
    .usePackage: no visible global function definition for
      ‘installed.packages’
    Undefined global functions or variables:
      install.packages installed.packages
    Consider adding
      importFrom("utils", "install.packages", "installed.packages")
    to your NAMESPACE file.
    ```

# interAdapt

Version: 0.1

## In both

*   checking DESCRIPTION meta-information ... NOTE
    ```
    Malformed Description field: should contain one or more complete sentences.
    ```

*   checking R code for possible problems ... NOTE
    ```
    ...
    compute_design_performance : expected_duration_plot: no visible global
      function definition for ‘legend’
    compute_design_performance : boundary_adapt_plot: no visible global
      function definition for ‘matplot’
    compute_design_performance : boundary_adapt_plot: no visible global
      function definition for ‘legend’
    compute_design_performance : boundary_standard_H0C_plot: no visible
      global function definition for ‘matplot’
    compute_design_performance : boundary_standard_H0C_plot: no visible
      global function definition for ‘legend’
    compute_design_performance : boundary_standard_H01_plot: no visible
      global function definition for ‘matplot’
    compute_design_performance : boundary_standard_H01_plot: no visible
      global function definition for ‘legend’
    Undefined global functions or variables:
      legend lines matplot plot read.csv rnorm
    Consider adding
      importFrom("graphics", "legend", "lines", "matplot", "plot")
      importFrom("stats", "rnorm")
      importFrom("utils", "read.csv")
    to your NAMESPACE file.
    ```

# ipumsr

Version: 0.4.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘R6’
      All declared Imports should be used.
    ```

# iSEE

Version: 1.2.3

## In both

*   checking examples ... ERROR
    ```
    Running examples in ‘iSEE-Ex.R’ failed
    The error most likely occurred in:
    
    > ### Name: annotateEnsembl
    > ### Title: Annotation via ENSEMBL database
    > ### Aliases: annotateEnsembl
    > 
    > ### ** Examples
    > 
    > library(scRNAseq)
    Error in library(scRNAseq) : there is no package called ‘scRNAseq’
    Execution halted
    ```

*   checking tests ...
    ```
     ERROR
    Running the tests in ‘tests/testthat.R’ failed.
    Last 13 lines of output:
      
      The following objects are masked from 'package:base':
      
          aperm, apply
      
      Loading required package: SingleCellExperiment
      > 
      > test_check("iSEE")
      Loading required package: scRNAseq
      Error in eval(exprs, env) : require(scRNAseq) is not TRUE
      Calls: test_check ... source_dir -> lapply -> FUN -> eval -> eval -> stopifnot
      In addition: Warning message:
      In library(package, lib.loc = lib.loc, character.only = TRUE, logical.return = TRUE,  :
        there is no package called 'scRNAseq'
      Execution halted
    ```

*   checking re-building of vignette outputs ... WARNING
    ```
    ...
    The following objects are masked from 'package:Biobase':
    
        anyMissing, rowMedians
    
    Loading required package: BiocParallel
    
    Attaching package: 'DelayedArray'
    
    The following objects are masked from 'package:matrixStats':
    
        colMaxs, colMins, colRanges, rowMaxs, rowMins, rowRanges
    
    The following objects are masked from 'package:base':
    
        aperm, apply
    
    Loading required package: SingleCellExperiment
    Quitting from lines 79-82 (basic.Rmd) 
    Error: processing vignette 'basic.Rmd' failed with diagnostics:
    there is no package called 'scRNAseq'
    Execution halted
    ```

*   checking package dependencies ... NOTE
    ```
    Packages suggested but not available for checking:
      ‘scRNAseq’ ‘org.Mm.eg.db’
    ```

*   checking installed package size ... NOTE
    ```
      installed size is 17.9Mb
      sub-directories of 1Mb or more:
        doc  17.1Mb
    ```

*   checking dependencies in R code ... NOTE
    ```
    Unexported object imported by a ':::' call: ‘S4Vectors:::selectSome’
      See the note in ?`:::` about the use of this operator.
    ```

# ivygapSE

Version: 1.4.0

## In both

*   checking re-building of vignette outputs ... WARNING
    ```
    Error in re-building vignettes:
      ...
    Error: processing vignette 'ivygapSE.Rmd' failed with diagnostics:
    there is no package called ‘BiocStyle’
    Execution halted
    ```

*   checking installed package size ... NOTE
    ```
      installed size is 16.6Mb
      sub-directories of 1Mb or more:
        data  13.9Mb
        doc    2.4Mb
    ```

*   checking R code for possible problems ... NOTE
    ```
    exprByType: no visible binding for global variable ‘ivySE’
    ivyGlimpse: no visible binding for global variable ‘ivySE’
    ivyGlimpse : server: no visible binding for global variable ‘ivySE’
    Undefined global functions or variables:
      ivySE
    ```

# jpmesh

Version: 1.1.2

## In both

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 176 marked UTF-8 strings
    ```

# jpndistrict

Version: 0.3.2

## In both

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 502 marked UTF-8 strings
    ```

# kokudosuuchi

Version: 0.4.2

## In both

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 52458 marked UTF-8 strings
    ```

# koRpus

Version: 0.11-5

## In both

*   checking package dependencies ... NOTE
    ```
    Packages suggested but not available for checking:
      ‘koRpus.lang.de’ ‘koRpus.lang.es’ ‘koRpus.lang.fr’ ‘koRpus.lang.it’
      ‘koRpus.lang.ru’
    
    Package which this enhances but not available for checking: ‘rkward’
    ```

# learnstats

Version: 0.1.1

## In both

*   checking R code for possible problems ... NOTE
    ```
    ...
    qqsim: no visible global function definition for ‘mtext’
    qqsim: no visible global function definition for ‘jpeg’
    qqsim: no visible global function definition for ‘dev.off’
    timeseressim: no visible global function definition for ‘rnorm’
    timeseressim: no visible global function definition for ‘par’
    timeseressim: no visible global function definition for ‘plot’
    timeseressim: no visible global function definition for ‘mtext’
    timeseressim: no visible global function definition for ‘jpeg’
    timeseressim: no visible global function definition for ‘dev.off’
    Undefined global functions or variables:
      axis dchisq dev.off dnorm dt hist jpeg legend mtext par pchisq pf
      plot pnorm polygon pt qchisq qf qqline qqnorm qt rchisq rnorm rt
      runif segments title
    Consider adding
      importFrom("grDevices", "dev.off", "jpeg")
      importFrom("graphics", "axis", "hist", "legend", "mtext", "par",
                 "plot", "polygon", "segments", "title")
      importFrom("stats", "dchisq", "dnorm", "dt", "pchisq", "pf", "pnorm",
                 "pt", "qchisq", "qf", "qqline", "qqnorm", "qt", "rchisq",
                 "rnorm", "rt", "runif")
    to your NAMESPACE file.
    ```

# levi

Version: 1.0.0

## In both

*   checking re-building of vignette outputs ... WARNING
    ```
    Error in re-building vignettes:
      ...
    Error: processing vignette 'levi.Rmd' failed with diagnostics:
    there is no package called ‘BiocStyle’
    Execution halted
    ```

*   checking R code for possible problems ... NOTE
    ```
    LEVIui: no visible global function definition for ‘is’
    levi_function: no visible binding for global variable ‘x’
    Undefined global functions or variables:
      is x
    Consider adding
      importFrom("methods", "is")
    to your NAMESPACE file (and ensure that your DESCRIPTION Imports field
    contains 'methods').
    ```

# likert

Version: 1.3.5

## In both

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 7 marked UTF-8 strings
    ```

# live

Version: 1.5.10

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘e1071’
      All declared Imports should be used.
    ```

# lmviz

Version: 0.1.1

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘shinyjs’
      All declared Imports should be used.
    ```

# mapdeck

Version: 0.2.1

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  7.4Mb
      sub-directories of 1Mb or more:
        doc           1.2Mb
        htmlwidgets   1.4Mb
        libs          3.5Mb
    ```

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘htmltools’
      All declared Imports should be used.
    ```

# mapedit

Version: 0.5.0

## In both

*   checking package dependencies ... NOTE
    ```
    Package which this enhances but not available for checking: ‘geojsonio’
    ```

# mbgraphic

Version: 1.0.0

## In both

*   checking package dependencies ... ERROR
    ```
    Package required but not available: ‘extracat’
    
    See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
    manual.
    ```

# memapp

Version: 2.12

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘DT’ ‘RColorBrewer’ ‘RODBC’ ‘dplyr’ ‘foreign’ ‘formattable’ ‘ggplot2’
      ‘haven’ ‘mem’ ‘openxlsx’ ‘plotly’ ‘readxl’ ‘shinyBS’ ‘shinydashboard’
      ‘shinydashboardPlus’ ‘shinyjs’ ‘shinythemes’ ‘stringi’ ‘stringr’
      ‘tidyr’
      All declared Imports should be used.
    ```

# memery

Version: 0.5.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘colourpicker’ ‘shinyBS’ ‘shinycssloaders’
      All declared Imports should be used.
    ```

# meta4diag

Version: 2.0.8

## In both

*   checking package dependencies ... NOTE
    ```
    Package suggested but not available for checking: ‘INLA’
    ```

# MetamapsDB

Version: 0.0.2

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘Matrix’ ‘shiny’
      All declared Imports should be used.
    ```

# MetCirc

Version: 1.12.1

## In both

*   checking tests ...
    ```
     ERROR
    Running the tests in ‘tests/runTests.R’ failed.
    Last 13 lines of output:
      ========================================
      
      > library(scales)
      > library(shiny)
      > 
      > data("sd01_outputXCMS", package = "MetCirc")
      > data("sd02_deconvoluted", package = "MetCirc")
      > data("binnedMSP", package = "MetCirc")
      > data("similarityMat", package = "MetCirc")
      > 
      > BiocGenerics:::testPackage("MetCirc")
      Error in library("RUnit", quietly = TRUE) : 
        there is no package called 'RUnit'
      Calls: <Anonymous> -> library
      Execution halted
    ```

*   checking dependencies in R code ... NOTE
    ```
    Unexported object imported by a ':::' call: ‘circlize:::get.sector.data’
      See the note in ?`:::` about the use of this operator.
    ```

# MethylAid

Version: 1.16.0

## In both

*   checking examples ... ERROR
    ```
    Running examples in ‘MethylAid-Ex.R’ failed
    The error most likely occurred in:
    
    > ### Name: summarize
    > ### Title: summarization of Illumina Human DNA Methylation array data
    > ### Aliases: summarize
    > 
    > ### ** Examples
    > 
    > library(minfiData)
    Error in library(minfiData) : there is no package called ‘minfiData’
    Execution halted
    ```

*   checking tests ...
    ```
     ERROR
    Running the tests in ‘tests/runTests.R’ failed.
    Last 13 lines of output:
      ERROR in test_summarize: Error in library(minfiData) : there is no package called 'minfiData'
      ERROR in test_visualize: Error in library(minfiData) : there is no package called 'minfiData'
      
      Test files with failing tests
      
         test_summarize.R 
           test_summarize 
      
         test_visualize.R 
           test_visualize 
      
      
      Error in BiocGenerics:::testPackage("MethylAid") : 
        unit tests failed for package MethylAid
      Execution halted
    ```

*   checking re-building of vignette outputs ... WARNING
    ```
    Error in re-building vignettes:
      ...
    Setting options('download.file.method.GEOquery'='auto')
    Setting options('GEOquery.inmemory.gpl'=FALSE)
    Quitting from lines 80-84 (MethylAid.Rnw) 
    Error: processing vignette 'MethylAid.Rnw' failed with diagnostics:
    there is no package called 'minfiData'
    Execution halted
    ```

*   checking package dependencies ... NOTE
    ```
    Packages suggested but not available for checking:
      ‘MethylAidData’ ‘minfiData’ ‘minfiDataEPIC’
    ```

# miRcomp

Version: 1.12.0

## In both

*   checking data for ASCII and uncompressed saves ... WARNING
    ```
      
      Note: significantly better compression could be obtained
            by using R CMD build --resave-data
                      old_size new_size compress
      lifetech.rda       350Kb    276Kb       xz
      qpcRb4.rda         290Kb    244Kb       xz
      qpcRb5.rda         288Kb    242Kb       xz
      qpcRdefault.rda    290Kb    242Kb       xz
      qpcRl5.rda         287Kb    239Kb       xz
      qpcRlinexp.rda     235Kb    199Kb       xz
    ```

# MLInterfaces

Version: 1.62.1

## In both

*   checking examples ... ERROR
    ```
    ...
    > #  needed to increase training set size to avoid a new randomForest condition
    > # on empty class
    > set.seed(1234)
    > X = MLearn(type~., sample.ExpressionSet[100:250,], randomForestI, 1:19, importance=TRUE )
    > library(randomForest)
    randomForest 4.6-14
    Type rfNews() to see new features/changes/bug fixes.
    
    Attaching package: ‘randomForest’
    
    The following object is masked from ‘package:Biobase’:
    
        combine
    
    The following object is masked from ‘package:BiocGenerics’:
    
        combine
    
    > library(hgu95av2.db)
    Error in library(hgu95av2.db) : there is no package called ‘hgu95av2.db’
    Execution halted
    ```

*   checking tests ...
    ```
     ERROR
    Running the tests in ‘tests/runTests.R’ failed.
    Last 13 lines of output:
          Vignettes contain introductory material; view with
          'browseVignettes()'. To cite Bioconductor, see
          'citation("Biobase")', and for packages 'citation("pkgname")'.
      
      
      Attaching package: 'S4Vectors'
      
      The following object is masked from 'package:base':
      
          expand.grid
      
      Error in library("RUnit", quietly = TRUE) : 
        there is no package called 'RUnit'
      Calls: <Anonymous> -> library
      Execution halted
    ```

*   checking running R code from vignettes ...
    ```
    ...
      B:M  10  35   1   4
      O:F   8   0  38   4
      O:M   3   3   0  44
    
    > library("ALL")
    
      When sourcing ‘MLprac2_2.R’:
    Error: there is no package called ‘ALL’
    Execution halted
    when running code in ‘xvalComputerClusters.Rnw’
      ...
        expand.grid
    
    Loading required package: XML
    Loading required package: cluster
    
    > library(golubEsets)
    
      When sourcing ‘xvalComputerClusters.R’:
    Error: there is no package called ‘golubEsets’
    Execution halted
    ```

*   checking package dependencies ... NOTE
    ```
    Packages suggested but not available for checking:
      ‘ALL’ ‘hgu95av2.db’ ‘hu6800.db’ ‘golubEsets’
    ```

*   checking dependencies in R code ... NOTE
    ```
    Unexported objects imported by ':::' calls:
      ‘MASS:::predict.lda’ ‘ada:::predict.ada’ ‘e1071:::predict.svm’
      ‘rpart:::predict.rpart’ ‘stats:::plot.hclust’
      See the note in ?`:::` about the use of this operator.
    ```

*   checking R code for possible problems ... NOTE
    ```
    hclustWidget : <anonymous>: no visible global function definition for
      ‘:=’
    hclustWidget : <anonymous>: no visible binding for global variable
      ‘key’
    Undefined global functions or variables:
      := key
    ```

*   checking Rd files ... NOTE
    ```
    prepare_Rd: plspinHcube.Rd:17-19: Dropping empty section \details
    ```

*   checking re-building of vignette outputs ... NOTE
    ```
    ...
    
    Attaching package: ‘S4Vectors’
    
    The following object is masked from ‘package:base’:
    
        expand.grid
    
    Loading required package: XML
    
    Attaching package: ‘XML’
    
    The following object is masked from ‘package:tools’:
    
        toHTML
    
    Loading required package: cluster
    
    Error: processing vignette 'MLInterfaces.Rnw' failed with diagnostics:
     chunk 1 
    Error in library(golubEsets) : there is no package called ‘golubEsets’
    Execution halted
    ```

# MMDiff2

Version: 1.10.0

## In both

*   checking package dependencies ... NOTE
    ```
    Package suggested but not available for checking: ‘BSgenome.Mmusculus.UCSC.mm9’
    ```

*   checking for hidden files and directories ... NOTE
    ```
    Found the following hidden files and directories:
      .BBSoptions
    These were most likely included in error. See section ‘Package
    structure’ in the ‘Writing R Extensions’ manual.
    ```

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘methods’
      All declared Imports should be used.
    ```

*   checking R code for possible problems ... NOTE
    ```
    DBAmmd: no visible global function definition for ‘new’
    getReads: no visible global function definition for ‘IRangesList’
    Undefined global functions or variables:
      IRangesList new
    Consider adding
      importFrom("methods", "new")
    to your NAMESPACE file (and ensure that your DESCRIPTION Imports field
    contains 'methods').
    ```

# MNLR

Version: 0.1.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘caret’ ‘datasets’ ‘e1071’ ‘nnet’ ‘shiny’ ‘stats’
      All declared Imports should be used.
    ```

# MODIStsp

Version: 1.3.8

## In both

*   checking package dependencies ... ERROR
    ```
    Package required but not available: ‘gWidgetsRGtk2’
    
    See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
    manual.
    ```

# MSGFgui

Version: 1.16.1

## In both

*   checking dependencies in R code ... NOTE
    ```
    Package in Depends field not imported from: ‘xlsx’
      These packages need to be imported from (in the NAMESPACE file)
      for when this namespace is loaded but not attached.
    ```

*   checking R code for possible problems ... NOTE
    ```
    ...
    renderMzID: no visible global function definition for ‘modifications’
    renderMzID: no visible global function definition for ‘database’
    server: no visible global function definition for ‘scans’
    server : <anonymous>: no visible global function definition for
      ‘createWorkbook’
    server : <anonymous>: no visible global function definition for
      ‘createSheet’
    server : <anonymous>: no visible global function definition for
      ‘addDataFrame’
    server : <anonymous>: no visible global function definition for
      ‘saveWorkbook’
    server : <anonymous>: no visible global function definition for
      ‘write.table’
    Undefined global functions or variables:
      addDataFrame createSheet createWorkbook database density dnorm loess
      modifications optimize peptides predict read.csv saveWorkbook scans
      write.table
    Consider adding
      importFrom("stats", "density", "dnorm", "loess", "optimize", "predict")
      importFrom("utils", "read.csv", "write.table")
    to your NAMESPACE file.
    ```

# MSnbase

Version: 2.8.3

## In both

*   checking examples ... ERROR
    ```
    Running examples in ‘MSnbase-Ex.R’ failed
    The error most likely occurred in:
    
    > ### Name: FeatComp-class
    > ### Title: Class '"FeatComp"'
    > ### Aliases: FeatComp-class compfnames-methods
    > ###   compfnames,MSnSet,MSnSet-method compfnames,list,missing-method
    > ###   compfnames show,FeatComp-method names,FeatComp-method
    > ###   common,FeatComp-method common,methods common unique1,FeatComp-method
    > ###   unique1,methods unique1 unique2,FeatComp-method unique2,methods
    > ###   unique2
    > ### Keywords: classes
    > 
    > ### ** Examples
    > 
    > library("pRolocdata")
    Error in library("pRolocdata") : there is no package called ‘pRolocdata’
    Execution halted
    ```

*   checking tests ...
    ```
     ERROR
    Running the tests in ‘tests/testthat.R’ failed.
    Last 13 lines of output:
      ══ testthat results  ═══════════════════════════════════════════════════════════
      OK: 3136 SKIPPED: 9 FAILED: 11
      1. Error: MSnSet coersion (@test_MSnSet.R#25) 
      2. Error: commonFeatureNames works with lists or MSnSetLists (@test_MSnSet.R#358) 
      3. Error: keeping common features (@test_MSnSet.R#377) 
      4. Error: nFeatures are added correctly (@test_MSnSet.R#458) 
      5. Error: (unknown) (@test_average.R#1) 
      6. Error: Feature variable selection (@test_fdata-selection.R#4) 
      7. Error: (unknown) (@test_foi.R#1) 
      8. Error: readMSnSet2: rownames and fnames (@test_io.R#84) 
      9. Error: (unknown) (@test_nadata.R#2) 
      1. ...
      
      Error: testthat unit tests failed
      Execution halted
    ```

*   checking re-building of vignette outputs ... WARNING
    ```
    Error in re-building vignettes:
      ...
    Warning in has_utility("convert", "ImageMagick") :
      ImageMagick not installed or not in PATH
    Warning: file MRM-standmix-5.mzML.gz contains multiple chromatograms with identical polarity, precursor and product m/z values
    Warning: Removed 8 rows containing non-finite values (stat_boxplot).
    Warning: Removed 7 rows containing non-finite values (stat_smooth).
    Warning: Removed 7 rows containing missing values (geom_point).
    Quitting from lines 1747-1752 (v01-MSnbase-demo.Rmd) 
    Error: processing vignette 'v01-MSnbase-demo.Rmd' failed with diagnostics:
    object 'dunkley2006' not found
    Execution halted
    ```

*   checking package dependencies ... NOTE
    ```
    Package suggested but not available for checking: ‘pRolocdata’
    ```

*   checking installed package size ... NOTE
    ```
      installed size is 13.3Mb
      sub-directories of 1Mb or more:
        R      2.0Mb
        data   2.1Mb
        doc    7.8Mb
    ```

*   checking DESCRIPTION meta-information ... NOTE
    ```
    Authors@R field gives more than one person with maintainer role:
      Laurent Gatto <lg390@cam.ac.uk> [aut, cre]
      Johannes Rainer <Johannes.Rainer@eurac.edu> [aut, cre]
      Sebastian Gibb <mail@sebastiangibb.de> [aut, cre]
    ```

*   checking dependencies in R code ... NOTE
    ```
    Unexported objects imported by ':::' calls:
      ‘Biobase:::.showAnnotatedDataFrame’ ‘MALDIquant:::.estimateNoise’
      ‘MALDIquant:::.localMaxima’ ‘MALDIquant:::.movingAverage’
      ‘MALDIquant:::.savitzkyGolay’
      ‘S4Vectors:::makeClassinfoRowForCompactPrinting’
      ‘S4Vectors:::makePrettyMatrixForCompactPrinting’
      ‘mzR:::.hasChromatograms’ ‘mzR:::.hasSpectra’
      See the note in ?`:::` about the use of this operator.
    ```

# MuChPoint

Version: 0.6.1

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘Matrix’ ‘capushe’ ‘shiny’
      All declared Imports should be used.
    ```

# nbc4va

Version: 1.1

## In both

*   checking package dependencies ... NOTE
    ```
    Package which this enhances but not available for checking: ‘openVA’
    ```

# NDP

Version: 0.1.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘shiny’
      All declared Imports should be used.
    ```

# neo4r

Version: 0.1.1

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘igraph’ ‘rlang’ ‘tidyselect’
      All declared Imports should be used.
    ```

# objectremover

Version: 0.6.4

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘rstudioapi’
      All declared Imports should be used.
    ```

# omicplotR

Version: 1.2.1

## In both

*   checking for hidden files and directories ... NOTE
    ```
    Found the following hidden files and directories:
      .github
    These were most likely included in error. See section ‘Package
    structure’ in the ‘Writing R Extensions’ manual.
    ```

*   checking R code for possible problems ... NOTE
    ```
    omicplotr.colvec: no visible global function definition for ‘col2rgb’
    Undefined global functions or variables:
      col2rgb
    Consider adding
      importFrom("grDevices", "col2rgb")
    to your NAMESPACE file.
    ```

# oneSENSE

Version: 1.4.1

## In both

*   checking examples ... WARNING
    ```
    Found the following significant warnings:
    
      Warning: 'export' is deprecated.
    Deprecated functions may be defunct as soon as of the next release of
    R.
    See ?Deprecated.
    ```

*   checking top-level files ... NOTE
    ```
    File
      LICENSE
    is not mentioned in the DESCRIPTION file.
    ```

# ontoProc

Version: 1.4.0

## In both

*   checking examples ... ERROR
    ```
    Running examples in ‘ontoProc-Ex.R’ failed
    The error most likely occurred in:
    
    > ### Name: cellTypeToGO
    > ### Title: utilities for approximate matching of cell type terms to GO
    > ###   categories and annotations
    > ### Aliases: cellTypeToGO cellTypeToGenes
    > 
    > ### ** Examples
    > 
    > data(allGOterms)
    > library(org.Hs.eg.db)
    Error in library(org.Hs.eg.db) : 
      there is no package called ‘org.Hs.eg.db’
    Execution halted
    ```

*   checking tests ...
    ```
     ERROR
    Running the tests in ‘tests/test.R’ failed.
    Last 13 lines of output:
      Loading required package: ontologyIndex
      > library(testthat)
      > 
      > test_check("ontoProc")
      ── 1. Error: cellTypeToGenes yields genes (@testAll.R#18)  ─────────────────────
      there is no package called 'org.Hs.eg.db'
      1: library(org.Hs.eg.db) at testthat/testAll.R:18
      2: stop(txt, domain = NA)
      
      ══ testthat results  ═══════════════════════════════════════════════════════════
      OK: 7 SKIPPED: 0 FAILED: 1
      1. Error: cellTypeToGenes yields genes (@testAll.R#18) 
      
      Error: testthat unit tests failed
      Execution halted
    ```

*   checking re-building of vignette outputs ... WARNING
    ```
    Error in re-building vignettes:
      ...
    Quitting from lines 21-29 (ontoProc.Rmd) 
    Error: processing vignette 'ontoProc.Rmd' failed with diagnostics:
    there is no package called 'org.Mm.eg.db'
    Execution halted
    ```

*   checking package dependencies ... NOTE
    ```
    Packages suggested but not available for checking:
      ‘org.Hs.eg.db’ ‘org.Mm.eg.db’
    ```

*   checking installed package size ... NOTE
    ```
      installed size is 28.0Mb
      sub-directories of 1Mb or more:
        ontoRda  26.9Mb
    ```

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 162 marked UTF-8 strings
    ```

# openPrimeRui

Version: 1.4.1

## In both

*   checking for hidden files and directories ... NOTE
    ```
    Found the following hidden files and directories:
      .travis.yml
    These were most likely included in error. See section ‘Package
    structure’ in the ‘Writing R Extensions’ manual.
    ```

*   checking dependencies in R code ... NOTE
    ```
    Package in Depends field not imported from: ‘openPrimeR’
      These packages need to be imported from (in the NAMESPACE file)
      for when this namespace is loaded but not attached.
    ```

# oppr

Version: 0.0.2

## In both

*   checking package dependencies ... NOTE
    ```
    Packages suggested but not available for checking: ‘gurobi’ ‘Rsymphony’
    ```

# pairsD3

Version: 0.1.0

## In both

*   checking R code for possible problems ... NOTE
    ```
    pairsD3: no visible global function definition for ‘gray.colors’
    Undefined global functions or variables:
      gray.colors
    Consider adding
      importFrom("grDevices", "gray.colors")
    to your NAMESPACE file.
    ```

# PanVizGenerator

Version: 1.10.0

## In both

*   checking for hidden files and directories ... NOTE
    ```
    Found the following hidden files and directories:
      .travis.yml
    These were most likely included in error. See section ‘Package
    structure’ in the ‘Writing R Extensions’ manual.
    ```

# PathoStat

Version: 1.8.4

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘ComplexHeatmap’ ‘RColorBrewer’
      All declared Imports should be used.
    ```

# pcadapt

Version: 4.1.0

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  5.6Mb
      sub-directories of 1Mb or more:
        doc       1.9Mb
        extdata   2.7Mb
    ```

# pcaExplorer

Version: 2.8.1

## In both

*   checking package dependencies ... ERROR
    ```
    Package required but not available: ‘GO.db’
    
    Packages suggested but not available for checking: ‘airway’ ‘org.Hs.eg.db’
    
    See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
    manual.
    ```

# pepStat

Version: 1.16.0

## In both

*   checking DESCRIPTION meta-information ... NOTE
    ```
    Malformed Description field: should contain one or more complete sentences.
    ```

*   checking whether the namespace can be loaded with stated dependencies ... NOTE
    ```
    Warning: no function found corresponding to methods exports from ‘pepStat’ for: ‘end’, ‘start’
    
    A namespace must be able to be loaded with just the base namespace
    loaded: otherwise if the namespace gets loaded by a saved object, the
    session will be unable to start.
    
    Probably some imports need to be declared in the NAMESPACE file.
    ```

*   checking R code for possible problems ... NOTE
    ```
    ...
    coerce,peptideSet-ExpressionSet: no visible global function definition
      for ‘annotation’
    end,peptideSet: no visible global function definition for ‘end’
    position,peptideSet: no visible global function definition for ‘start’
    position,peptideSet: no visible global function definition for ‘end’
    start,peptideSet: no visible global function definition for ‘start’
    write.pSet,peptideSet: no visible global function definition for
      ‘start’
    write.pSet,peptideSet: no visible global function definition for ‘end’
    write.pSet,peptideSet: no visible global function definition for
      ‘write.csv’
    Undefined global functions or variables:
      annotation dev.flush dev.hold dev.interactive devAskNewPage end
      lm.fit lm.wfit mcols mcols<- median read.csv sd start write.csv
    Consider adding
      importFrom("grDevices", "dev.flush", "dev.hold", "dev.interactive",
                 "devAskNewPage")
      importFrom("stats", "end", "lm.fit", "lm.wfit", "median", "sd",
                 "start")
      importFrom("utils", "read.csv", "write.csv")
    to your NAMESPACE file.
    ```

# periscope

Version: 0.4.1

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘httr’
      All declared Imports should be used.
    ```

# phenocamr

Version: 1.1.3

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘jsonlite’ ‘memoise’
      All declared Imports should be used.
    ```

# pitchRx

Version: 1.8.2

## In both

*   checking package dependencies ... NOTE
    ```
    Package suggested but not available for checking: ‘ggsubplot’
    ```

# pivottabler

Version: 1.2.0

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  7.2Mb
      sub-directories of 1Mb or more:
        R      2.0Mb
        data   2.0Mb
        doc    3.0Mb
    ```

# plethem

Version: 0.1.7

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘V8’ ‘devtools’ ‘formatR’ ‘gdata’ ‘rhandsontable’ ‘shinythemes’
      ‘sqldf’
      All declared Imports should be used.
    ```

# plotGrouper

Version: 1.0.1

## In both

*   checking R code for possible problems ... NOTE
    ```
    gplot: no visible binding for global variable ‘max_value’
    gplot: no visible binding for global variable ‘max_error’
    Undefined global functions or variables:
      max_error max_value
    ```

# plotly

Version: 4.9.0

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  6.2Mb
      sub-directories of 1Mb or more:
        htmlwidgets   3.4Mb
    ```

# pmd

Version: 0.1.1

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘shiny’
      All declared Imports should be used.
    ```

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 62 marked UTF-8 strings
    ```

# pogos

Version: 1.2.1

## In both

*   checking re-building of vignette outputs ... WARNING
    ```
    Error in re-building vignettes:
      ...
    Error: processing vignette 'pogos.Rmd' failed with diagnostics:
    there is no package called ‘BiocStyle’
    Execution halted
    ```

*   checking R code for possible problems ... NOTE
    ```
    compoundsByCell: no visible binding for global variable ‘cell_lines_v1’
    compoundsByCell: no visible binding for global variable ‘compounds_v1’
    compoundsByCell: no visible binding for global variable ‘datasets_v1’
    lkc: no visible binding for global variable ‘cell_lines_v1’
    lkc: no visible binding for global variable ‘compounds_v1’
    lkc: no visible binding for global variable ‘datasets_v1’
    plot,DRProfSet-missing: no visible binding for global variable ‘dose’
    plot,DRProfSet-missing: no visible binding for global variable
      ‘response’
    plot,DRProfSet-missing: no visible binding for global variable ‘drug’
    plot,DRTraceSet-missing: no visible binding for global variable ‘dose’
    plot,DRTraceSet-missing: no visible binding for global variable
      ‘response’
    plot,DRTraceSet-missing: no visible binding for global variable
      ‘cell_line’
    Undefined global functions or variables:
      cell_line cell_lines_v1 compounds_v1 datasets_v1 dose drug response
    ```

# PopED

Version: 0.4.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘tidyr’
      All declared Imports should be used.
    ```

# poppr

Version: 2.8.2

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  5.1Mb
      sub-directories of 1Mb or more:
        R     2.0Mb
        doc   2.4Mb
    ```

# powdR

Version: 0.2.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘shinyWidgets’
      All declared Imports should be used.
    ```

# predictoR

Version: 1.0.4

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘DT’ ‘ROCR’ ‘ada’ ‘colourpicker’ ‘corrplot’ ‘e1071’ ‘flexdashboard’
      ‘kknn’ ‘neuralnet’ ‘randomForest’ ‘rattle’ ‘rpart’ ‘scatterplot3d’
      ‘shinyAce’ ‘shinyWidgets’ ‘shinydashboardPlus’ ‘shinyjs’ ‘tidyverse’
      ‘xgboost’ ‘zip’
      All declared Imports should be used.
    ```

# primirTSS

Version: 1.0.1

## In both

*   checking package dependencies ... ERROR
    ```
    Packages required but not available:
      ‘BSgenome.Hsapiens.UCSC.hg38’ ‘phastCons100way.UCSC.hg38’
    
    See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
    manual.
    ```

# prioritizr

Version: 4.0.3

## In both

*   checking package dependencies ... NOTE
    ```
    Packages suggested but not available for checking: ‘gurobi’ ‘Rsymphony’
    ```

# processanimateR

Version: 1.0.0

## In both

*   checking installed package size ... NOTE
    ```
      installed size is 11.1Mb
      sub-directories of 1Mb or more:
        doc           6.5Mb
        help          2.1Mb
        htmlwidgets   2.5Mb
    ```

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘zoo’
      All declared Imports should be used.
    ```

# processR

Version: 0.1.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘TH.data’ ‘jtools’ ‘modelr’ ‘prediction’ ‘rlang’ ‘tidyr’
      All declared Imports should be used.
    ```

# pRolocGUI

Version: 1.16.0

## In both

*   checking examples ... ERROR
    ```
    Running examples in ‘pRolocGUI-Ex.R’ failed
    The error most likely occurred in:
    
    > ### Name: pRolocVis
    > ### Title: Interactive visualisation of spatial proteomics data
    > ### Aliases: pRolocVis pRolocVis_aggregate pRolocVis_classify
    > ###   pRolocVis_compare pRolocVis_pca
    > 
    > ### ** Examples
    > 
    > library("pRoloc")
    > library("pRolocdata")
    Error in library("pRolocdata") : there is no package called ‘pRolocdata’
    Execution halted
    ```

*   checking re-building of vignette outputs ... WARNING
    ```
    ...
    
    
    Attaching package: 'annotate'
    
    The following object is masked from 'package:mzR':
    
        nChrom
    
    Loading required package: cluster
    Loading required package: BiocParallel
    
    This is pRoloc version 1.22.2 
      Visit https://lgatto.github.io/pRoloc/ to get started.
    
    
    This is pRolocGUI version 1.16.0
    
    Quitting from lines 77-79 (pRolocGUI.Rmd) 
    Error: processing vignette 'pRolocGUI.Rmd' failed with diagnostics:
    there is no package called 'pRolocdata'
    Execution halted
    ```

*   checking package dependencies ... NOTE
    ```
    Package suggested but not available for checking: ‘pRolocdata’
    ```

*   checking DESCRIPTION meta-information ... NOTE
    ```
    Authors@R field gives more than one person with maintainer role:
      Lisa Breckels <lms79@cam.ac.uk> [aut, cre]
      Laurent Gatto <lg390@cam.ac.uk> [aut, cre]
    ```

*   checking dependencies in R code ... NOTE
    ```
    Unexported object imported by a ':::' call: ‘pRoloc:::remap’
      See the note in ?`:::` about the use of this operator.
    ```

# psichomics

Version: 1.8.2

## In both

*   checking package dependencies ... ERROR
    ```
    Package required but not available: ‘org.Hs.eg.db’
    
    See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
    manual.
    ```

# QCA

Version: 3.4

## In both

*   checking Rd cross-references ... NOTE
    ```
    Package unavailable to check Rd xrefs: ‘cna’
    ```

# qlcData

Version: 0.2.1

## In both

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 1459 marked UTF-8 strings
    ```

# qqplotr

Version: 0.0.3

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘knitr’ ‘purrr’ ‘rmarkdown’
      All declared Imports should be used.
    ```

# questionr

Version: 0.7.0

## In both

*   checking Rd cross-references ... NOTE
    ```
    Package unavailable to check Rd xrefs: ‘Hmisc’
    ```

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 4145 marked UTF-8 strings
    ```

# R3CPET

Version: 1.14.0

## In both

*   checking package dependencies ... NOTE
    ```
    Package suggested but not available for checking: ‘org.Hs.eg.db’
    ```

*   checking installed package size ... NOTE
    ```
      installed size is  6.0Mb
      sub-directories of 1Mb or more:
        data      3.0Mb
        example   1.0Mb
    ```

*   checking DESCRIPTION meta-information ... NOTE
    ```
    Package listed in more than one of Depends, Imports, Suggests, Enhances:
      ‘methods’
    A package should be listed in only one of these fields.
    ```

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: 'BiocGenerics'
      All declared Imports should be used.
    ```

*   checking R code for possible problems ... NOTE
    ```
    ...
    .formatDAVIDResult: no visible global function definition for
      'formatList'
    .formatDAVIDResult: no visible global function definition for
      'formatGene2Gene'
    .formatDAVIDResult: no visible global function definition for
      'formatAnnotationReport'
    .get.NetworksGenes: no visible global function definition for
      'annotatePeakInBatch'
    EnsemblToHGNC: no visible global function definition for 'useMart'
    EnsemblToHGNC: no visible global function definition for 'useDataset'
    EnsemblToHGNC: no visible global function definition for 'getBM'
    EntrezToHGNC: no visible global function definition for 'useMart'
    EntrezToHGNC: no visible global function definition for 'useDataset'
    EntrezToHGNC: no visible global function definition for 'getBM'
    createServer,ChiapetExperimentData-NetworkCollection-ChromMaintainers:
      no visible global function definition for 'runApp'
    Undefined global functions or variables:
      TxDb.Hsapiens.UCSC.hg19.knownGene annotatePeakInBatch
      formatAnnotationReport formatGene2Gene formatGeneReport
      formatGeneReportFull formatList getBM org.Hs.eg.db org.Hs.egUCSCKG
      runApp select toTable useDataset useMart
    ```

# RagGrid

Version: 0.2.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘knitr’
      All declared Imports should be used.
    ```

# rAmCharts

Version: 2.1.10

## In both

*   checking installed package size ... NOTE
    ```
      installed size is 14.1Mb
      sub-directories of 1Mb or more:
        api           3.1Mb
        htmlwidgets   9.2Mb
    ```

# Rariant

Version: 1.18.0

## In both

*   checking examples ... ERROR
    ```
    ...
    > ### Aliases: tallyPlot
    > 
    > ### ** Examples
    > 
    >   library(ggbio)
    Loading required package: ggplot2
    Need specific help about ggbio? try mailing 
     the maintainer or visit http://tengfei.github.com/ggbio/
    
    Attaching package: 'ggbio'
    
    The following objects are masked from 'package:ggplot2':
    
        geom_bar, geom_rect, geom_segment, ggsave, stat_bin, stat_identity,
        xlim
    
    >   library(GenomicRanges)
    >   library(BSgenome.Hsapiens.UCSC.hg19)
    Error in library(BSgenome.Hsapiens.UCSC.hg19) : 
      there is no package called 'BSgenome.Hsapiens.UCSC.hg19'
    Execution halted
    ```

*   checking package dependencies ... NOTE
    ```
    Package suggested but not available for checking: ‘BSgenome.Hsapiens.UCSC.hg19’
    ```

*   checking installed package size ... NOTE
    ```
      installed size is  7.8Mb
      sub-directories of 1Mb or more:
        doc       2.3Mb
        extdata   5.2Mb
    ```

*   checking R code for possible problems ... NOTE
    ```
    tallyBamRegion: no visible global function definition for 'PileupParam'
    tallyBamRegion: no visible global function definition for
      'ScanBamParam'
    tallyBamRegion: no visible global function definition for 'pileup'
    Undefined global functions or variables:
      PileupParam ScanBamParam pileup
    ```

*   checking installed files from ‘inst/doc’ ... NOTE
    ```
    The following files should probably not be installed:
      ‘rariant-inspect-ci.png’, ‘rariant-inspect-shift.png’
    
    Consider the use of a .Rinstignore file: see ‘Writing R Extensions’,
    or move the vignette sources from ‘inst/doc’ to ‘vignettes’.
    ```

# rbin

Version: 0.1.1

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘utils’
      All declared Imports should be used.
    ```

# rblt

Version: 0.2.4.0

## In both

*   checking package dependencies ... ERROR
    ```
    Package required but not available: ‘h5’
    
    See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
    manual.
    ```

# rcellminer

Version: 2.4.0

## In both

*   checking package dependencies ... ERROR
    ```
    Package required but not available: ‘rcellminerData’
    
    See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
    manual.
    ```

# rCGH

Version: 1.12.0

## In both

*   checking package dependencies ... ERROR
    ```
    Packages required but not available:
      ‘TxDb.Hsapiens.UCSC.hg18.knownGene’
      ‘TxDb.Hsapiens.UCSC.hg38.knownGene’ ‘org.Hs.eg.db’
    
    See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
    manual.
    ```

# RDML

Version: 0.9-9

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  5.5Mb
      sub-directories of 1Mb or more:
        R     2.0Mb
        doc   2.4Mb
    ```

# recmap

Version: 1.0.1

## In both

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 1036 marked UTF-8 strings
    ```

# RefNet

Version: 1.18.0

## In both

*   checking tests ...
    ```
     ERROR
    Running the tests in ‘tests/runTests.R’ failed.
    Last 13 lines of output:
       
      1 Test Suite : 
      RefNet RUnit Tests - 1 test function, 1 error, 0 failures
      ERROR in /Users/barret/odrive/AmazonCloudDrive/git/rstudio/shiny/shiny/revdep/checks.noindex/RefNet/new/RefNet.Rcheck/RefNet/unitTests/test_RefNet.R: Error while sourcing  /Users/barret/odrive/AmazonCloudDrive/git/rstudio/shiny/shiny/revdep/checks.noindex/RefNet/new/RefNet.Rcheck/RefNet/unitTests/test_RefNet.R : Error in library(org.Hs.eg.db) : 
        there is no package called 'org.Hs.eg.db'
      
      Test files with failing tests
      
         test_RefNet.R 
           /Users/barret/odrive/AmazonCloudDrive/git/rstudio/shiny/shiny/revdep/checks.noindex/RefNet/new/RefNet.Rcheck/RefNet/unitTests/test_RefNet.R 
      
      
      Error in BiocGenerics:::testPackage("RefNet") : 
        unit tests failed for package RefNet
      Execution halted
    ```

*   checking running R code from vignettes ...
    ```
       ‘RefNet.Rnw’ ... failed
     WARNING
    Errors in running code in vignettes:
    when running code in ‘RefNet.Rnw’
      ...
    [30] DOI: 10.4161/cc.20402                                                            
    [31] PMCID: PMC3359123                                                                
    [32] PMID: 22580460  [Indexed for MEDLINE]                                            
    [33]                                                                                  
    
    > library(org.Hs.eg.db)
    
      When sourcing ‘RefNet.R’:
    Error: there is no package called ‘org.Hs.eg.db’
    Execution halted
    ```

*   checking package dependencies ... NOTE
    ```
    Package suggested but not available for checking: ‘org.Hs.eg.db’
    ```

*   checking DESCRIPTION meta-information ... NOTE
    ```
    Malformed Description field: should contain one or more complete sentences.
    ```

*   checking re-building of vignette outputs ... NOTE
    ```
    ...
        ‘/Users/barret//.AnnotationHub/27766’
    downloading 0 resources
    loading from cache 
        ‘/Users/barret//.AnnotationHub/27767’
    downloading 0 resources
    loading from cache 
        ‘/Users/barret//.AnnotationHub/27768’
    downloading 0 resources
    loading from cache 
        ‘/Users/barret//.AnnotationHub/27769’
    checking for biomart access...
       does 'http://www.ensembl.org' respond?
       creating ensembl mart
       hsapiens_gene_ensembl dataset provided?
    connecting to biomart...
    
    Error: processing vignette 'RefNet.Rnw' failed with diagnostics:
     chunk 11 (label = alias) 
    Error in library(org.Hs.eg.db) : 
      there is no package called ‘org.Hs.eg.db’
    Execution halted
    ```

# ReportingTools

Version: 2.22.1

## In both

*   checking package dependencies ... ERROR
    ```
    Package required but not available: ‘PFAM.db’
    
    Packages suggested but not available for checking:
      ‘ALL’ ‘hgu95av2.db’ ‘org.Mm.eg.db’ ‘org.Sc.sgd.db’
    
    See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
    manual.
    ```

# reprex

Version: 0.2.1

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘tools’
      All declared Imports should be used.
    ```

# revtools

Version: 0.3.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘SnowballC’ ‘stringdist’
      All declared Imports should be used.
    ```

# RforProteomics

Version: 1.20.0

## In both

*   checking whether package ‘RforProteomics’ can be installed ... WARNING
    ```
    Found the following significant warnings:
      Warning: replacing previous import ‘MSnbase::plot’ by ‘graphics::plot’ when loading ‘RforProteomics’
    See ‘/Users/barret/odrive/AmazonCloudDrive/git/rstudio/shiny/shiny/revdep/checks.noindex/RforProteomics/new/RforProteomics.Rcheck/00install.out’ for details.
    ```

*   checking re-building of vignette outputs ... WARNING
    ```
    ...
    The following object is masked from 'package:tools':
    
        toHTML
    
    
    Attaching package: 'annotate'
    
    The following object is masked from 'package:mzR':
    
        nChrom
    
    Loading required package: cluster
    Loading required package: BiocParallel
    
    This is pRoloc version 1.22.2 
      Visit https://lgatto.github.io/pRoloc/ to get started.
    
    Quitting from lines 29-47 (RProtVis.Rmd) 
    Error: processing vignette 'RProtVis.Rmd' failed with diagnostics:
    there is no package called 'pRolocdata'
    Execution halted
    ```

*   checking package dependencies ... NOTE
    ```
    Packages suggested but not available for checking:
      ‘synapterdata’ ‘GO.db’ ‘org.Hs.eg.db’ ‘pRolocdata’
    ```

*   checking installed package size ... NOTE
    ```
      installed size is 11.7Mb
      sub-directories of 1Mb or more:
        doc  10.8Mb
    ```

# rgl

Version: 0.100.19

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  8.0Mb
      sub-directories of 1Mb or more:
        doc     3.6Mb
        fonts   1.5Mb
    ```

*   checking Rd cross-references ... NOTE
    ```
    Packages unavailable to check Rd xrefs: ‘heplots’, ‘tkrgl’
    ```

# rhandsontable

Version: 0.3.7

## In both

*   checking installed package size ... NOTE
    ```
      installed size is 11.5Mb
      sub-directories of 1Mb or more:
        doc          10.2Mb
        htmlwidgets   1.2Mb
    ```

# RLumShiny

Version: 0.2.2

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘RCarb’ ‘rmarkdown’ ‘shinyjs’
      All declared Imports should be used.
    ```

# rmarkdown

Version: 1.12

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  9.0Mb
      sub-directories of 1Mb or more:
        rmd   8.2Mb
    ```

# rmd

Version: 0.1.4

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘blogdown’ ‘bookdown’ ‘bookdownplus’ ‘citr’ ‘pagedown’ ‘rticles’
      ‘tinytex’ ‘xaringan’
      All declared Imports should be used.
    ```

# RnBeads

Version: 2.0.1

## In both

*   checking tests ...
    ```
     ERROR
    Running the tests in ‘tests/runTests.R’ failed.
    Last 13 lines of output:
       
      1 Test Suite : 
      RnBeads RUnit Tests - 9 test functions, 1 error, 0 failures
      ERROR in /Users/barret/odrive/AmazonCloudDrive/git/rstudio/shiny/shiny/revdep/checks.noindex/RnBeads/new/RnBeads.Rcheck/RnBeads/unitTests/test_differential.R: Error while sourcing  /Users/barret/odrive/AmazonCloudDrive/git/rstudio/shiny/shiny/revdep/checks.noindex/RnBeads/new/RnBeads.Rcheck/RnBeads/unitTests/test_differential.R : Error in logger.error(txt) : 
        Missing required package missMethyl or its dependency
      
      Test files with failing tests
      
         test_differential.R 
           /Users/barret/odrive/AmazonCloudDrive/git/rstudio/shiny/shiny/revdep/checks.noindex/RnBeads/new/RnBeads.Rcheck/RnBeads/unitTests/test_differential.R 
      
      
      Error in BiocGenerics:::testPackage("RnBeads") : 
        unit tests failed for package RnBeads
      Execution halted
    ```

*   checking package dependencies ... NOTE
    ```
    Package suggested but not available for checking: ‘IlluminaHumanMethylation450kmanifest’
    
    Depends: includes the non-default packages:
      ‘BiocGenerics’ ‘S4Vectors’ ‘GenomicRanges’ ‘MASS’ ‘cluster’ ‘ff’
      ‘fields’ ‘ggplot2’ ‘gplots’ ‘gridExtra’ ‘limma’ ‘matrixStats’
      ‘illuminaio’ ‘methylumi’ ‘plyr’
    Adding so many packages to the search path is excessive and importing
    selectively is preferable.
    ```

*   checking for hidden files and directories ... NOTE
    ```
    Found the following hidden files and directories:
      .travis.yml
    These were most likely included in error. See section ‘Package
    structure’ in the ‘Writing R Extensions’ manual.
    ```

*   checking installed package size ... NOTE
    ```
      installed size is  8.6Mb
      sub-directories of 1Mb or more:
        R     3.1Mb
        doc   3.2Mb
    ```

*   checking DESCRIPTION meta-information ... NOTE
    ```
    Package listed in more than one of Depends, Imports, Suggests, Enhances:
      ‘qvalue’
    A package should be listed in only one of these fields.
    ```

*   checking whether the namespace can be loaded with stated dependencies ... NOTE
    ```
    Warning: no function found corresponding to methods exports from ‘RnBeads’ for: ‘samples’
    
    A namespace must be able to be loaded with just the base namespace
    loaded: otherwise if the namespace gets loaded by a saved object, the
    session will be unable to start.
    
    Probably some imports need to be declared in the NAMESPACE file.
    ```

*   checking dependencies in R code ... NOTE
    ```
    Unexported objects imported by ':::' calls:
      'Gviz:::.getBMFeatureMap' 'doParallel:::.options'
      'grDevices:::.smoothScatterCalcDensity'
      'minfi:::.default.450k.annotation' 'minfi:::.extractFromRGSet450k'
      'minfi:::.normalizeFunnorm450k'
      See the note in ?`:::` about the use of this operator.
    ```

*   checking R code for possible problems ... NOTE
    ```
    ...
      Density Deviance Difference DoISVA Error EstDimRMT GenomeAxisTrack ID
      IdeogramTrack IlluminaHumanMethylation450kmanifest
      IlluminaHumanMethylationEPICmanifest Index Intensity Measure
      PairsBootRefFreeEwasModel Probe RGChannelSet Rd2HTML RefFreeEwasModel
      SNP Sample Slide Target Term UcscTrack Value addSex as.profileCGH
      assayDataElement assayDataElementNames barcode bv chrom combinedRank
      combinedRank.var comma covgMedian covgPercLow covgPercUp cv.glmnet
      daglad diffmeth diffmeth.p.adj.fdr diffmeth.p.val
      dinucleotideFrequency eps expectedCounts featureData featureData<-
      featureNames featureNames<- foreach geneCounts genome<- getCN
      getDoParWorkers getGreen getManifest getMeth getRed getSex getUnmeth
      getVarCov glmnet grid.draw grid.newpage group group1 group2 i
      impute.knn is.subsegmentation k letterFrequency lme loadRegionDB
      log10FDR log10P mapToGenome mclapply mean.diff mean.quot.log2 melt
      mergeRegionDBs muted n.sites ng.2 num.sites numSites numeric.names
      oddsRatios p.vals.t.na.adj pData percent_format phenoData phenoData<-
      plotTracks preprocessSWAN pvalues qvalue refText reg.type region.size
      registerDoParallel relative.coord report runLOLA samples seqlengths
      seqlevels<- sigCategories sites2ignore size solve.QP stopCluster sva
      target tsne type types universeCounts useMart v var.diff varFit
      varLabels x xmlValue y yint
    ```

# rosr

Version: 0.0.6

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘bookdown’ ‘rstudioapi’ ‘tinytex’
      All declared Imports should be used.
    ```

# rpostgisLT

Version: 0.6.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘htmltools’
      All declared Imports should be used.
    ```

# Rqc

Version: 1.16.2

## In both

*   checking for hidden files and directories ... NOTE
    ```
    Found the following hidden files and directories:
      .travis.yml
    These were most likely included in error. See section ‘Package
    structure’ in the ‘Writing R Extensions’ manual.
    ```

# RQuantLib

Version: 0.4.8

## In both

*   checking examples ... ERROR
    ```
    ...
    +                fixFreq="Annual",
    +                floatFreq="Semiannual")
    + 
    + setEvaluationDate(as.Date("2016-2-16"))               
    + times<-times <- seq(0,14.75,.25)
    + dcurve <- DiscountCurve(params, tsQuotes, times=times,legparams)
    + 
    + # Price the Bermudan swaption
    + pricing <- AffineSwaption(params, dcurve,swaptionMaturities, swapTenors, volMatrix,legparams)
    + summary(pricing)
    + 
    + }    
    
     *** caught segfault ***
    address 0x0, cause 'memory not mapped'
    
    Traceback:
     1: affineWithRebuiltCurveEngine(params, matchlegs, c(ts$table$date),     ts$table$zeroRates, expiry, tenor, vol)
     2: AffineSwaption.default(params, dcurve, swaptionMaturities, swapTenors,     volMatrix, legparams)
     3: AffineSwaption(params, dcurve, swaptionMaturities, swapTenors,     volMatrix, legparams)
    An irrecoverable exception occurred. R is aborting now ...
    ```

*   checking tests ...
    ```
     ERROR
    Running the tests in ‘tests/RQuantlib.R’ failed.
    Last 13 lines of output:
      +                             settleDate=as.Date('2002-2-15'),
      +                             dt=0.25,
      +                             interpWhat='discount', interpHow='loglinear')
      > discountCurve <- DiscountCurve(discountCurve.param, list(flat=0.05))
      > 
      > ZeroCouponBond(bond, discountCurve, dateparams)
      
       *** caught segfault ***
      address 0x0, cause 'memory not mapped'
      
      Traceback:
       1: ZeroBondWithRebuiltCurve(bond, c(discountCurve$table$date), discountCurve$table$zeroRates,     dateparams)
       2: ZeroCouponBond.default(bond, discountCurve, dateparams)
       3: ZeroCouponBond(bond, discountCurve, dateparams)
      An irrecoverable exception occurred. R is aborting now ...
    ```

# rsconnect

Version: 0.8.13

## In both

*   checking Rd cross-references ... NOTE
    ```
    Packages unavailable to check Rd xrefs: ‘keras’, ‘tensorflow’
    ```

# rtimicropem

Version: 1.3

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘R6’
      All declared Imports should be used.
    ```

# rTRMui

Version: 1.20.0

## In both

*   checking package dependencies ... ERROR
    ```
    Packages required but not available: ‘org.Hs.eg.db’ ‘org.Mm.eg.db’
    
    See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
    manual.
    ```

# RtutoR

Version: 1.2

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘DT’ ‘rmarkdown’
      All declared Imports should be used.
    ```

# RxODE

Version: 0.8.0-9

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘n1qn1’
      All declared Imports should be used.
    ```

# sangerseqR

Version: 1.18.0

## In both

*   checking R code for possible problems ... NOTE
    ```
    ...
    chromatogram,sangerseq: no visible global function definition for ‘IQR’
    chromatogram,sangerseq: no visible global function definition for ‘pdf’
    chromatogram,sangerseq: no visible global function definition for
      ‘plot’
    chromatogram,sangerseq: no visible global function definition for
      ‘rect’
    chromatogram,sangerseq: no visible global function definition for
      ‘lines’
    chromatogram,sangerseq: no visible global function definition for
      ‘mtext’
    chromatogram,sangerseq: no visible global function definition for
      ‘axis’
    chromatogram,sangerseq: no visible global function definition for
      ‘dev.off’
    Undefined global functions or variables:
      IQR axis dev.off lines mtext par pdf plot quantile rect
    Consider adding
      importFrom("grDevices", "dev.off", "pdf")
      importFrom("graphics", "axis", "lines", "mtext", "par", "plot", "rect")
      importFrom("stats", "IQR", "quantile")
    to your NAMESPACE file.
    ```

# santaR

Version: 1.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘gridExtra’
      All declared Imports should be used.
    ```

# SC3

Version: 1.10.1

## In both

*   checking re-building of vignette outputs ... WARNING
    ```
    Error in re-building vignettes:
      ...
    Error: processing vignette 'SC3.Rmd' failed with diagnostics:
    there is no package called ‘BiocStyle’
    Execution halted
    ```

*   checking installed package size ... NOTE
    ```
      installed size is  6.2Mb
      sub-directories of 1Mb or more:
        data   3.0Mb
        doc    2.5Mb
    ```

# scone

Version: 1.6.1

## In both

*   checking re-building of vignette outputs ... WARNING
    ```
    ...
    
    The following objects are masked from 'package:Biobase':
    
        anyMissing, rowMedians
    
    Loading required package: BiocParallel
    
    Attaching package: 'DelayedArray'
    
    The following objects are masked from 'package:matrixStats':
    
        colMaxs, colMins, colRanges, rowMaxs, rowMins, rowRanges
    
    The following objects are masked from 'package:base':
    
        aperm, apply
    
    Quitting from lines 75-84 (sconeTutorial.Rmd) 
    Error: processing vignette 'sconeTutorial.Rmd' failed with diagnostics:
    there is no package called 'scRNAseq'
    Execution halted
    ```

*   checking package dependencies ... NOTE
    ```
    Package suggested but not available for checking: ‘scRNAseq’
    ```

*   checking R code for possible problems ... NOTE
    ```
    ...
    sconeReport : server: no visible global function definition for ‘theme’
    sconeReport : server: no visible global function definition for
      ‘element_blank’
    sconeReport : server: no visible global function definition for
      ‘ggplotly’
    sconeReport : server: no visible global function definition for
      ‘geom_violin’
    sconeReport : server: no visible global function definition for
      ‘coord_cartesian’
    sconeReport : server: no visible global function definition for
      ‘scale_fill_manual’
    sconeReport : server: no visible global function definition for
      ‘geom_point’
    sconeReport : server: no visible global function definition for
      ‘guides’
    Undefined global functions or variables:
      %>% aes coord_cartesian element_blank geom_bar geom_point geom_violin
      ggplot ggplotly guides labs plot_ly plotlyOutput renderVisNetwork
      scale_fill_manual theme visEdges visGroups visHierarchicalLayout
      visLegend visNetwork visNetworkOutput visNetworkProxy visOptions
      visSelectNodes ylim
    ```

# SDEFSR

Version: 0.7.1.0

## In both

*   checking re-building of vignette outputs ... WARNING
    ```
    ...
    Error in re-building vignettes:
      ...
    Warning in grep(paste(r, collapse = "|"), text, value = TRUE) :
      input string 1294 is invalid in this locale
    Warning in grep(paste(r, collapse = "|"), text, value = TRUE) :
      input string 1295 is invalid in this locale
    Warning in grep("^\\s*$", x) :
      input string 1294 is invalid in this locale
    Warning in grep("^\\s*$", x) :
      input string 1295 is invalid in this locale
    Warning in grep("^! ", x) : input string 1294 is invalid in this locale
    Warning in grep("^! ", x) : input string 1295 is invalid in this locale
    ! Misplaced alignment tab character &.
    <argument> ...rd/record.uri?eid=2-s2.0-0038500689&
                                                      partnerID=40&md5=c145be999...
    l.1542 ...40&md5=c145be9994977d3b34110e35c227cf31}
                                                      . 
    
    Error: processing vignette 'SDEFSRpackage.Rmd' failed with diagnostics:
    Failed to compile SDEFSRpackage.tex. See https://yihui.name/tinytex/r/#debugging for debugging tips. See SDEFSRpackage.log for more info.
    Execution halted
    ```

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘grDevices’
      All declared Imports should be used.
    ```

# SEA

Version: 1.0

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  8.8Mb
      sub-directories of 1Mb or more:
        R   8.0Mb
    ```

# semdrw

Version: 0.1.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘dplyr’ ‘lavaan’ ‘psych’ ‘semPlot’ ‘semTools’ ‘shinyAce’
      All declared Imports should be used.
    ```

# SEPA

Version: 1.12.0

## In both

*   checking package dependencies ... ERROR
    ```
    Packages required but not available: ‘org.Hs.eg.db’ ‘org.Mm.eg.db’
    
    See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
    manual.
    ```

# seqplots

Version: 1.20.1

## In both

*   checking Rd \usage sections ... WARNING
    ```
    Undocumented arguments in documentation object 'plotHeatmap'
      ‘plotz’ ‘FO’ ‘CL’ ‘sort_by’ ‘sort_mids’ ‘sort_dst’ ‘clst_mids’
    
    Functions with \usage entries need to have the appropriate \alias
    entries, and all their arguments documented.
    The \usage entries must correspond to syntactically valid R code.
    See chapter ‘Writing R documentation files’ in the ‘Writing R
    Extensions’ manual.
    ```

*   checking installed package size ... NOTE
    ```
      installed size is 14.8Mb
      sub-directories of 1Mb or more:
        doc        3.7Mb
        seqplots  10.1Mb
    ```

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘BiocManager’
      All declared Imports should be used.
    ```

*   checking foreign function calls ... NOTE
    ```
    Foreign function call to a different package:
      .Call("BWGFile_summary", ..., PACKAGE = "rtracklayer")
    See chapter ‘System and foreign language interfaces’ in the ‘Writing R
    Extensions’ manual.
    ```

*   checking R code for possible problems ... NOTE
    ```
    ...
    plotHeatmap,list: no visible global function definition for ‘hclust’
    plotHeatmap,list: no visible global function definition for ‘dist’
    plotHeatmap,list: no visible global function definition for ‘cutree’
    plotHeatmap,list: no visible global function definition for
      ‘as.dendrogram’
    plotHeatmap,list: no visible global function definition for ‘title’
    Undefined global functions or variables:
      Var1 Var2 abline adjustcolor approx as.dendrogram axis box
      capture.output colorRampPalette cutree dist doFileOperations hclust
      image kmeans layout lines mtext par plot.new qt rainbow rect rgb text
      title value
    Consider adding
      importFrom("grDevices", "adjustcolor", "colorRampPalette", "rainbow",
                 "rgb")
      importFrom("graphics", "abline", "axis", "box", "image", "layout",
                 "lines", "mtext", "par", "plot.new", "rect", "text",
                 "title")
      importFrom("stats", "approx", "as.dendrogram", "cutree", "dist",
                 "hclust", "kmeans", "qt")
      importFrom("utils", "capture.output")
    to your NAMESPACE file.
    ```

# sglr

Version: 0.7

## In both

*   checking DESCRIPTION meta-information ... NOTE
    ```
    Malformed Description field: should contain one or more complete sentences.
    ```

*   checking R code for possible problems ... NOTE
    ```
    .computePStar: no visible global function definition for ‘uniroot’
    plotBoundary: no visible global function definition for
      ‘scale_y_continuous’
    Undefined global functions or variables:
      scale_y_continuous uniroot
    Consider adding
      importFrom("stats", "uniroot")
    to your NAMESPACE file.
    ```

# shiny.router

Version: 0.1.1

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘magrittr’
      All declared Imports should be used.
    ```

# shiny.semantic

Version: 0.2.1

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘utils’
      All declared Imports should be used.
    ```

# shinyAce

Version: 0.3.3

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  7.8Mb
      sub-directories of 1Mb or more:
        www   7.7Mb
    ```

# shinyaframe

Version: 1.0.1

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘shiny’
      All declared Imports should be used.
    ```

# shinyBS

Version: 0.61

## In both

*   checking R code for possible problems ... NOTE
    ```
    popify: no visible global function definition for ‘runif’
    tipify: no visible global function definition for ‘runif’
    Undefined global functions or variables:
      runif
    Consider adding
      importFrom("stats", "runif")
    to your NAMESPACE file.
    ```

# shinyEffects

Version: 0.1.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘shinydashboard’
      All declared Imports should be used.
    ```

# shinyHeatmaply

Version: 0.1.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘RColorBrewer’ ‘htmlwidgets’ ‘jsonlite’ ‘viridis’
      All declared Imports should be used.
    ```

# shinyhelper

Version: 0.3.1

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘markdown’
      All declared Imports should be used.
    ```

# ShinyItemAnalysis

Version: 1.3.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘DT’ ‘data.table’ ‘ggdendro’ ‘gridExtra’ ‘knitr’ ‘latticeExtra’ ‘msm’
      ‘plotly’ ‘shinyBS’ ‘shinydashboard’ ‘xtable’
      All declared Imports should be used.
    ```

*   checking Rd cross-references ... NOTE
    ```
    Package unavailable to check Rd xrefs: ‘WrightMap’
    ```

# shinyjs

Version: 1.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘htmltools’
      All declared Imports should be used.
    ```

# shinyKGode

Version: 1.0.5

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘KGode’ ‘XML’ ‘ggplot2’ ‘gridExtra’ ‘mvtnorm’ ‘reshape2’ ‘shinyjs’
      All declared Imports should be used.
    ```

# shinyMethyl

Version: 1.18.0

## In both

*   checking package dependencies ... ERROR
    ```
    Package required but not available: ‘IlluminaHumanMethylation450kmanifest’
    
    Package suggested but not available for checking: ‘minfiData’
    
    See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
    manual.
    ```

# shinyrecap

Version: 0.1.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘CARE1’ ‘LCMCR’ ‘coda’ ‘conting’ ‘dga’ ‘future’ ‘ggplot2’ ‘ipc’
      ‘promises’ ‘reshape’ ‘shinycssloaders’ ‘testthat’
      All declared Imports should be used.
    ```

# shinystan

Version: 2.5.0

## In both

*   checking Rd cross-references ... NOTE
    ```
    Package unavailable to check Rd xrefs: ‘brms’
    ```

# shinyTANDEM

Version: 1.20.1

## In both

*   checking dependencies in R code ... NOTE
    ```
    Packages in Depends field not imported from:
      ‘methods’ ‘mixtools’ ‘rTANDEM’ ‘shiny’ ‘xtable’
      These packages need to be imported from (in the NAMESPACE file)
      for when this namespace is loaded but not attached.
    ```

*   checking R code for possible problems ... NOTE
    ```
    ...
    stats.ui: no visible global function definition for ‘div’
    stats.ui: no visible global function definition for ‘h3’
    stats.ui: no visible global function definition for ‘uiOutput’
    tableAsHTML: no visible global function definition for ‘capture.output’
    tableAsHTML: no visible global function definition for ‘xtable’
    Undefined global functions or variables:
      GetResultsFromXML HTML abline actionButton addResourcePath at
      basicPage capture.output conditionalPanel dataset density div
      expect.value h2 h3 h4 h5 helpText htmlOutput includeHTML is isolate
      label legend like lines modified new normalmixEM num.peptides
      numericInput observe p pep.id plot plotOutput points prot.uid
      reactive reactiveValues renderPlot renderText renderUI runApp
      selectInput singleton span tabPanel tabsetPanel tag tagList tags
      textInput type uiOutput uid xtable
    Consider adding
      importFrom("graphics", "abline", "legend", "lines", "plot", "points")
      importFrom("methods", "is", "new")
      importFrom("stats", "density")
      importFrom("utils", "capture.output")
    to your NAMESPACE file (and ensure that your DESCRIPTION Imports field
    contains 'methods').
    ```

# sigmajs

Version: 0.1.3

## In both

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 28 marked UTF-8 strings
    ```

# SimDesign

Version: 1.13

## In both

*   checking package dependencies ... NOTE
    ```
    Package suggested but not available for checking: ‘doMPI’
    ```

# singleCellTK

Version: 1.2.3

## In both

*   checking package dependencies ... ERROR
    ```
    Package required but not available: ‘GSVAdata’
    
    Packages suggested but not available for checking:
      ‘bladderbatch’ ‘org.Mm.eg.db’ ‘org.Hs.eg.db’ ‘scRNAseq’
    
    See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
    manual.
    ```

# soc.ca

Version: 0.7.3

## In both

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 833 marked UTF-8 strings
    ```

# soilcarbon

Version: 1.2.0

## In both

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 145 marked UTF-8 strings
    ```

# soundgen

Version: 1.4.0

## In both

*   checking Rd cross-references ... NOTE
    ```
    Package unavailable to check Rd xrefs: ‘spectral’
    ```

# SpaDES.addins

Version: 0.1.2

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘devtools’ ‘rstudioapi’
      All declared Imports should be used.
    ```

# SpatialEpiApp

Version: 0.3

## In both

*   checking package dependencies ... NOTE
    ```
    Package suggested but not available for checking: ‘INLA’
    ```

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘RColorBrewer’ ‘SpatialEpi’ ‘dplyr’ ‘dygraphs’ ‘ggplot2’
      ‘htmlwidgets’ ‘knitr’ ‘leaflet’ ‘mapproj’ ‘maptools’ ‘rgdal’ ‘rgeos’
      ‘rmarkdown’ ‘shinyjs’ ‘spdep’ ‘xts’
      All declared Imports should be used.
    ```

# spectrolab

Version: 0.0.8

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘devtools’ ‘usethis’
      All declared Imports should be used.
    ```

# SSDM

Version: 0.2.4

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘shinyFiles’
      All declared Imports should be used.
    ```

# sstModel

Version: 1.0.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘shinydashboard’
      All declared Imports should be used.
    ```

# STAT

Version: 0.1.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘Hmisc’ ‘corrgram’ ‘datasets’ ‘dplyr’ ‘psych’ ‘psycho’ ‘rpivotTable’
      ‘shiny’
      All declared Imports should be used.
    ```

# steemr

Version: 0.1.3

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘rlist’ ‘tm’ ‘zoo’
      All declared Imports should be used.
    ```

# stminsights

Version: 0.3.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘huge’ ‘readr’ ‘scales’ ‘shinyjs’
      All declared Imports should be used.
    ```

# strataG

Version: 2.0.2

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘survival’
      All declared Imports should be used.
    ```

# subscreen

Version: 2.0.1

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘DT’ ‘V8’ ‘bsplus’ ‘colourpicker’ ‘dplyr’ ‘grDevices’ ‘graphics’
      ‘jsonlite’ ‘shinyjs’
      All declared Imports should be used.
    ```

# tableHTML

Version: 2.0.0

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  6.1Mb
      sub-directories of 1Mb or more:
        doc   5.8Mb
    ```

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘shiny’
      All declared Imports should be used.
    ```

# tablerDash

Version: 0.1.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘knitr’
      All declared Imports should be used.
    ```

# TAShiny

Version: 0.1.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘SnowballC’ ‘dplyr’ ‘igraph’ ‘tm’ ‘wordcloud2’
      All declared Imports should be used.
    ```

# TCGAbiolinksGUI

Version: 1.8.1

## In both

*   checking package dependencies ... ERROR
    ```
    Package required but not available: ‘sesameData’
    
    See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
    manual.
    ```

# tenXplore

Version: 1.4.1

## In both

*   checking package dependencies ... ERROR
    ```
    Package required but not available: ‘org.Mm.eg.db’
    
    Package suggested but not available for checking: ‘org.Hs.eg.db’
    
    See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
    manual.
    ```

# testextra

Version: 0.1.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘stringi’ ‘utils’
      All declared Imports should be used.
    ```

# TFutils

Version: 1.2.0

## In both

*   checking examples ... ERROR
    ```
    Running examples in ‘TFutils-Ex.R’ failed
    The error most likely occurred in:
    
    > ### Name: genemodelDF
    > ### Title: use EnsDb to generate an exon-level model of genes identified by
    > ###   symbol
    > ### Aliases: genemodelDF
    > 
    > ### ** Examples
    > 
    > if (requireNamespace("EnsDb.Hsapiens.v75")) {
    +  orm = genemodelDF("ORMDL3", EnsDb.Hsapiens.v75::EnsDb.Hsapiens.v75)
    +  dim(orm)
    + }
    Loading required namespace: EnsDb.Hsapiens.v75
    Failed with error:  'there is no package called 'EnsDb.Hsapiens.v75''
    > head(orm)
    Error in head(orm) : object 'orm' not found
    Execution halted
    ```

*   checking tests ...
    ```
     ERROR
    Running the tests in ‘tests/testthat.R’ failed.
    Last 13 lines of output:
      4: getExportedValue(pkg, name)
      5: asNamespace(ns)
      6: getNamespace(ns)
      7: tryCatch(loadNamespace(name), error = function(e) stop(e))
      8: tryCatchList(expr, classes, parentenv, handlers)
      9: tryCatchOne(expr, names, parentenv, handlers[[1L]])
      10: value[[3L]](cond)
      
      Failed with error:  'there is no package called 'EnsDb.Hsapiens.v75''
      ══ testthat results  ═══════════════════════════════════════════════════════════
      OK: 3 SKIPPED: 0 FAILED: 1
      1. Error: grabTab returns expected records (@test.R#8) 
      
      Error: testthat unit tests failed
      Execution halted
    ```

*   checking re-building of vignette outputs ... WARNING
    ```
    Error in re-building vignettes:
      ...
    Quitting from lines 38-59 (TFutils.Rmd) 
    Error: processing vignette 'TFutils.Rmd' failed with diagnostics:
    there is no package called 'org.Hs.eg.db'
    Execution halted
    ```

*   checking package dependencies ... NOTE
    ```
    Packages suggested but not available for checking:
      ‘org.Hs.eg.db’ ‘EnsDb.Hsapiens.v75’ ‘GO.db’
    ```

*   checking R code for possible problems ... NOTE
    ```
    directHitsInCISBP: no visible binding for global variable
      ‘DISEASE.TRAIT’
    directHitsInCISBP: no visible binding for global variable ‘MAPPED_GENE’
    directHitsInCISBP: no visible binding for global variable ‘cisbpTFcat’
    directHitsInCISBP: no visible binding for global variable ‘HGNC’
    directHitsInCISBP: no visible binding for global variable ‘Family_Name’
    topTraitsOfTargets: no visible global function definition for
      ‘geneIdType’
    topTraitsOfTargets: no visible global function definition for
      ‘mapIdentifiers’
    topTraitsOfTargets: no visible global function definition for
      ‘SymbolIdentifier’
    topTraitsOfTargets: no visible global function definition for ‘geneIds’
    topTraitsOfTargets: no visible global function definition for ‘mcols’
    topTraitsOfTargets: no visible binding for global variable
      ‘DISEASE.TRAIT’
    Undefined global functions or variables:
      DISEASE.TRAIT Family_Name HGNC MAPPED_GENE SymbolIdentifier
      cisbpTFcat geneIdType geneIds mapIdentifiers mcols
    ```

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 62 marked UTF-8 strings
    ```

# timeline

Version: 0.9

## In both

*   checking dependencies in R code ... NOTE
    ```
    'library' or 'require' call to ‘shiny’ in package code.
      Please use :: or requireNamespace() instead.
      See section 'Suggested packages' in the 'Writing R Extensions' manual.
    Package in Depends field not imported from: ‘ggplot2’
      These packages need to be imported from (in the NAMESPACE file)
      for when this namespace is loaded but not attached.
    ```

*   checking R code for possible problems ... NOTE
    ```
    timeline: no visible global function definition for ‘ggplot’
    timeline: no visible global function definition for ‘geom_segment’
    timeline: no visible global function definition for ‘aes_string’
    timeline: no visible global function definition for ‘geom_rect’
    timeline: no visible global function definition for ‘geom_text’
    timeline: no visible global function definition for ‘theme’
    timeline: no visible global function definition for ‘element_blank’
    timeline: no visible global function definition for ‘xlab’
    timeline: no visible global function definition for ‘ylab’
    timeline: no visible global function definition for ‘xlim’
    timeline: no visible global function definition for
      ‘scale_y_continuous’
    timeline: no visible global function definition for ‘geom_point’
    timeline: no visible global function definition for ‘scale_color_grey’
    timeline: no visible global function definition for ‘geom_hline’
    Undefined global functions or variables:
      aes_string element_blank geom_hline geom_point geom_rect geom_segment
      geom_text ggplot scale_color_grey scale_y_continuous theme xlab xlim
      ylab
    ```

# TimerQuant

Version: 1.12.0

## In both

*   checking R code for possible problems ... NOTE
    ```
    ...
      ‘rainbow’
    plotPrimordiumProfile: no visible binding for global variable ‘median’
    plotPrimordiumProfile: no visible binding for global variable ‘mad’
    plotPrimordiumProfile: no visible global function definition for ‘par’
    plotPrimordiumProfile: no visible global function definition for ‘plot’
    plotPrimordiumProfile: no visible global function definition for ‘axis’
    plotPrimordiumProfile: no visible global function definition for
      ‘points’
    plotPrimordiumProfile: no visible global function definition for
      ‘polygon’
    plotPrimordiumProfile: no visible global function definition for ‘rgb’
    simulatedRatio: no visible global function definition for ‘rnorm’
    Undefined global functions or variables:
      approxfun axis mad median optimize par plot points polygon predict
      rainbow rgb rnorm
    Consider adding
      importFrom("grDevices", "rainbow", "rgb")
      importFrom("graphics", "axis", "par", "plot", "points", "polygon")
      importFrom("stats", "approxfun", "mad", "median", "optimize",
                 "predict", "rnorm")
    to your NAMESPACE file.
    ```

# timeseriesdb

Version: 0.4.1

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘shiny’
      All declared Imports should be used.
    ```

# timevis

Version: 0.5

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘lubridate’
      All declared Imports should be used.
    ```

# tmaptools

Version: 2.0-1

## In both

*   checking Rd cross-references ... NOTE
    ```
    Package unavailable to check Rd xrefs: ‘osmar’
    ```

# TreeSearch

Version: 0.3.0

## In both

*   checking re-building of vignette outputs ... WARNING
    ```
    Error in re-building vignettes:
      ...
    Quitting from lines 40-68 (profile-scores.Rmd) 
    Error: processing vignette 'profile-scores.Rmd' failed with diagnostics:
    non-conformable arrays
    Execution halted
    ```

# treespace

Version: 1.1.3.1

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  5.0Mb
      sub-directories of 1Mb or more:
        doc   3.5Mb
    ```

# tricolore

Version: 1.2.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘dplyr’
      All declared Imports should be used.
    ```

*   checking data for non-ASCII characters ... NOTE
    ```
      Note: found 88 marked UTF-8 strings
    ```

# TSCAN

Version: 1.20.0

## In both

*   checking R code for possible problems ... NOTE
    ```
    ...
      ‘lm’
    exprmclust: no visible global function definition for ‘dist’
    plotmclust: no visible binding for global variable ‘pca_dim_1’
    plotmclust: no visible binding for global variable ‘pca_dim_2’
    plotmclust: no visible binding for global variable ‘sample_name’
    preprocess: no visible binding for global variable ‘sd’
    preprocess: no visible global function definition for ‘hclust’
    preprocess: no visible global function definition for ‘dist’
    preprocess: no visible global function definition for ‘cutree’
    preprocess: no visible global function definition for ‘aggregate’
    singlegeneplot: no visible global function definition for
      ‘fitted.values’
    singlegeneplot: no visible binding for global variable ‘predict’
    Undefined global functions or variables:
      aggregate cutree dist fitted.values hclust lm p.adjust pca_dim_1
      pca_dim_2 pchisq prcomp predict sample_name sd
    Consider adding
      importFrom("stats", "aggregate", "cutree", "dist", "fitted.values",
                 "hclust", "lm", "p.adjust", "pchisq", "prcomp", "predict",
                 "sd")
    to your NAMESPACE file.
    ```

# ttestshiny

Version: 0.1.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘dplyr’ ‘shinyAce’ ‘shinyjs’
      All declared Imports should be used.
    ```

# TVTB

Version: 1.8.0

## In both

*   checking tests ...
    ```
     ERROR
    Running the tests in ‘tests/testthat.R’ failed.
    Last 13 lines of output:
        rs1426654 rs150379789 rs570906312 rs538198029 rs553496066 rs574775672 
             TRUE        TRUE       FALSE       FALSE        TRUE       FALSE 
      rs140666229 rs556950130 rs575303689 rs147513140 rs187525777 rs192454382 
             TRUE       FALSE        TRUE        TRUE       FALSE       FALSE 
      rs184818838 rs566886499 rs199924625 rs555872528 rs531820822 rs201353600 
            FALSE       FALSE       FALSE       FALSE       FALSE       FALSE 
      rs550201688 rs565338261 rs201239799 rs200461129 rs146726548 
            FALSE       FALSE       FALSE       FALSE        TRUE 
      ══ testthat results  ═══════════════════════════════════════════════════════════
      OK: 225 SKIPPED: 2 FAILED: 2
      1. Error: all signatures work to completion (@test_plotInfo-methods.R#25) 
      2. Error: invalid metric/phenotype combination is detected (@test_plotInfo-methods.R#50) 
      
      Error: testthat unit tests failed
      Execution halted
    ```

*   checking re-building of vignette outputs ... WARNING
    ```
    Error in re-building vignettes:
      ...
    Overwriting INFO keys in data:
    - REF
    - HET
    - ALT
    - AAF
    - MAF
    Overwriting INFO keys in header:
    - REF
    - HET
    - ALT
    - AAF
    - MAF
    Quitting from lines 569-576 (Introduction.Rmd) 
    Error: processing vignette 'Introduction.Rmd' failed with diagnostics:
    there is no package called 'EnsDb.Hsapiens.v75'
    Execution halted
    ```

*   checking package dependencies ... NOTE
    ```
    Package suggested but not available for checking: ‘EnsDb.Hsapiens.v75’
    ```

*   checking installed package size ... NOTE
    ```
      installed size is  5.2Mb
      sub-directories of 1Mb or more:
        R     2.0Mb
        doc   2.2Mb
    ```

# twoddpcr

Version: 1.6.0

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  5.9Mb
      sub-directories of 1Mb or more:
        data   1.2Mb
        doc    4.1Mb
    ```

# Ularcirc

Version: 1.0.0

## In both

*   checking package dependencies ... ERROR
    ```
    Package required but not available: ‘mirbase.db’
    
    See section ‘The DESCRIPTION file’ in the ‘Writing R Extensions’
    manual.
    ```

# VariantFiltering

Version: 1.18.0

## In both

*   checking examples ... ERROR
    ```
    ...
    
    > ### Name: VariantFilteringParam-class
    > ### Title: VariantFiltering parameter class
    > ### Aliases: sequence_variant.gSOXP class:VariantFilteringParam
    > ###   VariantFilteringParam VariantFilteringParam-class
    > ###   show,VariantFilteringParam-method $,VariantFilteringParam-method
    > ###   names,VariantFilteringParam-method
    > ###   filters,VariantFilteringParam-method
    > ###   cutoffs,VariantFilteringParam-method sog,VariantFilteringParam-method
    > ###   spliceSiteMatricesHuman variantLocations
    > ### Keywords: classes,methods
    > 
    > ### ** Examples
    > 
    > vfpar <- VariantFilteringParam(system.file("extdata", "CEUtrio.vcf.bgz", package="VariantFiltering"),
    +                                system.file("extdata", "CEUtrio.ped", package="VariantFiltering"),
    +                                snpdb=character(0), otherAnnotations=character(0))
    Error in .loadAnnotationPackageObject(bsgenome, "bsgenome", "BSgenome") : 
      please install the Bioconductor package BSgenome.Hsapiens.1000genomes.hs37d5.
    Calls: VariantFilteringParam -> .loadAnnotationPackageObject
    Execution halted
    ```

*   checking tests ...
    ```
     ERROR
    Running the tests in ‘tests/runTests.R’ failed.
    Last 13 lines of output:
      Test files with failing tests
      
         test_VariantFilteringParam-methods.R 
           test_VariantFilteringParam 
      
         test_inheritance-models.R 
           /Users/barret/odrive/AmazonCloudDrive/git/rstudio/shiny/shiny/revdep/checks.noindex/VariantFiltering/new/VariantFiltering.Rcheck/VariantFiltering/unitTests/test_inheritance-models.R 
      
         test_location-methods.R 
           test_location_annotations 
      
      
      Error in BiocGenerics:::testPackage("VariantFiltering") : 
        unit tests failed for package VariantFiltering
      Execution halted
    ```

*   checking running R code from vignettes ...
    ```
       ‘usingVariantFiltering.Rnw’ ... failed
     ERROR
    Errors in running code in vignettes:
    when running code in ‘usingVariantFiltering.Rnw’
      ...
    
    
    > CEUvcf <- file.path(system.file("extdata", package = "VariantFiltering"), 
    +     "CEUtrio.vcf.bgz")
    
    > vfpar <- VariantFilteringParam(CEUvcf)
    
      When sourcing 'usingVariantFiltering.R':
    Error: please install the Bioconductor package BSgenome.Hsapiens.1000genomes.hs37d5.
    Execution halted
    ```

*   checking package dependencies ... NOTE
    ```
    Packages suggested but not available for checking:
      ‘org.Hs.eg.db’ ‘BSgenome.Hsapiens.1000genomes.hs37d5’
      ‘SNPlocs.Hsapiens.dbSNP144.GRCh37’ ‘MafDb.1Kgenomes.phase1.hs37d5’
      ‘phastCons100way.UCSC.hg19’ ‘PolyPhen.Hsapiens.dbSNP131’
      ‘SIFT.Hsapiens.dbSNP137’
    ```

*   checking installed package size ... NOTE
    ```
      installed size is  5.2Mb
      sub-directories of 1Mb or more:
        extdata   3.6Mb
    ```

*   checking dependencies in R code ... NOTE
    ```
    Unexported objects imported by ':::' calls:
      'S4Vectors:::labeledLine' 'VariantAnnotation:::.checkArgs'
      'VariantAnnotation:::.consolidateHits'
      'VariantAnnotation:::.returnEmpty'
      See the note in ?`:::` about the use of this operator.
    There are ::: calls to the package's namespace in its code. A package
      almost never needs to use ::: for its own objects:
      '.adjustForStrandSense' '.ancestorsSO' '.findSOIDs'
    ```

*   checking R code for possible problems ... NOTE
    ```
    annotateVariants,MafDb: no visible global function definition for
      'mafByOverlaps'
    Undefined global functions or variables:
      mafByOverlaps
    ```

*   checking Rd cross-references ... NOTE
    ```
    Package unavailable to check Rd xrefs: ‘phastCons100way.UCSC.hg19’
    ```

*   checking re-building of vignette outputs ... NOTE
    ```
    ...
    The following object is masked from ‘package:DelayedArray’:
    
        type
    
    The following object is masked from ‘package:base’:
    
        strsplit
    
    
    Attaching package: ‘VariantAnnotation’
    
    The following object is masked from ‘package:base’:
    
        tabulate
    
    
    Error: processing vignette 'usingVariantFiltering.Rnw' failed with diagnostics:
     chunk 3 
    Error in .loadAnnotationPackageObject(bsgenome, "bsgenome", "BSgenome") : 
      please install the Bioconductor package BSgenome.Hsapiens.1000genomes.hs37d5.
    Execution halted
    ```

# vdiffr

Version: 0.3.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘freetypeharfbuzz’
      All declared Imports should be used.
    ```

# visNetwork

Version: 2.0.6

## In both

*   checking installed package size ... NOTE
    ```
      installed size is 11.1Mb
      sub-directories of 1Mb or more:
        doc           4.2Mb
        docjs         1.4Mb
        htmlwidgets   3.9Mb
    ```

# wallace

Version: 1.0.6

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘DT’ ‘ENMeval’ ‘RColorBrewer’ ‘XML’ ‘dismo’ ‘dplyr’ ‘leaflet.extras’
      ‘maptools’ ‘raster’ ‘rgdal’ ‘rgeos’ ‘rmarkdown’ ‘shinyjs’
      ‘shinythemes’ ‘spThin’ ‘spocc’ ‘zip’
      All declared Imports should be used.
    ```

# wiseR

Version: 1.0.1

## In both

*   checking installed package size ... NOTE
    ```
      installed size is  7.2Mb
      sub-directories of 1Mb or more:
        bn   7.1Mb
    ```

*   checking dependencies in R code ... NOTE
    ```
    Namespaces in Imports field not imported from:
      ‘DT’ ‘DescTools’ ‘HydeNet’ ‘RBGL’ ‘Rgraphviz’ ‘arules’ ‘bnlearn’
      ‘dplyr’ ‘graph’ ‘igraph’ ‘linkcomm’ ‘missRanger’ ‘parallel’ ‘psych’
      ‘rhandsontable’ ‘rintrojs’ ‘shinyBS’ ‘shinyWidgets’ ‘shinyalert’
      ‘shinycssloaders’ ‘shinydashboard’ ‘tools’ ‘visNetwork’
      All declared Imports should be used.
    ```

# wTO

Version: 1.6.3

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘shiny’
      All declared Imports should be used.
    ```

# yuimaGUI

Version: 1.3.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘ghyp’
      All declared Imports should be used.
    ```

# zscorer

Version: 0.2.0

## In both

*   checking dependencies in R code ... NOTE
    ```
    Namespace in Imports field not imported from: ‘tidyr’
      All declared Imports should be used.
    ```

