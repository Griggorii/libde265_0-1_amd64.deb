# libde265_V0.0.12 property compilation command tutorial
supported encoders: de265 / hm / hmscc / x265 / f265 / x264 / mpeg2

Original source download https://github.com/strukturag/libde265

My patent property compilation command tutorial x86_64-linux-gnu not x86_64-linux-gnu replace example i386 -> {prefix}/lib/i386   u̶s̶r̶/̶l̶i̶b̶/̶i̶3̶8̶6<-not   {prefix}/lib/i386<-good !

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

Warning Danger ./autogen.sh configuration ! rm sed system crash 19.04 , 19.10 , 20.04



