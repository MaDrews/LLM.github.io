---
title: "CheckLine: fake news detection on social media"
#date: 2019-04-19T15:34:30-04:00
date: 2023-08-31T17:40:02+02:00
categories:
  - blog
tags:
  - Story
  - LLM
---
![fakenews](/LLM.github.io/assets/images/fakenews.png)
Fake news, hate speech and propaganda have always been a big issue for democratic societies. Especially with the rise of the Internet and social media, it has become easy to reach a large group of people with harmful opinions and deceptive statements. Large Language Models have had a significant impact on these issues as they can write propaganda that is persuasive with little human editing or even completely on its own (Goldstein et al., 2023). Also, the automatization of language agents has caused a flood synthetic (fake news) writing on social media.

As a consequence, users are easily manipulated into believing a contorted picture of reality. Furthermore, misinformation campaigns pose a threat to democratic discourse and democratic institutions as manipulation of a big group of people can prevent formation of informed opinions and decisions. 

That is why CheckLine, a new detection model has been introduced. It is an LLM-based model that is used on social media platforms to flag or filter out hateful posts and fake news, as well as social bots (Heidari & Jones, 2022), which might be more likely to post problematic content. CheckLine can deal with multiple languages (Schütz et al., 2022). The model was broadly implemented in a government initiative to counteract online disinformation campaigns.
 
## Best Case
CheckLine is proven to be a successful tool in countering disinformation on social media, as it is fast in detecting false claims. Finally, social media platforms have a chance in countering the huge amount of fake news. Institutionalized fake news are filtered out, rendering the public less polarized and less susceptible to extremist views. Consequentially, users can discuss more fairly and more transparently about important issues. Also, the retrieval of fake accounts and social bots behind problematic posts reveal insights into the structures behind single propaganda profiles.
 
## Worst Case
CheckLine is biased so that only a relatively small margin of posts is not flagged as fake news. Only a very narrow range of voices are given room to speak. Not only controversial, but also uncommon or minority opinions are filtered out and do not have a chance of discussion in the public discourse. Discussions critical of government actions are easily silenced as propaganda. As a consequence, user discussions are not real, free disputes, but rather uninformative and monotonous conversations. Apart from that, CheckLine in the end fails to achieve its goal – instead of mitigating polarization of society, it introduces oppression of certain opinions.
 
## What could be done better?
A propaganda detection model has to be conscientiously designed and evaluated to avoid excluding opinions. Policies have to be put in place to secure fair and transparent social media regulation and independent control, so that not one interest group becomes too powerful and oppresses others. From a technical point of view, propaganda detection tools have to be balanced between filtering out too little content that is actual propaganda and filtering out too much content that might contain loaded or provocative language but isn’t actual propaganda. What, in any case, should be fairly easy to establish is that fake news detection tools don’t automatically remove critical posts, but rather flag them as attention-worthy, so that a second (human) fact checker can assess whether they really offend guidelines.
 
## References
Goldstein, J. A., Chao, J., Grossman, S., Stamos, A., & Tomz, M. (2023). Can AI Write Persuasive Propaganda?.

Heidari, M., & Jones Jr, J. H. (2022). Bert model for social media bot detection.

Schütz, M., Böck, J., Andresel, M., Kirchknopf, A., Liakhovets, D., Slijepčević, D., & Schindler, A. (2022). AIT FHSTP at CheckThat! 2022: cross-lingual fake news detection with a large pre-trained transformer. Working Notes of CLEF.
