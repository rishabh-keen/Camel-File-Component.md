<img src="https://ezeiatech.com/wp-content/uploads/2019/05/apache-camel-interview-questions.jpg">
 <h1 align="center">𝕮𝖆𝖒𝖊𝖑 𝕱𝖎𝖑𝖊 𝕮𝖔𝖒𝖕𝖔𝖓𝖊𝖓𝖙 <h1>
  
## ᴡʜᴀᴛ ɪs ғɪʟᴇ ᴄᴏᴍᴘᴏɴᴇɴᴛ?
The File component provides access to file systems, allowing files to be processed by any other Camel Components or messages from other components to be saved to disk..
  
  <hr>
  <h3 align=center> 🆃🅷🅸🆂 🅸🆂 🅲🅾🅳🅴 🅾🅵 🅵🅸🅻🅴 🅲🅾🅼🅿🅾🅽🅴🅽🆃 </h3>
  
  <br><br>
  
  :one: **ᴡʜʏ ᴀʀᴇ ᴡᴇ ᴜsᴇᴅ, ʀᴏᴜᴛᴇ ɪᴅ="sɪᴍᴘʟᴇ-ʀᴏᴜᴛᴇ" ɪɴ ᴄᴀᴍᴇʟ ғɪʟᴇ ᴄᴏᴍᴘᴏɴᴇɴᴛ**
  
  We can use multiple route IDs in a CamelContext project.  But it should be noted that the name of each route ID should be different.
  
  <br><br><br>
  
  
 :two: **<ғʀᴏᴍ ɪᴅ="ʀᴏᴜᴛᴇ-ᴛɪᴍᴇʀ" ᴜʀɪ="ғɪʟᴇ:/ʜᴏᴍᴇ/ʀɪsʜᴀʙʜ/ᴅᴏᴡɴʟᴏᴀᴅs/ɪɴᴘᴜᴛ?ɴᴏᴏᴘ=ᴛʀᴜᴇ&ᴀᴍᴘ;ɪɴᴄʟᴜᴅᴇ=.*.ᴄsᴠ&ᴀᴍᴘ;ᴅᴇʟᴀʏ=𝟷𝟶𝟶𝟶𝟶&ᴀᴍᴘ;sᴏʀᴛʙʏ=ʀᴇᴠᴇʀsᴇ:ғɪʟᴇ:ᴍᴏᴅɪғɪᴇᴅ"/>**
  
  In the uri option, we will write the file component next.  Then we will give the path of our producer. <br> **ⓃⓄⓄⓅ -** If the condition of our noop is true then the file will only be copied.  If the condition of our noop is false then the file will be deleted from the producer and go to the consumer. <br> **ⒾⓃⒸⓁⓊⒹⒺ -** And include means.  We can also define our type in which type of file we want to send. <br> **ⒹⒺⓁⒶⓎ -** And we are using delay because in how long will our file go. <br> **&ⓐⓜⓟ -** And we are using & amp because we can use multiple components on the same line. <br> **ⓢⓞⓡⓣⒷⓨ -** And sortBy we are doing shorting of files. <br> 
  <br>
  <br>
  3️⃣ **ᴡʜʏ ᴀʀᴇ ᴡᴇ ᴜsᴇᴅ, ʀᴏᴜᴛᴇ ɪᴅ="sɪᴍᴘʟᴇ-ʀᴏᴜᴛᴇ" ɪɴ ᴄᴀᴍᴇʟ ғɪʟᴇ ᴄᴏᴍᴘᴏɴᴇɴᴛ**
  
  And we are using the log before receiving the file.  Therefore, just before the file is received, our log will be printed and the message will be Hello.
  <br>
  <br>
  <br>
  
   4️⃣ **ᴡʜʏ ᴀʀᴇ ᴡᴇ ᴜsᴇᴅ, <ᴛᴏ ɪᴅ="ᴛᴏ-ɪᴅ" ᴜʀɪ="ғɪʟᴇ:/ʜᴏᴍᴇ/ʀɪsʜᴀʙʜ/ᴅᴏᴡɴʟᴏᴀᴅs/ᴏᴜᴛᴘᴜᴛ?ᴅᴏɴᴇғɪʟᴇɴᴀᴍᴇ=${ғɪʟᴇ:ɴᴀᴍᴇ}.ᴅᴏɴᴇ"/> ɪɴ ᴄᴀᴍᴇʟ ғɪʟᴇ ᴄᴏᴍᴘᴏɴᴇɴᴛ**
 
  In the option, we give the path where we want the file.
 <br> 
 <br>
 <br>
 :five: **ᴡʜʏ ᴀʀᴇ ᴡᴇ ᴜsᴇᴅ, <ʟᴏɢ ɪᴅ="ʀᴏᴜᴛᴇ-ʟᴏɢ" ᴍᴇssᴀɢᴇ=">>> ʜᴇᴀᴅᴇʀs : ${ʜᴇᴀᴅᴇʀs}"/> ɪɴ ᴄᴀᴍᴇʟ ғɪʟᴇ ᴄᴏᴍᴘᴏɴᴇɴᴛ**
 
 And in this header log our header log is generated such as in the output folder from where we are sending the file and the path of the input folder where the file is going.
