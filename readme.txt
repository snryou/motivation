reputation_date_info.csv: The file contains the initial information of 120 experts from multiple datasets. 
Id: potential expert ID.
Version：Dataset version.
CreationDate: potential expert registration date, representing the date of the first reputation point.
LastAccessDate: potential expert's last access date, representing the date of reputation.
Reputation: the accumulated reputation of a potential expert.
UpVotes: accumulated upvotes of a potential expert.
WebsiteUrl: the link to the personal page of a potential expert.

status_date_info.csv: The file contains the information of statuses and their acquisition dates.
Id:  potential expert ID.
status: a certain status.
reputation: the corresponding reputation of a status.
cdate: potential expert registration date.
rdate: the estimated date on which a status and its reputation were obtained.

variable_info.csv: The file contains all the information on the measurement variables of 120 experts at each status. 
Id： expert user ID.
post: average daily posts created at certain status.
badge: average daily nbadges obtained at certain status.
reputation: average daily reputation points obtained at certain status.
learning: average daily upvotes at certain status.
reciprocity: average daily answers received at certain status.
status: inverse number of days to obtain the sth status
day: days since registration.
url: whether the expert has a personal page or not?
status_level: a certain status.

variable_info(centralized).csv: The file centralizes the information of variable_info.csv. Additionally, it computes the interaction items.  
