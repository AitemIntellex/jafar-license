# Jafar Pro — Foydalanuvchi Kelishuvi va AI-Assistentdan Foydalanish Shartlari

**So'nggi yangilanish: 2026-05-15**

---

## I QISM: FOYDALANUVCHI KELISHUVI

### 1. Kirish

Ushbu hujjat (bundan keyin — «Kelishuv») **Jafar Pro** dasturiy ta'minoti (bundan keyin — «DT») Muallifi va Foydalanuvchi (bundan keyin — «Foydalanuvchi», «Siz») o'rtasidagi munosabatlarni tartibga soladi.

**DIQQAT:** DT dan foydalanishni boshlashdan oldin ushbu Kelishuvni diqqat bilan o'qing. DT dan foydalanishni boshlash Sizning ushbu Kelishuvning barcha shartlariga to'liq va so'zsiz roziligingizni anglatadi. Agar biron-bir bandga rozi bo'lmasangiz, DT dan foydalanishni darhol to'xtatishingiz shart.

### 2. Broker

**DT ning ushbu versiyasi faqat Topstep (TopstepX) brokeri bilan ishlaydi.**

- DT faqat TopstepX API bilan integratsiya qilingan
- Boshqa brokerlarga (Tradovate, NinjaTrader, Interactive Brokers va boshq.) ulanish ushbu versiyada qo'llab-quvvatlanmaydi
- Foydalanuvchi Topstep brokerida hisoblarni mustaqil ro'yxatdan o'tkazadi va broker qoidalariga (Daily Loss Limit, Consistency Rule va boshq.) rioya qilish uchun javobgar hisoblanadi

### 3. Ijara Modeli: Leader-hisobdan Copy-Trade

DT Foydalanuvchiga **ijaraga** beriladi. Ijara to'lovi «Copy-Trade» modeli bo'yicha undiriladi:

#### 3.1 Hisoblar tuzilmasi
- Foydalanuvchi **1 (bitta) asosiy leader-hisob** va **4 (to'rt) tagacha** qo'shimcha copy-hisoblarga ega
- Barcha hisoblar DT ga copy-trade rejimida ulangan
- **Copy-hisoblardan biri har doim Muallif hisobi hisoblanadi** (bundan keyin — «Muallif Hisobi»)

#### 3.2 Copy-trade tamoyili
- Leader-hisob savdo qarorlarini belgilaydi; barcha copy-hisoblar leader-hisob bitimlarini **aynan takrorlaydi**
- Barcha kirishlar, chiqishlar, stop-loss va take-profit barcha hisoblarda bir xil
- Agar leader-hisob $3,000 ishlab topsa — har bir copy-hisob ham $3,000 ishlab topgan
- Muallif Hisobi DT ga faol ulanish mavjud ekan, copy-tradedan uzib bo'lmaydi

#### 3.3 Ijara to'lovi
- **Muallif Hisobida ishlab topilgan foyda DT dan foydalanganlik uchun ijara to'lovi hisoblanadi**
- Foydalanuvchi belgilangan oylik to'lovni amalga oshirmaydi
- Foydalanuvchi Muallif Hisobidagi zararlarni o'z mablag'lari hisobidan qoplamaydi
- Agar Muallif Hisobida zarar hosil bo'lgan bo'lsa — ushbu davr uchun ijara to'lovi nolga teng hisoblanadi
- **Misol:** Leader-hisob $3,000 ishlab topdi. Har bir copy-hisob (shu jumladan Muallif Hisobi) ham $3,000 ishlab topdi. Muallif ijara to'lovi sifatida $3,000 oladi. Foydalanuvchi leader-hisob foydasini ($3,000) + o'z copy-hisoblari foydasini (3 tagacha × $3,000 = $9,000) saqlab qoladi. Jami Foydalanuvchi: $12,000 gacha, Muallif: $3,000.

#### 3.4 Foydalanuvchi majburiyatlari
- Foydalanuvchi DT dan foydalanish davomida DT ga barcha hisoblarga (shu jumladan Muallif Hisobiga) kirishni ta'minlash majburiyatini oladi
- Foydalanuvchi Muallif Hisobini copy-tradedan uzmaslik majburiyatini oladi
- Foydalanuvchi Muallif Hisobini chetlab o'tish uchun DT ning alohida nusxalarini yaratmaslik majburiyatini oladi
- Foydalanuvchi Muallif Hisobini copy-tradedan chiqarish maqsadida DT ni modifikatsiya qilmaslik majburiyatini oladi

#### 3.5 Buzilish uchun javobgarlik
3.4-bo'lim shartlarining buzilishi quyidagilarga olib keladi:
- DT ga kirishning darhol to'xtatilishi
- DT dan foydalanishning butun davri uchun Muallifga boy berilgan foydani qoplash majburiyati
- Amaldagi qonunchilikka muvofiq sud ta'qibi imkoniyati

### 4. Xizmat tavsifi

**Jafar Pro** — bu moliyaviy bozorlarni tahlil qilish uchun dasturiy kompleks bo'lib, quyidagilarni o'z ichiga oladi:

- **AI-Assistent** — sun'iy intellekt (DeepSeek, Claude Opus, Gemini, Ollama) asosidagi analitik vosita bo'lib, savdo tavsiyalari, bozor tuzilmasi tahlili (SMC/ICT), qo'llab-quvvatlash/qarshilik darajalari va volatillikni baholashni taqdim etadi
- **Savdo botlari (Blade, Autobot)** — TopstepX brokeri API orqali savdo operatsiyalarini avtomatlashtirilgan tahlil qilish va bajarish tizimlari
- **Trener (Coach)** — savdo sessiyalariga tayyorgarlik va post-tahlil uchun interaktiv AI-mentor
- **Akademiya (Lesson)** — SMC/ICT metodologiyasi bo'yicha o'quv modullari
- **Bozor skaneri** — algoritmik tahlil asosida savdo imkoniyatlarini qidirish vositasi

### 5. Foydalanuvchi maqomi

- Foydalanuvchi voyaga yetgan bo'lishi kerak (18+)
- Foydalanuvchi taqdim etilgan ma'lumotlarning (API kalitlari, savdo hisobi ma'lumotlari) ishonchliligi uchun to'liq javobgar
- Foydalanuvchi DT dan faqat qonuniy maqsadlarda foydalanish majburiyatini oladi
- DT ning bitta nusxasi bitta Foydalanuvchi tomonidan foydalanish uchun mo'ljallangan

