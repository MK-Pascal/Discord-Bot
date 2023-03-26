# MK Open Source Files

## 🎫 Ticket system v1.3

Hier habe ich für euch ein kleines Ticket System was eins meiner ersten Ticket Systeme war, die ich gemacht habe. Deswegen hat es nur halb so viele Features, wie ein gutes Ticket System.



## 📋 Features 
- Einen Cooldown von 120 Sekunden verhindert es, dass zu viele Tickets geöffnet werden können.  
- Es hat einen Ticket-Count, der die Anzahl der Tickets hochzählt, wenn ein neues Ticket geöffnet wird.  
- Die Chatverläufe werden in einen Log Channel gesendet.



## 🛠️ Einrichtung
***
1. Zuerst muss mit `/ticket send` oder `/ticket guild` die Guild ID hinzugefügt werden, damit der Ticket Count hochgezählt werden kann.  
    `/ticket send` sendet das Embed, das für das Erstellen eines Tickets zuständig ist.  
    `/ticket guild` kann verwendet werden, um die Guild ID zu aktualisieren, ohne den `/ticket send` Befehl erneut zu verwenden.

‎ 

<div class="ok">
  <video width="640px" height="320px" controls id="myVideo">
    <style>
		video {
			max-width: auto;
			height: auto;
            border-radius: 20px;
            border: solid 5px #3F3F3F;
		}
	</style>
    <source src="https://cdn.discordapp.com/attachments/1089596110806466672/1089596415963041792/Ticket_senden.mp4" type="video/mp4">
  </video>
    <script>
  var video = document.getElementById("myVideo");
  video.setAttribute("controlsList", "nodownload");
</script>
</div>

***
##  ⌛ Cooldown
2. Durch den Cooldown kann man erst aller 2 Minuten wieder ein neues Ticket öffnen.  
Damit ist es auch durch einen Raid geschützt.
<div>
  <img width="auto" height="auto" src="https://cdn.discordapp.com/attachments/1089596110806466672/1089646286225018952/image.png">
  </img>
</div>

***

## 🏷️ Embed
3. Sobald das Embed erstellt wurde können auch schon die Ticket erstellt werden.  
Es ist wichtig das die richtigen ID's eingetragen sind, sonst können keine Ticket's erstellt werden.

<div>
  <video width="640" height="320" controls>
  	<style>
		video {
			max-width: auto;
			height: auto;
		}
	</style>
    <source src="https://cdn.discordapp.com/attachments/1089596110806466672/1089596416562835456/ticket_erstellen.mp4" type="video/mp4">
  </video>
</div> 


***

## 📝 Chatverlauf
4. Nachdem das Ticket geschlossen wurde, wird der Chatverlauf zusammen mit einem Embed und einen .txt File in einen Log-Channel gesendet.  
Dadurch ist der Chatverlauf auch noch für spätereZwecke verfügbar.  
Diese Funktion ist äußerst nützlich, da man jederzeit auf vergangene Chats zurückgreifen kann, um Probleme nachzuvollziehen oder um sich an frühere Konversationen zu erinnern.
<div>
  <img width="auto" height="auto" src="https://cdn.discordapp.com/attachments/1089596110806466672/1089657878039761037/Comp_1_01469.png">
  </img>
</div>   

<div style="border-radius: 15px; overflow: hidden; width: 50%; margin: auto;">
  <video style="border-radius: 35px;" width="100%" height="auto" controls>
    <source src="yourvideo.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>
</div>

<footer class="text glass" align="center">
    Make by MK_Pascal#0505
    <style>
        .text{
            margin-top: 5%;
            background-color: black;
            position: absolute;
            height: 50px;
            width: 120px;
            left: 50%;
            transform: translate(-50%, -50%);
        }
        .glass{
        background: linear-gradient(135deg, rgba(63, 63, 63, 0.1), rgba(63, 63, 63, 0.2));
        backdrop-filter: blur(10px);
        -webkit-backdrop-filter: blur(10px);
        border-radius: 20px;
        border:1px solid rgba(255, 255, 255, 0.18);
        box-shadow: 0 0px 32px 0 rgba(0, 0, 0, 0.20);
        transition: 400ms;
        }
        .glass:hover{
        background: linear-gradient(135deg, rgba(99, 48, 246, 0.1), rgba(99, 48, 246, 0.2));
        border-radius: 15px;
        }
    </style>
</footer>



