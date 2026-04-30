Markatze Lengoaiak  
Erronka honetan lehen erabilitako, html eta css erabiliko dugu, java scripateren kasuan, aldaketa batzuk egingo ditugu, eta azkenik, xml, json eta Ajax erabiliko ditugu gure web orrian datuak grafiko eta bineta moduan ipintzeko

***HTML:***

* Hasiera(Menua)  
* Pistak(eskaitzen ditugun pistak)  
* Ikasgaiak (zer ikasgai eskaintzen ditugu)  
* Denda (saltzen ditugun gauzak)  
* Datuak (binetak eta grafikoa ipiniko dugun lekua)

Lehenik, Menutik hasiko gara:  
<img width="602" height="234" alt="image" src="https://github.com/user-attachments/assets/872eaab5-5700-422e-bce5-6dc9b193a6fb" />
<img width="594" height="206" alt="image" src="https://github.com/user-attachments/assets/e8bfc880-f74d-4744-9581-22a0ac89244b" />

Menua egiteko, navbar bat sortu dugu, navbar horretan beste orri batzuen linka ipini dugu.  
<img width="493" height="287" alt="image" src="https://github.com/user-attachments/assets/1ccbd4b8-c1da-45f3-a43d-cea4b9377f43" />
Ondorengo botoia egiteko JS erabili dugu:   
<img width="580" height="319" alt="image" src="https://github.com/user-attachments/assets/72202c52-257b-4ce8-a5db-0738a6f13604" />
emen erabilitako jsa. Bukatzeko behealdean footer bat ipini dugu izenentzako  
<img width="464" height="94" alt="image" src="https://github.com/user-attachments/assets/ccc18d9b-775e-4792-b72d-d44f19ff73fd" />


Bigarren orrian, gure pistak ikusiko ditugu, hemen html eta nola ikusten den web orriaren barruan:  
<img width="604" height="234" alt="image" src="https://github.com/user-attachments/assets/6cee722c-0cb8-47bd-86d7-76f10e3b2b30" />

ikusten den bezala narvar eta footerra errespetatuz, 3 pista erakusten ditugu eskaera moduan. Html hurrengo da:  
<img width="546" height="749" alt="image" src="https://github.com/user-attachments/assets/ca7f6474-8b4c-4e69-8dc7-633353ad37bc" />


Hirugarren puntu bezala, Ikasgaiak ipiniko ditugu.  
<img width="542" height="202" alt="image" src="https://github.com/user-attachments/assets/8a3927bc-5911-4a10-a3ea-708d76877007" />

web orrian ikusten den bezala footerra eta navbar ere errespetatzen ditugu esta 2 argazki ipintzen ditugu, bat skyari buruz eta bestea Snowbordingaren buruz gure klaseak ikusteko.  
<img width="543" height="601" alt="image" src="https://github.com/user-attachments/assets/0499732d-cfa9-44ae-9da0-be6b2a4f0936" />
hemen erabilitako htmla.

Laugarren puntu bezala, denda bat sortu dugu. Dendan gure restortak eskaintzen dituen produktu garritsuenak ipini ditugu hau da, kaskoa patina eta Snow tabla.  
![][image10]hemen ditugu, 3 artikuluak prezio bat behealdean, erosleentzat erosoagoa izateko.![][image11]  
eta hemen erabilitako htmla

