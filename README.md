# fine-tuning_resnet
# 🌸 Fine-Tuning ResNet on Oxford 102 Flowers

Этот проект демонстрирует **дообучение модели ResNet-18** на датасете **Oxford 102 Flowers** для классификации изображений.

## 🚀 Описание
В проекте обучаются две модели:
- **ResNet-18 с нуля** (без предобученных весов).
- **ResNet-18 с Fine-Tuning** (дообучение на ImageNet).

### 📊 **Результаты**
| Модель              | Train Accuracy | Valid Accuracy | Время обучения |
|---------------------|---------------|---------------|----------------|
| **С нуля**         | 91.49%         | 94.44%        | ~6m 29s        |
| **Предобученная**  | 96.45%         | 100%          | ~2m 32s        |

## 🛠️ **Технологии**
- **Google Colab**
- **PyTorch**
- **Torchvision**
- **ResNet-18**
- **Oxford 102 Flowers Dataset**

## 📌 **Как запустить?**
1. **Откройте блокнот в Google Colab/**
2. **Запустите ячейки последовательно.**

🔗 Дополнительные ссылки

    📄 Oxford 102 Flowers Dataset
    📜 ResNet Paper

4. **Структура репозитория**
📂 fine-tuning_resnet/
│
├── fine_tuning_oxford102.ipynb  # Блокнот с кодом (Colab)
├── README.md                    # Описание проекта
└── dataset_info.txt              # Описание датасета

5. **📝 Лицензия: MIT**
