# ClickGPT

A small app to fix text using Open AI GPT models.

![ClickGPT](/res/preview.gif)

## Usage

Create API key at https://platform.openai.com/api-keys or use existing one

Copy and paste an API key into config.ini to APIKey field

```ini
[OpenAI]
ApiKey=YOUR_API_KEY_HERE
```

Start an app using `start.sh` or `start.bat`(Windows)

To fix the text select it and press **Ctrl+`** Then select needed operation. Wait for the answer and then copy paste text.

## Limitation

Since it is using Open AI GPT model, sometimes responses may be wrong or unclear. Use on your own risk!