Azkenik, gure datuak nun erakutsiko den orria. orri honetan, datu basetik atetutako datuak datuak (json), xmlera pasatu dugu.  
# Json:  
{  
  "metadata": {  
    "last\_update": "2026-04-28T11:23:47.000Z",  
    "source": "ski\_resort\_db"  
  },  
  "data": {  
    "igoera\_kopuru\_agregatua": \[  
      {  
        "resort\_id": 2,  
        "lift\_id": 5,  
        "total\_igoerak": 1158  
      },  
      {  
        "resort\_id": 1,  
        "lift\_id": 4,  
        "total\_igoerak": 1127  
      },  
      {  
        "resort\_id": 3,  
        "lift\_id": 1,  
        "total\_igoerak": 1208  
      },  
      {  
        "resort\_id": 2,  
        "lift\_id": 2,  
        "total\_igoerak": 1235  
      },  
      {  
        "resort\_id": 3,  
        "lift\_id": 4,  
        "total\_igoerak": 1222  
      },  
      {  
        "resort\_id": 2,  
        "lift\_id": 1,  
        "total\_igoerak": 3051  
      },  
      {  
        "resort\_id": 2,  
        "lift\_id": 4,  
        "total\_igoerak": 1218  
      },  
      {  
        "resort\_id": 3,  
        "lift\_id": 5,  
        "total\_igoerak": 3080  
      },  
      {  
        "resort\_id": 3,  
        "lift\_id": 2,  
        "total\_igoerak": 1240  
      },  
      {  
        "resort\_id": 2,  
        "lift\_id": 3,  
        "total\_igoerak": 1896  
      },  
      {  
        "resort\_id": 1,  
        "lift\_id": 2,  
        "total\_igoerak": 1068  
      },  
      {  
        "resort\_id": 3,  
        "lift\_id": 3,  
        "total\_igoerak": 1787  
      },  
      {  
        "resort\_id": 1,  
        "lift\_id": 5,  
        "total\_igoerak": 1138  
      },  
      {  
        "resort\_id": 1,  
        "lift\_id": 3,  
        "total\_igoerak": 557  
      },  
      {  
        "resort\_id": 1,  
        "lift\_id": 1,  
        "total\_igoerak": 2787  
      }  
    \],  
    "demografia\_datuak": \[  
      {  
        "resort\_id": 1,  
        "forfait\_type": "junior",  
        "total\_igoerak": 1313  
      },  
      {  
        "resort\_id": 3,  
        "forfait\_type": "adult",  
        "total\_igoerak": 4249  
      },  
      {  
        "resort\_id": 3,  
        "forfait\_type": "junior",  
        "total\_igoerak": 2132  
      },  
      {  
        "resort\_id": 2,  
        "forfait\_type": "adult",  
        "total\_igoerak": 5685  
      },  
      {  
        "resort\_id": 1,  
        "forfait\_type": "adult",  
        "total\_igoerak": 4099  
      },  
      {  
        "resort\_id": 2,  
        "forfait\_type": "retired",  
        "total\_igoerak": 1457  
      },  
      {  
        "resort\_id": 1,  
        "forfait\_type": "retired",  
        "total\_igoerak": 1265  
      },  
      {  
        "resort\_id": 3,  
        "forfait\_type": "retired",  
        "total\_igoerak": 2156  
      },  
      {  
        "resort\_id": 2,  
        "forfait\_type": "junior",  
        "total\_igoerak": 1416  
      }  
    \],  
    "erabilera\_gailurrak": \[  
      {  
        "ordua": "13:00",  
        "total\_igoerak": 2987  
      },  
      {  
        "ordua": "11:00",  
        "total\_igoerak": 5628  
      },  
      {  
        "ordua": "10:00",  
        "total\_igoerak": 2125  
      },  
      {  
        "ordua": "12:00",  
        "total\_igoerak": 4929  
      },  
      {  
        "ordua": "09:00",  
        "total\_igoerak": 7215  
      },  
      {  
        "ordua": "07:00",  
        "total\_igoerak": 244  
      },  
      {  
        "ordua": "08:00",  
        "total\_igoerak": 644  
      }  
    \]  
  }  
}  
eta hemen transformatutako 
# XML:  
\<?xml version\="1.0" encoding\="UTF-8" ?\>  
 \<root\>  
     \<metadata\>  
         \<last\_update\>2026-04-28T11:23:47.000Z\</last\_update\>  
         \<source\>ski\_resort\_db\</source\>  
     \</metadata\>  
     \<data\>  
         \<igoera\_kopuru\_agregatua\>  
             \<resort\_id\>2\</resort\_id\>  
             \<lift\_id\>5\</lift\_id\>  
             \<total\_igoerak\>1158\</total\_igoerak\>  
         \</igoera\_kopuru\_agregatua\>  
         \<igoera\_kopuru\_agregatua\>  
             \<resort\_id\>1\</resort\_id\>  
             \<lift\_id\>4\</lift\_id\>  
             \<total\_igoerak\>1127\</total\_igoerak\>  
         \</igoera\_kopuru\_agregatua\>  
         \<igoera\_kopuru\_agregatua\>  
             \<resort\_id\>3\</resort\_id\>  
             \<lift\_id\>1\</lift\_id\>  
             \<total\_igoerak\>1208\</total\_igoerak\>  
         \</igoera\_kopuru\_agregatua\>  
         \<igoera\_kopuru\_agregatua\>  
             \<resort\_id\>2\</resort\_id\>  
             \<lift\_id\>2\</lift\_id\>  
             \<total\_igoerak\>1235\</total\_igoerak\>  
         \</igoera\_kopuru\_agregatua\>  
         \<igoera\_kopuru\_agregatua\>  
             \<resort\_id\>3\</resort\_id\>  
             \<lift\_id\>4\</lift\_id\>  
             \<total\_igoerak\>1222\</total\_igoerak\>  
         \</igoera\_kopuru\_agregatua\>  
         \<igoera\_kopuru\_agregatua\>  
             \<resort\_id\>2\</resort\_id\>  
             \<lift\_id\>1\</lift\_id\>  
             \<total\_igoerak\>3051\</total\_igoerak\>  
         \</igoera\_kopuru\_agregatua\>  
         \<igoera\_kopuru\_agregatua\>  
             \<resort\_id\>2\</resort\_id\>  
             \<lift\_id\>4\</lift\_id\>  
             \<total\_igoerak\>1218\</total\_igoerak\>  
         \</igoera\_kopuru\_agregatua\>  
         \<igoera\_kopuru\_agregatua\>  
             \<resort\_id\>3\</resort\_id\>  
             \<lift\_id\>5\</lift\_id\>  
             \<total\_igoerak\>3080\</total\_igoerak\>  
         \</igoera\_kopuru\_agregatua\>  
         \<igoera\_kopuru\_agregatua\>  
             \<resort\_id\>3\</resort\_id\>  
             \<lift\_id\>2\</lift\_id\>  
             \<total\_igoerak\>1240\</total\_igoerak\>  
         \</igoera\_kopuru\_agregatua\>  
         \<igoera\_kopuru\_agregatua\>  
             \<resort\_id\>2\</resort\_id\>  
             \<lift\_id\>3\</lift\_id\>  
             \<total\_igoerak\>1896\</total\_igoerak\>  
         \</igoera\_kopuru\_agregatua\>  
         \<igoera\_kopuru\_agregatua\>  
             \<resort\_id\>1\</resort\_id\>  
             \<lift\_id\>2\</lift\_id\>  
             \<total\_igoerak\>1068\</total\_igoerak\>  
         \</igoera\_kopuru\_agregatua\>  
         \<igoera\_kopuru\_agregatua\>  
             \<resort\_id\>3\</resort\_id\>  
             \<lift\_id\>3\</lift\_id\>  
             \<total\_igoerak\>1787\</total\_igoerak\>  
         \</igoera\_kopuru\_agregatua\>  
         \<igoera\_kopuru\_agregatua\>  
             \<resort\_id\>1\</resort\_id\>  
             \<lift\_id\>5\</lift\_id\>  
             \<total\_igoerak\>1138\</total\_igoerak\>  
         \</igoera\_kopuru\_agregatua\>  
         \<igoera\_kopuru\_agregatua\>  
             \<resort\_id\>1\</resort\_id\>  
             \<lift\_id\>3\</lift\_id\>  
             \<total\_igoerak\>557\</total\_igoerak\>  
         \</igoera\_kopuru\_agregatua\>  
         \<igoera\_kopuru\_agregatua\>  
             \<resort\_id\>1\</resort\_id\>  
             \<lift\_id\>1\</lift\_id\>  
             \<total\_igoerak\>2787\</total\_igoerak\>  
         \</igoera\_kopuru\_agregatua\>  
         \<demografia\_datuak\>  
             \<resort\_id\>1\</resort\_id\>  
             \<forfait\_type\>junior\</forfait\_type\>  
             \<total\_igoerak\>1313\</total\_igoerak\>  
         \</demografia\_datuak\>  
         \<demografia\_datuak\>  
             \<resort\_id\>3\</resort\_id\>  
             \<forfait\_type\>adult\</forfait\_type\>  
             \<total\_igoerak\>4249\</total\_igoerak\>  
         \</demografia\_datuak\>  
         \<demografia\_datuak\>  
             \<resort\_id\>3\</resort\_id\>  
             \<forfait\_type\>junior\</forfait\_type\>  
             \<total\_igoerak\>2132\</total\_igoerak\>  
         \</demografia\_datuak\>  
         \<demografia\_datuak\>  
             \<resort\_id\>2\</resort\_id\>  
             \<forfait\_type\>adult\</forfait\_type\>  
             \<total\_igoerak\>5685\</total\_igoerak\>  
         \</demografia\_datuak\>  
         \<demografia\_datuak\>  
             \<resort\_id\>1\</resort\_id\>  
             \<forfait\_type\>adult\</forfait\_type\>  
             \<total\_igoerak\>4099\</total\_igoerak\>  
         \</demografia\_datuak\>  
         \<demografia\_datuak\>  
             \<resort\_id\>2\</resort\_id\>  
             \<forfait\_type\>retired\</forfait\_type\>  
             \<total\_igoerak\>1457\</total\_igoerak\>  
         \</demografia\_datuak\>  
         \<demografia\_datuak\>  
             \<resort\_id\>1\</resort\_id\>  
             \<forfait\_type\>retired\</forfait\_type\>  
             \<total\_igoerak\>1265\</total\_igoerak\>  
         \</demografia\_datuak\>  
         \<demografia\_datuak\>  
             \<resort\_id\>3\</resort\_id\>  
             \<forfait\_type\>retired\</forfait\_type\>  
             \<total\_igoerak\>2156\</total\_igoerak\>  
         \</demografia\_datuak\>  
         \<demografia\_datuak\>  
             \<resort\_id\>2\</resort\_id\>  
             \<forfait\_type\>junior\</forfait\_type\>  
             \<total\_igoerak\>1416\</total\_igoerak\>  
         \</demografia\_datuak\>  
         \<erabilera\_gailurrak\>  
             \<ordua\>13:00\</ordua\>  
             \<total\_igoerak\>2987\</total\_igoerak\>  
         \</erabilera\_gailurrak\>  
         \<erabilera\_gailurrak\>  
             \<ordua\>11:00\</ordua\>  
             \<total\_igoerak\>5628\</total\_igoerak\>  
         \</erabilera\_gailurrak\>  
         \<erabilera\_gailurrak\>  
             \<ordua\>10:00\</ordua\>  
             \<total\_igoerak\>2125\</total\_igoerak\>  
         \</erabilera\_gailurrak\>  
         \<erabilera\_gailurrak\>  
             \<ordua\>12:00\</ordua\>  
             \<total\_igoerak\>4929\</total\_igoerak\>  
         \</erabilera\_gailurrak\>  
         \<erabilera\_gailurrak\>  
             \<ordua\>09:00\</ordua\>  
             \<total\_igoerak\>7215\</total\_igoerak\>  
         \</erabilera\_gailurrak\>  
         \<erabilera\_gailurrak\>  
             \<ordua\>07:00\</ordua\>  
             \<total\_igoerak\>244\</total\_igoerak\>  
         \</erabilera\_gailurrak\>  
         \<erabilera\_gailurrak\>  
             \<ordua\>08:00\</ordua\>  
             \<total\_igoerak\>644\</total\_igoerak\>  
         \</erabilera\_gailurrak\>  
     \</data\>  
 \</root\>

