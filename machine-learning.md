
# <p align="center">Machine Learning</p>
###### <div dir="rtl">یہ اصطلاح دراصل کسی پروگرامر کی جانب سے لکھی گئی کوڈ ( یا مزید بہتر انداز میں کہیں تو    Set of Algorithms)    کے لیے استعمال ہوتی ہے ۔ یہ      Set of Algorithms    وہ ہوتے ہیں جو کہ آپ کے پاس دستیاب مواد (یعنی ڈیٹا) پہ اپنی تربیت کرتے ہیں اور پھر اصل ڈیٹا کے اوپر استعمال ہونے کے بعد یہ     Prediction    کرتے ہیں اور  ان کی اس     Prediction کے وجہ سے جس نظام یعنی     System     میں بھی یہ کام کررہے ہوتے ہیں انہیں فائدہ ہوتا ہے ۔ </div>

###### <div dir="rtl">اگر آپ     Machine Learning     کے بارے میں مزید جاننا چاہتے ہیں تو انٹرنیٹ پہ اس موضوع پہ بے تحاشہ مواد موجود ہے ۔ </div>

### <p align="center">Supervised Machine Learning</p>
###### <div dir="rtl">مختصر طور پہ یوں کہا جائے گا کہ یہ     مشین لرننگ     کی وہ قسم ہے جس کا انحصار اس بات پہ ہوتا ہے کہ آپ کے پاس پہلے سے ماضی کا ڈیٹا دستیاب ہو اور اس ڈیٹا کو لے کر آپ اس کی خصوصیات   Features کا اندازہ لگائیں اور پھر اس کے اوپر اپنی جانب سے     مشین لرننگ   کے مختلف      Algorithms    استعمال کریں اور پھر یہ دیکھیں کہ کون سی Technique  یعنی آپ کا استعمال کردہ     Algorithm    آپ کو وہ  نتیجہ لا کردے رہا ہے جو کہ ماضی کے ریکارڈ کیے گئے ڈیٹا میں موجود نتائج سے قریب تر ہے ۔ جب آپ کو قریبی نتائج حاصل ہوجائیں تو پھر آپ کو اپنے بنائے ہوئے     Machine Learning Model کو    Test Data     پہ Applyکرنا ہوتا ہے ۔ </div>
###### <div dir="rtl">اس کا آسان سا طریقہ یہ ہوتا ہے کہ آپ کے پاس ماضی کا ڈیٹا اور اس کے نتائج دستیاب ہیں ۔ آپ نے اس ڈیٹا کو دو حصوں میں بانٹ دیا ۔ فرض کیا کہ 30 فیصد     Training Data     اور 70 فیصد     Test Data۔ </div>
###### <div dir="rtl">اس کے بعد آپ    Training Data     پہ اپنے     Machine Learning Model  کو استعمال کرکے مختلف قسم کی تکنیک لگائیں گے اور نتائج اخذ کریں گے ۔ جب آپ کا یہ نظام پختہ ہوجائے گا۔ تو آپ اس      Machine Learning Model کو   70 فیصد والے     Test Dataپہ استعمال ہوگا۔ </div>
###### <div dir="rtl">جب نتائج آجائیں گے تو پھر آپ مختلف طریقوں سے ان نتائج کو جانچیں گے ۔ جیسے     Confusion Matrix   اور   Accuracy Scoreوغیرہ۔ </div>
###### <div dir="rtl">جب آپ کے اخذ کردہ نتائج ، پہلے سے موجودہ نتائج کے قریب تر ہوں ۔ فرض کریں کہ 95 فیصد ہوں  (یاد رہے کہ یہ آپ پہ منحصر ہے کہ آپ اپنے پراجیکٹ اور جس شعبہ میں آپ کام کررہے ہیں ۔ اس میں کامیابی کا معیار 95 فیصد ہے یا اس سے کم) تو آپ اس کا کامیابی تصور کرتے ہوئے اپنے بنائے ہوئے     Machine Learning Model کو     Production    میں  Deploy کردیتے ہیں </div>

### <p align="center">Un-Supervised Machine Learning</p>
###### <div dir="rtl">یہ     Machine Learning     کی وہ قسم ہے جس کی تربیت کرنے کے لیے آپ کے پاس ماضی کا ڈیٹا دستیاب نہیں ہوتا ہے بلکہ یہ ایک Unsupervised Machine Learning کے تحت اپنی تربیت آپ کرتی ہے ۔   Topic Modelingبھی اسی کہ ایک قسم ہے ۔ہم اب اس کا جائزہ لیں گے اور اس کی چند Coding Examples    دیکھیں گے ۔</div>

- [Main Page](README.md)
- [What is Topic Modeling](topic-modeling.md)
