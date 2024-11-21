# ReqSync

## ReqSync is a platform designed to transform your inputs—text, voice, and documents—into actionable business requirements through powerful analysis, risk assessment, and entity identification. Built to streamline project planning and decision-making, ReqSync leverages state-of-the-art AI technologies.

## Features

	•	Multi-Input Processing: Handle text, voice recordings, and documents seamlessly.
	•	Advanced Analysis: Perform sentiment analysis, risk assessment, and entity extraction.
	•	Business Requirement Generation: Convert inputs into structured, actionable requirements.
	•	AI-Powered: Powered by OpenAI services, including ChatGPT, Whisper, and Vision.
	•	Export Options: Share results easily with exportable formats like JSON and PDF.

## Tech Stack

	•	Frontend: Next.js
	•	API Framework: Hono using Next.js routes
	•	Database: Drizzle with libSQL
	•	Authentication: Clerk
	•	AI Services: OpenAI API (ChatGPT, Whisper, Vision)
	•	Documentation: VitePress

## Development Workflow

	1.	Documentation: Built with VitePress.
	2.	Testing:
	•	Unit testing with Vitest.
	•	End-to-end testing with Playwright.
	3.	Database Setup: Drizzle ORM with libSQL.
	4.	API Development: Modular and scalable endpoints using Hono.
	5.	Frontend: User-friendly interface with Next.js.

## Getting Started

### Prerequisites

	•	Node.js (v18 or higher recommended)
	•	npm or Bun as the package manager

### Installation

	1.	Clone the repository:

git clone https://github.com/your-username/reqsync.git


	2.	Navigate to the project directory:

cd reqsync


	3.	Install dependencies:

npm install



### Running Locally

	1.	Start the development server:

npm run dev


	2.	Open your browser at http://localhost:3000.

### Testing

	•	Run unit tests:

npm run test


	•	Run end-to-end tests:

npm run e2e



## Roadmap

	1.	Documentation with VitePress.
	2.	Basic API setup for text, voice, and document processing.
	3.	Database integration for input and output management.
	4.	Frontend design and integration.
	5.	Additional features for export and visualization.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

## License

ReqSync is licensed under the AGPL v3. See the LICENSE file for more information.

