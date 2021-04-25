# SpotifyDownloader

(Drive link: https://drive.google.com/drive/folders/1BuUAEHOF22aum0fWCuHXfbCzR4AZohh-?usp=sharing)

Fejlesztési nyelv: C#, Python
Programon belüli rövid dokumentációk, program nyelve: Angol

(A programot saját felhasználásra készítettem, a funkcionalitást előtérbe helyezve, saját specifikáció alapján, mivel nem találtam erre az interneten működő felületet.)

A felhasználónak lehetősége van egész, Spotify által összeállított lejátszási listát (zeneszámos rádió, heti kaland, napi mix) letölteni egyszerre, illetve keresések nélkül 1-1 zeneszámot is automatizálva - offline felhasználáshoz - a Spotifyt futtató alkalmazás eszközén kívül is, pl autó, tv.

A program működési elve, a Spotify lejátszási lista forráskódjából adat kinyerése, majd ezt a youtube felületén felhasználva egy Python segédprogram segítségével annak letöltése.

A felhasználónak annyi a dolga, hogy bemásolja a lejátszási listát (3 lépésben, a Help gombbal megjelennek az utasítások), vagy beírja a kedvenc zeneszáma címét, majd a hozzá tartozó gombot megnyomja.

Amint letöltődtek a zenéi, saját mappába tudja másolni őket egy gombnyomással.

Alapjában véve ez a program időt spórol ezekhez a folyamatokhoz, automatizálja helyettünk a lépéseket.

Tervben van a program gyorsítása, többszálúsítása.
