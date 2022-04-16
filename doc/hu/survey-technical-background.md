# Technical background and limitations

## @kazso:matrix.tilos.hu

> sajna. a felhő drága.
> megpróbálom megpingelni volt kolléga, Ő > 10 éve alapított 'felhőalapú megoldások' szolgáltatást.

## @sdd-:matrix.org

* @sdd-:libera.chat

> a webmester@tilos.hu emailcimen tudod felvenni a kapcsolatot a csodalatos Tilos IT szakkorrel ez ugyben

## @szabi:matrix.tilos.hu

> technikailag nem tudunk kiszolgálni annyi hallgatót online, amennyit az FM kiszolgál :(
> Jelenleg 30000 a max hallgatottság. Legyen mondjuk ez számolási hiba és 10000 a max. Az hatalmas gépigény, sávszélesség. rengeteg költség, ráadásul nem minden hallgatót lehet átszoktatni online-ra, mert nincs eszköze. Ezek jellemzően az autorádiós és ún. konyhai hallgatók. 
> nem kell tesztelni. pontosan tudjuk, mit bír a rendszerünk és folyamatosan kapunk róla statisztikát.
> jelen helyzetben anyagilag nem tudunk átállni annyi hallgatóra, amennyi az FM-mel együtt van.
> még csak sejtésünk van róla, hisz az árak kb naponta változnak és mondom: nem tudjuk, hogy hény hallgató szokik át az onlinera
> Majd küldök tachnikai infókat, de most kicsit el vagyok elhavazva ezzel az üggyel.
> Biztos, hogy brutál sávszélesség kell hozzá és nagyságrandileg több pénz az online cuccokra, miközben a stúdióköltség nem változik. Mondjuk az antennabérlésen nyerünk :))))
> Korábban többször volt stream szerver leállás, mert túl sokan hallgatták, azaz  többen, mint, amennyire a szerver kalibrált volt. Ahogy nőtt a hallgatottság, úgy kellett bővíteni a szervert és a sávszélességet, amit használ.
> és ezt kéne most nagyságrendileg bővíteni, de mondom, hogy jelentkezek a részletekkel, csak én is próbálom érzelmileg feldolgozni a helyzetet.
> UPDATE: keddre áll össze, hogy a teljes onlinera átállás nagyságrendileg milyen költséggel jár, de már most látszik, hogy a drága hallgatók nagyon aktívak lettek és sok egyedi támogatás és állandó támogatási beállítás született az elmúlt 16 órában.

> wagner: batyo madbal A Tilos stream szerver jelenleg megközelítőleg 1000 hallgató kiszolgálására alkalmas. Ezt mindig ráhagyással számoljuk, azaz - optimális esetben - akár 1500 hallgatóval is elbír, de azért van a ráhagyás, hogy ne legyen olyan lehalás, mint pl. a 3. utas Feldmár adása közben anno. Ha ezt vesszük alapul, akkor 5000 hallgatóra jó eséllyel 5 db hasonló szervert kell beindítani, amelyek ugyanakkora sávszélességet kapnak a világháló felé és a szervereken futó icecast szervert úgy kell konfigurálni hogy tükrözze a jelenlegi, "fő icecast" szerver streamjeit. Ezután DNS-ben úgy kell konfigurálni hogy minden üzemben levő icecast szerver címére történjen a hallgatók csatlakozása. Így szerverenként ugyanazok a számok érvényesek max terhelésre amit a jelenlegi szerver esetében tud a cucc. Viszont ez ötször ennyi gép, felügyelet, hibalehetőség stb. Szóval ezért nagyobb a költség több online hallgatóra és most még csak 5000 hallgatóról beszélünk, holott akár 30000 hallgatóig is felkúszott a napi unikális hallgatók száma a Tilosnál, de azok javarészét az FM szolgálta ki.	Minderre azért nem jó egy hatalmas gép, mert a centralizált kiszolgálás sérülékenyebb, mint a decentralizált.

> az nmhh szerint 2019-ben a tilost 11000-en hallgatták https://nmhh.hu/cikk/207634/Budapesti_es_orszagos_napi_radiohallgatottsag_2019_julius__2019_szeptember
> Van, hogy országos, van, hogy fővárosi mintában vizsgálták a Tilost. Volt napi 30e egyedi és havi majdnem 100e egyedi hallgató jött ki egy vizsgálatból.

## References

* https://matrix.to/#/#tilos:matrix.tilos.hu
* 2022-04-14 13:59:10
* 2022-04-15

## News

* https://rtl.hu/belfold/2022/04/14/tilos-radio-nmhh-frekvencia-mediatanacs
* https://tilos.hu/news/62587f11c073467c255169d4
* https://444.hu/2022/04/14/az-nmhh-nem-hosszabbitja-meg-a-tilos-radio-frekvenciajat
* https://tilos.hu/page/sajto-2001
* https://media1.hu/2022/04/14/nem-kap-hosszabbitast-a-tilos-radio-a-mediatanacstol/
* https://www.napi.hu/magyar-vallalatok/mediatanacs-nmhh-tilos-radio-sajtoszabadsag.750417.html
