# 😰👉 generateAPT.py 
> For when you need someone to point the finger at.

Fell for a phish? User suffered business email compromise? Someone run "moreram.exe"?  
If everyone is looking at you and there ain't no excuses, its time to point the finger at an **ATP**!

Simply run `generateAPT.py` to be INSTANTLY provided with a genuine looking APT name you can throw in your CISO's face to distract them while you prepare your resume.

# Usage
1. Clone the repo or save `generateAPT.py` locally
2. Run `python generateAPT.py`
3. Copy and paste output into email to CISO.

# Example
```
$ python generateAPT.py
Forensic evidence shows it came from "Misty Basilisk"
```

```
From: Me
To: CISO
Subject: RE: How the hell did this get through our spam filter!?

Dear CISO, 

I've found the culprit!
Forensic evidence shows we suffered a determined 0-day attack from "Misty Basilisk"

Regards,
IT Security Expert

> Send
```

# Further usage
If it's _really_ hit the fan and you need multiple "APT"s to blame you can use the **count** arg.

```
$ python generateAPT.py -count 5
The threat actor responsible is "Relieved River Dolphin"
Krebs said it was "Envious Tarsier"
A reputable source has confirmed this originated from "Angry Killer Whale"
Our next-gen machine learning attributed it to "Stormy Duck"
Evidence suggests it was "Fancy Guinea Pig"
```

Likewise, if you just need names with no excuses, use the **noexcuse** flag.
```
$ python generateAPT.py -count 5 -noexcuse
Frantic Polar Bear
Distinct Chameleon
Light Snapping Turtle
Bewildered Bearded Dragon
Motionless Arctic Wolf
```
