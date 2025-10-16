# Hastane Chatbot - PDF Tabanlı NLP Projesi

Bu proje, bir hastanenin PDF dökümanındaki tüm bilgileri kullanarak **soru-cevap (Q&A) chatbot** oluşturmayı amaçlamaktadır. OpenAI GPT-3.5-turbo modeli ile entegre edilmiştir ve PDF içeriğinden en ilgili parçayı bularak kullanıcının sorularına doğru ve kısa cevaplar üretir.

---

## 🚀 Özellikler

- PDF’den metin çıkarma ve parçalara bölme (chunking)
- Kullanıcı sorusuna en ilgili metin parçasını bulma
- OpenAI GPT-3.5-turbo ile sorulara cevap üretme
- Farklı soruları test etmek için otomatik soru listesi
- Basit ve düşük maliyetli çözüm

---

## 🛠 Kurulum

1. Python 3.10 veya üzeri yükleyin.
2. Gerekli kütüphaneleri yükleyin:

```bash
pip install --upgrade openai PyMuPDF tiktoken
