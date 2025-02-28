To run this project, first you need to login to livekit, craete an account and generate their free livekit api key, livekit secret key and livekit url.

create an .env file and set the following environment variables

OPENAI_API_KEY = 
LIVEKIT_URL = 
LIVEKIT_API_SECRET = 
LIVEKIT_API_KEY =

After this create an python environment

```bash
python3 -m venv venv
```

and then run

```bash
python main.py start
```

And you'll get connect to your room and the agent.