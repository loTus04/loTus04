
<img align='right' src="https://github.com/loTus04/loTus04/blob/main/img/Webp.net-resizeimage.gif">

# Hellooooo there! <img src="https://github.com/loTus04/loTus04/blob/main/img/wave.gif" width="30px">
<!DOCTYPE html>
<html>
<head>

<style>
 #typing-text {
     color: #63B54E;
     border: ridge 0px #A8A8A8;
     font-weight: bold;
     text-align: left;
     font-family: Courier New;
     overflow: hidden;
     background-color: #000000;
     font-size: 14px;
     height: 204px;
     width: 500px;
     outline: none;
     resize: none;
     box-sizing: border-box;
}
</style>
</head>
<body>
<textarea id="typing-text" readonly></textarea>


<script>
(function () {
   var CharacterPos = 0;
   var MsgBuffer = "";
   var TypeDelay = 50; 
   var NxtMsgDelay = 1000;
   var MsgIndex = 0;
   var delay;
   var MsgArray = ["I am a young passionate about cybersecurity and IT in general. I mainly program in python. Get ready to see one of the best python content of all Github ! (Just kidding, Im shit)\nNever forget: Python > * !"];

   function StartTyping() {
      var id = document.getElementById("typing-text");
      if (CharacterPos != MsgArray[MsgIndex].length) {
         MsgBuffer  = MsgBuffer + MsgArray[MsgIndex].charAt(CharacterPos);
         id.value = MsgBuffer+"_";
         delay = TypeDelay;
         id.scrollTop = id.scrollHeight; 
      } else {
         delay = NxtMsgDelay;
         MsgBuffer   = "";
         CharacterPos = -1;
         if (MsgIndex!=MsgArray.length-1){
           MsgIndex++;
         }else {
           MsgIndex = 0;
         }
       }
       CharacterPos++;
       setTimeout(StartTyping,delay);
   }
StartTyping();
})();
</script>

</body>
</html>

# :book: 𝙰𝚋𝚘𝚞𝚝 𝙼𝚎
- 🖥 Python developer
- 💼 15 years
- 🇫🇷 French
- 🎮 Gammer


## 📫 𝙿𝚛𝚘𝚏𝚒𝚕𝚎𝚜
- 🧠 Root-Me : [Click](https://www.root-me.org/loTus01)
- 👨‍💻 TryHackMe : [Click](https://tryhackme.com/p/loTus)
- 🖤 Github : [Click](https://github.com/loTus04)
- 💬 Discord : loTus01#7075

## &#x1f4c8; GitHub Stats

<a href="https://github.com/loTus04">
  <img align="center" src="https://github-readme-stats.vercel.app/api/top-langs/?username=loTus04&hide=java,html&title_color=ff3855&text_color=30d5c8&icon_color=ffff00&bg_color=291b29" />
</a>
<a href="https://github.com/loTus04">
  <img align="center" src="https://github-readme-stats.vercel.app/api?username=loTus04&show_icons=true&line_height=27&count_private=true&title_color=ff3855&text_color=30d5c8&icon_color=ffff00&bg_color=291b29" alt="loTus04's GitHub Stats" />
</a>
