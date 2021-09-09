# tax-season-prophet
Scraping IRS site Data to model tax return submissions. Just a proof of concept on implementing the Prophet API and some dataset creation.

### individual_returns_by_week.Rmd
built the dataset, saved in that text file (*IRS_indv_returns_by_week.csv*)

### modeling_return_traffic.Rmd
wrote a simple model to predect the next 52 weeks out from the current data. At some point I'll merge the advanced stuff I did with the Tax Deadlines, etc.
You can look at the graphs if you render *modeling_return_traffic.nb.html* in a web browser or something.
