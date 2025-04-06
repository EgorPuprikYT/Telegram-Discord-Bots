# 🌟 **WelcomeBot Pro** — Идеальное приветствие для вашего Discord-сервера

[![Python](https://img.shields.io/badge/Python-3.10+-blue?logo=python)](https://www.python.org)
[![Disnake](https://img.shields.io/badge/Disnake-2.10+-purple?logo=discord)](https://docs.disnake.dev)
[![Discord](https://img.shields.io/badge/Discord-Support-7289DA?logo=discord)](https://discord.gg/[ваша-ссылка](https://discord.gg/6yfpJXSZSA))
![License](https://img.shields.io/badge/License-MIT-brightgreen)

<div align="center">
  <img src="https://cdn.discordapp.com/attachments/1357935407227998238/1358014875862827089/minecraft_title1.png?ex=67f24d69&is=67f0fbe9&hm=106d31f16486e30bd1a8af83376786d6eed206e53c7309e0fb1cdb1d3a7a2e18&" width="600" alt="WelcomeBot Preview">
</div>

## 🚀 **Ключевые особенности**

✨ **Персонализированные приветствия** с 50+ вариантами  
🎨 **Стильные Embed-сообщения** с настраиваемым дизайном  
🛡️ **Автоматическая выдача ролей** новым участникам  
📊 **Детальное логирование** всех событий  
⚡ **Оптимизированная производительность** для больших серверов  

---

## 🛠 **Быстрый старт**

### 1. Установка
```bash
git clone https://github.com/yourname/WelcomeBot.git
cd WelcomeBot
pip install -r requirements.txt
```

### 2. Настройка (`config.py`)
```python
TOKEN = "ваш_токен_бота"  # Получить на [Discord Developer Portal](https://discord.com/developers)
WELCOME_CHANNEL_ID = 123456789  # ID канала для приветствий
```

### 3. Запуск
```bash
python main.py
```

---

## 🎨 **Кастомизация**

### Настройки оформления:
```python
# В config.py
EMBED_COLOR = disnake.Color.gold()  # Золотой цвет
WELCOME_IMAGE_URL = "https://i.imgur.com/ваша_картинка.jpg"  # Фоновое изображение
FOOTER_TEXT = "Добро пожаловать в наше сообщество!"  # Текст в подвале
```

### Фразы приветствия (`greetings.txt`):
```
{user} | Добро пожаловать в {guild}!
{user} | Рады видеть тебя среди нас!
{user} | Приготовься к удивительному приключению!
```

---

## 📸 **Пример работы**

<div align="center">
  <img src="[https://i.imgur.com/welcome-example1.png](https://cdn.discordapp.com/attachments/1357979619587915958/1358395689851162634/image.png?ex=67f3b012&is=67f25e92&hm=4b962a880495d599de71525cc899bf827524aa24665683b64eefce07521da122&)" width="400" alt="Пример 1">
  <img src="[https://i.imgur.com/welcome-example2.png](https://cdn.discordapp.com/attachments/1357979619587915958/1358397013384761526/image.png?ex=67f3b14d&is=67f25fcd&hm=977fe38baceea98fd46775179632b3f89a968259c7d305279fa3a544cbfb607b&)" width="400" alt="Пример 2">
</div>

---

## 💼 **Профессиональные настройки**

```python
# Для больших серверов:
AUTO_ROLE_ID = 987654321  # Автоматическая выдача роли
ADMIN_CHANNEL_ID = 567891234  # Канал для уведомлений об ошибках

# Премиум-оформление:
EMBED_COLOR = disnake.Color.dark_purple()
WELCOME_IMAGE_URL = "https://i.imgur.com/premium-bg.jpg"
```

---

## 📞 **Поддержка**

По всем вопросам обращайтесь в наш [Discord-сервер]([https://discord.gg/6yfpJXSZSA)  
Или пишите на почту: **novaspace618@gmail.com**

---

## 📜 **Лицензия**

Этот проект распространяется под лицензией MIT.  
Полный текст лицензии доступен в файле [LICENSE](LICENSE).

---

<div align="center">
  <h3>❤️ Нравится проект? Поставьте звезду на GitHub!</h3>
  <p>Ваша поддержка помогает нам развиваться</p>
</div>
