# llm-hindsights
A list of not serious but bothering flaws in pretrained generative language models

| Checkpoint | Tag | Description | Reference | Examples |
|------------|-----|-------------|-----------|----------|
| `tinyllama`  | `tokenizer` | They use bos as the document separator. So, bos token should not be prepended in the sequence. | TBD | TBD |
