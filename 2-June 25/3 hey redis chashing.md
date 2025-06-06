# 📝 Dev Journal — 2025-06-03

## ⚙️ Redis Setup via WSL — Done!

Over the past couple of days, I’ve been refining the **UI for mobile** to make sure the MVP is polished and smooth on all devices. Today, I tackled something bigger — **Redis integration**.

Since Redis doesn’t run natively on Windows, I went ahead and:
- Installed **WSL**,
- Set up **Redis** inside it,
- Migrated my project into WSL,
- Configured the **Redis channel layer**, and...
✅ It worked perfectly!

Everything is up and running now — real-time messaging works great through Redis inside WSL.

---

## 💬 Messaging & MARK1's Core

Real-time chat is a huge part of **MARK1**, and Redis plays a key role in making that experience fast and reliable.  
For now, I’ll continue developing in this setup, and then switch to **Redis for caching and channels in production** when I deploy.

---

## 🧩 What’s Left?

We’re getting really close to wrapping this build!  
Only two core features remain:
- **Groups**
- **Clubs**

After that, it’s all polish, testing, and deployment!

---

## 🚀 Almost There...

This project is coming together beautifully. Every day I’m learning, adapting, and building something I’m genuinely proud of.
