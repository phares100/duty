# duty
Dutycalc Website

<!DOCTYPE html>
 <html>
     <head>
	   <meta charset="UTF-8">
	   <meta name="viewport" content="width=device-width,""initial-scale=1">
       <title>Welcome to our website</title>
	   <link rel="stylesheet" type="text/css" href="style.css">
     </head>
	<body>
	
	<header class="banner">   
       <h1>DUTY CALCULATOR</h1>
	       <p>Simplicity at best</p>
   </header>
   
   
   <div class="topnav">
       <a class="active" href="#home">Home</a>
       <a href="#about">About</a>
       <a href="#blog">Blog</a>
       <a href="#contact">Contact</a>
    </div>
   
		   
	    <style>
         .design{
          width:300px; height:20px;
		  
		  
		  padding: 12px;
           margin: 2px 0;
       box-sizing: border-box;
           border: 3px solid #ccc;
          outline: none;
}

input[type=text]:focus {
    border: 3px solid #555;

                }
        </style>

           

             <form>
			 
			<p><br>
			 
               
                <b>Direct Import:</b> <input type="radio" name="rbtest" value="one" checked="checked" id="used"
				
                title="radio button1 sample">
                <b>Previously registered in Kenya:</b> <input type="radio" name="rbtest" value="two" 
				
                title="radio button2 sample">
				
				<b>Generators:</b> <input type="radio" name="rbtest" value="three" 
                title="radio button3 sample"><br><br>
 
				
				
            </p> <br>
			
			<h3>Year of Manufacture</h3>
	                                
    <div>
	
	
	
	
	<select id="month_of_purchase" name="entry[month_of_purchase]">
            <option value="">Month</option>
            <option value="1">Jan</option>
            <option value="2">Feb</option>
            <option value="3">Mar</option>
            <option value="4">Apr</option>
            <option value="5">May</option>
            <option value="6">Jun</option>
            <option value="7">Jul</option>
            <option value="8">Aug</option>
            <option value="9">Sep</option>
            <option value="10">Oct</option>
            <option value="11">Nov</option>
            <option value="12">Dec</option>
        </select>
        <select id="day_of_purchase" name="entry[day_of_purchase]">
            <option value="">Day</option>
            <option value="1">1</option>
            <option value="2">2</option>
            <option value="3">3</option>
            <option value="4">4</option>
            <option value="5">5</option>
            <option value="6">6</option>
            <option value="7">7</option>
            <option value="8">8</option>
            <option value="9">9</option>
            <option value="10">10</option>
            <option value="11">11</option>
            <option value="12">12</option>
            <option value="13">13</option>
            <option value="14">14</option>
            <option value="15">15</option>
            <option value="16">16</option>
            <option value="17">17</option>
            <option value="18">18</option>
            <option value="19">19</option>
            <option value="20">20</option>
            <option value="21">21</option>
            <option value="22">22</option>
            <option value="23">23</option>
            <option value="24">24</option>
            <option value="25">25</option>
            <option value="26">26</option>
            <option value="27">27</option>
            <option value="28">28</option>
            <option value="29">29</option>
            <option value="30">30</option>
            <option value="31">31</option>
        </select>
        <select id="year_of_purchase" name="entry[year_of_purchase]">
            <option value="">Year</option>
            <option value="2011">2011</option>
            <option value="2012">2012</option>
            <option value="2013">2013</option>
            <option value="2014">2014</option>
            <option value="2015">2015</option>
            <option value="2016">2016</option>
			<option value="2016">2017</option>
			<option value="2016">2018</option>
        </select>
<div id="datepicker"></div><br>
	
        
                     <h3>Expected time of arrival</h3>
	                                
    <div>
               <input type="date" id="start" name="trip"
               value="01-01-2011"
               min="01-01-2011" max="31-12-2018" />
    </div><br><br>



	   	 
	


			 
			 
         <b>Make</b><br>
    <select class="design">
	   <option value=""></option>
	   <option value="Toyota"> Toyota</option>
	   <option value="Nissan"> Nissan</option>


    </select><br><br>
	
	    <b>Model</b><br>
	<select class="design">
	   <option value=""></option>
	   <option value="corolla"> Corolla</option>
	   <option value="Sunny"> Sunny</option>

    </select><br><br>
	
	
	
	<b>Body Type</b><br>
	<select class="design">
	   <option value=""></option>
	   <option value=""></option>
	   <option value=""></option>

    </select><br><br>
	
	
	
	<b>Engine Capacity</b><br>
	<select class="design">
	   <option value=""></option>
	 
	 
    </select><br><br>
	
	<button class="btn success">SUBMIT</button>
	
	
	
             </form><br><br>
			 
			 
    	
		<br><br>
		
		
		
		<p><b><u>RESULTS</u></b></p>
		
     <table id="t01">
  <tr>
    <th>ITEM</th>
    <th>AMOUNT</th> 
    
  </tr>
  <tr>
    <td>CRSP</td>
    <td id="demo"></td> 
    
  </tr>
  <tr>
    <td>CUSTOMS VALUE</td>
    <td id="demo1"></td> 
    
  </tr>
  <tr>
    <td>DEPRECIATION</td>
    <td id="demo2"></td> 
    
  </tr>
  <tr>
    <td>IMPORT DUTY</td>
    <td id="demo3"></td> 
    
  </tr>
  <tr>
    <td>EXCISE DUTY</td>
    <td id="demo4"></td> 
    
  </tr>
  <tr>
    <td>VAT</td>
    <td id="demo5"></td> 
    
  </tr>
  <tr>
    <td>IDF</td>
    <td id="demo6"></td> 
    
  </tr>
  <tr>
    <td>RDL</td>
    <td id="demo7" ></td> 
    
  </tr>
  <tr>
    <td>MOTOR VEHICLE REGISTRATION</td>
    <td id="demo8"></td> 
    
  </tr>
  <tr>
    <td><H4>TOTAL TAXES</H4></td>
    <td id="demo9"></td> 
    
  </tr>
</table><br><br>








     <table id="t01">
  <tr>
    <th>ITEM</th>
    <th>AMOUNT</th> 
    
  </tr>
  <tr>
    <td>TOTAL PORT CHARGES</td>
    <td id="demo"></td> 
    
  </tr>
  <tr>
    <td>MARINE SURCHARGE</td>
    <td id="demo1"></td> 
    
  </tr>
  <tr>
    <td>CLEARING AGENT COST</td>
    <td id="demo2"></td> 
    
  </tr>
  <tr>
    <td>SHIPPING DELIVERY ORDER</td>
    <td id="demo3"></td> 
    
  </tr>
  <tr>
    <td>TOTAL DUTY & CLEARING COST</td>
    <td id="demo4"></td> 
    
  </tr>
  <tr>
    <td><H4>TOTAL IMPORTATION COST</H4></td>
    <td></td> 
    
  </tr>

</table><br>

<script src= "scripts/script.js" ></script>

   





 
 
 
 
    </body> 
 
 
 </html>
