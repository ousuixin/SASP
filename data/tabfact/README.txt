table.jsonl contains all preprocessed tables
data_shard/dev.jsonl contains all preprocessed examples in the development set
data_shard/test.jsonl contains all preprocessed examples in the test set
data_shard/train*.jsonl contains all preprocessed examples in the train set
  - we process examples with "preprocess_example.py" and "gen_with_func.py", and move the processed examples into data_shard
saved_programs.jsonl contains all programs (around 10 programs per example) sampled with ζt in eq(2)
trigger_word_all.json contains all trigger words
../config/config.vanilla_bert.json contains some hyper parameters
