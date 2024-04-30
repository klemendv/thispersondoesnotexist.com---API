# thispersondoesnotexist.com---API
Ker smo pri enem izmed projektov, rabili api, za naključno generiranje in izibro slik iz thispersondoesnotexist.com, in ima še kar nekj prostih sistemskih sredstev,
smo se odločili, da g ponudimo v javno rabo, Deluje preko get parametrov, zanekrat zahteva parameter ?number (ki pove koliko slik naj zgenerira (najmanj 1 največ 5) v primeru zlorab apija, bo sistem IP naslov zahtevka avtomatsko 
benal
```
OSNOVNI URL: https://carlog.org/api/tp.php?number=ŠTEVILO SLIK KI JIH ŽELITE
```
PRIMER POIZVEDBE:
```
https://carlog.org/api/tp.php?number=1
```
IN DOBIMO:
```
{"image_links":["https:\/\/carlog.org\/api\/person\/person_6630e476b57f5.jpg"]}
```
Slik iz strežnika ne brišemo
