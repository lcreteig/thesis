---
output:
  pdf_document: default
  html_document: default
---


# Spontaneous eye blink rate does not predict attentional blink size, nor the effects of tDCS on attentional blink size {#AB-tDCS-sEBR}
\chaptermark{sEBR \& tDCS do not influence attentional blink size}

\vspace*{\fill}

---

\small
\noindent
_This chapter is in preparation as_: Reteig, L. C., Newman, L. A., Ridderinkhof, K. R., & Slagter, H. A. (n.d.). Spontaneous eye blink rate does not predict attentional blink size, nor the effects of tDCS on attentional blink size.
\newpage
\normalsize

`<p><strong>Abstract</strong></p>`{=html}
`\begin{abstract}`{=latex}
The attentional blink (AB) phenomenon illustrates our limited capacity to process incoming information. When tasked to identify two targets embedded in close temporal proximity in a stream of distractors, the second target is often missed. The magnitude of the AB (the proportion of times this second target is missed) varies considerably across individuals. Here, we examined two factors that might drive these individual differences: baseline dopamine levels and cortical excitability. We measured spontaneous Eye Blink Rate (sEBR) as a proxy for dopamine levels, and attempted to manipulate cortical excitability using transcranial Direct Current Stimulation (tDCS). Participants (n=40) performed an AB task before, during, and after anodal or cathodal tDCS to the left dorsolateral prefrontal cortex, in two separate sessions. At the start of each session, we measured their sEBR. sEBR had good test-retest reliability across the sessions. Test-retest reliability for AB magnitude was moderate, but in line with previous reports. We found no linear- or U-shaped relationship between sEBR and AB magnitude at baseline (before tDCS onset), with more evidence for the null hypothesis. Lastly, we also did not find an association between sEBR and the effect of tDCS on AB magnitude (neither anodal nor cathodal tDCS, compared to baseline). Larger-scale studies with more direct measures of dopamine and cortical excitability are called for to advance our understanding of their effects on the attentional blink, and rapid, selective gating of information, more generally.
`\end{abstract} \newpage`{=latex}


## Introduction {#AB_sEBR-introduction}

We are constantly barraged by sensory information beyond our limited processing capacity. This is clearly brought to light by the attentional blink (AB) phenomenon: detection of the second of two targets (T2) is impaired for 100--500 ms after the initial target (T1) is presented within a stream of distractors [@Raymond1992; for reviews, see @Dux2009; @Martens2010]. Although the AB would seem to be a fundamental bottleneck, there are large individual differences in the magnitude of the AB (i.e., the proportion of times that T2 is missed vs. seen) [@Willems2016]. Some participants nearly always miss T2, a small group of others do not have an AB at all [e.g. @Martens2006], and most participants fall somewhere between these two extremes. The source of these individual differences remains largely unknown. Here, we examine two potential modulators of AB magnitude: baseline dopamine levels, and changes in cortical excitability induced by transcranial Direct Current Stimulation (tDCS).

@London2015 were the first to study whether the effects of tDCS on the AB differ across individuals. tDCS can change the excitability of neurons from outside the skull, by passing a weak electrical current between an anodal and cathodal electrode [@Gebodh2019a]. Anodal and cathodal tDCS are generally assumed to have opposite effects on cortical excitability. While this holds in non-human work [@Purpura1965; @Bindman1964] and the human motor cortex [@Nitsche2000; @Nitsche2001], it is likely an oversimplification [@Liu2018] and might not generalize to other brain areas [@Bestmann2014; @Parkin2015]. Nonetheless, @London2015 found a differential effect of anodal vs. cathodal tDCS over the left dorsolateral prefrontal cortex (lDLPFC) at the individual subject level. Those individuals that showed a decrease in AB magnitude during anodal tDCS (compared to a baseline measurement) tended to show an increase during cathodal tDCS, and vice versa.

Many factors may influence the effect of tDCS on a given individual [@Krause2014; @Li2015b]. One of the most prominent candidates is baseline cortical excitability, i.e. the balance of excitation and inhibition in the cortex (before tDCS onset). @Krause2013 suggested that the behavioral outcome of tDCS is governed by an Inverted-U-shaped relationship with cortical excitability. The effect of anodal/cathodal tDCS on a given individual would then depend on his or her position on this excitability axis (Figure \@ref(fig:AB-sEBR-fig-model), left panel). Individuals with excess excitation compared to the optimum would benefit from cathodal but not anodal tDCS, whereas over-inhibited individuals would benefit from anodal but not cathodal tDCS. This matches the pattern of performance changes reported by @London2015.

In the present study, we aimed to extend the findings of @London2015 by examining the influence of dopamine. Dopaminergic projections are pervasive and shape global brain activity [@Schultz2007; @Bjorklund2007]. In particular, dopaminergic signalling between the striatum and the prefrontal cortex is crucial for healthy cognitive functioning [@Nieoullon2002; @Robbins2009]. Striatal dopamine has been linked to updating of goal representations and gating of information in the prefrontal cortex [@Cohen2004; @Cools2011]---processes that both seem to go awry in the AB. Indeed, several lines of evidence implicate dopamine in the AB. First, activity in the ventral striatum differentiates between trials in which T2 was seen or missed, both when measured with intracranial EEG [@Slagter2017] and with fMRI [@Slagter2010]. Changing dopamine levels by administering L-DOPA can change the size of the AB in Parkinson patients [@Slagter2016a] (although dopamine antagonists in healthy individuals might not affect the AB [@Gibbs2007]). Finally, AB size is correlated to dopamine receptor binding in the striatum as measured with Positron Emission Tomography (PET) [@Slagter2012].

The relationship between dopamine and cognitive function appears to follow an Inverted-U shape, where both too high and too low levels of dopamine hurt performance [@Cools2011]. @Slagter2012 proposed this also holds for the AB, which should be smallest at an optimal level of (striatal) dopamine. Too low levels of dopamine would restrict gating such that T2 is prevented from being processed; too high levels of dopamine would cause interference by "opening the gate too far" such that distractors are also processed. However, this model has not been formally tested, partly because it is so difficult to assess dopamine in humans without invasive measures such as PET.

There is converging evidence that spontaneous Eye Blink Rate (sEBR) could serve as such a non-invasive index of striatal dopamine [for a review, see @Jongkees2016]. One study indeed found a negative correlation between sEBR and the AB [@Colzato2008], suggesting that individuals with higher levels of dopamine have a smaller AB. However, a later study was unable to replicate this result [@Slagter2013].

No study to date has investigated the combined effects of dopamine and tDCS on the AB. But we do know that dopamine is an important moderator of the neurophysiological effects of tDCS [@Stagg2011b]. Dopaminergic activity is necessary for tDCS to have physiological after-effects, as these are abolished when dopamine receptors are blocked [@Nitsche2006]. Dopamine also shapes the time course and direction of tDCS-induced changes in cortical excitability: dopamine agonists may prolong the inhibitory effects of cathodal tDCS, and flip the anodal effect from excitatory to inhibitory [@Kuo2008].

