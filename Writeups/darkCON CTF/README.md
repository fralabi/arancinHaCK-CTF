# [darkCON CTF](https://ctftime.org/event/1250)

### OSINT/Travel to the home

```
I Travelled from MAS to CBE at 10 Jan 2020 (Any direction) and i took a beautiful picture while travelling
Find the Exact location (co-ordinates upto 2 decimal point) and approximate time while i took the pick
Flag format will be {lat,long,time} for time it is 1 hour duration like (01-02)
Flag Format: darkCON{1.11,1.11,01-02}
Hint: Don't brute as maybe you could miss something on location , Find the time correctly and location 
```

### Svolgimento
Ho trovato sul web che la tratta MAS-CBE è una tratta ferroviaria in India -> [LINK](https://etrain.info/train/Mas-Cbe-Sf-Exp-02673/schedule)<br> 
<img src="https://github.com/fralabi/v1770r14n1-CTF/blob/main/Writeups/darkCON%20CTF/chall.jpg" width="500px" height="500px"> <br>
Vista la foto allegata nella challenge che mostra una foto con tre particolari: <br>
* Un ponte che attraversa un fiume 
* A sinistra un tempio mentre ancora 
* In fondo più a sinistra un impianto industriale con un nastro o scivolo in blu. 
 <br>
Seguendo la tratta su Google Maps ho controllato tutti gli attraversamenti dei fiumi che corrispondessero alle mie supposizioni ed ho trovato il seguente luogo ->
<a src="https://www.google.it/maps/place/Vinayagar+and+Perumal+Temple/@11.3490821,77.753334,435m/data=!3m1!1e3!4m5!3m4!1s0x3ba965faf1f27fe1:0x5588f9b51131e1d2!8m2!3d11.3490821!4d77.7544284">LINK</a> <br>

Le coordinate trovate sono 11.34 e 77.75

Visto che la foto è stata palesemente scattata durante il giorno ho provato tutte le possibili ore di sole 

La flag è: ```darkCON{11.34,77.75,11-12}```
