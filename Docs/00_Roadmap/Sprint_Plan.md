# AI Content Generator - Sprint Plan

## Tổng quan

- **Tổng số Sprint**: 24 (Sprint 0 → Sprint 23)
- **Độ dài Sprint**: 1 tuần (trừ Sprint 0: 2 ngày)
- **Phương pháp**: Scrum
- **Tracking**: GitHub Projects / Trello

---

## Sprint 0 — Chuẩn bị (2 ngày)

**Mục tiêu**: Thiết lập môi trường phát triển

| Task | Giờ | Người phụ trách |
|---|---|---|
| Cài đặt Git & tạo GitHub repository | 1 | Dev |
| Cài VS Code + extensions cần thiết | 1 | Dev |
| Cài IntelliJ IDEA Community + SDK | 1 | Dev |
| Cài MySQL/PostgreSQL + DBeaver | 1 | Dev |
| Cài Postman | 0.5 | Dev |
| Cài Docker Desktop | 0.5 | Dev |
| Tạo tài khoản Figma | 0.5 | Dev |
| Kiểm tra toàn bộ môi trường hoạt động | 1 | Dev |

**Deliverables**: Repository GitHub, môi trường dev ready

**Definition of Done**: Tất cả tool đã cài và chạy được, repo có README

---

## Sprint 1 — Software Engineering (1 tuần)

**Mục tiêu**: Hiểu SDLC, Agile, Scrum, viết Roadmap & Sprint Plan

| Task | Giờ |
|---|---|
| Đọc tài liệu SDLC (Atlassian, Microsoft Learn) | 4 |
| Đọc Agile Manifesto + 12 Principles | 2 |
| Đọc Scrum Guide | 3 |
| Tìm hiểu Kanban, Git Flow | 2 |
| Viết ghi chú tổng hợp | 3 |
| Tạo Roadmap.md | 2 |
| Tạo Sprint_Plan.md | 2 |
| Tạo Checklist.md | 1 |
| Review & chỉnh sửa | 1 |

**Deliverables**: Roadmap, Sprint Plan, Checklist, ghi chú SE

**DoD**: Có thể giải thích được SDLC, phân biệt Scrum/Kanban, có đủ 3 tài liệu quản lý dự án

---

## Sprint 2 — Product Discovery (1 tuần)

**Mục tiêu**: Xác định vấn đề, thị trường, mô hình kinh doanh

| Task | Giờ |
|---|---|
| Nghiên cứu thị trường AI content generation | 4 |
| Phân tích đối thủ (Copy.ai, Jasper, Writesonic, ChatGPT) | 4 |
| Viết Vision Document | 3 |
| Phân tích SWOT | 2 |
| Vẽ Lean Canvas | 2 |
| Vẽ Business Model Canvas | 2 |
| Review & chỉnh sửa | 1 |

**Deliverables**: Vision Document, Competitor Analysis, SWOT, Lean Canvas, BMC

**DoD**: 5 tài liệu hoàn chỉnh, hiểu rõ thị trường và positioning

---

## Sprint 3 — Business Analysis (1 tuần)

**Mục tiêu**: Xác định stakeholders, persona, và luồng nghiệp vụ

| Task | Giờ |
|---|---|
| Xác định danh sách stakeholders | 2 |
| Xây dựng 3 personas (Content Creator, Marketer, Business Owner) | 4 |
| Vẽ User Journey Map | 3 |
| Viết 10–15 User Stories theo format chuẩn | 4 |
| Vẽ Use Case Diagram + mô tả chi tiết | 4 |
| Viết BRD (Business Requirement Document) | 3 |

**Deliverables**: Personas, User Journey, User Stories, Use Case, BRD

**DoD**: BRD hoàn chỉnh, tất cả user stories được phê duyệt

---

## Sprint 4 — Requirement Analysis (1 tuần)

**Mục tiêu**: Viết SRS, tạo Product Backlog

| Task | Giờ |
|---|---|
| Liệt kê Functional Requirements | 4 |
| Liệt kê Non-functional Requirements | 3 |
| Xác định Business Rules | 2 |
| Viết Acceptance Criteria (Given/When/Then) cho từng story | 4 |
| Tạo Product Backlog (estimate story points) | 4 |
| Viết SRS (IEEE 830 format) | 5 |

**Deliverables**: SRS, Product Backlog, Acceptance Criteria

**DoD**: SRS hoàn chỉnh, backlog được prioritize với story points

---

## Sprint 5 — UX/UI: Tuần 1 — Information Architecture & Wireframe

**Mục tiêu**: Thiết kế cấu trúc thông tin và wireframe

