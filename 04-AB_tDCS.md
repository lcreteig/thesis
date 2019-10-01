

# Effects of tDCS on the attentional blink revisited: A statistical evaluation of a replication attempt {#AB-tDCS-EEG}
\chaptermark{Replicating tDCS effects on the attentional blink}

\vspace*{\fill}

---

\small
\noindent
_This chapter is in preparation as_: Reteig, L. C., Newman, L. A., Ridderinkhof, K. R., & Slagter, H. A. (n.d.). Effects of tDCS on the attentional blink revisited: A statistical evaluation of a replication attempt.
\newpage
\normalsize

`<p><strong>Abstract</strong></p>`{=html}
`\begin{abstract}`{=latex}
The attentional blink (AB) phenomenon reveals a bottleneck of human information processing: the second of two targets is often missed when they are presented in rapid succession among distractors. A recent study by London & Slagter (_Journal of Cognitive Neuroscience_, _27_, 2382--93, 2015) showed that the size of the AB can be changed by applying transcranial direct current stimulation (tDCS) over the left dorsolateral prefrontal cortex (lDLPFC). Although AB size at the group level remained unchanged, the effects of anodal and cathodal tDCS were negatively correlated: if a given individual's AB size decreased from baseline during anodal tDCS, their AB size would increase during cathodal tDCS, and vice versa. Here, we attempted to replicate this finding. Like London & Slagter, we found no group effects of tDCS, but also no longer found a significant negative correlation. We present a series of statistical measures of replication success, all of which confirm that both studies are not in agreement. First, the correlation here is significantly smaller than a conservative estimate of the original correlation. Second, the difference between the correlations is greater than expected due to sampling error, and our data are more consistent with a zero-effect than with the original estimate. Finally, the overall effect when combining both studies is small and not significant. Our findings thus indicate that the effects of lDPLFC-tDCS on the AB are less substantial than suggested by London & Slagter (2015). Although this should be quite a common scenario, negative findings can be difficult to interpret and are still under-represented in the brain stimulation and cognitive neuroscience literatures. An auxiliary goal of this chapter is therefore to provide a tutorial for other researchers, to maximize the evidential value from negative findings.
`\end{abstract} \newpage`{=latex}

## Introduction {#AB_tDCS-introduction}

The _attentional blink_ (AB) phenomenon clearly demonstrates that our capacity to process incoming information is easily overwhelmed. The AB occurs when two targets are embedded in a rapidly presented stream of distractors [@Raymond1992; for reviews, see @Dux2009; @Martens2010]. The first target (T1) is usually reported with little difficulty. When there is a longer lag between the two targets [> 500 ms; @MacLean2012], accuracy for the second target (T2) can be on par with the first. However, for shorter lags, T2 is most often missed---as if the attentional system momentarily faltered ("blinked").

While the AB might seem to be a fundamental bottleneck, it can under some circumstances be overcome. For example, the size of the AB can be reduced by distracting activities [@Olivers2005; @Olivers2006; @Thomson2015a], or after following an intensive mental training program [@Slagter2007]. Others have tried to use non-invasive brain stimulation [@Dayan2013] as a means to influence the AB. Several studies have shown that repetitive transcranial magnetic stimulation (TMS) can improve target perception in AB tasks [@Cooper2004; @Arasanz2012; @Esterman2017]. Yet, as TMS did not show a differential effect for targets presented at shorter or longer lags, it did not affect the AB itself.

Transcranial direct current stimulation (tDCS) is another brain stimulation technique that has gained traction in the past two decades. In tDCS, an electrical current flows between an anodal and cathodal electrode, which can affect the excitability of the underlying cortex [@Gebodh2019a]. Anodal stimulation generally enhances cortical excitability, while cathodal stimulation may have an inhibitory effect [@Nitsche2000; @Nitsche2001] (though note that this does not hold in all cases [@Parkin2018], and the underlying physiology is complex [@Bikson2019; @Liu2018; @Stagg2018]).

@London2015 were the first to examine the effects of tDCS on the AB. They applied anodal and cathodal tDCS over the left dorsolateral prefrontal cortex (lDPLFC, with the other electrode on the right forehead)---one of the core brain areas implicated in the AB [@Slagter2010; @Hommel2006]. At the group level, tDCS did not appear to have any effects on AB size. However, anodal and cathodal tDCS did appear to systematically affect the AB within individuals, as their effects were negatively correlated. For a given individual, this negative correlation implies that when AB size increased (compared to a baseline measurement) during anodal tDCS, AB size would decrease during cathodal tDCS (or vice versa).

London and Slagter's [-@London2015] findings mesh well with earlier literature showing large individual differences in both the AB [@Willems2016] and effects of tDCS [@Krause2014]. However, it remains the only tDCS study of the AB to date. Also, the negative correlation between the effects of anodal and cathodal tDCS was based on an exploratory analysis. We thus decided to conduct another study aiming to replicate this finding.  

To foreshadow our results, like @London2015, we do not find a group effect of tDCS on the AB. However, the correlation between the effects of anodal and cathodal tDCS was also not significant. Although this indicates that the two studies may differ, a failure to reject the null hypothesis by itself does not tell us much [@Harms2018]: it is crucial to also take measures of the uncertainty and effect size in both studies into account [@Simonsohn2015].

Therefore, we employ a number of statistical methods to maximize the evidential value in these two studies. We ask three questions that all aim to evaluate to what extent the present study is a successful replication [@Zwaan2018; cf. @Camerer2018; @OSC2015] of @London2015. First, while the effect in our study was not significant, there might still be a meaningful effect that is simply smaller than anticipated. Therefore, we used equivalence testing [@Lakens2018] to answer the question "_is the correlation in study 2 significantly small?_". Second, although our result differs from @London2015, it could still be more consistent with their findings than with alternative explanations. So in addition, we asked "_are the correlations consistent across studies 1 and 2?_", and aimed to answer this question using prediction intervals [@Spence2016; @Patil2016] and replication Bayes factors [@Wagenmakers2016; @Verhagen2014]. Finally, it could be that the effect in our study alone is not sufficiently large, but the overall effect based on both studies is. This raises the question "_is the effect significant when combining study 1 and 2?_", which we addressed through meta-analysis [@Quintana2015;@Goh2016] and by pooling the data.

These questions address issues of reproducibility that are currently faced by many in the brain stimulation field [@Heroux2017], and in the cognitive neuroscience community at large [@Munafo2017; @Huber2019]. Therefore, aside from our focus on tDCS and the AB, an auxiliary goal of this chapter is to provide a tutorial on the statistical evaluation of replication studies. We hope this may prove useful to other researchers who find themselves in similar situations.

