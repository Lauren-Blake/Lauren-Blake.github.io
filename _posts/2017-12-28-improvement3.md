---
layout: post
title: "Improvement #3: Structuring each paragraph in the results section"
date: 2017-12-28
---

## Introduction

In the first draft of my first journal article, I took the name of the "Results" section too literally. I mistakenly wrote out the results without any context as to why the analysis was performed or what the results suggested. For example, one of the sections that I wrote was, "Changes in variance around the primitive streak appears to be conserved. 48% of genes whose expression undergoes a significant reduction of variation from the iPSC to primitive streak in humans also do so in chimpanzees and 88% when the species are interchanged (Figures 4B and 4F). There is also a significant overlap of genes whose expression undergoes a significant increase in variation throughout the transition from primitive streak to the endoderm progenitor stage (Figure 4D and 4H, 0 for chimpanzees conditioned on significant results in the human samples = 0.32, humans conditioned on significant results in the chimpanzee samples = 0.11). This result is robust with respect to number of significant genes used in the conditioning step (Supplementary Figure X)." This result in and of itself isn't incorrect; it was problematic because there was no narrative surrounding around it. 

## What exactly do I mean by narrative?

For each subsection (usually a paragraph or two) in the Results section, we want to concentrate on 4 things:

1) What question was driving the experiment/analysis? What did we want to know?

2) What did we do to answer this question?

3) What did we discover in our experiment/analysis?

4) How do we interpret these results? What does this discovery suggest or indicate?

## Applying the narrative 

Let's see how we edited this section, "The proportion of genes with reduced within-species variation in expression levels in primitive streak samples is quite different between humans and chimpanzees (Figures 7A-B, Day 0 to 1). Yet, we had not observed this pattern in any other differentiation state in our data (Figures 7A-B, Days 1 to 2, 2 to 3, and 1 to 3). We thus asked about the overlap of genes with reduced variation in primitive streak samples across the two species. Specifically, we asked whether human genes with lower within-species variation in expression levels in primitive streak are more likely to show the same pattern in chimpanzee genes. For this analysis, we again used the Storey approach [28] to estimate the proportion of true positive tests in one species, conditional on the observation of reduced variation in the other species (using a relaxed cutoff of unadjusted P value of 5%; see Methods). We estimated that 47% of genes whose variation in expression level is reduced in human primitive streak samples showed a similar pattern in chimpanzees (under a permuted null we expect 27%, P < 10-4, see Methods; Figure 7C, Figure S13A in Additional File 15, Table S14 in Additional File 1). When we condition on observing a reduction of variation in chimpanzees, the overlap with humans was 84% (this high value was not unexpected because of the initial large proportion of human genes with a clear signature of reduced variation in primitive streak; under a permuted null we expect 83%, P = 0.38; Figure 7D, Figure S13B in Additional File 15, Table S14 in Additional File 1). These observations support, yet probably underestimate, the degree of high conservation of regulatory patterns in humans and chimpanzees, because any technical differences that are confounded with species would contribute to increased inter-species differences."

Let's break this down into our 4 questions from the previous section:

1) What we wanted to know: We thus asked about the overlap of genes with reduced variation in primitive streak samples across the two species. Specifically, we asked whether human genes with lower within-species variation in expression levels in primitive streak are more likely to show the same pattern in chimpanzee genes.

2) What analysis we did to answer this question: For this analysis, we again used the Storey approach [28] to estimate the proportion of true positive tests in one species, conditional on the observation of reduced variation in the other species (using a relaxed cutoff of unadjusted P value of 5%; see Methods).

3) The results of our analysis: We estimated that 47% of genes whose variation in expression level is reduced in human primitive streak samples showed a similar pattern in chimpanzees (under a permuted null we expect 27%, P < 10-4, see Methods; Figure 7C, Figure S13A in Additional File 15, Table S14 in Additional File 1). When we condition on observing a reduction of variation in chimpanzees, the overlap with humans was 84% (this high value was not unexpected because of the initial large proportion of human genes with a clear signature of reduced variation in primitive streak; under a permuted null we expect 83%, P = 0.38; Figure 7D, Figure S13B in Additional File 15, Table S14 in Additional File 1).

4) What our results suggest: These observations support, yet probably underestimate, the degree of high conservation of regulatory patterns in humans and chimpanzees, because any technical differences that are confounded with species would contribute to increased inter-species differences. 

## My improvement for paper #2

After [writing the "Results" headers](http://lauren-blake.github.io/2017/12/23/improvement2.html), I then went and filled in each section with the bullet points for each result. I used about 5-10 bullet points for each subsection and usually about 3 subsection per results header. 

After I finished this task, I took a mental break for a few days (Happy winter holidays!) and then I came back to the outline with fresh eyes. Instead of immediately jumping into writing the paper, I then looked to see if the bullets in each subsection answered questions #1-4 above. Most of them answered some combination of them (most commonly #2 and #3, but not all of them!) Therefore, I added text to answer questions #1-4, which helped me to build the narrative. Hopefully you can see from this what I mean:   

For example, my original bullet point read, "Conserved inter-tissue gene expression differences (since we are most confident in these) and compared to rank in GTEx data, consistency between the data. GO for tissue specific". While this  discussed what we did and the results (somewhat, since I still have to finish the analysis), it didn't address questions #1 and #4 above. As a result, I added in the following, 

"Attempted to benchmark our use of adaptive shrinkage method. We chose to test the conserved inter-tissue gene expression differences (since we are most confident in these), resulting in one set of genes for each tissue. We first compared each set to its relative rank in GTEx data, and found consistency between the data. When we performed Gene Ontology (GO), we found for tissue-specific functions were highly enriched in the proper tissue, e.g. ) These results suggest that the use of adaptive shrinkage/FSR increases our power to detect genes with a conserved, significant tissue-specific direction in expression, while still maintaining a high sensitivity." Phrase 1 discuss the overall goal of the analysis (question #1), phrase 2 and the beginnings of phrases 3 and 4 discuss what we did (question #2), the ends of phrases 3 and 4 discuss our findings (question #3) and the last sentence sentence discusses what the results suggest (question #4). 

I found that writing the outline in stages helped me to first get my ideas on the page (and make sure I wasn't missing any major results!), *and then* focus on the narrative of the paper. Perhaps breakingit down will also work for you!

## Worksheet coming soon!
     


