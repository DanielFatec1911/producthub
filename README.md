# ProductHub 🛍️

Catálogo de produtos fullstack com Django, Next.js e armazenamento de imagens na nuvem.

## 🏗️ Arquitetura

```
[Usuário] → [Next.js :3000] → [Django API :8000] → [Banco de dados]
                                      ↓
                               [Cloudinary — imagens na nuvem]
```

## 🛠️ Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![Cloudinary](https://img.shields.io/badge/Cloudinary-3448C5?style=for-the-badge&logo=cloudinary&logoColor=white)

## ⚙️ Como rodar

**Back-end:**
```bash
cd producthub
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

**Front-end:**
```bash
cd frontend
npm install
npm run dev
```

## 👨‍💻 Autor

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/daniel-silva-97a3202a9/)
