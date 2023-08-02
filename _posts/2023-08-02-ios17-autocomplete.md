---
title: "Autocomplete on iOS 17"
date: 2023-08-02T12:40:00+01:00
categories:
  - blog
tags:
  - AI
  - Transformers
  - iOS
---
🔗 [Link to "The Talk Show" - episode 382](https://daringfireball.net/thetalkshow/2023/07/31/ep-382)

In the most recent episode of "The Talk Show," John Gruber and Craig Hockenberry discussed the new autocomplete feature of iOS 17.

Gruber:
> To me, it is THE single biggest improvement to [iOS] since the very first iPhone.

Not only is it one of the most significant improvements to iOS from a UX perspective, but it's also one of the biggest milestones in AI. In fact, it's hard to overstate the importance of this development for Apple's future in AI. To understand why, we need to delve a little deeper into the technical details of this feature.

The new autocomplete feature is powered by a specific neural network architecture called `Transformers`. It's the same architecture that powers popular AI chatbots like ChatGPT and Bard. In a talk I gave at the [Data Science Conference](https://datasciconference.com/) in October 2022, I referred to GPT-3 (the predecessor to ChatGPT) as ["autocomplete on steroids"](https://youtube.com/clip/Ugkx4KFCXi7LIVnVJ4H8G6IV0_8kZYbdsyCe).

Hockenberry:
> [...] it's basically working off a corpus of information [...] it's got more context.

That's exactly right: These AI models are capable of understanding the context of the preceding text and then *magically* guess the next word correctly (more often than not). This ability is what makes these chatbots so enticing (although the magic & novelty has worn off quite a bit for me since ChatGPT's release in Nov 2022).

Now, you might have heard that running these AI systems is very compute-intensive, which is correct. They usually require many GPUs, a necessity stemming from the fact that computational requirements grow quadratically with the length of the text. Being able to run such a sophisticated AI system locally on an iPhone is *bananas*! There have been successful attempts to run open-source language models [locally on laptops](https://github.com/ggerganov/llama.cpp), but doing so as a hobby project versus running it on a device/operating system exposed to 1 billion (!) users with production-grade quality are two entirely different challenges.

The feat of running a transformer AI model on an iPhone marks an unprecedented accomplishment for Apple, catapulting them to the forefront of the AI revolution, in my opinion anyway. This is not just a technical marvel but a statement of intent, highlighting Apple's commitment to integrating cutting-edge AI into everyday user experiences, whether they want to call it *AI* or not. Leveraging the Transformers architecture, which powers some of the most advanced AI systems in the world, within a handheld device is a glimpse into a future where AI becomes more personalized and accessible, right at our fingertips.
