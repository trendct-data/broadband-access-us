# Broadband internet availability nationwide

Based on FCC Form 477 data - https://www.fcc.gov/general/broadband-deployment-data-fcc-form-477

# The gist

Census blocks are really small. There are more than 11 million of them.

Internet providers tell the FCC the max speeds they advertise to consumers at the census block level.

I looked at the percentage of blocks in each state where the max advertised speed was sub-broadband (25Mbps/3Mbps) and compared the states.

# Satellite of love

When you look at the same data without fixed satellite data, the percentage of slow-speed blocks in each state drops, in some cases dramatically. This makes sense. A lot of areas would be left off completely if it weren't for satellite. Satellite doesn't require lines to the building so in some places that can be the only Internet connection available. But the FCC says no satellite provider offers broadband speeds. So areas where only broadband is provdided are going to skew things.

I believe it's more accurate to leave them in, so I did. I only looked at Census blocks where some kind of Internet is advertised, since Census blocks are not necessarily populated. But if people can hand over money and get Internet access, it should be graded, no matter what the technology.

# Data file too big

Six gigs of data when unzipped: http://transition.fcc.gov/form477/BroadbandData/Fixed/Jun15/Version%203/US-Fixed-with-Satellite-Jun2015.zip