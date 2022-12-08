# regex in linux

# get strings in line with not's content number of range 0-9
grep -E '^[^0-9]+$'

# get strings which content lenght 12 or 14
grep -E '(^.{12,14}$)'

# get strings with content only string lowercase  
grep -E '[a-z]+$'

# ignore accents
grep -E '^[^\.,-_@&*]+$'
