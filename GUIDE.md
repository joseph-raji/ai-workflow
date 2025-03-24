# AI Calendar Workflow Guide  

## 1. Setup n8n  
- Sign up at [n8n.io](https://n8n.io)  
- Create a new workflow  

## 2. Add AI Agent
![image](https://github.com/user-attachments/assets/2534ad9f-896a-42ca-ae47-57998ed56c6f)

   ### 2.1 Integrate ChatGPT for AI Processing  
   - Add an **Chat Model**  
   - Connect to **OpenAI API** for natural language understanding  
   - You can create a free API key here: [OpenAI Account](https://auth.openai.com/create-account)
     ![image](https://github.com/user-attachments/assets/2af067eb-8648-4680-ad68-2640d08b6f24)

   ### 2.2 Connect Google Calendar  
   - Add a **Google Calendar node** in n8n  
   - Configure authentication and permissions to enable event scheduling
     ![image](https://github.com/user-attachments/assets/c2b1f6d8-883a-47f9-b6b2-0a3539684542)


## Troubleshooting  
- **Events not scheduling?** Check API keys and workflow logic  
- **Incorrect times?** Ensure time zone settings are correct  

## Cleanup  
- Delete credentials in n8n  
- Remove test calendar events  
