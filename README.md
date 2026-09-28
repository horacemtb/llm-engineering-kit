## Содержание

### 1. `practice_1_part_1.ipynb`
**Prompt Engineering**

Задания:
- влияние system prompt;
- влияние длины контекста;
- влияние `temperature` и `max_tokens`;
- управление стилем и форматом ответа;
- комбинирование system prompt, контекста и параметров генерации.

### 2. `practice_1_part_2.ipynb`
**Structured Output**

Задания:
- JSON Schema;
- strict и non-strict режимы;
- Structured Output vs JSON через prompt;
- zero-shot vs few-shot;
- влияние длины контекста;
- fallback-стратегии;
- сравнение OpenRouter и GigaChat;
- разделение ответственности между schema, prompt и программной логикой.

### 3. `practice_2_part_1.ipynb`
**Локальный запуск LLM и квантизация**

Задания:
- сравнение Transformers, llama.cpp, Ollama и LM Studio;
- замеры TTFT, времени генерации и tokens/sec;
- проверка OpenAI-compatible API;
- сравнение Q4, Q5 и Q8;
- влияние квантизации на скорость, память и качество ответов.

### 4. `practice_2_part_2.ipynb`
**CPU/GPU и размер модели**

Задания:
- сравнение CPU и GPU;
- замеры скорости, RAM/VRAM и TTFT;
- 10 последовательных и 5 параллельных запросов;
- сравнение моделей Qwen2.5 размером 0.5B, 1.5B и 3B;
- зависимость размера модели от скорости, ресурсов и качества ответов.
