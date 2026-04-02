# llm-playground

A lightweight LLM playground built with zero dependencies —
pure HTML, CSS and vanilla JavaScript. Test prompts, compare
models side by side and track costs in your browser.

## Features

- Prompt editor with system prompt support
- Side-by-side model comparison
- Cost estimation per run
- Token counting with live estimate
- Latency tracking per call
- Run history with localStorage persistence
- Ctrl+Enter shortcut to run
- Zero dependencies — single HTML file

## Run

Just open the file in your browser:
```bash
open index.html
```

Or serve it locally:
```bash
npx serve .
python -m http.server 8080
```

Then enter your OpenAI API key in the sidebar.

## Usage

1. Paste your OpenAI API key in the sidebar
2. Choose a model and set temperature / max tokens
3. Write your prompt and press **▶ Run** or **Ctrl+Enter**
4. Switch to **Compare** tab to test two models side by side
5. Click any history entry to restore the response

## Project Structure
```
llm-playground/
├── index.html    # Everything — UI, logic, styles
└── README.md
```

## Author

**Szymon Wypler**
