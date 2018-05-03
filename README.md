# Tennis

This is a Python package about tennis. Using statistics of each player, this library determines the outcome of a tennis match: the winner and the length of time the match lasts.  In addition, this library can also recall a male player's rank, titles, wins, and losses, as well as a female player's rank, points, and tournament wins.

## Usage

Open Anaconda prompt, and navigate to Library.
To install:

    $ python setup.py install  

To install a version that changes when changes are made to the source files:

    $ python setup.py develop

Open Python.
    
    >>> import tennis 

Here is an example of how to obtain an outcome for a match between two male players, where the first output is the winner and the second is the length of time the match lasts:

    >>> tennis.m_match(tennis.nadal, tennis.federer)    
    ('Roger Federer', 158)    

Similarly, here is an example of how to obtain an outcome for a match between two female players:

    >>> tennis.f_match(tennis.halep, tennis.wozniacki)    
    ('Simona Halep', 83)


## Development

Open Anaconda Prompt, and navigate to Library\tests.
To run the tests:
    
    $ pytest
