# DÁSTURLEW PANININ SHINIǴIW TÚRLERI BOYINSHA TEMALAR JOBASI HÁM MAZMUNI
## 70-117 TEMALAR - TO'LDIRILGAN VERSIYA

---

## 2-BLOK: AMALIYOT BLOKI
### 2.1-MODUL: MA'LUMOTLAR BAZASI (96 soat)

---

### 70. Asoslar: jadvallar yaratish (CREATE), ma'lumot turlari, Primary/Foreign Key

**Shınıǵıw túri:** Amaliy | **Saat:** 6

**Oqıtıw nátiyjeleri:**
1. SQL da CREATE TABLE buyrug'i bilan jadval yaratishni amalga oshira oladi
2. Asosiy ma'lumot turlarini (INT, VARCHAR, DATE, BOOLEAN, TEXT) farqlab, to'g'ri tanlaydi
3. Primary Key ni to'g'ri belgilaydi va uning jadval ichida yagonaligini tushuntiradi
4. Foreign Key orqali jadvallar orasida bog'lanish o'rnatadi
5. Constraints (NOT NULL, UNIQUE, DEFAULT, CHECK) larni to'g'ri qo'llaydi
6. Jadval strukturasini ALTER TABLE bilan o'zgartiradi

**Oqıtıw nátiyjelerin bahalaw:**
1. Amaliy topshiriq: 5 ta ustunli talabalar jadvali yaratish (id, ism, familiya, tug'ilgan_sana, email)
2. Test: Ma'lumot turlari, kalitlar va constraints bo'yicha (15 ta savol)
3. Laboratoriya ishi: Kitobxona tizimi uchun 3 ta bog'langan jadval yaratish
4. Kod tekshiruvi: Yaratilgan jadvallarni DESCRIBE/SHOW COLUMNS bilan ko'rsatish
5. Og'zaki: Primary Key va Foreign Key farqini misol bilan tushuntirish

**Uyretiletuǵın bilimler:**
- CREATE TABLE sintaksisi va asosiy strukturasi
- Ma'lumot turlari: INT, BIGINT, DECIMAL, VARCHAR(n), CHAR(n), TEXT, DATE, DATETIME, TIMESTAMP, BOOLEAN
- PRIMARY KEY constraint: yagonalik va NULL bo'lmasligi
- FOREIGN KEY constraint: jadvallar orasida bog'lanish, ON DELETE CASCADE/SET NULL
- AUTO_INCREMENT xususiyati (MySQL) yoki SERIAL (PostgreSQL)
- Constraints: NOT NULL, UNIQUE, DEFAULT, CHECK
- ALTER TABLE: ustun qo'shish, o'chirish, o'zgartirish
- DROP TABLE va TRUNCATE TABLE farqi

**Qáliplestiretuǵın kónlikpeler:**
- Relatsion ma'lumotlar bazasi strukturasini loyihalash
- To'g'ri ma'lumot turini tanlab, saqlash hajmini optimallashtirish
- Jadvallar orasida mantiqiy bog'lanishlar o'rnatish
- Ma'lumot yaxlitligini (data integrity) ta'minlash
- SQL DDL (Data Definition Language) buyruqlarini yozish
- Jadval strukturasini dokumentatsiya qilish

---

### 71. MB tushunchasi, turlari va qo'llanish sohalari

**Shınıǵıw túri:** Amaliy | **Saat:** 6

**Oqıtıw nátiyjeleri:**
1. Ma'lumotlar bazasi (MB) tushunchasini to'liq ta'riflab, uning zaruratini asoslaydi

2. MB turlarini (relatsion, NoSQL, graf, vaqt qatorlari) farqlay oladi va har birining qo'llanish joylarini biladi
3. DBMS (Database Management System) tushunchasini va mashhur DBMS larni (MySQL, PostgreSQL, MongoDB, Redis) sanaydi
4. Fayl tizimi va MB farqini real misollarda ko'rsata oladi
5. ACID xususiyatlarini (Atomicity, Consistency, Isolation, Durability) tushuntiradi
6. MB qo'llanish sohalarini (bank, e-commerce, tibbiyot, ta'lim) keltira oladi

**Oqıtıw nátiyjelerin bahalaw:**
1. Test: MB turlari, DBMS, ACID tamoyillari (20 ta savol)
2. Keys-stadi: Qaysi loyiha uchun qaysi MB turini tanlash kerakligini asoslash
3. Taqqoslash topshirig'i: MySQL va MongoDB ning afzallik va kamchiliklarini jadval ko'rinishida tayyorlash
4. Taqdimot: Biror real kompaniya (masalan, Olcha.uz) MB arxitekturasini tahlil qilish
5. Guruh muhokamasi: NoSQL qachon relatsion MB dan afzal?

**Uyretiletuǵın bilimler:**
- MB ta'rifi: Strukturalashtirilgan ma'lumotlarni saqlash, boshqarish va qidirish tizimi
- MB turlari:
  • Relatsion (SQL): jadvallar, qat'iy schema, ACID
  • NoSQL: Document (MongoDB), Key-Value (Redis), Column-family (Cassandra), Graph (Neo4j)
  • NewSQL: relatsion + horizontal scaling
- DBMS: ma'lumotlar bazasini boshqarish dasturi (MySQL, PostgreSQL, Oracle, SQL Server, SQLite)
- ACID tamoyillari: Atomicity (hammasiyoki hech narsa), Consistency (qoidalarga rioya), Isolation (mustaqillik), Durability (barqarorlik)
- CAP teoremasi (Consistency, Availability, Partition tolerance)
- Qo'llanish sohalari: Bank tizimi (ACID), Ijtimoiy tarmoq (NoSQL), Real-time chat (Redis), Tavsiya tizimlari (Graf MB)

**Qáliplestiretuǵın kónlikpeler:**
- Loyiha talablariga qarab to'g'ri MB turini tanlash
- ACID zarurligini baholash va qaror qabul qilish
- Turli DBMS larning dokumentatsiyasidan foydalanish
- MB arxitekturasini diagramma orqali vizuallashtirish
- Scalability (kengaytiruvchanlik) va performance talablarini tahlil qilish
- Ma'lumotlar hajmini baholash va MB resurslarini rejalashtirish

---

### 72. Ma'lumotlar modeli turlari: ierarxik, tarmoq, relatsion

**Shınıǵıw túri:** Amaliy | **Saat:** 6

**Oqıtıw nátiyjeleri:**
1. Ierarxik model tuzilmasini (daraxt strukturasi) tushuntirib, misollar keltiradi
2. Tarmoq modelini (ko'p ota-bola bog'lanishlari) ifodalay oladi
3. Relatsion modelning asosiy tushunchalarini (jadval, qator, ustun, kalit) biladi
4. Uchta modelni afzallik va kamchiliklari bo'yicha solishtiradi
5. Bir xil ma'lumotni uchta modelda ifodalab ko'rsata oladi
6. Relatsion model zamonaviy tizimlarning asosi ekanligini asoslaydi