Behin hau edukita, htmla sortu dugu:  
\<\!DOCTYPE html\>  
\<html lang\="es"\>  
\<head\>  
  \<meta charset\="UTF-8" /\>  
  \<title\>Buscador Skiers\</title\>  
  \<link rel\="stylesheet" href\="CSS/style.css"\>  
\</head\>  
\<body\>  
   \<nav class\="navbar"\>  
        \<div class\="logo"\>LOS\<span\>GALACTICOS\</span\>\</div\>  
        \<ul class\="nav-links" id\="navLinks"\>  
            \<li\>\<a href\="Erronka.html"\>Hasiera\</a\>\</li\>  
            \<li\>\<a href\="Pistak.html"\>Pistak\</a\>\</li\>  
            \<li\>\<a href\="Ikasgaiak.html"\>Ikasgaiak\</a\>\</li\>  
            \<li\>\<a href\="Denda.html"\>Denda\</a\>\</li\>  
            \<li\>\<a href\="Datuak.html"\>Datuak\</a\>\</li\>  
        \</ul\>  
    \</nav\>

  \<h1\>Buscador\</h1\>

\<div class\="datosmostrar"\>  
  \<div class\="resortak"\>  
    \<label for\="resortselect"\>Resortak\</label\>  
    \<select id\="resortselect"\>  
        \<option value\="1"\>1\</option\>  
        \<option value\="2"\>2\</option\>  
        \<option value\="3"\>3\</option\>  
    \</select\>  
  \</div\>  
