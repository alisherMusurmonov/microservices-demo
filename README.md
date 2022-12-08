# API gateway pattern - Microservice Architecture

The application has 3 backend services with their own database
- Users services - running on [http://localhost:5000](http://localhost:5000)
- Documents services - running on [http://localhost:5001](http://localhost:5001)
- API Gateway - running on [http://localhost:5002](http://localhost:5002)

## Installation

In a real world, this services could be hosted from independent servers. But for testing purpose I have merged all of them into one file for up and running quickly. Main purpose of this demo to show how to use implement API gateway pattern and made it very simple as possible.

In order to start application locally rub below command and it will get lates changes from GitHub repositories and starts services.

```bash
yarn dev
```

## Notes

Main purpose of the Gateway is provides single API endpoint for developers and it makes developers lives easier when implementing frontend with backend. 

## Github repos
- Users services repo - [link](https://github.com/alisherMusurmonov/microservices-users)
- Documents services repo - [link](https://github.com/alisherMusurmonov/microservices-documents)
- API Gateway repo - [link](https://github.com/alisherMusurmonov/microservices-gateway)