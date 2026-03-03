# CMS_lab1

## Pasul 1. Pregătirea mediului
- Instalează XAMPP (sau un stack similar: OpenServer, MAMP, Docker)
- Pornește modulele Apache și MySQL. Asigură-te că http://localhost se deschide.
<img width="821" height="526" alt="image" src="https://github.com/user-attachments/assets/93bd5b65-a7e4-4e56-b980-b3c81e02229a" />

- În phpMyAdmin, creează o bază de date nouă, de exemplu wp_lab2.
<img width="276" height="34" alt="image" src="https://github.com/user-attachments/assets/7219a345-1c43-483a-823c-1f00a7518088" />


## Pasul 2. Instalarea WordPress
- Descarcă WordPress de pe wordpress.org.
- Dezarhivează fișierele în folderul htdocs (sau echivalentul acestuia pentru stack-ul tău).
<img width="1039" height="243" alt="image" src="https://github.com/user-attachments/assets/723967b2-b64b-41bf-b17f-232545730051" />

- În browser, deschide http://localhost/wp_lab2 și parcurge procesul de instalare.
<img width="1920" height="1080" alt="Screenshot (1)" src="https://github.com/user-attachments/assets/2fc097ee-cff0-4c45-a8b4-f85111f9f835" />
<img width="1920" height="1080" alt="Screenshot (3)" src="https://github.com/user-attachments/assets/e1486f35-ce1e-4c36-ae51-b95dd507cf59" />
<img width="1920" height="1080" alt="Screenshot (4)" src="https://github.com/user-attachments/assets/acd1bb7f-996a-4f37-af53-01b76a352125" />


## Pasul 3. Setările inițiale ale site-ului
- În panoul de administrare, accesează secțiunea Settings → General. Schimbă numele site-ului și fusul orar.
<img width="1920" height="1080" alt="Screenshot (5)" src="https://github.com/user-attachments/assets/b2db4e83-6b9e-4600-969e-7c2fd8854551" />
<img width="1010" height="729" alt="Screenshot 2026-03-02 121031" src="https://github.com/user-attachments/assets/4a228668-4cb8-48c8-8547-fea11f3dee0c" />
<img width="815" height="439" alt="Screenshot 2026-03-02 121039" src="https://github.com/user-attachments/assets/149ef736-d538-4f2e-9598-6ccfe4715ab9" />

- În Settings → Permalinks, selectează opțiunea Post name pentru link-uri mai prietenoase.
<img width="1470" height="728" alt="Screenshot 2026-03-02 121127" src="https://github.com/user-attachments/assets/0796ed9d-0ad9-4661-8370-5baed522640c" />


## Pasul 4. Lucrul cu teme
- Deschide secțiunea Appearance → Themes.
- Instalează o temă nouă din catalogul oficial (de exemplu, „Astra”).
- Activează tema și compară cum s-a schimbat aspectul site-ului.
- În meniul Appearance → Customize, configurează:
  * logoul site-ului,
  * schema de culori,
  * titlul și descrierea.


## Pasul 5. Lucrul cu plugin-uri
- Accesează secțiunea Plugins → Add New.
- Instalează și activează:
  * pluginul Classic Editor (pentru editorul clasic de postări);
  * pluginul Contact Form 7 (pentru adăugarea unui formular de contact).
- Verifică noile funcționalități în panoul de administrare (adăugarea unei postări cu Classic Editor și crearea unui formular cu Contact Form 7).
- În Plugins → Installed Plugins, dezactivează unul dintre plugin-uri și asigură-te că funcționalitatea acestuia a dispărut.


## Pasul 6. Crearea de conținut
- Creează o pagină simplă „Contacte” și inserează formularul de contact.
- Creează câteva postări pe blog cu conținut diferit (text, imagini).
- Verifică modul în care este afișat conținutul pe site.


## Întrebări de control
### Ce face o temă în WordPress și ce face un plugin?
- 
### De ce nu se pierde conținutul site-ului atunci când se schimbă tema?
- 
### Cum se poate modifica aspectul site-ului fără a edita codul?
- 