## Materials and Methods {#AB_tDCS-methods}

### Participants {#AB_tDCS-participants}

Fourty-eight participants took part in total, 8 of whom were excluded after the first session. One participant was excluded as a precaution because they developed an atypical headache after the first session, and we could not rule out this was related to the tDCS. Another stopped responding to our requests to schedule the second session. The remaining six participants were excluded because their mean T1 accuracy in the first session was too low, which would leave too few trials to analyze, because our T2 accuracy measure included only trials in which T1 was seen. We used a cut-off of 63% T1 accuracy as an exclusion criterium, which was two standard deviations below the mean of a separate pilot study (n = 10).

This left a final sample of 40 participants (29 female, mean age = 20.94, _SD_ = 2.45, range = 18--28). This sample size was determined a priori to slightly exceed @London2015 (n = 34).

The experiment and recruitment took place at the University of Amsterdam. All procedures for this study were approved by the ethics review board of the Faculty for Social and Behavioral Sciences, and complied with relevant laws and institutional guidelines. All participants provided their written informed consent and were compensated with course credit or €10 per hour (typically €65 for completing two full sessions).

### Procedure {#AB_tDCS-procedure}

The study procedures were identical to @London2015: participants received anodal and cathodal tDCS in separate sessions (Figure \@ref(fig:AB-tDCS-fig-procedure)), which typically took place exactly one week apart (cf. minimum of 48 hours in @London2015). The time in between served to keep the sessions as similar as possible, and to minimize the risk of tDCS carry-over effects. 18 participants received anodal tDCS in the first session and cathodal tDCS in the second, and vice versa for the remaining 22 participants.

