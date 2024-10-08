![saplings](https://github.com/kanopi/saplings/assets/5177009/a6377e32-deb2-49d8-873a-f3dd5a36fa7c)

# Saplings - AI CKEditor Experience

Helpful AI functionality for content creators.

## Features
- Generation of content using AI.
- Alteration of content in specific tones using AI.
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
environments on the site's host. If you place it in the canonical environment,
it will get cloned on subsequent multidev clones.

## Usage

To use the configured AI tools, start by clicking the *AI Assistant* button in
any Full HTML CKEditor instance.

### Generate with AI

When you click the AI Assistant button > Generate with AI option, a modal pops
up presenting:

> What would you like to ask or get ideas for?

- Enter your prompt to AI to help you write your content.

  Example: Write three paragraphs about Kanopi Studio's Saplings suite of
  Recipes.

- After you have written your prompt, click the *Generate* button.

  You can click the button multiple times to get different responses from the AI
  source.

  After you click the Generate button, below the *Response from AI* field, you
  will see the *AI Writer: Idle* message switch to
  *AI Writer: Waiting for response*.

  Once the AI action has completed, it will switch back to Idle.

- The response is saved in the *Response from AI* field.

  You can edit the response before saving it back to the main editor.

  When you are satisfied with the content, click the *Save changes to editor*
  button.

- Be sure to click *Save* on your node/page to ensure your changes are saved.

### Summarize

- Select text in CKEditor.

- Click the AI Assistant button, then select *Summarize*.

- Click the *Summarize* button.

  After you click the Summarize button, below the *Response from AI* field, you
  will see the *AI Writer: Idle* message switch to
  *AI Writer: Waiting for response*.

  Once the AI action has completed, it will switch back to Idle.

- The response is saved in the *Response from AI* field.

  You can edit the response before saving it back to the main editor.

  When you are satisfied with the content, click the *Save changes to editor*
  button.

- Be sure to click *Save* on your node/page to ensure your changes are saved.

### Tone

- Select text in CKEditor.

- Click the AI Assistant button, then select *Tone*.

- Select the Tone you want to rewrite your content in, then click the *Generate*
  button.

  After you click the Generate button, below the *Response from AI* field, you
  will see the *AI Writer: Idle* message switch to
  *AI Writer: Waiting for response*.

  Once the AI action has completed, it will switch back to Idle.

- The response is saved in the *Response from AI* field.

  You can edit the response before saving it back to the main editor.

  When you are satisfied with the content, click the *Save changes to editor*
  button.

- Be sure to click *Save* on your node/page to ensure your changes are saved.

### Translate

- Select text in CKEditor.

- Click the AI Assistant button, then select *Translate*.

- Select or add the Language you want to rewrite your content in, then click the
  *Translate* button.

  After you click the Translate button, below the *Response from AI* field, you
  will see the *AI Writer: Idle* message switch to
  *AI Writer: Waiting for response*.

  Once the AI action has completed, it will switch back to Idle.

- The response is saved in the *Response from AI* field.

  You can edit the response before saving it back to the main editor.

  When you are satisfied with the content, click the *Save changes to editor*
  button.

- Be sure to click *Save* on your node/page to ensure your changes are saved.
