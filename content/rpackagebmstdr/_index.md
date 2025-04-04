---
title: " Bayesian modeling of spatio-temporal data with R."

date: "2015-09-01T00:00:00Z"
doi: ""



# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]


abstract: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum. Sed ac faucibus dolor, scelerisque sollicitudin nisi. Cras purus urna, suscipit quis sapien eu, pulvinar tempor diam. Quisque risus orci, mollis id ante sit amet, gravida egestas nisl. Sed ac tempus magna. Proin in dui enim. Donec condimentum, sem id dapibus fringilla, tellus enim condimentum arcu, nec volutpat est felis vel metus. Vestibulum sit amet erat at nulla eleifend gravida.

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: false

links:
- name: Custom Link
  url: https://www.sujitsahu.com/publicationlist



# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).

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