\</div\>  
    \<button id\="btnBuscar"\>Buscar\</button\>  
\</div\>

\<div class\="data-container"\>  
    \<div id\="resultado"\>\</div\>  
\</div\>

  \<div class\="Grafico"\>  
    \<canvas id\="grafikoa"\>\</canvas\>  
  \</div\>

  \<script src\="JS/jquery-4.0.0.min.js"\>\</script\>  
  \<script src\="JS/chart.min.js"\>\</script\>  
  \<script src\="JS/function.js"\>\</script\>  
  \<script src\="JS/Grafico.js"\>\</script\>  
  \<footer\>  
        \<p\>Adrian, Anne, Oinatz, Salah eta Jagoba\</p\>  
    \</footer\>  
\</body\>  
\</html\>

html honetan bi sati banatu beharko ditugu, biñeten zatia eta grafiko zatia.  
Biñetaren satian, hau ipiniko genuke jsan:  
$.ajax({  
      url: 'DATUAK/datuak.xml',  
      dataType: 'xml',  
      success: function (erantzuna) {  
        var html \= "";  
        var datuiragaziak \= \[\];

         
        $(erantzuna).find('igoera\_kopuru\_agregatua').each(function () {  
          var Resortak \= $(this).find('resort\_id').text();  
          var Lift \= $(this).find('lift\_id').text();  
          var Igoerak \= $(this).find('total\_igoerak').text();

          if (Resortak \=== ResortAutatuta) {  
            html \+= "\<div class='data-card'\>";  
            html \+= "  \<div class='data-item'\>";  
            html \+= "    \<span class='label'\>Resort ID\</span\>";  
            html \+= "    \<span class='value'\>" \+ Resortak \+ "\</span\>";  
            html \+= "  \</div\>";  
            html \+= "  \<div class='data-item'\>";  
            html \+= "    \<span class='label'\>Lift ID\</span\>";  
            html \+= "    \<span class='value'\>" \+ Lift \+ "\</span\>";  
            html \+= "  \</div\>";  
            html \+= "  \<div class='data-item'\>";  
            html \+= "    \<span class='label'\>Total Igoerak\</span\>";  
            html \+= "    \<span class='value'\>" \+ Igoerak \+ "\</span\>";  
            html \+= "  \</div\>";  
            html \+= "\</div\>";  
          }  
        });

         
        $(erantzuna).find('erabilera\_gailurrak').each(function () {  
          var Ordua \= $(this).find('ordua').text();  
          var Igoerak \= parseInt($(this).find('total\_igoerak').text());  
          datuiragaziak.push({ ordua: Ordua, total\_igoerak: Igoerak });  
        });

        if (html \=== "") {  
          $('\#resultado').html("\<p\>Ez da daturik aurkitu iragazki hauekin.\</p\>");  
          if (Grafikoa) Grafikoa.destroy();  
        } else {  
          $('\#resultado').html(html);  
          grafikoEguneratu(datuiragaziak);  
        }  
      },  
      error: function () {  
        alert("Errorea XML fitxategia kargatzerakoan.");  
      }  
    });  
  });  
});  
eta web orriaren barruak horrela ikusiko genuke:  
<img width="550" height="157" alt="image" src="https://github.com/user-attachments/assets/18199722-08d5-44c6-a3f1-5cbd89927430" />

