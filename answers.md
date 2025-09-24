1.If you only had 200 labeled replies, how would you improve the model without collecting thousands more?
With just 200 labeled replies, i would try techniques like data augmentation (ex: paraphrasing sentences or using back-translation) and transfer learning from a pre-trained model. I could also use semi-supervised learning by making use of unlabeled replies to improve the model without collecting thousands more labels.

2. How would you ensure your reply classifier doesn’t produce biased or unsafe outputs in production?
To avoid biased or unsafe predictions, I would make sure the dataset is balanced and diverse, apply filters to catch unsafe content, and regularly check the model’s predictions to fix any issues that arise.

4. Suppose you want to generate personalized cold email openers using an LLM. What prompt design strategies would you use to keep outputs relevant and non-generic?
I would give the model clear context like the recipients details, industry, and the tone I want. I would also provide examples or instructions to make the output more relevant and personalized, rather than generic.
