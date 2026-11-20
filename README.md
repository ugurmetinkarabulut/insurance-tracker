# Insurance Tracker v1.5

## Türkçe

Insurance Tracker, sigorta acenteleri için geliştirilmiş bir masaüstü uygulamasıdır. Bir müşterinin hangi poliçelerinin bulunduğunu, son yenileme görüşmesinde ne konuşulduğunu ve ne kadar borcu kaldığını aynı uygulamada takip edebilirsiniz. Uygulama JavaFX ile çalışır ve kayıtları bilgisayarınızdaki SQLite veritabanında saklar.

### Güne başlarken

Ana ekranda yaklaşan poliçe vadelerini ve takip bekleyen işleri gözden geçirin. Örneğin, önümüzdeki 30 gün içinde poliçesi bitecek müşterileri filtreleyebilir, sık kullandığınız filtreyi kaydedebilir ve gün içinde yeniden görüşeceğiniz müşterileri ana ekrana sabitleyebilirsiniz. Aşağıdaki ekran görüntüleri örnek kayıtlarla alınmıştır. Tam boy görmek için görsele tıklayın.

[![Ana ekranda poliçe vadeleri ve takip listesi](docs/screenshots/ana-ekran.png)](docs/screenshots/ana-ekran.png)

### Müşteri ve poliçe dosyası

Müşteriyi ad, T.C. kimlik numarası veya telefonla arayın. Müşteri özetinde iletişim bilgilerini, notları, poliçeleri ve açık bakiyeyi birlikte görün. Buradan WhatsApp mesajı hazırlayabilir, müşteri adına yeni poliçe açabilir veya tahsilat kaydedebilirsiniz.

Poliçe listesinde portföyün tamamını inceleyebilir veya tek bir müşteriye geçebilirsiniz. Seçtiğiniz poliçenin sigorta şirketini, primini, vadesini ve bağlı PDF belgesini sağ panelde görebilirsiniz. Evrak kontrol listesi, hangi belgelerin teslim alındığını ve hangilerinin eksik kaldığını gösterir.

[![Poliçe listesi ve seçili poliçenin ayrıntıları](docs/screenshots/policeler.png)](docs/screenshots/policeler.png)

### Tekliften yenilemeye

Yenileme panosu poliçeleri **Bekliyor**, **Teklif verildi**, **Onaylandı**, **Yenilendi** ve **Kaybedildi** aşamalarında gösterir. Müşteriye sunduğunuz teklifi, görüşmenin sonucunu ve bir sonraki arama tarihini kaydedebilirsiniz. Müşteri teklifi kabul ettiğinde yeni dönemi mevcut poliçeden başlatabilir, şirketi, primi ve bitiş tarihini güncelleyebilirsiniz. Önceki dönemin teklifleri, belgeleri ve mali kayıtları eski poliçede saklanır.

[![Beş aşamalı yenileme panosu](docs/screenshots/yenileme-panosu.png)](docs/screenshots/yenileme-panosu.png)

### Tahsilatlar, taksitler ve gün sonu

Tahsilatlar ekranında açık hesabı olan müşteriyi bulup ödeme tarihini ve tutarını kaydedin. Ödeme müşteri bakiyesine yansır. Örneğin, müşteri borcunun bir kısmını bugün ödüyorsa tahsilatı kaydedebilir, kalan bakiye için aylık taksit planı oluşturabilirsiniz. Plan üzerinden kısmi ödemeleri ve vadesi geçen taksitleri izleyebilirsiniz.

Gün sonunda **Gün özeti** ekranından seçtiğiniz tarihte kaydedilen poliçeleri, yenilemeleri ve tahsilatları inceleyin. Yönetim panelinde ise dönem boyunca tahsilatların nasıl değiştiğini ve primlerin sigorta branşlarına göre dağılımını görebilirsiniz.

[![Açık müşteri hesapları ve tahsilat ekranı](docs/screenshots/tahsilatlar.png)](docs/screenshots/tahsilatlar.png)

### Excel aktarımı, çıktılar ve yedekleme

