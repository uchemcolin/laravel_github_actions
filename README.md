# Laravel GitHub Actions

A learning-focused repository for experimenting with **GitHub Actions** using **Laravel 12** on **Ubuntu GitHub runners**.

This project explores:

* Laravel CI/CD pipelines
* Automated testing
* Composer dependency installation
* Environment setup
* MySQL services in workflows
* Code quality checks
* Deployment automation
* GitHub Actions best practices

---

## Tech Stack

* PHP 8.3+
* Laravel 12
* GitHub Actions
* Ubuntu Latest Runner
* Composer
* MySQL
* PHPUnit

---

## Goals

The purpose of this repository is to learn and practice:

* Creating GitHub Actions workflows
* Running Laravel tests automatically
* Setting up CI pipelines
* Understanding workflow jobs and steps
* Using environment variables and secrets
* Automating deployments

---

## Project Setup

Clone the repository:

```bash
git clone https://github.com/your-username/laravel_github_actions.git
```

Move into the project directory:

```bash
cd laravel_github_actions
```

Install dependencies:

```bash
composer install
```

Copy environment file:

```bash
cp .env.example .env
```

Generate application key:

```bash
php artisan key:generate
```

Run migrations:

```bash
php artisan migrate
```

Start development server:

```bash
php artisan serve
```

---

## GitHub Actions

This repository includes GitHub Actions workflows for:

* Installing dependencies
* Running PHPUnit tests
* Validating Laravel setup
* CI automation on push and pull requests

Workflow files are located in:

```bash
.github/workflows/
```

---

## Example Workflow Features

* Ubuntu runners
* PHP setup
* Composer caching
* MySQL service containers
* Laravel environment preparation
* Automated test execution

---

## Learning Notes

This repository is intended for educational purposes while learning:

* CI/CD concepts
* GitHub workflow syntax
* Laravel automation
* DevOps basics

---

## License

This project is open-source and available under the MIT License.
