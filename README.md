# Kurikulum Laravel Backend

## Modul 1: Dasar-dasar Laravel
- Pengenalan Laravel dan PHP modern
- Instalasi Laravel dan persiapan lingkungan pengembangan 
- MVC Pattern dan struktur folder Laravel
- Artisan CLI, konfigurasi dan file .env
- Routing dasar dan controller
- Blade templating dan view

## Modul 2: Database dan Query Builder (Diperdalam)
- Konfigurasi koneksi database di Laravel
- Struktur migrasi dan skema database
- **Query Builder dasar: select, where, orderBy**
- **Query Builder lanjutan: join, union, subqueries**
- **Raw queries dan expressions**
- **Transactions dalam Query Builder**
- **Performance tuning untuk Query Builder**
- Implementasi Database Seeder dan Factory

## Modul 3: Eloquent ORM dan Perbandingan dengan Query Builder
- Eloquent Model dasar
- Relasi antar model (one-to-one, one-to-many, many-to-many)
- **Kasus penggunaan Query Builder vs Eloquent ORM**
- **Menggunakan Query Builder di dalam Model**
- **Hybrid approach: menggabungkan Eloquent dan Query Builder**
- Eloquent Collections dan manipulasi data

## Modul 4: Middleware dan Request Lifecycle
- **Konsep Middleware dalam Laravel**
- **Request Lifecycle di Laravel**
- **Membuat Global Middleware**
- **Membuat Route Middleware**
- **Middleware Groups dan prioritas eksekusi**
- **Implementasi use-case umum Middleware:**
  - **Authentication Middleware**
  - **CORS Middleware**
  - **Rate Limiting Middleware**
  - **Request Logging Middleware**
  - **API Versioning Middleware**
- **Menerapkan Middleware pada Controller dan Route Groups**
- **Custom Response Middleware**

## Modul 5: API Development
- RESTful API concepts
- Route API dan Route Resource
- API Controller
- **Mengoptimalkan query database untuk API**
- **Integrasi Middleware dengan API routes**
- Response format (JSON)
- API authentication dengan Laravel Sanctum/Passport
- API versioning

## Modul 6: Repository Pattern dengan Query Builder
- Konsep Repository Pattern
- Interface dan implementasi repository
- **Implementasi Query Builder di dalam Repository**
- **Abstraksi SQL kompleks dalam Repository**
- Dependency Injection pada Laravel
- Membuat BaseRepository generik dengan Query Builder
- Unit testing repository dengan database mock

## Modul 7: Service Pattern
- Konsep Service Pattern dan business logic
- Implementasi Service Layer
- Integrasi Service dengan Repository
- **Data transformation dan mapping**
- Dependency Injection untuk Service
- Unit testing service

## Modul 8: Repository-Service Pattern Integration
- Arsitektur aplikasi dengan Repository-Service Pattern
- Controller dengan Service Injection
- Separation of Concerns
- **Database optimization dalam arsitektur Repository-Service**
- **Integrasi Middleware dengan Repository-Service Pattern**
- Best practice implementasi Repository-Service
- Contoh kasus kompleks dengan Repository-Service Pattern

## Modul 9: Advanced Database Topics
- **Query optimization dan profiling**
- **Database indexing strategy**
- **Pagination dan infinite scrolling dengan Query Builder**
- **Soft deletes dan data archiving**
- **Multi-database dan database sharding**
- **Database migrations strategy untuk production**

## Modul 10: Advanced Middleware and Application Security
- **Custom Request Validation Middleware**
- **Content Negotiation Middleware**
- **API Throttling dan Rate Limiting Advanced**
- **JWT Authentication Middleware Implementation**
- **Request dan Response Transformasi Middleware**
- **Middleware untuk monitoring dan logging**
- **Security Middleware (XSS Protection, CSRF, etc.)**

## Modul 11: Project Praktis
- Implementasi CRUD API lengkap dengan Repository-Service Pattern
- **Implementasi Query Builder complex untuk reporting**
- **Middleware pipeline optimization**
- Authentication dan Authorization
- Error handling dan validasi
- Logging dan monitoring database queries
- Deployment best practices

## Proyek Akhir
- Pengembangan aplikasi backend skala besar dengan arsitektur lengkap
- Implementasi semua konsep yang telah dipelajari
- Performance tuning dan code review
- Optimasi query database dan middleware pipeline
