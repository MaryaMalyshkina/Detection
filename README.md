# Detection
Detection of doors and windows on a floor plan

Проект посвящен распознаванию дверных и оконных проемов и определению их координат.

Стек технологий

| Компонент                | Технологии                           |
|--------------------------|--------------------------------------|
| Детекция дверей и окон   | Ultralytics YOLO (model.pt)          |
| Отрисовка изображений    | OpenCV, NumPy                        |
| Веб-интерфейс            | Gradio                               |
| Исследования             | GoogleColab                          |

Структура проекта:

plan_points/
├── Docker/
│   ├── Dockerfile                # Docker-образ для приложения
│   ├── requirements.txt          # Python-зависимости
│   ├── main.py                   # Основной Gradio-приложение
│   ├── app.py                    # Альтернативный запуск для Hugging Face Spaces
│   ├── model.pt                  # Вес модели YOLO (не хранится в репозитории)
│   └── _dockerignore             # Исключения для Docker
├── планы помещений/              # Примеры планов (подпапки: хорошие, средне, плохие)
├── PlanPoints_yolo_11.ipynb      # Jupyter Notebook для экспериментов
├── screenshot.png                # Скриншот интерфейса
├── README.md                     # Документация по проекту
└── .gitignore                    # Исключения для git

