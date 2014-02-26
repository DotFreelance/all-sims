all-sims
========

This project enumerates all of the PhET Sims so they can be checked out simultaneously.

Here are the commands that will check out all of the PhET Sims:

1. Install git
2. Install npm
3. Install grunt
4. Run the following commands

```
mkdir phet
cd phet
git clone https://github.com/phetsims/all-sims.git
git clone https://github.com/phetsims/chipper.git
git clone https://github.com/phetsims/sherpa.git
cd all-sims
npm install
grunt get-dependencies
```