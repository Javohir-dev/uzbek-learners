# GitHub-da `repo` ochish va `clone` qilish
### Barcha savollaringizni shu [Uzbek Learners | Chat](https://t.me/uzbek_learners_team)da bering albatta javob olasiz.

Bu berilgan ketmaketlikni bajarishingiz uchun sizda Git va GitHub account bo'lishi shart.

## `Repo` ochish

- [GitHub](https://github.com/)gadagi sahifangizga kiring.
- Repositories bo'limiga o'ting
- `New` tugmasiga bosing
- Repository name* ga yaratmoqchi bo'lgan loyihangiz uchun nom yozing
- Kerakli sozlamalardan keyin `Create repository` tugmasiga bosing

## `Clone Repository`

Loyihani yuklab olish uchun kerakli papkaga kiring va shu joyda terminal ochib quyidagi buyruqlarni birma-bir kiriting.
- `Git bash`ni ochish uchun kerakli joyga borib sichqonchani o'ng tugmasini bosasiz
- `Open Git Bash here`ni bosasiz.

![Folders](https://avatars.mds.yandex.net/get-images-cbir/1957816/RM7RLFKt0ty8nQ66ohRCcw2659/ocr)
- `~ $` lar shunchaki buyruqlar chunarli bo'lishi uchun qo'yilgan, buni terminalga yozmaysiz.

```bash
~ $ git remote add origin https://github.com/sahifangiz-nomi/loyihangiz-nomi.git
~ $ git branch -M master
~ $ git push -u origin master
```
Quyidagi buyruq shu loyihangizni `VSCode` ichida ochib beradi.
```shell
~ $ code .
```
# O'zgarishlarni `GitHub`ga yuklash
- O'zingiz istagan terminalganni loyiha ichida ochasiz
- Quyidagi buyruqlarni birma-bir kiritasiz

```bash
~ $ git add .
~ $ git commit -m "Qilgan ishingiz haqida izoh"
~ $ git push origin master
```
## Natija:
![Git Buyruqlari](https://avatars.mds.yandex.net/get-images-cbir/1769266/9DRrbjFyHXm_sNeXSkxflA3587/ocr)
- `git add .` **O'z Kompyuteringizdagi `git`ga o'zgarishlarni o'shadi**
- `git commit -m "Qilgan ishingiz haqida izoh"` **Shu o'zgarishlarga nom berib saqlaydi**
- `git push origin master` **Saqlanganlarini `master` branchida yuboradi**