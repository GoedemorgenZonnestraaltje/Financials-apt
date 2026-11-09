# Financials-apt

Installatiepakketten en apt-bron van **Financials**, het administratiepakket.

- **Installeren:** download het `.deb` van de [nieuwste release](../../releases/latest) en open het, of `sudo apt install ./financials_<versie>_amd64.deb`. Daarna komen updates via Software-updates van Ubuntu.
- **Apt-bron:** <https://goedemorgenzonnestraaltje.github.io/Financials-apt/>. Het pakket stelt die zelf in.

Deze repository bevat geen code. De releases worden gemaakt door de workflows in de (privé) repository Financials; `.github/workflows/pages.yml` zet daarna de index en het nieuwste pakket van elk kanaal op GitHub Pages.

Eenmalig instellen: *Settings → Pages → Build and deployment → Source:* **GitHub Actions**.
