# Using-LLMs-to-Discover-Legal-Factors

In this repository we hold the prompts used in the paper *Using LLMs to Discover Legal Factors*, available at https://arxiv.org/abs/2410.07504. 

case_analysis_conclusion_finding_prompt: This prompt was used with a large context window LLM (132k) to identify the court's analysis and conclusion of a particular issue, such as reasonable suspicion to detain a motorist on suspicion of drug trafficking.

initial_factor_finding_prompt: This was used to generate a list of rough factors based on multiple analysis and conclusion sections from different opinions on the same legal issue.  In the paper we refer to this as 'rough' set of factors. 

factor_refinement_prompt_general: This prompt was used to create a refined factor representation based on the rough set of factors identified by the initial_factor_finding_prompts. 

### Attribution: Please cite the paper and make proper attributions when using these prompts or variations thereof. Until the final version is published, please use this citation: 
Gray, M., Savelka, J., Oliver, W., & Ashley, K. (2024). Using LLMs to Discover Legal Factors. arXiv preprint arXiv:2410.07504.

