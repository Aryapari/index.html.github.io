<html>
    <head>
        <title>
            Calculator
        </title>
    </head>
    <body>
    </body>
    <script>
     function main(){
        var num1=parseInt(prompt("Enter 1st Number"));
        var num2=parseInt(prompt("Enter 2nd Number"));
        var op=prompt("Enter operater")
        document.write("number1: "+num1+"<br>");
        document.write("number2: "+num2+"<br>");
        switch(op){
            case  "+":
            sum_two_number(num1,num2)
            // document.write("sum: "+sum_two_number(num1,num2)+"<br>");
            break;
            case'-':
            document.write("difference:"+sub_two_number(num1,num2)+"<br>");
            break;
            case '*':
            document.write("product:"+product_two_number(num1,num2)+"<br>");
            break;
            case '/':
            document.write("div: "+div_two_number(num1,num2)+"<br>");
            break;
            default:
            document.write("Invalid operater")
        }
    }    
        main();
        function sum_two_number(num1,num2){
              var sum=num1+num2;
              document.write("sum: "+sum);
                  }
        function sub_two_number(num1,num2){
            var  different=num1-num2;
            return different;
        }    
        function product_two_number(num1,num2){
            var product=num1*num2
            return product;
        }   
        function div_two_number(num1,num2){
            var div=num1/num2;
            return div;
        }  
    </script>
</html>
