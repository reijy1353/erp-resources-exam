# Sistem ERP pentru Gestionarea Resurselor Companiei

## 📝 Descriere Proiect
Acest sistem Enterprise Resource Planning (ERP) este conceput pentru companii de dimensiuni medii, având ca scop centralizarea managementului echipelor, sarcinilor, resurselor umane și financiare.

## 🚀 Tehnologii Utilizate
* **Frontend:** React / Angular
* **Backend:** Spring Boot (Java) sau .NET (C#)
* **Bază de date:** Oracle SQL / SQL Server
* **Orchestrare:** Kubernetes (Docker)
* **Management & CI/CD:** Trello, GitHub Actions

## 📋 Cerințe de Sistem
* Node.js (v18+)
* JDK 17+ sau .NET 8 SDK
* Docker & Kubernetes (Minikube pentru rulare locală)
* Instanță activă de bază de date

## 🛠️ Ghid de Instalare și Rulare
1. **Clonarea repository-ului:**
   ```bash
   git clone <url-repository>

2. **Pornirea Backend-ului:**
   ```bash
   cd backend
   ./mvnw spring-boot:run  # sau dotnet run

3. **Pornirea Frontend-ului:**
   ```bash
   cd frontend
   npm install
   npm start

4. **Deploy în Kubernetes:**
   ```bash
   kubectl apply -f k8s/
