# gh license

Add a LICENSE file to the current directory.

Usage:
```sh
$ gh extension install mislav/gh-license

# list available licenses
$ gh license

# add a specific license
$ gh license bsd-3-clause
```

The result will be a LICENSE file in the current directory:
```
$ head LICENSE
BSD 3-Clause License

Copyright (c) 2022, Mislav Marohnić
All rights reserved.

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions are met:

1. Redistributions of source code must retain the above copyright notice, this
   list of conditions and the following disclaimer.
```

You can also choose a license interactively through the web interface:
```
gh license --web
```
