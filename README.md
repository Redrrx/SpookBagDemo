# SpookBagDemo

Spookbag is a browser automation framework that is specialized for stealth and bot counter-countermeasures,
its POC has been proven and the work continues on it as long as it remains viable.

The project was created for educational purposes only and is currently not ready to be shared, this repository was created to share some insight to collaborators on other projects that will be using Spookbag, sadly i will not be addressing  requests as the repository name states this is a demonstration.



## Both sides

### Pros 
* Can bypass most protections and countermeasures even after few retries.
* Can be Sync or async depends on the requirements of the project.
* Headless is completely undetected.
* Integrated Plugin system.
* Integrated Proxy, either HTTP or SOCKS.

### Cons
* Current implementation is very slow compared to the counterparties.
* Due the Tug of war happening with the protection services, the core of Spookbag could require a radical change every time they add a change which makes it high maintenance.
* too experimental.


## Current stealth and CCM capabilities

| Provider | Success rate | Test location|
|-----:|-----------|-------|
|Cloudflare|100%|Multiple websites|
|Datadome| 100% (inconclusive tests)| https://antoinevastel.com/bots/datadome|
|botprotect.io| TBD %|  TBD|
|Imperva| TBD %| TBD|
|Arkose Labs| TBD %| TBD|
|Webdriver detection| 100%| Multiple websites|
|Headless detection| 100% | Multiple websites|




## Demonstrations
I will be posting better and clearer demonstrations as those hide too much and were done in a short time.



* Cloudflare captcha on nopecha test website. (This takes a little time due me pressing the debugger steps)

![CF](https://github.com/Redrrx/SpookBagDemo/blob/main/spookbagdemo.gif?raw=true)


* Datadome test on https://antoinevastel.com/bots/datadome

![Datadome](https://github.com/Redrrx/SpookBagDemo/blob/main/spookbagdemo_datadome.gif?raw=true])
