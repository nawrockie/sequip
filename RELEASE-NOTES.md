# sequip 0.x release notes 

### sequip 0.06 release (July 2020): Minor bug-fix update
  * sqp_utils.pm:utl_ConcatenateListOfFiles() is now more robust. 
    Previous version could, in extreme cases, create 'cat' calls that
    exceeded number of allowed characters in a command. Documented
    as github issue#2. Tests added to the testsuite to cover this.

---

For more information, see the [git log for the develop
branch](https://github.com/nawrockie/vadr/commits/develop).

