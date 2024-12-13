# Course_Project

Instead of navigating to the desired event data via querying, I have included a giant DataFrame (CSV) of all the events in question-- One Season of the English Premier League.

The CSV file can be downloaded from the file.io link below. I re-upload them to file.io after each download.

Active Since--Dec 13, 2 pm  
https://file.io/QKKzKFal1S4E



distance1 = [100,80]
distance2 = [40,20]


distance1_subset = shots[shots['x']<distance1[0]]
d1_sub = distance1_subset[distance1_subset['x']>distance1[1]]



distance2_subset = shots[shots['x']<distance2[0]]
d2_sub= distance2_subset[distance2_subset['x']>distance2[1]]

d1 =d1_sub['y']
d2 =d2_sub[d2_sub['x']>65]['x']
