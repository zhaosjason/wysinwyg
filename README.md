# WYSINWYG: What you see is ***not*** what you get                                                                                                                                    

Everyone wants code to be styled according to their own preferences, yet we also enforce 
global style constraints within codebases.

Since all formatting styles of code are sematically equivalent, why can we format code 
according to each person's preferences at "runtime" (ie. when someone is looking at  
the code).

### Goals
 - Our IDEs should automatically format codebases according to our individual style preferences
 - Version control should render diffs / track changes within an individual style regime

### Issues
 - Your style has to be completely codified and generable by a formatter
    - If not then your working version might change from under you.  Maybe that's fine?
 - Formatter directives are handled differently by each formatter; conflicts?