### 6. Savdo xatarlari

**JUDA MUHIM:**

CME fyucherslari bilan savdo qilish yuqori darajadagi xatar bilan bog'liq va kapitalning to'liq yo'qotilishiga olib kelishi mumkin. Siz quyidagilarni tan olasiz va rozilik bildirasiz:

- O'tmishdagi natijalar kelajakdagi daromadlarni kafolatlamaydi
- AI-Assistentning har qanday savdo tavsiyalari axborot xarakteriga ega va investitsiya maslahati hisoblanmaydi
- Botlar orqali avtomatik savdo qo'lda savdoga qaraganda tezroq zararlarga olib kelishi mumkin
- Siz o'zingizning savdo hisobingiz orqali amalga oshirilgan barcha bitimlar uchun TO'LIQ va YAKKA SHAXSAN javobgarsiz
- Na Muallif, na DT litsenziyalangan moliyaviy maslahatchi yoki broker hisoblanmaydi

### 7. Javobgarlikni cheklash

Qonun tomonidan ruxsat etilgan maksimal darajada:

- Muallif to'g'ridan-to'g'ri, bilvosita, tasodifiy yoki keyingi zararlar, shu jumladan boy berilgan foyda, ma'lumotlar yo'qotilishi yoki savdo kapitalining yo'qotilishi uchun javobgar emas
- Muallif tashqi API lardan (TopstepX, Yahoo Finance, Financial Modeling Prep, yangiliklar manbalari) olingan ma'lumotlarning aniqligi, to'liqligi yoki o'z vaqtidaligini kafolatlamaydi
- Muallif quyidagilar natijasida kelib chiqqan zararlar uchun javobgar emas: texnik nosozliklar, API xatolari, ma'lumotlarni uzatishdagi kechikishlar, elektr ta'minotining uzilishi yoki uchinchi shaxslarning harakatlari
- Barcha savdo qarorlari Foydalanuvchi tomonidan mustaqil qabul qilinadi. AI-Assistent va botlar faqat analitik ma'lumotlarni taqdim etadi

### 8. API kalitlari va xavfsizlik

- Foydalanuvchi o'z API kalitlari, tokenlari va parollarining saqlanishi uchun mustaqil javobgar
- DT kalitlarni muhit o'zgaruvchilari va Foydalanuvchi konfiguratsiya fayllarida saqlaydi
- Muallif Foydalanuvchining API kalitlariga kirish imkoniyatiga ega emas
- Foydalanuvchi hisobdagi har qanday shubhali faollik haqida darhol brokeriga xabar berish majburiyatini oladi

---

## II QISM: AI-ASSISTENTDAN FOYDALANISH SHARTLARI

### 9. AI-tavsiyalarning tabiati

Jafar Pro AI-Assistenti analitik hisobotlarni yaratish uchun katta til modellaridan (LLM) foydalanadi. Siz quyidagilarni tan olasiz va rozilik bildirasiz:

