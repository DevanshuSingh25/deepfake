# DeepfakeGuard - Voice Detection & Watermarking Platform

A real-time deepfake voice detection and watermarking platform that allows users to analyze audio files or live streams to detect AI-generated voices and track manipulated recordings.

## Features

- **Deepfake Detection**: Upload audio files to analyze them for signs of AI manipulation
- **Audio Watermarking**: Embed imperceptible watermarks in your audio files to verify authenticity
- **Live Detection**: Real-time analysis of voice streams to detect deepfakes during calls or meetings
- **Reports & History**: View past analysis results and export reports

## Tech Stack

### Frontend
- React with Next.js
- TailwindCSS for styling
- WebRTC API for real-time audio processing

### Backend
- Next.js API Routes
- TensorFlow.js for client-side ML inference
- Audio processing utilities

## Getting Started

### Prerequisites

- Node.js 18+ and npm

### Installation

1. Clone the repository
```bash
git clone https://github.com/yourusername/deepfake-guard.git
cd deepfake-guard
```

2. Install dependencies
```bash
npm install
```

3. Run the development server
```bash
npm run dev
```

4. Open [http://localhost:3000](http://localhost:3000) in your browser

## Usage

### Deepfake Detection

1. Navigate to the Deepfake Detection page
2. Upload an audio file or record directly through your microphone
3. Click "Analyze Audio" to process the file
4. View the results showing the probability of the audio being real or fake

### Audio Watermarking

1. Navigate to the Watermarking page
2. Upload an audio file
3. Configure watermark settings (type, strength, identifier)
4. Apply the watermark and download the watermarked file
5. Use the verification tab to check if an audio file contains a specific watermark

### Live Detection

1. Navigate to the Live Detection page
2. Grant microphone access
3. Click "Start Detection" to begin analyzing your voice in real-time
4. View the results updating as you speak

## Project Structure

```
deepfake-app/
├── src/
│   ├── app/
│   │   ├── api/                  # API routes
│   │   │   ├── detect/           # Deepfake detection API
│   │   │   └── watermark/        # Audio watermarking API
│   │   ├── components/           # Reusable components
│   │   ├── features/             # Feature-specific components
│   │   ├── utils/                # Utility functions
│   │   ├── deepfake-detection/   # Deepfake detection page
│   │   ├── watermarking/         # Watermarking page
│   │   ├── live-detection/       # Live detection page
│   │   ├── reports/              # Reports page
│   │   ├── authentication/       # Authentication page
│   │   ├── layout.tsx            # Root layout
│   │   └── page.tsx              # Homepage
│   └── ...
├── public/                       # Static assets
└── ...
```

## Future Enhancements

- Integration with more sophisticated ML models for higher accuracy
- Support for more audio formats and longer files
- User authentication and saved profiles
- API access for third-party applications
- Mobile application support

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- [TensorFlow.js](https://www.tensorflow.org/js) for browser-based ML
- [Next.js](https://nextjs.org/) for the React framework
- [TailwindCSS](https://tailwindcss.com/) for styling
"# deepfake" 
