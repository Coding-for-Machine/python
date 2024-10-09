
| class          | shakli                                             |
| -------------- | ---------------------------------------------------|
| bool           | True yoki False                                    |
| int            | Butun sonlar                                       |
| ﬂoat           | Haqiqiy sonlar                                     |
| list           | Ro'yxat(ob'ektlarning o'zgaruvchan ketma-ketligi)  |
| tuple          | ob'ektlarning o'zgarmas ketma-ketligi              |
| str            | belgilar qatori                                     |
| set            | alohida ob'ektlarning tartibsiz to'plami            |
| frozenset      | to'plam sinfining o'zgarmas shakli                  |
| dict           | assotsiativ xaritalash (aka lug'at)                 |

## 1-Python uchun tez-tez ishlatiladigan o'rnatilgan sinflar
<br>

### Ro'yxat List sinf
Ro'yxat namunasi ob'ektlar ketma-ketligini saqlaydi. Ro'yxat xuddi o'zi kabi yo'naltiruvchi tuzilmadir
texnik jihatdan uning elementlariga havolalar ketma-ketligini saqlaydi (1.4-rasmga qarang). El-
ro'yxat elementlari ixtiyoriy ob'ektlar bo'lishi mumkin (jumladan, None ob'ekti). Ro'yxatlar
massivga asoslangan ketma-ketliklar va nol indekslangan, shuning uchun n uzunlikdagi ro'yxat elementlarga ega
0 dan n - 1 gacha indekslangan. Ro'yxatlar, ehtimol, eng ko'p ishlatiladigan konteyner turi
Python va ular bizning ma'lumotlar tuzilmalari va algoritmlarini o'rganishda juda muhim bo'ladi.
ritmlar. Ular juda ko'p qimmatli xatti-harakatlarga ega, shu jumladan dinamik qobiliyatga ega
kerak bo'lganda o'z imkoniyatlarini kengaytiradi va qisqartiradi. Ushbu bobda biz faqat muhokama qilamiz
ro'yxatlarning eng asosiy xususiyatlari. Biz barcha Python-ning ichki ishini qayta ko'rib chiqamiz
ketma-ketlik turlari 5-bobning diqqat markazida.
Python [ ] belgilaridan roʻyxat harfi uchun chegaralovchi sifatida foydalanadi, oʻzi esa [ ]
bo'sh ro'yxat. Yana bir misol sifatida, [ qizil , yashil , ko'k ] o'z ichiga olgan ro'yxatdir
uchta qatorli misollar. Literal ro'yxatining mazmuni literal sifatida ifodalanishi shart emas;
a va b identifikatorlari o'rnatilgan bo'lsa, [a, b] sintaksisi qonuniydir.
list( ) konstruktori sukut bo'yicha bo'sh ro'yxat hosil qiladi. Biroq, qurilish-
tor takrorlanadigan turdagi har qanday parametrni qabul qiladi. Biz iteratsiyani muhokama qilamiz
Keyinchalik 1.8-bo'limda keltirilgan, ammo takrorlanadigan turlarga misollar barcha standart shartlarni o'z ichiga oladi.
tayner turlari (masalan, satrlar, ro'yxatlar, kortejlar, to'plamlar, lug'atlar). Masalan, sintaksis
list( hello ) alohida belgilar roʻyxatini ishlab chiqaradi, [ h , e , l , l , o ].
Mavjud ro'yxatning o'zi takrorlanishi mumkinligi sababli, sintaksis zaxirasi = ro'yxat (ma'lumotlar) bo'lishi mumkin
original bilan bir xil tarkibga havola qiluvchi yangi ro'yxat namunasini yaratish uchun ishlatiladi.

![image](https://github.com/user-attachments/assets/aebbce4f-dee0-439a-8d6b-aa53d58ea57a)

### 1.4-rasm: Pythonning butun sonlar roʻyxatining ichki koʻrinishi.
tub = [2, 3, 5, 7, 11, 13, 17, 19, 23, 29, 31]. Elementlarning yashirin indekslari
mentlar har bir yozuv ostida ko'rsatilgan.
<br>

## Tuple klassi
Tuple klassi ketma-ketlikning o'zgarmas versiyasini taqdim etadi va shuning uchun uning
misollar ichki ko'rinishga ega bo'lib, u yanada soddalashtirilgan bo'lishi mumkin
ro'yxat. Python roʻyxatni chegaralash uchun [ ] belgilaridan foydalansa, qavslar a chegarasini belgilaydi
kortej, ( ) bo'sh kortej bo'ladi. Bitta muhim noziklik bor. ifodalash uchun
literal sifatida bir uzunlikdagi kortej, elementdan keyin vergul qo'yilishi kerak, lekin
qavslar ichida. Masalan, (17,) bir elementli kortejdir. Buning sababi
bu talab shundan iboratki, keyingi vergulsiz ifoda (17) ko'riladi
oddiy qavs ichidagi sonli ifoda sifatida.