| Task | Giờ |
|---|---|
| Phân tích IA: phân loại nội dung, menu, navigation | 3 |
| Vẽ Sitemap | 2 |
| Vẽ User Flow (login, tạo content, xem history) | 3 |
| Thiết kế Wireframe Lo-fi cho tất cả màn hình | 10 |
| Review wireframe | 2 |

**Deliverables**: Sitemap, User Flow, Wireframe Lo-fi

**DoD**: Wireframe được review, sitemap và user flow hoàn chỉnh

---

## Sprint 6 — UX/UI: Tuần 2 — Design System & Prototype

**Mục tiêu**: Xây dựng Design System và Prototype tương tác

| Task | Giờ |
|---|---|
| Chọn Color Palette (primary, secondary, accent) | 2 |
| Chọn Typography (font family, sizes, weights) | 1 |
| Xây dựng Component Library (Button, Input, Card, Modal, Navbar) | 6 |
| Thiết kế Responsive (desktop, tablet, mobile) | 3 |
| Dựng Prototype Hi-fi trên Figma | 6 |
| Kết nối prototype tương tác | 2 |

**Deliverables**: Design System, Prototype Hi-fi

**DoD**: Prototype tương tác được trên Figma, design system đầy đủ components

---

## Sprint 7 — Database & API: Tuần 1 — Database Design

**Mục tiêu**: Thiết kế cơ sở dữ liệu

| Task | Giờ |
|---|---|
| Ôn tập SQL (JOIN, INDEX, CONSTRAINT) | 3 |
| Xác định entities & relationships | 3 |
| Vẽ ERD | 4 |
| Tạo Data Dictionary | 3 |
| Thiết kế bảng (users, contents, categories, templates, history) | 4 |
| Đặt khóa chính/ngoại, index | 2 |
| Viết SQL Script (CREATE TABLE, INSERT mẫu) | 3 |

**Deliverables**: ERD, Data Dictionary, SQL Script

**DoD**: SQL script chạy không lỗi, ERD vẽ đầy đủ relationships

---

## Sprint 8 — Database & API: Tuần 2 — API Design

**Mục tiêu**: Thiết kế REST API và tài liệu

| Task | Giờ |
|---|---|
| Học RESTful conventions, HTTP methods, status codes | 3 |
| Liệt kê tất cả API endpoints | 3 |
| Thiết kế JSON request/response cho từng endpoint | 4 |
| Viết OpenAPI/Swagger spec | 5 |
| Tạo Postman Collection với environment variables | 3 |
| Thiết kế Authentication Flow (JWT) | 2 |

**Deliverables**: OpenAPI Spec, Postman Collection, Auth Flow

**DoD**: API spec đầy đủ, Postman collection test được

---

## Sprint 9 — System Design: Tuần 1 — HLD

**Mục tiêu**: Thiết kế kiến trúc hệ thống tổng quan

| Task | Giờ |
|---|---|
| Học SOLID, Clean Architecture | 4 |
| Xác định kiến trúc (monolithic vs microservices) | 2 |
| Vẽ Architecture Diagram (layers, components) | 4 |
| Thiết kế data flow | 2 |
| Chọn tech stack chi tiết | 2 |
| Viết HLD Document | 4 |

**Deliverables**: Architecture Diagram, HLD Document

**DoD**: Architecture diagram rõ ràng, HLD document hoàn chỉnh

---

## Sprint 10 — System Design: Tuần 2 — LLD

**Mục tiêu**: Thiết kế chi tiết class, sequence

| Task | Giờ |
|---|---|
| Học Design Patterns (Singleton, Factory, Strategy, DI) | 4 |
| Thiết kế Class Diagram (Controllers, Services, Repositories, DTOs) | 6 |
| Thiết kế Sequence Diagram (login, create content, call AI) | 4 |
| Viết LLD Document | 4 |
| Review toàn bộ design | 2 |

**Deliverables**: Class Diagram, Sequence Diagram, LLD Document

**DoD**: Diagrams vẽ đầy đủ, design patterns áp dụng hợp lý

---

## Sprint 11 — Backend: Tuần 1 — Project Setup & Entities

**Mục tiêu**: Khởi tạo Spring Boot project, tạo entities và repositories

| Task | Giờ |
|---|---|
| Khởi tạo Spring Boot project (Spring Initializr) | 1 |
| Cấu hình application.yml (datasource, JPA, logging) | 2 |
| Tạo Entities: User, Content, Category, Template, History | 5 |
| Định nghĩa Relationships (@OneToMany, @ManyToOne) | 2 |
| Tạo Repositories (JpaRepository) | 2 |
| Cấu hình Lombok, DevTools | 1 |
| Tạo data mẫu (import.sql) | 2 |
| Kiểm tra kết nối database | 1 |

**Deliverables**: Spring Boot project, Entities, Repositories

**DoD**: Ứng dụng chạy được, kết nối DB, entities mapping đúng

---

