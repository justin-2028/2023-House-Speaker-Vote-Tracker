# 2023 House Speaker Vote Tracker

![](https://www.googleapis.com/download/storage/v1/b/kaggle-user-content/o/inbox%2F12064410%2F0d2cf839e352f54fab12217e5f6ea9d6%2Fhouse%20speaker%20flag%20logo.png?generation=1672819425185054&alt=media)

# DAY 2 (January 3rd, 2023 - January 4th, 2023)
This is a dataset that describes each representative's information and vote details for all ballots during the 2023 House Speaker Vote.

All data are official figures from the U.S. House of Representatives's government website that have been compiled and structured by myself. To be clear, the House of Representatives usually has **435 MEMBERS**, but **ONLY 434 ARE PARTICIPATING IN THE VOTE** due to the sudden vacancy of Virginia's 4th District seat (that resulted from the death of Rep. Donald McEachin). There are also 5 delegates representing the District of Columbia, the Virgin Islands, Guam, American Samoa, and the Commonwealth of the Northern Mariana Islands and 1 resident commissioner representing Puerto Rico, but they are outside of the 435 House members and do not have voting powers.

# Data Sources
##### The primary data source used was the Human Rights Activists News Agency (HRANA), an organization that has covered the 2022 Iran protests extensively since its inception. HRANA has attempted to compile countless individual, group, media, and government reports to make rough statistical estimates, something no other public organization has done so far.

1. [U.S. House of Representatives's Office of the Clerk](https://clerk.house.gov/) - The Office of the Clerk published daily roll call reports that clearly explained the details of the vote and the selected/proposed nominee of each representative.
2. [U.S. House of Representatives's Directory of Representatives](https://www.house.gov/representatives) - The Directory of Representatives provided a structure to build the dataset around as it provided vital information about each representative such as their political affiliation. 
3. [White House's "The Legislative Branch" Article](https://www.whitehouse.gov/about-the-white-house/our-government/the-legislative-branch/) - Information about the 6 non-voting delegates of the U.S. House of Representatives cleared up prior confusion about the listing of 440 names on the Directory of Representatives rather than 434 (excluding the vacancy in Virginia's 4th District seat).

# Statistics Being Tracked
- **Name** - Name of representative serving in the US House of Representatives as part of the 118th United States Congress.
- **US State/District** - Name of the representative’s US state and specific congressional district.
- **Party Affiliation** - Political party of the representative.
- **Ballot 1** - Name voted for in Ballot 1 by the representative.
- **Ballot 2** - Name voted for in Ballot 2 by the representative.
- **Ballot 3** - Name voted for in Ballot 3 by the representative.

# Dataset History
2023-01-03 - Dataset is created (0 days after the 2023 House Speaker Vote began).

[GitHub Repository](https://github.com/justin-2028/2023-House-Speaker-Vote-Tracker) - The same data but on GitHub.

# Code Starter
[Daily Data and Plot Example](https://www.kaggle.com/code/justin2028/daily-statistics-of-2022-iran-protests)
