# Profile Picture Upload with Minio

## Overview
This project enhances user profile management by allowing users to upload and store their profile pictures using Minio, a scalable distributed object storage system. It integrates robust API endpoints for uploading, storing, and retrieving profile pictures, ensuring a dynamic user experience.

## Features
- **Profile Picture Upload**: Users can upload their profile pictures through a dedicated API endpoint.
- **Secure Storage with Minio**: Uploaded images are stored securely in Minio.
- **Profile Management**: Users can update and retrieve their profile pictures via user profile API endpoints.
- **Image Resizing and Optimization**: Ensures consistent image sizes and faster loading times.
- **Validation**: Restricts the allowed image formats and sizes to maintain consistency.

## Getting Started

### Prerequisites
- Docker
- Python 3.8 or higher
- FastAPI
- nginx

### Installation
Clone the repository to your local machine:
```bash
git clone https://github.com/<your-username>/<repository-name>.git
cd <repository-name>

### Setting Up Minio
docker pull minio/minio
docker run -p 9000:9000 minio/minio server /data
