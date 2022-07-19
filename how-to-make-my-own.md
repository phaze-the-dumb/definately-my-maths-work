# How To Use Your Own Domain

Note: If you want a domain thats not `.tk`, `.cf`, `.ml`, `.gq` or `.ga`, I use https://porkbun.com/ and they sell `.xyz` very cheap!

### Freenom
- Firstly you need a domain, you can get one of these for free from `freenom.com` just be aware that you need an account for any of it to work.
- Search for a domain you want: ![image](https://user-images.githubusercontent.com/57566773/179756929-aee9392d-9e28-4ac3-9571-1f8bbe3ff702.png)
- Select the domain you want from the list, click `get it now` > `checkout` > change `3 months @ free` to `12 months @ free` > continue
- Agree and complete the order

### Cloudflare
- Go to https://www.cloudflare.com/ and setup an account, when the panel loads click add a site and type in the domain you just registered on freenom
- Copy the nameservers from cloudflare and paste them into freenom
- ![image](https://user-images.githubusercontent.com/57566773/179757500-a485a656-8476-411d-9a33-03551f34912a.png)
- ![image](https://user-images.githubusercontent.com/57566773/179757549-ce557a54-0a0f-4add-ad2e-1726d2e04638.png)
- Click change nameservers to confirm
- THESE CAN TAKE UP TO 24 HOURS TO GO THROUGH

### Reflect4
- A good proxy service is reflect4 most of the proxies I host use their software.
- Go to https://reflect4.me/register and create an account
- Then just put your domain in as well as a username and password, and a cloudflare api token
- YOU NEED TO CREATE DNS RECORDS YOURSELF, Due to cloudflares api not working on free domains
- Create 2 `CNAME` records:
  - `@` > `fa.cplbx.info`
  - `www` > `fa.cplbx.info`
  WITH PROXYING ON!!!
