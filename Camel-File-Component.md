<img src="https://ezeiatech.com/wp-content/uploads/2019/05/apache-camel-interview-questions.jpg">
 <h1 align="center">๐ฎ๐๐๐๐ ๐ฑ๐๐๐ ๐ฎ๐๐๐๐๐๐๐๐ <h1>
  
## แดกสแดแด ษชs Fษชสแด แดแดแดแดแดษดแดษดแด?
The File component provides access to file systems, allowing files to be processed by any other Camel Components or messages from other components to be saved to disk..
  
  <hr>
  <h3 align=center> ๐๐ท๐ธ๐ ๐ธ๐ ๐ฒ๐พ๐ณ๐ด ๐พ๐ต ๐ต๐ธ๐ป๐ด ๐ฒ๐พ๐ผ๐ฟ๐พ๐ฝ๐ด๐ฝ๐ </h3>
 
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
  <summary><b>:one: ๐๐๐ฎ ๐ผ๐ง๐ ๐๐ ๐๐จ๐๐, <๐ง๐ค๐ช๐ฉ๐ ๐๐> ๐๐ฃ ๐พ๐๐ข๐๐ก ๐๐๐ก๐๐พ๐ค๐ข๐ฅ๐ค๐ฃ๐๐ฃ๐ฉ</b></summary>   
     
   <p align ="center"><img src="https://github.com/rishabh-keen/photos.md/blob/master/id.png"></p>
  </details>
  
  We can use multiple route IDs in a CamelContext project.  But it should be noted that the name of each route ID should be different.
  <br>
 <br>
 
 :two: <๐๐ง๐ค๐ข ๐๐="๐ง๐ค๐ช๐ฉ๐-๐ฉ๐๐ข๐๐ง" ๐ช๐ง๐="๐๐๐ก๐:/๐๐ค๐ข๐/๐ง๐๐จ๐๐๐๐/๐ฟ๐ค๐ฌ๐ฃ๐ก๐ค๐๐๐จ/๐๐ฃ๐ฅ๐ช๐ฉ?๐ฃ๐ค๐ค๐ฅ=๐ฉ๐ง๐ช๐&๐๐ข๐ฅ;๐๐ฃ๐๐ก๐ช๐๐=.*.๐๐จ๐ซ&๐๐ข๐ฅ;๐๐๐ก๐๐ฎ=10000&๐๐ข๐ฅ;๐จ๐ค๐ง๐ฉ๐ฝ๐ฎ=๐ง๐๐ซ๐๐ง๐จ๐:๐๐๐ก๐:๐ข๐ค๐๐๐๐๐๐"/>
  
  In the uri option, we will write the file component next.  Then we will give the path of our producer. <br> **โโโโ -** If the condition of our noop is true then the file will only be copied.  If the condition of our noop is false then the file will be deleted from the producer and go to the consumer. <br> **โพโโธโโโนโบ -** And include means.  We can also define our type in which type of file we want to send. <br> **โนโบโโถโ -** And we are using delay because in how long will our file go. <br> **&โโโ -** And we are using & amp because we can use multiple components on the same line. <br> **โขโโกโฃโทโจ -** And sortBy we are doing shorting of files. <br> 
  <br>
  <br>
  3๏ธโฃ ๐๐๐ฎ ๐๐ง๐ ๐ฌ๐ ๐ช๐จ๐๐, <๐ก๐ค๐ ๐๐="๐ง๐ค๐ช๐ฉ๐-๐ก๐ค๐" ๐ข๐๐จ๐จ๐๐๐=">>> ๐๐๐ก๐ก๐ค"/> ๐๐ฃ ๐๐๐ข๐๐ก ๐๐๐ก๐๐๐ค๐ข๐ฅ๐ค๐ฃ๐๐ฃ๐ฉ
  
  And we are using the log before receiving the file.  Therefore, just before the file is received, our log will be printed and the message will be Hello.
  <br>
  <br>
  <br>
  
   4๏ธโฃ ๐๐๐ฎ ๐๐ง๐ ๐ฌ๐ ๐ช๐จ๐๐, <๐ฉ๐ค ๐๐="๐ฉ๐ค-๐๐" ๐ช๐ง๐="๐๐๐ก๐:/๐๐ค๐ข๐/๐ง๐๐จ๐๐๐๐/๐ฟ๐ค๐ฌ๐ฃ๐ก๐ค๐๐๐จ/๐ค๐ช๐ฉ๐ฅ๐ช๐ฉ?๐๐ค๐ฃ๐๐๐๐ก๐๐๐๐ข๐=${๐๐๐ก๐:๐ฃ๐๐ข๐}.๐๐ค๐ฃ๐"/> ๐๐ฃ ๐๐๐ข๐๐ก ๐๐๐ก๐๐๐ค๐ข๐ฅ๐ค๐ฃ๐๐ฃ๐ฉ
 
  In the option, we give the path where we want the file.
 <br> 
 <br>
 <br>
 :five: ๐๐๐ฎ ๐๐ง๐ ๐ฌ๐ ๐ช๐จ๐๐, <๐ก๐ค๐ ๐๐="๐ง๐ค๐ช๐ฉ๐-๐ก๐ค๐" ๐ข๐๐จ๐จ๐๐๐=">>> ๐๐๐๐๐๐ง๐จ : ${๐๐๐๐๐๐ง๐จ}"/> ๐๐ฃ ๐๐๐ข๐๐ก ๐๐๐ก๐๐๐ค๐ข๐ฅ๐ค๐ฃ๐๐ฃ๐ฉ
 
 And in this header log our header log is generated such as in the output folder from where we are sending the file and the path of the input folder where the file is going.

 
  
