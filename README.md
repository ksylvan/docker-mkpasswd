# docker-mkpasswd

Quick alpine python based container to run the Linux sha-512
password algorithm.

## Usage

    docker run --rm kayvan/mkpasswd --method=sha-512 TeStPassword
    $6$07O48v3a47GeYR$l8F.xYUjtKnVU8o/GXWY4mZ8Ix4PNF3K.OcJn8PCaDY[...]

*Author: Kayvan Sylvan <kayvansylvan@gmail.com>*
