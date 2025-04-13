# pnpm-angular-nestjs

This is a monorepo project that uses **pnpm** as the package manager. It includes an Angular frontend application and a
NestJS backend application.

## Project Structure

- `apps/angular-app`: Angular frontend application.
- `apps/nest-app`: NestJS backend application.

## Prerequisites

- [Node.js](https://nodejs.org/) (v20 or later recommended)
- [pnpm](https://pnpm.io/) (v10.7.0 or later)

## Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd pnpm-angular-nestjs

## Install dependencies:

```
 pnpm install
```

### Scripts

#### Start Applications

- Start the backend (NestJS):

```
pnpm start:api
```

### Start the frontend (Angular):

```
pnpm start:app
```

### Build Applications

- Build the backend (NestJS):

```
pnpm build:api
```

### Build the frontend (Angular):

```
pnpm build:app
```

### Test Applications

- Test the backend (NestJS):

```
pnpm test:api
```

### Test the frontend (Angular):

```
pnpm test:app
```

### License

This project is licensed under the MIT License.
