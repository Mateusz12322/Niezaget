# libssh2

In late 2006, I wanted to add SCP and SFTP support to curl. I investigated the
library situation for SSH support and I found that there existed two similar
Open Source libraries for this purpose, confusingly similarly named too:
libssh2 and libssh.

As I wanted the SSH library to work a with a non-blocking API to suit curl
proper, I reached out to both the SSH library projects I had found and asked
them about their current support and how they viewed the future and offered to
work on providing such API/functionality myself. I thought the by far most
promising and friendly response came from **libssh2**, so I made my choice.

In November 2006 we started to add support for SCP and SFTP to curl based on
libssh2, and at the same time I started contributing improvements in the
libssh2 project. In particular to make sure the API could be set to and behave
in non-blocking way.

libssh2 was founded by Sara Golemon in December 2004 and she was still the
lead developer when I joined the project but I soon become a co-maintainer and
when Sara changed jobs in 2007 she was blocked to contribute to the project
anymore and I became almost the sole maintainer.

I am still a maintainer of the libssh2 project but I try to keep my activities
to a minimum. Others do the real work there now.

In OpenSSF's [criticality score](https://github.com/ossf/criticality_score)
update in early 2021 where they rank how critical Open Source projects are to
the world, they put libssh2 as #3222 out of 102,507.
