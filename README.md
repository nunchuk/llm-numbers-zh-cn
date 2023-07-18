# Numbers every LLM Developer should know

# Cheatsheet

<img width="1097" alt="llm-numbers-zh-cn" src="https://github.com/ray-project/llm-numbers/assets/16042528/7006be1e-ab3a-4366-b020-6281cd93e137">

# Next Steps

See our earlier [blog series on solving Generative AI infrastructure](https://www.anyscale.com/blog/ray-common-production-challenges-for-generative-ai-infrastructure) and [using LangChain with Ray](https://www.anyscale.com/blog/llm-open-source-search-engine-langchain-ray). \
 \
If you are interested in learning more about Ray, see [Ray.io](http://ray.io/) and [Docs.Ray.io](http://docs.ray.io/). \
 \
To connect with the Ray community join #LLM on the [Ray Slack](https://docs.google.com/forms/d/e/1FAIpQLSfAcoiLCHOguOm8e7Jnn-JJdZaCxPGjgVCvFijHB5PLaQLeig/viewform) or our [Discuss forum](https://discuss.ray.io/). \
 \
If you are interested in our Ray hosted service for ML Training and Serving, see [Anyscale.com/Platform ](http://www.anyscale.com/platform)and click the 'Try it now' button

**Ray Summit 2023:** If you are interested to learn much more about how Ray can be used to build performant and scalable LLM applications and fine-tune/train/serve LLMs on Ray, join [Ray Summit](https://raysummit.anyscale.com/) on September 18-20th! We have a set of great keynote speakers including John Schulman from OpenAI and Aidan Gomez from Cohere, community and tech talks about Ray as well as [practical training focused on LLMs](https://github.com/ray-project/ray-educational-materials/blob/main/NLP_workloads/Text_generation/LLM_finetuning_and_batch_inference.ipynb).

<!-- Footnotes themselves at the bottom. -->
## Notes

[^1]:
     Based on experimentation with GPT-3.5-Turbo using a suite of prompts on 2023-05-08. 

[^2]:
     Retrieved from [http://openai.com/pricing](http://openai.com/pricing) on 2023-05-08. 

[^3]:
      **GPT-4**: 6c/1k tokens for the prompt, 12c/1k tokens for the generation (32,000 window version, 8,000 window version is half that). **GPT-3.5 Turbo**: 0.2c/1k tokens. 

[^4]:
     This assumes the vector lookup is “free.” It’s not, but it uses CPUs (much cheaper) and is fairly fast. 

[^5]:
     1 million words / 0.75 tokens/word / 1000*0.03 = $40. 