- **Excel’den aktarım.** Portföy dosyanızdaki sayfaları seçin ve sütunları müşteri veya poliçe alanlarıyla eşleştirin. Kaydetmeden önce değişecek değerleri önizlemede kontrol edin. Atlanan satırları ve nedenlerini CSV raporunda inceleyebilirsiniz.
- **Müşteriye verilecek belgeler.** Teklifleri ve taksit planlarını acentenizin iletişim bilgileriyle PDF olarak hazırlayabilir, aylık poliçe listesini Excel’e aktarabilirsiniz.
- **Erişim ve yedekleme.** İlk kurulumda yönetici hesabınızı oluşturun. Yönetici ve çalışan rolleri farklı işlem yetkilerine sahiptir. Uygulama açıkken günlük otomatik yedek alabilir. Yedek, kayıtlarla birlikte bağlı poliçe belgelerini de içerir.

### Ticari lisans

Insurance Tracker ticari bir üründür. Kullanım, dağıtım ve kaynak koduna erişim geliştiricinin yazılı iznine tabidir. [Lisans koşulları](LICENSE)

### İletişim

Demo, lisans ve iş birliği talepleriniz için geliştirici **Uğur Metin Karabulut** ile iletişime geçebilirsiniz.

- **E-posta** · [ugurmetinkarabulut@gmail.com](mailto:ugurmetinkarabulut@gmail.com)
- **LinkedIn** · [Uğur Metin Karabulut](https://www.linkedin.com/in/uğur-metin-karabulut-a16106340/)

---

## English

Insurance Tracker is a desktop application for insurance agencies. You can see which policies a customer holds, what you discussed during the last renewal call, and how much they still owe, all in one place. The application runs on JavaFX and stores records in a local SQLite database on your computer.

### Start of day

Use the home screen to review upcoming policy expirations and outstanding follow-ups. For example, you can filter for customers whose policies expire in the next 30 days, save that filter, and pin customers you plan to call again later in the day. The screenshots below use sample records. Select an image to see it at full size.

[![Home screen showing policy expirations and follow-ups](docs/screenshots/ana-ekran.png)](docs/screenshots/ana-ekran.png)

### Customer and policy records

Find a customer by name, Turkish national ID number, or phone number. The customer summary brings together contact details, notes, policies, and the outstanding balance. From there you can draft a WhatsApp message, create a policy for the customer, or record a payment.

Browse the full policy portfolio or narrow the list to one customer. The side panel shows the selected policy’s insurer, premium, expiration date, and attached PDF. The document checklist shows which documents the agency has received and which are still missing.

[![Policy list and details of the selected policy](docs/screenshots/policeler.png)](docs/screenshots/policeler.png)

### From quote to renewal

The renewal board groups policies into five stages: **Pending**, **Quoted**, **Approved**, **Renewed**, and **Lost**. Record the quote you offered, the outcome of the conversation, and the next call date. When the customer accepts, you can start a new term from the existing policy and update the insurer, premium, and expiration date. The previous term’s quotes, documents, and financial records stay with the original policy.

[![Renewal board showing the five stages](docs/screenshots/yenileme-panosu.png)](docs/screenshots/yenileme-panosu.png)

### Payments, instalments, and end-of-day review

Find a customer with an outstanding balance on the collections screen and enter the payment date and amount. The payment updates the customer’s balance. For example, if a customer pays part of their debt today, you can record it and set up monthly instalments for the remaining amount. The plan lets you track partial payments and overdue instalments.

At the end of the day, open the **Daily summary** to review policies recorded, renewals, and payments for your chosen date. The admin dashboard shows how collections changed over the period and how premiums break down by line of insurance.

[![Outstanding customer balances and collections screen](docs/screenshots/tahsilatlar.png)](docs/screenshots/tahsilatlar.png)

### Excel imports, exports, and backups

- **Import from Excel.** Select the worksheets in your portfolio file and map the columns to customer or policy fields. Preview the values that will change before saving. The CSV report lists skipped rows and explains why they were skipped.
- **Customer documents.** Generate PDF quotes and instalment schedules with your agency’s contact details, or export the monthly policy list to Excel.
- **Access and backups.** Create an administrator account during setup. Administrators and employees have different permissions. The application can create daily backups while it is running. Each backup includes the records and their linked policy documents.

### Commercial licence

Insurance Tracker is a commercial product. Use, distribution, and access to the source code require written permission from the developer. [Licence terms](LICENSE)

### Contact

For a demo, licensing enquiries, or collaboration, contact the developer, **Uğur Metin Karabulut**.

- **Email** · [ugurmetinkarabulut@gmail.com](mailto:ugurmetinkarabulut@gmail.com)
- **LinkedIn** · [Uğur Metin Karabulut](https://www.linkedin.com/in/uğur-metin-karabulut-a16106340/)
