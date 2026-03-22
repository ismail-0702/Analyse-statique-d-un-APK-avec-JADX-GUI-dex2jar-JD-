# Analyse-statique-d-un-APK-avec-JADX-GUI-dex2jar-JD-
[Analyse statique d'un APK avec JADX GUI + dex2jar + JD-GUI.docx](https://github.com/user-attachments/files/26167708/Analyse.statique.d.un.APK.avec.JADX.GUI.%2B.dex2jar.%2B.JD-GUI.docx)
Créer un environnement de travail organisé et vérifier l'intégrité de l'APK.Mettez l'APK à analyser dans le dossier.
Vérifiez que l'APK est bien une archive ZIP
<img width="1309" height="689" alt="Capture d&#39;écran 2026-03-22 164109" src="https://github.com/user-attachments/assets/f1743fde-74d2-47c1-a5ad-609033aabc15" />
Listez le contenu de l'APK
<img width="1464" height="422" alt="Capture d&#39;écran 2026-03-22 164217" src="https://github.com/user-attachments/assets/2838ab07-b64d-46bd-87ac-f8f62bae34e6" />
Calculez le hash de l'APK pour traçabilité
<img width="1453" height="128" alt="Capture d&#39;écran 2026-03-22 164310" src="https://github.com/user-attachments/assets/63644b1f-1f8d-470c-af58-c5297bbf2c58" />
Aprés l'installation de l'outil JADX GUI, deplacez l'apk que vous voulez tester dans JADX et vous voyez la structure de l'application 
<img width="1920" height="1020" alt="Capture d&#39;écran 2026-03-22 164715" src="https://github.com/user-attachments/assets/d4e801c6-3283-470b-a786-4a889aacdec2" />
Explorer la structure de l'APK et analyser son manifeste en essayons de detecter les vulnérabilites dans le code et de collecter le maximum des informations.
<img width="1920" height="1020" alt="Capture d&#39;écran 2026-03-22 165301" src="https://github.com/user-attachments/assets/32d58411-bfbf-4072-80ff-e23b61413fae" />
Le fichiers strings.xml
<img width="1542" height="185" alt="Capture d&#39;écran 2026-03-22 165514" src="https://github.com/user-attachments/assets/c44ad817-ca5b-460e-a53b-b7856d82152f" />
Identifier les informations sensibles codées en dur dans l'application.
<img width="960" height="1020" alt="Capture d&#39;écran 2026-03-22 170135" src="https://github.com/user-attachments/assets/0a333932-fbef-4286-8eaf-241753f5c320" />
<img width="960" height="1020" alt="Capture d&#39;écran 2026-03-22 170828" src="https://github.com/user-attachments/assets/e8d238c6-7aa9-4841-a0d9-1b74ad492105" />
<img width="960" height="1020" alt="Capture d&#39;écran 2026-03-22 170910" src="https://github.com/user-attachments/assets/a4fa295e-9227-40d5-ae4c-89390f046ea6" />
<img width="960" height="1020" alt="Capture d&#39;écran 2026-03-22 170916" src="https://github.com/user-attachments/assets/3728f905-9adc-4d3f-8576-be60a20be6cc" />
<img width="960" height="1020" alt="Capture d&#39;écran 2026-03-22 170937" src="https://github.com/user-attachments/assets/09d9fe06-659a-4f61-9efe-7077448fb7fc" />
Transformer le bytecode Android en format JAR pour une analyse alternative.
<img width="1418" height="249" alt="Capture d&#39;écran 2026-03-22 172033" src="https://github.com/user-attachments/assets/b8159343-de1c-4fd9-8d64-07a77cbae272" />
<img width="1378" height="337" alt="Capture d&#39;écran 2026-03-22 172052" src="https://github.com/user-attachments/assets/f10b29d1-35df-447b-9517-92575ee578e8" />

Vérifiez les fichiers DEX extraits .

<img width="937" height="196" alt="Capture d&#39;écran 2026-03-22 172134" src="https://github.com/user-attachments/assets/3171d480-13b2-4734-a65f-724b8c1979ef" />

Essayez de exporter le projet pour avoir le dossier contenant JAVA. 

<img width="255" height="528" alt="Capture d&#39;écran 2026-03-22 173253" src="https://github.com/user-attachments/assets/af618dee-fda1-4c10-be11-590254f6e040" />

Choisissez 'Simple Java' et donnez le chemin extraction

<img width="452" height="349" alt="Capture d&#39;écran 2026-03-22 173415" src="https://github.com/user-attachments/assets/428f6c9f-5019-46f2-9f4c-436d56dc4e2d" />

Le fichier telecharger.

<img width="1012" height="201" alt="Capture d&#39;écran 2026-03-22 174238" src="https://github.com/user-attachments/assets/dfdf7609-d140-4073-bbf6-bee90e7e0024" />

Apres utiliser l'outil JD-GUI pour s'assurer que le code est bon.

