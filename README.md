# Doğa Takvimi
ics (iCalendar)  formatında doğanın geleneksel takvimi. 

### Yükleme
dogatakvimi.ics'yi indirin ve takvim uygulamasıyla (Splanner, iCalendar, Outlook, ... vs) içeri aktarın.

### Tarih ekleme/değiştirme

Takvimin ics formatı hali Emacs orgmode kullanılarak oluşturuldu. Dolayısıyla birşey eklemek veya değiştirilmek istenirse aynı şekilde Emacs ile yapılabilir.

### Alarm ekleme

Alarm eklemek için oluşturulan .ics dosyasındaki  ```END:VEVENT``` 'i 
```
BEGIN:VALARM
TRIGGER:-PT150M
ACTION:DISPLAY
END:VALARM
END:VEVENT
```
ile değiştirince önceki gece saat 2130da alarm çalar. Değiştirme işlemi birçok editor'de bulunan search&replace komutuyla rahatça yapılabilir. 
