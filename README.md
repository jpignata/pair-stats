# pair-stats

At a glance statistics from your git repository showing with whom you've paired over the last month.

The days column shows the number of unique days you've had a check-in with the other author, commits shows the number of individual repository commits made and % uses days to illustrate how often you've paired with the other author.

Commits made without a pair are grouped under "Solo."

This assumes your commit authors are developers names joined with "and", an ampersand and/or a comma.

## Usage:

    jp@populuxe:~/Projects/lorem(master)$ ./pair-stats Habitasse Platea
    Pairing stats for Habitasse Platea since 2009-12-06
    
    Developer            Days     Commits  %
    ---------------      ----     -------  ---
    Tincidunt Nec        8        55       33%
    Congue vel Mauris    5        40       20%
    Sed Facilisis        4        21       16%
    Etiam Blandit        3        16       12%
    Solo                 3        9        12%
    Magna Dui            1        17       4%
    Dolor Elit           0        0        0%