# Insurance Tracker v1.5

[Demo ve iletişim](#demo-ve-iletişim) · [Read in English](#english)

## Türkçe

Insurance Tracker, sigorta acenteleri için bir masaüstü uygulamasıdır. Sabah vadesi yaklaşan poliçeleri görün, gün içinde kime hangi teklifi verdiğinizi kaydedin, akşam hangi müşteriden ne kadar tahsilat yaptığınızı kontrol edin. Müşteri dosyaları, görüşme geçmişi ve hesap hareketleri bilgisayarınızda saklanır.

[![Ana ekranda önümüzdeki 30 günde bitecek üç poliçe ve seçili poliçenin özeti](docs/screenshots/ana-ekran.png)](docs/screenshots/ana-ekran.png)

*Ana ekrandaki bu örnekte üç poliçenin vadesi yaklaşıyor. Seçili kasko poliçesinin bitmesine üç gün kaldığını, primini ve yenileme durumunu sağda görebilirsiniz. Ekran görüntülerine tıklayarak ayrıntıları büyütebilirsiniz.*

### Günün aramalarını planlayın

**Genel bakış** ekranında vadesi geçen, bugün bitecek ve yaklaşan poliçeleri ayrı ayrı inceleyebilirsiniz. **Görevler** ekranındaki **Bugün aranacaklar** listesi ise daha önce takip tarihi verdiğiniz müşterileri gösterir. Örneğin, poliçesinin bitmesine bir ay olan bir müşteri bugün aranmak istediyse, o görüşmeyi bugünün listesinde bulursunuz. Sık kullandığınız filtreleri kaydedebilir ve yeniden görüşeceğiniz müşterileri ana ekrana sabitleyebilirsiniz.

### Müşteri dosyasından yenilemeye

1. **Görüşmeye hazırlanın.** Müşteriyi adı, T.C. kimlik numarası veya telefonuyla bulun. Müşteri kartında iletişim bilgilerini, notları, poliçeleri ve açık bakiyeyi inceleyin. İlgili poliçenin PDF’sini açabilir, eksik evrakı kontrol edebilir veya müşteriye bir WhatsApp mesajı hazırlayabilirsiniz.
2. **Teklifi ve dönüş tarihini kaydedin.** Teklifi acentenizin logosu ve iletişim bilgileriyle PDF olarak hazırlayın. Müşteri cuma günü tekrar aranmak isterse görüşme notunu ve takip tarihini kaydedin. Yenileme panosunda teklif verilen, onaylanan ve henüz teklif verilmemiş dosyaları yan yana görebilirsiniz.
3. **Yeni dönemi açın.** Müşteri kabul ettiğinde mevcut poliçeden yeni dönem oluşturun. Şirketi, primi ve bitiş tarihini yeni sözleşmeye göre güncelleyin. Önceki dönemin teklifleri, PDF’si ve mali hareketleri eski poliçede kalır.

[![Yenileme panosunda bekleyen, teklif verilen, onaylanan, yenilenen ve kaybedilen poliçeler](docs/screenshots/yenileme-panosu.png)](docs/screenshots/yenileme-panosu.png)

### Tahsilat, taksit ve gün sonu

**Tahsilatlar** ekranında açık bakiyeleri ve son tahsilat tarihlerini görebilirsiniz. Örneğin 12.000 TL borcu olan bir müşteriden 4.000 TL aldığınızda ödemeyi hesabına kaydedip kalan 8.000 TL için aylık taksit planı oluşturabilirsiniz. Her taksitte kısmi ödemeleri, kalan tutarı ve geciken vadeleri takip edebilirsiniz.

**Gün özeti**, seçtiğiniz tarihin poliçe kayıtlarını, yenilemelerini ve tahsilatlarını bir araya getirir. Daha uzun bir dönemi incelemek için yönetim panelinde tahsilatların günlere, primlerin ise sigorta branşlarına göre dağılımını görebilirsiniz.

| Poliçe dosyası | Müşteri hesabı |
| --- | --- |
| [![Poliçe listesi, vade önceliği ve seçili poliçenin primi](docs/screenshots/policeler.png)](docs/screenshots/policeler.png) | [![Açık bakiyeler, son tahsilatlar ve seçili müşterinin hesap özeti](docs/screenshots/tahsilatlar.png)](docs/screenshots/tahsilatlar.png) |

### Portföy aktarımı ve kayıtların korunması

- **Excel aktarımı.** Çalışma sayfalarını seçip sütunları müşteri ve poliçe alanlarıyla eşleştirin. Hangi değerlerin değişeceğini kaydetmeden önce görebilir, atlanan satırları nedenleriyle birlikte CSV olarak alabilirsiniz. Aylık poliçe listesi Excel’e aktarılabilir.
- **Kullanıcı yetkileri.** İlk kurulumda acentenin yönetici hesabını oluşturursunuz. Çalışanlar günlük kayıt ve takip işlemlerini yürütür. Silinen müşteri veya poliçeyi çöp kutusundan geri alma ve yedekleri yönetme işlemleri yöneticiye aittir.
- **Yedekleme.** Uygulama açıkken günlük otomatik yedek alabilir. Yedek, veritabanıyla birlikte bağlı poliçe belgelerini de içerir. Geri yüklemede dosyaların bütünlüğü kontrol edilir.

### Deneme ve ticari lisans

İlk kullanımda **14 günlük deneme** başlar. Yıllık lisansa geçmek için kurulum kimliğinizi geliştiriciye iletebilirsiniz. Lisans dosyası bilgisayarınızda doğrulanır. Kullanım, dağıtım ve kaynak koduna erişim geliştiricinin yazılı iznine tabidir. [Lisans koşulları](LICENSE)

### Demo ve iletişim

Ürünü acentenizin iş akışı üzerinden görmek, yıllık lisans almak veya iş birliği görüşmek için geliştirici **Uğur Metin Karabulut** ile iletişime geçebilirsiniz.

[E-posta · ugurmetinkarabulut@gmail.com](mailto:ugurmetinkarabulut@gmail.com) · [LinkedIn · Uğur Metin Karabulut](https://www.linkedin.com/in/uğur-metin-karabulut-a16106340/)

---

## English

[Demo and contact](#demo-and-contact) · [Türkçeye dön](#türkçe)

Insurance Tracker is a desktop application for insurance agencies. Start the morning with policies nearing expiry, keep a record of the quotes you send during the day, and check which customers paid before you close. Customer files, conversations, and account transactions are stored on your computer.

[![Home screen showing three policies expiring in the next 30 days and a summary of the selected policy](docs/screenshots/ana-ekran.png)](docs/screenshots/ana-ekran.png)

*In this sample portfolio, three policies are approaching expiry. The panel on the right shows that the selected motor policy expires in three days, alongside its premium and renewal status. Select any screenshot to view it at full size.*

### Plan the day’s calls

The **Overview** groups policies by whether they have expired, expire today, or are approaching expiry. In **Tasks**, the **Calls due today** list follows the dates you set for customer contact. For example, if a customer asked you to call today about a policy that expires in a month, that conversation appears on today’s list. You can save frequently used filters and pin customers to the home screen for your next conversation.

### From customer record to renewal

1. **Prepare for the conversation.** Find a customer by name, Turkish national ID number, or phone number. Their record brings together contact details, notes, policies, and outstanding balance. Open the policy PDF, check which documents are missing, or draft a WhatsApp message.
2. **Record the quote and the next call.** Prepare a PDF quote with your agency’s logo and contact details. If the customer asks you to call again on Friday, save a note and set the follow-up date. The renewal board shows which policies have been quoted, which have been approved, and which are still pending.
3. **Start the new term.** When the customer accepts, create a new term from the existing policy. Update the insurer, premium, and expiry date to match the new contract. The previous term keeps its quotes, policy PDF, and financial history.

[![Renewal board showing pending, quoted, approved, renewed, and lost policies](docs/screenshots/yenileme-panosu.png)](docs/screenshots/yenileme-panosu.png)

### Collections, instalments, and end-of-day review

The **Collections** screen shows outstanding balances and the date of each customer’s last payment. For example, if a customer owes TRY 12,000 and pays TRY 4,000, record the payment on their account and create a monthly instalment plan for the remaining TRY 8,000. Track partial payments, the amount remaining on each instalment, and overdue amounts.

The **Daily summary** brings together policies recorded, renewals, and payments for the date you select. For a longer view, the admin dashboard shows collections by day and premiums by line of insurance.

| Policy record | Customer account |
| --- | --- |
| [![Policies ordered by expiry and the selected policy’s premium](docs/screenshots/policeler.png)](docs/screenshots/policeler.png) | [![Open balances, latest payments, and the selected customer’s account summary](docs/screenshots/tahsilatlar.png)](docs/screenshots/tahsilatlar.png) |

### Importing and protecting your portfolio

- **Excel import.** Select the worksheets and map columns to customer and policy fields. Preview changes before saving and export a CSV showing which rows were skipped and why. You can also export the monthly policy list to Excel.
- **User permissions.** Create the agency’s administrator account during setup. Staff handle day-to-day records and follow-ups. Administrators manage backups and can restore deleted customers or policies from the recycle bin.
- **Backups.** The application can create a daily backup while it is running. Backups include both the database and linked policy documents. File integrity is checked during restoration.

### Trial and commercial licence

A **14-day trial** starts on first use. To switch to an annual licence, send your installation ID to the developer. The licence file is verified on your computer. Use, distribution, and access to the source code require written permission from the developer. [Licence terms](LICENSE)

### Demo and contact

To see how Insurance Tracker fits your agency’s workflow, obtain an annual licence, or discuss a partnership, contact the developer, **Uğur Metin Karabulut**.

[Email · ugurmetinkarabulut@gmail.com](mailto:ugurmetinkarabulut@gmail.com) · [LinkedIn · Uğur Metin Karabulut](https://www.linkedin.com/in/uğur-metin-karabulut-a16106340/)
