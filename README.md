# Mahshad-Ahmad
Programmers 
 <html> 
        <head>
             <meta name="viewport" content="width=device-width, intial-scale=1">
             <title> Form </title>
       </head>
  <style>
     
   form {
        font-family:'Itim', cursive;
        
   }

   button{
          border:2px solid black;
          padding:17px 15px;
          border-radius:15px 14px;
          width:100%;
          cursor:pointer;
          font-family:'Roboto', sans-serif;
          font-size:15px;
          background-color:rgb(225,195,225);
          box-shadow: 5px 5px grey;  
}


  
.p  {
      padding:1px 3px;
      border:4px solid black;
      border-radius:15px;
      font-family: 'Roboto', sans-serif;
      font-size:17px;
   }
  
 textarea {
                font-family: 'Itim', cursive;
                border: 1px solid;
                padding: 10px;
                box-shadow: 5px 10px red;   
               
             }
          
select{
          font-family:'Roboto', sans-serif;
        }

a {
   text-decoration:none;
   border:3px solid black;
   padding: 10px  15px;
   border-radius:15px;
   background-color:skyblue;
  }
  
h2 {
    font-family: 'Girassol', cursive;
     border:2px solid black;
     padding:5px 10px;
     border-radius:30px;
     background-color:white;
     box-shadow:5px 4px grey;
    }    

input[type=text], select {
  width: 100%;
  padding: 12px 20px;
  margin: 4px 0;
  display: inline-block;
  border: 1px solid ;
  border-radius: 4px;
  box-sizing: border-box;
}   

 input[type=password], select {
  width: 100%;
  padding: 12px 20px;
  margin: 8px 0;
  display: inline-block;
  border: 1px solid ;
  border-radius: 4px;

}

input[type=email ], select{
  width: 100%;
  padding: 12px 20px;
  margin: 8px 0;
  display: inline-block;
  border: 1px solid ;
  border-radius: 4px;
  box-sizing: border-box;
}

input[type=number], select {
  width: 100%;
  padding: 12px 20px;
  margin: 8px 0;
  display: inline-block;
  border: 1px solid ;
  border-radius: 4px;
  box-sizing: border-box;
}

input[type=date], select {
  width: 100%;
  padding: 12px 20px;
  margin: 8px 0;
  display: inline-block;
  border: 1px solid ;
  border-radius: 4px;
  box-sizing: border-box;
}
 </style>
  <body style="background-color:orange">

    <div> 
       <u>  <h2 align="center"> Admission Form </h2>  </u>
 </div>
   <form align="center">
          <fieldset>
        <div> <b>
             First name :
             <input type="text" placeholder="Enter your name"> <br> <br>
        </div>
       <div>
          Last name :
           <input type="text" placeholder="Enter father name"> <br> <br>
       </div>
      <div>
           Father name :
          <input type="text" placeholder="Enter last name"> <br> <br>
      </div>
     <div>
         DOB :
        <input type="date" > <br> <br>
      <div>
          Mobile No :
        <input type="number" placeholder="+91"> <br> <br>
      </div>
       <div>
         Email-id :
        <input type="email" placeholder="Enter@gmail.com"> <br> <br>
      </div>
        <tr><th>
           Password :
        </th></td>
       <td>  <input type="password" placeholder="Atleast 8 characters"/> </td>
     </tr>
        <div>
         Confirm  P:
         <input type="password" placeholder="Atleast 8 characters"> <br> <br>
        <div>
           Select your city :
         <select> 
               <option>Gonda</option>
               <option>Basti </option>
              <option> Balrampur</option>
             <option>Faizabad</option>
             <option>Lucknow</option>
                       <option>kanpur</option>
             <option>Gorakhpur</option>
             <option>Prayagraj</option>
       </select> <br> <br> 
      </div><div>
           COLLAGE :
          <input type="text" placeholder="MSITM DEGREE COLLAGE"><br><br>
      </div>
<div>
           COURSE :
         <select> 
               <option>CCC</option>
               <option>DCA</option>
               <option>A LEVEL</option>
               <option>B LEVEL</option>
               <option>O LEVEL</option>
                 <option>TALLY</option>
          </select><br><br>
    </div>
      <div>
         Select your gender :<br>
    Male:<input type="radio" name="r1" value="gender">
   Female:<input type="radio" name="r1" value="gender">
   Other:<input type="radio" name="r1" value="gender">
    </div> <br> 
  
       <div style="color:red">
           Address : <br> <br>
            <textarea rows="5" cols="20" placeholder="Enter your address here."> </textarea> 
      </div><br>
             <strong style="color:blue"> O LEVEL </strong>  <br>    
                Select optional subjects :-- <br>                   
                          <strong style="color:skyblue"> <label for="subject1">IT TOOLS </label></strong>
              <input type="checkbox" id="subject1" name="subject1" value="IT TOOLS"><br>
                          <strong style="color:red"> <label for="subject2">WEB DESIGN</label></strong>
              <input type="checkbox" id="subject2" name="subject2" value="WEB DESIGN"><br>
                          <strong style="color:green"> <label for="subject3">PYTHON</label></strong>
              <input type="checkbox" id="subject3" name="subject3" value="PYTHON"><br>
                          <strong style="color:blue"> <label for="subject4"> IOT</label></strong>      
              <input type="checkbox" id="subject4" name="subject4" value="IOT"><br>                           
        </div>
      <div >
       <button type="reset"  value="Reset"> Reset </button>
    <button type= name="b1" value="submit"> SUBMIT </button>
   </div>
</fieldset> <br>
  <div class="p">
 <u> <p style="color:red"> Developed By mahshadahmad40@gmail.com</u></p> 
  </div>  
<div>
<a href="https://youtube.com/channel/UCiMSPlYbIE1iCfpjhAFh_yg">Mahshad Ahmad</a>
</div>
<div><p> please subscribe my channel </p>
</div>
<hr>
  </form>
 </body>
 </html>
