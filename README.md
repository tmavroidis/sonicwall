# sonicwall
tips for securing sonicwalls

GeoFilter:

This morning started with a ton of failed signon attempts to my VPN, it had to be a brute force password guessing program.
There was no way to limit the number of attempts on the VPN, so I came across a post about using the geo-ip filter.
I blocked all countries except Canada and the US and the attacks stopped immediately.

![Alt text](https://github.com/tmavroidis/sonicwall/blob/main/j2Nl6vPBSFWnOFQ2.png)
