<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?color=%2336BCF7&lines=GPT4ALL&font=Fira%20Code&center=true&width=380&height=50&duration=4000&pause=1000" alt="GPT4All">
</p>

<p align="center">
  <h1 align="center">Free GPT-4 API access</h1> 
</p>

We provide free access to the GPT-3.5-Turbo, GPT-4, GPT-4-Turbo and many other models.
To familiarize yourself with the API usage please follow this link

> [!IMPORTANT]
> - [Documentation](https://docs.gpt4-all.xyz)
> - [Telegram Channel](https://t.me/gpt4alltg)
> - [How to receive a token](https://docs.gpt4-all.xyz/main/receiving-a-api-token)

## API Endpoint
Endpoint

https://api.gpt4-all.xyz/v1

# Usage
## Python

Chat Completions
``` Python
from openai import OpenAI

client = OpenAI(api_key="YOUR_TOKEN", base_url="https://api.gpt4-all.xyz/v1")

response = client.chat.completions.create(
    model="gpt-4o-mini",
    messages=[{"role": "user", "content": "hi"}],
    stream=False,
)

print(response.choices[0].message.content)
```

Images Generations
``` Python
from openai import OpenAI

client = OpenAI(api_key="YOUR_TOKEN", base_url="https://api.gpt4-all.xyz/v1")

response = client.images.generate(
    model="dall-e-3",
    prompt="cat",
)

print(response)
```

## Link
[Telegram Channel](https://t.me/gpt4alltg)

[Telegram bot](https://t.me/gpt4all_robot)

[Docs](https://docs.gpt4all.pp.ua)
