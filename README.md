
1. Erstelle einen neuen Ordner namens mywebsite
2. Initialisiere dort git mit ```git init``` 
3. Downloade 3 Bilder, die als Größe "medium" haben, mithilfe von Google Advanced Image Search. Speicher diese Bilder als "image1.jpg", "image2.jpg" und "image3.jpg"
4. Bevor du Committen kannst, müssen die Bilder erst geadded werden. 

    ```git add .```

4. Erstelle deinen ersten commit. Vergiss nicht eine Commit Message anzugeben.

5. In dem mywebsite Ordner brauchen wir noch 2 Ordner: /image and /code. Erstelle sie. 
6. Verschiebe die Bilder in /image
7. ```cd``` in den /code folder
8. ```touch``` eine neue Datei namens index.html
9. Öffne diese Datei mit dem Terminal Befehl ```code index.html``` und füge diesen HTML Code hinzu:

```
<html>
	<head></head>
	<body>
		<img src=../image/image1.jpg />
		<img src=../image/image2.jpg />
		<img src=../image/image3.jpg />
	</body>
</html>
```
10. Gucke dir index.html mit Chrome an
11. Adde deine Veränderungen und erstelle deinen zweiten git commit.
12. In index.html füge 
```<title>Learning Git</title>``` zwischen ```<head>``` und ```</head>``` ein.

13. In /images, erstelle einen unterordner namens /jpg und verschiebe die Bilder da rein.
14. Mach jetzt noch einen Commit. Vergiss nicht zu adden und dem Commit eine Message zu geben. 
15. Öffne index.html mit Chrome
16. index.html scheint wohl kaputt zu sein. Reparier die Pfade in den ```<img>``` tags. 
17. Committe. 


**bonus** Erstelle auf Github dein erstes Repository und mach einen push.
