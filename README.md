# llm-hacking
CSE 227 project on hacking TritonGPT.

PROMPT ATTACKS:
- Imprompter
- Neural Exec

Models / Products:
- Llama 3, TritonGPT
- Mixtral, LeChat

Evaluation datasets:
- Adversarial strings: https://github.com/llm-attacks/llm-attacks/tree/main/data/advbench

Evaluation metrics:
- Success rate
- Toxicity as judged by LM (GPT-4o if it doesn't defer on toxic judgments, Llama-3 Instruct if not)




TODO:
- Find more adversarial datasets
- Find a few handcrafted prompts for heuristic baselines (probably will not work on product)
- Find prompts from:
    - Imprompter
    - Transferable Attacks
    - Neural Exec

- Implement evaluation loop
    - Start with hand-inputting into TritonGPT (eventually should automate)# llm-hacking
