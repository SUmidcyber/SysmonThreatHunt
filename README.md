# Sysmon General Security & Threat Monitoring Configuration

Bu repo, **Windows sistemlerinde Sysmon kullanarak genel güvenlik tehditlerini tespit etmek** amacıyla oluşturulmuş XML konfigürasyon dosyalarını içerir.

## 🔍 İzlenen Olaylar:
✅ **Şüpheli süreç çalıştırmaları** (PowerShell, CMD, Wscript)  
✅ **Zararlı ağ bağlantıları** (Netcat, Meterpreter, RDP abuse)  
✅ **Kötü amaçlı dosya oluşturma işlemleri**  
✅ **Windows Defender'ı devre dışı bırakma girişimleri**  
✅ **LSASS gibi kritik süreçlere DLL enjeksiyonu**  

## 🚀 Kullanım:
1. Sysmon'u indirip yükleyin:
   ```powershell
   sysmon -accepteula -i sysmon-general-security-config.xml