## Sprint 12 — Backend: Tuần 2 — CRUD APIs

**Mục tiêu**: Xây dựng Services, DTOs, và CRUD Controllers

| Task | Giờ |
|---|---|
| Tạo DTOs (Request/Response) cho từng entity | 3 |
| Xây dựng Mappers (Entity ↔ DTO) | 2 |
| Tạo Validators | 2 |
| Viết Services: UserService, ContentService, CategoryService, TemplateService | 6 |
| Viết Controllers: CRUD endpoints | 5 |
| Global Exception Handler (@ControllerAdvice) | 2 |
| Test APIs bằng Postman | 3 |

**Deliverables**: REST CRUD APIs, Service layer, DTOs

**DoD**: Tất cả CRUD endpoints hoạt động, Postman test pass

---

## Sprint 13 — Backend: Tuần 3 — Auth & Security

**Mục tiêu**: Xây dựng authentication và authorization

| Task | Giờ |
|---|---|
| Cấu hình Spring Security | 3 |
| Implement JWT (generate token, validate, refresh) | 5 |
| Xây dựng AuthController (login, register, refresh) | 3 |
| Phân quyền role-based (USER, ADMIN) | 2 |
| Secure các endpoints | 2 |
| Exception Handling cho security | 1 |
| Logging (SLF4J + Logback) | 2 |
| Test toàn bộ flow auth + CRUD | 4 |

**Deliverables**: Auth module, Spring Security, JWT, Logging

**DoD**: Login/Register hoạt động, protected routes chặn đúng, log đầy đủ

---

## Sprint 14 — AI Integration: Tuần 1 — Prompt Engineering & LLM API

**Mục tiêu**: Tích hợp LLM API, xây dựng prompt templates

| Task | Giờ |
|---|---|
| Học Prompt Engineering (temperature, tokens, system/user) | 4 |
| Đăng ký LLM API key (OpenAI / Gemini / Claude) | 1 |
| Xây dựng AIService (call LLM API, parse response) | 5 |
| Xử lý errors (rate limit, timeout, invalid key) | 2 |
| Tạo prompt templates cho từng loại content | 4 |
| Test service với Postman | 2 |

**Deliverables**: AIService, Prompt Templates

**DoD**: Gọi LLM API thành công, parse response đúng format

---

## Sprint 15 — AI Integration: Tuần 2 — Optimize & Cache

**Mục tiêu**: Tối ưu prompt, caching, tích hợp vào API

| Task | Giờ |
|---|---|
| Tinh chỉnh prompt parameters cho output quality | 4 |
| Implement caching (in-memory / Redis) | 4 |
| Tạo ContentGeneratorController (kết nối AI + lưu kết quả) | 3 |
| Tạo API endpoint cho AI generation | 2 |
| Xử lý async (CompletableFuture) cho request dài | 2 |
| Viết unit test cho AIService | 3 |

**Deliverables**: ContentGenerator API, Cache module, Unit tests

**DoD**: AI generation API hoạt động, cache giảm request trùng, có unit test

---

## Sprint 16 — Frontend: Tuần 1 — Project Setup & Auth

**Mục tiêu**: Khởi tạo React app, xây dựng login/register

| Task | Giờ |
|---|---|
| Khởi tạo React app (Vite / CRA) | 1 |
| Cài thư viện: React Router, Axios, Tailwind/MUI | 2 |
| Xây dựng Layout (Navbar, Sidebar, Footer) | 3 |
| Xây dựng Login page (form + API call) | 4 |
| Xây dựng Register page | 2 |
| Lưu token (localStorage), protected routes | 3 |
| Xử lý error messages | 1 |

**Deliverables**: React app, Auth pages, Protected routes

**DoD**: Login/Register hoạt động, token lưu đúng, redirect sau auth

---

## Sprint 17 — Frontend: Tuần 2 — Dashboard & Generator

**Mục tiêu**: Xây dựng Dashboard và trang Generator

| Task | Giờ |
|---|---|
| Xây dựng Dashboard (stats, recent content, quick actions) | 5 |
| Xây dựng Generator form (topic, tone, length, category) | 4 |
| Gọi AI API từ frontend | 3 |
| Preview kết quả (loading, success, error states) | 3 |
| Save content vào history | 2 |
| Xử lý responsive cho generator | 1 |

**Deliverables**: Dashboard page, Generator page

**DoD**: Generator form gọi API thành công, hiển thị kết quả, lưu history

---

## Sprint 18 — Frontend: Tuần 3 — History & Profile

**Mục tiêu**: Xây dựng History, Profile, responsive

