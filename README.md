# llm-authorship-cmpsc448

# Who Wrote It? Identifying LLMs from Their Responses

CMPSC 448 Midterm Project by Jiya Patel - Solo

Classifies which LLM family (GPT, Claude, Llama, Mistral, Google) wrote a response, using a CNN and a bidirectional LSTM in PyTorch.

## Files
- `llm_authorship.ipynb`: all code (data prep, models, experiments)
- `Who Wrote It...pdf`: project report
- `confusion.png`, `curves.png`, `rq2.png`: figures used in the report

## Data
LMArena (formerly LMSYS) Chatbot Arena dataset, `arena-human-preference-55k` on Hugging Face. The notebook downloads it automatically.

## How to run
Open the notebook in Google Colab, set the runtime to GPU, and run all cells.