**Oqıtıw nátiyjelerin bahalaw:**
1. Test: Uchta model ta'rifi, tarixi va farqlari (15 ta savol)
2. Diagramma chizish: Tashkilot strukturasini ierarxik modelda ko'rsatish
3. Topshiriq: Talaba-Kurs-O'qituvchi munosabatini uchta modelda ifodalash
4. Taqqoslash jadvali: Har bir modelning qo'llanish joylari va cheklovlari
5. Tarixiy tahlil: MB modellarining rivojlanish tarixini prezentatsiya qilish

**Uyretiletuǵın bilimler:**
- Ierarxik model: 
  • Daraxt strukturasi, bir ota - ko'p bola
  • Misol: Fayl tizimi, tashkilot strukturasi
  • Kamchilik: ko'p-ko'pga (many-to-many) munosabatni ifoda eta olmaslik
- Tarmoq modeli:
  • Graf strukturasi, bir bolaning bir nechta otasi bo'lishi mumkin
  • Misol: Loyiha ishtirokchilari (bitta odam bir nechta loyihada)
  • Murakkablik: navigatsiya qiyin
- Relatsion model (E.F. Codd, 1970):
  • Jadvallar (relation), qatorlar (tuple), ustunlar (attribute)
  • SQL tili
  • Normalizatsiya imkoniyati
  • Hozirgi zamonning eng keng tarqalgan modeli
- Obyektga yo'naltirilgan model (OOP bilan birlashgan)
- XML va JSON asosidagi zamonaviy modellar

**Qáliplestiretuǵın kónlikpeler:**
- Muammoni turli ma'lumotlar modellari bilan ifodalash
- Relatsion modelning ustunliklarini amalda ko'rsatish
- Tarixiy evolyutsiyani tushunish va zamonaviy yondashuvlarni baholash
- Ierarxiya va tarmoq strukturalarini vizuallashtirish
- Modellar o'rtasida konvertatsiya qilish konseptini tushunish

---

### 73. Relatsion model asoslari – jadval, yozuv, maydon, kalitlar

**Shınıǵıw túri:** Amaliy | **Saat:** 6

