# Web-application-for-uploading-images-with-descriptions
This is a Django web application that allows users to upload images along with descriptions and categorization. 
It provides an API for image upload and retrieval of uploaded images with descriptions. Users can view the uploaded images and add descriptions to them using Bootstrap modules. 
The application is containerized using Docker.
Features
  User-friendly interface for uploading images and adding descriptions
  API endpoints for image upload and retrieval
  Bootstrap integration for a responsive and visually appealing design
  Docker containerization for easy deployment and scalability
Prerequisites
Make sure you have the following installed on your system:
  Python (version 3.9 or higher)
  Docker
Installation
  1. Clone the repository:  git clone <repository-url>
  2. Navigate to the project directory: cd <project-directory>
  3. Build the Docker image: docker build -t image-upload-app .
  4. Run the Docker container: docker run -p 8000:8000 image-upload-app
  5. Access the application in your web browser at http://localhost:8000.
Usage
  1. Open the web application in your browser.
  2. Click on the «A»dd Photo button to upload an image.
  3. Provide a description, select a category or create your own if there is no such image and click on the "Submit" button.
  4. The uploaded image will be displayed along with its description.
  5. To view the list of uploaded images, click "ALL Pictures" in the left menu.
  6. A list of images with their category will be displayed.
Technologies Used
  Django: Python web framework for building the application
  Bootstrap: Front-end framework for responsive design and UI components
  Docker: Containerization for easy deployment and scalability
Contributing
Contributions are welcome! If you have any suggestions, improvements, or bug fixes, please open an issue or submit a pull request.

Веб-приложение для загрузки изображений с описаниями
Это веб-приложение на языке Django, позволяющее пользователям загружать изображения с описаниями и категорией. 
Оно предоставляет API для загрузки изображений и получения загруженных изображений с описаниями. 
Пользователи могут просматривать загруженные изображения и добавлять к ним описания с помощью модулей Bootstrap. Приложение контейнеризировано с помощью Docker.
Особенности
  Удобный интерфейс для загрузки изображений и добавления описаний
  Конечные точки API для загрузки и получения изображений
  Интеграция Bootstrap для создания отзывчивого и визуально привлекательного дизайна
  Контейнеризация Docker для простоты развертывания и масштабируемости
Необходимые условия
Убедитесь, что в вашей системе установлено следующее:
  Python (версия 3.6 или выше)
  Docker
Установка
  1. Клонируйте репозиторий: git clone <repository-url>.
  2. Перейдите в каталог проекта: cd <project-directory>
  3. Соберите образ Docker: docker build -t image-upload-app .
  4. Запустите Docker-контейнер: docker run -p 8000:8000 image-upload-app
  5. Получите доступ к приложению в веб-браузере по адресу http://localhost:8000.
Откройте веб-приложение в браузере.
  1. Нажмите на кнопку "Upload Image" для загрузки изображения.
  2. Укажите описание, выберете категорию или создайте свою если такой нету  изображения и нажмите кнопку "Отправить".
  3. Загруженное изображение будет отображено вместе с его описанием.
  4. Чтобы просмотреть список загруженных изображений, нажмите в левом меню "ВСЕ Фотографии 
  5. Отобразится список изображений с их категорией.
Используемые технологии
  Django: Веб-фреймворк Python для создания приложения
  Bootstrap: Front-end фреймворк для создания отзывчивого дизайна и компонентов пользовательского интерфейса
  Docker: Контейнеризация для упрощения развертывания и масштабирования
Вклад
Вклад в разработку приветствуется! Если у вас есть предложения, улучшения или исправления ошибок, пожалуйста, откройте проблему или отправьте запрос на исправление.
