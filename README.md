
# Professional Certifications Showcase

## Overview

This project is a dynamic, interactive web application designed to showcase professional certifications. Built with React and Next.js, it features a responsive grid layout of certification cards, each expandable for detailed information. The application utilizes modern web technologies to create a smooth, engaging user experience.

## Live Demo

Check out the live demo of the Professional Certifications Showcase: [Live Demo](https://mycertificate-five.vercel.app/)

## Features

- Responsive grid layout of certification cards
- Interactive card expansion for detailed views
- Image zoom functionality for certificate inspection
- Smooth animations and transitions using Framer Motion
- Mobile-friendly design

## Technologies Used

- React
- Next.js
- TypeScript
- Tailwind CSS
- Framer Motion
- Lucide React (for icons)

## Getting Started

### Prerequisites

- Node.js (v14 or later)
- npm or yarn

### Installation

1. Clone the repository:
   ```
   git clone https://github.com/your-username/professional-certifications-showcase.git
   ```

2. Navigate to the project directory:
   ```
   cd professional-certifications-showcase
   ```

3. Install dependencies:
   ```
   npm install
   # or
   yarn install
   ```

4. Start the development server:
   ```
   npm run dev
   # or
   yarn dev
   ```

5. Open [http://localhost:3000](http://localhost:3000) in your browser to view the application.

## Usage

- The main page displays a grid of certification cards.
- Click on a card to view detailed information about the certification.
- In the detailed view, you can:
  - Read about what was learned in the certification
  - Zoom in/out of the certificate image
  - Return to the main grid view

## Customization

To add or modify certifications, edit the `certificates` array in the main component file. Each certificate object should include:

- `id`: A unique identifier
- `title`: The name of the certification
- `issuer`: The organization that issued the certification
- `date`: The date the certification was obtained
- `imageUrl`: A link to the certificate image
- `learnings`: A description of the skills or knowledge gained

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
