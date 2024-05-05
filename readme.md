
# Building a Full-stack TypeScript Application with Turborepo

## Project Overview

This project demonstrates the development of a full-stack TypeScript application using Turborepo. It includes a backend API, frontend web application, and shared TypeScript types managed within a monorepo structure.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/MehdiBukhari/full-stack-typescript-with-turborepo-demo.git
   ```

2. Navigate to the project directory:
   ```bash
   cd full-stack-typescript-with-turborepo-demo
   ```

3. Install dependencies:
   ```bash
   pnpm install
   ```

## Usage

### Development

Start the development servers for both the backend API and frontend web application simultaneously:
```bash
pnpm dev
```

Start only the backend API development server:
```bash
pnpm dev:api
```

Start only the frontend web application development server:
```bash
pnpm dev:web
```

### Type Checking

Perform TypeScript type checking across the entire project:
```bash
pnpm type-check
```

### Building

Build the project:
```bash
pnpm build
```

## Project Structure

- **api**: Contains the backend API implementation.
- **web**: Contains the frontend web application.
- **types**: Contains shared TypeScript types used by both the API and web packages.

## Contributing

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-name`).
3. Make your changes and commit them (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature-name`).
5. Create a new Pull Request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- **Turborepo**: Thank you to the creators of Turborepo for providing an excellent monorepo management tool.
- **Contributors**: Special thanks to all contributors who have helped improve this project.
``` 

This is a basic structure; you can customize it further to fit your project's specific details.