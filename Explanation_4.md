Explanations on problem 4 - Active Directory

I applied recursive concept to search for user in an active directory. The recursive
function is within a for loop. Thus the worst run time can go on and on until the
last layer of the folders being searched. If there's three layers of folders and
each layer contains n folders. The O(n) is O(n^3)

Space complexity of active directory will be: O(paths), since the output will only
be generated once the paths are found
