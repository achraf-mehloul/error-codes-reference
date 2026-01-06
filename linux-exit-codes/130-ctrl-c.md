
## 130-terminated-by-ctrl-c.md

```markdown
# رمز الخروج 130: إنهاء بواسطة Ctrl+C (Terminated by Control-C)

### وصف مختصر
يُشير رمز الخروج 130 إلى إنهاء العملية بواسطة إشارة SIGINT (Interrupt)، غالبًا بالضغط على Ctrl+C.

### الأسباب الشائعة لظهور الرمز
- تدخل المستخدم لإيقاف الأمر (Ctrl+C).
- إرسال إشارة SIGINT برمجيًا.

### مثال عملي
```bash
sleep 100  # شغل هذا، ثم اضغط Ctrl+C
echo $?    # سيطبع 130
