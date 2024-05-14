<p align="center"><a href="https://inertiajs.com" target="_blank"><img src="https://github.com/inertiajs/.github/blob/master/LOGO.png" alt="Inertia Logo"></a></p>

<p align="center">
  <a href="https://github.com/inertiajs/inertia-laravel/releases">
    <img src="https://img.shields.io/github/release/inertiajs/inertia-laravel.svg?style=flat-square" alt="Latest Version">
  </a>
  <a href="https://github.com/inertiajs/inertia-laravel/actions/workflows/tests.yml?query=workflow%3Atests+branch%3Amaster">
    <img src="https://github.com/inertiajs/inertia-laravel/actions/workflows/tests.yml/badge.svg?branch=master" alt="Build Status">
  </a>
  <a href="https://packagist.org/packages/inertiajs/inertia-laravel">
    <img src="https://img.shields.io/packagist/dt/inertiajs/inertia-laravel.svg?style=flat-square" alt="Total Downloads">
  </a>
</p>

## About InertiaJS

Inertia is a new approach to building classic server-driven web apps. We call it the modern monolith.

Inertia allows you to create fully client-side rendered, single-page apps, without the complexity that comes with modern SPAs. It does this by leveraging existing server-side patterns that you already love.

Inertia has no client-side routing, nor does it require an API. Simply build controllers and page views like you've always done! Inertia works great with any backend framework, but it's fine-tuned for Laravel.

## Learning Laravel Inertia React (client-side)

Once you have your server-side framework configured, you then need to setup your client-side framework. Inertia currently provides support for React, Vue, and Svelte.

You can see the Laravel Inertia tutorial on the <a href="https://www.inertiajs.com">official Inertiajs website</a> and also via video on <a href="https://www.youtube.com/watch?v=HkCQVhWtexQ&list=PLxzARwISlmzgO74VI9Yva7sxbUhJJ56yW&ab_channel=WEBDEVIndo">YouTube</a>.

### Premium Partners

- **[Vehikl](https://vehikl.com/)**
- **[Tighten Co.](https://tighten.co)**
- **[WebReinvent](https://webreinvent.com/)**
- **[Kirschbaum Development Group](https://kirschbaumdevelopment.com)**
- **[64 Robots](https://64robots.com)**
- **[Curotec](https://www.curotec.com/services/technologies/laravel/)**
- **[Cyber-Duck](https://cyber-duck.co.uk)**
- **[DevSquad](https://devsquad.com/hire-laravel-developers)**
- **[Jump24](https://jump24.co.uk)**
- **[Redberry](https://redberry.international/laravel/)**
- **[Active Logic](https://activelogic.com)**
- **[byte5](https://byte5.de)**
- **[OP.GG](https://op.gg)**

# Requirement

-   PHP `>= v8.2`
-   Composer `>= v2.x`
-   Node.js `>= v16.x`
-   PostgreSQL `v14.x`

## Development

1 - Clone the project

```bash
git clone https://github.com/Mmtza/inertia-portofolio.git
```

2 - Go to the project directory

```bash
cd inertia-portofolio
```

3 - Install dependencies (NPM recommended)

```bash
composer install
npm install
```

4 - Copy .env file

```bash
cp .env.example .env
```

5 - Generate Artisan Key

```bash
php artisan key:generate
```

6 - Create Database & Run Migration ( create db `my_porto` firstly )

```bash
php artisan migrate --seed
```

7 - Start Dev

```bash
php artisan serve
npm run dev
```

## Security Vulnerabilities

If you discover a security vulnerability within Laravel, please send an e-mail to Taylor Otwell via [taylor@laravel.com](mailto:taylor@laravel.com). All security vulnerabilities will be promptly addressed.

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
