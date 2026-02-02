# LLM Project

This project sends an image and a text prompt to Groq's multimodal LLM and prints the response.

## Requirements
- Python 3.10+
- A Groq API key set in the environment as `GROQ_API_KEY`

## Setup
1. Install dependencies:
	- `pip install -r requirements.txt`
2. Create a `.env` file (optional) and add:
	- `GROQ_API_KEY=your_key_here`

## Usage
1. Put an image file (default: `acne.jpg`) in the project folder.
2. Run:
	- `python llm_brain.py`

## Notes
- The script includes basic exception handling for missing API keys, missing image files, and request errors.
- Update `query`, `model`, or the image path in `llm_brain.py` to change behavior.
