---
title: "{{ replace .Name "-" " " | title }}"
author: ""
type: ""
date: {{ .Date }}
subtitle: ""
image: ""
tags: []
---

```{r, setup, include = FALSE}
knitr::opts_chunk$set(
  class.output  = "bg-success",
  class.message = "bg-info text-info",
  class.warning = "bg-warning text-warning",
  class.error   = "bg-danger text-danger"
)
knitr::opts_chunk$set(fig.path = "") 
```


<br />
<details>
  <summary>
    <tt>devtools::session_info()</tt>
  </summary>
```{r sessionInfo, echo = FALSE}
devtools::session_info()
```
</details>
<br />