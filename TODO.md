TODO
====

Trivial
-------

I would have done these right away, but I'm under enormous time pressure. (Sorry, FOSS! Gotta eat)

 - fix the fix for the directory creation problem such that it distinguishes between showstoppers, like a perms problem, and the directory
   already existing. (Easy enough, just add a test for existence of target t when getting an error after a 'mkdir t')
 - fix the fix (ibid.) such that it does not spam you with warnings when it's being all idempotent and stuff


