# The KINDLY License
A human readable license designed for open-source projects.

## Why yet another open-source license?
I'm not a supporter of closed source software. I do not use closed source software
and I do not promote it. This license contains simple and human readable terms.
It lets the author to decide if he/she allows using their work in closed source
projects or not. :four_leaf_clover:

## The license content
```
The KINDLY License
Copyright (c) <year> <author>

You have the permission to use this software, read its source code, modify and
redistribute it under the following terms:

 - if you want to use this software or include parts of its code in a
   closed-source or commercial project you should kindly ask the
   author (via a private message or email) and get a positive answer
 - this license should be included in the modified versions of this software
 - in case of redistributing modified copies, you are encouraged to clearly
   indicate that the copies are based on this work
 - if you think that your redistributed copy is awesome, you are encouraged to
   show the author of this software what you did and how you helped the others

You are free to install and use this software on as many machines as you want,
free of charge, making sure you met the terms above.

You are encouraged to kindly support the software and its author by:

 - sharing his/her work
 - reporting issues/bugs and asking for feature requests
 - donating money or any other things that can help the author
 - contribute on the software code by fixing bugs and adding features
```

## Installation
You can use this as command line tool and generate KINDLY licenses providing
the copyright data.

```sh
$ npm install -g kindly-license
$ kindly-license --help
```

If you want to use it programmatically, that's possible too.

## Documentation
### `KindlyLicense(year, author)`
Generates a version of the KINDLY license providing the year and the author.

#### Params
- **String** `year`: The copyright year.
- **String** `author`: The copyright holder.

#### Return
- **String** The KINDLY License generated for provided data.

## How to contribute
1. File an issue in the repository, using the bug tracker, describing the
   contribution you'd like to make. This will help us to get you started on the
   right foot.
2. Fork the project in your account and create a new branch:
   `your-great-feature`.
3. Commit your changes in that branch.
4. Open a pull request, and reference the initial issue in the pull request
   message.

## License
See the [LICENSE](./LICENSE) file.