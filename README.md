Next.js Project Setup
This is a Next.js project bootstrapped with create-next-app.

Getting Started
First, run the development server:

npm run dev
# or
yarn dev

Open http://localhost:3000 with your browser to see the result.

You can start editing the page by modifying pages/index.js. The page auto-updates as you edit the file.

Environment Setup
Create a .env.local file in the root of your project and add the following environment variables:

NEXT_PUBLIC_MAPBOX_ACCESS_TOKEN=your_mapbox_access_token_here
SANITY_PROJECT_ID=your_sanity_project_id_here
SANITY_TOKEN=your_sanity_token_here
MAPBOX_PLACES_API_URL=your_mapbox_places_api_url_here
MAPBOX_DIRECTIONS_API_URL=your_mapbox_directions_api_url_here
NEXT_PUBLIC_UBER_ADDRESS=your_uber_address_here

Replace the placeholders with your actual API keys and project IDs.

Sanity Server
To set up your Sanity server and add car images from assets, follow these steps:

Navigate to your Sanity project directory.
Run the following command to start the Sanity server:
sanity start

Add your car images to the Sanity assets.
Make sure to replace the placeholders with your actual values. Also, ensure that your .env.local file is included in your .gitignore to prevent sensitive information from being pushed to version control.
