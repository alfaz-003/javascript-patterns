<html>
  <button onclick="pattern_1()">A</button>
  <button onclick="pattern_2()">B</button>
  <button onclick="pattern_3()">C</button>
  <button onclick="pattern_4()">D</button>
  <button onclick="pattern_5()">E</button>
  <button onclick="pattern_6()">F</button>
  <button onclick="pattern_7()">G</button>
  <button onclick="pattern_8()">H</button>
  <button onclick="pattern_9()">I</button>
  <button onclick="diamond()">Dia</button>




<head>
<script type="text/javascript">

function pattern_6(){
  for(var i=0;i<=5;i++)
  {
    for(var j=4;j>=i;j--)
    {
      console.log(" ");
      document.write("'&nbsp;'")
    }
    for(var k=0;k<=i;k++)
    {
      console.log("*");
      document.write("*")
    }
    document.write('</br>')
  }

  for(var i=0;i<=5;i++)
  {
    for(var j=4;j>=i;j--)
    {
      console.log(" ");
      document.write("'&nbsp;'")
    }
    for(var k=0;k<=i;k++)
    {
      console.log("*");
      document.write("*")
    }
    document.write('</br>')
  }
}



function pattern_5(){
  for(var i=0;i<=5;i++)
  {
    for(var j=4;j>=i;j--)
    {
      console.log(" ");
      document.write("'&nbsp;'")
    }
    for(var k=0;k<=i;k++)
    {
      console.log("*");
      document.write("*")
    }
    document.write('</br>')
  }
}




function pattern_4(){

  for(var i=0;i<=4;i++)
  {
    for(var j=4;j>=i;j--)
    {
      document.write("&nbsp;");
    }
    for(var k=0;k<=i;k++)
    {
      document.write('*');
    }
    document.write('<br/>')
  }
 


}
 
 function pattern_3(){

  for(var a=1;a<=5;a++){
    for(var b=1;b<=a;b++) {
      document.write('*')
    }
    document.write('<br />')
  }

  for(var x=0;x<=5;x++) {

for(var y=0;y<=5-x;y++) {
    document.write('*')
    }
  document.write('<br />')
 }


 

}






 
 function pattern_1(){
  var i,j;
 for(i=1; i <= 5; i++)
 {
  for(j=1; j<=i; j++)
 {
   
   document.write('*');
   console.log("*")
  }
   document.write('<br />');
   console.log(" ");
  }

 }







 function pattern_2() {
   
  for(var x=0;x<=5;x++) {

    for(var y=0;y<=5-x;y++) {
      document.write('*')
      console.log("*")
    }
    document.write('<br />')
    console.log(" ")
  }
 }


 function pattern_7(){
   for(var i=1;i<=5;i++)
   {
     for(var j=1;j<=5;j++)
     {
       if(i>=2 && j>=2 && i<=4 && j<=4)
       {
         document.write("&nbsp;&nbsp;")
       }
       else {
         document.write("*")
       }
     }
     document.write('<br />')
   }
  
 }



function pattern_8(){

  for(var i=1;i<=5;i++){
    document.write("*")
    document.write('<br />')
  }
  for(var i=1;i<=5;i++)
  {
    for(var j=5;j>=i;j--)
    {
      document.write('&nbsp');
    }
    for(var r=1;r<(i*2);r++)
    {
      if(r>1 && r<(i*2)-1)
      {
        document.write('&nbsp')
      }
      else {
        document.write("*");
      }
    }
   document.write('<br />')
  }

  for(var i=5;i>=1;i--)
  {
    for(var j=5;j>i;j--)
    {
      document.write('&nbsp');
    }
    for(var r=1;r<(i*2);r++)
    {
      if(r>1 && r<(i*2)-1)
      {
        document.write('&nbsp')
      }
      else {
        document.write("*");
      }
    }
   document.write('<br />')
  }

  for(var i=1;i<=5;i++){
   
    document.write("*")
    document.write('<br />')
  }

}




function pattern_9(){

  for(var i=1;i<=5;i++)
  {
    for (var j=1;j<=5-i+1;j++)
    {
      document.write("*")
    }
    for(var k=1;k<=2*i+2;k++)
    {
      document.write("v")
    }
    for(var j=0;j<=5-i+1;j++)
    {
      document.write("*")
    }
    document.write('<br />')
  }

  for(var i=4;i>=1;i--)
  {
    for(var j=i;j<=5;j++)
    {
      document.write("*")
    }
    for(var k=1;k<=(2*i)-2;k++)
    {
      document.write("V")
    }
    for(var j=i;j<=5;j++)
    {
      document.write("*")
    }
    document.write('<br />')
  }


}

function diamond(){

  for(var i=1;i<=2*5-1;i++){
    document.write("*")
  }
  document.write('<br />')
for(var r=1;r<=5;r++)
{
  for(var cs=5-r;cs>=1;cs--)
  {
    document.write("*")
  }
  for(var cs=1;cs<=2*r-1;cs++)
  {
    document.write('&nbsp;&nbsp')
  }
  for(var cs=5-r;cs>=1;cs--)
  {
    document.write("*")
  }
  document.write('<br />')
}


for(var r=5-1;r>=1;r--)
{
  for(var cs=1;cs<=5-r;cs++)
  {
    document.write("*")
  }
  for(var cs=1;cs<=2*r-1;cs++){
    document.write('&nbsp;&nbsp')
  }
  for(var cs=1;cs<=5-r;cs++)
  {
    document.write("*")
  }
  document.write('<br />')
}
for(var i=1;i<=2*5-1;i++){
    document.write("*")
  }
  document.write('<br />')

}

    




 

  
  





    
</script>
</head>
<body>
</body>
</html>
