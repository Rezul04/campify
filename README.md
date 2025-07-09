# Campify - Next.js Campground Application

A modern, full-stack campground sharing application built with Next.js, TypeScript, and MongoDB.

## Features

- 🏕️ Browse and discover campgrounds
- 📍 Interactive maps with Mapbox integration
- 🖼️ Image upload with Cloudinary
- ⭐ Review and rating system
- 🔐 User authentication and authorization
- 📱 Responsive design with Tailwind CSS
- 🚀 Optimized for Vercel deployment

## Tech Stack

- **Frontend**: Next.js 14, React, TypeScript, Tailwind CSS
- **Backend**: Next.js API Routes
- **Database**: MongoDB with Mongoose
- **Authentication**: JWT with HTTP-only cookies
- **File Upload**: Cloudinary
- **Maps**: Mapbox GL JS
- **Deployment**: Vercel

## Getting Started

### Prerequisites

- Node.js 18+ 
- MongoDB database
- Cloudinary account
- Mapbox account

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd campground-nextjs
```

2. Install dependencies:
```bash
npm install
```

3. Set up environment variables:
Create a `.env.local` file in the root directory and add:

```env
MONGODB_URI=your_mongodb_connection_string
NEXTAUTH_SECRET=your_nextauth_secret
CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret
NEXT_PUBLIC_MAPBOX_TOKEN=your_mapbox_token
JWT_SECRET=your_jwt_secret
```

4. Run the development server:
```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) to view the application.
