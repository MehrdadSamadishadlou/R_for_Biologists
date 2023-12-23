---
title: Course Materials
layout: template
filename: materials
--- 

All sessions will be recorded and  uploaded to YouTube. You can find the videos in the following link:

<a href="https://www.youtube.com/@MehrdadSamadishadlou" target="_blank"><button>R Videos</button></a>


## Installing R and RStudio

<p style='text-align: justify;'>
You can download it free from the <b>CRAN</b> if you haven't installed R on your computer yet. Follow this link to the download page:
</p>

<a href="https://cran.r-project.org/index.html" target="_blank"><button>R Download Page</button></a>

<p style='text-align: justify;'>
An IDE, or Integrated Development Environment, is a software application that provides a comprehensive environment for programmers to write, edit, and debug code. RStudio is a popular and powerful IDE developed for R by Posit. RStudio makes using R much easier, especially for beginners. The R console and environment are seamlessly integrated into RStudio so you can run R code and see plots, output, and results. RStudio also comes pre-installed with packages and functions to help you be more productive with R.
</p>

<a href="https://posit.co/download/rstudio-desktop/" target="_blank"><button>RStudio Download Page</button></a>


# Session 1

RStudio CheatSheet including its most common key bindings: <a href="https://rstudio.github.io/cheatsheets/html/rstudio-ide.html" target="_blank"><button>RStudio IDE :: Cheatsheet</button></a>

Other materials including presentation slides and R script can be downloaded here:

<a href="https://drive.google.com/file/d/1RditmwTi0UPQcINqIMcxBhs__BZc6-iV/view?usp=sharing" target="_blank"><button>Presentation</button></a>  <a href="https://drive.google.com/file/d/1HWuZxByTwAC9rI0sce4G4KMNGa44ZiwY/view?usp=sharing" target="_blank"><button>Session 1 Codes</button></a>

# Session 2

You can download the script of the second session from the following link. You can also download the notes taken and generously shared by Mr. Shahin Ahmadian. 

<a href="https://drive.google.com/file/d/1ErsrrPM3xyI_9SV0E83EBipK1CNU25sA/view?usp=sharing" target="_blank"><button>Session 2 Codes</button></a>  <a href="https://drive.google.com/file/d/1Cuuv8aLX5hazIn5xvi_dvfTjhjfNG5m0/view?usp=sharing" target="_blank"><button>Session 2 Notes</button></a>

# Session 3

The script and notes (thanks to Mr. Ahmadian) for the third session are available for download.

<a href="https://drive.google.com/file/d/1vCmEAkvv0PWJnn09A9RWlfjZ0GNVmbmY/view?usp=sharing" target="_blank"><button>Session 3 Codes</button></a>  <a href="https://drive.google.com/file/d/1XnJlFzh-OoDcyhP4iOj6nJh3pQO1OM5C/view?usp=sharing" target="_blank"><button>Session 3 Notes</button></a> 

# Session 4

The script for the Fourth session is available for download.

<a href="https://drive.google.com/file/d/1rxdDZbJ0PRMvAQkQEpJrWIBBlBc585Pa/view?usp=sharing" target="_blank"><button>Session 4 Codes</button></a> <a href="https://drive.google.com/file/d/11hjxDG0aORA-vbKskxztF6lhkwXTd7uF/view?usp=sharing" target="_blank"><button>Visualization Presentation</button></a>

# Session 5

The script for the Fifth session is available for download.

<a href="https://drive.google.com/file/d/1meiTiqPGwR4-CZlug0G35xg7hhGwSHsw/view?usp=sharing" target="_blank"><button>Session 5 Codes</button></a>

# Session 6

The script for the sixth session is available for download.

<a href="https://drive.google.com/file/d/1QVaiHeDP77YPmb0IQQGcMJFCZscW8AI_/view?usp=sharing" target="_blank"><button>Session 6 Codes</button></a>


# Session 7

The data related to the lesson can be downloaded through the following links:

<a href="https://drive.google.com/file/d/1Rgiv8Po2LcmaqNrdVSYBGcs1awEdqYJO/view?usp=sharing" target="_blank"><button>Experiment Data</button></a> <a href="https://drive.google.com/file/d/1ge-P5TPioz3BYc_2Dgdh6d5Y7jSFTLim/view?usp=sharing" target="_blank"><button>Population Data</button></a>

The script for the Seventh session is available for download.

<a href="https://drive.google.com/file/d/1iarMQKoAaQtbBjl-3joTAFQ9mAVURZx6/view?usp=sharing" target="_blank"><button>Session 7 Codes</button></a>

# Sessions 8 and 9

The dataset related to the lesson can be downloaded through the following links:

<a href="https://drive.google.com/file/d/1WQYCOsGOvLN2bJUiQlMDtHOrx-8no1bP/view?usp=sharing" target="_blank"><button>Expression Matrix</button></a> <a href="https://drive.google.com/file/d/1_iYToXhwk4qa_b9uXP9C67bIE62RRwMK/view?usp=sharing" target="_blank"><button>Platform Annotation</button></a>

```
#### Differential Express Analysis ####
gr <- factor(gr)
geneset$description <- gr

design <- model.matrix(~ description + 0, geneset)
colnames(design) <- levels(gr)

fit <- lmFit(geneset, design)
cont.matrix <- makeContrasts(c-h, levels=design)
fit2 <- contrasts.fit(fit, cont.matrix)
fit2 <- eBayes(fit2, 0.01)
tT <- topTable(fit2, adjust="fdr", sort.by="B", number=Inf)
```

The script of the DEG analysis and RMarkdpwn demo is available for download as a zip file.

<a href="https://drive.google.com/file/d/1oGDfNchc9ve51WknNs1bHER_uYRPXDP-/view?usp=sharing" target="_blank"><button>Expression Matrix</button></a> 
