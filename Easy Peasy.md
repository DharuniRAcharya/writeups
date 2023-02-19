# Easy-Peasy

## Category
Cryptography

## Points
40

## Description
A one-time pad is unbreakable, but can you manage to recover the flag? (Wrap with picoCTF{}) 
nc mercury.picoctf.net 36449  [otp.py](https://mercury.picoctf.net/static/3cdfde8de474ba94b23aba4a2dfc7eeb/otp.py)

## Approach 
I used the command below to produce the key for the flag.
```
python3 -c "print('a'*49968);print(''a'*32)" | nc mercury.picoctf.net 36449  
```

The following output was obtained.

![Alt text](/easy_peasy2.png)

Next simple python commands were executed as shown below.

![Alt text](/easy_peasy.png)

The result was then converted into text using online hex to text converter.

![Alt text](/easy_peasy1.png)

The required flag was thus obtained and the level was finished.

![Alt text](/easy_peasy3.png)
