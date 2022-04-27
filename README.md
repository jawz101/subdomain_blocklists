# subdomain_blocklists
entries with many subdomains.  Usually tied to many business clients.

Longer description:
Some ad companies use a DNS scheme that clutters up host file blocklists.

example:

shoestore.adcompany.com

foodplace.adcompany.com

cardealer.adcompany.com

... and hundreds more

Some browser-based ad blockers can support a fancier wildcard rule to block all subdomains of a top-level domain (example: *.adcompany.com) but a host file can only treat each name as its own line item.  Consequently, this list takes these domains and breaks them out.  The list is compiled from lookups taken from the Cisco Umbrella Top 1 Million list.  Cisco has some public DNS resolvers which billions of devices use

https://umbrella.cisco.com/products/recursive-dns-services

They publish a Top 1 Million list every day here:

http://s3-us-west-1.amazonaws.com/umbrella-static/index.html

This list is just a quick skim of that daily file and pulls out some domains which are known ad/tracking/analytics companies and throws them into a host file.  You could argue "this is a lot of junk for just one company.  Sheesh."  But if you just have a host file, this is how you would have to block the 20,000 companies these companies who use these ad/tracking/analytic products.

It is just an experiment so I won't likely update it often.  If someone wants to do so I would gladly hand it off.


* 2mdn (a part of the Google Doubleclick product)
* [Adjust](https://www.adjust.com/)
* [Appier](https://www.appier.com/)
* [Casalemedia](http://www.casalemedia.com/)
* [Demdex](https://experienceleague.adobe.com/docs/audience-manager/user-guide/reference/demdex-calls.html?lang=en) (Adobe's [Audience Manager](https://developer.adobe.com/audience-manager/))
* [Doubleclick](https://marketingplatform.google.com/about/enterprise/) (Google)
* [IGoDigital](https://developer.salesforce.com/docs/marketing/marketing-cloud/guide/pb-collect-tracking.html) (bought by ExactTarget which was then bought by Salesforce)
* [Marketo](https://www.marketo.com/)
* [Moatpixel](https://www.moat.com/) (by Oracle)
* [Mobileapptracking](https://www.tune.com) (bought by HasOffers and then bought by Tune)
* [Omtrdc](http://www.omniture.com/) (Omniture.  Bought by Adobe)
* [Optimizely](https://www.optimizely.com/)
* [Qualtrics](https://www.qualtrics.com/) (bought by SAP)
* [Rubiconproject](https://rubiconproject.com/)
* [Smartadserver](https://smartadserver.com/)
* [Swrve](https://www.swrve.com/)
* [Taboola](https://www.taboola.com/)
* [Tremorhub](https://www.taptica.com/) (Bought by Taptica)
* [Usebutton](https://www.usebutton.com/)
