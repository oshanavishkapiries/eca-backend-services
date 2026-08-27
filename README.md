# ⚙️ Backend Business Microservices Super-Repository

**Module**: Enterprise Cloud Architecture (ITS 2130)  
**Type**: Parent Super-Repository (Polyrepo with Git Submodules - Section 6)

---

## 👤 Student Information (Section 12 Compliance)

- **Student Name**: OSHAN AVISHKA
- **Student Number**: HDSE-24-1234
- **Slack Handle**: @oshanavishka
- **GCP Project ID**: eca-its2130-project

---

## 📖 Component Description

This super-repository acts as the parent repository for all **Business Microservices** of the Online Book Order Platform. It includes all service repositories as Git Submodules.

---

## 🔗 Microservice Git Submodules

| Microservice | Port | Database / Storage | Submodule Link |
| :--- | :--- | :--- | :--- |
| **`book-service`** | `8082` | MongoDB (NoSQL) + GCS | [book-service](https://github.com/oshanavishkapiries/book-service) |
| **`user-service`** | `8081` | MySQL / H2 (Relational) | [user-service](https://github.com/oshanavishkapiries/user-service) |
| **`order-service`** | `8083` | MySQL (Relational) + GCS | [order-service](https://github.com/oshanavishkapiries/order-service) |

---

## 🚀 Cloning & Initializing Submodules

To clone this parent repository along with all its submodule repositories:

```bash
git clone --recursive https://github.com/oshanavishkapiries/eca-backend-services.git
```

If already cloned:
```bash
git submodule update --init --recursive
```
