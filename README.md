# Celebrity Lookalike AI

An AI-powered web application that analyzes uploaded photos and identifies which celebrity the person most closely resembles. Built with React, Node.js, and Deep Infra's Vision AI.

## Features

- Upload and analyze photos
- AI-powered celebrity lookalike detection
- Responsive design
- Image compression for optimal performance

## Tech Stack

- **Frontend**: React + Vite
- **Backend**: Node.js + Express
- **AI**: Deep Infra Vision API

## Getting Started

### Prerequisites

- Node.js 18 or higher
- Deep Infra API key

### Installation

1. Clone the repository:
```bash
git clone https://github.com/nodcn13/Lookalike-AI.git
```
2. Navigate to the project directory:
```bash
cd Lookalike-AI
```
3. Install dependencies for both the frontend and backend:
```bash
cd server && npm install && cd ../client && npm install
```
4. Set up your Deep Infra API key in the `.env` file in the `server` directory. Make sure your model can take images as input. Make sure endpont ends with /chat/completions.
```bash
    API_KEY=your_api_key_here
    API_URL=OpenAI_Chat_completions_compatible_endpoint
    VISION_MODEL=your_model_here
    PORT=5001
``` 

5. Start the development server on port 5001:
```bash
    cd server && node server.js
```
6. Start the client on port 5173:
```bash
    cd client && npm run dev
```
  
