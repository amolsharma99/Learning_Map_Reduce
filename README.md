# Understanding Map Reduce

To get an idea of how it works without going at code level - http://stevekrenzel.com/finding-friends-with-mapreduce

In mapreduce, it comes down to define two functions - 1. mapper, 2. reducer

Mapper Fn -
Input - value
Output - key, value

Reducer Fn -
Input - key, list of values
Output - key, value (after transformation)

