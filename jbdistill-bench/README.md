**JBDistill-Bench** is a challenging benchmark for LLM safety. It is produced by running our proposed Jailbreak Distillation method, which transforms seed goals into adversarial prompts using diverse attacks, and then employ prompt selection algorithms to select an effective set of evaluation prompts.
JBDistill-Bench contains 500 single-turn adversarial prompts and 500 multi-turn adversarial prompts.

## HarmBench format for dataset
- `rbs500_4singleturn/test_cases/test_cases.json` contains the single turn benchmark.
- `rbs500_4multiturn/test_cases/test_cases.json` contains the multi turn benchmark.

## Evaluation Results on Popular LLMs
As shown below, our JBDistill-Bench achieves very high attack success rate (ASR) on a wide range of LLMs. Specifically, **we successfully attack OpenAI o1 with >60% ASR**, evaluated using the HarmBench judge.

![image/png](https://cdn-uploads.huggingface.co/production/uploads/62fb40b59af1d16bc0ac60f4/2WIr6MDslHsWaH3Kuz7vS.png)
