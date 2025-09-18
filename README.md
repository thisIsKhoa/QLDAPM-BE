# 🚗 VoltRent Microservices – Hệ thống Quản lý & Cho thuê Phương Tiện Xanh

VoltRent là nền tảng trực tuyến cho phép người dùng tìm, đặt và thanh toán dịch vụ thuê phương tiện xanh (xe đạp điện, xe máy điện, ô tô điện) một cách nhanh chóng và tiện lợi, đồng thời hỗ trợ chủ xe quản lý và quảng bá phương tiện.

---

## 📌 Kiến trúc tổng quan

Dự án được triển khai theo mô hình **Microservices** với **Spring Boot** và **Spring Cloud**.
## 📁 Cấu trúc thư mục
voltrent-microservices/
│── eureka-server/     # Service Discovery (Eureka)
│── api-gateway/       # API Gateway (Spring Cloud Gateway)
│── auth-service/      # Xác thực, quản lý người dùng, JWT
│── vehicle-service/   # Quản lý phương tiện, lịch khả dụng
│── booking-service/   # Quản lý đặt xe
└── README.md          # Tài liệu dự án
## ⚙️ Công nghệ sử dụng

- **Java 17**
- **Spring Boot 3.x**
- **Spring Cloud 2022.x**
- **Spring Data JPA** + **PostgreSQL**
- **Spring Security** + **JWT**
- **Spring Cloud Netflix Eureka** (Service Discovery)
- **Spring Cloud Gateway** (API Gateway)
- **Lombok**
- **Springdoc OpenAPI** (Swagger UI)

---

## 🚀 Cách cài đặt & chạy dự án

### 1️⃣ Yêu cầu môi trường
- Cài **Java 17** và **Maven 3.8+**
- Cài **PostgreSQL**
- IDE gợi ý: IntelliJ IDEA / Spring Tool Suite

### 2️⃣ Clone source code
```bash
git clone https://github.com/thisIsKhoa/QLDAPM-BE.git
cd voltrent-microservices
