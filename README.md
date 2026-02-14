# nlp-algorithms
This repository presents implementation of key strategies used in natural language processing.

# Contents

### BPE Tokenizer (`bpe_tokenizer.ipynb`)

The notebook provides a full overview of how byte-pair encoding can be employed to split sentences into sequences of subword tokens. The Brown Corpus was used for training. I adapt the solution from the following <a href="https://arxiv.org/pdf/1508.07909">paper</a> by R. Sennrich. Additionally, for faster inference, the tokenization part was tuned to find possible merges in each word and apply them based on appearence in vocabulary instead of exhaustive search over all merges.