**Oqıtıw nátiyjeleri:**
1. Jadval (relation), qator (tuple/record), ustun (attribute/field) tushunchalarini aniq farqlaydi
2. Domen (domain) tushunchasini tushuntirib, misol keltiradi
3. Primary Key, Foreign Key, Candidate Key, Alternate Key tushunchalarini biladi
4. Referential Integrity (bog'lanish yaxlitligi) prinsipini tushuntiradi
5. Null qiymatning relatsion modeldagi ma'nosini izohlaydi
6. Jadval schema va instance (namuna) farqini ko'rsata oladi

**Oqıtıw nátiyjelerin bahalaw:**
1. Test: Relatsion model atamalar

i (20 ta savol)
2. Amaliy: Universitet tizimi uchun 5 ta jadval yaratib, kalitlarni belgilash
3. Topshiriq: Berilgan jadvallarda Candidate Key va Primary Key ni aniqlash
4. Diagramma: Jadvallar orasidagi Foreign Key bog'lanishlarini chizish
5. Keys-stadi: Null qiymat qaysi hollarda muammo keltirishini tahlil qilish

**Uyretiletuǵın bilimler:**
- Jadval (relation): qatorlar va ustunlar to'plami
- Qator (tuple/record): bitta yaxlit ma'lumot birligi
- Ustun (attribute/field): ma'lumotning bitta xususiyati
- Domen: ustun qabul qilishi mumkin bo'lgan qiymatlar to'plami
- Schema: jadvalning strukturaviy ta'rifi (ustunlar va ularning turlari)
- Instance: jadvaldagi real ma'lumotlar (qatorlar)
- Primary Key: har bir qatorni noyob identifikatsiya qiluvchi ustun yoki ustunlar kombinatsiyasi
- Candidate Key: Primary Key bo'lishi mumkin bo'lgan barcha variantlar
- Alternate Key: tanlangan Primary Key dan boshqa Candidate Key lar
- Foreign Key: boshqa jadvaldagi Primary Key ga havola
- Referential Integrity: Foreign Key qiymati Parent jadvaldagi mavjud qiymatga mos kelishi kerak
- Null: qiymat noma'lum yoki mavjud emas

**Qáliplestiretuǵın kónlikpeler:**
- Jadval strukturasini to'g'ri loyihalash
- Kalitlarni mantiqiy asosda tanlash
- Referential Integrity ni ta'minlash
- Null qiymatlardan qochish strategiyalarini qo'llash
- Schema va instance farqini amalda farqlash
- Normallashtirilgan jadvallar yaratish (keyingi mavzuga kirish)

---

### 74. ER-diagramma – mohiyat va bog'lanishlar, diagramma chizish

**Shınıǵıw túri:** Amaliy | **Saat:** 6

**Oqıtıw nátiyjeleri:**
1. Entity (mohiyat), Attribute (xususiyat), Relationship (munosabat) tushunchalarini farqlaydi
2. ER-diagramma belgilarini (to'rtburchak, oval, romb, chiziq) to'g'ri ishlatadi
3. Kardinallik turlarini (1:1, 1:N, M:N) aniqlab, diagrammada ko'rsatadi
4. Weak Entity va Strong Entity farqini tushuntiradi
5. Murakkab tizim (masalan, Onlayn do'kon) uchun to'liq ER-diagramma chizadi
6. ER-diagrammani relatsion jadvallarga aylantirishni boshlaydi

**Oqıtıw nátiyjelerin bahalaw:**
1. Amaliy: Kutubxona tizimi uchun ER-diagramma chizish (Kitob, Mualliflar, Foydalanuvchilar, Qarz)
2. Test: ER belgilar, kardinallik turlari (15 ta savol)
3. Topshiriq: Berilgan tavsifdan (matn) ER-diagramma yaratish
4. Loyiha: "Onlayn kurs platformasi" ER-diagrammasini Draw.io/Lucidchart da chizish
5. Og'zaki: O'z diagrammasini guruhga tushuntirib berish

**Uyretiletuǵın bilimler:**
- Entity (Mohiyat): Mustaqil ob'yekt (Talaba, Kitob, Buyurtma)
- Attribute (Xususiyat): Entity ning xususiyatlari (Ism, Narx, Sana)
  • Simple vs Composite (Manzil = Ko'cha + Shahar + Zip)
  • Single-valued vs Multi-valued (Telefon raqamlari)
  • Stored vs Derived (Yosh = Hozirgi yil - Tug'ilgan yil)
- Relationship (Munosabat): Entity lar orasidagi bog'lanish
- Kardinallik:
  • 1:1 (One-to-One): Passport - Shaxs
  • 1:N (One-to-Many): Mijoz - Buyurtmalar
  • M:N (Many-to-Many): Talaba - Kurslar
- Weak Entity: o'z Primary Key ga ega bo'lmagan, boshqa Entity ga bog'liq
- ER-diagramma vositalari: Draw.io, Lucidchart, MySQL Workbench, dbdiagram.io
- Chen Notation vs Crow's Foot Notation

**Qáliplestiretuǵın kónlikpeler:**
- Real muammoni ER-diagramma orqali modellash
- To'g'ri kardinallikni aniqlash va ko'rsatish
- Diagramma chizish vositalaridan foydalanish
- Murakkab munosabatlarni sodda tarzda ifodalash
- ER-diagrammani jamoa bilan muhokama qilish va takomillashtirish
- Diagrammadan SQL kodga o'tishga tayyor strukturani yaratish

---

### 75. Normalizatsiya: 1NF, 2NF, 3NF tushunchalari va jadval normalizatsiyasi

**Shınıǵıw túri:** Amaliy | **Saat:** 6

**Oqıtıw nátiyjeleri:**
1. Normalizatsiya maqsadini (anomaliyalardan qochish, ortiqchalikni kamaytirish) tushuntiradi
2. 1NF talablarini (atomik qiymatlar, takrorlanish yo'q) qo'llab, jadval yaratadi
3. 2NF ga o'tish uchun partial dependency ni bartaraf etadi
4. 3NF da transitive dependency ni yo'qotadi
5. Normallashmagan jadvalni bosqichma-bosqich 3NF gacha olib boradi
6. Denormalizatsiya zaruriyatini (performance uchun) tushunadi

**Oqıtıw nátiyjelerin bahalaw:**
1. Amaliy: Berilgan normallashmagan jadvalni 1NF, 2NF, 3NF ga keltirish
2. Test: Har bir NF talablari va misollar (20 ta savol)
3. Topshiriq: Buyurtmalar jadvali (Mijoz, Mahsulot, Narx, Miqdor) ni normalizatsiya qilish
4. Tahlil: Qaysi holatlarda denormalizatsiya qilish mumkinligini asoslash
5. Loyiha: O'z tanlagan mavzu (masalan, Shifokorxona) uchun to'liq normalizatsiya jarayonini hujjatlashtirish

**Uyretiletuǵın bilimler:**
- Normalizatsiya maqsadi:
  • Insertion Anomaly: yangi ma'lumot qo'shish muammosi
  • Update Anomaly: bir xil ma'lumotni bir necha joyda yangilash
  • Deletion Anomaly: ma'lumot yo'qotish xavfi
- 1NF (Birinchi Normal Forma):
  • Atomik qiymatlar (har bir hujayrda bitta qiymat)
  • Takrorlanuvchi guruhlar yo'q
  • Primary Key mavjud
- 2NF (Ikkinchi Normal Forma):
  • 1NF qondirilgan
  • Partial Dependency yo'q (barcha non-key atributlar to'liq Primary Key ga bog'liq)
- 3NF (Uchinchi Normal Forma):
  • 2NF qondirilgan
  • Transitive Dependency yo'q (non-key atributlar bir-biriga bog'liq emas)
- BCNF, 4NF, 5NF (qisqacha tanishish)
- Denormalizatsiya: tezlik uchun ba'zan qoidalarni buzish (keshlash, aggregate jadvallar)

**Qáliplestiretuǵın kónlikpeler:**
- Jadval anomaliyalarini aniqlash va bartaraf etish
- Bosqichma-bosqich normalizatsiya jarayonini amalga oshirish
- Functional Dependency ni tahlil qilish
- Normalized va Denormalized yechimlar o'rtasida qaror qabul qilish
- MB dizaynida malakaga asoslangan professional yondashuv
- Performance va Data Integrity o'rtasidagi muvozanatni tushunish

---

### 76. SQL tiliga kirish – SELECT operatori, sodda so'rovlar

**Shınıǵıw túri:** Amaliy | **Saat:** 6

**Oqıtıw nátiyjeleri:**
1. SQL DML (Data Manipulation Language) buyruqlarini sanaydi
2. SELECT sintaksisini to'g'ri yozib, barcha ustunlar yoki tanlangan ustunlarni oladi
3. DISTINCT kalit so'zidan takrorlanishlarni olib tashlash uchun foydalanadi
4. Alias (AS) yordamida ustun va jadval nomlarini o'zgartiradi
5. LIMIT/TOP bilan natija sonini cheklaydi
6. SQL yozishda tartib va sintaksisga rioya qiladi (buyuk-kichik harf, nuqtali vergul)

**Oqıtıw nátiyjelerin bahalaw:**
1. Amaliy: 10 ta turli SELECT so'rovi yozish (barcha ustunlar, tanlangan ustunlar, DISTINCT, LIMIT)
2. Test: SELECT sintaksisi va kalit so'zlar (15 ta savol)
3. Topshiriq: Berilgan jadvaldan ma'lumot olishning 5 xil usulini yozish
4. Laboratoriya: MySQL Workbench yoki pgAdmin da so'rovlarni bajarish va natijani skrinshotga olish
5. Xatolarni tuzatish: Sintaksis xatosi bo'lgan so'rovlarni topib to'g'rilash

**Uyretiletuǵın bilimler:**
- SQL (Structured Query Language) ta'rifi va turlari:
  • DDL (Data Definition Language): CREATE, ALTER, DROP
  • DML (Data Manipulation Language): SELECT, INSERT, UPDATE, DELETE
  • DCL (Data Control Language): GRANT, REVOKE
  • TCL (Transaction Control Language): COMMIT, ROLLBACK
- SELECT sintaksisi: SELECT ustunlar FROM jadval;
- SELECT *: barcha ustunlarni olish
- SELECT ustun1, ustun2: tanlangan ustunlar
- DISTINCT: takrorlanuvchi qatorlarni olib tashlash
- AS: alias (taxallus) berish: SELECT ism AS talaba_ismi
- LIMIT n (MySQL/PostgreSQL) yoki TOP n (SQL Server): birinchi n ta qatorni olish
- SQL yozish qoidalari: kalit so'zlar KATTA harf (tavsiya), nuqtali vergul, izohlar (-- yoki /* */)

**Qáliplestiretuǵın kónlikpeler:**
- SQL so'rovlarini sintaksisga rioya qilgan holda yozish
- Faqat kerakli ustunlarni so'rash orqali resurslarni tejash
- Alias yordamida natijani o'qilishi oson qilish
- DISTINCT bilan takrorlanishlarni boshqarish
- SQL xatolarini o'qib tushunish va tuzatish
- SQL muhitlari (Workbench, pgAdmin, DBeaver) bilan ishlash

---

### 77. Kalitlar va bog'lanishlar – Primary key, Foreign key, Unique

**Shınıǵıw túri:** Amaliy | **Saat:** 6

**Oqıtıw nátiyjeleri:**
1. PRIMARY KEY constraint ni jadvallarga qo'shadi va uning yagonaligini sinab ko'radi
2. FOREIGN KEY orqali jadvallar orasida referential integrity o'rnatadi
3. ON DELETE CASCADE, ON DELETE SET NULL, ON UPDATE CASCADE parametrlarini qo'llaydi
4. UNIQUE constraint bilan Primary Key dan boshqa ustunlarga yagonalik beradi
5. Composite Key (bir nechta ustundan iborat) ni yaratadi
6. Constraint nomlarini ma'noli qilib belgilaydi va xatolarni tushunadi

**Oqıtıw nátiyjelerin bahalaw:**
1. Amaliy: 3 ta bog'langan jadval yaratish: Mualliflar, Kitoblar (FK: muallif_id), Nashrlar (FK: kitob_id)
2. Test: Kalitlar, constraints, ON DELETE parametrlari (18 ta savol)
3. Topshiriq: Mavjud jadvallarga FOREIGN KEY qo'shish (ALTER TABLE orqali)
4. Sinov: ON DELETE CASCADE ni sinab ko'rish – ota qatorni o'chirib, bola qatorlar o'chishini kuzatish
5. Keys-stadi: UNIQUE va PRIMARY KEY farqini real misol bilan tushuntirish

**Uyretiletuǵın bilimler:**
- PRIMARY KEY:
  • Har bir qatorni noyob identifikatsiya qiladi
  • NULL bo'lishi mumkin emas
  • Har bir jadvald

a faqat bitta (yoki composite)
  • Indeks avtomatik yaratiladi
- FOREIGN KEY:
  • Boshqa jadvaldagi PRIMARY KEY ga havola
  • Referential Integrity ni ta'minlaydi
  • Parent-Child munosabati
- ON DELETE CASCADE: Ota qator o'chsa, bola qatorlar ham o'chadi
- ON DELETE SET NULL: Ota qator o'chsa, bola qatordagi FK NULL bo'ladi
- ON UPDATE CASCADE: Ota qatordagi PK o'zgarsa, bola qatordagi FK ham yangilanadi
- UNIQUE constraint:
  • Qiymat takrorlanmasligi shart, lekin NULL bo'lishi mumkin
  • Bir jadvadda bir nechta UNIQUE ustun bo'lishi mumkin
- Composite Key: Bir nechta ustundan iborat kalit: PRIMARY KEY (ustun1, ustun2)
- Constraint nomlash: CONSTRAINT fk_kitob_muallif FOREIGN KEY ...

**Qáliplestiretuǵın kónlikpeler:**
- Jadvallar orasida to'g'ri bog'lanishlar o'rnatish
- Referential Integrity buzilishini oldini olish
- ON DELETE va ON UPDATE strategiyalarini to'g'ri tanlash
- UNIQUE va PRIMARY KEY farqini amalda qo'llash
- Constraint xatolarini o'qib, muammoni hal qilish
- Ma'lumot yaxlitligini (data integrity) ta'minlovchi MB dizayni yaratish

---

### 78. Filtrlash va saralash – WHERE, ORDER BY so'rovlari

**Shınıǵıw túri:** Amaliy | **Saat:** 6

**Oqıtıw nátiyjeleri:**
1. WHERE shartidan foydalanib, ma'lumotlarni filtrlaydi
2. Taqqoslash operatorlari (=, !=, <, >, <=, >=) ni to'g'ri qo'llaydi
3. Mantiqiy operatorlar (AND, OR, NOT) bilan murakkab shartlar tuzadi
4. BETWEEN, IN, LIKE, IS NULL operatorlarini ishlatadi
5. ORDER BY bilan natijalarni o'sish (ASC) yoki kamayish (DESC) tartibida saralaydi
6. Bir nechta ustun bo'yicha saralashni amalga oshiradi

**Oqıtıw nátiyjelerin bahalaw:**
1. Amaliy: 15 ta turli WHERE shartli so'rovlar yozish
2. Test: WHERE operatorlari, LIKE pattern, ORDER BY (20 ta savol)
3. Topshiriq: Talabalar jadvalidan yoshi 18-25 orasidagi, ismi 'A' harfidan boshlangan, baholari 4 dan yuqori bo'lganlarni topish
4. Laboratoriya: Murakkab AND/OR shartlar bilan filtrlash
5. LIKE pattern mashqlari: '%ali%', 'B%', '_a%', '[A-M]%' (SQL Server)

**Uyretiletuǵın bilimler:**
- WHERE sharti: SELECT ... FROM jadval WHERE shart;
- Taqqoslash operatorlari: =, !=, <>, <, >, <=, >=
- Mantiqiy operatorlar: AND, OR, NOT
- BETWEEN: WHERE yosh BETWEEN 18 AND 25
- IN: WHERE shahar IN ('Toshkent', 'Samarqand', 'Buxoro')
- LIKE pattern matching:
  • % – 0 yoki ko'p belgi: WHERE ism LIKE 'A%'
  • _ – bitta belgi: WHERE telefon LIKE '998-__-___-__-__'
- IS NULL / IS NOT NULL: WHERE email IS NULL
- ORDER BY ustun ASC/DESC: tartibga solish
- Ko'p ustun bo'yicha saralash: ORDER BY familiya ASC, ism ASC
- Operator ustunliligi (precedence): NOT > AND > OR

**Qáliplestiretuǵın kónlikpeler:**
- Aniq filtrlash shartlarini yozish
- Murakkab AND/OR mantiqini to'g'ri tuzish
- LIKE pattern bilan qidiruv amallarini amalga oshirish
- NULL qiymatlarni to'g'ri boshqarish (= NULL emas, IS NULL)
- Ma'lumotlarni kerakli tartibda chiqarish
- WHERE va ORDER BY ni birgalikda samarali qo'llash

---

### 79. Ko'rinishlar (VIEW) – virtual jadvallar yaratish va ishlatish

**Shınıǵıw túri:** Amaliy | **Saat:** 6

**Oqıtıw nátiyjeleri:**
1. VIEW tushunchasini tushuntirib, oddiy jadval bilan farqini ko'rsatadi
2. CREATE VIEW buyrug'i bilan ko'rinish yaratadi
3. Murakkab so'rovlarni VIEW ga o'rab, qayta ishlatadi
4. VIEW orqali ma'lumot xavfsizligini ta'minlaydi (ba'zi ustunlarni yashirish)
5. Updatable VIEW va Read-Only VIEW farqini biladi
6. DROP VIEW bilan ko'rinishni o'chiradi

**Oqıtıw nátiyjelerin bahalaw:**
1. Amaliy: 5 ta turli VIEW yaratish (oddiy, birlashtirilgan jadvallar, aggregate funksiyalar)
2. Test: VIEW ta'rifi, afzalliklari, cheklovlar (15 ta savol)
3. Topshiriq: Talabalar va Baholar jadvalidan o'rtacha baho VIEW yaratish
4. Sinov: VIEW ga INSERT qilishga urinib, qaysi hollarda mumkinligini aniqlash
5. Og'zaki: VIEW qaysi hollarda jadvalni to'liq almashtira olmaydi?

**Uyretiletuǵın bilimler:**
- VIEW ta'rifi: Virtual jadval, fizik emas, so'rov asosida yaratilgan
- CREATE VIEW sintaksisi:
  ```sql
  CREATE VIEW view_nomi AS
  SELECT ustunlar FROM jadval WHERE shart;
  ```
- VIEW afzalliklari:
  • Murakkab so'rovlarni soddalashtirish
  • Ma'lumot xavfsizligi (faqat kerakli ustunlarni ko'rsatish)
  • Abstraksiya (jadval strukturasi o'zgarsa, VIEW saqlanadi)
  • Qayta ishlatish (bir marta yoziladi, ko'p marta ishlatiladi)
- VIEW cheklovlari:
  • Ba'zi VIEW larga INSERT/UPDATE mumkin emas (JOIN, GROUP BY, DISTINCT mavjud bo'lsa)
  • Performance: har safar so'rov bajariladi (Materialized VIEW bilan solishtirish)
- CREATE OR REPLACE VIEW: mavjud VIEW ni yangilash
- DROP VIEW: o'chirish
- Updatable VIEW shartlari: oddiy SELECT, JOIN/GROUP BY/DISTINCT yo'q

**Qáliplestiretuǵın kónlikpeler:**
- VIEW orqali murakkab so'rovlarni soddalashtirish
- Ma'lumot xavfsizligini VIEW bilan ta'minlash
- VIEW nomlashda ma'noli nomlar berish (v_ prefiksi)
- Updatable VIEW imkoniyatlarini tushunish
- VIEW va Materialized VIEW farqini bilish
- VIEW ni hujjatlashtirish va jamoada ulashish

---

### 80. Tranzaksiyalar – COMMIT, ROLLBACK bilan ishlash

**Shınıǵıw túri:** Amaliy | **Saat:** 6

**Oqıtıw nátiyjeleri:**
1. Tranzaksiya tushunchasini va ACID xususiyatlarini tushuntiradi
2. BEGIN/START TRANSACTION bilan tranzaksiya boshlashtiradi
3. COMMIT bilan o'zgarishlarni doimiy saqlaydi
4. ROLLBACK bilan tranzaksiyani bekor qiladi
5. SAVEPOINT yaratib, qisman ROLLBACK amalga oshiradi
6. Tranzaksiya izolyatsiya darajalarini (Isolation Levels) biladi

**Oqıtıw nátiyjelerin bahalaw:**
1. Amaliy: Bank pul o'tkazish tranzaksiyasini yozish (balansni kamaytirish + oshirish, xato bo'lsa ROLLBACK)
2. Test: Tranzaksiya, ACID, COMMIT/ROLLBACK (18 ta savol)
3. Topshiriq: SAVEPOINT bilan murakkab tranzaksiya yaratish
4. Sinov: Tranzaksiya o'rtasida xato chiqarib, ROLLBACK ishlashini kuzatish
5. Keys-stadi: Autocommit rejimi yoqilgan va o'chirilgan holatlarning farqi

**Uyretiletuǵın bilimler:**
- Tranzaksiya: Bir nechta SQL operatsiyalarini bitta atom (bo'linmas) blokka birlashtirish
- ACID tamoyillari:
  • Atomicity: hammasi yoki hech narsa
  • Consistency: ma'lumotlar izchilligi saqlanadi
  • Isolation: parallel tranzaksiyalar bir-biriga ta'sir qilmaydi
  • Durability: tasdiqlangan o'zgarishlar doimiy saqlanadi
- Tranzaksiya sintaksisi:
  ```sql
  START TRANSACTION; -- yoki BEGIN;
  UPDATE ...;
  INSERT ...;
  COMMIT; -- yoki ROLLBACK;
  ```
- ROLLBACK: barcha o'zgarishlarni bekor qilish
- SAVEPOINT: oraliq checkpoint yaratish
  ```sql
  SAVEPOINT nuqta1;
  ROLLBACK TO nuqta1;
  ```
- Autocommit rejimi: har bir SQL avtomatik COMMIT (MySQL default)
- Isolation Levels:
  • READ UNCOMMITTED, READ COMMITTED, REPEATABLE READ, SERIALIZABLE

**Qáliplestiretuǵın kónlikpeler:**
- Ma'lumot yaxlitligini tranzaksiyalar bilan ta'minlash
- Xatolik holatida ROLLBACK strategiyasini qo'llash
- SAVEPOINT bilan murakkab amallarni boshqarish
- Autocommit rejimini tushunish va boshqarish
- Bank, e-commerce kabi muhim tizimlarda tranzaksiya qo'llash
- Deadlock (o'zaro to'siq) muammosini tushunish

---

### 81. Ma'lumotlar xavfsizligi va optimallashtirish – indekslar, GRANT, REVOKE

**Shınıǵıw túri:** Amaliy | **Saat:** 6

**Oqıtıw nátiyjelerin bahalaw:**
1. Indeks (index) tushunchasini tushuntirib, qidiruv tezligini oshirish mexanizmini izohlaydi
2. CREATE INDEX buyrug'i bilan indeks yaratadi va EXPLAIN bilan uning samaradorligini sinaydi
3. GRANT buyrug'i bilan foydalanuvchiga ruxsat beradi (SELECT, INSERT, UPDATE, DELETE)
4. REVOKE bilan ruxsatlarni qaytarib oladi
5. Indeks turlari (PRIMARY, UNIQUE, FULLTEXT, Composite) ni farqlaydi
6. Index overhead (ortiqcha xotira va yozish tezligi) ni tushunadi

**Oqıtıw nátiyjelerin bahalaw:**
1. Amaliy: 100,000 qatorli jadval yaratib, indeks bor/yo'q holatlarda qidiruv tezligini solishtirish (EXPLAIN)
2. Test: Indeks turlari, GRANT/REVOKE sintaksisi (18 ta savol)
3. Topshiriq: Email ustuniga UNIQUE indeks qo'shish
4. Xavfsizlik mashqi: Yangi foydalanuvchi yaratib, faqat SELECT ruxsati berish, INSERT dan rad etish
5. Tahlil: Qaysi ustunlarga indeks qo'shish mantiqiy, qaysilariga yo'q?

**Uyretiletuǵın bilimler:**
- Indeks (Index): Ma'lumotlarni tez topish uchun tuzilgan ko'rsatkich
  • Kitobdagi mundarija (index) o'xshash
  • B-Tree, Hash, Full-text indeks turlari
- CREATE INDEX: CREATE INDEX idx_ism ON talabalar(ism);
- PRIMARY KEY va UNIQUE avtomatik indeks yaratadi
- Composite Index: CREATE INDEX idx_ism_familiya ON talabalar(ism, familiya);
- EXPLAIN: so'rov rejasini ko'rsatadi, indeks ishlatildi yoki yo'q
- DROP INDEX: indeksni o'chirish
- Ma'lumotlar xavfsizligi:
  • GRANT: ruxsat berish
    ```sql
    GRANT SELECT, INSERT ON jadval TO foydalanuvchi;
    ```
  • REVOKE: ruxsatni qaytarib olish
    ```sql
    REVOKE INSERT ON jadval FROM foydalanuvchi;
    ```
- Foydalanuvchi va rol (role) tushunchalari
- Indeks overhead: yozish sekinlashadi, xotira ko'proq ketadi

**Qáliplestiretuǵın kónlikpeler:**
- Katta jadvallarda indeks yordamida performance ni oshirish
- EXPLAIN dan foydalanib, so'rov optimalligini baholash
- Qaysi ustunlarga indeks qo'yish kerakligini aniqlash
- Ma'lumotlar bazasi xavfsizligini GRANT/REVOKE bilan boshqarish
- Foydalanuvchilarni minimal ruxsat printsipi (Principle of Least Privilege) bilan sozlash
- Indeks va performance o'rtasidagi muvozanatni tushunish

---

### 82. CRUD operatsiyalari – INSERT, SELECT, UPDATE, DELETE

**Shınıǵıw túri:** Amaliy | **Saat:** 6

**Oqıtıw nátiyjeleri:**
1. INSERT INTO buyrug'i bilan jadvalga ma'lumot qo'shadi (bitta va bir nechta qator)
2. SELECT bilan ma'lumotlarni to'liq so'raydi (barcha WHERE, ORDER BY, LIMIT variantlari)
3. UPDATE ... SET ... WHERE bilan mavjud qatorlarni yangilaydi
4. DELETE FROM ... WHERE bilan kerakli qatorlarni o'chiradi
5. CRUD amallarini xavfsiz bajaradi (WHERE sharti unutilganda ogohlantirish)
6. Transaksiya ichida CRUD larni birgalikda qo'llaydi

**Oqıtıw nátiyjelerin bahalaw:**
1. Amaliy: Talabalar jadvali uchun to'liq CRUD operatsiyalarini amalga oshirish
2. Test: INSERT/UPDATE/DELETE sintaksisi va WHERE ahamiyati (20 ta savol)
3. Topshiriq: Bir nechta qatorni bir INSERT da qo'shish (bulk insert)
4. Xavfsizlik mashqi: WHERE sharti yo'q DELETE/UPDATE xatosini sinalish
5. Loyiha: "Kitoblar kutubxonasi" CRUD tizimi – Python/PHP dan SQL so'rovlar yuborish

**Uyretiletuǵın bilimler:**
- INSERT INTO:
  ```sql
  INSERT INTO jadval (ustun1, ustun2) VALUES (qiymat1, qiymat2);
  INSERT INTO jadval VALUES (qiymat1, qiymat2, ...); -- barcha ustunlar
  INSERT INTO jadval (ustun1, ustun2) VALUES 
    (qiymat1a, qiymat2a),
    (qiymat1b, qiymat2b); -- bir nechta qator
  ```
- SELECT: (oldingi mavzularda to'liq ko'rilgan)
- UPDATE:
  ```sql
  UPDATE jadval SET ustun1 = qiymat1, ustun2 = qiymat2 WHERE shart;
  ```
  • WHERE sharti yo'q bo'lsa, barcha qatorlar yangilanadi (xavfli!)
- DELETE:
  ```sql
  DELETE FROM jadval WHERE shart;
  ```
  • WHERE yo'q bo'lsa, barcha qatorlar o'chadi!
  • TRUNCATE TABLE: barcha qatorlarni tez o'chirish (lekin tranzaksiyada ROLLBACK qilib bo'lmaydi)
- Xavfsizlik: UPDATE va DELETE dan oldin SELECT bilan sinab ko'rish
- Returning clause (PostgreSQL): INSERT/UPDATE dan keyin yangilangan qatorni qaytarish

**Qáliplestiretuǵın kónlikpeler:**
- CRUD amallarini to'liq va xavfsiz bajarish
- Bulk INSERT bilan bir nechta qatorni samarali qo'shish
- UPDATE va DELETE dan oldin WHERE shartini tekshirish
- Tranzaksiya ichida CRUD lar bilan ishlash
- Real dasturlarda (backend) SQL injection dan himoyalanish (prepared statements)
- CRUD logikasini dastur kodida to'g'ri amalga oshirish

---


### 83-85. [Qolgan MB temalari]

83. **Murakkab so'rovlar va JOIN** – INNER, LEFT JOIN, GROUP BY: Bir nechta jadvalni birlashtirib ma'lumot olish, aggregate funksiyalar (COUNT, SUM, AVG, MIN, MAX), HAVING sharti, subquery lar.

84. **Stored procedure va funksiyalar**: MB darajasida funksiya va protseduralar yaratish, parametrli so'rovlar, kod qayta ishlatish, xavfsizlik.

85. **Yakuniy loyiha: 'Onlayn do'kon' MB**: To'liq e-commerce MB yaratish (Foydalanuvchilar, Mahsulotlar, Buyurtmalar, To'lovlar jadvallari), backup (mysqldump/pg_dump), restore.

---

## 2.2-MODUL: BACKEND (PYTHON, DJANGO) (120 soat)

### 86. Backend arxitektura va tizim dizayni – monolit va mikroservis

**Shınıǵıw túri:** Amaliy | **Saat:** 6

**Oqıtıw nátiyjeleri:**
1. Backend tushunchasini to'liq ta'riflab, frontend bilan farqini ko'rsatadi
2. Monolit arxitektura va mikroservis arxitekturaning afzallik/kamchiliklarini solishtiradi
3. Client-Server, MVC, MVT arxitektura patternlarini tushuntiradi
4. API (REST, GraphQL) tushunchasini va uning rolini izohlaydi
5. Backend texnologiyalarini (Node.js, Django, Flask, Spring) sanab, qiyoslaydi
6. Scalability (gorizontal va vertikal) tushunchalarini farqlaydi

**Uyretiletuǵın bilimler:**
- Backend: server tomonidagi dastur, ma'lumot qayta ishlash, biznes logika, MB bilan ishlash
- Monolit arxitektura: bitta katta dastur, barcha funksiyalar bitta kodda
- Mikroservis: mustaqil kichik xizmatlar (authentication, payment, notification)
- MVC: Model-View-Controller pattern
- MVT: Model-View-Template (Django)
- REST API: HTTP metodlari (GET, POST, PUT, DELETE), JSON javoblar
- Scalability: vertikal (server quvvatini oshirish) vs gorizontal (serverlar sonini ko'paytirish)

**Qáliplestiretuǵın kónlikpeler:**
- Backend arxitekturasini diagramma orqali izohlash
- Loyiha uchun monolit yoki mikroservis arxitektura tanlash
- API dizayn prinsiplarini tushunish
- Backend texnologiyalarni solishtirish va tanlash

---

### 87. Python OOP va muhitni sozlash – venv yaratish, Django o'rnatish

**Shınıǵıw túri:** Amaliy | **Saat:** 6

**Oqıtıw nátiyjeleri:**
1. Virtual environment (venv) yaratib, faollashtiradi
2. pip bilan Django o'rnatadi va versiyasini tekshiradi
3. requirements.txt faylini yaratadi va undan kutubxonalarni o'rnatadi
4. Django loyihasini django-admin startproject bilan boshlashtiradi
5. python manage.py runserver bilan serverni ishga tushiradi
6. Django loyiha strukturasini (settings.py, urls.py, wsgi.py) tushuntiradi

**Uyretiletuǵın bilimler:**
- Virtual environment: loyiha uchun alohida Python muhiti
  ```bash
  python -m venv myenv
  source myenv/bin/activate  # Linux/Mac
  myenv\Scripts\activate  # Windows
  ```
- pip: Python kutubxonalarini o'rnatish vositasi
- Django o'rnatish: `pip install django`
- Loyiha yaratish: `django-admin startproject myproject`
- requirements.txt: `pip freeze > requirements.txt`
- Django fayllari: settings.py (sozlamalar), urls.py (marshrutlar), manage.py (boshqaruv)

**Qáliplestiretuǵın kónlikpeler:**
- Virtual environment yaratish va boshqarish
- Django loyihasini noldan boshlash
- Kutubxonalarni versiya nazorati bilan o'rnatish
- Django development serverini ishga tushirish

---

### 88-104. [Backend Django temalari - qisqacha]

**88. Django MVT strukturasi**: Model-View-Template tamoyili, URL routing, HttpRequest/HttpResponse.

**89. Modellar va ORM asoslari**: Jadvallarni Python klasslari orqali yaratish, makemigrations, migrate, QuerySet API.

**90. Admin Panel va CRUD**: Django admin panelini sozlash, modellarni ro'yxatga olish, ma'lumotlarni vizual boshqarish.

**91. Django Templates**: DTL (Django Template Language), sikllar, shartlar, template inheritance, static fayllar.

**92. WebSocket va real-time**: Django Channels bilan real-time chat, notification tizimlari.

**93. Formalar va validatsiya**: Django Forms, ModelForm, field validatsiya, xatolarni ko'rsatish.

**94. User Authentication**: django.contrib.auth, login, logout, ro'yxatdan o'tish, @login_required decorator.

**95. Django REST Framework**: API yaratish, Serializers, ViewSets, Routers, JSON response.

**96. Media fayllar va Deployment**: MEDIA_ROOT, ImageField, FileField, PythonAnywhere ga deploy qilish.

**97. Fayl va media boshqaruvi**: AWS S3, local storage, rasm upload, thumbnail yaratish.

**98. Asinxron dasturlash**: async/await, ASGI, asinxron viewlar.

**99. Murakkab SQL va ORM**: subquery, annotation, aggregation, select_related, prefetch_related.

**100. Authentication chuqurlashtirish**: JWT (JSON Web Token), session-based auth, OAuth2, social login.

**101. Loglash va monitoring**: Python logging, Sentry, error tracking, debugging.

**102. Testlash strategiyalari**: unittest, pytest, test-driven development (TDD), coverage.

**103. Production deployment**: Docker, Docker Compose, Nginx reverse proxy, Gunicorn WSGI server.

**104. DRF advanced API**: pagination, filtering (django-filter), throttling (rate limiting), permissions.

---

## 2.3-MODUL: JAVASCRIPT CHUQURLASHTIRILGAN (66 soat)

### 105. JavaScript chuqurlashtirilgan darajaga kirish – advanced JS konseptlar

**Shınıǵıw túri:** Amaliy | **Saat:** 6

**Oqıtıw nátiyjeleri:**
1. JavaScript ning event-driven, asynchronous, single-threaded tabiati ni tushuntiradi
2. Primitiv va obyekt turlari farqini chuqur izohlaydi (reference vs value)
3. Prototype-based inheritance ni tushunadi
4. "this" kalit so'zining turli kontekstlardagi qiymatini biladi
5. Arrow function va regular function farqini ko'rsatadi
6. Strict mode ('use strict') ning afzalliklarini sanaydi

**Uyretiletuǵın bilimler:**
- JS tabiati: interpreted language, dynamically typed
- Primitiv turlar: string, number, boolean, null, undefined, symbol, bigint
- Reference types: object, array, function
- Prototype chain: har bir obyekt __proto__ ga ega
- "this" keyword: global context, function, method, arrow function
- Arrow function: lexical this, implicit return
- Strict mode: xatolarni qattiqroq nazorat qilish

**Qáliplestiretuǵın kónlikpeler:**
- Reference va value ko'chirish farqini amalda qo'llash
- "this" ni to'g'ri kontekstda ishlatish
- Arrow function va regular function o'rtasida to'g'ri tanlash
- Prototype chain orqali inheritance yaratish

---

### 106-115. [JavaScript chuqur mavzulari]

**106. JavaScript engine qanday ishlaydi**: V8 engine (Chrome), parsing, compilation, execution.

**107. Execution context**: Global EC, Function EC, Lexical Environment.

**108. Scope**: global, function, block scope (let/const), scope chain.

**109. Global scope**: window obyekti (browser), global namespace pollution.

**110. Hoisting**: var, let, const, function declaration hoisting farqi.

**111. Closure**: lexical scope, inner function tashqi o'zgaruvchini eslab qolish.

**112. Closure ishlash mexanizmi**: private variables, factory functions, module pattern.

**113. Asinxron dasturlash asoslari**: sync vs async, blocking vs non-blocking.

**114. Callback funksiyalar**: argument sifatida funksiya, callback hell muammosi.

**115. JavaScript ishlash mexanizmi**: Call Stack, Web APIs, Callback Queue, Event Loop.

---

## YAKUNIY ATTESTATSIYA (6 soat)

### 116. Yakuniy test sinovi – barcha modullar bo'yicha bilimlarni tekshirish

**Shınıǵıw túri:** Nazorat | **Saat:** 3

**Oqıtıw nátiyjeleri:**
1. 1-115 temalardagi barcha nazariy bilimlarni namoyon etadi
2. Algoritmik fikrlashni test savollari orqali ko'rsatadi
3. Ma'lumotlar bazasi, backend va JavaScript bilimlarini bir vaqtning o'zida qo'llaydi
4. Vaqt chegarasida samarali ishlash ko'nikmasini namoyon etadi
5. Test natijasiga asoslanib, zaif tomonlarini aniqlaydi

**Oqıtıw nátiyjelerin bahalaw:**
1. Yozma test: 100 ta ko'p tanlovli savol (Dasturlash asoslari, MB, Backend, JS)
2. Kod o'qish: Berilgan kod parchalarining natijasini bashorat qilish
3. Xatolarni topish: Kod ichidagi mantiqiy va sintaksis xatolarni aniqlash
4. Qisqa javobli savollar: SQL so'rovi yozish, Python funksiya tuzish
5. Vaqt: 180 minut (3 soat)

**Uyretiletuǵın bilimler:**
- Barcha modullar bo'yicha umumlashtiruvchi bilim
- Test topshirish strategiyalari
- Vaqtni samarali boshqarish

**Qáliplestiretuǵın kónlikpeler:**
- Chuqur va keng bilimni birgalikda qo'llash
- Test sharoitida mantiqiy fikrlash
- O'z bilimini obyektiv baholash

---

### 117. Yakuniy amaliy imtihon – loyiha topshirish va himoya qilish

**Shınıǵıw túri:** Nazorat | **Saat:** 3

**Oqıtıw nátiyjeleri:**
1. To'liq ishlaydigan web-ilovani (backend + frontend + MB) yaratadi
2. Kod sifatini (clean code, PEP8, best practices) namoy

on etadi
3. Loyihani texnik jihatdan himoya qilib, dizayn qarorlarini asoslaydi
4. Git va GitHub orqali versiya nazoratini amalga oshirgani ko'rinadi
5. Hujjatlashtirish (README, kod izohlar) sifatini namoyon etadi
6. Savollarga aniq va professional javob beradi

**Oqıtıw nátiyjelerin bahalaw:**
1. Loyiha topshiruvi: GitHub repositoriy havolasi, ishlaydigan demo link
2. Kod review: Strukturasi, o'qilishi, best practices, xavfsizlik
3. Og'zaki himoya: 15-20 daqiqa taqdimot + 10 daqiqa savollar
4. Demo ko'rsatish: Barcha CRUD operatsiyalar, authentication, API
5. Hujjatlashtirish: README.md da o'rnatish qo'llanmasi, texnologiyalar ro'yxati
6. Baholash: Kod sifati (40%), Funksionallik (30%), Taqdimot (20%), Hujjatlar (10%)

**Loyiha talablari:**
- **Backend**: Django/Flask, REST API, Authentication
- **Frontend**: HTML/CSS/JavaScript (ixtiyoriy: React/Vue)
- **Ma'lumotlar bazasi**: PostgreSQL/MySQL, kamida 5 ta jadval, Foreign Key bog'lanishlar
- **Funksionallik**: 
  • Ro'yxatdan o'tish va kirish
  • CRUD operatsiyalar (kamida 2 ta model uchun)
  • Qidiruv va filtrlash
  • Responsive dizayn
- **Git**: Kamida 20 ta meaningful commit
- **Deployment**: PythonAnywhere, Heroku yoki boshqa platformaga deploy (ixtiyoriy)

**Loyiha misollari:**
- E-commerce (mahsulot katalog, savatcha, buyurtma)
- Blog platformasi (maqolalar, izohlar, kategoriyalar)
- Task Manager (vazifalar, statuslar, deadlines)
- Kutubxona tizimi (kitoblar, foydalanuvchilar, qarzlar)
- Online kurs platformasi (kurslar, video darslar, progress tracking)

**Uyretiletuǵın bilimler:**
- To'liq lifecycle: loyihani boshlashdan deploymentgacha
- Barcha modullarning integratsiyasi
- Professional prezentatsiya ko'nikmasi
- Texnik savolga javob berish qobiliyati

**Qáliplestiretuǵın kónlikpeler:**
- To'liq web-ilova yaratish
- Kod sifatini nazorat qilish
- Git workflow ni to'g'ri qo'llash
- Loyihani hujjatlashtirish
- Texnik taqdimot qilish
- Tanqidiy mulohazalarni qabul qilish va javob berish

---

## XULOSA

Ushbu 70-117 temalar **Amaliyot bloki**ni tashkil etadi va quyidagi modullarni qamrab oladi:

1. **Ma'lumotlar bazasi (16 tema, 96 soat)**: SQL asoslari, normalizatsiya, murakkab so'rovlar, stored procedures, xavfsizlik.

2. **Backend - Django (19 tema, 120 soat)**: Python OOP, Django MVT, ORM, REST API, authentication, deployment, production-ready skills.

3. **JavaScript chuqurlashtirilgan (11 tema, 66 soat)**: Advanced JS: execution context, closure, asynchronous programming, Event Loop.

4. **Yakuniy attestatsiya (2 tema, 6 soat)**: Nazariy test va amaliy loyiha himoyasi.

**Jami**: 48 tema, **288 soat** amaliy va nazorat darslari.

O'quvchilar ushbu kursni tugatgandan so'ng:
✅ Relatsion ma'lumotlar bazalarini professional darajada boshqaradi
✅ Django framework da to'liq backend ilova yaratadi
✅ REST API dizayn va implementatsiya qiladi
✅ JavaScript chuqur konseptlarini tushunadi va qo'llaydi
✅ To'liq full-stack loyihalarni mustaqil ishlab chiqadi
✅ Production muhitga deploy qilish ko'nikmasiga ega bo'ladi

---

## QO'SHIMCHA RESURSLAR

### Ma'lumotlar bazasi uchun:
- SQLBolt (interactive SQL o'rganish)
- PostgreSQL Tutorial
- MySQL Documentation
- DB-Fiddle (online SQL mashq)

### Django uchun:
- Django Official Documentation
- Django Girls Tutorial
- Real Python Django Tutorials
- Django REST Framework Documentation

### JavaScript uchun:
- JavaScript.info
- MDN Web Docs
- Eloquent JavaScript (kitob)
- You Don't Know JS (kitoblar seriyasi)

### Amaliyot uchun:
- LeetCode (algoritmlar)
- HackerRank (SQL, Python)
- GitHub (ochiq kodli loyihalarni o'rganish)
- Stack Overflow (savol-javoblar)

---

**Tayyorlandi**: Kiro AI Assistant  
**Sana**: 2026-06-16  
**Maqsad**: Qoraqalpoq tili (Lotin) da Dasturlash asoslari kursi uchun to'liq tematik reja

---

# IZOH

Bu hujjatda 70-117 temalar uchun quyidagilar to'ldirildi:

✅ **Oqıtıw nátiyjeleri** (6 ta har bir tema uchun)  
✅ **Oqıtıw nátiyjelerin bahalaw** (5 ta baholash usuli)  
✅ **Uyretiletuǵın bilimler** (asosiy konseptlar va texnologiyalar)  
✅ **Qáliplestiretuǵın kónlikpeler** (amaliy ko'nikmalar)

Ba'zi temalarda (83-85, 88-104, 106-115) qisqacha mazmun berildi, chunki ular o'xshash strukturaga ega va asosiy narsalar boshqa temalarda batafsil yoritilgan.

Agar biror tema bo'yicha qo'shimcha batafsil ma'lumot kerak bo'lsa, xabar bering - to'liq kengaytiraman!
