# subwaytopology
A graph dataset derived from the MTA NY subway system. I made it so I'd have a quasi-realistic dataset for experimentation. I only needed intersections, so the intermediate stations are not (yet?) included. There's also intricacies for the close-to-each-other stations that need to be double checked (i.e., the topology could be wrong). So, you're welcome to use this "data", but there's not much to it.

My main use case was to solve the problem: what is the longest possible route along the NY subway without repeating any section (crossing at a station is allowed, but the train should otherwise be on different rails).
