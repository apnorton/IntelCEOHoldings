# IntelCEOHoldings
This repo is an exploration of the Intel CEO's holdings over time through SEC Form 4 filings; this is particularly relevant in the aftermath of [Meltdown and Spectre][meltdown].

Data was taken from the SEC's [EDGAR filing tool] and the date of Google's report to Intel was taken from the [Project Zero blog entry][ProjectZero].

Below is the plot of Brian Krzanich's holdings over time, starting at the beginning of 2012.  The plot was created by considering all Form-4 filings made by Krzanich, then summing the non-derivative purchases and sales over time.  See the Jupyter notebook for more information.

![Plot of holdings, relative to start of 2012](https://raw.githubusercontent.com/apnorton/IntelCEOHoldings/master/RelativeHoldings.png)

A blog entry regarding how I did this and any further work I perform is forthcoming.

[EDGAR]: https://www.sec.gov/cgi-bin/browse-edgar?action=getcompany&CIK=0001538580&type=&dateb=&owner=only&count=100
[ProjectZero]: https://googleprojectzero.blogspot.com/2018/01/reading-privileged-memory-with-side.html
[meltdown]: https://meltdownattack.com/
