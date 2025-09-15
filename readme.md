# For local code migration steps

1. Create .env file and set the key
   GEMINI_API_KEY=<place the gemini key>

2. Disable colab settings and enable local.

# Step 2: Import and Configure

!pip install python-dotenv

from dotenv import load_dotenv
import os   
load_dotenv()
API_KEY = os.getenv("GEMINI_API_KEY")

