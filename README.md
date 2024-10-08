![saplings](https://github.com/kanopi/saplings/assets/5177009/a6377e32-deb2-49d8-873a-f3dd5a36fa7c)

# Saplings - AI CKEditor Experience

Helpful AI functionality for content creators.

## Features
- Generation of content from AI using optional style and tones.
- Translation of content using user determined languages using AI.
- Summary of selected text using AI.

Includes `AI Tones` and `AI Languages` taxonomies.

## Installation

```
composer require kanopi/saplings-ai-ckeditor-experience
cd web && php core/scripts/drupal recipe ../recipes/saplings-ai-ckeditor-experience
```

### Configure OpenAI

While the AI module supports many AI services, this recipe is configure to use
OpenAI.

1. Create an API key at https://platform.openai.com
2. Create a key file at `private://keys/openai_provider.key`. That is usually at
   `[webroot]/sites/default/files/private/keys/openai_provider.key`.
3. Once you are ready to deploy, be sure to place that key in your cloud
environments.
