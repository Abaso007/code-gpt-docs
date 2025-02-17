---
sidebar_position: 8
---

# Google Vertex AI
Official website [https://cloud.google.com/](https://cloud.google.com/)

## Connect your Vertex credentials
Obtaining your credentials on Google Cloud can be tricky. As of March 28, 2024, here's the process to obtain them:

### On Google Cloud
- Navigate to https://cloud.google.com/ and log in with your Gmail account.
- Initiate the Console by selecting the option in the top right corner.
- In the left panel, click on the "Models Garden" tab.
- In the search box at the top, type "Vertex AI". Choose "Virtual Studio Vertex".
- Ensure you have enabled the Vertex AI API, Dataform API, and Compute Engine API.
- Go to the [Dashboard](https://console.cloud.google.com/home/dashboard).
- From the right-hand menu, select "API & Services" and click "Credentials". Click on the email associated with Service Accounts.
You'll be directed to the Service Account page. From there, navigate to the "Keys" tab and select "Add Key." The download should start automatically, and the file should be saved as a .json.
- Rename the downloaded file to "credentials".
- For the Custom Link, customize it as needed, ensuring the LOCATION, PROJECT_ID, and MODEL are changed.
`https://LOCATION-aiplatform.googleapis.com/v1/projects/PROJECT_ID/locations/LOCATION/publishers/google/models/MODEL:streamGenerateContent`
- Choose `Vertex` as `Provider`.
- Click on `Connect` or `Set connection`
- Paste the link model and Upload the credential.json file.
- Click on `Connect`




:::caution Remove Key
If you want to remove your API Key from CodeGPT, click on the provider box and click on `Disconnect`.


:::
 

## Vextex Models available in CodeGPT

### Gemini
- Llama3-8b-Hf
- llama3-8b-chat-hf
- llama3-70b-hf
- llama3-70b-chat-hf
- gemini-pro
- gemini-1.0-pro
- gemini-1.5-pro-latest
- gemini-1.5-pro-preview-0514
- gemini-1.5-flash-preview-0514
- gemini-ultra
- gemini-nano

## API Errors
If you are getting API errors, check the following link: [Vertex AI Documentation](https://cloud.google.com/vertex-ai/docs)
