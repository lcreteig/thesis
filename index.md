--- 
title: "Neuroplasticity of Attention"
subtitle: "How brain stimulation and mental fatigue affect attentional performance"
author: "Leon C. Reteig"
date: "23 September, 2019"
bibliography: [bib/thesis.bib, bib/r-packages.bib]
description: This is the PhD thesis of Leon Reteig
url: 'https\://lcreteig.github.io/thesis'
github-repo: "lcreteig/thesis"
cover-image: "cover/thesis_cover.jpg"
documentclass: memoir
lang: en
fontsize: 11pt
indent: true
site: bookdown::bookdown_site
biblio-style: "apa"
biblatexoptions: "useprefix=true"
link-citations: yes
citecolor: gray
nocite: |
  @Reteig2017, @Reteig2018b, @Reteig2019a
#links-as-notes: true # own implementation, so it can be turned off
---




# Preface {-}

<div class="figure">
<img src="cover/thesis_cover.jpg" alt="(ref:caption-cover)" width="390px" height="550px" />
<p class="caption">(\#fig:unnamed-chunk-3)(ref:caption-cover)</p>
</div>

(ref:caption-cover) __Cover art:__ _ENTROPY VIII_ (2018), &copy;Alicia Martin Lopez, <http://www.aliciamartinlopez.com>

Attention allows us to focus on what is relevant and to ignore what is not. While we call upon attention at every waking moment, it is not static: we cannot sustain attention indefinitely, and often fall prey to distractions. This PhD thesis is a study of the short-term _neuroplasticity_ of attentional processes: how susceptible is attention to change, and what processes in the brain (_neuro_-) give rise to changes in attention (-_plasticity_)? In Chapters 2--5, I examined whether attention can be improved with electrical stimulation of the brain, in the form of transcranial Direct Current Stimulation (tDCS). Previous studies that attempted to use tDCS to enhance attention have yielded promising, but inconsistent results (reviewed in Chapter 2). My attempt to enhance _spatial_ attention with tDCS (Chapter 3) was unsuccessful, as stimulation of the frontal eye fields did not lead to changes in eye movements. Applying tDCS over the dorsolateral prefrontal cortex also did not enhance _temporal_ attention (Chapters 4 and 5), as participants' performance on an attentional blink task remained unchanged. In Chapter 6, I investigated the opposite effect: decreases in attention, when attention has to be _sustained_ for a long time. Using EEG, I tracked whether similar decreases occurred in different attention-related signals in the brain. tDCS may one day be used to counteract these declines, or to relieve other deficits in attention. However, barring a deeper understanding of the technique and more large-scale studies of its efficacy, such practical applications of tDCS are not yet feasible.

---

This PhD project was conducted under the supervision of Prof. Dr. [Heleen A. Slagter](https://www.heleenslagter.com/) and Prof. Dr. [K. Richard Ridderinkhof](https://www.uva.nl/en/profile/r/i/k.r.ridderinkhof/k.r.ridderinkhof.html) at the [Department of Psychology](https://psyres.uva.nl/), Faculty of Behavioral and Social Sciences, University of Amsterdam.

The investigations in this thesis were supported by a Research Talent Grant (452-10-018) from the Netherlands Organization for Scientific Research (NWO).

```{=html}
<p><a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />The online version of this thesis is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>. The <i class="fa fa-file-pdf-o"></i> pdf version of the thesis is available for download on the toolbar above.</p>
```

<br>

> There's an awful lot of talk about groundbreaking research... [G]roundbreaking is what you do when you start a building. You go into a field and you dig a hole in the ground. If you're only rewarded for groundbreaking research, there's going to be a lot of fields with a small hole in, and no buildings.
>
> --- _Ottoline Leyser_ in [The Life Scientific, BBC Radio 4](https://www.bbc.co.uk/programmes/b08q5wxx)
