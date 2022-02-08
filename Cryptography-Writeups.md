# CyberYami-CTF Writeups: <br />

### Cryptography: <br />

So first of all we got a "7z" file witha text file in it named chipher.txt <br />
after opeing the text file we got a text like this :-  W3_Uu}H4BS_·Llr_t·{luy0·RYt00· <br />

I tried to decode this with some automating tool but it didn't workout. <br />
so, after analysing it we can find a pattern of "WHL" it's the starting of our flag right! <br />

if We start from "W" after 5 charecter we got "H" again we get "L" 
Tn the end we again start from the next charecter like here is "3". <br />
So let's follow this and our <br />

FLAG = WHL{R34llY_BrutUS_y0u_t00}