eta bestaldetik, grafikoa egiteko, hau ikusiko beharko zen jsean:  
$(document).ready(function () {  
  var Grafikoa \= null;

  function grafikoEguneratu(datuak) {  
    var ctx \= document.getElementById('grafikoa').getContext('2d');  
    if (Grafikoa \!== null) {  
      Grafikoa.destroy();  
    }  
    datuak.sort((a, b) \=\> parseInt(a.ordua) \- parseInt(b.ordua));

    var etiketak \= datuak.map(d \=\> d.ordua);  
    var serieDatuak \= datuak.map(d \=\> d.total\_igoerak);

    Grafikoa \= new Chart(ctx, {  
      type: 'line',  
      data: {  
        labels: etiketak,  
        datasets: \[{  
          label: 'Total igoerak orduka',  
          data: serieDatuak,  
          borderColor: 'rgba(52, 152, 219, 1)',  
          backgroundColor: 'rgba(52, 152, 219, 0.2)',  
          fill: true,  
          tension: 0.3  
        }\]  
      },  
      options: {  
        maintainAspectRatio: false,  
        scales: {  
          y: { beginAtZero: true }  
        }  
      }  
    });  
  }

web orrian horrela ikusteko:  
![][image13]

Grafikoak eta txartelak egiteko ere beste js batzuk sortu behar izan ditugu:  
Query izeneko hau:  
<img width="556" height="62" alt="image" src="https://github.com/user-attachments/assets/600439c0-ddd5-4022-9787-0f1f67f05e9a" />

Charmin izeneko hau:  
<img width="545" height="136" alt="image" src="https://github.com/user-attachments/assets/70585d11-9928-4036-b3f2-0f99fa24e4a1" />

eta azkenik grafikoa funtzionatu ahal izateko js hau:  
<img width="540" height="119" alt="image" src="https://github.com/user-attachments/assets/2e47aeb3-0d3c-4ed0-8b7a-0ac3d62aa3d1" />


Dokumentazioan ikusi duzuen bezala, taulak, koloreak, irudien txartelak, grafikoak etab politak sortzeko CSS kodea erabili dugu, hau da gure css kode osoa:

\* {  
    margin: 0;  
    padding: 0;  
    box-sizing: border-box;  
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;  
}

body {  
    background-color: \#f4f7f6;  
    line-height: 1.6;  
    color: darkturquoise;  
}

.navbar {  
    display: flex;  
    justify-content: space-between;  
    align-items: center;  
    background: \#1a2a6c;  
    color: white;  
    padding: 1rem 5%;  
    position: sticky;  
    top: 0;  
    z-index: 100;  
    box-shadow: 0 2px 10px rgba(0,0,0,0.1);  
}

.logo {  
    font-size: 1.8rem;  
    font-weight: 700;  
}

.logo span {  
    color: \#00d2ff;  
}

.nav-links {  
    display: flex;  
    list-style: none;  
    gap: 30px;  
}

.nav-links a {  
    color: white;  
    text-decoration: none;  
    font-weight: 500;  
    transition: color 0.3s ease;  
}

.nav-links a:hover {  
    color: \#00d2ff;  
}

.hero {  
    height: 70vh;  
    background-color: \#00d2ff;  
    display: flex;  
    flex-direction: column;  
    justify-content: center;  
    align-items: center;  
    color: white;  
    text-align: center;  
    padding: 20px;  
}

.hero h1 {  
    font-size: 3.5rem;  
    margin-bottom: 1rem;  
    text-shadow: 2px 2px 4px rgba(0,0,0,0.7);  
}

.hero p {  
    font-size: 1.5rem;  
    margin-bottom: 2rem;  
    text-shadow: 1px 1px 3px rgba(0,0,0,0.7);  
}

.btn-main {  
    background-color: white;  
    color:  \#00d2ff;  
    padding: 15px 30px;  
    border: none;  
    border-radius: 50px;  
    font-size: 1.1rem;  
    cursor: pointer;  
    transition: background-color 0.3s ease, transform 0.2s ease;  
}

.btn-main:hover {  
    background-color: \#00a8cc;  
    transform: translateY(\-2px);  
}

.container {  
    text-align: center;  
    max-width: 1200px;  
    margin: 0 auto;  
}

.container h2 {  
    font-size: 2.5rem;  
    margin-bottom: 3rem;  
    color: \#1a2a6c;  
}

.flex-grid {  
    display: flex;  
    flex-wrap: wrap;  
    gap: 30px;  
    justify-content: center;  
    margin-top: 2rem;  
}

.card {  
    flex: 1 1 300px;  
    background: white;  
    padding: 2rem;  
    border-radius: 12px;  
    box-shadow: 0 8px 25px rgba(0,0,0,0.1);  
    transition: transform 0.3s ease;  
    display: flex;  
    flex-direction: column;  
    align-items: center;  
    text-align: center;  
}

.card:hover {  
    transform: translateY(\-5px);  
}

.card img {  
    width: 100%;  
    max-height: 200px;  
    object-fit: cover;  
    border-radius: 8px;  
    margin-bottom: 1.5rem;  
}

.card h3 {  
    font-size: 1.8rem;  
    margin-bottom: 1rem;  
    color: \#1a2a6c;  
}

.card p {  
    font-size: 1.1rem;  
    color: \#555;  
}

footer {  
    background: \#1a2a6c;  
    color: white;  
    text-align: center;  
    padding: 2rem 5%;  
    margin-top: 4rem;  
    font-size: 0.9rem;  
}

.burger {  
    display: none;  
    cursor: pointer;  
    flex-direction: column;  
    justify-content: space-around;  
    width: 30px;  
    height: 25px;  
}

.burger span {  
    display: block;  
    width: 100%;  
    height: 3px;  
    background: white;  
    transition: all 0.3s ease;  
}

@media (max-width: 768px) {  
    .nav-links {  
        display: none;  
        flex-direction: column;  
        width: 100%;  
        background: \#1a2a6c;  
        position: absolute;  
        top: 70px;  
        left: 0;  
        padding: 1rem 0;  
    }

    .nav-links.active {  
        display: flex;  
    }

    .nav-links li {  
        text-align: center;  
        margin: 10px 0;  
    }

    .burger {  
        display: flex;  
    }

    .hero h1 {  
        font-size: 2.5rem;  
    }

    .hero p {  
        font-size: 1.2rem;  
    }

    .container h2 {  
        font-size: 2rem;  
    }  
}

.data-container {  
    display: flex;  
    flex-direction: column;  
    gap: 15px;  
    max-width: 900px;  
    margin: 0 auto;  
}

.data-card {  
    display: flex;  
    flex-wrap: wrap;  
    background: white;  
    padding: 15px;  
    border-radius: 8px;  
    box-shadow: 0 2px 4px rgba(0,0,0,0.1);  
    align-items: center;  
    border-left: 5px solid \#3498db;  
}

.data-item {  
    flex: 1;  
    min-width: 150px;  
    padding: 5px 10px;  
}

.label {  
    display: block;  
    font-size: 0.75rem;  
    color: \#7f8c8d;  
    text-transform: uppercase;  
    font-weight: bold;  
}

.value {  
    font-size: 1rem;  
    color: \#2c3e50;  
    font-weight: 500;  
}

.adult { color: \#2980b9; }  
.retired { color: \#27ae60; }  
.junior { color: \#f39c12; }

.search-container {  
    max-width: 900px;  
    margin: 0 auto 20px auto;  
}

\#searchInput {  
    width: 100%;  
    padding: 12px 20px;  
    font-size: 1rem;  
    border: 2px solid \#ddd;  
    border-radius: 25px;  
    outline: none;  
    transition: border-color 0.3s;  
    box-sizing: border-box;  
}

\#searchInput:focus {  
    border-color: \#3498db;  
    box-shadow: 0 0 8px rgba(52, 152, 219, 0.2);  
}

.Grafico{  
    background-color: white;  
    margin-left: 5%;  
    margin-right: 5%;  
}

