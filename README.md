# CST8915 Lab 3: 

**Student Name**: Bosi Chen\
**Student ID**: 041040774\
**Course**: CST8915 Full-stack Cloud-native Development\
**Semester**: Winter 2026

---

## Demo Video

🎥 [Watch Demo Video](https://youtu.be/3RwBniFxMJ4)

---

## Reflection Questions

1. What challenges did you encounter when configuring environment variables in the GitHub Actions workflow?
   
   My challenges start with understanding the concept on switching from the local `.env` file to configurations in a PaaS model. It took me a few time to find where to pass those configurations since they are ingnored by git and thus not in the GitHub repo.

2. How does deploying microservices on Azure Web App Service differ from running them locally?
   
   Locally, the services should be started manually (e.g., `node index.js`, `cargo go` or `python3 app.py`), and all the dependencies are managed locally and manually as well. On Azure Web Service, the cloud provider handels VM, OS and runtime on behalf and the services are started automatically.

3. Why is it important to use environment variables for configurations in a cloud environment?
   
   To make sure that all the sensitive configuration data such as the ID, password, key strings etc. are kept secret locally. This also aligns with the configuration in the twelve-factor application, store the configuration in environment to ensure better portability and security.

---

## Service Repositories

- [order-service](https://github.com/bosichen-ac/order-service)

- [product-service](https://github.com/bosichen-ac/product-service-new)

- [store-front](https://github.com/bosichen-ac/store-front)