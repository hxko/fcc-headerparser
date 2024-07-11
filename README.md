# Node.js Express API Project

This project sets up a basic Node.js server using Express to create an API endpoint at `/api/whoami` that returns information about the client's IP address, preferred language, and user-agent (software).

## Prerequisites

Before running the project locally, ensure you have the following installed:
- Node.js
- npm (Node Package Manager)
  
## Tasks completed

- A request to /api/whoami should return a JSON object with your IP address in the ipaddress key.
- A request to /api/whoami should return a JSON object with your preferred language in the language key.
- A request to /api/whoami should return a JSON object with your software in the software key.

## API Endpoints
Request to `GET /api/whoami`
Return a JSON object with the following information:

- ipaddress: The IP address of the client making the request.
- language: The preferred language of the client's browser based on the accept-language header.
- software: The user-agent string of the client's browser/device based on the user-agent header.

## Output Example

```
{
  "ipaddress":"::ffff:192.168.188.74",  
  "language":"de-DE,de;q=0.9,en-US;q=0.8,en;q=0.7",  
  "software":"Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/126.0.0.0 Safari/537.36"  
}
```
