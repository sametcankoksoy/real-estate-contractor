# 🏠 Emlak Sözleşme Asistanı

**Emlak Sözleşme Asistanı**, kira ve alım-satım sözleşmelerini kolayca hazırlayıp `.docx` formatında indirmenizi sağlayan bir **Streamlit** uygulamasıdır.

## 🚀 Özellikler

- 🏢 **Kira Sözleşmesi Oluşturma:**  
  Gerekli bilgileri girerek standart bir kira sözleşmesi ve özel hükümleri içeren belgeyi otomatik olarak oluşturur.

- 🏡 **Emlak Alım-Satım Sözleşmesi Oluşturma:**  
  Taşınmazın ve tarafların bilgilerini girerek ön protokol niteliğinde bir alım-satım sözleşmesi hazırlar.

- 📄 **Word Belgesi İndirme:**  
  Oluşturulan sözleşmeleri anında `.docx` formatında indirebilme imkanı sunar.

## 🛠️ Kurulum ve Çalıştırma

### 🔧 Önkoşullar

  Bu projeyi yerel makinenizde çalıştırmak için aşağıdaki yazılımların kurulu olması gerekmektedir:

- **Python 3.7+**

### ⚙️ Kurulum Adımları

1. **Projeyi klonlayın veya kodu indirin:**
   ```bash
   git clone https://github.com/kullaniciadi/emlak-sozlesme-asistani.git
   cd emlak-sozlesme-asistani
   ```
2. **Gerekli kütüphaneleri yükleyin::**
   ```bash
   pip install streamlit python-docx
   ```
3. **Uygulamayı çalıştırın:**
   ```bash
   streamlit run emlak_asistani.py
   ```

### 💡 Kullanım

Tarayıcınızda açılan Streamlit arayüzünde, üst kısımdaki sekmeler arasında geçiş yaparak istediğiniz sözleşme türünü seçebilirsiniz:

### 🧾 1. Kira Sözleşmesi

- Kiralananın ve tarafların adres, kimlik, kira bedeli gibi tüm bilgilerini girin.
- “Sözleşmeyi Oluştur” butonuna tıklayın.
- Sözleşme oluşturulduktan sonra “Sözleşmeyi indir (Word)” butonuna tıklayarak belgeyi indirin.

### 🏠 2. Alım-Satım Sözleşmesi

- Taşınmazın tapu ve adres bilgilerini (Pafta, Ada, Parsel vb.), alıcı-satıcı bilgilerini ve fiyat detaylarını girin.
- “Sözleşmeyi Oluştur” butonuna basın.
- Görünen “Sözleşmeyi indir (Word)” butonu ile alım-satım ön protokolünü indirin.

### ⚖️ Yasal Uyarı
**Bu uygulama tarafından oluşturulan sözleşmeler, standart şablonlardır ve yalnızca taslak niteliğindedir.
Hukuki geçerliliğin sağlanması ve özel durumlarınıza uygun hale getirilmesi için mutlaka bir avukat tarafından gözden geçirilmelidir.**

**Uygulama geliştiricisi, sözleşmelerin kullanımından doğacak hiçbir sorumluluğu kabul etmez.**

### 📚 Kullanılan Teknolojiler
Streamlit
python-docx
Python Standart Kütüphaneleri

### 👨‍💻 Geliştirici Notu:
**Bu proje, gayrimenkul işlemlerinde sık kullanılan sözleşme metinlerini hızlıca oluşturmak isteyen kullanıcılar için geliştirilmiştir.**
