# RAG Application

This app uses a Retrieval-Augmented Generation (RAG) system AI chatbot to provide trained LLM answer based on podcast transript PDFs.

### Features:
- RAG system
- Loads PDF data
- Generates vector embeddings
- Storing embeddings and data in a database
- Database updates

### Backend Stack:
- Next.js
- Python
- FastAPI
- Docker
- AWS (Bedrock, API Gateway, S3, EC2, Lambda, DynamoDB, CloudFormation & CloudWatch)

### Frontend Stack:
- Next.js
- TailwindCSS
- Shadcn-UI

### Setup Steps
Please see the [rag-app-backend](./rag-app-backend) folder and [rag-app-frontend](./rag-app-frontend) folder for an in-depth review of the build steps for each part.

### Production
- AWS Hosted Zones (Route 53 & Amplify)
