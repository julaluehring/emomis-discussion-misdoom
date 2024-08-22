# Presentation at MISDOOM 2024 in Münster
*6th Multidisciplinary International Symposium on Disinformation in Open Online Media*
Wednesday, 04.09.2024, 10.30am

Presentation slides [here]().

Title: Effects of Misinformation on Online Discussions 

Extended abstract: Research shows that misinformation elicits negative sentiments (e.g., Zollo et al., 2015), boosting its traction and engagement on social media (Robertson et al., 2023). However, data collection methods often sample subsets of news, such as fact-checked stories, thereby misrepresenting the broader spectrum of news shared on social media platforms. In addition, existing studies frequently fail to distinguish emotions within news from reactions to the news, a crucial distinction for understanding their role in engagement (Lühring, Shetty, et al., 2023). Therefore, it is unclear whether observed dynamics are unique to misinformation, or if we are, in fact, measuring common causes like political orientation or emotions in the stimuli, for instance, in hateful topics (Mosleh et al., 2024). Here, we study 9M German Twitter (now X) discussions from October 2020 to March 2022 that follow a post mentioning sources with varying trustworthiness levels (~22M posts). Hence, we operationalize misinformation as posts mentioning untrustworthy sources. To do so, we rely on continuous source trustworthiness (0-100) and political orientation (left/right) ratings by the organization NewsGuard. 
In the first analysis step, we used a nonparametric matching approach to categorize the discussions (with at least one reply) into trustworthy vs. untrustworthy and balance our dataset on a set of covariates to approximate causal inference (emotions in the initial post, political orientation, author following/follower count, word count, time difference between first and last reply). Using pre-existing machine learning classifiers to infer eight distinct emotions (pol_emo_mDeBERTa; Widmann & Wich, 2022; macro F1=0.7) and out-group references (Lasser at al., 2023; F1=0.8) from text, we analyzed the effects of posts mentioning sources with varying trustworthiness and different political orientations on the development of online discussions. Results of OLS regressions showed that untrustworthy sources in the first tweet predict significantly more anger co-occurring with out-group references, both in emotions aggregated for the whole discussion and the first reply to the initial post only. Vice versa, trustworthy sources predict more joy. An analysis of the covariates hints at the underlying processes: For every aggregated emotion in the discussion, the same emotion was always the strongest predictor. Without the matching, including the initial posts that did not get a reply, therefore using models that account for zero-inflated data, we analyzed the posts starting a discussion and found that posts containing untrustworthy sources significantly showed more anger and out-group references. Lower trustworthiness was associated with more retweets and quotes.
In conclusion, our study indicates that misinformation has negative effects on online discussions, potentially leading to increased engagement. However, due to its low prevalence, these effects are limited overall and seem to hinge on misinformation containing more anger and conflict. We plan to further test the robustness of our results by bootstrapping the heavy-tailed distributions and to characterize the full discussion trees. 


Lasser, J., Herderich, A., Garland, J., Aroyehun, S. T., Garcia, D., & Galesic, M. (2023). Collective moderation of hate, toxicity, and extremity in online discussions (arXiv:2303.00357). arXiv. http://arxiv.org/abs/2303.00357
Lühring, J., Shetty, A., Koschmieder, C., Garcia, D., Waldherr, A., & Metzler, H. (2023). Emotions in misinformation studies: Distinguishing affective state from emotional response and misinformation recognition from acceptance. PsyArXiv. https://doi.org/10.31234/osf.io/udqms
Mosleh, M., Cole, R., & Rand, D. G. (2024). Misinformation and harmful language are interconnected, rather than distinct, challenges. PNAS Nexus, 3(3), pgae111. https://doi.org/10.1093/pnasnexus/pgae111
Robertson, C. E., Pröllochs, N., Schwarzenegger, K., Pärnamets, P., Van Bavel, J. J., & Feuerriegel, S. (2023). Negativity drives online news consumption. Nature Human Behaviour, 7(5), https://doi.org/10.1038/s41562-023-01538-4
Widmann, T., & Wich, M. (2022). Creating and Comparing Dictionary, Word Embedding, and Transformer-Based Models to Measure Discrete Emotions in German Political Text. Political Analysis, 1–16. https://doi.org/10.1017/pan.2022.15
Zollo, F., Novak, P. K., Vicario, M. D., Bessi, A., Mozetič, I., Scala, A., Caldarelli, G., & Quattrociocchi, W. (2015). Emotional Dynamics in the Age of Misinformation. PLOS ONE, 10(9), e0138740. https://doi.org/10.1371/journal.pone.0138740

**Find the full conference program [here](https://www.misdoom2024.uni-muenster.de/).** 
