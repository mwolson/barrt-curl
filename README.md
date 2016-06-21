# barrt-curl - cURL support for BARRT (A Bash Rspec-like Regression Test framework)

## Use it

Install these two modules from npm:

```sh
npm i --save barrt
npm i --save barrt-curl
```

Edit the `setup.sh` file in your test suite to include the following:

```sh
#!/bin/bash

modules=$(dirname "$BASH_SOURCE")/node_modules

. "$modules"/barrt/setup.sh
. "$modules"/barrt-curl/setup.sh

# other setup tasks...
```

Create a `runner.sh` file in your test suite with these contents:

```sh
#!/bin/bash

modules=$(dirname "$BASH_SOURCE")/node_modules

exec "$modules"/barrt/runner.sh
```

## API


## License

MIT
