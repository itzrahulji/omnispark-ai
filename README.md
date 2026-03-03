# OmniSpark AI

OmniSpark AI is a modular, AI-powered SaaS web application designed to provide a seamless and intelligent user experience. It integrates advanced AI models for chat, image generation, video processing, voice interaction, and real-time intelligence, leveraging the power of Gemini, Veo, and Nano Banana models.

## Tech Stack

- **Frontend**: Next.js, React, Tailwind CSS
- **Backend**: Node.js, Firebase (Authentication, Firestore, Storage)
- **AI Models**: Gemini (Text/Multimodal), Veo (Video), Nano Banana (Image/Artistic)
- **Deployment**: Vercel
- **State Management**: React Hooks, Context API
- **API**: RESTful API, Serverless Functions

## Feature List

- **Intelligent Chat**: Real-time conversational AI with streaming support.
- **Image Generation**: High-quality image creation using Nano Banana models.
- **Video Processing**: Advanced video generation and analysis with Veo.
- **Voice Interaction**: Speech-to-text and text-to-speech capabilities.
- **Real-time Intelligence**: Dynamic insights and data processing.
- **User Authentication**: Secure login and profile management via Firebase.
- **Modular Architecture**: Easily extensible folder structure for scalable development.

## Setup Instructions

1.  **Clone the repository**:
    ```bash
    git clone https://github.com/itzrahulji/omnispark-ai.git
    cd omnispark-ai
    ```

2.  **Install dependencies**:
    ```bash
    npm install
    ```

3.  **Configure environment variables**:
    Create a `.env.local` file in the root directory and add the required variables (see template below).

4.  **Run the development server**:
    ```bash
    npm run dev
    ```

## Environment Variables Template

```env
# Firebase Configuration
NEXT_PUBLIC_FIREBASE_API_KEY=your_api_key
NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=your_auth_domain
NEXT_PUBLIC_FIREBASE_PROJECT_ID=your_project_id
NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET=your_storage_bucket
NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID=your_sender_id
NEXT_PUBLIC_FIREBASE_APP_ID=your_app_id

# AI Model API Keys
GEMINI_API_KEY=your_gemini_api_key
VEO_API_KEY=your_veo_api_key
NANO_BANANA_API_KEY=your_nano_banana_api_key

# Other Configuration
NEXT_PUBLIC_BASE_URL=http://localhost:3000
```

## Deployment Instructions (Vercel)

1.  **Push your changes** to the GitHub repository.
2.  **Connect your repository** to Vercel.
3.  **Configure the environment variables** in the Vercel dashboard.
4.  **Deploy** the application. Vercel will automatically build and deploy your project on every push to the main branch.

## License

This project is licensed under the [MIT License](LICENSE).
