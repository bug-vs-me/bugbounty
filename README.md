# This h1finder.sh is script which collect all program names and then collect all assets and save it into wild and non-wild domains 

You can get your API key from https://hackerone.com/settings/api_token/edit  

note i had set this script to select(.attributes.offers_bounties == true)  in line 16 if you want all domains just edit it to false

https://github.com/bug-vs-me/bugbounty/blob/main/h1finder.sh#L16

# Installation

**Please replace your api-token and username**
```
git clone https://github.com/bug-vs-me/bugbounty.git
cd bugbounty
chmod +x h1finder
mv h1finder /usr/bin/
```

# Usage
```
h1finder -t <token> -u <username>
```

**wild.txt files output will look like this:**
```
hackerone-ext-content.com
hackerone-user-content.com
cloudflare.com
cloudflarepartners.com
teams.cloudflare.com
```

**nonwild.txt files output will look like this:**
```
a5s.hackerone-ext-content.com
api.hackerone.com
app.pullrequest.com
b5s.hackerone-ext-content.com
cover-photos-us-east-2.hackerone-user-content.com
```
