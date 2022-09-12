***CROH - CHECK RESPONSES OF HTTP/HTTPS***
```
This Python script for 40X responses bypassing.
```

**Installation:**
```
git clone https://github.com/AkhilKoradiya/CROH.git
cd check
chmod u+x check.py
./check.py
or
python3 check.py
```

**Usage:** Start URL with http or https.
```
python3 check.py <cURL options> <target>

Some cURL options you may use as example:
  -L follow redirections (30X responses)
  -x <ip>:<port> to set a proxy
  -m <seconds> to set a timeout
  -H for new headers
  -d for data in the POST requests body
  -...
```
**Example:**
```
python3 check.py https://www.google.es/test
```
**Features:**
```
- Multiple HTTP verbs/methods
- Multiple methods mentioned in #bugbountytips
- Multiple headers: Referer, X-Custom-IP-Authorization...
- Accepts any cURL option
- New module, test for 2454 UserAgents from SecList
```
**Tips:**
```
- You can add proxychains to use with BurpSuite
- Interlace is a good option for multithreading multiples URLs
```
