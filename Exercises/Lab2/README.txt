Lab2: Archive and web download

Context: in order to know more about Linux Jean has decided to download all the
HOWTOs files from the site "The Linux Documentation project". you will have to
help him to collect, unarchive and inspect the contends of this file.

1) get the archive

$ curl http://tldp.org/Linux-HOWTO-text.tar.gz

2) check the md5sum of this file

$ md5sum Linux-HOWTO-text.tar.gz

this will give you a trail of digits, compare it with another student

3) list the contends of the archive

$ tar -tf Linux-HOWTO-text.tar.gz| tee filelist.txt

( this will display the list _and_ create also a filelist.txt file with this
list in it )

4) extract
 mkdir howtos && cd howtos && tar -xvzf ../Linux-HOWTO-text.tar.gz && cd ..

5) get the number of lines within each files
for i in `cat filelist`
do
wc -l howtos/$i >> filesizes.txt
done

6) sort out which files are the shortest
sort -g filesizes.txt | head

7) Read one of them
less howtos/README
( press q to exit )
