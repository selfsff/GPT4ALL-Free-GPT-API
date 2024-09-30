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

## Limits

When you sign up, you will have **free access to 4 dollars per month.** You can spend them when using GPT 4, GPT 3.5 and other models. 

But the prices for the models will be much lower than OpenAI and Anthropic. In the future there may be changes in price and starting balance, follow the news in our telegram channel. 

You can also buy tariffs, with which you will have access to limited models, as well as will be increased balance per month.

## Rate Limits
**Limit for /v1/chat/completions:**

***Free plan** 15 requests per minute, 200 requests per day* 

***Tier 1** 50 requests per minute, 800 per day* 

***Tier 2** 80 requests per minute, 1300 per day*

***Tier 3** 2500 requests per day*

***Tier 4** 4200 requests per day*

***Tier 5** 7500 requests per day*

***Tier 6** 12000 requests per day*


**Limit for /v1/image/generations:**

***Free plan** 8 requests per minute, 60 requests per day* 

***Tier 1** 30 requests per minute, 120 per day* 

***Tier 2** 60 requests per minute, 160 per day*

***Tier 3** 350 requests per day*

***Tier 4** 350 requests per day*

***Tier 5** 350 requests per day*

***Tier 6** 350 requests per day*

These limits are also subject to change

## Plans
*detailed description of tariffs is written in the documentation*

## Models
### OpenAI
- o1-preview (premium)
- o1-mini (premium)
- gpt-4o (premium)
- gpt-4o-mini
- gpt-4
- gpt-3.5-turbo
- dall-e-3

### Open Source
- llama-3.1-405b
- llama-3.1-70b
- llama-3-70b
- llama-3-8b
- wizardlm-2-8x22B
- mixtral-8x22b

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
