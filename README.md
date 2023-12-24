# Goole Dorking
Google üzerindeki aramalarımızı iyileştiren ve hız kazandıran sorgulara ‘GOOGLE DORK’ denir. 

## site:
`site: <aranacak_site> <aranan_kelime>`  

**Not:** Suç ve Ceza kitabını aramak istersek eğer “ ” içine yazmazsak Suç kelimesini ayrı ve kelimesini ayrı Ceza kelimesini ayrı olarak arayabilir o yüzden birleşik kelimeleri “ " içine yazmak daha iyi arama sonuçları karşımıza çıkarır.

 Örn: `site:kitapyurdu "Suç ve Ceza"`

 Eğer arama sonuçlarına etki etmesini istediğiniz bir parametre var ise **+<arancak_kelime>** şeklinde ekleyebiliriz.

 Örn: `site:kitapyurdu "Suç ve Ceza"+"iş Bankası Yayınları"`

 Eğer bir kelimenin arama sonuçlarında çıkmasını istemiyorsanız **-<istenmeyen_kelime>** şeklinde o kelimeyi arama sonuçlarından silersiniz.

 Örn: `site:kitapyurdu "Suç ve Ceza"+"iş Bankası Yayınları" -ciltli`

 ## inurl:

`inurl:<aranan_kelime>`

 URL sinde aradığımız kelime geçen siteleri bize listeler. 

 ## intitle:

 `intitle:<aranan_kelime>`

 Adı üstünde aradığımız kelimeye sahip title ları listeler.

 ## intext:

 `intext:<aranan_kelime>`

 intitle komutuna benzer ama title yerine kelimeyi sayfanın text (içeriğinde) tinde arar.

 ## allintext:
 
`allintext:<aranan_kelime>`

 Aradığımız kelimeyi bütün textlerin içinde arar.

 Not: Eğer aradığımız kelimenin başını veya sonun bilmiyorsak * ile tamamlayabiliriz. Örneğin `allintext:"*@gmail.com"`
 ifadesi ile sonu @gmail.com ile biten kelimeleri arayacak.

 ## filetype:

 Aranan kelimenin hangi dosya tipinde olmasını istediğimizi filitrelememize yarar.

 Örn: `filetype:pdf hacking` hacking kelimesinin geçtiği pdf dosyalarını bize listeleyecek.

 ## AND - OR

 Arama filitreleriini AND ve OR komutları ile düzenleyebiliriz.

 Örn: `allintext:"*@gmail.com" OR "Password"`
 Örn: `allintext:"*@gmail.com" AND "Password"`
 
