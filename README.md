# ✨ Full-Stack Portfolio Samples
<p align="right"><a href="#hu">Magyarul alább olvasható ⬇️</a></p>

Welcome 👋—this repo bundles **five fully runnable reference projects** that demonstrate my range across **PHP (OOP), React, Spring Boot and .NET 8**.  
Each folder is tracked as a **Git subtree**, so you can explore them independently while cloning the whole portfolio with one command.

| Project | Primary Tech | Elevator Pitch | Badge |
|---------|--------------|----------------|-------|
| **php-slim-skeleton/** | PHP 8 · Slim 4 | PSR-7/15 REST micro-service with JWT auth & PHPUnit tests | ![PHP](https://img.shields.io/badge/php-8.x-777?logo=php&logoColor=white) |
| **php-laravel-blog/**  | PHP 8 · Laravel 11 | CRUD blog with queued email notifications & S3 image uploads | ![Laravel](https://img.shields.io/badge/laravel-11.x-red?logo=laravel) |
| **react-todo/**        | React 18 · TypeScript | SPA Todo list with Context + Reducer state, RTL tests & CI | ![React](https://img.shields.io/badge/react-18.x-61dafb?logo=react&logoColor=black) |
| **springboot-petclinic/** | Java 17 · Spring Boot 3 | Layered veterinary clinic app; Dockerised Postgres & OpenAPI docs | ![Spring Boot](https://img.shields.io/badge/spring--boot-3.x-6db33f?logo=spring&logoColor=white) |
| **dotnet-todo-api/**   | .NET 8 · Blazor WASM | Minimal API + EF Core back-end with Blazor front-end; Swagger & xUnit | ![.NET](https://img.shields.io/badge/.NET-8.0-512BD4?logo=dotnet&logoColor=white) |

> **💡 Why these?**  
> Together they highlight clean OOP design, modern front-end patterns, cloud-ready Java & .NET APIs, and CI/CD fundamentals.

---

## 🏃‍♂️ Quick Start

| Stack | One-liner |
|-------|-----------|
| Slim 4      | `docker compose --profile slim up` |
| Laravel     | `docker compose --profile laravel up` |
| React       | `docker compose --profile react up` |
| Spring Boot | `./mvnw -f springboot-petclinic spring-boot:run` |
| .NET        | `dotnet run --project dotnet-todo-api/Todo.Api` |

> **Prerequisites:** Docker ≥ 24, Node 18 LTS, Java 17, .NET 8 SDK, PHP 8.3 + Composer.

---

## 🧭 Repo Map
    .
    ├── php-slim-skeleton/      # PSR-15 middleware micro-service
    ├── php-laravel-blog/       # Laravel MVC blog
    ├── react-todo/             # TypeScript React SPA
    ├── springboot-petclinic/   # Spring Boot sample app
    └── dotnet-todo-api/        # .NET 8 minimal API + Blazor front-end

Each project contains its **own README** with deeper docs, screenshots and test commands.

---

## 🔍 What to look at

| Skill | File / Concept |
|-------|----------------|
| **Clean Architecture (PHP)** | `php-slim-skeleton/src/Domain` — entities & repositories |
| **Queue vs Sync (Laravel)** | `php-laravel-blog/app/Jobs` |
| **Typed Front-End** | `react-todo/src/types.ts` |
| **Profile-based Config** | `springboot-petclinic/src/main/resources/application-*.yaml` |
| **Minimal APIs** | `dotnet-todo-api/Todo.Api/Program.cs` |

---

## 🤝 Feedback

Spotted an issue or have a question?  
Open an issue or reach me on [LinkedIn](https://www.linkedin.com/in/your-profile).

---

## 📜 Licences

Each sub-folder retains its original open-source licence; see individual `LICENSE` files.  
My additions are released under MIT unless stated otherwise.

<p align="center"><b>Thanks for stopping by — enjoy the code!</b></p>


 <a id="hu"></a>
 
## 🇭🇺 Magyar verzió

Üdv 👋—ez a repó **öt teljesen futtatható mintaprojektet** tartalmaz, amelyek bemutatják a tapasztalataimat **PHP (OOP), React, Spring Boot és .NET 8** területeken.  
Minden mappa **Git subtree**-ként szerepel, így a portfólió egyetlen klónozással letölthető, de a projektek külön is frissíthetők.

| Projekt | Fő technológia | Gyors bemutató | Jelvény |
|---------|----------------|----------------|---------|
| **php-slim-skeleton/** | PHP 8 · Slim 4 | PSR-7/15 alapú REST mikroszolgáltatás JWT hitelesítéssel és PHPUnit tesztekkel | ![PHP](https://img.shields.io/badge/php-8.x-777?logo=php&logoColor=white) |
| **php-laravel-blog/**  | PHP 8 · Laravel 11 | CRUD blog, sor-alapú email értesítésekkel és S3 képfeltöltéssel | ![Laravel](https://img.shields.io/badge/laravel-11.x-red?logo=laravel) |
| **react-todo/**        | React 18 · TypeScript | SPA Todo lista Context + Reducer állapottal, RTL tesztekkel és CI-val | ![React](https://img.shields.io/badge/react-18.x-61dafb?logo=react&logoColor=black) |
| **springboot-petclinic/** | Java 17 · Spring Boot 3 | Rétegzett állatorvosi klinika app; Dockeres Postgres és OpenAPI dokumentáció | ![Spring Boot](https://img.shields.io/badge/spring--boot-3.x-6db33f?logo=spring&logoColor=white) |
| **dotnet-todo-api/**   | .NET 8 · Blazor WASM | Minimal API + EF Core háttér, Blazor front-enddel; Swagger és xUnit | ![.NET](https://img.shields.io/badge/.NET-8.0-512BD4?logo=dotnet&logoColor=white) |

> **💡 Miért pont ezek?**  
> Együttesen mutatják be a tiszta OOP tervezést, a modern front-end mintákat, a felhőre kész Java és .NET API-kat, valamint a CI/CD alapokat.

---

### 🏃‍♂️ Gyors indítás

| Stack | Egy soros parancs |
|-------|-------------------|
| Slim 4      | `docker compose --profile slim up` |
| Laravel     | `docker compose --profile laravel up` |
| React       | `docker compose --profile react up` |
| Spring Boot | `./mvnw -f springboot-petclinic spring-boot:run` |
| .NET        | `dotnet run --project dotnet-todo-api/Todo.Api` |

> **Előfeltételek:** Docker ≥ 24, Node 18 LTS, Java 17, .NET 8 SDK, PHP 8.3 + Composer.

---

### 🧭 Mappastruktúra
    .
    ├── php-slim-skeleton/      # PSR-15 middleware mikroszerviz
    ├── php-laravel-blog/       # Laravel MVC blog
    ├── react-todo/             # TypeScript React SPA
    ├── springboot-petclinic/   # Spring Boot mintaalkalmazás
    └── dotnet-todo-api/        # .NET 8 minimal API + Blazor felület

---

### 🔍 Érdemes belenézni

| Képesség | Fájl / Koncepció |
|----------|------------------|
| **Tiszta architektúra (PHP)** | `php-slim-skeleton/src/Domain` — entitások és repository-k |
| **Queue vs szinkron (Laravel)** | `php-laravel-blog/app/Jobs` |
| **Típusos front-end** | `react-todo/src/types.ts` |
| **Profil-alapú konfiguráció** | `springboot-petclinic/src/main/resources/application-*.yaml` |
| **Minimal API-k** | `dotnet-todo-api/Todo.Api/Program.cs` |

---

### 🤝 Visszajelzés

Hibát találtál vagy kérdésed van?  
Nyiss egy *issue-t* vagy keress [LinkedInen](https://www.linkedin.com/in/your-profile).

---

### 📜 Licencek

Minden almappa megtartja az eredeti nyílt forráskódú licencét; lásd az egyes `LICENSE` fájlokat.  
A saját kiegészítéseim MIT licenc alatt érhetők el, hacsak másként nem jelzem.

<p align="center"><b>Köszönöm, hogy benéztél — jó kódolást!</b></p>
