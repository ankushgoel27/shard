# Shard For Python 2.7+


## Install Instructions

1. Install Python 2.7+ or Python 3.5+
2. Download this folder
3. Install dependencies with `sudo pip install -r requirements.txt`
4. Use with `python shard.py -l` for checking loaded modules
5. Use with `python shard.py -u <USERNAME> -p <PASSWORD>` for a password check.

## Dependencies
Requests for making HTTP requests

Implements all of the original shard modules in Python (straight rewrites)
There's an AbstractModule added that can be used for implementing additional modules.


## Tests
To run the tests you need to install extra dependencies.
You can find them in `test-requirements.txt'.

To actually run the tests execute `nose2 -v`.

### Writing tests
Tests need to be places inside the tests directory.
The files need to start with "test".
Please refer to nose2's documentation for more information
