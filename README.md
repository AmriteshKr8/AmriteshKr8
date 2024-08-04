import AmriteshKr8 as s
import random as r
acts = ["code","chill","learn","play","go-out"]
def life():
  mood = s.getmood()
  if (mood != "happy"):
    s.action("fetch-headphones")
    s.action("blast-music")
    act = int(r.random()*5)
    s.action(acts[act])
  else ():
    act = int(r.random()*3)
    if (act == 1):
      s.action("study")
    else ():
      s.action("chill")
while True:
  life()
  if(s.getmood() == "sucidal"):
    break
s.action("die")
