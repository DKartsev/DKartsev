# AI Developer - Daniil Kartsev

## Профиль
AI Developer, фокус на прикладных AI-продуктах: LLM/RAG, чат-ассистенты, аналитика использования моделей, а также ML/CV/RL-исследования в формате reproducible notebook-проектов.

- GitHub: [github.com/DKartsev](https://github.com/DKartsev)
- Публичных репозиториев: 46 (на 24 февраля 2026)
- Ключевой стек: Python, Dart/Flutter, TypeScript, Jupyter Notebook, SQL, API-интеграции

## Pet project -  AIChatFlutter
[AIChatFlutter](https://github.com/DKartsev/AIChatFlutter) - мультиплатформенное AI-чат-приложение на Flutter (Android/iOS/Desktop) с рабочей продуктовой архитектурой.

Что реализовано:
- Многостраничный UX (4 экрана): главная страница чата, настройки провайдера, статистика токенов, расходы по дням.
- Переключение AI-провайдера в UI: OpenRouter и VSEGPT.
- Безопасный ввод и хранение API-ключей и base URL для каждого провайдера.
- Подсчет токенов и стоимости по сообщениям/моделям.
- Визуальная аналитика: агрегаты по моделям + график дневных расходов.
- Локальное хранение истории (SQLite), экспорт истории и логов.
- Обработка ошибок API и fallback-модели при неполной конфигурации.

Технологии проекта:
- Flutter, Provider, HTTP, SharedPreferences, sqflite, flutter_dotenv.

## Портфолио по группам

### LLM, RAG, агенты и боты
- [HybridRAG_Platform](https://github.com/DKartsev/HybridRAG_Platform) - эксперименты с гибридным RAG-подходом.
- [rag_security_nemo_guardrails](https://github.com/DKartsev/rag_security_nemo_guardrails) - RAG + guardrails/безопасность.
- [knowledge_graph_gradio](https://github.com/DKartsev/knowledge_graph_gradio) - knowledge graph + Gradio интерфейс.
- [-RAG-Service-Architecture-Implementation](https://github.com/DKartsev/-RAG-Service-Architecture-Implementation) - сервисная архитектура RAG для Telegram-бота.
- [telegram-openai-agentkit](https://github.com/DKartsev/telegram-openai-agentkit) - агентный Telegram-бот.
- [telegram-openai-agentkit-1](https://github.com/DKartsev/telegram-openai-agentkit-1) - fork AgentKit-обертки для Telegram.
- [bot-test](https://github.com/DKartsev/bot-test) - экспериментальный бот-проект на TypeScript.
- [Testquizbot](https://github.com/DKartsev/Testquizbot) - Telegram quiz bot.
- [ESL-AI-Test](https://github.com/DKartsev/ESL-AI-Test) - AI-проект для языкового тестирования.
- [bert_dialogue_bot](https://github.com/DKartsev/bert_dialogue_bot) - диалоговый бот на BERT.
- [Chatbot_transformer](https://github.com/DKartsev/Chatbot_transformer) - чатбот на Transformer-архитектуре.
- [headline_generation_ru](https://github.com/DKartsev/headline_generation_ru) - генерация заголовков на русском языке.
- [Saiga-CPU-Evaluation](https://github.com/DKartsev/Saiga-CPU-Evaluation) - оценка качества/производительности LLM на CPU.

### Computer Vision и мультимодальные модели
- [Cat-and-Dog-Image-Classification-Using-MobileNet](https://github.com/DKartsev/Cat-and-Dog-Image-Classification-Using-MobileNet) - классификация кошек и собак на MobileNet.
- [Classification-of-dog-breeds-using-EfficientNetV2B0](https://github.com/DKartsev/Classification-of-dog-breeds-using-EfficientNetV2B0) - классификация пород собак на EfficientNetV2B0.
- [Covid19_unet](https://github.com/DKartsev/Covid19_unet) - сегментация медицинских изображений с U-Net.
- [DCGAN-Comparison-on-Fashion-MNIST](https://github.com/DKartsev/DCGAN-Comparison-on-Fashion-MNIST) - сравнение DCGAN-подходов на Fashion-MNIST.
- [Glasses-Overlay-with-Focus-Blur](https://github.com/DKartsev/Glasses-Overlay-with-Focus-Blur) - CV-эффекты: наложение очков и размытие фона.
- [handwritten-letters-classification](https://github.com/DKartsev/handwritten-letters-classification) - классификация рукописных символов.
- [MNIST-Sketch-Classifier](https://github.com/DKartsev/MNIST-Sketch-Classifier) - классификация рукописных цифр.
- [yolov3_chess](https://github.com/DKartsev/yolov3_chess) - детекция шахматных фигур с YOLOv3.
- [Image-Captioning](https://github.com/DKartsev/Image-Captioning) - генерация текстовых описаний изображений.
- [Im2LaTeX-Seq2Seq-with-Attention](https://github.com/DKartsev/Im2LaTeX-Seq2Seq-with-Attention) - преобразование формул из изображения в LaTeX.
- [ClearMark-Autoencoder](https://github.com/DKartsev/ClearMark-Autoencoder) - автоэнкодер для восстановления/очистки изображений.

### Reinforcement Learning и управление
- [atari_policy_gradient_colab](https://github.com/DKartsev/atari_policy_gradient_colab) - обучение policy gradient-агента на Atari.
- [Pong_DQN_FC_1channel](https://github.com/DKartsev/Pong_DQN_FC_1channel) - DQN для Pong с одноканальным входом.
- [acrobot_mc_control](https://github.com/DKartsev/acrobot_mc_control) - управление Acrobot с методами RL/MC-control.
- [reinforce_parallel_pybullet](https://github.com/DKartsev/reinforce_parallel_pybullet) - параллельное обучение REINFORCE в средах PyBullet.

### NLP, классификация и аналитика данных
- [fake-news-detector](https://github.com/DKartsev/fake-news-detector) - детекция фейковых новостей.
- [IMDB-Movie-Reviews-Classifier](https://github.com/DKartsev/IMDB-Movie-Reviews-Classifier) - классификация тональности отзывов IMDB.
- [City-Issue-Classification-Model](https://github.com/DKartsev/City-Issue-Classification-Model) - классификация городских обращений по категориям.
- [Neural-Stylometry-Authorship-Classification-in-Russian-Literature](https://github.com/DKartsev/Neural-Stylometry-Authorship-Classification-in-Russian-Literature) - стилометрия и определение авторства в русской литературе.
- [HAR-UCI-Smartphone-Dataset-Baseline-vs-Transformer-vs-Attention](https://github.com/DKartsev/HAR-UCI-Smartphone-Dataset-Baseline-vs-Transformer-vs-Attention) - сравнение baseline, Transformer и Attention на HAR-датасете.
- [DEC-vs-k-means](https://github.com/DKartsev/DEC-vs-k-means) - сравнение методов кластеризации DEC и k-means.

### Временные ряды и tabular ML
- [AAPL-time-series-forecasting](https://github.com/DKartsev/AAPL-time-series-forecasting) - прогноз временного ряда акций Apple.
- [Japanese-Car-Price-Prediction](https://github.com/DKartsev/Japanese-Car-Price-Prediction) - предсказание стоимости автомобилей по признакам.
- [parkinsons-xgboost-classifier](https://github.com/DKartsev/parkinsons-xgboost-classifier) - классификатор болезни Паркинсона на XGBoost.
- [Shopping-List-Model-API](https://github.com/DKartsev/Shopping-List-Model-API) - API-модель для задач, связанных со списками покупок.

### Audio/Speech
- [speech_toolkit_lid_tts_loudness](https://github.com/DKartsev/speech_toolkit_lid_tts_loudness) - toolkit для LID, TTS и нормализации громкости.
- [Neural-Music-Generation](https://github.com/DKartsev/Neural-Music-Generation) - генерация музыкальных последовательностей нейросетями.

### Приложения, утилиты и прочие репозитории
- [FLET](https://github.com/DKartsev/FLET) - эксперименты с Python/Flet-приложениями.
- [esperanto-leto-miniapp](https://github.com/DKartsev/esperanto-leto-miniapp) - miniapp-проект на TypeScript.
- [DKartsev-Java](https://github.com/DKartsev/DKartsev-Java) - тестовое задание по Java.
- [DKartsev](https://github.com/DKartsev/DKartsev) - профильный/служебный репозиторий аккаунта.
- [CHEAT](https://github.com/DKartsev/CHEAT) - рабочие заметки и справочные материалы.

## Что я делаю как AI Developer
- Разрабатываю AI-продукты end-to-end: от идеи и прототипа до интерфейса и аналитики.
- Интегрирую LLM API и строю прикладные сценарии (чат, RAG, бот-автоматизация).
- Проектирую хранение данных, метрики использования и cost-aware аналитику.
- Поддерживаю исследовательский контур: CV, NLP, RL, генеративные и классификационные модели.
