
# termux-shenex-recon

Termux ortamı üzerinde çalışan, sistem analizi ve keşif (recon) süreçleri için tasarlanmış bir framework'tür. 

## Proje Hakkında
Bu proje, siber güvenlik araştırmalarında terminal üzerinden ağ analizi ve veri sorgulama süreçlerini incelemek amacıyla geliştirilmiştir. Teknik süreçleri otomatize etmek ve sistemin nasıl tepki verdiğini gözlemlemek için optimize edilmiştir.

## Kurulum
```bash
# Gerekli araçları yükleyin
pkg install python git

# Repoyu klonlayın
git clone [https://github.com/codeorax/termux-shenex-recon.git](https://github.com/codeorax/termux-shenex-recon.git)
cd termux-shenex-recon

# Gereksinimleri kurun
pip install -r requirements.txt

## Kullanım
```bash
python sherlock.py
