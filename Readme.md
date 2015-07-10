# Confessional Lutheran Fortunes

This repository contains a set of public domain selections formatted for the
Unix `fortune` application.


## Files

Here are the data files and what they contain.


### small_catechism

Luther's Small Catechism, divided as best I could into small chunks. The source
is (bookofconcord.org)[http://bookofconcord.org/smallcatechism.php]. This is, I
believe, the Triglot translation. I cannot redistribute the more normally used
1986 version as it is copyrighted. If you agree with me that this is morally
repugnant, please contact CPH.

I may at some future date try to write a convertor which the user can run to
generate a 1986 fortune file from public sources.


## Installation for Mac or Linux

Make sure that you have the fortune application installed. You can usually find
it in your package manager. For Mac, try `brew install fortune`.

Check out this repository to a folder on your machine, and then add it to your
`.bash_profile` or equivalent.

    git clone git@github.com:will-in-wi/confessional-lutheran-fortunes.git ~/.confessional_lutheran_fortunes
    echo "~/.confessional_lutheran_fortunes/cl_fortune.sh" >> ~/.bash_profile


## Contributing

For simple contributions, just create a ticket describing what you would like
added. Make sure to include:
* The text
* Your source
* Copyright status

For larger contributions, fork the repository, make your changes, and send a
pull request.

Upon editing or creating a new file, run `strfile data/filename data/filename.dat` to create the compiled file.

If you create a new file, you will need to add it to the cl_fortune file.
