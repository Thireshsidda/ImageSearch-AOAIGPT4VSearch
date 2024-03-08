# ImageSearch-AOAIGPT4VSearch

### This is image retrieval multi modal RAG pipeline which can results text and releveant images as completion to the user's query.
### Here are the steps that I had followed to creat this pipeline.
1. Install and import necessary packages
2. Define utility functions.
3. Data preparation
4. Creating Azure cognitive search with dataframe content
5. Search results


### In order to run your application, you should have the following credentials of Azure OpenAI and Azure Cognitive Search in your ".env" file.
#### Azure OpenAI
    api_base = '' 
    deployment_name = ''
    API_KEY = ''
    base_url = f"{api_base}openai/deployments/{deployment_name}" 


#### Azure Cognitive Search
    cs_key = os.getenv("COG_SEARCH_ADMIN_KEY")
    cs_endpoint = os.getenv("COG_SEARCH_ENDPOINT")
