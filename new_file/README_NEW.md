# Aider Fork

This fork of the [original Aider repository](https://github.com/paul-gauthier/aider) introduces several changes to make the Aider tool compatible with the OpenAI GPT-4-32k model and to modify the OpenAI API request to work with OpenRouter.

## Changes

1. The default model has been changed from GPT-3.5 to GPT-4-32k in both the `base_coder.py` and `main.py` files.

2. The `send_with_retries` function in `base_coder.py` has been updated to use the "openai/gpt-4-32k" model and additional headers have been added to the API request.

3. A new model, GPT4_32k, has been added to the `models.py` file, and the known tokens and pricing for this model have been updated.

## Credits

All credit for the original Aider tool goes to the [original repository](https://github.com/paul-gauthier/aider).