Furthermore, two recent studies suggest that both tDCS and dopamine levels interact to determine cognitive performance in a systematic manner [@Wiegand2016]. These capitalize on genetic differences in dopamine activity caused by a common polymorphism of the gene coding for the COMT enzyme. This enzyme regulates dopamine levels, especially in the prefrontal cortex [@Kaenmaki2010]. Individuals that are homozygous for the Met-allele of the gene exhibit higher levels of cortical dopamine; individuals homozygous for the Val-allele exhibit lower levels of dopamine [@Schacht2016]. In one study, cathodal tDCS decreased performance on a go-no go task, but only in Val-homozygotes [@Nieratschker2015]; in the other study, anodal tDCS decreased performance on a different aspect of the task, and only in Met-homozygotes [@Plewnia2013]. @Wiegand2016 synthesized these findings in a model (Figure \@ref(fig:AB-sEBR-fig-model), right panel), proposing that individuals with low dopaminergic tone (e.g. Val-homozygotes) benefit from anodal but not cathodal tDCS, whereas individuals with high dopaminergic tone (e.g. Met-homozygotes) benefit from cathodal but not anodal tDCS. The outcome of anodal or cathodal tDCS would then differ as a function of baseline dopamine levels, which could provide another explanation for individual differences like those reported by @London2015.

In the present study, we aimed to shed more light on the relation between dopamine and the AB, as well as the modulatory role that dopamine might play in the effects of tDCS on the AB. Following @London2015, participants performed an AB task before, during, and after anodal or cathodal tDCS to the lDLPFC, in two separate sessions. At the start of each session, we measured sEBR as a proxy for baseline dopamine levels. First, we investigated whether sEBR is a reliable measure, as there is little data on the test-retest reliability of sEBR [@Jongkees2016]. Our study design with two sEBR-measurements per individual is uniquely suited to help fill this gap. Second, we examined how sEBR relates to AB magnitude. One study found a significant negative correlation [@Colzato2008], but this was not replicated in a second study [@Slagter2013]. Furthermore, both of these studies only tested for a linear relationship, although there is mounting evidence that the relationship between dopamine and cognitive performance is Inverted-U-shaped [@Cools2011]. Third, we assessed whether the effects of tDCS on AB magnitude depend on sEBR. Following the model in Figure \@ref(fig:AB-sEBR-fig-model) [@Krause2013; @London2015; @Wiegand2016], anodal tDCS should increase performance (i.e., decrease AB magnitude) in low dopamine (i.e., low sEBR) individuals, but decrease performance in high dopamine individuals, and vice versa for cathodal tDCS.

