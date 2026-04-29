---
layout: page
title: Sistema Eragileak
---

<h2>Urrutiko kudeaketa</h2>
Zerbitzariaren kudeaketa erosoagoa eta malguagoa izan dadin, urrutiko sarbide bikoitza konfiguratu dugu:
<ul><li>SSH : Terminal bidezko kudeaketa segurua ahalbidetzeko, SSH zerbitzua martxan jarri dugu. Bezero makina batetik terminal bidezko kontrol osoa daukagula egiaztatu dugu.</li>
<img width="1114" height="408" alt="1" src="https://github.com/user-attachments/assets/4ba779a2-d3d2-45fc-bd0d-5b03408f23b6" />
<li>AnyDesk: Ingurune grafikoko urrutiko kudeaketa behar denerako, AnyDesk tresna instalatu dugu. Honen bidez, urrutiko makina batetik zerbitzariaren mahaigainera sartu eta konfigurazio bisualak egin ditzakegu.</li>
<img width="1919" height="1079" alt="2" src="https://github.com/user-attachments/assets/c1ea9f3e-dd44-42f9-84aa-cf7b62d6a0de" /></ul>
<h2>Segurtasun analisiak</h2> 
Zerbitzaria seguru egoteko, segurtasun analisien automatizazio sistema bat konfiguratu dugu. Rkhunter tresna erabili dugu sistemako fitxategiak aztertzeko, baimen desegokiak edo rootkit-ak detektatzeko asmoz.
<img width="1086" height="617" alt="3" src="https://github.com/user-attachments/assets/7707d2de-7fcb-4880-8215-2fb6946f2bc1" />
Lan hau eskuz egin behar ez izateko, Crontab tresna erabili dugu zereginak programatzeko. Script bat martxan jartzen da automatikoki eta dena log fitxategi batean gordetzen du. Horrela, zerbait gertatzen bada, fitxategi horretara jo dezakegu zer gertatu den ikusteko administratzaileak eskuz ezer egin gabe.
<img width="753" height="477" alt="4" src="https://github.com/user-attachments/assets/28c12745-80b8-4f52-994c-7cd2c54a8b89" />
<h2>Monitorizazio sistemak</h2>
Zerbitzariaren baliabideak (CPU, RAM, Diskoa eta Sarea) kontrolatzeko, monitorizazio tresna dezberdinak erabili ditugu, bakoitzak funtzio espezifiko bat betetzen duena:
<ul><li>Cockpit: Web bidezko kudeaketa interfazea instalatu dugu. Honen bidez, zerbitzuak, sareko konfigurazioak eta sistemaren log-ak modu bisualean kudeatu ditzakegu.
<img width="1919" height="974" alt="5" src="https://github.com/user-attachments/assets/1cedf867-8c4e-45f8-accb-2354e3da0b3c" /></li>
<li>Htop: Terminal bidezko kudeaketarako, htop tresna erabili dugu prozesuak denbora errealean aztertzeko eta baliabide gehien kontsumitzen dituzten zereginak identifikatzeko.
<img width="1100" height="620" alt="6" src="https://github.com/user-attachments/assets/47a80e3a-1f6e-42b4-9438-c421183b2015" /></li>
<li>Netdata: Tresna honen bidez denbora errealeko monitorizazio grafikoa lortu dugu. Alerta sistema bat konfiguratu dugu, baliabideak muga kritikoetara iristen direnean abisua emateko.
<img width="1915" height="947" alt="7" src="https://github.com/user-attachments/assets/c7cd9097-c6c9-4456-a5b8-51187e572eb5" />
<img width="1535" height="270" alt="8" src="https://github.com/user-attachments/assets/fc0f34be-e161-43af-8555-d4398cc522ec" /></li></ul>
<h2>Samba eta Disko Kuotak</h2> 
Erabiltzaileen artean fitxategiak partekatzeko Samba konfiguratu dugu. Konfigurazio honi esker, Windows eta Linux bezeroek zerbitzariko karpeta partekatuak ikusi eta erabili ditzakete.
<ul><li>Windows-etik:</li>
<img width="937" height="707" alt="9" src="https://github.com/user-attachments/assets/80a41c7a-ca4d-4e65-9ba4-e5bf19b5d80d" />
<img width="1138" height="483" alt="10" src="https://github.com/user-attachments/assets/47a0bbcc-4b94-40d7-b74e-13855f6aae7d" />
<li>Linux-etik:</li>
<img width="890" height="549" alt="11" src="https://github.com/user-attachments/assets/a1a1eb7e-6219-42a9-8b86-941f4ac66181" />
<img width="846" height="352" alt="12" src="https://github.com/user-attachments/assets/289180ea-67b9-4828-89c3-bae12f5ad07b" /></ul>
Diskoaren erabilera kontrolatzeko kuotak jarri ditugu. Taldeko erabiltzaileei muga bat jarri diogu diskoan, horrela norbaitek gauza gehiegi igotzen baditu, sistemak gelditu egiten du eta ez du uzten disko guztia betetzen.
<img width="748" height="103" alt="13" src="https://github.com/user-attachments/assets/cddd4724-be9c-454c-afd2-943897fd5291" />
<h2>Saretik instalatzea</h2>
Bezeroak saretik instalatzeko sistema prestatu dugu,  USBrik edo CDrik gabe instalatu ahal izateko. Bezeroak gure zerbitzariari IPa eskatzen dio eta gure zerbitzariak Debian instalatzeko menua bidaltzen dio saretik.
<img width="1210" height="618" alt="14" src="https://github.com/user-attachments/assets/e74abb67-af8c-43ca-af9b-d17b4b154405" />
