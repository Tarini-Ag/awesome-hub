<div align="center">
  <h1>AwesomeHub</h1>
  <p>A modern, searchable hub for all "Awesome XYZ" lists on GitHub</p>
  
[![Hacktoberfest](https://img.shields.io/badge/Hacktoberfest-2025-orange?style=for-the-badge)](https://hacktoberfest.digitalocean.com/)

</div>

## About

AwesomeHub is a centralized platform that aggregates, categorizes, and makes discoverable all the amazing "Awesome" lists scattered across GitHub. From `awesome-react` to `awesome-machine-learning`, we bring together the best curated resources for developers, designers, and tech enthusiasts.

### Features

- **Smart Search**: Find repositories by name, description, topics, or programming language
- **Real-time Stats**: Live metrics on repositories, stars, and contributors
- **Smart Categorization**: Automatic categorization and tagging of repositories
- **Trending**: Discover trending and newly added awesome lists

## Visual Tour

<img width="1902" height="990" alt="image" src="./assets/images/homepage.jpg" />

## Quick Start

### Prerequisites

- Node.js 18+ and npm
- Git
- GitHub Personal Access Token (optional, for higher rate limits)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/awesome-hub.git
   cd awesome-hub
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up environment variables (optional)**
   ```env
   # Edit `.env` and add your GitHub token for higher rate limits:
   GITHUB_TOKEN=your_github_personal_access_token_here
   ```

4. **Start the development server**
    ```bash   
    npm run dev
    ```

**Note**: The application works without a GitHub token but will have lower rate limits. Adding a token is recommended for development.

## Tech Stack

- **Frontend**: Next.js 14, React, TypeScript
- **Styling**: Tailwind CSS, Shadcn UI
- **Data**: GitHub GraphQL API
- **Deployment**: Vercel

## Contributing

We welcome contributions! Please see our [Contributing Guide](CONTRIBUTING.md) for details.

### How to Contribute

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Inspired by the amazing [Awesome](https://github.com/sindresorhus/awesome) lists community
- Built with ❤️ by the open source community
