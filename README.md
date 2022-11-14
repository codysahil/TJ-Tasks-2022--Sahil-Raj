# TJ-Tasks-2022--Sahil-Raj![Screenshot (41)](https://user-images.githubusercontent.com/98708331/201332329-a5c7efdc-f0e7-4de1-b729-f4b5b2dd046c.png)
Q1 - power of 2
Algorithm - Using bit manipulation
Approach - As we know, a number is power of two or a multiple of two if it has only one bit set in its binary representation, so if I do N & (N-1) then the result should be 0 for a number to be a power of 2.


Q2 ![Screenshot (42)](https://user-images.githubusercontent.com/98708331/201334604-e07294e3-f30f-4f4b-94ac-018b8bc55ef9.png)
using loops having two pointers i for outer loop and j for inner loop and comparing the values 



Q3 ![Screenshot (43)](https://user-images.githubusercontent.com/98708331/201336170-8258f5d4-7a83-405c-aeb5-cb89ed3352b6.png)
I just used the modulo operator which returns remainder and if their remainder is same then i just increment the count value by 1

Q4 ![Screenshot (44)](https://user-images.githubusercontent.com/98708331/201646740-ea5e5188-f489-47fa-a489-f217b834343a.png)

HTML SURVEY FORM 
![Screenshot (45)](https://user-images.githubusercontent.com/98708331/201650989-3bd726d0-c4c9-4df8-beef-11ecb6801455.png)
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <form method="post" action="//submit.form" onSubmit="return validateForm();">
        <div style="max-width: 400px;">
        </div>
        <div style="padding-bottom: 18px;font-size : 24px;">Student Survey</div>
        <div style="display: flex; padding-bottom: 18px;max-width : 450px;">
        <div style=" margin-left: 0; margin-right: 1%; width: 49%;">First name<br/>
        <input type="text" id="data_2" name="data_2" style="max-width: 100%;" class="form-control"/>
        </div>
        <div style=" margin-left: 1%; margin-right: 0; width: 49%;">Last name<br/>
        <input type="text" id="data_3" name="data_3" style="max-width: 100%;" class="form-control"/>
        </div>
        </div><div style="padding-bottom: 18px;">Name of your college/university<span style="color: red;"> *</span><br/>
        <input type="text" id="data_4" name="data_4" style="max-width : 450px;" class="form-control"/>
        </div>
        <div style="padding-bottom: 18px;">How long your college run?<br/>
        <input type="text" id="data_5" name="data_5" style="max-width : 450px;" class="form-control"/>
        </div>
        <div style="padding-bottom: 18px;">Do you attend regularly?<br/>
        <span><input type="radio" id="data_6_0" name="data_6" value="Yes"/> Yes</span><br/>
        <span><input type="radio" id="data_6_1" name="data_6" value="No"/> No</span><br/>
        </div>
        <div style="padding-bottom: 18px;">Rate your college out of 5<br/>
        <select id="data_7" name="data_7" style="max-width : 250px;" class="form-control"><option>Please rate</option>
        <option>1</option>
        <option>2</option>
        <option>3</option>
        <option>4</option>
        <option>5</option>
        </select>
        </div>
        <div style="padding-bottom: 18px;">How many friends do you have in college<br/>
        <select id="data_8" name="data_8" style="max-width : 250px;" class="form-control"><option>Please rate</option>
        <option>1</option>
        <option>2</option>
        <option>3</option>
        <option>4</option>
        <option>5/5+</option>
        </select>
        </div>
        <div style="padding-bottom: 18px;">Your course<br/>
        <select id="data_9" name="data_9" style="max-width : 250px;" class="form-control"><option>Please rate</option>
        <option>BTECH</option>
        <option>BCA</option>
        <option>BBA</option>
        <option>LAW</option>
        <option>MBA</option>
        </select>
        </div>
        <div style="padding-bottom: 18px;">Song selection<br/>
        <select id="data_11" name="data_11" style="max-width : 250px;" class="form-control"><option>Please rate</option>
        <option>1</option>
        <option>2</option>
        <option>3</option>
        <option>4</option>
        <option>5</option>
        </select>
        </div>
        <div style="padding-bottom: 18px;">Rate your faculties<br/>
        <select id="data_10" name="data_10" style="max-width : 250px;" class="form-control"><option>Please rate</option>
        <option>1</option>
        <option>2</option>
        <option>3</option>
        <option>4</option>
        <option>5</option>
        </select>
        </div>
        <div style="padding-bottom: 18px;">How many backlogs have u got till now?<br/>
        <select id="data_13" name="data_13" style="max-width : 250px;" class="form-control"><option>Please rate</option>
        <option>1</option>
        <option>2</option>
        <option>3</option>
        <option>4</option>
        <option>5/5+</option>
        </select>
        </div>
        <div style="padding-bottom: 18px;">Favourite Food<br/>
        <select id="data_14" name="data_14" style="max-width : 250px;" class="form-control"><option>Please rate</option>
        <option>Chhole bhature</option>
        <option>GHar ka Kuch bhi</option>
        <option>Pizza/Burger</option>
        <option>Dahi chura</option>
        
        </select>
        </div>
       
        <div style="padding-bottom: 18px;">Do u like your college or not .Explain<br/>
        <textarea id="data_16" false name="data_16" style="max-width : 450px;" rows="6" class="form-control"></textarea>
        </div>
        <div style="padding-bottom: 18px;"><input name="skip_Submit" value="Submit" type="submit"/></div>
        <div>
        <div style="float:right"><a href="https://www.100forms.com" id="lnk100" title="form to email">form to email</a></div>

        </div>
        </form>
        
       
</body>
</html>
