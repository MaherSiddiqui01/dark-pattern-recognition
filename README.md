# Dark Pattern Detector

A Chrome extension that detects and highlights dark patterns on websites: deceptive design and manipulative language that pushes users into choices they did not intend to make.

## What it does
- Analyzes on-page text with a BERT-based NLP model to flag manipulative or misleading wording (fake urgency, guilt-tripping, confusing opt-outs).
- Scans the page for tricks like pre-checked boxes, disguised ads, and misleading buttons.
- Shows real-time alerts with a short explanation of why each element was flagged.

## Why
Dark patterns quietly steer people into subscriptions, extra purchases, and data sharing. SakV helps users spot them while browsing.

## Tech
Python, BERT (Transformers), NLP, JavaScript, Chrome Extension

## How it works
1. The extension reads visible text and elements from the current page.
2. The text goes to the model, which classifies it as a dark pattern or not.
3. Flagged elements are highlighted on the page with an explanation.

## Installation
1. Clone the repo:
```bash
   git clone https://github.com/MaherSiddiqui01/dark-pattern-recognition.git
```
2. Open `chrome://extensions` and turn on **Developer mode**.
3. Click **Load unpacked** and select the `extension` folder.
4. Open any website and the extension will scan the page.

## Author
Maher Siddiqui