- AI-modellar xatolar, gallyutsinatsiyalar va noaniqliklarga yo'l qo'yishi mumkin
- Savdo darajalari, prognozlar va tavsiyalar ehtimollik modellari asosida yaratiladi va **kafolatlangan emas**
- AI-Assistent ong, intuitsiya yoki taqdim etilgan ma'lumotlardan tashqari kontekstni tushunishga ega emas
- AI javobining sifati kirish ma'lumotlarining (bozor kotirovkalari, stakan ma'lumotlari, yangiliklar foni) sifati va dolzarbligiga bog'liq

### 10. AI-provayderlar

DT quyidagi AI-modellardan foydalanishi mumkin:

| Provayder | Model | Flag |
|---|---|---|
| DeepSeek | deepseek-chat / deepseek-v4 | `--deepseek` (default) |
| Anthropic | Claude Opus 4.7 | `--claude` / `-c` |
| Google | Gemini 2.5 Pro | `--gemini` / `-g` |
| Ollama | Lokal modellar | `--ollama` |

- Bulutli AI-provayderlardan foydalanganda so'rovingiz ma'lumotlari tegishli provayder serverlariga uzatiladi
- Foydalanuvchi tegishli AI-provayderning foydalanish shartlariga rozi bo'ladi
- Ollama (lokal) dan foydalanganda ma'lumotlar Foydalanuvchi qurilmasidan tashqariga chiqmaydi
- Muallif AI-provayderlar tomonidan ma'lumotlarni qayta ishlashni nazorat qilmaydi va buning uchun javobgar emas

### 11. Ovozli assistent (Muxlisa)

- Ovozli chiqish (`--voice`) faqat Foydalanuvchining aniq so'rovi bo'yicha faollashtiriladi
- To'liq AI-tahlil emas, faqat qisqacha xulosalar ovozli chiqariladi
- Ovozli chiqishdan foydalanganda DT lokal TTS-dvigatel (macOS `say`) dan foydalanadi

---

## III QISM: MAXFIYLIK VA MA'LUMOTLAR

### 12. Ma'lumotlarni yig'ish va qayta ishlash

**Tashqi xizmatlarga uzatiladigan ma'lumotlar:**
- Bozor so'rovlari → TopstepX API, Yahoo Finance, Financial Modeling Prep
- AI-so'rovlar → DeepSeek API, Anthropic API, Google Gemini API (tanlangan provayderga qarab)
- Telegram-bildirishnomalar → Telegram Bot API (bitim raqamlari, balans, PnL)

**Lokal saqlanadigan ma'lumotlar:**
- API kalitlari va tokenlar → muhit o'zgaruvchilari / `.env`
- Savdo jurnali → `TRADING_JOURNAL.md`
- Konfiguratsiya → DT konfiguratsiya fayllari

**Muallif YIG'MAYDI, SAQLAMAYDI va KIRISH IMKONIYATIGA EGA EMAS:**
- Foydalanuvchining savdo tarixi
- Savdo hisobi ma'lumotlari
- Foydalanuvchining API kalitlari
- Foydalanuvchining AI-so'rovlari mazmuni

### 13. Telegram-bildirishnomalar

DT Telegramga bildirishnomalar yuborishi mumkin (ishga tushirish, savdo signallari, Coach sessiyalari natijalari). Bildirishnomalar quyidagilarni o'z ichiga oladi:
- Instrument va savdo harakati
- Balans va PnL
- Savdo darajalari
- Qisqacha tahlil

Telegram-bildirishnomalar DT interfeysining **o'rnini bosmaydi** va «boricha» taqdim etiladi. Bildirishnomaning kechikishi yoki yo'qligi ushbu Kelishuv shartlarining buzilishi hisoblanmaydi.

---

## IV QISM: YAKUNIY QOIDALAR

### 14. Shartlarni o'zgartirish

Muallif istalgan vaqtda ushbu Kelishuv shartlarini o'zgartirish huquqini saqlab qoladi. Yangi versiya nashr etilgan paytdan boshlab kuchga kiradi. O'zgartirishlardan keyin DT dan foydalanishni davom ettirish yangi shartlarga rozilikni anglatadi.

### 15. Aloqa

Ushbu Kelishuv bilan bog'liq barcha masalalar bo'yicha Muallifga murojaat qiling.

### 16. Tan olish

Jafar Pro dan foydalanishni boshlab, Siz quyidagilarni tasdiqlaysiz:
- [ ] Ushbu Kelishuvni o'qidingiz va tushundingiz
- [ ] CME fyucherslari bilan savdo qilish xatarlarini tushunasiz
- [ ] AI-modellar va ularning tavsiyalari cheklovlarini tushunasiz
- [ ] Barcha savdo qarorlari uchun to'liq javobgarlikni o'z zimmangizga olasiz
- [ ] Ma'lumotlarni qayta ishlash shartlariga rozisiz

---

**© 2024–2026 Jafar Pro. Barcha huquqlar himoyalangan.**
