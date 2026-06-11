<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ne Kadar Kaldı? — Gizlilik Politikası</title>
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; }
        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
            background: #0A0A0F;
            color: #E0E0E8;
            line-height: 1.7;
            padding: 40px 20px;
        }
        .container { max-width: 700px; margin: 0 auto; }
        h1 { color: #6C63FF; font-size: 28px; margin-bottom: 8px; }
        .subtitle { color: #6B6B80; font-size: 14px; margin-bottom: 32px; }
        h2 { color: #A0A0B8; font-size: 18px; margin: 24px 0 8px; }
        p, li { color: #A0A0B8; font-size: 15px; margin-bottom: 12px; }
        ul { padding-left: 20px; }
        .highlight { color: #6C63FF; }
        .footer { margin-top: 40px; padding-top: 20px; border-top: 1px solid #2A2A3E; color: #6B6B80; font-size: 13px; }
    </style>
</head>
<body>
    <div class="container">
        <h1>🕐 Ne Kadar Kaldı?</h1>
        <p class="subtitle">Gizlilik Politikası — Son güncelleme: 11 Haziran 2026</p>

        <h2>1. Toplanan Veriler</h2>
        <p>Bu uygulama <span class="highlight">hesap, e-posta, telefon, konum veya reklam kimliği toplamaz</span>. Üyelik sistemi yoktur. Yalnızca isteğe bağlı <strong>Gruplar</strong> özelliğini kullanırsanız, sizin girdiğiniz sınırlı veriler sunucuda saklanır (bkz. madde 3).</p>

        <h2>2. Cihazda Saklanan Veriler</h2>
        <p>Aşağıdaki veriler yalnızca cihazınızda (AsyncStorage) saklanır ve sunucuya gönderilmez:</p>
        <ul>
            <li>Eklediğiniz kişisel etkinlikler (başlık, tarih, emoji)</li>
            <li>Favori etkinlik tercihleriniz</li>
            <li>Tema tercihiniz (aydınlık / karanlık)</li>
        </ul>

        <h2>3. Gruplar Özelliği (isteğe bağlı)</h2>
        <p>Gruplar özelliğini kullanmayı seçerseniz, grubun çalışması için şu veriler sunucumuzda (Supabase, AB — Frankfurt) saklanır:</p>
        <ul>
            <li><strong>Görünen ad:</strong> Gruba katılırken kendinizin yazdığı takma ad (gerçek ad zorunlu değildir).</li>
            <li><strong>Grup içeriği:</strong> Grup adı ve grupta paylaşılan etkinlikler (başlık, tarih, emoji).</li>
            <li><strong>Rastgele cihaz kimliği:</strong> Üyeliğinizi tanımak için cihazda üretilen rastgele bir numara. Kimliğinizle, telefonunuzla veya başka bir bilgiyle eşleştirilemez.</li>
        </ul>
        <p>Bu veriler uygulamada yalnızca grup üyelerine gösterilir; üçüncü taraflarla paylaşılmaz, reklam/analitik için kullanılmaz. Grup içeriği, yalnızca şikayetlerin incelenmesi ve uygunsuz içeriğin kaldırılması (moderasyon) amacıyla uygulama geliştiricisi tarafından görüntülenebilir. <strong>Silme:</strong> Etkinliğinizi veya grubunuzu uygulamadan silebilirsiniz; gruptan ayrıldığınızda adınız üye listesinden kaldırılır. Talep için iletişim adresine de yazabilirsiniz.</p>

        <h2>4. Ağ Erişimi</h2>
        <p>Uygulama yalnızca şu amaçlarla internete bağlanır:</p>
        <ul>
            <li><strong>Resmi tatil verileri:</strong> Nager.Date API'den Türkiye resmi tatilleri çekilir.</li>
            <li><strong>Etkinlik güncellemeleri:</strong> GitHub'da barındırılan JSON dosyasından sınav ve bayram tarihleri güncellenir.</li>
            <li><strong>Gruplar:</strong> Yalnızca Gruplar özelliğini kullanırsanız, madde 3'teki veriler sunucuyla eşitlenir.</li>
        </ul>

        <h2>5. Bildirimler</h2>
        <p>Uygulama, etkinliklere yaklaştığınızda sizi bilgilendirmek için yerel (lokal) bildirim gönderir. Bildirimler tamamen cihazınızda oluşturulur; uzak sunucu kullanılmaz.</p>

        <h2>6. Üçüncü Taraf Hizmetler</h2>
        <p>Uygulama reklam, analitik veya izleme aracı içermez. Gruplar verisi, barındırma hizmeti olarak yalnızca Supabase altyapısında tutulur.</p>

        <h2>7. Çocukların Gizliliği</h2>
        <p>Uygulama her yaş grubuna uygundur ve çocuklardan özel veri toplamaz. Gruplara katılım davet koduyla sınırlıdır; herkese açık bir akış yoktur.</p>

        <h2>8. İçerik Şikayeti</h2>
        <p>Grup içinde uygunsuz içerik görürseniz uygulamadaki <strong>Bildir</strong> seçeneğini kullanın veya iletişim adresine yazın; 24 saat içinde incelenir.</p>

        <h2>9. İletişim</h2>
        <p>Sorularınız için: <span class="highlight">tanerenn@github.com</span></p>

        <div class="footer">
            © 2026 Ne Kadar Kaldı? — Tüm hakları saklıdır.
        </div>
    </div>
</body>
</html>