| Task | Giờ |
|---|---|
| Xây dựng History page (bảng danh sách content) | 4 |
| Search & filter content (theo category, date, keyword) | 3 |
| Xem chi tiết content, copy nội dung | 2 |
| Xây dựng Profile page (thông tin, đổi mật khẩu) | 3 |
| Tối ưu responsive toàn bộ app | 4 |
| Xử lý loading, empty, error states | 2 |
| Review & fix UI bugs | 2 |

**Deliverables**: History page, Profile page, Responsive UI

**DoD**: Toàn bộ flow hoạt động, responsive đẹp, không còn UI bugs

---

## Sprint 19 — Testing: Tuần 1 — Test Plan & Unit Tests

**Mục tiêu**: Viết Test Plan, Unit Tests cho Backend

| Task | Giờ |
|---|---|
| Viết Test Plan (scope, strategy, schedule) | 3 |
| Viết Test Cases cho từng use case | 4 |
| Unit Test cho Service layer (JUnit 5 + Mockito) | 6 |
| Unit Test cho Utilities, Mappers | 3 |
| Đo code coverage | 1 |

**Deliverables**: Test Plan, Test Cases, Unit Tests

**DoD**: Coverage > 70% cho Service layer

---

## Sprint 20 — Testing: Tuần 2 — Integration & API Tests

**Mục tiêu**: Integration Test, API Test, Bug Fix

| Task | Giờ |
|---|---|
| Integration Test cho Controller + Repository (Spring Boot Test) | 6 |
| API Test với Postman Newman (auto collection) | 4 |
| Frontend component test (Jest / React Testing Library) | 4 |
| Bug triage & fix | 4 |
| Re-test & báo cáo | 2 |

**Deliverables**: Integration tests, Newman collection, Bug-free code

**DoD**: All tests pass, bug list empty

---

## Sprint 21 — Deployment: Tuần 1 — Docker & CI/CD

**Mục tiêu**: Docker hóa ứng dụng, thiết lập CI/CD

| Task | Giờ |
|---|---|
| Viết Dockerfile cho Backend | 2 |
| Viết Dockerfile cho Frontend (Nginx multi-stage) | 2 |
| Viết docker-compose.yml (backend, frontend, db) | 3 |
| Cấu hình GitHub Actions (build, test, push image) | 5 |
| Test CI pipeline | 2 |

**Deliverables**: Dockerfiles, docker-compose, GitHub Actions CI

**DoD**: Docker images build được, CI pipeline chạy thành công

---

## Sprint 22 — Deployment: Tuần 2 — Deploy & Domain

**Mục tiêu**: Deploy lên production, domain, SSL

| Task | Giờ |
|---|---|
| Setup VPS / Railway / AWS | 3 |
| Deploy Docker containers | 3 |
| Cấu hình Nginx reverse proxy | 2 |
| Mua domain, trỏ DNS | 1 |
| Cài SSL (Let's Encrypt / Certbot) | 2 |
| Kiểm tra production | 2 |
| Monitoring cơ bản | 1 |

**Deliverables**: Production URL, HTTPS, CI/CD pipeline hoàn chỉnh

**DoD**: App chạy production, HTTPS, CI/CD auto deploy

---

## Sprint 23 — Documentation (1 tuần)

**Mục tiêu**: Hoàn thiện tài liệu và portfolio

| Task | Giờ |
|---|---|
| Viết README.md (tổng quan, tech stack, cài đặt, screenshots) | 3 |
| Viết User Guide (hướng dẫn sử dụng từng tính năng) | 4 |
| API Documentation (Swagger UI / Redoc) | 3 |
| Viết Release Notes (v1.0.0) | 1 |
| Quay demo video | 3 |
| Xây dựng GitHub Portfolio (README đẹp, topics, website) | 3 |
| Review toàn bộ tài liệu | 1 |

**Deliverables**: README, User Guide, API Docs, Release Notes, Demo, Portfolio

**DoD**: Tài liệu đầy đủ, portfolio sẵn sàng giới thiệu

---

## Tổng hợp Sprint

| Sprint | Phase | Tuần | Giờ ước tính |
|---|---|---|---|
| 0 | Chuẩn bị | 2 ngày | 6 |
| 1 | Software Engineering | 1 | 20 |
| 2 | Product Discovery | 1 | 20 |
| 3 | Business Analysis | 1 | 22 |
| 4 | Requirement Analysis | 1 | 22 |
| 5–6 | UX/UI | 2 | 40 |
| 7–8 | Database & API | 2 | 40 |
| 9–10 | System Design | 2 | 40 |
| 11–13 | Backend | 3 | 60 |
| 14–15 | AI Integration | 2 | 40 |
| 16–18 | Frontend | 3 | 56 |
| 19–20 | Testing | 2 | 40 |
| 21–22 | Deployment | 2 | 40 |
| 23 | Documentation | 1 | 21 |
| **Total** | **14 phases** | **24 tuần** | **~447 giờ** |
