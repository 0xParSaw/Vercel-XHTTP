
xray -test -config /usr/local/etc/xray/config.json
systemctl restart xray
```

### Certificate تمدید خودکار می‌شه؟
بله. acme.sh یه cron job می‌سازه و هر ۶۰ روز خودکار renew می‌کنه. می‌تونی manual تست کنی:
```bash
~/.acme.sh/acme.sh --renew -d xray.yourdomain.com --force --ecc
```

---

## License

MIT — مثل پروژه‌ی اصلی.

## Disclaimer

این پروژه برای آموزش و تست شخصیه. مسئولیت استفاده با خودته. قوانین کشور و TOS Vercel رو رعایت کن.

---

## 📢 ارتباط با ما

اگه این راهنما برات مفید بود، یا سوال/پیشنهاد داری، از طریق کانال تلگرام در ارتباط باش:

<div align="center">

[![Join Telegram](https://img.shields.io/badge/%D9%87%D9%85%D8%B1%D8%A7%D9%87%20%D9%85%D8%A7%20%D8%B4%D9%88-Avaco%20Cloud-26A5E4?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/avaco_cloud)

**[https://t.me/avaco_cloud](https://t.me/avaco_cloud)**

*آموزش‌های بیشتر • کانفیگ‌های آپدیت • روش‌های دور زدن سانسور • پشتیبانی*

</div>

---

⭐ اگه پروژه به دردت خورد، یه **Star** بذار تا بیشتر دیده بشه.
