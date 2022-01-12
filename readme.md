
<h1>Git Ohjeet</h1>

<h2>Git peruskomennot:</h2>
<h3>Git add</h3>
= lisää tiedostot versionhallinnan piiriin. 
<h3>git commit</h3>	
= siirtää tiedostojen uusimman tilan versionhallintaan yhdeksi commitiksi
<h3>git status</h3>	
= nähdään tehdyt tiedostot, mutta vielä commit'oimattomat muutokset
<h3>git push</h3>	
= tiedosto siirtyy palvelimelle
<h3>git branch</h3>	
= näkee mitä haaroja on käytettävissä. Uuden haaran voi tehdä: git branch esimerkki , jolloin syntyy kehityshaara nimeltään esimerkki.
<h3>git checkout</h3>
= siirrytään uuteen kehityshaaraan (git checkout esimerkki), jolloin esimerkki on aktiivisena
<h3>git revert</h3>
= poistaa commitin
<h3>git reset</h3>
= voidaan palata takaisin tiettyyn vanhaan commitiin. Komento poistaa kaikki tehdyt commitit viitatun commitin jälkeen. Komentoa ei pidä käyttää julkisesti, vaan sen sijaan komentoa git revert, joka on mainittu yläpuolella.
<h3>Paikallinen git työhakemisto GitHub ympäristöön:</h3>
= Git remote add origin https://githubrepositio.com -komento kytkee versiohallinnan repositioon, git init -komento 
<h3>tiedon lähettäminen paikallisesta työhakemistosta GitHubiin:</h3>
= Githubiin repositorio, johon tietoa voidaan lähettää. Paikallinen git työhakemisto sinne ja git remote add upstream https://githubrepositio.com -komennolla tietoja sinne. Repositoriosta tietojen lataus git pull -komennolla.
<h3>Fork</h3>
Fork on repositorio joka on syntynyt fork toiminnon takia kopiona toisen Github repositoriosta. Fork:n omistaa kopion luonut henkilö. 
Vieraasta remotesta sisällön lataus omaan työhakemistoon komennolla git clone (nettisivusto).



![image](https://user-images.githubusercontent.com/93643733/149132448-8f010c26-16c0-456a-a4b0-64412f6552f8.png)

