# User Agents

A collection of browser and operating system User-Agent strings for Any projects and other applications.

## Features

- 1,000+ User-Agent entries
- Windows, macOS and Linux user agents
- Android and iOS user agents
- Multiple browser types
- Easy to integrate into projects

## Repository Structure

```text
useragents/
├── Useragent.txt
└── README.md
```

## Usage

You can use the User-Agent list in Python by importing it:

```python
import random

from Useragent import user_agents

user_agent = random.choice(user_agents)

print(user_agent)
```

Alternatively, you can download the file directly:

```python
import requests

url = "https://raw.githubusercontent.com/replitcode956-hub/useragents/main/Useragent.txt"

response = requests.get(url)
print(response.text)
```

## Disclaimer

This repository is provided for educational and development purposes.

User-Agent strings are identifiers supplied by clients when making HTTP requests. They should not be treated as reliable proof of a client's identity or browser.

## License

Use, modify, and distribute this collection at your own discretion, subject to the applicable rights of the original data sources.
