### [mruby-cli-docker](https://github.com/hone/mruby-cli-docker/blob/master/Dockerfile)

```
...

# install osx cross compiling tools
RUN cd /opt/ && \
  git clone https://github.com/tpoechtrager/osxcross.git
COPY MacOSX10.10.sdk.tar.bz2 /opt/osxcross/tarballs/
RUN echo "\n" | bash /opt/osxcross/build.sh
RUN rm /opt/osxcross/tarballs/*
ENV PATH /opt/osxcross/target/bin:$PATH
ENV SHELL /bin/bash

# install msitools
RUN cd /tmp && wget https://launchpad.net/ubuntu/+archive/primary/+files/gcab_0.6.orig.tar.xz && tar -xf gcab_0.6.orig.tar.xz && cd gcab-0.6 && ./configure && make && make install

...
```

https://github.com/hone/mruby-cli-docker/blob/master/Dockerfile
