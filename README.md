# Prompt Management in GCP (Vertex AI)

Prompt Management in GCP allows you to create, version, and store prompt templates for LLMs like Gemini. These templates can be reused across your AI apps, ensuring consistency and easy updates.



# saved prompts
![Screenshot 2025-04-13 191944](https://github.com/user-attachments/assets/45dc850e-fbc6-4259-a053-d7d53448a426)

/
✅ How to Use Saved Prompts

1-In Vertex AI Studio
 Test and update prompts directly in the UI with different models (e.g., Gemini Pro).

2-In Your Code (Python / API)
 Load the prompt template, fill in dynamic variables, and call the model:
```
prompt = f"Summarize this text: {document_text}"
model.predict(prompt=prompt)
```
/

3-In RAG Pipelines

Retrieve relevant context from documents.

Inject it into a saved prompt template.

Send it to the LLM for a response.




## One-shot prompting
![Screenshot 2025-04-13 192047](https://github.com/user-attachments/assets/2fd109ee-fe9e-4866-817c-31d8a4a4c6e9)
![Screenshot 2025-04-13 192110](https://github.com/user-attachments/assets/fff42d26-0e81-486e-b8fe-12f13979b641)


## Few-shot prompting
![Screenshot 2025-04-13 191400](https://github.com/user-attachments/assets/b00bb413-d339-4f72-b223-139efaac6316)
![Screenshot 2025-04-13 191506](https://github.com/user-attachments/assets/37783a63-9b75-46d7-845b-43a8501a8b3b)


## Instructions
![Screenshot 2025-04-13 191720](https://github.com/user-attachments/assets/3055608c-0d20-420f-a9de-d5ce82138ece)
![Screenshot 2025-04-13 191846](https://github.com/user-attachments/assets/c84bfa13-c197-4837-871a-3ce3590b4d44)


