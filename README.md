# Daily Motivational Quote Logic App

This project demonstrates a simple Azure Logic App that sends a motivational quote to your email every morning. It’s designed as an AZ‑900–level showcase of cloud automation, serverless workflows, and API integration.



## Features
- Daily scheduled trigger  
- Fetches quotes from a public API  
- Parses JSON  
- Sends formatted email  
- Fully deployable via ARM template  



## Architecture
1. **Recurrence Trigger** – runs every morning  
2. **HTTP GET** – calls https://api.api-ninjas.com/v2/quotes 
3. **Parse JSON** – extracts quote + author  
4. **Email Connector** – sends the message  



## Example Email

> "The best way to predict the future is to create it."  
> — Peter Drucker



## License
This project is licensed under the MIT License.
