# Rick's Stuff - Portal Color Key (Forge 1.20.1)

Portal silahi elindeyken **C** tusuna (Ayarlar > Kontroller > "Rick's Stuff - Portal Rengi" altindan degistirilebilir)
basinca portal rengi siradaki renge gecer: Yesil > Mavi > Turuncu > Mor > Kirmizi > Pembe > Sari > Camgobegi > Beyaz > ...

Gerekenler: Forge 1.20.1 (47.x) + Rick's Stuff 0.0.4.3. Hem client hem server'a kurulmali.

## Derleme
1. JDK 17 kur.
2. Forge 1.20.1 MDK'yi indir (files.minecraftforge.net, 1.20.1 - 47.3.x, "Mdk").
   MDK icindeki `gradlew`, `gradlew.bat` ve `gradle/` klasorunu bu projenin icine kopyala.
3. Bu klasorde: `./gradlew build` (Windows: `gradlew.bat build`)
4. Cikti: `build/libs/rick_portal_color_key-1.20.1-1.0.0.jar` -> mods klasorune at.

Renkleri degistirmek icin `ColorPalette.java` dosyasini duzenle.
