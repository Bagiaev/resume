# 🎭 Анализ аудиофайлов для распознавания эмоций  

## 📌 Цель  
Провести анализ аудиофайлов с целью распознавания эмоций в речи и построения эффективных признаков для этой задачи.  

### 🔹 Основные задачи:  
- Изучение методов **извлечения признаков** из аудиофайлов:  
  - **Мел-частотные кепстральные коэффициенты (MFCC)**  
  - **Спектральные характеристики**  
  - **Временные параметры**  
- Разработка функций для аугментации данных  
- Обучение моделей на различных наборах голосов  

---

## 📂 Набор данных  
Использованы четыре различных датасета с аудиофайлами:  

| Датасет  | Количество аудиофайлов |
|----------|------------------------|
| **CREMA-D** | 7,442  |
| **TESS**    | 2,800  |
| **RAVDESS** | 2,076  |
| **SAVE**    | 480    |

Перед обучением набор данных был разделен на:  
- **Женские, мужские и смешанные голоса**

Набор данных после аугментации: 
- **Обучающий набор: 68,107 образцов**  
- **Валидационный набор: 17,027 образцов**  

---

## 🚀 Обучение модели  
🔹 В ходе работы были продемонстрированы новые функции для аугментации данных.  
🔹 Полное обучение модели на всех наборах данных заняло около 16 часов.  

**📊 Итог:**  
- **Точность предсказания эмоций ≈ 90%**  
- Дальнейшие исследования могут включать:  
  - Улучшение моделей  
  - Глубокий анализ конкретных эмоций  
  - Расширение датасета для повышения производительности  

---
