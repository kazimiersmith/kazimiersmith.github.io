---
layout: default
title: Kazimier Smith
---

![Kazimier Smith](kazimier_smith_headshot.jpeg)

# Kazimier Smith

**kazimiersmith@gmail.com**

I am a Postdoctoral Associate at the Massachusetts Institute of Technology.
I work under the supervision of
[Neil Thompson](https://www.neil-t.com).
I am interested in the economics of digital platforms, artificial intelligence, and social media.
I completed my PhD in economics at the Stern School of Business at New York University under the supervision of
[Luís Cabral](http://www.luiscabral.net).
Here is my [CV](/docs/kazimier_smith_cv.pdf).
I describe my research below.

## Research

### Working papers

- [From Funding to Findings (FIND): An Open Database of NSF Awards and Research Outputs](/docs/nsf_output.pdf)
    (with [Yucheng Lu](https://sites.google.com/nyu.edu/yuchenglu/home) and Qiaochu Fan).
    Public funding plays a central role in driving scientific discovery. To better understand the link between research inputs and outputs, we introduce FIND (Funding-Impact NSF Database), an open-access dataset that systematically links NSF grant proposals to their downstream research outputs, including publication metadata and abstracts. The primary contribution of this project is the creation of a large-scale, structured dataset that enables transparency, impact evaluation, and metascience research on the returns to public funding. To illustrate the potential of FIND, we present two proof-of-concept NLP applications. First, we analyze whether the language of grant proposals can predict the subsequent citation impact of funded research. Second, we leverage large language models to extract scientific claims from both proposals and resulting publications, allowing us to measure the extent to which funded projects deliver on their stated goals. Together, these applications highlight the utility of FIND for advancing metascience, informing funding policy, and enabling novel AI-driven analyses of the scientific process.

- [Influencer Dynamics](/docs/influencer_dynamics.pdf)
    Consumers use social media for entertainment and to discover new products. To reach potential customers, brands pay influencers to feature products in their content. Payment depends on the size of the influencer’s audience, and the effectiveness of the endorsement relies on trust. Excessive product recommendations may erode the relationship between an influencer and their followers. I develop a dynamic model in which an influencer produces sponsored posts (which include product recommendations) and organic posts (without product recommendations). Both affect the influencer’s growth and require effort to produce. A sponsored post incurs additional costs: it requires searching for and negotiating with brands, and followers are less likely to engage with it. Using 2,780,011 Instagram posts and 136,453 TikTok posts from 1,369 influencers, I quantify the engagement penalty by comparing identical posts across platforms. Analyzing the influencers’ career histories, I show that organic and sponsored posts have similar effects on follower growth. I leverage variation in the number and types of posts to estimate the unknown cost parameters in the model. An influencer with 100,000 followers optimally produces about 0.25 sponsored posts and two organic posts per week, and influencers with more followers produce more content of both types. Viral posts provide a transient boost to growth, but career progression largely depends on consistent content production. Regulating sponsored content can theoretically backfire by decreasing incentives to produce organic posts, but counterfactual simulations assuage this concern. A cost increase that reduces sponsored content by 25% only causes a 2.7% drop in organic content.

- [Feeding LLM Annotations to BERT Classifiers at Your Own Risk](/docs/llm_bert.pdf)
    (with [Yucheng Lu](https://sites.google.com/nyu.edu/yuchenglu/home))
    Using LLM-generated labels to fine-tune smaller encoder-only models for text classification has gained popularity in various settings. While this approach may be justified in simple and low-stakes applications, we conduct empirical analysis to demonstrate how the perennial curse of training on synthetic data manifests itself in this specific setup. Compared to models trained on gold labels, we observe not only the expected performance degradation in accuracy and F1 score, but also increased instability across training runs and premature performance plateaus. These findings cast doubts on the reliability of such approaches in real-world applications. We contextualize the observed phenomena through the lens of error propagation and offer several practical mitigation strategies, including entropy-based filtering and ensemble techniques. Although these heuristics offer partial relief, they do not fully resolve the inherent risks of propagating non-random errors from LLM annotations to smaller classifiers, underscoring the need for caution when applying this workflow in high-stakes text classification tasks.

### Works in progress

- [Platform Competition with Network-based Ad Targeting](/docs/platform_choice_networks_slides.pdf)
