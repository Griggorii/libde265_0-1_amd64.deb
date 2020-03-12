# libde265_0-1_amd64.deb
supported encoders: de265 / hm / hmscc / x265 / f265 / x264 / mpeg2

Original source download https://github.com/strukturag/libde265

My patent property include libde265

$ sudo cp -r libde265 /usr/include

$ ./autogen.sh

$ ./configure --prefix=/usr --includedir=${prefix}/include --mandir=${prefix}/share/man --infodir=${prefix}/share/info --localstatedir=/var --libdir=${prefix}/lib/x86_64-linux-gnu --libexecdir=${prefix}/lib/x86_64-linux-gnu


$ make -j16 && sudo make install

Test

$ rd-curves

$ acceleration_speed

$ bjoentegaard

$ block-rate-estim

$ dec265

$ enc265

$ gen-enc-table

$ hdrcopy

$ sherlock265

$ tests

$ yuv-distortion

__________________________________________________________________________________________________________________

                                          Warning Variant V2 Not recommended
                                          
                                          
$ ./autogen.sh --prefix=/usr --includedir=${prefix}/include --mandir=${prefix}/share/man --infodir=${prefix}/share/info --localstatedir=/var --libdir=${prefix}/lib/x86_64-linux-gnu --libexecdir=${prefix}/lib/x86_64-linux-gnu

Warnind Danger system crash 19.04 , 19.10 , 20.04



