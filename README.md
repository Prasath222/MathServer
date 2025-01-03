# Ex.05 Design a Website for Server Side Processing
## Date:27/11/24

## AIM:
 To design a website to calculate the power of a lamp filament in an incandescent bulb in the server side. 


## FORMULA:
P = I<sup>2</sup>R
<br> P --> Power (in watts)
<br> I --> Intensity
<br> R --> Resistance

## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Create python programs for views and urls to perform server side processing.

### Step 5:
Create a HTML file to implement form based input and output.

### Step 6:
Publish the website in the given URL.

## PROGRAM :
```
<html>
    <head>
     </head>
    <body align="center" >
        <div>
            <br>
            <font size="5px">Calculate Power</font>
            <br>
            <br>
            <input type="text" placeholder="Enter Intensity" id="v1">
            <br>
            <br>
            <input type="text" placeholder="Enter Resistance" id="v2">
            <br>
            <br>
            <button onclick="cal()">Calculate</button>
            <br>
            <br>
            <output id="out"></output>

        </div>
        <script>
            function cal()
            {
                var int=Number(document.getElementById("v1").value);
                var res=Number(document.getElementById("v2").value);

                var pow=int*int*res
                document.getElementById("out").innerText="Power = "+ pow +" W";

            }
        </script>
    </body>
</html>
```


## SERVER SIDE PROCESSING:

![alt text](<Screenshot 2024-11-27 113915.png>)

## HOMEPAGE:

![alt text](<Screenshot 2024-11-27 113800.png>)


![image](https://github.com/user-attachments/assets/70345225-e4fe-4991-b554-ee9fa2ad3127)



## RESULT:
The program for performing server side processing is completed successfully.
