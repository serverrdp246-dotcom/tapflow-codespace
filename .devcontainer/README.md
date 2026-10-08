# tapflow Development Environment - Codespace Configuration

هذا المجلد يحتوي على إعدادات GitHub Codespace لتطوير tapflow.

## البدء السريع

1. افتح المستودع على GitHub
2. اضغط على **Code** → **Codespaces** → **Create codespace on main**
3. انتظر حتى ينتهي التثبيت (سيتم تثبيت المتعلقات تل��ائياً)
4. شغّل أحد الأوامر التالية:

```bash
# للتطوير المحدود (بدون محاكاة أجهزة حقيقية)
pnpm dev:lean

# أو للتطوير مع وكلاء محاكاة
pnpm dev:pool

# أو للتطوير الكامل
pnpm dev
```

## المنافذ المتاحة

- **4000**: Relay Server
- **5173**: Dashboard Development

## الملفات

- `devcontainer.json`: إعدادات Codespace الرئيسية
- `Dockerfile`: صورة Docker المخصصة

## البيئة

- **Node.js**: 22.x
- **pnpm**: Enabled
- **Extensions**: ESLint, Prettier, Vue.volar, Biome, GitHub Copilot
