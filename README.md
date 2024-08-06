- 👋 Hi, I’m @Fayzullo20073
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
Fayzullo20073/Fayzullo20073 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

def func(lst):
    print(lst)

func(['ds', 32, 44, 'ss'])

a = ["vvytc","UHYF","123","sad","1234"]
a_int=[]
a_str=[]
for i in a:
    if type(i)==int:
        a_int.append(i)
    elif type(i)==str:
        a_str.append(i)
print("sonlar",a_int)
print("strlar",a_str)           





import random,time
p1=input("Jangchi 1: ")
p2=input("Jangchi 2: ")
p=p1,p2
a,b=100,100
while (a or b)>=0:
for i in p:
  time.sleep(2)
  x=random.randint(0,100)
  print(i,"zarba berdi🥊")
  print("⚡️Zarba kuchi:",x)
  if i==p1:
   b-=x
   print("❤️",p1,":",a)
   print("❤️",p2,":",b)
  else:
   a-=x
   print("❤️",p1,":",a)
   print("❤️",p2,":",b)
w=min(a,b)
if w==a:
print(p2,"yutdi🏆")
else:
print(p1,"yutdi🏆")
