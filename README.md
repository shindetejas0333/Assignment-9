# Assignment-9
# To find BOD at 7th day 25C
# To find Decay Coefficient at 25C
K= float(input("Decay Coefficient:"))
T= float(input("Temperature of 3rd day BOD:"))
TI=float(input("Temperature of 7th day BOD:"))
K2 = (K*(1.047**(TI-T)))
print ("The value ofK2 is:", K2)
# To find Ultimate BOD
e=2.718
print ("The value ofe is:", e)
Bl = float(input("BOD at 3rd day 20c:"))
t = float(input("time in days for finding B1:"))
E = (1 - 2.71828 ** (-0.23 * t))
print ("The value of E is:", E)
BI = 10 * E
print ("The value of 10 is:", 10)
# To find BOD at 7th day 25C
B2 = float(input("BoD at 7rd day 25c:"))
t1 =float(input("time in days for findinfB2:"))
El =(1-e**(-0.289*t1))
print ("The value ofEl is:", El)
B2 = (10*El)
print ("The value of B2 is:", B2)
