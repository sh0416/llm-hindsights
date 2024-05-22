# llm-hindsights
A list of not serious flaws in pretrained language models

| Checkpoint | Tag | Description | Reference |
|------------|-----|-------------|-----------|
| `tinyllama`  | `tokenizer` | They use bos as the document separator. So, bos token should not be prepended in the sequence. | TBD |