<div class="figure">
<img src="AB_tDCS_files/figures/figure_1_procedure.png" alt="(ref:caption-AB-tDCS-fig-procedure)"  />
<p class="caption">(\#fig:AB-tDCS-fig-procedure)(ref:caption-AB-tDCS-fig-procedure)</p>
</div>

First, participants experienced the sensations induced by tDCS in a brief trial stimulation (see the [tDCS](#AB_tDCS-tDCS) section). Next, participants completed 20 practice trials of the task (see the [Task](#AB_tDCS-task) section). For the main portion of the experiment, participants performed three blocks of the task (Figure \@ref(fig:AB-tDCS-fig-procedure)): before tDCS (_baseline_), during anodal/cathodal tDCS (_tDCS_), and after tDCS (_post_). Finally, after completing the three blocks, participants filled in a questionnaire on tDCS-related adverse effects (see Table \@ref(tab:tab-AB-tDCS-AE) and Figure \@ref(fig:fig-AB-tDCS-AE) in Appendix \@ref(AB-tDCS-supplement)).

Within each block of the task, participants took a self-timed break every 50 trials (~5 minutes); between the blocks, the experimenter walked in. Participants performed the task for exactly 20 minutes during the _baseline_ and _post_ blocks. During the _tDCS_ block, the task started after the 1-minute ramp-up of the current was complete, and continued for 21 minutes (constant current, plus 1-minute of ramp-down).

(ref:caption-AB-tDCS-fig-procedure) __Experimental design__. After a baseline block without stimulation, participants performed the attentional blink task during 20 minutes of anodal (red) or cathodal (blue) tDCS, followed by a post-test block (also without stimulation). The second session (typically 7 days later) was identical, except that the tDCS polarity was reversed.

### Task {#AB_tDCS-task}

The attentional blink task (Figure \@ref(fig:AB-tDCS-fig-task)) was almost identical to the one used in @London2015 and @Slagter2013, which in turn was based on a task designed by @Dux2008. A rapid serial visual presentation stream of 15 letters (cf. 17 letters in @London2015) was shown on each trial, using Presentation software (Neurobehavioral Systems, Inc.). Each letter was displayed for 91.7 ms (11 frames at 120 Hz) on a dark gray background. The letters were presented in font size 40 (font: Courier New) at a viewing distance of 90 cm. On each trial, the letters were randomly sampled without replacement from the alphabet, excluding the letters I, L, O, Q, U and V, as they were too similar to each other. All distractor letters were mid-gray, whereas T1 and T2 were colored. T1 was red and always appeared at position 5 in the stream. T2 was green and followed T1 after either 2 distractors (_lag 3_) or 7 distractors (_lag 8_) (cf. lags 2, 4 and 10 in @London2015).

The letter stream was preceded by a fixation cross (same color as the letters) presented for 1750 ms (cf. 480 ms in @London2015) and followed by another fixation cross (cf. none in @London2015). Finally, the participant was prompted to type in (using a standard keyboard) the letter they thought was presented as T1 ("Which letter was red?"), followed by T2 ("Which letter was green?").

Trial duration varied slightly because both the T1 and T2 response questions were self-paced, so some participants completed more trials than others depending on their response times. On average, participants completed 130 short lag trials (_SD_ = 17; range = 78--163) and 65 long lag trials (_SD_ = 9; range = 39--87) per 20-minute block.

<div class="figure">
<img src="AB_tDCS_files/figures/figure_2_task.png" alt="(ref:caption-AB-tDCS-fig-task)"  />
<p class="caption">(\#fig:AB-tDCS-fig-task)(ref:caption-AB-tDCS-fig-task)</p>
</div>

(ref:caption-AB-tDCS-fig-task) __Attentional blink task__. Participants viewed rapid serial visual presentation streams of 15 letters, all of which were distractors (gray letters) except for T1 and T2. T1 was presented in red at position 5; T2 was presented in green and followed T1 after 2 distractors (_lag 3_, inside the AB window) or 7 distractors (_lag 8_, outside the AB window). At the end of the trial, participants reported the identity of T1 and then T2 (self-paced).

### tDCS {#AB_tDCS-tDCS}

Transcranial direct current stimulation was delivered online (i.e. during performance of the attentional blink task) using a DC-STIMULATOR PLUS (NeuroCare Group GmbH). The current was ramped up to 1 mA in 1 minute, stayed at 1 mA for 20 minutes, and was ramped down again in 1 minute.

One electrode was placed at F3 (international 10-20 system) to target the lDLPFC; the other was placed over the right forehead, centered above the eye (approximately corresponding to position Fp2). Both electrodes were 5 x 7 cm in size (35 cm^2^), leading to a current density of 0.029 mA/cm^2^. The montage and tDCS parameters are identical to @London2015, the only exception being the conductive medium. We used Ten20 conductive paste (Weaver and Company), because it was easier to apply concurrently with the EEG equipment (see the [EEG](#AB_tDCS-EEGdata) section); @London2015 used saline solution as a conductive medium, together with rubber straps to keep the electrodes in place.

Participants received either anodal tDCS (anode on F3, cathode on right forehead) or cathodal tDCS (cathode on F3, anode on right forehead) in separate sessions. The procedure was double-blinded: both the participant and the experimenters were unaware which polarity was applied in a given session. The experimenter loaded a stimulation setting on the tDCS device (programmed by someone not involved in data collection), without knowing whether it was mapped to anodal or cathodal tDCS. In the second session, the experimenter loaded a second setting mapped to the opposite polarity (half the dataset), or simply connected the terminals of the device to the electrodes in the opposite way.

At the start of the experiment, participants received a brief trial stimulation, based on which they decided whether or not they wanted to continue with the rest of the session. The experimenter offered to terminate the experiment in case tDCS was experienced as too uncomfortable, but none of the participants opted to do so. For the trial stimulation, the current was ramped up to 1 mA in 45 seconds, stayed at 1 mA for 15 seconds, and was ramped down again in 45 seconds.

### EEG {#AB_tDCS-EEGdata}

We also recorded EEG during all three task blocks. Originally, we aimed to analyze the EEG data to obtain a neurophysiological correlate of the individual differences in response to tDCS [@Krause2014; @Li2015b; @Harty2017]. However, since we did not replicate the behavioral effect in @London2015, we refrained from further analysis of the EEG data. Instead, we are making the EEG data publicly available [on the OpenNeuro platform](https://doi.org/10.18112/openneuro.ds001810.v1.1.0) [@Reteig2019_data]. The dataset is formatted according to the new Brain Imaging Data Structure (BIDS) standard [@Gorgolewski2016] for EEG [@Pernet2018], to facilitate re-use. We include the raw data, as well as the fully preprocessed data and the MATLAB code that generated it.

### Data analysis



Data were analyzed using R [Version 3.5.1; @R-base][^papaja_pkg_citations_AB_tDCS] from within RStudio [Version 1.1.463; @RStudio2016].



[^papaja_pkg_citations_AB_tDCS]: We, furthermore, used the R-packages *BayesFactor* [Version 0.9.12.4.2; @R-BayesFactor], *broom* [Version 0.5.1; @R-broom], *cowplot* [Version 0.9.99; @R-cowplot], *emmeans* [Version 1.3.0; @R-emmeans], *here* [Version 0.1; @R-here], *kableExtra* [Version 1.1.0; @R-kableExtra], *knitr* [Version 1.21; @R-knitr], *papaja* [Version 0.1.0.9842; @R-papaja], *psychometric* [Version 2.2; @R-psychometric], *pwr* [Version 1.2.2; @R-pwr], and *tidyverse* [Version 1.2.1; @R-tidyverse].



#### Group-level analysis

Repeated measures ANOVAs were conducted on T1 accuracy (percentage of trials where T1 was reported correctly) and T2|T1 accuracy (percentage of trials where T2 was reported correctly, out of the subset of T1-correct trials) using the *afex* package [Version NA; @R-afex]. The same factors were included for both repeated measures ANOVAs, following @London2015: Lag (3, 8), Block (baseline, tDCS, post), Stimulation (anodal, cathodal), and the between-subject factor Session order (anodal tDCS in the first session vs. cathodal tDCS in the first session). Effect sizes are reported as generalized eta-squared ($\hat{\eta}^2_G$) [@Bakeman2005]. Greenhouse-Geisser-adjusted degrees of freedom ($\mathit{df}^{GG}$) and p-values are reported as a correction for sphericity violations.

#### Individual differences analysis {#AB_tDCS-ind-diffs}

We reproduced the analysis behind Figure 4 of @London2015, which showed a differential effect of anodal vs. cathodal tDCS at the individual participant level. First, we calculated AB magnitude by subtracting T2|T1 accuracy at lag 3 from T2|T1 accuracy at lag 8. Next, change scores were created by subtracting AB magnitude in the _baseline_ block from the _tDCS_ and the _post_ blocks, respectively. The change scores in the anodal and cathodal session were then correlated to each other. Again following @London2015, we computed a partial correlation (using the *ggm* package [Version NA; @R-ggm]), attempting to adjust for variance due to Session order.

#### Replication analyses {#AB_tDCS-rep-analyses}

In contrast to @London2015, the analysis described in the previous section did not produce a significant correlation in our dataset. Therefore, we conducted five follow-up analyses that aim to quantify to what extent our results (do not) replicate @London2015. These all provide a complementary perspective on this question. First, we performed an [equivalence test](#eq) (1) to assess whether the effect in the present study was significantly smaller than in @London2015. While this procedure is more focused on hypothesis testing, we also constructed [prediction intervals](#pi) (2) to capture the range of effect sizes we can expect in a replication of @London2015. Both of these procedures are based on frequentist statistics, which cannot directly quantify the amount of evidence for a (null) hypothesis. Therefore, we also computed a [replication Bayes factor](#repBF) (3) that expresses whether the data in the present study are more likely under the null hypothesis that the effect is absent, vs. the alternative hypothesis that the effect is comparable to @London2015. Finally, we directly combined both studies and estimated the size of the overall effect, through [meta-analysis](#meta) (4) of both correlations, and by computing a new correlation on the [pooled dataset](#pool) (5). More details on each analysis can be found in the following sections, and the provided online resources.

##### Equivalence tests {#eq}

Equivalence tests can be used to test for the _absence_ of an effect of a specific size [see @Lakens2018 for a tutorial]. Usually, the effect size used for the test is the smallest effect size of interest (the SESOI). Typically, equivalence tests are two one-sided tests: one test of the null hypothesis that the effect exceeds the upper equivalence bound (positive SESOI), and one that the effect exceeds the lower equivalence bound (negative SESOI). However, a one-sided test is more appropriate here: @London2015 found that the effects of anodal and cathodal tDCS were anticorrelated, so we are only interested in negative effect sizes. This is known as an inferiority test [@Lakens2018].

We follow the "small telescopes" [@Simonsohn2015] approach to set the SESOI to $r_{33\%}$: the correlation that @London2015 had 33% power to detect. The reasoning behind this approach is that it is difficult to prove that an effect does not exist at all, but easier to show that it is surprisingly small. An equivalence test can suggest that the effect is unlikely to exceed $r_{33\%}$, such that the odds to detect it were stacked at least 2:1 against @London2015. That would not mean the effect does not exist at all, but it would mean the original evidence for the effect is not very convincing, as "too small a telescope" (in this case, an inadequate sample size) was used to reliably detect it.

There are many possible specifications of the SESOI, none of which are necessarily wrong or right [@Lakens2018]. We favored the "small telescopes" approach because it constitutes a relatively strict test---$r_{33\%}$ is much smaller than the original correlation in @London2015. Because the observed correlation in @London2015 could have overestimated the true correlation, it is prudent to set the SESOI to be smaller. Furthermore, the approach was specifically designed to evaluate replication results [@Simonsohn2015], and has been used previously in large-scale replication studies [e.g. @Camerer2018]. 

We conducted an inferiority test using the *TOSTER* package [Version NA; @R-TOSTER] against the null hypothesis that the correlation coefficient in the present study is at least as negative as $-r_{33\%}$. At a standard alpha level of 0.05, the test is significant if the 90% confidence interval around the observed correlation does not contain $r_{33\%}$. This would mean that the observed correlation should be considered "statistically inferior", as it is then significantly smaller (i.e. less negative) than $-r_{33\%}$.

##### Prediction interval {#pi}

Prediction intervals contain a range of values we can expect a new observation to fall within. In our case, the observation of interest is the correlation between the effects of anodal and cathodal tDCS. This correlation is estimated based on a sample, and is thus subject to sampling error: any two estimates of the correlation will almost never be exactly the same. Prediction intervals aim to quantify how dissimilar two estimates can be before we should be surprised.

Here, we construct a prediction interval around the original estimate of the correlation in @London2015. This prediction interval contains the range of correlation coefficients we can expect to see in the present study, given the results of @London2015. The width of the interval depends on the sample sizes of both studies, as larger samples will reduce variation in the estimates, leading to smaller prediction intervals [@Patil2016].

If the original study were replicated 100 times, 95 of the observed correlation coefficients would fall within the 95% prediction interval [@Patil2016]. Note that this definition is related to, but different from, a _confidence interval_, which quantifies uncertainty about the (unknown) true correlation in the population (95 out of every hundred constructed 95% confidence intervals contain the true population parameter). Because prediction intervals concern the next single observation, they make a more specific claim, and will be wider than confidence intervals.

We calculated a 95% prediction interval for correlations, following @Spence2016, using the *predictionInterval* package [Version NA; @R-predictionInterval].

##### Replication Bayes factor {#repBF}

Bayes factors can be used to express the relative evidence for the null ($H_0$) or alternative hypothesis ($H_1$) [@Wagenmakers2018a]. In a default Bayesian hypothesis test, $H_0$ states the effect size is absent (i.e. exactly zero); $H_1$ states that the effect is present (specified further by a prior distribution of effect sizes). 

In a replication context, we want to decide between two different scenarios [@Verhagen2014]. $H_0$ is the hypothesis of an idealized skeptic, who disregards the information from the original study and believes the effect is absent. The alternative hypothesis $H_r$ belongs to an idealized proponent, who believes that the effect is exactly as in the original study, i.e. their prior distribution is simply the posterior distribution of the original study. 

We used the replication Bayes factor test for correlations developed by @Wagenmakers2016. The replication Bayes factor $BF_{0r}$ expresses evidence for $H_0$ : "the correlation is 0" relative to $H_r$ : "the correlation is as in the original study". We use the interpretation scheme from @Wagenmakers2018, where $1 < BF_{0r} < 3$ constitutes "anecdotal evidence" for $H_0$, $3 < BF_{0r} < 10$ ~ "moderate evidence", and $10 < BF_{0r} < 30$ ~ "strong evidence".

##### Meta-analysis {#meta}

The outcomes from multiple studies on the same phenomenon can be combined through meta-analysis. Here we compute a meta-analytic estimate of the correlation based on the correlations observed here and as reported by @London2015, using the *metafor* package [Version NA; @R-metafor]. We weighed the estimate by sample size, so the present study will have a slightly higher influence on the meta-analytic effect size (because its sample size exceeds @London2015). We specified the meta-analysis as a fixed-effects model, because both studies are highly similar and from the same population (e.g., the experiments were conducted in the same location, and the sample was from the same university student population). With a fixed-effects analysis, we estimate the size of the effect _in the set of available studies_, meaning our inferences cannot generalize beyond. A random-effects meta-analysis would be appropriate in case the studies were more dissimilar, and if we sought an estimate of _the true effect in the population_, but we would need more than just two studies for this approach. Note that while meta-analyses are a powerful way to assess the overall effect in a series of studies, they are particularly vulnerable to false positives when the selection of studies (or any single study) is biased [@Ueno2016].

##### Pooling the data with @London2015 {#pool}

Another approach is to pool the single-subject data from both studies, and to re-calculate the partial correlation on the combined sample (n = 74). The main difference between the two studies is that @London2015 presented T2 at lags 2, 4 and 10; here we used lags 3 and 8. The long lags (lag 8 vs. lag 10) should be fairly comparable, as they are both well outside the attentional blink window [> 500 ms following T1; @MacLean2012]. However, there should be a sizeable performance difference at the short lags (lag 2 vs. lag 3), as the attentional blink is larger at lag 2 than lag 3. Therefore, we opted to also create a "lag 3" condition in the data from @London2015, by averaging T2|T1 accuracy at lag 2 and lag 4. The difference from lag 2 to 4 (and 4 to 10) in @London2015 looks fairly linear (see their Figure 3), so this seems a fair approximation of "true" lag 3 performance. Afterwards we recomputed the partial correlation between AB magnitude change scores as described previously (see the [Individual differences analysis](#AB_tDCS-ind-diffs) section).

Note that this analysis is tailored to this series of studies, and not generally advisable. To get a more accurate estimate of the effect at lag 3, it is necessary to redo the analysis on the larger, combined sample. But repeating a statistical test after collecting more data ("optional stopping") invalidates the interpretation of the p-value and can drastically increase the false positive rate [@Simmons2011]. This would only be acceptable when the analysis plan has been preregistered, and the false positive rate of sequential analyses is controlled [for potential solutions, see @Lakens2014]. We therefore do not report a p-value for this test, but only the effect size and its confidence interval. 

### Data, materials, and code availability

All of the data and materials from this study and the data from @London2015 are available on the [Open Science Framework](https://doi.org/10.17605/OSF.IO/Y6HSF). The analysis code is available on [GitHub](https://doi.org/10.5281/zenodo.3233872) (and also from our OSF page), in the form of an R notebook detailing all the analyses that we ran for this project, along with the results. We also include an Rmarkdown [@Xie2018] source file for this chapter that can be run to reproduce the pdf version of the text, along with all the figures and statistics.

## Results {#AB_tDCS-results}

### Group-level

<div class="figure">
<img src="AB_tDCS_files/figures/figure_3_group.png" alt="(ref:caption-fig-group)"  />
<p class="caption">(\#fig:fig-group)(ref:caption-fig-group)</p>
</div>

(ref:caption-fig-group) __No effects of tDCS on the attentional blink at the group level__. There was a clear attentional blink effect: a lower % T2 accuracy (given T1 correct: _T2|T1_; dashed lines) for _lag 3_ (T2 presented inside the attentional blink window) than _lag 8_ (T2 presented outside the attentional blink window, on par with _T1 accuracy_). However, the attentional blink did not change systematically over stimulation conditions (_anodal_, _cathodal_) and blocks (_pre_, _tDCS_, _post_). T1 accuracy (solid lines) was also not affected by tDCS.

Figure \@ref(fig:fig-group) shows the attentional blink (T2|T1 accuracy per lag) for each of the three blocks (pre, tDCS, post) and stimulation conditions separately. The summary statistics and ANOVA results for T2|T1 accuracy can be found in Tables \@ref(tab:tab-descriptives-T2) and \@ref(tab:tab-anova-T2).  There was a clear attentional blink effect on average (main effect of Lag, $F[1, 38] = 432.11$, $p < .001$), as T2|T1 accuracy for lag 8 was higher than lag 3. 

<table class="table" style="margin-left: auto; margin-right: auto;">
<caption>(\#tab:tab-descriptives-T2)Descriptive statistics for T2|T1 accuracy</caption>
 <thead>
<tr>
<th style="border-bottom:hidden" colspan="1"></th>
<th style="border-bottom:hidden; padding-bottom:0; padding-left:3px;padding-right:3px;text-align: center; " colspan="2"><div style="border-bottom: 1px solid #ddd; padding-bottom: 5px; ">First session: anodal (n = 18)</div></th>
<th style="border-bottom:hidden; padding-bottom:0; padding-left:3px;padding-right:3px;text-align: center; " colspan="2"><div style="border-bottom: 1px solid #ddd; padding-bottom: 5px; ">First session: cathodal (n = 22)</div></th>
</tr>
  <tr>
   <th style="text-align:left;">  </th>
   <th style="text-align:left;"> anodal </th>
   <th style="text-align:left;"> cathodal </th>
   <th style="text-align:left;"> anodal </th>
   <th style="text-align:left;"> cathodal </th>
  </tr>
 </thead>
<tbody>
  <tr grouplength="2"><td colspan="5" style="border-bottom: 1px solid;"><strong>baseline</strong></td></tr>
<tr>
   <td style="text-align:left; padding-left: 2em;" indentlevel="1"> lag 3 </td>
   <td style="text-align:left;"> 0.395 (0.149) </td>
   <td style="text-align:left;"> 0.486 (0.167) </td>
   <td style="text-align:left;"> 0.469 (0.211) </td>
   <td style="text-align:left;"> 0.423 (0.168) </td>
  </tr>
  <tr>
   <td style="text-align:left; padding-left: 2em;" indentlevel="1"> lag 8 </td>
   <td style="text-align:left;"> 0.826 (0.119) </td>
   <td style="text-align:left;"> 0.819 (0.095) </td>
   <td style="text-align:left;"> 0.854 (0.125) </td>
   <td style="text-align:left;"> 0.855 (0.087) </td>
  </tr>
  <tr grouplength="2"><td colspan="5" style="border-bottom: 1px solid;"><strong>tDCS</strong></td></tr>
<tr>
   <td style="text-align:left; padding-left: 2em;" indentlevel="1"> lag 3 </td>
   <td style="text-align:left;"> 0.415 (0.168) </td>
   <td style="text-align:left;"> 0.450 (0.165) </td>
   <td style="text-align:left;"> 0.460 (0.201) </td>
   <td style="text-align:left;"> 0.444 (0.188) </td>
  </tr>
  <tr>
   <td style="text-align:left; padding-left: 2em;" indentlevel="1"> lag 8 </td>
   <td style="text-align:left;"> 0.787 (0.131) </td>
   <td style="text-align:left;"> 0.819 (0.098) </td>
   <td style="text-align:left;"> 0.830 (0.115) </td>
   <td style="text-align:left;"> 0.849 (0.096) </td>
  </tr>
  <tr grouplength="2"><td colspan="5" style="border-bottom: 1px solid;"><strong>post</strong></td></tr>
<tr>
   <td style="text-align:left; padding-left: 2em;" indentlevel="1"> lag 3 </td>
   <td style="text-align:left;"> 0.437 (0.171) </td>
   <td style="text-align:left;"> 0.451 (0.160) </td>
   <td style="text-align:left;"> 0.453 (0.190) </td>
   <td style="text-align:left;"> 0.447 (0.164) </td>
  </tr>
  <tr>
   <td style="text-align:left; padding-left: 2em;" indentlevel="1"> lag 8 </td>
   <td style="text-align:left;"> 0.783 (0.118) </td>
   <td style="text-align:left;"> 0.825 (0.098) </td>
   <td style="text-align:left;"> 0.840 (0.145) </td>
   <td style="text-align:left;"> 0.846 (0.120) </td>
  </tr>
</tbody>
<tfoot><tr><td style="padding: 0; border: 0;" colspan="100%">
<sup></sup> Values are "Mean (SD)"</td></tr></tfoot>
</table>

Effects of tDCS at the group-level should manifest as a three-way interaction between Block, Stimulation, and Lag. As in @London2015, this interaction was not significant ($F[1.77, 67.17] = 2.77$, $p = .076$). However, the higher-order interaction with Session order did reach significance ($F[1.77, 67.17] = 7.25$, $p = .002$). This interaction appears to be mostly driven by a learning effect across sessions and blocks (the Session order by Stimulation by Lag interaction). From the first to the 2nd session, lag 3 performance improved, while lag 8 performance declined somewhat (leading to a smaller attentional blink). This change was stronger in participants that received anodal tDCS in the first session, and less pronounced in the cathodal-first group. We do not consider this a genuine effect of tDCS on the attentional blink, because there is no clear reason why these randomized groups should differ, and because the largest difference between the anodal and cathodal session occurred in the baseline block already (see Table \@ref(tab:tab-descriptives-T2)).

We ran the same repeated measures ANOVA for T1 accuracy (Table \@ref(tab:tab-anova-T1)). On average, participants correctly identified T1 in 82% of trials (Figure \@ref(fig:fig-group)), which is comparable to previous studies using this task [86% in @London2015; in 82% in @Slagter2013]. T1 accuracy was also slightly lower for lag 3 than lag 8 (main effect of Lag, $F[1, 38] = 29.23$, $p < .001$). There was a main effect of Block, reflecting that T1 accuracy decreased _within_ a session ($F[1.89, 71.87] = 6.64$, $p = .003$). Finally, T1 performance also decreased _across_ the sessions (interaction between Session order and Stimulation: $F[1, 38] = 11.24$, $p = .002$).

In sum, we conclude that there is no significant effect of tDCS on the attentional blink or T1 accuracy at the group level, in agreement with @London2015.

\begingroup
\setlength{\LTleft}{-20cm plus -1fill}
\setlength{\LTright}{\LTleft}

<caption>(\#tab:tab-anova-T2)</caption>

<caption>*Repeated measures ANOVA on T2|T1 accuracy*</caption>



Effect                                                           $F$      $\mathit{df}_1^{GG}$   $\mathit{df}_2^{GG}$   $p$      $\hat{\eta}^2_G$ 
---------------------------------------------------------------  -------  ---------------------  ---------------------  -------  -----------------
Session order                                                    0.33     1                      38                     .568     .006             
Block                                                            1.13     1.91                   72.71                  .328     .001             
Stimulation                                                      2.47     1                      38                     .125     .002             
Lag                                                              432.11   1                      38                     < .001   .634             
Session order $\times$ Block                                     0.29     1.91                   72.71                  .741     .000             
Session order $\times$ Stimulation                               5.55     1                      38                     .024     .005             
Session order $\times$ Lag                                       0.48     1                      38                     .494     .002             
Block $\times$ Stimulation                                       0.28     1.91                   72.51                  .747     .000             
Block $\times$ Lag                                               1.67     1.7                    64.73                  .199     .001             
Stimulation $\times$ Lag                                         0.10     1                      38                     .751     .000             
Session order $\times$ Block $\times$ Stimulation                1.93     1.91                   72.51                  .154     .001             
Session order $\times$ Block $\times$ Lag                        0.24     1.7                    64.73                  .752     .000             
Session order $\times$ Stimulation $\times$ Lag                  5.84     1                      38                     .021     .002             
Block $\times$ Stimulation $\times$ Lag                          2.77     1.77                   67.17                  .076     .001             
Session order $\times$ Block $\times$ Stimulation $\times$ Lag   7.25     1.77                   67.17                  .002     .003             

\endgroup

\begingroup
\setlength{\LTleft}{-20cm plus -1fill}
\setlength{\LTright}{\LTleft}

<caption>(\#tab:tab-anova-T1)</caption>

<caption>*Repeated measures ANOVA on T1 accuracy*</caption>



Effect                                                           $F$     $\mathit{df}_1^{GG}$   $\mathit{df}_2^{GG}$   $p$      $\hat{\eta}^2_G$ 
---------------------------------------------------------------  ------  ---------------------  ---------------------  -------  -----------------
Session order                                                    0.96    1                      38                     .332     .018             
Block                                                            6.64    1.89                   71.87                  .003     .010             
Stimulation                                                      0.00    1                      38                     .996     .000             
Lag                                                              29.23   1                      38                     < .001   .013             
Session order $\times$ Block                                     0.60    1.89                   71.87                  .540     .001             
Session order $\times$ Stimulation                               11.24   1                      38                     .002     .030             
Session order $\times$ Lag                                       0.04    1                      38                     .844     .000             
Block $\times$ Stimulation                                       0.24    1.92                   73.08                  .777     .000             
Block $\times$ Lag                                               1.91    1.93                   73.2                   .158     .001             
Stimulation $\times$ Lag                                         0.31    1                      38                     .584     .000             
Session order $\times$ Block $\times$ Stimulation                9.94    1.92                   73.08                  < .001   .007             
Session order $\times$ Block $\times$ Lag                        0.19    1.93                   73.2                   .821     .000             
Session order $\times$ Stimulation $\times$ Lag                  0.96    1                      38                     .333     .000             
Block $\times$ Stimulation $\times$ Lag                          0.31    1.86                   70.75                  .718     .000             
Session order $\times$ Block $\times$ Stimulation $\times$ Lag   0.53    1.86                   70.75                  .580     .000             

\endgroup

### Individual differences

Our main aim was to replicate @London2015, who found a negative correlation between AB magnitude change scores (comparing the _tDCS_ and _baseline_ blocks) in the anodal and cathodal sessions (_r_(31) = -.45, _p_ = .009). Their interpretation was that the effects of anodal and cathodal tDCS were anti-correlated: those participants that improve their performance (i.e., show a smaller AB) due to anodal tDCS tend to worsen due to cathodal tDCS, and vice versa.

We ran the same partial correlation (attempting to adjust for Session order) between the anodal and cathodal AB magnitude change scores (_tDCS_ - _baseline_) on our data (Figure \@ref(fig:fig-corr)). However, here the resulting correlation did not go in the same direction (_r_(37) = .02), and was not significant (_p_ = .899). In the next sections, we present a number of follow-up analyses that further explore this difference in results between both studies (see the [Replication analyses](#AB_tDCS-rep-analyses) subsection in the [Methods](#AB_tDCS-methods) section).

<div class="figure">
<img src="AB_tDCS_files/figures/figure_4_corr.png" alt="(ref:caption-fig-corr)"  />
<p class="caption">(\#fig:fig-corr)(ref:caption-fig-corr)</p>
</div>

(ref:caption-fig-corr) __The effects of anodal and cathodal tDCS are not correlated in the present study.__ Data points show AB magnitude change scores (_tDCS - baseline_, _post - baseline_) for each participant in the study, in the _anodal_ session (x-axis) and the _cathodal_ session (y-axis). While @London2015 found a negative partial correlation (for _tDCS - baseline_), suggesting opposite effects of anodal and cathodal tDCS, this effect appears to be absent here. The partial correlation coefficients (attempting to adjust for Session order) and p-values are printed in the upper left.

#### Is the correlation in study 2 significantly small?

@London2015 found a medium- to large correlation (_r_ = -.45), but the correlation we find here is much smaller (_r_ = .02). We use equivalence testing (@Lakens2018; see the [Equivalence tests](#eq) subsection in the [Methods](#AB_tDCS-methods) section) to assess whether this correlation is significantly smaller than a smallest effect size of interest (SESOI). Following the "small telescopes" approach [@Simonsohn2015], we set the SESOI to $r_{33\%}$, the correlation @London2015 had 33% power to detect. Given their sample size of 34 participants, $r_{33\%}$ = .27.

An inferiority test shows that the correlation here is significantly less negative than $-r_{33\%}$ (_p_ = .038) (Figure \@ref(fig:fig-rep-estimate)), although only by a small margin. The effect is therefore "statistically inferior": the correlation does not exceed the lower equivalence bound ($-r_{33\%}$ = -.27). By this definition, the correlation is too small (i.e. not negative enough) to be considered meaningful, indicating that we did not successfully replicate @London2015.

#### Are the correlations consistent across studies 1 and 2?

To evaluate whether the correlation in the present study was to be expected based on @London2015, we constructed a 95% _prediction interval_ (PI) [@Spence2016], using the correlation in @London2015 and the sample size of both studies (see the [Prediction interval](#pi) subsection of the [Methods](#AB_tDCS-methods) section).

The 95% PI[-0.82, -0.05] around the original correlation (_r_ = -.45) is very wide, so almost any negative correlation would fall within it. However, it does not include the replication result (_r_ = .02) (Figure \@ref(fig:fig-rep-estimate)). Assuming the results of both studies differ only due to sampling error, the correlation observed  here has a 95% chance to fall within the interval. This means the correlation in our replication study is inconsistent with the correlation in @London2015, and thus that the replication should not be considered successful.

Another approach to quantify the consistency between study 1 and 2 is to construct a replication Bayes Factor [@Wagenmakers2016]. We use this Bayes factor to assess evidence for $H_0$ : "the effects of anodal and cathodal tDCS are uncorrelated" relative to $H_r$ : "the effects of anodal and cathodal tDCS are anticorrelated as in @London2015" (see the [Replication Bayes factor](#repBF) subsection of the [Methods](#AB_tDCS-methods) section).

This replication Bayes factor expresses that the data are $BF_{0r}$ = 9.66 times more likely under $H_0$ than under $H_r$. This constitutes moderate to strong evidence that the effect is absent vs. consistent with @London2015, and thus that the effect did not replicate.

#### Is the effect significant when combining study 1 and 2?

The sample size in both study 1 (n = 34) and 2 (n = 40) is on the lower end. Therefore, we might get a more accurate estimate of the size of the effect when combining both studies.

The meta-analytic estimate of the correlation is _r_ = -0.20, 95%CI[-0.42, 0.04], _p_ = .094 (Figure \@ref(fig:fig-rep-estimate)). So, when combining the correlation from @London2015 and the correlation observed here, the overall effect is no longer significant.

In addition, we pooled the data from both studies at the single-subject level and re-calculated the partial correlation on the combined sample (n = 74). To make the datasets as comparable as possible, we first averaged over T2|T1 accuracy at lags 2 and 4 in @London2015, to mimic a "lag 3" condition cf. the present study (Figure \@ref(fig:fig-corr-pooled)).

<div class="figure">
<img src="AB_tDCS_files/figures/figure_5_pooledcorr.png" alt="(ref:caption-fig-corr-pooled)"  />
<p class="caption">(\#fig:fig-corr-pooled)(ref:caption-fig-corr-pooled)</p>
</div>

(ref:caption-fig-corr-pooled) __The effects of anodal and cathodal tDCS are also not correlated when pooling data from both studies.__ As in Figure \@ref(fig:fig-corr), data points show AB magnitude change scores (_tDCS_ - _baseline_) in the _anodal_ session (x-axis) and the _cathodal_ session (y-axis), but now for each participant in @London2015 (_study 1_) and the present study (_study 2_). While @London2015 found a negative partial correlation, suggesting opposite effects of anodal and cathodal tDCS, this effect appears to be absent when based on the combined data of both studies. The partial correlation coefficient (attempting to adjust for Session order) is printed in the upper left.

The partial correlation based on the pooled data is _r_(71) = -.18. Thus, the correlation across a combination of both samples is a lot smaller than in @London2015, and slightly smaller still than the meta-analytic estimate that included the original correlation from @London2015 (Figure \@ref(fig:fig-rep-estimate)).

<div class="figure">
<img src="AB_tDCS_files/figures/figure_6_estimates.png" alt="(ref:caption-fig-rep-estimate)"  />
<p class="caption">(\#fig:fig-rep-estimate)(ref:caption-fig-rep-estimate)</p>
</div>

(ref:caption-fig-rep-estimate) __Summary of all the replication analyses__ (with exception of the replication Bayes Factor). The first two rows show the partial correlation (attempting to adjust for Session order) between the AB magnitude change scores (tDCS - baseline) in the anodal and cathodal sessions, for @London2015 and the present study. The first is significantly negative, the second is slightly positive and not significant, because its 95% confidence interval (CI) overlaps with zero. The third row shows the 90% CI around the correlation in the present study. Because this interval does not overlap with the "small telescopes" effect size, (indicated by the `x`: $-r_{33\%}$ = -.27), this correlation is significantly smaller. The fourth row shows the  95% prediction interval (PI) around the correlation in @London2015. Because this interval does not overlap with the correlation in the present study, both correlations are not consistent. The final two rows show the overall effect when the two correlations are meta-analyzed, and when one correlation is computed over the pooled data from both studies. Neither are significant (95% CI overlaps with zero). Thus, our replication analyses all suggest that we failed to replicate London & Slagter (2015), and when the results are examined in combination, no evidence in support of a negative relationship between the AB magnitude change scores (_tDCS - baseline_) in the anodal and cathodal sessions is obtained.

## Discussion {#AB_tDCS-discussion}

@London2015 were the first to uncover a potential effect of tDCS on the AB. Although there was no group-level effect of tDCS, they found a negative correlation between the effects of anodal and cathodal tDCS on T2|T1 accuracy across individuals. This analysis suggested an interesting pattern of individual differences in response to tDCS: those that tended to benefit from anodal tDCS (i.e., whose AB became smaller compared to baseline) would tend to worsen during cathodal tDCS, and vice versa. This finding seemed plausible given the substantial and well-documented individual differences in both the AB [@Willems2016] and the effects of tDCS [@Krause2014].

We conducted a replication study, and again found no effect of tDCS at the group level. However, in contrast to @London2015, the correlation between the AB magnitude change scores (tDCS - baseline) in the anodal and cathodal sessions here is not significant, and not in the same direction. We also computed several statistical measures of replication success focused on the negative correlation between anodal and cathodal tDCS. These showed that the correlation is smaller than in @London2015, and than the smallest correlation they could have reasonably detected (i.e., an equivalence test for the lower bound of $r_{33\%}$ [@Simonsohn2015] is significant). The difference between the two studies is greater than expected based on sampling error alone (i.e., the correlation in the present study falls outside of the 95% prediction interval). Further, the data provide moderate to strong evidence for the null hypothesis of zero correlation compared to the alternative that the correlation is as in @London2015 (i.e. we found a replication Bayes factor in favor of the null hypothesis of ~10). Finally, combining both studies yields a smaller and non-significant correlation (both in a meta-analysis and by pooling the data).

The overall picture is consistent: all measures indicate that the present study is not a successful replication of @London2015. But because both studies were similar in design and sample size, it is not warranted to dismiss the findings of @London2015. Our analysis revealed substantial variation between both estimates of the effect, and so the conclusion whether tDCS is effective should not be based on any single study.

Still, the marked difference in results of both studies is surprising: they are similar enough that the present study could be considered a direct replication [@Zwaan2018] of @London2015. We used the exact same electrode montage and tDCS parameters, followed the same experimental design (Figure \@ref(fig:AB-tDCS-fig-procedure)), ran the experiment in the same location with the same participant population, and used a virtually identical task. Nevertheless, there are some discrepancies between the studies that could have contributed to the different outcome. 

The most important difference is that @London2015 presented T2 at lags 2, 4, and 10, whereas we used lags 3 and 8. This means that AB magnitude (the difference in T2|T1 accuracy between the shortest and longest lag) was on average smaller in the present study. We introduced the change for precisely this reason: to have about as many trials for the EEG analyses in which T2 was seen vs. missed, we needed the AB to be smaller. But this increase in average T2|T1 accuracy may have also reduced the between-subject variability that is essential for analyses that capitalize on individual differences. Indeed, from Figure \@ref(fig:fig-corr-pooled) it seems that the sample in @London2015 had a larger spread, at least in the change scores for AB magnitude.

Though the change in lags is probably the most important, the concurrent EEG measurement did introduce other differences as well. Each session took longer to complete, because the EEG setup required extra time, and the pace of the task was slowed down with extra inter-stimulus intervals. Finally, the current flow could have changed due to the presence of the EEG cap and electrodes, as well as the use of conductive paste instead of saline solution.

At the group level, our results are in agreement with @London2015: we find no differential effects of anodal and cathodal tDCS on the AB. This strongly suggests that the AB is not amenable to tDCS over the lDPLFC, at least with our fairly standard electrode montage and stimulation parameters [@Santarnecchi2015]. These null results are consistent with recent reviews and meta-analyses highlighting there is little evidence that prefrontal tDCS can be used to enhance cognition [@Medina2017]; or if so, that its effects are difficult to predict [@Tremblay2014a], rather small [@Dedoncker2016a], and restricted to a limited subset of outcome measures and stimulation parameters [@Imburgio2018].

Interpreting null results is always difficult, especially in brain stimulation studies [@DeGraaf2018]. Ultimately, a myriad of possible underlying explanations may apply, most of which we have no direct access to. For one, we cannot be sure that the current density in the lDLPFC reached sufficient levels [@Kim2014; @Opitz2015] based on our montage alone. More precise targeting of the stimulation towards the lDPLFC [@Datta2009] and modeling of the current flow [@DeBerker2013; @Karabanov2019] could provide some more confidence. Still, it would be difficult to verify that anodal tDCS and cathodal tDCS indeed had an opposite effect on cortical excitability [@Bestmann2014; @Bestmann2017]. This assumption holds in many cases, and would provide a plausible explanation [@Krause2014] for the negative correlation in @London2015. But ideally, it should be validated with direct measures of cortical excitability. Such measures are hard to obtain, although some recent studies suggest that combining tDCS with magnetic resonance spectroscopy can be used for this purpose [@Filmer2019; @Antonenko2019; @Talsma2018].

It is also possible that we do not find an effect because the studies did not have sufficient statistical power [@Minarik2016]. Especially for the individual differences analyses, the sample size in both studies is on the lower end. For example, to detect a medium-sized correlation (_r_ = 0.3) with 80% power, the required sample size is n = 84. We do approach this sample size when combining both studies (n = 74). Also, the correlation in @London2015 was larger (_r_ = -0.45), but we cannot have much confidence in the precision of this estimate. To estimate the size of a medium correlation (_r_ = 0.3) within ± 0.15 with 90% confidence, a sample size of n = 134 would be required [@Schonbrodt2013]. Although our analyses suggest that the correlation is small if anything, this means we cannot accurately estimate how small---even with the combined sample.

These are all decisions to be made at the design stage, which can increase the value of a null result [@DeGraaf2018]. However, after the data are in, additional tools are available to increase the value of a null result [@Harms2018], especially in the case of a replication study [@Simonsohn2015]. Here, we used a selection of these tools to scrutinize our own two studies on tDCS effects on the attentional blink, as these are the only ones available to date.

In addition, we hope this chapter provides inspiration for others in the fields of brain stimulation and cognitive neuroscience. Many speak of a crisis of confidence [@Heroux2017] and fear that the current literature is lacking in evidential value [@Medina2017]. This is certainly not a unique development, as these sentiments [@Baker2015] and low rates of replication abound in many research areas [@OSC2015; @Camerer2018; @Klein2018]. But it is perhaps aggravated by the fact that the brain stimulation field has not matured yet [@Parkin2015]. 

To make sure the literature accurately reflects the efficacy of the technique, it is crucial to combat publication bias. Positive results are heavily over-represented in most of the scientific literature, [@Ferguson2012; @Franco2014; @Fanelli2012], which has recently prompted a call to brain stimulation researchers to also publish their null results[^frontiers]. Publishing null results and replication studies---and making the most of their interpretation---is crucial to better this situation.

[^frontiers]: Research Topic in Frontiers, "Non-Invasive Brain Stimulation Effects on Cognition and Brain Activity: Positive Lessons from Negative Findings": <https://www.frontiersin.org/research-topics/5535>