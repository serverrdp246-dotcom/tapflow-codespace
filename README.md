# tapflow Codespace

بيئة تطوير tapflow محسّنة لـ GitHub Codespace

## ماذا هو tapflow؟

tapflow هو بديل ذاتي الاستضافة لـ Appetize و BrowserStack - يسمح بتشغيل محاكي iOS وأجهزة محاكاة Android مباشرة في المتصفح.

📖 [الموقع الرسمي](https://www.tapflow.dev)

## البدء السريع مع Codespace

### 1. إنشاء Codespace

```bash
# اضغط على Code → Codespaces → Create codespace on main
```

### 2. تثبيت المتعلقات (تلقائي)

سيتم تثبيت `pnpm` والمتعلقات تلقائياً عند إنشاء Codespace.

### 3. تشغيل بيئة التطوير

```bash
# للبدء السريع
pnpm dev:lean

# أو
pnpm dev:pool
```

## الأوامر المتاحة

| الأمر | الوصف |
|------|-------|
| `pnpm dev` | تشغيل كامل البيئة |
| `pnpm dev:lean` | تطوير محدود (بدون أجهزة محاكاة حقيقية) |
| `pnpm dev:pool` | تطوير مع وكلاء محاكاة |
| `pnpm build` | بناء المشروع |
| `pnpm test` | تشغيل الاختبارات |
| `pnpm lint` | فحص الكود |

## الموارد

- 📖 [التوثيق الكاملة](https://www.tapflow.dev)
- 🚀 [البدء السريع](https://www.tapflow.dev/get-started/quick-start)
- 💻 [مستودع tapflow الأصلي](https://github.com/jo-duchan/tapflow)

## ملاحظات

⚠️ **Codespace على Linux**: 
- يمكن تشغيل Relay Server والـ Dashboard
- تشغيل محاكي iOS وأجهزة محاكاة Android الحقيقية يتطلب macOS
- استخدم `pnpm dev:lean` أو `pnpm dev:pool` للتطوير

## المساهمة

هذا المستودع توثيق فقط لإعدادات Codespace.
للمساهمة في tapflow نفسه، راجع [المستودع الأصلي](https://github.com/jo-duchan/tapflow).

## الترخيص

MIT - انظر [LICENSE](LICENSE)
