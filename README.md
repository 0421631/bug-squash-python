# bug squash python

Welcome to the terrastruct python bug squash.

## setup

Please run the following to set yourself up:

```sh
cd requests
python3 -m venv .venv
source .venv/bin/activate
pip3 install -r requirements-dev.txt
```

## tests

Now you can run the tests with:

```sh
pytest tests/test_requests.py --verbose --capture=no --timeout=30
```

Fix the unexpected behaviour. Don't underestimate the bug, it's not a typo.

The bug is in the request module's code and not in the tests.

This was a real bug in the python [psf/requests](https://github.com/psf/requests) library
and is often given as an interview challenge at Stripe.

Good luck!
