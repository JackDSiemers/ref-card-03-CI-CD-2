
### Ref Card 03 CI-CD

Schritte - Workflow Dockerhub

1. Projekt pullen und remote source auf eigenes repo wechslen.
2. Dockerfile erstellen, mit einfachen copy & build process.
3. Docker-publish.yml file erstellen und korrekt initialisieren.
4. Secrets auf Github erstellen.
5. Pushen und warten auf die Pipeline.
![image](/resources/Screenshot%202024-09-26%20at%2007.51.04.png)

Schritte - Github Container Registry.
1. gleiches Dockerfile, Docker-registry-publish erstellt und korrekt definiert.
2. Neuer Github Token erstellen und in Secrets speichern.
3. Pushen und warten auf Pipeline.
![image](/resources/Screenshot%202024-09-26%20at%2009.11.08.png)

Schritte - AWS
1. Secrets von AWS CLI auf github secrets speichern.
![image](/resources/Screenshot%202024-10-03%20at%2009.23.01.png)
2. Registry Auf AWS Academy Leaner Lab > ECR erstellen und push commands hinauslesen. Dannach auch als Secrets speichern.
![image](/resources/Screenshot%202024-10-03%20at%2009.32.38.png)
3. YML file erstellen und die Secrets verwenden.
4. Dannach Pushen und auf Github actions bestätigen.
5. ECS Cluster erstellen mit Service
