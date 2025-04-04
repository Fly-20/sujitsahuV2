---
title: R package bmstdr
cms_exclude: true
#url: talk

# View
view: card

# Optional cover image (relative to `assets/media/` folder).
image:
  caption: ''
  filename: ''
---

<ul>
<li> Please install the package directly from CRAN.

```{r source, echo=TRUE, eval=FALSE}
install.packages("bmstdr", dependencies = TRUE)
```

<li> There is a long list of dependent packages that may need to be installed on your computer. You may find   <a href="/bmbook/install-bmstdr.R"> the commands in this R file </a> useful to install those packages.

<li>  Development version of the package can be installed from github using the <b> R </b> command:

```{r source, echo=TRUE, eval=FALSE}
devtools::install_github("sujit-sahu/bmstdr", build_vignettes = TRUE)
```

<li> You may check the installation:

```{r source, echo=TRUE, eval=FALSE}
library(bmstdr)
ls("package:bmstdr")
browseVignettes('bmstdr')
```

<li>
<h2>
<font color="#FF00FF" face="arial" size="5"> Here is   <a href="/bmbook/bmstdr-full_vignette.html"> a full version of the vignette.</a> This version has not been distributed with the package because of file size limitation in CRAN.</a> </font>
</h2>

<li> <a href="/bmbook/bmstdr_0.3.0.manual.pdf"> A pdf version of the manual </a> is also available. </li>

<li>
<font color="#FF00FF" face="arial" size="5"> Here is   <a href="/bmbook/bmstdr_poster.pdf"> a conference poster for bmstdr.</a>
</li>

</ul>