<img src="https://ezeiatech.com/wp-content/uploads/2019/05/apache-camel-interview-questions.jpg">
 <h1 align="center">𝕮𝖆𝖒𝖊𝖑 𝕱𝖎𝖑𝖊 𝕮𝖔𝖒𝖕𝖔𝖓𝖊𝖓𝖙 <h1>
  
## ᴡʜᴀᴛ ɪs Fɪʟᴇ ᴄᴏᴍᴘᴏɴᴇɴᴛ?
The File component provides access to file systems, allowing files to be processed by any other Camel Components or messages from other components to be saved to disk..
  
  <hr>
  <h3 align=center> 🆃🅷🅸🆂 🅸🆂 🅲🅾🅳🅴 🅾🅵 🅵🅸🅻🅴 🅲🅾🅼🅿🅾🅽🅴🅽🆃 </h3>
 
 **Note :-** Before reading the option of all these codes, you click on the **Code Pic**. After seeing the code, you will be able to understand all these options and their theory.
  
  <br>
  <details close="close"> 
  <summary><b>Code Pic</b></summary>   
     
   <p align ="center"><img src="https://github.com/rishabh-keen/photos.md/blob/master/1.png"></p>
  </details>
 
   <details close="close"> 
  <summary><b>Log Pic</b></summary>   
     
   <p align ="center"><img src="https://github.com/rishabh-keen/photos.md/blob/master/2.png"></p>
  </details>
 
   <details close="close"> 
  <summary><b>POM File</b></summary>   
     
   <h4>https://github.com/rishabh-keen/photos.md/blob/master/pom</h4>
  </details>
 <br>
 <br>
  
   <details close="close"> 
  <summary><b>:one: 𝙒𝙝𝙮 𝘼𝙧𝙚 𝙒𝙚 𝙐𝙨𝙚𝙙, <𝙧𝙤𝙪𝙩𝙚 𝙞𝙙> 𝙄𝙣 𝘾𝙖𝙢𝙚𝙡 𝙁𝙞𝙡𝙚𝘾𝙤𝙢𝙥𝙤𝙣𝙚𝙣𝙩</b></summary>   
     
   <p align ="center"><img src="https://github.com/rishabh-keen/photos.md/blob/master/id.png"></p>
  </details>
  
  We can use multiple route IDs in a CamelContext project.  But it should be noted that the name of each route ID should be different.
  <br>
 <br>
 
 :two: <𝙛𝙧𝙤𝙢 𝙞𝙙="𝙧𝙤𝙪𝙩𝙚-𝙩𝙞𝙢𝙚𝙧" 𝙪𝙧𝙞="𝙛𝙞𝙡𝙚:/𝙝𝙤𝙢𝙚/𝙧𝙞𝙨𝙝𝙖𝙗𝙝/𝘿𝙤𝙬𝙣𝙡𝙤𝙖𝙙𝙨/𝙞𝙣𝙥𝙪𝙩?𝙣𝙤𝙤𝙥=𝙩𝙧𝙪𝙚&𝙖𝙢𝙥;𝙞𝙣𝙘𝙡𝙪𝙙𝙚=.*.𝙘𝙨𝙫&𝙖𝙢𝙥;𝙙𝙚𝙡𝙖𝙮=10000&𝙖𝙢𝙥;𝙨𝙤𝙧𝙩𝘽𝙮=𝙧𝙚𝙫𝙚𝙧𝙨𝙚:𝙛𝙞𝙡𝙚:𝙢𝙤𝙙𝙞𝙛𝙞𝙚𝙙"/>
  
  In the uri option, we will write the file component next.  Then we will give the path of our producer. <br> **ⓃⓄⓄⓅ -** If the condition of our noop is true then the file will only be copied.  If the condition of our noop is false then the file will be deleted from the producer and go to the consumer. <br> **ⒾⓃⒸⓁⓊⒹⒺ -** And include means.  We can also define our type in which type of file we want to send. <br> **ⒹⒺⓁⒶⓎ -** And we are using delay because in how long will our file go. <br> **&ⓐⓜⓟ -** And we are using & amp because we can use multiple components on the same line. <br> **ⓢⓞⓡⓣⒷⓨ -** And sortBy we are doing shorting of files. <br> 
  <br>
  <br>
  3️⃣ 𝙒𝙝𝙮 𝙖𝙧𝙚 𝙬𝙚 𝙪𝙨𝙚𝙙, <𝙡𝙤𝙜 𝙞𝙙="𝙧𝙤𝙪𝙩𝙚-𝙡𝙤𝙜" 𝙢𝙚𝙨𝙨𝙖𝙜𝙚=">>> 𝙃𝙚𝙡𝙡𝙤"/> 𝙞𝙣 𝙘𝙖𝙢𝙚𝙡 𝙁𝙞𝙡𝙚𝙘𝙤𝙢𝙥𝙤𝙣𝙚𝙣𝙩
  
  And we are using the log before receiving the file.  Therefore, just before the file is received, our log will be printed and the message will be Hello.
  <br>
  <br>
  <br>
  
   4️⃣ 𝙒𝙝𝙮 𝙖𝙧𝙚 𝙬𝙚 𝙪𝙨𝙚𝙙, <𝙩𝙤 𝙞𝙙="𝙩𝙤-𝙞𝙙" 𝙪𝙧𝙞="𝙛𝙞𝙡𝙚:/𝙝𝙤𝙢𝙚/𝙧𝙞𝙨𝙝𝙖𝙗𝙝/𝘿𝙤𝙬𝙣𝙡𝙤𝙖𝙙𝙨/𝙤𝙪𝙩𝙥𝙪𝙩?𝙙𝙤𝙣𝙚𝙁𝙞𝙡𝙚𝙉𝙖𝙢𝙚=${𝙛𝙞𝙡𝙚:𝙣𝙖𝙢𝙚}.𝙙𝙤𝙣𝙚"/> 𝙞𝙣 𝙘𝙖𝙢𝙚𝙡 𝙁𝙞𝙡𝙚𝙘𝙤𝙢𝙥𝙤𝙣𝙚𝙣𝙩
 
  In the option, we give the path where we want the file.
 <br> 
 <br>
 <br>
 :five: 𝙒𝙝𝙮 𝙖𝙧𝙚 𝙬𝙚 𝙪𝙨𝙚𝙙, <𝙡𝙤𝙜 𝙞𝙙="𝙧𝙤𝙪𝙩𝙚-𝙡𝙤𝙜" 𝙢𝙚𝙨𝙨𝙖𝙜𝙚=">>> 𝙝𝙚𝙖𝙙𝙚𝙧𝙨 : ${𝙝𝙚𝙖𝙙𝙚𝙧𝙨}"/> 𝙞𝙣 𝙘𝙖𝙢𝙚𝙡 𝙁𝙞𝙡𝙚𝙘𝙤𝙢𝙥𝙤𝙣𝙚𝙣𝙩
 
 And in this header log our header log is generated such as in the output folder from where we are sending the file and the path of the input folder where the file is going.

 
  
