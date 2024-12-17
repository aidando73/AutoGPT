```bash
cd classic

source ~/miniconda3/bin/activate && conda create -n auto-gpt python=3.10

source ~/miniconda3/bin/activate && conda activate auto-gpt

./run setup

./run agent create ExampleAgent

./run agent start ExampleAgent
```
