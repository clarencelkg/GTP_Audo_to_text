# GTP_Audo_to_text
Used Whisper to Transcribe, GPT-4o to Summarize NDP key note taken from CNA.
1. Installs the Python package called "openai" using the pip package manager
   and Import all the necessary class and module.
   pip install openai
   
2. Setup your API key with an environment variable
   export OPENAI_API_KEY='sk-...'
   or Setup your API key by using the OpenAI package
   You can set up a key within your Python program using openai.api_key.
   This method is not recommended as it exposes your API to the public.
   I using this method only for testing purpose.

   api_key = "sk-"
   os.environ["OPENAI_API_KEY"] = api_key 
   
   
