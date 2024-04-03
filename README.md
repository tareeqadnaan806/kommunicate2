 
Here are my solutions 

## 1. Here is the hoisted link and code where i have designed the UI using only HTML and CSS  
link:
code:

## 2. here is the code for 2nd problem  
   function getUrlParameterValue(url, parameter) {  
  var query = url.split("?")[1];  
  var params = query.split("&");  
  for (var i = 0; i < params.length; i++) {  
    var search = params[i].split("=");  
    if (search[0] === parameter) {  
      return search[1];  
    }  
  }  
  return null;  
}  

var url =  
  "https://www.kommunicate.io/poweredby?utm_source=https://www.kommunicate.io/&utm_medium=webplugin&utm_campaign=poweredby";  
  
console.log(getUrlParameterValue(url, "utm_medium"));  
console.log(getUrlParameterValue(url, "utm_campaign"));  


## 3. Here is the code for 3rd problem  
   function reverseNumber(number) {  
  var reversed = 0;  
  while (number !== 0) {  
    var digit = number % 10;  
    reversed = reversed * 10 + digit;  
    number = (number - digit) / 10;  
  }  
  
  return reversed;  
}  

var number = 149;  
console.log(reverseNumber(number));  


## 4.My best project  
one of my best project is i have developed the UI of restaurant. I have made this particular project to know more about the Reactjs and JavaScript and to implement my skills. At first, i have designed figma of it and i searched for api's respectively. As i deep-dive into this project iimplemented react concepts like react-router-dom, useparam hook and so on. To complete this project i took help from documentation and also from chatGPT and internet. Atlast i hosted my project on vercel app.   
Here is the hosted link for my project: https://react-mct-jet.vercel.app/  
