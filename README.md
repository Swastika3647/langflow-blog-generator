AI Blog Post Generator (Langflow)
This repository contains a Langflow workflow that automatically scrapes a tool's website and generates a 600-word professional blog post.

Components Used:
URL Component: Scrapes content from a provided URL (currently configured for toptools.zustbio.com).

Parser: Extracts the relevant text from the scraped data.

Prompt Template: Formats the input for the LLM.

Groq Model: Uses openai/gpt-oss-120b (via Groq) to generate the final copy.
