Notes
-----

jvar project forked from https://code.google.com/p/jvarkit/

At this point this fork differs from the original some changes in the "VCFBigWig.java". The first change is to set contained to true when calling the getBigWigIterator method. The second is to change from "," to "." in the output info field (as well as adding some decimals in the output).

Run `setup.sh` to get and build the BigWig dependencies, and then get the vcgbigwig by `ant vcfbigwig`.

Usage
-----

`java -jar dist/vcfbigwig.jar -f file.bw (file.vcf|stdin)`

Options
-------

` -f (bigwig-file) required.
 -i (String) VCF-ID optional. `


Licence
-------

[GNU GPL v3](http://www.gnu.org/licenses/gpl.html)
