# دور دراز ریپوزٹریوں کے ساتھ تعاون

- [ریموٹ ریپوزٹریوں کو ترتیب دینا (GitHub, GitLab, Bitbucket)](#ریموٹ-ریپوزٹریوں-کو-ترتیب-دینا-github-gitlab-bitbucket)
- [گِٹ ہب (GitHub)](#گِٹ-ہب-github)
- [گِٹ لیب (GitLab)](#گِٹ-لیب-gitlab)
- [بِٹ بَکٹ (Bitbucket)](#بِٹ-بَکٹ-bitbucket)
- [ریموٹ ریپوزٹریوں سے تبدیلیاں بھیجنا اور حاصل کرنا](#ریموٹ-ریپوزٹریوں-سے-تبدیلیاں-بھیجنا-اور-حاصل-کرنا)
- [مرج تنازعات کو سنبھالنا](#مرج-تنازعات-کو-سنبھالنا)
- [بہترین طریقے](#بہترین-طریقے)

## ریموٹ ریپوزٹریوں کو ترتیب دینا (GitHub, GitLab, Bitbucket)

سافٹ ویئر ڈیولپمنٹ کی دنیا میں، ورژن کنٹرول سسٹمز کوڈ ریپوزٹریوں کا نظم و نسق کرنے، تعاون کو آسان بنانے اور ٹیم ممبرز کے درمیان ورک فلو کو ہموار کرنے میں اہم کردار ادا کرتے ہیں۔ گِٹ ہب، گِٹ لیب اور بِٹ بَکٹ جیسے پلیٹ فارمز پر ہوسٹ کی گئی ریموٹ ریپوزٹریاں ڈویلپرز کو ایک مرکزی مقام فراہم کرتی ہیں جہاں وہ اپنے کوڈ کو اسٹور، منظم اور شیئر کر سکتے ہیں۔ اس مضمون میں، ہم ان تینوں پلیٹ فارمز پر ریموٹ ریپوزٹری کو ترتیب دینے کے مرحلہ وار طریقہ کار کو تفصیل سے بیان کریں گے۔

### گِٹ ہب (GitHub)

گِٹ ہب گِٹ ورژن کنٹرول کے لیے سب سے زیادہ مقبول ویب بیسڈ ہوسٹنگ پلیٹ فارم میں سے ایک ہے۔ گِٹ ہب پر ریموٹ ریپوزٹری سیٹ اپ کرنے کا تفصیلی طریقہ:

**مرحلہ 1:** گِٹ ہب اکاؤنٹ بنائیں  
اگر آپ کے پاس پہلے سے اکاؤنٹ نہیں ہے، تو [github.com](https://github.com) پر جا کر سائن اپ کریں۔

**مرحلہ 2:** نئی ریپوزٹری بنائیں  
لاگ ان ہونے کے بعد، گِٹ ہب ڈیش بورڈ کے اوپری دائیں کونے میں موجود "+ New" بٹن پر کلک کریں۔ اپنی ریپوزٹری کے لیے ایک نام فراہم کریں، ایک اختیاری تفصیل شامل کریں، اور فیصلہ کریں کہ آیا یہ پبلک ہوگی یا پرائیویٹ۔

**مرحلہ 3:** ریپوزٹری کو ابتدائی بنائیں  
ریپوزٹری بنانے کے بعد، آپ کے پاس یہ اختیار ہوگا کہ آپ اسے README فائل کے ساتھ ابتدائی بنائیں، جو اکثر تجویز کیا جاتا ہے۔ README فائل آپ کے پروجیکٹ کے بارے میں بنیادی معلومات فراہم کرتی ہے۔

**مرحلہ 4:** ریپوزٹری کو کلون کریں (اختیاری)  
اگر آپ اپنے کمپیوٹر پر مقامی طور پر ریپوزٹری کے ساتھ کام کرنا چاہتے ہیں، تو درج ذیل گِٹ کمانڈ استعمال کریں:  

```bash
git clone <repository_url>
```

### گِٹ لیب (GitLab)

گِٹ لیب ایک اور مقبول ویب بیسڈ گِٹ ریپوزٹری مینیجر ہے جو وسیع فیچرز فراہم کرتا ہے۔ گِٹ لیب پر ریموٹ ریپوزٹری سیٹ اپ کرنے کا طریقہ:

**مرحلہ 1:** گِٹ لیب اکاؤنٹ بنائیں  
[gitlab.com](https://gitlab.com) پر جا کر سائن اپ کریں اگر آپ کا اکاؤنٹ نہیں ہے۔

**مرحلہ 2:** نیا پروجیکٹ بنائیں  
لاگ ان ہونے کے بعد، ڈیش بورڈ پر "New Project" بٹن پر کلک کریں۔ ایک نام فراہم کریں، ایک اختیاری تفصیل شامل کریں، اور اپنے پروجیکٹ کی ویزیبلٹی (پبلک، انٹرنل، یا پرائیویٹ) کا انتخاب کریں۔

**مرحلہ 3:** ریپوزٹری کو ابتدائی بنائیں  
گِٹ ہب کی طرح، آپ یہاں بھی ریپوزٹری کو README فائل کے ساتھ ابتدائی بنا سکتے ہیں۔

**مرحلہ 4:** ریپوزٹری کو کلون کریں (اختیاری)  
اگر آپ اپنے کمپیوٹر پر مقامی طور پر کام کرنا چاہتے ہیں تو درج ذیل گِٹ کمانڈ استعمال کریں:  

```bash
git clone <repository_url>
```

### بِٹ بَکٹ (Bitbucket)

بِٹ بَکٹ، جس کا مالک Atlassian ہے، گِٹ ریپوزٹریوں کی ہوسٹنگ کے لیے ایک اور مقبول پلیٹ فارم ہے۔ بِٹ بَکٹ پر ریموٹ ریپوزٹری سیٹ اپ کرنے کے مراحل:

**مرحلہ 1:** بِٹ بَکٹ اکاؤنٹ بنائیں  
[bitbucket.org](https://bitbucket.org) پر جا کر سائن اپ کریں۔

**مرحلہ 2:** نئی ریپوزٹری بنائیں  
لاگ ان کے بعد، بِٹ بَکٹ ڈیش بورڈ پر "Create repository" بٹن پر کلک کریں۔ ایک نام، اختیاری تفصیل فراہم کریں، اور رسائی کی سطح (پبلک یا پرائیویٹ) منتخب کریں۔

**مرحلہ 3:** ریپوزٹری کی قسم منتخب کریں  
بِٹ بَکٹ آپ کو گِٹ یا مرکوریئل ریپوزٹری بنانے کا انتخاب دیتا ہے۔ یہاں "Git" کو منتخب کریں۔

**مرحلہ 4:** ریپوزٹری کو ابتدائی بنائیں  
دیگر پلیٹ فارمز کی طرح یہاں بھی آپ README فائل کے ساتھ ابتدائی بنا سکتے ہیں۔

**مرحلہ 5:** ریپوزٹری کو کلون کریں (اختیاری)  
اگر آپ اپنے کمپیوٹر پر کام کرنا چاہتے ہیں تو درج ذیل کمانڈ استعمال کریں:  

```bash
git clone <repository_url>
```

## ریموٹ ریپوزٹریوں سے تبدیلیاں بھیجنا اور حاصل کرنا

گِٹ میں تبدیلیاں بھیجنے (push) اور حاصل کرنے (pull) کے عمل کا بنیادی مقصد یہ ہے کہ ٹیم کے تمام اراکین کا کوڈ اپ ڈیٹ اور ہم آہنگ رہے۔  

**تبدیلیاں بھیجنے کے لیے:**

1. اپنی لوکل ریپوزٹری میں تبدیلیاں محفوظ کریں:  
```bash
git commit -m "آپ کی تبدیلی کا خلاصہ"
```

2. ریموٹ ریپوزٹری چیک کریں:  
```bash
git remote -v
```

3. تبدیلیاں بھیجیں:  
```bash
git push origin main
```

**تبدیلیاں حاصل کرنے کے لیے:**

1. پہلے اپنی تبدیلیاں محفوظ کریں:  
```bash
git commit -m "لوکل تبدیلیاں محفوظ"
```

2. ریموٹ سے تبدیلیاں لائیں:  
```bash
git fetch origin
```

3. تبدیلیاں ضم کریں:  
```bash
git merge origin/main
```

## مرج تنازعات کو سنبھالنا

اگر ریموٹ اور لوکل ریپوزٹری میں ایک ہی لائنز میں تبدیلیاں کی گئی ہوں تو گِٹ تنازعات کو خودکار طور پر حل نہیں کر سکتا۔

1. متصادم فائل کھولیں اور تنازعہ حل کریں۔
2. تنازعات کے نشانات کو ہٹائیں۔
3. تبدیلیاں محفوظ کریں:  
```bash
git commit -m "تنازعہ حل"
```

## بہترین طریقے

- ہمیشہ **پُش کرنے سے پہلے پُل** کریں۔  
- **چھوٹے، منطقی کمیٹس** بنائیں۔  
- **فیچر برانچز** استعمال کریں۔  
- **کوڈ ریویو** کریں۔  
- **مسلسل انضمام (CI)** کا استعمال کریں۔
