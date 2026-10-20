# Install a AllyMailer SDK or framework package

Every package reads the API key from `ALLYMAILER_API_KEY` and has an `AGENTS.md` with the integration rules. Prefer the framework package when the project uses that framework: it brings the SDK, configuration, the mailer and the webhook endpoint. Two lines of a language (PHP 8.1 / 7.2, Node.js 18 / 14, Java 11 / 8, .NET 8 / Standard 2.0) are two major versions of one package: the package manager picks the line of the runtime.

## SDKs

### PHP — PHP 8.1+

```bash
composer require allymailer/allymailer-sdk
```

[github.com/allymailer/allymailer-php-sdk](https://github.com/allymailer/allymailer-php-sdk), [AGENTS.md](https://github.com/allymailer/allymailer-php-sdk/blob/HEAD/AGENTS.md)

### PHP — PHP 7.2+

```bash
composer require allymailer/allymailer-sdk
```

[github.com/allymailer/allymailer-php-sdk](https://github.com/allymailer/allymailer-php-sdk), [AGENTS.md](https://github.com/allymailer/allymailer-php-sdk/blob/HEAD/AGENTS.md)

### Python — Python 3.8+

```bash
pip install allymailer-python-sdk
```

[github.com/allymailer/allymailer-python-sdk](https://github.com/allymailer/allymailer-python-sdk), [AGENTS.md](https://github.com/allymailer/allymailer-python-sdk/blob/HEAD/AGENTS.md)

### Node.js — Node.js 18+

```bash
npm install @allymailer/allymailer-node-sdk
```

[github.com/allymailer/allymailer-node-sdk](https://github.com/allymailer/allymailer-node-sdk), [AGENTS.md](https://github.com/allymailer/allymailer-node-sdk/blob/HEAD/AGENTS.md)

### Node.js — Node.js 14+

```bash
npm install @allymailer/allymailer-node-sdk
```

[github.com/allymailer/allymailer-node-sdk](https://github.com/allymailer/allymailer-node-sdk), [AGENTS.md](https://github.com/allymailer/allymailer-node-sdk/blob/HEAD/AGENTS.md)

### Ruby — Ruby 2.7+

```bash
gem install allymailer-ruby-sdk
```

[github.com/allymailer/allymailer-ruby-sdk](https://github.com/allymailer/allymailer-ruby-sdk), [AGENTS.md](https://github.com/allymailer/allymailer-ruby-sdk/blob/HEAD/AGENTS.md)

### Go — Go 1.18+

```bash
go get github.com/allymailer/allymailer-go-sdk
```

[github.com/allymailer/allymailer-go-sdk](https://github.com/allymailer/allymailer-go-sdk), [AGENTS.md](https://github.com/allymailer/allymailer-go-sdk/blob/HEAD/AGENTS.md)

### Java — Java 11+

```xml
<dependency>
    <groupId>ua.com.allymailer</groupId>
    <artifactId>java-sdk</artifactId>
    <version>2.0.0</version>
</dependency>
```

[github.com/allymailer/allymailer-java-sdk](https://github.com/allymailer/allymailer-java-sdk), [AGENTS.md](https://github.com/allymailer/allymailer-java-sdk/blob/HEAD/AGENTS.md)

### Java — Java 8+

```xml
<dependency>
    <groupId>ua.com.allymailer</groupId>
    <artifactId>java-sdk</artifactId>
    <version>1.0.0</version>
</dependency>
```

[github.com/allymailer/allymailer-java-sdk](https://github.com/allymailer/allymailer-java-sdk), [AGENTS.md](https://github.com/allymailer/allymailer-java-sdk/blob/HEAD/AGENTS.md)

### .NET (C#) — .NET 8

```bash
dotnet add package AllyMailer.Sdk
```

[github.com/allymailer/allymailer-dotnet-sdk](https://github.com/allymailer/allymailer-dotnet-sdk), [AGENTS.md](https://github.com/allymailer/allymailer-dotnet-sdk/blob/HEAD/AGENTS.md)

### .NET (C#) — .NET Standard 2.0 (.NET Framework 4.6.1+, .NET Core 2.0+)

```bash
dotnet add package AllyMailer.Sdk
```

[github.com/allymailer/allymailer-dotnet-sdk](https://github.com/allymailer/allymailer-dotnet-sdk), [AGENTS.md](https://github.com/allymailer/allymailer-dotnet-sdk/blob/HEAD/AGENTS.md)

### Rust — Rust 1.70+ (edition 2021), async runtime (tokio)

```bash
cargo add allymailer-rust-sdk
cargo add tokio --features macros,rt-multi-thread
```

[github.com/allymailer/allymailer-rust-sdk](https://github.com/allymailer/allymailer-rust-sdk), [AGENTS.md](https://github.com/allymailer/allymailer-rust-sdk/blob/HEAD/AGENTS.md)

## Framework packages

### Laravel — `allymailer/allymailer-laravel`

```bash
composer require allymailer/allymailer-laravel
php artisan vendor:publish --tag=allymailer-config  # config/allymailer.php
```

[github.com/allymailer/allymailer-laravel](https://github.com/allymailer/allymailer-laravel), [AGENTS.md](https://github.com/allymailer/allymailer-laravel/blob/HEAD/AGENTS.md)

### Symfony — `allymailer/allymailer-symfony-bundle`

```bash
composer require allymailer/allymailer-symfony-bundle
```

[github.com/allymailer/allymailer-symfony](https://github.com/allymailer/allymailer-symfony), [AGENTS.md](https://github.com/allymailer/allymailer-symfony/blob/HEAD/AGENTS.md)

### Django — `allymailer-django`

```bash
pip install allymailer-django
```

[github.com/allymailer/allymailer-django](https://github.com/allymailer/allymailer-django), [AGENTS.md](https://github.com/allymailer/allymailer-django/blob/HEAD/AGENTS.md)

### Flask — `allymailer-flask`

```bash
pip install allymailer-flask
```

[github.com/allymailer/allymailer-flask](https://github.com/allymailer/allymailer-flask), [AGENTS.md](https://github.com/allymailer/allymailer-flask/blob/HEAD/AGENTS.md)

### FastAPI — `allymailer-fastapi`

```bash
pip install allymailer-fastapi
```

[github.com/allymailer/allymailer-fastapi](https://github.com/allymailer/allymailer-fastapi), [AGENTS.md](https://github.com/allymailer/allymailer-fastapi/blob/HEAD/AGENTS.md)

### Express — `@allymailer/express`

```bash
npm install @allymailer/express express nodemailer
```

[github.com/allymailer/allymailer-express](https://github.com/allymailer/allymailer-express), [AGENTS.md](https://github.com/allymailer/allymailer-express/blob/HEAD/AGENTS.md)

### NestJS — `@allymailer/nestjs`

```bash
npm install @allymailer/nestjs nodemailer
```

[github.com/allymailer/allymailer-nestjs](https://github.com/allymailer/allymailer-nestjs), [AGENTS.md](https://github.com/allymailer/allymailer-nestjs/blob/HEAD/AGENTS.md)

### Ruby on Rails — `allymailer-rails`

```bash
bundle add allymailer-rails
```

[github.com/allymailer/allymailer-rails](https://github.com/allymailer/allymailer-rails), [AGENTS.md](https://github.com/allymailer/allymailer-rails/blob/HEAD/AGENTS.md)

### Spring Boot — `ua.com.allymailer:allymailer-spring-boot-starter`

```xml
# pom.xml
<dependency>
    <groupId>ua.com.allymailer</groupId>
    <artifactId>allymailer-spring-boot-starter</artifactId>
    <version>2.0.0</version>
</dependency>
```

[github.com/allymailer/allymailer-spring](https://github.com/allymailer/allymailer-spring), [AGENTS.md](https://github.com/allymailer/allymailer-spring/blob/HEAD/AGENTS.md)

### ASP.NET Core — `AllyMailer.AspNetCore`

```bash
dotnet add package AllyMailer.AspNetCore
```

[github.com/allymailer/allymailer-aspnetcore](https://github.com/allymailer/allymailer-aspnetcore), [AGENTS.md](https://github.com/allymailer/allymailer-aspnetcore/blob/HEAD/AGENTS.md)

### Go net/http — `github.com/allymailer/allymailer-nethttp`

```bash
go get github.com/allymailer/allymailer-nethttp
```

[github.com/allymailer/allymailer-nethttp](https://github.com/allymailer/allymailer-nethttp), [AGENTS.md](https://github.com/allymailer/allymailer-nethttp/blob/HEAD/AGENTS.md)

### axum — `allymailer-axum`

```bash
cargo add allymailer-axum allymailer-rust-sdk
```

[github.com/allymailer/allymailer-axum](https://github.com/allymailer/allymailer-axum), [AGENTS.md](https://github.com/allymailer/allymailer-axum/blob/HEAD/AGENTS.md)