<div class="figure">
<img src="AB_sEBR_files/figures/figure_1_model.png" alt="(ref:caption-AB-sEBR-fig-model)"  />
<p class="caption">(\#fig:AB-sEBR-fig-model)(ref:caption-AB-sEBR-fig-model)</p>
</div>

(ref:caption-AB-sEBR-fig-model) __Model where AB task performance is dependent on cortical excitability [left, @London2015] and dopamine levels [right, @Wiegand2016]__. Whether anodal (red arrows) or cathodal (blue arrows) tDCS improves performance depends on the baseline starting point on these axes, as shown in two example cases. First, an individual with relatively low levels of dopamine / cortical excitability (diamond shape) should benefit from anodal tDCS (as they move closer to the optimum), whereas cathodal tDCS would be detrimental (as they are pushed further away from the optimum). Reversely, an individual with high levels of dopamine / cortical excitability (square shape) would benefit from cathodal but not anodal tDCS.

## Materials and methods {#AB_sEBR-methods}

A different set of results based on this dataset were reported in Chapter \@ref(AB-tDCS-EEG). We include the full materials and methods here for convenience.[^methods_overlap]

[^methods_overlap]: Compared to Chapter \@ref(AB-tDCS-EEG), the [Participants](#AB_sEBR-participants), [Task](#AB_sEBR-task), and [tDCS](#AB_sEBR-tDCS) sections are virtually identical; the [Procedure](#AB_sEBR-procedure) section has been adapted to include the sEBR measurement, the [Statistical analysis](#AB_sEBR-stats) and [sEBR](#AB_sEBR-sEBR) sections are entirely novel.

### Participants {#AB_sEBR-participants}

Fourty-eight participants took part in total, 8 of whom were excluded after the first session. One participant was excluded as a precaution because they developed an atypical headache after the first session, and we could not rule out this was related to the tDCS. Another stopped responding to our requests to schedule the second session. The remaining six participants were excluded because their mean T1 accuracy in the first session was too low, which would leave too few trials to analyze, because our T2 accuracy measure included only trials in which T1 was seen. We used a cut-off of 63% T1 accuracy as an exclusion criterium, which was two standard deviations below the mean of a separate pilot study (n = 10).

This left a final sample of 40 participants (29 female, mean age = 20.94, _SD_ = 2.45, range = 18--28). This sample size was determined a priori to slightly exceed @London2015 (n = 34). Mean T1 accuracy in the remaining 40 participants was 82%, which is comparable to previous studies using this task [86% in @London2015; in 82% in @Slagter2013].

The experiment and recruitment took place at the University of Amsterdam. All procedures for this study were approved by the ethics review board of the Faculty for Social and Behavioral Sciences, and complied with relevant laws and institutional guidelines. All participants provided their written informed consent and were compensated with course credit or €10 per hour (typically €65 for completing two full sessions).

### Procedure {#AB_sEBR-procedure}

The study procedures were identical to @London2015: participants received anodal and cathodal tDCS in separate sessions (Figure \@ref(fig:AB-sEBR-fig-procedure)), which typically took place exactly one week apart (for 29 participants; sessions were separated by 6 days for 6 participants; 8 days for 3 participants; 4 days for 1 participant; 10 days for 1 participant). The time in between served to keep the sessions as similar as possible, and to minimize the risk of tDCS carry-over effects. 18 participants received anodal tDCS in the first session and cathodal tDCS in the second, and vice versa for the remaining 22 participants.

First, participants experienced the sensations induced by tDCS in a brief trial stimulation (see the [tDCS](#AB_sEBR-tDCS) section). Next, sEBR was measured for 6 minutes (see the [sEBR](#AB_sEBR-sEBR) section), after which participants completed 20 practice trials of the task (see the [Task](#AB_sEBR-task) section). For the main portion of the experiment, participants performed three blocks of the task (Figure \@ref(fig:AB-sEBR-fig-procedure)): before tDCS (_baseline_), during anodal/cathodal tDCS (_tDCS_), and after tDCS (_post_).

Within each block of the task, participants took a self-timed break every 50 trials (~5 minutes); between the blocks, the experimenter walked in. Participants performed the task for exactly 20 minutes during the _baseline_ and _post_ blocks. During the _tDCS_ block, the task started after the 1-minute ramp-up of the current was complete, and continued for 21 minutes (constant current, plus 1-minute of ramp-down).

<div class="figure">
<img src="AB_sEBR_files/figures/figure_2_procedure.png" alt="(ref:caption-AB-sEBR-fig-procedure)"  />
<p class="caption">(\#fig:AB-sEBR-fig-procedure)(ref:caption-AB-sEBR-fig-procedure)</p>
</div>

(ref:caption-AB-sEBR-fig-procedure) __Experimental design__. Spontaneous eye blink rate was measured for 6 minutes prior to the start of the task. Then (following a short practice block), participants performed three 20-minute blocks of the attentional blink task: a _baseline_ block without stimulation, a _tDCS_ block during 20 minutes of anodal (red) or cathodal (blue) stimulation, and finally a _post_-test block (also without stimulation). The second session (typically 7 days later at the same time of day) was identical, except that the tDCS polarity was reversed.

### Task {#AB_sEBR-task}

The attentional blink task (Figure \@ref(fig:AB-sEBR-fig-task)) was almost identical to the one used in @London2015 and @Slagter2013, which in turn was based on a task designed by @Dux2008. A rapid serial visual presentation stream of 15 letters (cf. 17 letters in @London2015) was shown on each trial, using Presentation software (Neurobehavioral Systems, Inc.). Each letter was displayed for 91.7 ms (11 frames at 120 Hz) on a dark gray background. The letters were presented in font size 40 (font: Courier New) at a viewing distance of 90 cm. On each trial, the letters were randomly sampled without replacement from the alphabet, excluding the letters I, L, O, Q, U and V, as they were too similar to each other. All distractor letters were mid-gray, whereas T1 and T2 were colored. T1 was red and always appeared at position 5 in the stream. T2 was green and followed T1 after either 2 distractors (_lag 3_) or 7 distractors (_lag 8_) (cf. lags 2, 4 and 10 in @London2015).

The letter stream was preceded by a fixation cross (same color as the letters) presented for 1750 ms and followed by another fixation cross (presented for 1000 ms). Finally, the participant was prompted to type in (using a standard keyboard) the letter they thought was presented as T1 ("Which letter was red?"), followed by T2 ("Which letter was green?").

Trial duration varied slightly because both the T1 and T2 response questions were self-paced, so some participants completed more trials than others depending on their response times. On average, participants completed 130 short lag trials (_SD_ = 17; range = 78--163) and 65 long lag trials (_SD_ = 9; range = 39--87) per 20-minute block.

<div class="figure">
<img src="AB_sEBR_files/figures/figure_3_task.png" alt="(ref:caption-AB-sEBR-fig-task)"  />
<p class="caption">(\#fig:AB-sEBR-fig-task)(ref:caption-AB-sEBR-fig-task)</p>
</div>

(ref:caption-AB-sEBR-fig-task) __Attentional blink task__. Participants viewed rapid serial visual presentation streams of 15 letters, all of which were distractors (gray letters) except for T1 and T2. T1 was presented in red at position 5; T2 was presented in green and followed T1 after 2 distractors (_lag 3_, inside the AB window) or 7 distractors (_lag 8_, outside the AB window). At the end of the trial, participants reported the identity of T1 and then T2 (self-paced).

### tDCS {#AB_sEBR-tDCS}

Transcranial direct current stimulation was delivered online (i.e. during performance of the attentional blink task) using a DC-STIMULATOR PLUS (NeuroCare Group GmbH). The current was ramped up to 1 mA in 1 minute, stayed at 1 mA for 20 minutes, and was ramped down again in 1 minute.

One electrode was placed at F3 (international 10-20 system) to target the lDLPFC; the other was placed over the right forehead, centered above the eye (approximately corresponding to position Fp2). Both electrodes were 5 x 7 cm in size (35 cm^2^), leading to a current density of 0.029 mA/cm^2^. The electrode montage and tDCS parameters are identical to @London2015, with two exceptions. First, we also measured EEG (see the [sEBR](#AB_sEBR-sEBR) section), so the EEG electrodes and headcap were applied on top of the tDCS electrodes. Second, we used Ten20 paste (Weaver and Company) as the conductive medium, whereas @London2015 used sponges soaked in saline.

Participants received either anodal tDCS (anode on F3, cathode on right forehead) or cathodal tDCS (cathode on F3, anode on right forehead) in separate sessions. The procedure was double-blinded: both the participant and the experimenters were unaware which polarity was applied in a given session. The experimenter loaded a stimulation setting on the tDCS device (programmed by someone not involved in data collection), without knowing whether it was mapped to anodal or cathodal tDCS. In the second session, the experimenter loaded a second setting mapped to the opposite polarity (half the dataset), or simply connected the terminals of the device to the electrodes in the opposite way.

At the start of the experiment, participants received a brief trial stimulation, based on which they decided whether or not they wanted to continue with the rest of the session. The experimenter offered to terminate the experiment in case tDCS was experienced as too uncomfortable, but none of the participants opted to do so. For the trial stimulation, the current was ramped up to 1 mA in 45 seconds, stayed at 1 mA for 15 seconds, and was ramped down again in 45 seconds.

### sEBR {#AB_sEBR-sEBR}

Movement of the eyelids across the eyes affects the electrical potential that naturally exists across the eyeball [@Matsuo1975]. Blinks can thus be recorded with electrodes placed on the face and/or scalp [@Luck2005].

We used a BioSemi ActiveTwo system with 64 Ag/AgCl active electrodes, placed according to the (10-10 subdivision of the) international 10-20 system. Two pairs of additional external electrodes were placed to record the electro-oculogram (EOG): above and below the left eye, and next to the left and right outer canthi. Finally, another pair of electrodes on the left and right earlobes served as the reference. This full setup was used because we also recorded the EEG during task performance. This dataset is available elsewhere [@Reteig2019_data].

sEBR was recorded for 6 minutes after setting up the EEG in each session. Participants were asked to sit still and look straight ahead at a white wall (about 1 meter away). Participants were told they were allowed to move their eyes, but the experimenter made no mention of eye blinks. The "cover story" was that we needed to monitor the quality of the EEG signal before being able to start the recordings. Because blink rate can increase in the evening [@Barbato2000], but is stable during the day time [@Barbato2000; @Doughty2006], we made sure all recordings were completed before 5 PM. Most participants started their first and second sessions at the exact same time of day (34 participants; 4 participants started their second session 5 hours earlier/later than their first, 2 started 3 hours earlier/later).

The raw data were preprocessed using the EEGLAB toolbox [@Delorme2004] in MATLAB (MathWorks, Inc.). First, data were re-referenced offline to the average of the earlobe electrodes. Next, horizontal and vertical EOG channels were created by subtracting the signals from each member of a horizontal/vertical electrode pair. A high-pass filter with a cut-off of .5 Hz was then applied. Finally, we ran an independent component analysis (ICA) to capture the eye blink events in a single time series. For each recording, we visually inspected the independent components and selected one that appeared to contain the eye blink signals, based on the waveform (large amplitude, positive deflections) and scalp distribution of the ICA weights (loading on frontal and EOG electrodes).

Eye blinks in this component were then detected using a semi-automatic procedure [cf. @Slagter2013; @Kruis2016]. First, a voltage threshold was set (initialized to the standard deviation of the signal) which captured most eye blink peaks. This threshold was moved up or down by the analyst if necessary. The sample with the maximum voltage between two threshold crossings was marked as an eye blink, with the restriction that two eye blinks must be at least 400 ms apart. We picked 400 ms as an upper estimate of the duration of a single blink [@Caffier2003]. The analyst then inspected the output, and removed or added eye blinks in the case of clear false positives (e.g., a muscle contraction) or false negatives (e.g., an eye blink waveform did not exceed the threshold, or was followed by another clear eye blink within 400 ms).

### Statistical analysis {#AB_sEBR-stats}



Data were analyzed using R [Version 3.5.1; @R-base][^papaja_pkg_citations_AB_sEBR] from within RStudio [Version 1.1.463; @RStudio2016]. Our analyses were focused on three dependent variables. _sEBR_ was expressed as the number of eye blinks per minute. For the AB, we examined T2|T1 accuracy, i.e. the percentage of trials where T2 was reported correctly, out of the subset of trials in which T1 was reported correctly. The size of the attentional blink (_AB magnitude_) was quantified by subtracting T2|T1 accuracy at lag 3 from T2|T1 accuracy at lag 8, for each session in each block. Lastly, we created _AB magnitude change scores_ for each session by subtracting AB magnitude in the "baseline" block from the "tDCS" and the "post" blocks, respectively.



[^papaja_pkg_citations_AB_sEBR]: We, furthermore, used the R-packages *broom* [Version 0.5.1; @R-broom], *cowplot* [Version 0.9.99; @R-cowplot], *here* [Version 0.1; @R-here], *knitr* [Version 1.21; @R-knitr], *lubridate* [Version 1.7.4; @R-lubridate], *papaja* [Version 0.1.0.9842; @R-papaja], and *tidyverse* [Version 1.2.1; @R-tidyverse].



#### Reliability {#AB_sEBR-methods-rel}

We evaluated the test-retest reliability of sEBR and AB magnitude across sessions by computing intraclass correlations (ICCs) using the *psych* package [Version NA; @R-psych]. We primarily report the single-rating, two-way ICC for absolute agreement, also known as ICC(2,1) in the conventions from @Shrout1979. This is the most appropriate ICC for test-retest reliability [@Koo2016]. In addition, we report Pearson's correlation, to be able to compare the reliability of sEBR with @Dang2017, and ICC(3,2), also known as Cronbach's alpha [@McGraw1996], to compare our results with @Kruis2016. We used the interpretation scheme in @Koo2016, which classifies reliability as "poor" for ICCs < .5, .5 < ICC < .75 as "moderate", .75 < ICC < .9 as "good", and ICCs > .9 as "excellent". For AB magnitude, we also report Pearson's correlation, as this measure was used by all previous studies on the reliability of the AB [e.g. @Dale2013]. Here we also used data from the _baseline_ block only, to rule out any influence of tDCS on the reliability scores.

#### Relation between sEBR and baseline AB magnitude {#AB_sEBR-methods-base}

##### Linear relationships

We calculated Pearson correlations to test for linear relationships between _sEBR_ and _AB magnitude_. We also computed a Bayes factor for these correlations, as proposed by @Ly2016 and implemented in the *BayesFactor* package [Version NA; @R-BayesFactor], with the standard prior distribution ($\kappa$ = .33). This Bayes factor ($BF_{01}$) expresses the relative evidence for the null hypothesis of zero correlation, vs. the alternative hypothesis that there is a non-zero correlation. We use the interpretation scheme from @Wagenmakers2018, where $1 < BF_{01} < 3$ constitutes "anecdotal" evidence for the null, $3 < BF_{01} < 10$ ~ "moderate" evidence, and $10 < BF_{01} < 30$ ~ "strong" evidence.

Because @Colzato2008 previously reported a negative relationship between _sEBR_ and _AB magnitude_, we computed two additional Bayes Factors that incorporate this prior information. First, we used the same prior but folded all of its mass to negative effect sizes only, effectively providing a Bayes factor for a one-sided test [@Wagenmakers2016]. This Bayes factor ($BF_{0-}$) expresses the relative evidence for the null hypothesis of zero correlation, vs. the alternative hypothesis that there is a negative correlation. Second, we computed a replication Bayes Factor, by using the posterior from @Colzato2008 as a prior [@Verhagen2014; @Wagenmakers2016]. This Bayes factor ($BF_{0r}$) expresses the relative evidence for the null hypothesis of zero correlation, vs. the alternative hypothesis that the correlation is as in @Colzato2008. 

##### Inverted-U-shaped relationships

To evaluate the presence of an (Inverted-) U-shaped relationship between _sEBR_ and _AB magnitude_, we used the "two-lines test" as proposed by @Simonsohn2018. This test revolves around the core assumption in any U-shaped relationship: that a sign flip occurs at a break point in the data. Values on one side of this break point should exhibit a positive relationship (rising flank of the U); values on the other side should exhibit a negative relationship (falling flank of the U). The "two-lines test" first estimates the value of the break point based on a cubic spline fit to all of the data, and then computes two linear regressions to estimate the slopes on either side of the break point. Both slopes have to be significant and of opposite sign to reject the null hypothesis that there is no U-shaped relationship. 

#### Relation between sEBR and the effect of tDCS on AB magnitude

We also calculated Pearson and Bayesian correlations between sEBR and _AB magnitude change scores_, cf. the relation between sEBR and AB magnitude at baseline. In general, such a correlation $r_{A(Y-X)}$ between a change score $Y-X$ (here, AB magnitude in the _tDCS_ or _post_ block minus the _baseline_ score) and another variable $A$ (here, sEBR), is a function of four components: 1) $r_{AX}$: the correlation between $A$ and the pre-test $X$, 2) $r_{AY}$: the correlation between $A$ and the post-test $Y$, 3) $r_{XY}$: the correlation between pre- and post-test (i.e., the reliability), and 4) $SD_y / SD_x$: the ratio between the standard deviations of the pre- and post-test [@Gardner1987; @Griffin1999]. Next to the correlation with the difference score, we also computed these constituent components (reported in Tables \@ref(tab:ABmag) and \@ref(tab:corrco)). A complementary way to test for $r_{A(Y-X)}$ is to test whether $r_X$ and $r_Y$ are significantly different. We used the Pearson-Filon test [-@Pearson1898] for this purpose, as implemented in the *cocor* package [Version NA; @R-cocor].

### Data, materials, and code availability

All of the data, materials, and code for this study are available on the [Open Science Framework](https://doi.org/10.17605/OSF.IO/PZBGY). The raw task data and sEBR recordings can also be downloaded from this page. The code to preprocess the sEBR data and perform the semi-automatic eye blink detection [cf. @Slagter2013; @Kruis2016] is supplied in MATLAB scripts. We provide the statistical analysis code in the form of an R notebook, detailing all the analyses that we ran for this project, along with the results. We also include an Rmarkdown [@Xie2018] source file for this paper that can be run to reproduce the pdf version of the text, along with all the figures and statistics.

## Results {#AB_sEBR-results}

### Reliability {#AB_sEBR-results-rel}

We first examined task performance in the baseline block of both sessions, i.e. before tDCS onset. All participants showed the characteristic AB effect in both sessions: T2|T1 accuracy was higher for lag 8 trials than for lag 3 (Figure \@ref(fig:fig-retest)A). 

There was also a significant difference in AB magnitude (lag 8 minus lag 3 T2|T1 accuracy) between the sessions: (_F_(1, 39) = 16.53, _p_ < .001). For most participants, AB magnitude was smaller in the second session than the first (Figure \@ref(fig:fig-retest)B). The average difference in AB magnitude over sessions seemed to be driven by lag 3 performance only (Figure \@ref(fig:fig-retest)A), meaning the AB genuinely decreased with practice.

To be able to uncover relationships between sEBR and AB magnitude (see the [subsequent sections](#AB_sEBR-ABmag)), it is crucial that the test-retest reliability of both measures is adequate, i.e. that there is substantial agreement between the scores in session 1 and 2. 

The intraclass correlation for AB magnitude (Figure \@ref(fig:fig-retest)B) is .60, indicating "moderate" test-retest reliability [@Koo2016], with a 95% confidence interval of .25 (poor) -- .79 (good). The standard (interclass) Pearson correlation for AB magnitude between sessions is comparable (_r_(38) = .68, CI~95%~ [.47, .82]) and comparable to previous reports [@Dale2013].

In contrast to AB magnitude, sEBR (Figure \@ref(fig:fig-retest)C), did not differ significantly between sessions (_F_(1, 39) = 0.149, _p_ = 0.701). We had some concerns that participants would blink less in the second session, because they had been instructed (after the sEBR measurement in session 1) that blinking can cause artifacts in the EEG signal (recorded during task performance). Yet, if anything, median sEBR was slightly higher in the second session (12.6) than the first (11.7). However, we also asked participants whether they had been in an EEG experiment

\newpage
\pagestyle{empty}
\changetext{}{}{-25mm}{}{}
\blandscape
\captionsetup{width=\linewidth}

<div class="figure">
<img src="AB_sEBR_files/figures/figure_4_retest.png" alt="(ref:caption-fig-retest)"  />
<p class="caption">(\#fig:fig-retest)(ref:caption-fig-retest)</p>
</div>

(ref:caption-fig-retest)  __Reliability of the attentional blink and spontaneous eye blink rate__. (__A__) All participants showed an attentional blink in both sessions: higher T2|T1 accuracy (% T2 correct in trials where T1 was also correct) for lag 8 (orange) than lag 3 (yellow). Horizontal lines show group-average T2|T1 accuracy. The attentional blink magnitude (lag 8 - lag 3) is slightly smaller in the second session (dotted lines) than the first session (solid lines), due to better lag 3 performance on average.  (__B__) AB magnitude for each participant in session 1 vs. 2. The intraclass correlation indicates moderate test-retest reliability, though the 95% confidence interval ranges all the way from poor to good. AB magnitude in (__A__) and (__B__) was calculated on the _baseline_ block only, before tDCS onset. (__C__) sEBR values for each participant in session 1 vs. 2. The intraclass correlation indicates that the test-retest reliability for sEBR is good.

\newpage
\elandscape
\changetext{}{}{+25mm}{}{}
\pagestyle{\defstyle}
\captionsetup{width=\textwidth}

\noindent before. Participants that had done so exhibited a greatly reduced median sEBR in both sessions (6.3 in session 1; 4.1 in session 2). Because these were only 6 cases in an already small sample, we are unsure whether this finding is robust, but it is a cautionary note to others aiming to measure sEBR using (a full setup of) EEG electrodes. Because smoking has been reported to increase sEBR [@Klein1993], we also asked whether participants self-identified as a smoker (n = 5). These individuals were not clear outliers in the distribution, neither were those wearing contact lenses (n = 4), which also generally should increase blink rate.

Most importantly, the test-retest reliability for sEBR was "good" [@Koo2016], indicated by an intraclass correlation of .85 CI~95%~ [.73, .92]. The Pearson correlation was _r_(38) = .84, CI~95%~ [.72, .91] [cf. @Dang2017]; Cronbach's alpha was .91, CI~95%~ [.84, .95] [cf. @Kruis2016]. 

One participant's sEBR in session 2 seems remarkably high (57 blinks per minute), and is quite a bit higher in session 2 than in session 1 (difference of 12). However, we confirmed this was not a data quality issue, and rerunning the analyses without this participant did not qualitatively change the results in the subsequent sections. Hence, this participant was included in all analyses.

### Relation between sEBR and baseline AB magnitude {#AB_sEBR-ABmag}

<div class="figure">
<img src="AB_sEBR_files/figures/figure_5_AB-corr.png" alt="(ref:caption-fig-AB-corr)"  />
<p class="caption">(\#fig:fig-AB-corr)(ref:caption-fig-AB-corr)</p>
</div>

(ref:caption-fig-AB-corr) __No significant relationships between sEBR and AB magnitude in the block before tDCS onset__. Grey solid lines show a linear fit over all data points (individual participants), with no clear relationship in both sessions. Grey dashed lines show a cubic spline fit over all data points. Colored lines show two separate linear fits, delimited by the break point in the cubic spline, as estimated with the "two-lines test" [@Simonsohn2018]. Both the spline fit and the two linear slopes suggest an Inverted-U shaped relationship in session 1, but neither slope is significant, and this pattern is not present in session 2. 

Based on the results of @Colzato2008, we should expect to find a negative correlation between sEBR and AB magnitude (in the baseline block). However, the correlation here was not significant in either session 1 (_r_(38) = .08, CI~95%~ [-.24, .38], _p_ = .637), or session 2 (_r_(38) = .003, CI~95%~ [-.31, .31], _p_ = .987). The direction of the effect is close to zero or slightly positive (Figure \@ref(fig:fig-AB-corr)), which is not in accord with @Colzato2008.

Bayesian correlations show that the data are BF~01~ = 2.57 times (session 1) and BF~01~ = 2.84 times (session 2) more likely under the null hypothesis, using the default prior. This constitutes some evidence for absence of a correlation, though not more than anecdotal. If we evaluate the prior over negative effect sizes only [based on the negative correlation in @Colzato2008], the support for the null increases slightly and becomes moderate (session 1: BF~0-~ = 3.90, session 2: BF~0-~ = 2.87). Finally, if we use the correlation as in @Colzato2008 (_r_(18) = -.53) as a prior [@Wagenmakers2016], the support for the null hypothesis becomes strong (session 1: BF~0r~ = 15.80, session 2: BF~0r~ = 10.43).

We also probed for an Inverted-U-shaped relationship between sEBR and AB magnitude, using the "two lines test" [@Simonsohn2018]. In session 1, a cubic spline-fit indeed suggests an Inverted-U-shaped relationship (Figure \@ref(fig:fig-AB-corr)). The linear regressions do as well, since the first slope is positive (_b_ = .012, _p_ = .058) and the second is negative (_b_ = -.006, _p_ = .602). However, neither slope is significant. Furthermore, this pattern is absent in session 2 (line 1: _b_ = .001, _p_ = .931; line 2: _b_ = .003, _p_ = .545), with the spline fit also showing a more erratic pattern.

### Relation between sEBR and the effect of tDCS on AB magnitude

<div class="figure">
<img src="AB_sEBR_files/figures/figure_6_tDCS-corr.png" alt="(ref:caption-fig-tDCS-corr)"  />
<p class="caption">(\#fig:fig-tDCS-corr)(ref:caption-fig-tDCS-corr)</p>
</div>

(ref:caption-fig-tDCS-corr) __No significant relationships between sEBR and AB magnitude change scores.__ Each plot shows spontaneous eye blink rates on the x-axis, and the change in AB magnitude on the y-axis (difference scores of the _tDCS_ block - the _baseline_ block, or the _post_ block - _baseline_) in the _anodal_ and _cathodal_ stimulation conditions.

Although there was no relationship between sEBR and AB magnitude itself, sEBR could potentially still be associated with tDCS-induced changes in AB magnitude. We therefore computed AB magnitude change scores (_tDCS - baseline_, _post - baseline_) in each stimulation condition (_anodal_, _cathodal_), and correlated these to sEBR. However, this analysis did not uncover any significant relationships (Figure \@ref(fig:fig-tDCS-corr) and columns 2--4 in Table \@ref(tab:corrco)). These change score correlations are ultimately based on a number of different variables: the within-session reliability of AB magnitude (Table \@ref(tab:ABmag)), the within-block variability in AB magnitude (Table \@ref(tab:corrco)), and, most importantly, the separate correlations between sEBR and AB magnitude in each block (Table \@ref(tab:ABmag)). None of the correlations in the baseline block differed significantly from the correlations in the subsequent blocks (columns 5--6 in Table \@ref(tab:corrco)), again suggesting there was no relationship between sEBR and AB magnitude change scores.

<table class="table" style="margin-left: auto; margin-right: auto;">
<caption>(\#tab:ABmag)Variability of attentional blink magnitude scores and correlation with sEBR, per stimulation condition and block.</caption>
 <thead>
  <tr>
   <th style="text-align:left;"> Block </th>
   <th style="text-align:right;"> $r$ sEBR<sup>a</sup> </th>
   <th style="text-align:right;"> SD<sup>b</sup> </th>
  </tr>
 </thead>
<tbody>
  <tr grouplength="3"><td colspan="3" style="border-bottom: 1px solid;"><strong>anodal session</strong></td></tr>
<tr>
   <td style="text-align:left; padding-left: 2em;width: 10em; " indentlevel="1"> baseline </td>
   <td style="text-align:right;"> .04 </td>
   <td style="text-align:right;"> 0.140 </td>
  </tr>
  <tr>
   <td style="text-align:left; padding-left: 2em;width: 10em; " indentlevel="1"> tDCS </td>
   <td style="text-align:right;"> .15 </td>
   <td style="text-align:right;"> 0.148 </td>
  </tr>
  <tr>
   <td style="text-align:left; padding-left: 2em;width: 10em; " indentlevel="1"> post </td>
   <td style="text-align:right;"> .25 </td>
   <td style="text-align:right;"> 0.137 </td>
  </tr>
  <tr grouplength="3"><td colspan="3" style="border-bottom: 1px solid;"><strong>cathodal session</strong></td></tr>
<tr>
   <td style="text-align:left; padding-left: 2em;width: 10em; " indentlevel="1"> baseline </td>
   <td style="text-align:right;"> .05 </td>
   <td style="text-align:right;"> 0.136 </td>
  </tr>
  <tr>
   <td style="text-align:left; padding-left: 2em;width: 10em; " indentlevel="1"> tDCS </td>
   <td style="text-align:right;"> -.05 </td>
   <td style="text-align:right;"> 0.128 </td>
  </tr>
  <tr>
   <td style="text-align:left; padding-left: 2em;width: 10em; " indentlevel="1"> post </td>
   <td style="text-align:right;"> .09 </td>
   <td style="text-align:right;"> 0.120 </td>
  </tr>
</tbody>
<tfoot>
<tr><td style="padding: 0; border: 0;" colspan="100%">
<sup>a</sup> Pearson's correlation between AB magnitude and spontaneous eye blink rate</td></tr>
<tr><td style="padding: 0; border: 0;" colspan="100%">
<sup>b</sup> Standard deviation of AB magnitude</td></tr>
</tfoot>
</table>

\begingroup

<table class="table" style="margin-left: auto; margin-right: auto;">
<caption>(\#tab:corrco)Attentional blink magnitude and spontaneous eye blink rate correlations.</caption>
 <thead>
<tr>
<th style="border-bottom:hidden" colspan="1"></th>
<th style="border-bottom:hidden; padding-bottom:0; padding-left:3px;padding-right:3px;text-align: center; " colspan="3"><div style="border-bottom: 1px solid #ddd; padding-bottom: 5px; ">Correlation<sup>a</sup>
</div></th>
<th style="border-bottom:hidden; padding-bottom:0; padding-left:3px;padding-right:3px;text-align: center; " colspan="2"><div style="border-bottom: 1px solid #ddd; padding-bottom: 5px; ">Pearson-Filon<br>test<sup>b</sup>
</div></th>
<th style="border-bottom:hidden; padding-bottom:0; padding-left:3px;padding-right:3px;text-align: center; " colspan="1"><div style="border-bottom: 1px solid #ddd; padding-bottom: 5px; ">Reliability<sup>c</sup>
</div></th>
</tr>
  <tr>
   <th style="text-align:left;"> contrast </th>
   <th style="text-align:right;"> $r$ </th>
   <th style="text-align:right;"> $p$ </th>
   <th style="text-align:right;"> $BF_{01}$ </th>
   <th style="text-align:right;"> $Z$ </th>
   <th style="text-align:right;"> $p$ </th>
   <th style="text-align:right;"> $r$ </th>
  </tr>
 </thead>
<tbody>
  <tr grouplength="2"><td colspan="7" style="border-bottom: 1px solid;"><strong>anodal session</strong></td></tr>
<tr>
   <td style="text-align:left; padding-left: 2em;" indentlevel="1"> tDCS - baseline </td>
   <td style="text-align:right;"> .21 </td>
   <td style="text-align:right;"> .199 </td>
   <td style="text-align:right;"> 1.37 </td>
   <td style="text-align:right;"> -1.27 </td>
   <td style="text-align:right;"> .204 </td>
   <td style="text-align:right;"> .84 </td>
  </tr>
  <tr>
   <td style="text-align:left; padding-left: 2em;" indentlevel="1"> post - baseline </td>
   <td style="text-align:right;"> .24 </td>
   <td style="text-align:right;"> .133 </td>
   <td style="text-align:right;"> 1.05 </td>
   <td style="text-align:right;"> -1.59 </td>
   <td style="text-align:right;"> .111 </td>
   <td style="text-align:right;"> .63 </td>
  </tr>
  <tr grouplength="2"><td colspan="7" style="border-bottom: 1px solid;"><strong>cathodal session</strong></td></tr>
<tr>
   <td style="text-align:left; padding-left: 2em;" indentlevel="1"> tDCS - baseline </td>
   <td style="text-align:right;"> -.16 </td>
   <td style="text-align:right;"> .313 </td>
   <td style="text-align:right;"> 1.81 </td>
   <td style="text-align:right;"> 1.05 </td>
   <td style="text-align:right;"> .296 </td>
   <td style="text-align:right;"> .82 </td>
  </tr>
  <tr>
   <td style="text-align:left; padding-left: 2em;" indentlevel="1"> post - baseline </td>
   <td style="text-align:right;"> .04 </td>
   <td style="text-align:right;"> .808 </td>
   <td style="text-align:right;"> 2.77 </td>
   <td style="text-align:right;"> -0.33 </td>
   <td style="text-align:right;"> .745 </td>
   <td style="text-align:right;"> .71 </td>
  </tr>
</tbody>
<tfoot>
<tr><td style="padding: 0; border: 0;" colspan="100%">
<sup>a</sup> Linear correlation (Pearson and Bayesian) between sEBR and AB magnitude change scores</td></tr>
<tr><td style="padding: 0; border: 0;" colspan="100%">
<sup>b</sup> Test for significant differences between the sEBR vs. AB magnitude correlations (reported in Table \@ref(tab:ABmag)) in the baseline vs. tDCS or post blocks</td></tr>
<tr><td style="padding: 0; border: 0;" colspan="100%">
<sup>c</sup> Pearson correlation between AB magnitude scores in the baseline vs. tDCS or post blocks</td></tr>
</tfoot>
</table>

\endgroup

## Discussion {#AB_sEBR-discussion}

Dopamine levels play a central role in regulating cognitive functions. tDCS may be used to enhance cognitive functions, but its precise effects appear to be dependent on dopamine as well. Here we attempted to use sEBR---a proxy for dopaminergic activity---to study how dopamine may determine the size of the AB and its modulation by tDCS. As a prerequisite, we assessed the test-retest reliabilities of sEBR and AB magnitude, which proved to be good to moderate, respectively, in line with previous reports [@Kruis2016; @Dang2017; @Dale2013]. We then attempted to replicate a result from @Colzato2008, who reported that individuals with high sEBR tend to exhibit a smaller AB. However, we found no significant linear or Inverted-U-shaped relationship between sEBR and AB magnitude, with more evidence for the null hypothesis of no association. Finally, we also did not find any evidence that sEBR is associated with the effects of tDCS on AB magnitude.

### sEBR and AB magnitude have good to moderate test-retest reliability

The test-retest reliability of sEBR across two testing sessions (separated by about one week) was "good", bordering on "excellent" [@Koo2016]. Only two other studies examined the reliability of sEBR to date. @Dang2017 (n = 18) found a Pearson correlation of .86 between sEBR under administration of bromocriptine (a dopamine agonist) or placebo (separated by 4 hours). Here, Pearson's correlation was comparable (.84). In @Kruis2016, Cronbach's alpha for sEBR ranged from .85 (three measurements of 27 long-term meditators) to .79 (2--3 measurements of 114 meditation-naive participants). In our data, Cronbach's alpha was even slightly higher (.91). Together, all three studies suggest that sEBR scores are trait-like and stable over time, even for short measurements of only several minutes (6 minutes here and in @Kruis2016; 5 minutes in @Dang2017). Although the reliability estimates are comparable, we measured sEBR twice under baseline conditions, whereas @Dang2017 administered a dopamine agonist in one measurement (vs. placebo), and @Kruis2016 measured sEBR following meditation practice (vs. a regular day). We did find that participants with prior EEG experience exhibited a two- to threefold lower sEBR. Future studies that measure sEBR with EEG electrodes might want to take this into account. However, this observation was based on only 6 participants, and sEBR did not significantly differ between sessions, despite the fact that all participants had EEG experience after the first session.

In contrast to sEBR, AB magnitude was significantly smaller in the second session. Previous studies have reported that performance on an AB task can improve across sessions [@Dale2013; @Slagter2007], but for targets at all lags, whereas here we observed a specific increase in lag 3 T2|T1 performance (inside the attentional blink window). Test-retest reliability of AB magnitude was lower than sEBR: the point-estimate indicated only "moderate" reliability, though the 95% confidence interval was also consistent with "poor" to "good" reliability. However, this is comparable to previous reports (see Table \@ref(tab:AB-reliability)). The Pearson correlation in the present study (_r_ = .68) is even on the higher end of the range reported in previous studies (though note that regular correlations can overestimate "true" test-retest reliability [@Bland1986]). 

\begingroup
\small
\LTcapwidth=\textwidth

| Study       | n   | Correlation             | Notes                                                                                 |
|---------------------------------|-----|-------------------------|---------------------------------------------------------------------------------------|
| @Kelly2011  | 37  | .33, .34, .48, .52,     | test and retest on same day; different values correspond to different tasks           |
| @Dale2013a  | 46  | .62, .39                | test and retest one week apart; 1st value is a task with a set-switch, 2nd is without |
| @Dale2013   | 118 | .41, .41, .45, .48, .49 | test and retest one week apart; different values correspond to different tasks        |
| @London2015 | 34  | .58                     | test and retest one week apart; almost same task as present study                     |

Table: (\#tab:AB-reliability) Previous reports on the reliability of AB magnitude. Note that these all used interclass (Pearson) correlations.

\endgroup

The moderate reliability for AB magnitude limits the correlation that can be obtained between AB magnitude and sEBR. The AB phenomenon might suffer from the "individual differences paradox" [@Hedge2018]: precisely because it is robust at the group level (almost everyone has an AB), it might not exhibit sufficient between-subject variability to be reliable. On the other hand, the AB seems to have a larger range of individual differences than other tasks [@Willems2016], and even a moderate reliability should provide "enough room" to detect correlations between sEBR and AB magnitude in a plausible range.

### No significant relationships between sEBR and baseline AB magnitude

@Colzato2008 (n = 20) found a negative correlation between sEBR and AB magnitude. Here, this correlation was not significant in either session, with an effect size around 0 (session 2) or even slightly positive (session 1). The main difference between both studies seems to be the distribution of AB magnitude scores. The AB was shallow in @Colzato2008, as average AB magnitude was less than 10%, with 5 out of 20 participants showing either a "negative" AB (higher T2|T1 accuracy at the shortest lag) or an AB magnitude around 0. Here, the blink was much more pronounced (40% on average)---even the best performing participant had an AB magnitude (11%) that exceeded the average in @Colzato2008.

Our AB task also involves an attentional set switch, while the task used by @Colzato2008 did not. In our task, T1 and T2 had different features (T1 was red; T2 was green), so participants had to update their attentional template and detect the second target on the basis of a different feature (color) than T1. In @Colzato2008, T1 and T2 were both digits, and thus belonged to the same set. @Kelly2011 suggest that such a set switch introduces an additional bottle neck that is dissociable from the AB [@Potter1998]. However, follow-up studies have shown that there is still a sizable correlation between non-switch and switch-versions of AB tasks [@Dale2013; @Dale2013a]. Although a set switch may introduce additional variance, it seems unlikely this would be sufficient to completely abolish a correlation between sEBR and AB magnitude. However, it could have reduced the size of the effect to a degree where it could no longer be reliably detected. The correlation between sEBR and AB magnitude in @Colzato2008 (_r_ = -.53) appears to exceed the average reliability of AB magnitude itself (Table \@ref(tab:AB-reliability)), suggesting it might be an overestimate of the true correlation. Further evidence that the effect might be small comes from @Unsworth2019, who conducted a large-scale study (n = 204) and only found a correlation of .17 between sEBR and attentional control (psychomotor vigilance task, antisaccade task), and no correlation with working memory (operation, symmetry, and reading span)---a core component in the AB [@Dux2009; @Martens2010]. Although our sample size is twice that of @Colzato2008, an effect of this magnitude would not have been detectable. It should also be noted that we used almost the same task as @Slagter2013 (n = 39), who also did not find a significant correlation between sEBR and AB magnitude. So both our studies do not support a relationship between sEBR and the AB.

No study to date has investigated an Inverted-U-shaped relationship between sEBR and AB magnitude, even though the underlying theory strongly suggests it [@Cools2011; @Slagter2012]. Here the data do conform to a weak Inverted-U-shaped relationship, but only in session 1, and neither the upward nor the downward slope were significantly different from 0. Because both would have to be significant [@Simonsohn2018], and each slope is estimated on a different subset of the sample, we likely did not have sufficient power to detect an Inverted-U-shaped relationship. To be able to detect an Inverted-U-shaped relationship, the participants in our sample should also cover the whole range of AB task performance and dopamine levels. If this assumption is not met, then a true Inverted-U-shaped relationship could also masquerade as a linear effect (if all participants are sub-optimal), or no effect (if all participants are in the optimal range).

Two recent studies have cast doubt on the validity of sEBR as proxy for striatal dopamine. Both used PET to measure dopamine non-invasively in humans, but found no relation between sEBR and striatal dopamine receptor availability [@Dang2017] or dopamine synthesis capacity [@Sescousse2018]. So, even though we find no relation between sEBR and the AB, there could still be a true relationship between dopamine and the AB---sEBR might simply not have high validity to measure it accurately.

### No significant relationship between sEBR and the effect of tDCS on AB magnitude

We suggested two factors that might underlie individual differences in the effects of tDCS on the AB (See Figure \@ref(fig:AB-sEBR-fig-model)). First, baseline cortical excitability might partially determine whether tDCS leads to behavioral improvements or impairments [@Krause2013] (Figure \@ref(fig:AB-sEBR-fig-model), left panel). This seems to fit the results of @London2015, who found that individuals that benefited from anodal tDCS tended to worsen with cathodal tDCS (and vice versa). However, we did not replicate this negative correlation between the effects of anodal and cathodal tDCS (see Chapter \@ref(AB-tDCS-EEG)), so this finding may not be robust.

Second, baseline dopamine levels may also partially determine the behavioral effects of tDCS [@Wiegand2016] (Figure \@ref(fig:AB-sEBR-fig-model), right panel). Assuming that sEBR is a valid index of dopamine levels, we found no evidence for this result, though our Bayes Factor analyses also did not indicate strong evidence of absence. The model proposed by @Wiegand2016 is based on just two studies [@Plewnia2013; @Nieratschker2015] that show different effects of tDCS in different COMT-subtypes, who should vary in baseline dopamine levels. However, a more recent study found that offline effects of prefrontal tDCS on working memory did not interact with COMT genotype [@Jongkees2018]. Because tDCS may also induce activation of [@Meyer2019] and dopamine release in the striatum [@Tanaka2013; @Fonteneau2018], the model is complicated even further. On a more basic level, it is also still disputed whether the COMT polymorphism can affect cognitive functioning [@Barnett2008], as most studies are likely severely underpowered [@Border2019]. The only study that looked at the relation between COMT and the AB also found no association [@Colzato2011], although this was a very small study for genotyping standards. Thus, the overall evidence that the effect of tDCS on the AB depends on baseline dopamine levels is preliminary.

Finally, it is unclear how both axes of the model (Figure \@ref(fig:AB-sEBR-fig-model)) relate to each other. Pairing tDCS with dopaminergic drugs produces complex and non-linear effects on cortical excitability [@Monte-Silva2009; @Fresnoza2014]. Two studies that have combined tDCS and administration of tyrosine (a dopamine precursor) in cognitive tasks have indeed led to divergent results. Cathodal tDCS of the lDLPFC appears to counteract the beneficial effects of tyrosine, as their combination had no net behavioral effect [@Jongkees2017; @Dennison2018]. In contrast, combining anodal tDCS with tyrosine led to impaired performance on an n-back task, where anodal tDCS alone would be expected to enhance performance [@Jongkees2017]. Future studies that manipulate both dopamine levels and cortical excitability are necessary to uncover the physiology that could lead to such interactions.

### Conclusions

We found that spontaneous eye blink rate is a reliable measure, but that it does not relate to the attentional blink, or to changes in attentional blink size following tDCS. Because dopamine is central to healthy cognitive and brain function, it remains plausible that dopamine interacts with manipulations of brain function, such as tDCS, as well as cognitive tasks such as the AB. But there is no good prior for how large the influence of dopamine is. Considering the large individual variability in AB size [@Willems2016], and the many factors that play a role in tDCS outcome [@Li2015b; @Krause2014], dopamine might account for only a small portion of the total variability. In addition, sEBR only provides an indirect measure of dopamine function, and this has recently also been questioned [@Dang2017; @Sescousse2018]. More large-scale studies that include more direct measurement (e.g., using ligand-PET) or manipulation (e.g., using pharmacology) of dopamine function will be needed to pinpoint the unique contribution of dopamine.