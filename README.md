# 🚀 Free AI APIs Collection

<div dir="rtl">

## 📞 اطلاعات تماس

📧 Email: **pchreza@gmail.com**  
💬 Telegram: **[@disreza](https://t.me/disreza)**

</div>

---

<div dir="rtl">

## لیست ارائه‌دهندگان API رایگان

### 🥇 XKiro - 5M توکن روزانه
- **توکن**: 5,000,000 روزانه (کاملاً رایگان)
- **RPM**: 60 درخواست در دقیقه
- **وبسایت**: [xkiro.com](https://xkiro.com)
- **نیاز به کارت**: ❌ خیر
- **مدل‌ها**: GPT-4, Claude 3, Llama 3, Gemini, Mistral

### 🥈 AnyModel - 10K توکن روزانه
- **توکن**: 10,000 روزانه (کاملاً رایگان)
- **RPM**: 20 درخواست در دقیقه
- **وبسایت**: [anymodel.org](https://anymodel.org)
- **نیاز به کارت**: ❌ خیر
- **مدل‌ها**: Llama 3, Mistral, Gemma, Qwen, Phi-3

### 🥉 NVIDIA - 1M توکن ماهانه
- **توکن**: 1,000,000 ماهانه (کاملاً رایگان)
- **RPM**: 100 درخواست در دقیقه
- **وبسایت**: [build.nvidia.com](https://build.nvidia.com)
- **نیاز به کارت**: ❌ خیر
- **مدل‌ها**: Llama 3.1, Mistral, Gemma, Phi-3

### ⚡ Groq - سریع‌ترین API
- **محدودیت**: 30 درخواست در دقیقه (کاملاً رایگان)
- **RPM**: 30
- **وبسایت**: [groq.com](https://groq.com)
- **نیاز به کارت**: ❌ خیر
- **مدل‌ها**: Llama 3.1, Mixtral, Gemma, Phi-3
- **زمان پاسخ**: 50-200ms (سریع‌ترین!)

### 🏠 Ollama - کاملاً نامحدود (محلی)
- **محدودیت**: بدون محدودیت (اجرای محلی)
- **وبسایت**: [ollama.com](https://ollama.com)
- **نیاز به ثبت‌نام**: ❌ خیر
- **مدل‌ها**: 100+ مدل مختلف

### 🎨 LM Studio - کاملاً نامحدود (محلی)
- **محدودیت**: بدون محدودیت (اجرای محلی)
- **وبسایت**: [lmstudio.ai](https://lmstudio.ai)
- **نیاز به ثبت‌نام**: ❌ خیر
- **مدل‌ها**: 50+ مدل GGUF

### 🔥 Together AI - $25 اعتبار
- **اعتبار**: $25 اولیه رایگان
- **RPM**: 30 درخواست در دقیقه
- **وبسایت**: [together.ai](https://together.ai)
- **نیاز به کارت**: ❌ خیر
- **مدل‌ها**: Llama 3.1, Mistral, Qwen, Falcon

### 🎆 Fireworks AI - $5 اعتبار
- **اعتبار**: $5 اولیه رایگان
- **RPM**: 60 درخواست در دقیقه
- **وبسایت**: [fireworks.ai](https://fireworks.ai)
- **نیاز به کارت**: ❌ خیر
- **مدل‌ها**: Llama 3.1, Qwen (چندزبانه), Yi

### 🌫️ Mistral AI - مدل‌های رایگان
- **محدودیت**: برخی مدل‌ها کاملاً رایگان
- **RPM**: 40 درخواست در دقیقه
- **وبسایت**: [mistral.ai](https://mistral.ai)
- **نیاز به کارت**: ❌ خیر
- **مدل‌های رایگان**: open-mistral-7b, open-mixtral-8x7b

### 🆕 SiliconFlow - 1M توکن
- **توکن**: 1,000,000 ماهانه (کاملاً رایگان)
- **RPM**: 20 درخواست در دقیقه
- **وبسایت**: [siliconflow.cn](https://siliconflow.cn)
- **نیاز به کارت**: ❌ خیر
- **مدل‌ها**: Qwen 2.5, DeepSeek, Yi

### 🆕 Hyperbolic - 500K توکن روزانه
- **توکن**: 500,000 روزانه (کاملاً رایگان)
- **RPM**: 30 درخواست در دقیقه
- **وبسایت**: [hyperbolic.xyz](https://hyperbolic.xyz)
- **نیاز به کارت**: ❌ خیر
- **مدل‌ها**: Llama 3.1, Mistral, Qwen

### 🆕 Segmind - 100 تصویر روزانه
- **تصویر**: 100 تصویر روزانه (کاملاً رایگان)
- **RPM**: 10 درخواست در دقیقه
- **وبسایت**: [segmind.com](https://segmind.com)
- **نیاز به کارت**: ❌ خیر
- **مدل‌ها**: SDXL, Flux, Stable Diffusion

### 🆕 Cloudflare Workers AI - 10K توکن
- **توکن**: 10,000 روزانه (کاملاً رایگان)
- **RPM**: 10 درخواست در دقیقه
- **وبسایت**: [developers.cloudflare.com/workers-ai](https://developers.cloudflare.com/workers-ai)
- **نیاز به کارت**: ❌ خیر
- **مدل‌ها**: Llama 3, Mistral, Qwen

</div>

---

<div dir="rtl">

## نحوه استفاده

```python
import requests

url = "https://api.xkiro.com/v1/chat/completions"
headers = {"Authorization": "Bearer YOUR_API_KEY"}
data = {"model": "gpt-4-turbo", "messages": [{"role": "user", "content": "Hello!"}]}

response = requests.post(url, json=data, headers=headers)
print(response.json())
```

</div>

---

<div dir="rtl">

**ساخته شده با ❤️ برای جامعه توسعه‌دهندگان ایرانی**

تماس: pchreza@gmail.com | Telegram: @disreza

</div>
