<!-- THIS FILE IS GENERATED VIA '.template-helpers/generate-tag-details.pl' -->

# Tags of `iojs`

-	[`iojs:1.8.4`](#iojs184)
-	[`iojs:1.8`](#iojs18)
-	[`iojs:1`](#iojs1)
-	[`iojs:1.8.4-onbuild`](#iojs184-onbuild)
-	[`iojs:1.8-onbuild`](#iojs18-onbuild)
-	[`iojs:1-onbuild`](#iojs1-onbuild)
-	[`iojs:1.8.4-slim`](#iojs184-slim)
-	[`iojs:1.8-slim`](#iojs18-slim)
-	[`iojs:1-slim`](#iojs1-slim)
-	[`iojs:2.5.0`](#iojs250)
-	[`iojs:2.5`](#iojs25)
-	[`iojs:2`](#iojs2)
-	[`iojs:2.5.0-onbuild`](#iojs250-onbuild)
-	[`iojs:2.5-onbuild`](#iojs25-onbuild)
-	[`iojs:2-onbuild`](#iojs2-onbuild)
-	[`iojs:2.5.0-slim`](#iojs250-slim)
-	[`iojs:2.5-slim`](#iojs25-slim)
-	[`iojs:2-slim`](#iojs2-slim)
-	[`iojs:3.3.0`](#iojs330)
-	[`iojs:3.3`](#iojs33)
-	[`iojs:3`](#iojs3)
-	[`iojs:latest`](#iojslatest)
-	[`iojs:3.3.0-onbuild`](#iojs330-onbuild)
-	[`iojs:3.3-onbuild`](#iojs33-onbuild)
-	[`iojs:3-onbuild`](#iojs3-onbuild)
-	[`iojs:onbuild`](#iojsonbuild)
-	[`iojs:3.3.0-slim`](#iojs330-slim)
-	[`iojs:3.3-slim`](#iojs33-slim)
-	[`iojs:3-slim`](#iojs3-slim)
-	[`iojs:slim`](#iojsslim)

## `iojs:1.8.4`

```console
$ docker pull library/iojs@sha256:74ce8d152cdc0c1c60693bebb915016722c7b94c9574796b81c6645c18afbf1b
```

-	Total Virtual Size: 634.3 MB (634263704 bytes)
-	Total v2 Content-Length: 249.6 MB (249647017 bytes)

### Layers (10)

#### `843e2bded49837e4846422f3a82a67be3ccc46c3e636e03d8d946c57564468ba`

```dockerfile
ADD file:c7d957020a6ee3df60f2407c7a383cabcfa67d43f6d5151b241b37034f5bc6e0 in /
```

-	Created: Mon, 07 Sep 2015 23:35:05 GMT
-	Docker Version: 1.7.1
-	Virtual Size: 125.2 MB (125159131 bytes)
-	v2 Blob: `sha256:f8efbffe7b954b520805da80ce0cce94e3834482c384c25c8851db98696e7f70`
-	v2 Content-Length: 51.4 MB (51359708 bytes)
-	v2 Last-Modified: Mon, 07 Sep 2015 23:38:06 GMT

#### `8c00acfb017549e44d28098762c3e6296872a1ca9b90385855f1019d84bb0dac`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Mon, 07 Sep 2015 23:35:07 GMT
-	Parent Layer: `843e2bded49837e4846422f3a82a67be3ccc46c3e636e03d8d946c57564468ba`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `8b49fe88b40b6c09bbe751e9b235d1919e704ae1765a304226047bd0b203b3fe`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 08 Sep 2015 15:27:57 GMT
-	Parent Layer: `8c00acfb017549e44d28098762c3e6296872a1ca9b90385855f1019d84bb0dac`
-	Docker Version: 1.7.1
-	Virtual Size: 44.4 MB (44355688 bytes)
-	v2 Blob: `sha256:d6314f6cfecf4fc37f622f99d2a114af91ec678d29c76983249f23995ef77563`
-	v2 Content-Length: 18.5 MB (18538583 bytes)
-	v2 Last-Modified: Thu, 10 Sep 2015 23:36:48 GMT

#### `20b348f4d5682b697d2f456322c97d916bafb65f6c4436697209ac1ec0f1803f`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 08 Sep 2015 15:29:05 GMT
-	Parent Layer: `8b49fe88b40b6c09bbe751e9b235d1919e704ae1765a304226047bd0b203b3fe`
-	Docker Version: 1.7.1
-	Virtual Size: 122.3 MB (122317988 bytes)
-	v2 Blob: `sha256:a6f2dac3eb9c26067c12dafd0c917f591d9881ee84a45f750d7a1d58187adfd8`
-	v2 Content-Length: 42.3 MB (42339522 bytes)
-	v2 Last-Modified: Tue, 08 Sep 2015 15:43:42 GMT

#### `16b189cc8ce688f9f1d8f1d837fa0891107450a06c795b1cba8f6c33a4454280`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		autoconf \
		automake \
		bzip2 \
		file \
		g++ \
		gcc \
		imagemagick \
		libbz2-dev \
		libc6-dev \
		libcurl4-openssl-dev \
		libevent-dev \
		libffi-dev \
		libgeoip-dev \
		libglib2.0-dev \
		libjpeg-dev \
		liblzma-dev \
		libmagickcore-dev \
		libmagickwand-dev \
		libmysqlclient-dev \
		libncurses-dev \
		libpng-dev \
		libpq-dev \
		libreadline-dev \
		libsqlite3-dev \
		libssl-dev \
		libtool \
		libwebp-dev \
		libxml2-dev \
		libxslt-dev \
		libyaml-dev \
		make \
		patch \
		xz-utils \
		zlib1g-dev \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 08 Sep 2015 15:31:25 GMT
-	Parent Layer: `20b348f4d5682b697d2f456322c97d916bafb65f6c4436697209ac1ec0f1803f`
-	Docker Version: 1.7.1
-	Virtual Size: 314.7 MB (314652151 bytes)
-	v2 Blob: `sha256:f4f48828d97bcfe36d5697d8f505088a4369e3d660307576f68ae74031884ca7`
-	v2 Content-Length: 128.5 MB (128531143 bytes)
-	v2 Last-Modified: Tue, 08 Sep 2015 15:45:31 GMT

#### `6227f463e6e24a6ea3c8eaae40b4b206aeb3d63b6c615c3512cd9706524f0a3e`

```dockerfile
RUN set -ex   && for key in\
     9554F04D7259F04124DE6B476D5A82AC7E37093B\
     94AE36675C464D64BAFA68DD7434390BDBE9B9C5\
     0034A06D9D9B0064CE8ADF6BF1747F4AD2306D93\
     FD3A5288F042B6850C66B31F09FE44734EB7990E\
     71DCFD284A79C3B38668286BC97EC7A07EDE3FC1\
     DD8F2338BAE7501E3DD5AC78C273792F7D83545D   ; do\
     gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"   ; done
```

-	Created: Thu, 10 Sep 2015 07:50:51 GMT
-	Parent Layer: `16b189cc8ce688f9f1d8f1d837fa0891107450a06c795b1cba8f6c33a4454280`
-	Docker Version: 1.7.1
-	Virtual Size: 39.4 KB (39419 bytes)
-	v2 Blob: `sha256:61f26d33ec3bbef5073f11f8bad058c136159dee3ea81e9f942337e2a919d062`
-	v2 Content-Length: 19.9 KB (19854 bytes)
-	v2 Last-Modified: Fri, 11 Sep 2015 04:31:02 GMT

#### `2e45961f9f233ca9913dff96558d65a5096aa0b2e6a34711d3ac51289a40f50d`

```dockerfile
ENV NPM_CONFIG_LOGLEVEL=info
```

-	Created: Thu, 10 Sep 2015 07:50:51 GMT
-	Parent Layer: `6227f463e6e24a6ea3c8eaae40b4b206aeb3d63b6c615c3512cd9706524f0a3e`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `9d71703fc5af6a867b93053bc59ed969aa95962f1583e5c6ada06af40c6ed733`

```dockerfile
ENV IOJS_VERSION=1.8.4
```

-	Created: Thu, 10 Sep 2015 07:50:52 GMT
-	Parent Layer: `2e45961f9f233ca9913dff96558d65a5096aa0b2e6a34711d3ac51289a40f50d`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `e71ccca3ecebb23e5aa7e83701fadc23f9ae39de1acc82bfa13a45b94ace6304`

```dockerfile
RUN curl -SLO "https://iojs.org/dist/v$IOJS_VERSION/iojs-v$IOJS_VERSION-linux-x64.tar.gz"   && curl -SLO "https://iojs.org/dist/v$IOJS_VERSION/SHASUMS256.txt.asc"   && gpg --verify SHASUMS256.txt.asc   && grep " iojs-v$IOJS_VERSION-linux-x64.tar.gz\$" SHASUMS256.txt.asc | sha256sum -c -   && tar -xzf "iojs-v$IOJS_VERSION-linux-x64.tar.gz" -C /usr/local --strip-components=1   && rm "iojs-v$IOJS_VERSION-linux-x64.tar.gz" SHASUMS256.txt.asc
```

-	Created: Thu, 10 Sep 2015 07:50:57 GMT
-	Parent Layer: `9d71703fc5af6a867b93053bc59ed969aa95962f1583e5c6ada06af40c6ed733`
-	Docker Version: 1.7.1
-	Virtual Size: 27.7 MB (27739327 bytes)
-	v2 Blob: `sha256:b9ee50e4201d1e2daec5cb3830428fe5b35b81762cdda5de7ad1409b2d79f28c`
-	v2 Content-Length: 8.9 MB (8858079 bytes)
-	v2 Last-Modified: Fri, 11 Sep 2015 04:30:49 GMT

#### `4a8b49bca7559021391dfdf0c28ede2002c9a5c2aedb9b2db11e35dfb29861d9`

```dockerfile
CMD ["iojs"]
```

-	Created: Thu, 10 Sep 2015 07:50:58 GMT
-	Parent Layer: `e71ccca3ecebb23e5aa7e83701fadc23f9ae39de1acc82bfa13a45b94ace6304`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

## `iojs:1.8`

```console
$ docker pull library/iojs@sha256:f144148bafb66aeb6b111d71c348c602915d8ede03e23889c47948ed088a3899
```

-	Total Virtual Size: 634.3 MB (634263704 bytes)
-	Total v2 Content-Length: 249.6 MB (249647017 bytes)

### Layers (10)

#### `843e2bded49837e4846422f3a82a67be3ccc46c3e636e03d8d946c57564468ba`

```dockerfile
ADD file:c7d957020a6ee3df60f2407c7a383cabcfa67d43f6d5151b241b37034f5bc6e0 in /
```

-	Created: Mon, 07 Sep 2015 23:35:05 GMT
-	Docker Version: 1.7.1
-	Virtual Size: 125.2 MB (125159131 bytes)
-	v2 Blob: `sha256:f8efbffe7b954b520805da80ce0cce94e3834482c384c25c8851db98696e7f70`
-	v2 Content-Length: 51.4 MB (51359708 bytes)
-	v2 Last-Modified: Mon, 07 Sep 2015 23:38:06 GMT

#### `8c00acfb017549e44d28098762c3e6296872a1ca9b90385855f1019d84bb0dac`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Mon, 07 Sep 2015 23:35:07 GMT
-	Parent Layer: `843e2bded49837e4846422f3a82a67be3ccc46c3e636e03d8d946c57564468ba`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `8b49fe88b40b6c09bbe751e9b235d1919e704ae1765a304226047bd0b203b3fe`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 08 Sep 2015 15:27:57 GMT
-	Parent Layer: `8c00acfb017549e44d28098762c3e6296872a1ca9b90385855f1019d84bb0dac`
-	Docker Version: 1.7.1
-	Virtual Size: 44.4 MB (44355688 bytes)
-	v2 Blob: `sha256:d6314f6cfecf4fc37f622f99d2a114af91ec678d29c76983249f23995ef77563`
-	v2 Content-Length: 18.5 MB (18538583 bytes)
-	v2 Last-Modified: Thu, 10 Sep 2015 23:36:48 GMT

#### `20b348f4d5682b697d2f456322c97d916bafb65f6c4436697209ac1ec0f1803f`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 08 Sep 2015 15:29:05 GMT
-	Parent Layer: `8b49fe88b40b6c09bbe751e9b235d1919e704ae1765a304226047bd0b203b3fe`
-	Docker Version: 1.7.1
-	Virtual Size: 122.3 MB (122317988 bytes)
-	v2 Blob: `sha256:a6f2dac3eb9c26067c12dafd0c917f591d9881ee84a45f750d7a1d58187adfd8`
-	v2 Content-Length: 42.3 MB (42339522 bytes)
-	v2 Last-Modified: Tue, 08 Sep 2015 15:43:42 GMT

#### `16b189cc8ce688f9f1d8f1d837fa0891107450a06c795b1cba8f6c33a4454280`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		autoconf \
		automake \
		bzip2 \
		file \
		g++ \
		gcc \
		imagemagick \
		libbz2-dev \
		libc6-dev \
		libcurl4-openssl-dev \
		libevent-dev \
		libffi-dev \
		libgeoip-dev \
		libglib2.0-dev \
		libjpeg-dev \
		liblzma-dev \
		libmagickcore-dev \
		libmagickwand-dev \
		libmysqlclient-dev \
		libncurses-dev \
		libpng-dev \
		libpq-dev \
		libreadline-dev \
		libsqlite3-dev \
		libssl-dev \
		libtool \
		libwebp-dev \
		libxml2-dev \
		libxslt-dev \
		libyaml-dev \
		make \
		patch \
		xz-utils \
		zlib1g-dev \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 08 Sep 2015 15:31:25 GMT
-	Parent Layer: `20b348f4d5682b697d2f456322c97d916bafb65f6c4436697209ac1ec0f1803f`
-	Docker Version: 1.7.1
-	Virtual Size: 314.7 MB (314652151 bytes)
-	v2 Blob: `sha256:f4f48828d97bcfe36d5697d8f505088a4369e3d660307576f68ae74031884ca7`
-	v2 Content-Length: 128.5 MB (128531143 bytes)
-	v2 Last-Modified: Tue, 08 Sep 2015 15:45:31 GMT

#### `6227f463e6e24a6ea3c8eaae40b4b206aeb3d63b6c615c3512cd9706524f0a3e`

```dockerfile
RUN set -ex   && for key in\
     9554F04D7259F04124DE6B476D5A82AC7E37093B\
     94AE36675C464D64BAFA68DD7434390BDBE9B9C5\
     0034A06D9D9B0064CE8ADF6BF1747F4AD2306D93\
     FD3A5288F042B6850C66B31F09FE44734EB7990E\
     71DCFD284A79C3B38668286BC97EC7A07EDE3FC1\
     DD8F2338BAE7501E3DD5AC78C273792F7D83545D   ; do\
     gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"   ; done
```

-	Created: Thu, 10 Sep 2015 07:50:51 GMT
-	Parent Layer: `16b189cc8ce688f9f1d8f1d837fa0891107450a06c795b1cba8f6c33a4454280`
-	Docker Version: 1.7.1
-	Virtual Size: 39.4 KB (39419 bytes)
-	v2 Blob: `sha256:61f26d33ec3bbef5073f11f8bad058c136159dee3ea81e9f942337e2a919d062`
-	v2 Content-Length: 19.9 KB (19854 bytes)
-	v2 Last-Modified: Fri, 11 Sep 2015 04:31:02 GMT

#### `2e45961f9f233ca9913dff96558d65a5096aa0b2e6a34711d3ac51289a40f50d`

```dockerfile
ENV NPM_CONFIG_LOGLEVEL=info
```

-	Created: Thu, 10 Sep 2015 07:50:51 GMT
-	Parent Layer: `6227f463e6e24a6ea3c8eaae40b4b206aeb3d63b6c615c3512cd9706524f0a3e`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `9d71703fc5af6a867b93053bc59ed969aa95962f1583e5c6ada06af40c6ed733`

```dockerfile
ENV IOJS_VERSION=1.8.4
```

-	Created: Thu, 10 Sep 2015 07:50:52 GMT
-	Parent Layer: `2e45961f9f233ca9913dff96558d65a5096aa0b2e6a34711d3ac51289a40f50d`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `e71ccca3ecebb23e5aa7e83701fadc23f9ae39de1acc82bfa13a45b94ace6304`

```dockerfile
RUN curl -SLO "https://iojs.org/dist/v$IOJS_VERSION/iojs-v$IOJS_VERSION-linux-x64.tar.gz"   && curl -SLO "https://iojs.org/dist/v$IOJS_VERSION/SHASUMS256.txt.asc"   && gpg --verify SHASUMS256.txt.asc   && grep " iojs-v$IOJS_VERSION-linux-x64.tar.gz\$" SHASUMS256.txt.asc | sha256sum -c -   && tar -xzf "iojs-v$IOJS_VERSION-linux-x64.tar.gz" -C /usr/local --strip-components=1   && rm "iojs-v$IOJS_VERSION-linux-x64.tar.gz" SHASUMS256.txt.asc
```

-	Created: Thu, 10 Sep 2015 07:50:57 GMT
-	Parent Layer: `9d71703fc5af6a867b93053bc59ed969aa95962f1583e5c6ada06af40c6ed733`
-	Docker Version: 1.7.1
-	Virtual Size: 27.7 MB (27739327 bytes)
-	v2 Blob: `sha256:b9ee50e4201d1e2daec5cb3830428fe5b35b81762cdda5de7ad1409b2d79f28c`
-	v2 Content-Length: 8.9 MB (8858079 bytes)
-	v2 Last-Modified: Fri, 11 Sep 2015 04:30:49 GMT

#### `4a8b49bca7559021391dfdf0c28ede2002c9a5c2aedb9b2db11e35dfb29861d9`

```dockerfile
CMD ["iojs"]
```

-	Created: Thu, 10 Sep 2015 07:50:58 GMT
-	Parent Layer: `e71ccca3ecebb23e5aa7e83701fadc23f9ae39de1acc82bfa13a45b94ace6304`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

## `iojs:1`

```console
$ docker pull library/iojs@sha256:f52025ee7ce351d63e10f60d24aed03d075c5f78dd1709edd3ee4a2bd400a0d1
```

-	Total Virtual Size: 634.3 MB (634263704 bytes)
-	Total v2 Content-Length: 249.6 MB (249647017 bytes)

### Layers (10)

#### `843e2bded49837e4846422f3a82a67be3ccc46c3e636e03d8d946c57564468ba`

```dockerfile
ADD file:c7d957020a6ee3df60f2407c7a383cabcfa67d43f6d5151b241b37034f5bc6e0 in /
```

-	Created: Mon, 07 Sep 2015 23:35:05 GMT
-	Docker Version: 1.7.1
-	Virtual Size: 125.2 MB (125159131 bytes)
-	v2 Blob: `sha256:f8efbffe7b954b520805da80ce0cce94e3834482c384c25c8851db98696e7f70`
-	v2 Content-Length: 51.4 MB (51359708 bytes)
-	v2 Last-Modified: Mon, 07 Sep 2015 23:38:06 GMT

#### `8c00acfb017549e44d28098762c3e6296872a1ca9b90385855f1019d84bb0dac`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Mon, 07 Sep 2015 23:35:07 GMT
-	Parent Layer: `843e2bded49837e4846422f3a82a67be3ccc46c3e636e03d8d946c57564468ba`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `8b49fe88b40b6c09bbe751e9b235d1919e704ae1765a304226047bd0b203b3fe`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 08 Sep 2015 15:27:57 GMT
-	Parent Layer: `8c00acfb017549e44d28098762c3e6296872a1ca9b90385855f1019d84bb0dac`
-	Docker Version: 1.7.1
-	Virtual Size: 44.4 MB (44355688 bytes)
-	v2 Blob: `sha256:d6314f6cfecf4fc37f622f99d2a114af91ec678d29c76983249f23995ef77563`
-	v2 Content-Length: 18.5 MB (18538583 bytes)
-	v2 Last-Modified: Thu, 10 Sep 2015 23:36:48 GMT

#### `20b348f4d5682b697d2f456322c97d916bafb65f6c4436697209ac1ec0f1803f`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 08 Sep 2015 15:29:05 GMT
-	Parent Layer: `8b49fe88b40b6c09bbe751e9b235d1919e704ae1765a304226047bd0b203b3fe`
-	Docker Version: 1.7.1
-	Virtual Size: 122.3 MB (122317988 bytes)
-	v2 Blob: `sha256:a6f2dac3eb9c26067c12dafd0c917f591d9881ee84a45f750d7a1d58187adfd8`
-	v2 Content-Length: 42.3 MB (42339522 bytes)
-	v2 Last-Modified: Tue, 08 Sep 2015 15:43:42 GMT

#### `16b189cc8ce688f9f1d8f1d837fa0891107450a06c795b1cba8f6c33a4454280`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		autoconf \
		automake \
		bzip2 \
		file \
		g++ \
		gcc \
		imagemagick \
		libbz2-dev \
		libc6-dev \
		libcurl4-openssl-dev \
		libevent-dev \
		libffi-dev \
		libgeoip-dev \
		libglib2.0-dev \
		libjpeg-dev \
		liblzma-dev \
		libmagickcore-dev \
		libmagickwand-dev \
		libmysqlclient-dev \
		libncurses-dev \
		libpng-dev \
		libpq-dev \
		libreadline-dev \
		libsqlite3-dev \
		libssl-dev \
		libtool \
		libwebp-dev \
		libxml2-dev \
		libxslt-dev \
		libyaml-dev \
		make \
		patch \
		xz-utils \
		zlib1g-dev \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 08 Sep 2015 15:31:25 GMT
-	Parent Layer: `20b348f4d5682b697d2f456322c97d916bafb65f6c4436697209ac1ec0f1803f`
-	Docker Version: 1.7.1
-	Virtual Size: 314.7 MB (314652151 bytes)
-	v2 Blob: `sha256:f4f48828d97bcfe36d5697d8f505088a4369e3d660307576f68ae74031884ca7`
-	v2 Content-Length: 128.5 MB (128531143 bytes)
-	v2 Last-Modified: Tue, 08 Sep 2015 15:45:31 GMT

#### `6227f463e6e24a6ea3c8eaae40b4b206aeb3d63b6c615c3512cd9706524f0a3e`

```dockerfile
RUN set -ex   && for key in\
     9554F04D7259F04124DE6B476D5A82AC7E37093B\
     94AE36675C464D64BAFA68DD7434390BDBE9B9C5\
     0034A06D9D9B0064CE8ADF6BF1747F4AD2306D93\
     FD3A5288F042B6850C66B31F09FE44734EB7990E\
     71DCFD284A79C3B38668286BC97EC7A07EDE3FC1\
     DD8F2338BAE7501E3DD5AC78C273792F7D83545D   ; do\
     gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"   ; done
```

-	Created: Thu, 10 Sep 2015 07:50:51 GMT
-	Parent Layer: `16b189cc8ce688f9f1d8f1d837fa0891107450a06c795b1cba8f6c33a4454280`
-	Docker Version: 1.7.1
-	Virtual Size: 39.4 KB (39419 bytes)
-	v2 Blob: `sha256:61f26d33ec3bbef5073f11f8bad058c136159dee3ea81e9f942337e2a919d062`
-	v2 Content-Length: 19.9 KB (19854 bytes)
-	v2 Last-Modified: Fri, 11 Sep 2015 04:31:02 GMT

#### `2e45961f9f233ca9913dff96558d65a5096aa0b2e6a34711d3ac51289a40f50d`

```dockerfile
ENV NPM_CONFIG_LOGLEVEL=info
```

-	Created: Thu, 10 Sep 2015 07:50:51 GMT
-	Parent Layer: `6227f463e6e24a6ea3c8eaae40b4b206aeb3d63b6c615c3512cd9706524f0a3e`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `9d71703fc5af6a867b93053bc59ed969aa95962f1583e5c6ada06af40c6ed733`

```dockerfile
ENV IOJS_VERSION=1.8.4
```

-	Created: Thu, 10 Sep 2015 07:50:52 GMT
-	Parent Layer: `2e45961f9f233ca9913dff96558d65a5096aa0b2e6a34711d3ac51289a40f50d`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `e71ccca3ecebb23e5aa7e83701fadc23f9ae39de1acc82bfa13a45b94ace6304`

```dockerfile
RUN curl -SLO "https://iojs.org/dist/v$IOJS_VERSION/iojs-v$IOJS_VERSION-linux-x64.tar.gz"   && curl -SLO "https://iojs.org/dist/v$IOJS_VERSION/SHASUMS256.txt.asc"   && gpg --verify SHASUMS256.txt.asc   && grep " iojs-v$IOJS_VERSION-linux-x64.tar.gz\$" SHASUMS256.txt.asc | sha256sum -c -   && tar -xzf "iojs-v$IOJS_VERSION-linux-x64.tar.gz" -C /usr/local --strip-components=1   && rm "iojs-v$IOJS_VERSION-linux-x64.tar.gz" SHASUMS256.txt.asc
```

-	Created: Thu, 10 Sep 2015 07:50:57 GMT
-	Parent Layer: `9d71703fc5af6a867b93053bc59ed969aa95962f1583e5c6ada06af40c6ed733`
-	Docker Version: 1.7.1
-	Virtual Size: 27.7 MB (27739327 bytes)
-	v2 Blob: `sha256:b9ee50e4201d1e2daec5cb3830428fe5b35b81762cdda5de7ad1409b2d79f28c`
-	v2 Content-Length: 8.9 MB (8858079 bytes)
-	v2 Last-Modified: Fri, 11 Sep 2015 04:30:49 GMT

#### `4a8b49bca7559021391dfdf0c28ede2002c9a5c2aedb9b2db11e35dfb29861d9`

```dockerfile
CMD ["iojs"]
```

-	Created: Thu, 10 Sep 2015 07:50:58 GMT
-	Parent Layer: `e71ccca3ecebb23e5aa7e83701fadc23f9ae39de1acc82bfa13a45b94ace6304`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

## `iojs:1.8.4-onbuild`

```console
$ docker pull library/iojs@sha256:13a8c6c4043ebd416042cbb9aac50b06f8ba3774c43e7494ff2359799a835170
```

-	Total Virtual Size: 634.3 MB (634263704 bytes)
-	Total v2 Content-Length: 249.6 MB (249647305 bytes)

### Layers (16)

#### `843e2bded49837e4846422f3a82a67be3ccc46c3e636e03d8d946c57564468ba`

```dockerfile
ADD file:c7d957020a6ee3df60f2407c7a383cabcfa67d43f6d5151b241b37034f5bc6e0 in /
```

-	Created: Mon, 07 Sep 2015 23:35:05 GMT
-	Docker Version: 1.7.1
-	Virtual Size: 125.2 MB (125159131 bytes)
-	v2 Blob: `sha256:f8efbffe7b954b520805da80ce0cce94e3834482c384c25c8851db98696e7f70`
-	v2 Content-Length: 51.4 MB (51359708 bytes)
-	v2 Last-Modified: Mon, 07 Sep 2015 23:38:06 GMT

#### `8c00acfb017549e44d28098762c3e6296872a1ca9b90385855f1019d84bb0dac`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Mon, 07 Sep 2015 23:35:07 GMT
-	Parent Layer: `843e2bded49837e4846422f3a82a67be3ccc46c3e636e03d8d946c57564468ba`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `8b49fe88b40b6c09bbe751e9b235d1919e704ae1765a304226047bd0b203b3fe`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 08 Sep 2015 15:27:57 GMT
-	Parent Layer: `8c00acfb017549e44d28098762c3e6296872a1ca9b90385855f1019d84bb0dac`
-	Docker Version: 1.7.1
-	Virtual Size: 44.4 MB (44355688 bytes)
-	v2 Blob: `sha256:d6314f6cfecf4fc37f622f99d2a114af91ec678d29c76983249f23995ef77563`
-	v2 Content-Length: 18.5 MB (18538583 bytes)
-	v2 Last-Modified: Thu, 10 Sep 2015 23:36:48 GMT

#### `20b348f4d5682b697d2f456322c97d916bafb65f6c4436697209ac1ec0f1803f`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 08 Sep 2015 15:29:05 GMT
-	Parent Layer: `8b49fe88b40b6c09bbe751e9b235d1919e704ae1765a304226047bd0b203b3fe`
-	Docker Version: 1.7.1
-	Virtual Size: 122.3 MB (122317988 bytes)
-	v2 Blob: `sha256:a6f2dac3eb9c26067c12dafd0c917f591d9881ee84a45f750d7a1d58187adfd8`
-	v2 Content-Length: 42.3 MB (42339522 bytes)
-	v2 Last-Modified: Tue, 08 Sep 2015 15:43:42 GMT

#### `16b189cc8ce688f9f1d8f1d837fa0891107450a06c795b1cba8f6c33a4454280`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		autoconf \
		automake \
		bzip2 \
		file \
		g++ \
		gcc \
		imagemagick \
		libbz2-dev \
		libc6-dev \
		libcurl4-openssl-dev \
		libevent-dev \
		libffi-dev \
		libgeoip-dev \
		libglib2.0-dev \
		libjpeg-dev \
		liblzma-dev \
		libmagickcore-dev \
		libmagickwand-dev \
		libmysqlclient-dev \
		libncurses-dev \
		libpng-dev \
		libpq-dev \
		libreadline-dev \
		libsqlite3-dev \
		libssl-dev \
		libtool \
		libwebp-dev \
		libxml2-dev \
		libxslt-dev \
		libyaml-dev \
		make \
		patch \
		xz-utils \
		zlib1g-dev \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 08 Sep 2015 15:31:25 GMT
-	Parent Layer: `20b348f4d5682b697d2f456322c97d916bafb65f6c4436697209ac1ec0f1803f`
-	Docker Version: 1.7.1
-	Virtual Size: 314.7 MB (314652151 bytes)
-	v2 Blob: `sha256:f4f48828d97bcfe36d5697d8f505088a4369e3d660307576f68ae74031884ca7`
-	v2 Content-Length: 128.5 MB (128531143 bytes)
-	v2 Last-Modified: Tue, 08 Sep 2015 15:45:31 GMT

#### `6227f463e6e24a6ea3c8eaae40b4b206aeb3d63b6c615c3512cd9706524f0a3e`

```dockerfile
RUN set -ex   && for key in\
     9554F04D7259F04124DE6B476D5A82AC7E37093B\
     94AE36675C464D64BAFA68DD7434390BDBE9B9C5\
     0034A06D9D9B0064CE8ADF6BF1747F4AD2306D93\
     FD3A5288F042B6850C66B31F09FE44734EB7990E\
     71DCFD284A79C3B38668286BC97EC7A07EDE3FC1\
     DD8F2338BAE7501E3DD5AC78C273792F7D83545D   ; do\
     gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"   ; done
```

-	Created: Thu, 10 Sep 2015 07:50:51 GMT
-	Parent Layer: `16b189cc8ce688f9f1d8f1d837fa0891107450a06c795b1cba8f6c33a4454280`
-	Docker Version: 1.7.1
-	Virtual Size: 39.4 KB (39419 bytes)
-	v2 Blob: `sha256:61f26d33ec3bbef5073f11f8bad058c136159dee3ea81e9f942337e2a919d062`
-	v2 Content-Length: 19.9 KB (19854 bytes)
-	v2 Last-Modified: Fri, 11 Sep 2015 04:31:02 GMT

#### `2e45961f9f233ca9913dff96558d65a5096aa0b2e6a34711d3ac51289a40f50d`

```dockerfile
ENV NPM_CONFIG_LOGLEVEL=info
```

-	Created: Thu, 10 Sep 2015 07:50:51 GMT
-	Parent Layer: `6227f463e6e24a6ea3c8eaae40b4b206aeb3d63b6c615c3512cd9706524f0a3e`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `9d71703fc5af6a867b93053bc59ed969aa95962f1583e5c6ada06af40c6ed733`

```dockerfile
ENV IOJS_VERSION=1.8.4
```

-	Created: Thu, 10 Sep 2015 07:50:52 GMT
-	Parent Layer: `2e45961f9f233ca9913dff96558d65a5096aa0b2e6a34711d3ac51289a40f50d`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `e71ccca3ecebb23e5aa7e83701fadc23f9ae39de1acc82bfa13a45b94ace6304`

```dockerfile
RUN curl -SLO "https://iojs.org/dist/v$IOJS_VERSION/iojs-v$IOJS_VERSION-linux-x64.tar.gz"   && curl -SLO "https://iojs.org/dist/v$IOJS_VERSION/SHASUMS256.txt.asc"   && gpg --verify SHASUMS256.txt.asc   && grep " iojs-v$IOJS_VERSION-linux-x64.tar.gz\$" SHASUMS256.txt.asc | sha256sum -c -   && tar -xzf "iojs-v$IOJS_VERSION-linux-x64.tar.gz" -C /usr/local --strip-components=1   && rm "iojs-v$IOJS_VERSION-linux-x64.tar.gz" SHASUMS256.txt.asc
```

-	Created: Thu, 10 Sep 2015 07:50:57 GMT
-	Parent Layer: `9d71703fc5af6a867b93053bc59ed969aa95962f1583e5c6ada06af40c6ed733`
-	Docker Version: 1.7.1
-	Virtual Size: 27.7 MB (27739327 bytes)
-	v2 Blob: `sha256:b9ee50e4201d1e2daec5cb3830428fe5b35b81762cdda5de7ad1409b2d79f28c`
-	v2 Content-Length: 8.9 MB (8858079 bytes)
-	v2 Last-Modified: Fri, 11 Sep 2015 04:30:49 GMT

#### `4a8b49bca7559021391dfdf0c28ede2002c9a5c2aedb9b2db11e35dfb29861d9`

```dockerfile
CMD ["iojs"]
```

-	Created: Thu, 10 Sep 2015 07:50:58 GMT
-	Parent Layer: `e71ccca3ecebb23e5aa7e83701fadc23f9ae39de1acc82bfa13a45b94ace6304`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `f0ed0e53dd58a300300895ddfc11f42ba380b5d892c17c2f66e0d792215f2d9c`

```dockerfile
RUN mkdir -p /usr/src/app
```

-	Created: Thu, 10 Sep 2015 07:51:35 GMT
-	Parent Layer: `4a8b49bca7559021391dfdf0c28ede2002c9a5c2aedb9b2db11e35dfb29861d9`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:2a57f56f1970941ef543d0c536769b7f5d5a4437c8516aaddfe233d137a9c03c`
-	v2 Content-Length: 128.0 B
-	v2 Last-Modified: Fri, 11 Sep 2015 04:37:17 GMT

#### `4f225461d57e7eb76ed2b60c2159de7bcece88bca7591d602d7feb3f2545df58`

```dockerfile
WORKDIR /usr/src/app
```

-	Created: Thu, 10 Sep 2015 07:51:35 GMT
-	Parent Layer: `f0ed0e53dd58a300300895ddfc11f42ba380b5d892c17c2f66e0d792215f2d9c`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `37e20e64a819b56199ccf4a221d7273f45889d38c8b5b2d6e715b80aa73a7fcb`

```dockerfile
ONBUILD COPY package.json /usr/src/app/
```

-	Created: Thu, 10 Sep 2015 07:51:36 GMT
-	Parent Layer: `4f225461d57e7eb76ed2b60c2159de7bcece88bca7591d602d7feb3f2545df58`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `a2fafb149118bcf80021482e76d5d13e00a5ed9fd059b686cbfd191b7f057caa`

```dockerfile
ONBUILD RUN npm install
```

-	Created: Thu, 10 Sep 2015 07:51:36 GMT
-	Parent Layer: `37e20e64a819b56199ccf4a221d7273f45889d38c8b5b2d6e715b80aa73a7fcb`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `04678cd0ead8f9cdb50a1b974487ca581c89e3e41f4a73040f9b5bb4d8c5086a`

```dockerfile
ONBUILD COPY . /usr/src/app
```

-	Created: Thu, 10 Sep 2015 07:51:37 GMT
-	Parent Layer: `a2fafb149118bcf80021482e76d5d13e00a5ed9fd059b686cbfd191b7f057caa`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `b590d3ee658428281816f126207d270c25c9e32509e2fc4f682fba334f3fadec`

```dockerfile
CMD ["npm" "start"]
```

-	Created: Thu, 10 Sep 2015 07:51:37 GMT
-	Parent Layer: `04678cd0ead8f9cdb50a1b974487ca581c89e3e41f4a73040f9b5bb4d8c5086a`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

## `iojs:1.8-onbuild`

```console
$ docker pull library/iojs@sha256:ca17a1e9d45e77be4daf1d4dbd6fbdb3b66d6d6d470ee79563d2bcc92d291faa
```

-	Total Virtual Size: 634.3 MB (634263704 bytes)
-	Total v2 Content-Length: 249.6 MB (249647305 bytes)

### Layers (16)

#### `843e2bded49837e4846422f3a82a67be3ccc46c3e636e03d8d946c57564468ba`

```dockerfile
ADD file:c7d957020a6ee3df60f2407c7a383cabcfa67d43f6d5151b241b37034f5bc6e0 in /
```

-	Created: Mon, 07 Sep 2015 23:35:05 GMT
-	Docker Version: 1.7.1
-	Virtual Size: 125.2 MB (125159131 bytes)
-	v2 Blob: `sha256:f8efbffe7b954b520805da80ce0cce94e3834482c384c25c8851db98696e7f70`
-	v2 Content-Length: 51.4 MB (51359708 bytes)
-	v2 Last-Modified: Mon, 07 Sep 2015 23:38:06 GMT

#### `8c00acfb017549e44d28098762c3e6296872a1ca9b90385855f1019d84bb0dac`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Mon, 07 Sep 2015 23:35:07 GMT
-	Parent Layer: `843e2bded49837e4846422f3a82a67be3ccc46c3e636e03d8d946c57564468ba`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `8b49fe88b40b6c09bbe751e9b235d1919e704ae1765a304226047bd0b203b3fe`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 08 Sep 2015 15:27:57 GMT
-	Parent Layer: `8c00acfb017549e44d28098762c3e6296872a1ca9b90385855f1019d84bb0dac`
-	Docker Version: 1.7.1
-	Virtual Size: 44.4 MB (44355688 bytes)
-	v2 Blob: `sha256:d6314f6cfecf4fc37f622f99d2a114af91ec678d29c76983249f23995ef77563`
-	v2 Content-Length: 18.5 MB (18538583 bytes)
-	v2 Last-Modified: Thu, 10 Sep 2015 23:36:48 GMT

#### `20b348f4d5682b697d2f456322c97d916bafb65f6c4436697209ac1ec0f1803f`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 08 Sep 2015 15:29:05 GMT
-	Parent Layer: `8b49fe88b40b6c09bbe751e9b235d1919e704ae1765a304226047bd0b203b3fe`
-	Docker Version: 1.7.1
-	Virtual Size: 122.3 MB (122317988 bytes)
-	v2 Blob: `sha256:a6f2dac3eb9c26067c12dafd0c917f591d9881ee84a45f750d7a1d58187adfd8`
-	v2 Content-Length: 42.3 MB (42339522 bytes)
-	v2 Last-Modified: Tue, 08 Sep 2015 15:43:42 GMT

#### `16b189cc8ce688f9f1d8f1d837fa0891107450a06c795b1cba8f6c33a4454280`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		autoconf \
		automake \
		bzip2 \
		file \
		g++ \
		gcc \
		imagemagick \
		libbz2-dev \
		libc6-dev \
		libcurl4-openssl-dev \
		libevent-dev \
		libffi-dev \
		libgeoip-dev \
		libglib2.0-dev \
		libjpeg-dev \
		liblzma-dev \
		libmagickcore-dev \
		libmagickwand-dev \
		libmysqlclient-dev \
		libncurses-dev \
		libpng-dev \
		libpq-dev \
		libreadline-dev \
		libsqlite3-dev \
		libssl-dev \
		libtool \
		libwebp-dev \
		libxml2-dev \
		libxslt-dev \
		libyaml-dev \
		make \
		patch \
		xz-utils \
		zlib1g-dev \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 08 Sep 2015 15:31:25 GMT
-	Parent Layer: `20b348f4d5682b697d2f456322c97d916bafb65f6c4436697209ac1ec0f1803f`
-	Docker Version: 1.7.1
-	Virtual Size: 314.7 MB (314652151 bytes)
-	v2 Blob: `sha256:f4f48828d97bcfe36d5697d8f505088a4369e3d660307576f68ae74031884ca7`
-	v2 Content-Length: 128.5 MB (128531143 bytes)
-	v2 Last-Modified: Tue, 08 Sep 2015 15:45:31 GMT

#### `6227f463e6e24a6ea3c8eaae40b4b206aeb3d63b6c615c3512cd9706524f0a3e`

```dockerfile
RUN set -ex   && for key in\
     9554F04D7259F04124DE6B476D5A82AC7E37093B\
     94AE36675C464D64BAFA68DD7434390BDBE9B9C5\
     0034A06D9D9B0064CE8ADF6BF1747F4AD2306D93\
     FD3A5288F042B6850C66B31F09FE44734EB7990E\
     71DCFD284A79C3B38668286BC97EC7A07EDE3FC1\
     DD8F2338BAE7501E3DD5AC78C273792F7D83545D   ; do\
     gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"   ; done
```

-	Created: Thu, 10 Sep 2015 07:50:51 GMT
-	Parent Layer: `16b189cc8ce688f9f1d8f1d837fa0891107450a06c795b1cba8f6c33a4454280`
-	Docker Version: 1.7.1
-	Virtual Size: 39.4 KB (39419 bytes)
-	v2 Blob: `sha256:61f26d33ec3bbef5073f11f8bad058c136159dee3ea81e9f942337e2a919d062`
-	v2 Content-Length: 19.9 KB (19854 bytes)
-	v2 Last-Modified: Fri, 11 Sep 2015 04:31:02 GMT

#### `2e45961f9f233ca9913dff96558d65a5096aa0b2e6a34711d3ac51289a40f50d`

```dockerfile
ENV NPM_CONFIG_LOGLEVEL=info
```

-	Created: Thu, 10 Sep 2015 07:50:51 GMT
-	Parent Layer: `6227f463e6e24a6ea3c8eaae40b4b206aeb3d63b6c615c3512cd9706524f0a3e`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `9d71703fc5af6a867b93053bc59ed969aa95962f1583e5c6ada06af40c6ed733`

```dockerfile
ENV IOJS_VERSION=1.8.4
```

-	Created: Thu, 10 Sep 2015 07:50:52 GMT
-	Parent Layer: `2e45961f9f233ca9913dff96558d65a5096aa0b2e6a34711d3ac51289a40f50d`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `e71ccca3ecebb23e5aa7e83701fadc23f9ae39de1acc82bfa13a45b94ace6304`

```dockerfile
RUN curl -SLO "https://iojs.org/dist/v$IOJS_VERSION/iojs-v$IOJS_VERSION-linux-x64.tar.gz"   && curl -SLO "https://iojs.org/dist/v$IOJS_VERSION/SHASUMS256.txt.asc"   && gpg --verify SHASUMS256.txt.asc   && grep " iojs-v$IOJS_VERSION-linux-x64.tar.gz\$" SHASUMS256.txt.asc | sha256sum -c -   && tar -xzf "iojs-v$IOJS_VERSION-linux-x64.tar.gz" -C /usr/local --strip-components=1   && rm "iojs-v$IOJS_VERSION-linux-x64.tar.gz" SHASUMS256.txt.asc
```

-	Created: Thu, 10 Sep 2015 07:50:57 GMT
-	Parent Layer: `9d71703fc5af6a867b93053bc59ed969aa95962f1583e5c6ada06af40c6ed733`
-	Docker Version: 1.7.1
-	Virtual Size: 27.7 MB (27739327 bytes)
-	v2 Blob: `sha256:b9ee50e4201d1e2daec5cb3830428fe5b35b81762cdda5de7ad1409b2d79f28c`
-	v2 Content-Length: 8.9 MB (8858079 bytes)
-	v2 Last-Modified: Fri, 11 Sep 2015 04:30:49 GMT

#### `4a8b49bca7559021391dfdf0c28ede2002c9a5c2aedb9b2db11e35dfb29861d9`

```dockerfile
CMD ["iojs"]
```

-	Created: Thu, 10 Sep 2015 07:50:58 GMT
-	Parent Layer: `e71ccca3ecebb23e5aa7e83701fadc23f9ae39de1acc82bfa13a45b94ace6304`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `f0ed0e53dd58a300300895ddfc11f42ba380b5d892c17c2f66e0d792215f2d9c`

```dockerfile
RUN mkdir -p /usr/src/app
```

-	Created: Thu, 10 Sep 2015 07:51:35 GMT
-	Parent Layer: `4a8b49bca7559021391dfdf0c28ede2002c9a5c2aedb9b2db11e35dfb29861d9`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:2a57f56f1970941ef543d0c536769b7f5d5a4437c8516aaddfe233d137a9c03c`
-	v2 Content-Length: 128.0 B
-	v2 Last-Modified: Fri, 11 Sep 2015 04:37:17 GMT

#### `4f225461d57e7eb76ed2b60c2159de7bcece88bca7591d602d7feb3f2545df58`

```dockerfile
WORKDIR /usr/src/app
```

-	Created: Thu, 10 Sep 2015 07:51:35 GMT
-	Parent Layer: `f0ed0e53dd58a300300895ddfc11f42ba380b5d892c17c2f66e0d792215f2d9c`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `37e20e64a819b56199ccf4a221d7273f45889d38c8b5b2d6e715b80aa73a7fcb`

```dockerfile
ONBUILD COPY package.json /usr/src/app/
```

-	Created: Thu, 10 Sep 2015 07:51:36 GMT
-	Parent Layer: `4f225461d57e7eb76ed2b60c2159de7bcece88bca7591d602d7feb3f2545df58`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `a2fafb149118bcf80021482e76d5d13e00a5ed9fd059b686cbfd191b7f057caa`

```dockerfile
ONBUILD RUN npm install
```

-	Created: Thu, 10 Sep 2015 07:51:36 GMT
-	Parent Layer: `37e20e64a819b56199ccf4a221d7273f45889d38c8b5b2d6e715b80aa73a7fcb`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `04678cd0ead8f9cdb50a1b974487ca581c89e3e41f4a73040f9b5bb4d8c5086a`

```dockerfile
ONBUILD COPY . /usr/src/app
```

-	Created: Thu, 10 Sep 2015 07:51:37 GMT
-	Parent Layer: `a2fafb149118bcf80021482e76d5d13e00a5ed9fd059b686cbfd191b7f057caa`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `b590d3ee658428281816f126207d270c25c9e32509e2fc4f682fba334f3fadec`

```dockerfile
CMD ["npm" "start"]
```

-	Created: Thu, 10 Sep 2015 07:51:37 GMT
-	Parent Layer: `04678cd0ead8f9cdb50a1b974487ca581c89e3e41f4a73040f9b5bb4d8c5086a`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

## `iojs:1-onbuild`

```console
$ docker pull library/iojs@sha256:fcf2f8c61462d0fcbbd1e7a56ae7a2a71645f2fb7bebc45103389c91349f5baa
```

-	Total Virtual Size: 634.3 MB (634263704 bytes)
-	Total v2 Content-Length: 249.6 MB (249647305 bytes)

### Layers (16)

#### `843e2bded49837e4846422f3a82a67be3ccc46c3e636e03d8d946c57564468ba`

```dockerfile
ADD file:c7d957020a6ee3df60f2407c7a383cabcfa67d43f6d5151b241b37034f5bc6e0 in /
```

-	Created: Mon, 07 Sep 2015 23:35:05 GMT
-	Docker Version: 1.7.1
-	Virtual Size: 125.2 MB (125159131 bytes)
-	v2 Blob: `sha256:f8efbffe7b954b520805da80ce0cce94e3834482c384c25c8851db98696e7f70`
-	v2 Content-Length: 51.4 MB (51359708 bytes)
-	v2 Last-Modified: Mon, 07 Sep 2015 23:38:06 GMT

#### `8c00acfb017549e44d28098762c3e6296872a1ca9b90385855f1019d84bb0dac`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Mon, 07 Sep 2015 23:35:07 GMT
-	Parent Layer: `843e2bded49837e4846422f3a82a67be3ccc46c3e636e03d8d946c57564468ba`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `8b49fe88b40b6c09bbe751e9b235d1919e704ae1765a304226047bd0b203b3fe`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 08 Sep 2015 15:27:57 GMT
-	Parent Layer: `8c00acfb017549e44d28098762c3e6296872a1ca9b90385855f1019d84bb0dac`
-	Docker Version: 1.7.1
-	Virtual Size: 44.4 MB (44355688 bytes)
-	v2 Blob: `sha256:d6314f6cfecf4fc37f622f99d2a114af91ec678d29c76983249f23995ef77563`
-	v2 Content-Length: 18.5 MB (18538583 bytes)
-	v2 Last-Modified: Thu, 10 Sep 2015 23:36:48 GMT

#### `20b348f4d5682b697d2f456322c97d916bafb65f6c4436697209ac1ec0f1803f`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 08 Sep 2015 15:29:05 GMT
-	Parent Layer: `8b49fe88b40b6c09bbe751e9b235d1919e704ae1765a304226047bd0b203b3fe`
-	Docker Version: 1.7.1
-	Virtual Size: 122.3 MB (122317988 bytes)
-	v2 Blob: `sha256:a6f2dac3eb9c26067c12dafd0c917f591d9881ee84a45f750d7a1d58187adfd8`
-	v2 Content-Length: 42.3 MB (42339522 bytes)
-	v2 Last-Modified: Tue, 08 Sep 2015 15:43:42 GMT

#### `16b189cc8ce688f9f1d8f1d837fa0891107450a06c795b1cba8f6c33a4454280`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		autoconf \
		automake \
		bzip2 \
		file \
		g++ \
		gcc \
		imagemagick \
		libbz2-dev \
		libc6-dev \
		libcurl4-openssl-dev \
		libevent-dev \
		libffi-dev \
		libgeoip-dev \
		libglib2.0-dev \
		libjpeg-dev \
		liblzma-dev \
		libmagickcore-dev \
		libmagickwand-dev \
		libmysqlclient-dev \
		libncurses-dev \
		libpng-dev \
		libpq-dev \
		libreadline-dev \
		libsqlite3-dev \
		libssl-dev \
		libtool \
		libwebp-dev \
		libxml2-dev \
		libxslt-dev \
		libyaml-dev \
		make \
		patch \
		xz-utils \
		zlib1g-dev \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 08 Sep 2015 15:31:25 GMT
-	Parent Layer: `20b348f4d5682b697d2f456322c97d916bafb65f6c4436697209ac1ec0f1803f`
-	Docker Version: 1.7.1
-	Virtual Size: 314.7 MB (314652151 bytes)
-	v2 Blob: `sha256:f4f48828d97bcfe36d5697d8f505088a4369e3d660307576f68ae74031884ca7`
-	v2 Content-Length: 128.5 MB (128531143 bytes)
-	v2 Last-Modified: Tue, 08 Sep 2015 15:45:31 GMT

#### `6227f463e6e24a6ea3c8eaae40b4b206aeb3d63b6c615c3512cd9706524f0a3e`

```dockerfile
RUN set -ex   && for key in\
     9554F04D7259F04124DE6B476D5A82AC7E37093B\
     94AE36675C464D64BAFA68DD7434390BDBE9B9C5\
     0034A06D9D9B0064CE8ADF6BF1747F4AD2306D93\
     FD3A5288F042B6850C66B31F09FE44734EB7990E\
     71DCFD284A79C3B38668286BC97EC7A07EDE3FC1\
     DD8F2338BAE7501E3DD5AC78C273792F7D83545D   ; do\
     gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"   ; done
```

-	Created: Thu, 10 Sep 2015 07:50:51 GMT
-	Parent Layer: `16b189cc8ce688f9f1d8f1d837fa0891107450a06c795b1cba8f6c33a4454280`
-	Docker Version: 1.7.1
-	Virtual Size: 39.4 KB (39419 bytes)
-	v2 Blob: `sha256:61f26d33ec3bbef5073f11f8bad058c136159dee3ea81e9f942337e2a919d062`
-	v2 Content-Length: 19.9 KB (19854 bytes)
-	v2 Last-Modified: Fri, 11 Sep 2015 04:31:02 GMT

#### `2e45961f9f233ca9913dff96558d65a5096aa0b2e6a34711d3ac51289a40f50d`

```dockerfile
ENV NPM_CONFIG_LOGLEVEL=info
```

-	Created: Thu, 10 Sep 2015 07:50:51 GMT
-	Parent Layer: `6227f463e6e24a6ea3c8eaae40b4b206aeb3d63b6c615c3512cd9706524f0a3e`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `9d71703fc5af6a867b93053bc59ed969aa95962f1583e5c6ada06af40c6ed733`

```dockerfile
ENV IOJS_VERSION=1.8.4
```

-	Created: Thu, 10 Sep 2015 07:50:52 GMT
-	Parent Layer: `2e45961f9f233ca9913dff96558d65a5096aa0b2e6a34711d3ac51289a40f50d`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `e71ccca3ecebb23e5aa7e83701fadc23f9ae39de1acc82bfa13a45b94ace6304`

```dockerfile
RUN curl -SLO "https://iojs.org/dist/v$IOJS_VERSION/iojs-v$IOJS_VERSION-linux-x64.tar.gz"   && curl -SLO "https://iojs.org/dist/v$IOJS_VERSION/SHASUMS256.txt.asc"   && gpg --verify SHASUMS256.txt.asc   && grep " iojs-v$IOJS_VERSION-linux-x64.tar.gz\$" SHASUMS256.txt.asc | sha256sum -c -   && tar -xzf "iojs-v$IOJS_VERSION-linux-x64.tar.gz" -C /usr/local --strip-components=1   && rm "iojs-v$IOJS_VERSION-linux-x64.tar.gz" SHASUMS256.txt.asc
```

-	Created: Thu, 10 Sep 2015 07:50:57 GMT
-	Parent Layer: `9d71703fc5af6a867b93053bc59ed969aa95962f1583e5c6ada06af40c6ed733`
-	Docker Version: 1.7.1
-	Virtual Size: 27.7 MB (27739327 bytes)
-	v2 Blob: `sha256:b9ee50e4201d1e2daec5cb3830428fe5b35b81762cdda5de7ad1409b2d79f28c`
-	v2 Content-Length: 8.9 MB (8858079 bytes)
-	v2 Last-Modified: Fri, 11 Sep 2015 04:30:49 GMT

#### `4a8b49bca7559021391dfdf0c28ede2002c9a5c2aedb9b2db11e35dfb29861d9`

```dockerfile
CMD ["iojs"]
```

-	Created: Thu, 10 Sep 2015 07:50:58 GMT
-	Parent Layer: `e71ccca3ecebb23e5aa7e83701fadc23f9ae39de1acc82bfa13a45b94ace6304`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `f0ed0e53dd58a300300895ddfc11f42ba380b5d892c17c2f66e0d792215f2d9c`

```dockerfile
RUN mkdir -p /usr/src/app
```

-	Created: Thu, 10 Sep 2015 07:51:35 GMT
-	Parent Layer: `4a8b49bca7559021391dfdf0c28ede2002c9a5c2aedb9b2db11e35dfb29861d9`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:2a57f56f1970941ef543d0c536769b7f5d5a4437c8516aaddfe233d137a9c03c`
-	v2 Content-Length: 128.0 B
-	v2 Last-Modified: Fri, 11 Sep 2015 04:37:17 GMT

#### `4f225461d57e7eb76ed2b60c2159de7bcece88bca7591d602d7feb3f2545df58`

```dockerfile
WORKDIR /usr/src/app
```

-	Created: Thu, 10 Sep 2015 07:51:35 GMT
-	Parent Layer: `f0ed0e53dd58a300300895ddfc11f42ba380b5d892c17c2f66e0d792215f2d9c`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `37e20e64a819b56199ccf4a221d7273f45889d38c8b5b2d6e715b80aa73a7fcb`

```dockerfile
ONBUILD COPY package.json /usr/src/app/
```

-	Created: Thu, 10 Sep 2015 07:51:36 GMT
-	Parent Layer: `4f225461d57e7eb76ed2b60c2159de7bcece88bca7591d602d7feb3f2545df58`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `a2fafb149118bcf80021482e76d5d13e00a5ed9fd059b686cbfd191b7f057caa`

```dockerfile
ONBUILD RUN npm install
```

-	Created: Thu, 10 Sep 2015 07:51:36 GMT
-	Parent Layer: `37e20e64a819b56199ccf4a221d7273f45889d38c8b5b2d6e715b80aa73a7fcb`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `04678cd0ead8f9cdb50a1b974487ca581c89e3e41f4a73040f9b5bb4d8c5086a`

```dockerfile
ONBUILD COPY . /usr/src/app
```

-	Created: Thu, 10 Sep 2015 07:51:37 GMT
-	Parent Layer: `a2fafb149118bcf80021482e76d5d13e00a5ed9fd059b686cbfd191b7f057caa`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `b590d3ee658428281816f126207d270c25c9e32509e2fc4f682fba334f3fadec`

```dockerfile
CMD ["npm" "start"]
```

-	Created: Thu, 10 Sep 2015 07:51:37 GMT
-	Parent Layer: `04678cd0ead8f9cdb50a1b974487ca581c89e3e41f4a73040f9b5bb4d8c5086a`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

## `iojs:1.8.4-slim`

```console
$ docker pull library/iojs@sha256:fefe97c6075e1c497ca2ad48d1df7a4db6dc4ed3006ea180901e419535984a4a
```

-	Total Virtual Size: 197.3 MB (197293565 bytes)
-	Total v2 Content-Length: 78.8 MB (78776351 bytes)

### Layers (8)

#### `843e2bded49837e4846422f3a82a67be3ccc46c3e636e03d8d946c57564468ba`

```dockerfile
ADD file:c7d957020a6ee3df60f2407c7a383cabcfa67d43f6d5151b241b37034f5bc6e0 in /
```

-	Created: Mon, 07 Sep 2015 23:35:05 GMT
-	Docker Version: 1.7.1
-	Virtual Size: 125.2 MB (125159131 bytes)
-	v2 Blob: `sha256:f8efbffe7b954b520805da80ce0cce94e3834482c384c25c8851db98696e7f70`
-	v2 Content-Length: 51.4 MB (51359708 bytes)
-	v2 Last-Modified: Mon, 07 Sep 2015 23:38:06 GMT

#### `8c00acfb017549e44d28098762c3e6296872a1ca9b90385855f1019d84bb0dac`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Mon, 07 Sep 2015 23:35:07 GMT
-	Parent Layer: `843e2bded49837e4846422f3a82a67be3ccc46c3e636e03d8d946c57564468ba`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `8b49fe88b40b6c09bbe751e9b235d1919e704ae1765a304226047bd0b203b3fe`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 08 Sep 2015 15:27:57 GMT
-	Parent Layer: `8c00acfb017549e44d28098762c3e6296872a1ca9b90385855f1019d84bb0dac`
-	Docker Version: 1.7.1
-	Virtual Size: 44.4 MB (44355688 bytes)
-	v2 Blob: `sha256:d6314f6cfecf4fc37f622f99d2a114af91ec678d29c76983249f23995ef77563`
-	v2 Content-Length: 18.5 MB (18538583 bytes)
-	v2 Last-Modified: Thu, 10 Sep 2015 23:36:48 GMT

#### `1e7917dfdd7dc805caa9fe209ae9df3a07529269f4989570f312e72ff4f339c8`

```dockerfile
RUN set -ex   && for key in\
     9554F04D7259F04124DE6B476D5A82AC7E37093B\
     94AE36675C464D64BAFA68DD7434390BDBE9B9C5\
     0034A06D9D9B0064CE8ADF6BF1747F4AD2306D93\
     FD3A5288F042B6850C66B31F09FE44734EB7990E\
     71DCFD284A79C3B38668286BC97EC7A07EDE3FC1\
     DD8F2338BAE7501E3DD5AC78C273792F7D83545D   ; do\
     gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"   ; done
```

-	Created: Thu, 10 Sep 2015 07:52:24 GMT
-	Parent Layer: `8b49fe88b40b6c09bbe751e9b235d1919e704ae1765a304226047bd0b203b3fe`
-	Docker Version: 1.7.1
-	Virtual Size: 39.4 KB (39419 bytes)
-	v2 Blob: `sha256:20f9453d177242021cc6799c74fa2a47f6687a3144251dcb13909e6e8edd0d96`
-	v2 Content-Length: 19.9 KB (19856 bytes)
-	v2 Last-Modified: Fri, 11 Sep 2015 04:39:29 GMT

#### `a2f363d07640f912e4ce880341f1c4a88ce12edaf9be3668776f45da3ca5c73d`

```dockerfile
ENV NPM_CONFIG_LOGLEVEL=info
```

-	Created: Thu, 10 Sep 2015 07:52:25 GMT
-	Parent Layer: `1e7917dfdd7dc805caa9fe209ae9df3a07529269f4989570f312e72ff4f339c8`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `149f5ebfd6a8b217f6a58329646685df8e696a9ad534b48a504dd1f21d640fcc`

```dockerfile
ENV IOJS_VERSION=1.8.4
```

-	Created: Thu, 10 Sep 2015 07:52:25 GMT
-	Parent Layer: `a2f363d07640f912e4ce880341f1c4a88ce12edaf9be3668776f45da3ca5c73d`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `c6f6fe91c2b5485eaa591e6d8c18be5967b16589c4f2572d2aba74f716684cb9`

```dockerfile
RUN curl -SLO "https://iojs.org/dist/v$IOJS_VERSION/iojs-v$IOJS_VERSION-linux-x64.tar.gz"   && curl -SLO "https://iojs.org/dist/v$IOJS_VERSION/SHASUMS256.txt.asc"   && gpg --verify SHASUMS256.txt.asc   && grep " iojs-v$IOJS_VERSION-linux-x64.tar.gz\$" SHASUMS256.txt.asc | sha256sum -c -   && tar -xzf "iojs-v$IOJS_VERSION-linux-x64.tar.gz" -C /usr/local --strip-components=1   && rm "iojs-v$IOJS_VERSION-linux-x64.tar.gz" SHASUMS256.txt.asc
```

-	Created: Thu, 10 Sep 2015 07:52:29 GMT
-	Parent Layer: `149f5ebfd6a8b217f6a58329646685df8e696a9ad534b48a504dd1f21d640fcc`
-	Docker Version: 1.7.1
-	Virtual Size: 27.7 MB (27739327 bytes)
-	v2 Blob: `sha256:8dcc546b529c982dc34f742a4246d749f4f25281e22c39faa35f0254e1fe50d7`
-	v2 Content-Length: 8.9 MB (8858076 bytes)
-	v2 Last-Modified: Fri, 11 Sep 2015 04:39:15 GMT

#### `2face4b93cc0e8f3fd806290a7200bcdb3013cf2fd9336602838c27400beb789`

```dockerfile
CMD ["iojs"]
```

-	Created: Thu, 10 Sep 2015 07:52:30 GMT
-	Parent Layer: `c6f6fe91c2b5485eaa591e6d8c18be5967b16589c4f2572d2aba74f716684cb9`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

## `iojs:1.8-slim`

```console
$ docker pull library/iojs@sha256:ce4a847f9b39037a51dc8f70d7db53042dfde381242bc1ed78ca3421019664f5
```

-	Total Virtual Size: 197.3 MB (197293565 bytes)
-	Total v2 Content-Length: 78.8 MB (78776351 bytes)

### Layers (8)

#### `843e2bded49837e4846422f3a82a67be3ccc46c3e636e03d8d946c57564468ba`

```dockerfile
ADD file:c7d957020a6ee3df60f2407c7a383cabcfa67d43f6d5151b241b37034f5bc6e0 in /
```

-	Created: Mon, 07 Sep 2015 23:35:05 GMT
-	Docker Version: 1.7.1
-	Virtual Size: 125.2 MB (125159131 bytes)
-	v2 Blob: `sha256:f8efbffe7b954b520805da80ce0cce94e3834482c384c25c8851db98696e7f70`
-	v2 Content-Length: 51.4 MB (51359708 bytes)
-	v2 Last-Modified: Mon, 07 Sep 2015 23:38:06 GMT

#### `8c00acfb017549e44d28098762c3e6296872a1ca9b90385855f1019d84bb0dac`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Mon, 07 Sep 2015 23:35:07 GMT
-	Parent Layer: `843e2bded49837e4846422f3a82a67be3ccc46c3e636e03d8d946c57564468ba`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `8b49fe88b40b6c09bbe751e9b235d1919e704ae1765a304226047bd0b203b3fe`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 08 Sep 2015 15:27:57 GMT
-	Parent Layer: `8c00acfb017549e44d28098762c3e6296872a1ca9b90385855f1019d84bb0dac`
-	Docker Version: 1.7.1
-	Virtual Size: 44.4 MB (44355688 bytes)
-	v2 Blob: `sha256:d6314f6cfecf4fc37f622f99d2a114af91ec678d29c76983249f23995ef77563`
-	v2 Content-Length: 18.5 MB (18538583 bytes)
-	v2 Last-Modified: Thu, 10 Sep 2015 23:36:48 GMT

#### `1e7917dfdd7dc805caa9fe209ae9df3a07529269f4989570f312e72ff4f339c8`

```dockerfile
RUN set -ex   && for key in\
     9554F04D7259F04124DE6B476D5A82AC7E37093B\
     94AE36675C464D64BAFA68DD7434390BDBE9B9C5\
     0034A06D9D9B0064CE8ADF6BF1747F4AD2306D93\
     FD3A5288F042B6850C66B31F09FE44734EB7990E\
     71DCFD284A79C3B38668286BC97EC7A07EDE3FC1\
     DD8F2338BAE7501E3DD5AC78C273792F7D83545D   ; do\
     gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"   ; done
```

-	Created: Thu, 10 Sep 2015 07:52:24 GMT
-	Parent Layer: `8b49fe88b40b6c09bbe751e9b235d1919e704ae1765a304226047bd0b203b3fe`
-	Docker Version: 1.7.1
-	Virtual Size: 39.4 KB (39419 bytes)
-	v2 Blob: `sha256:20f9453d177242021cc6799c74fa2a47f6687a3144251dcb13909e6e8edd0d96`
-	v2 Content-Length: 19.9 KB (19856 bytes)
-	v2 Last-Modified: Fri, 11 Sep 2015 04:39:29 GMT

#### `a2f363d07640f912e4ce880341f1c4a88ce12edaf9be3668776f45da3ca5c73d`

```dockerfile
ENV NPM_CONFIG_LOGLEVEL=info
```

-	Created: Thu, 10 Sep 2015 07:52:25 GMT
-	Parent Layer: `1e7917dfdd7dc805caa9fe209ae9df3a07529269f4989570f312e72ff4f339c8`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `149f5ebfd6a8b217f6a58329646685df8e696a9ad534b48a504dd1f21d640fcc`

```dockerfile
ENV IOJS_VERSION=1.8.4
```

-	Created: Thu, 10 Sep 2015 07:52:25 GMT
-	Parent Layer: `a2f363d07640f912e4ce880341f1c4a88ce12edaf9be3668776f45da3ca5c73d`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `c6f6fe91c2b5485eaa591e6d8c18be5967b16589c4f2572d2aba74f716684cb9`

```dockerfile
RUN curl -SLO "https://iojs.org/dist/v$IOJS_VERSION/iojs-v$IOJS_VERSION-linux-x64.tar.gz"   && curl -SLO "https://iojs.org/dist/v$IOJS_VERSION/SHASUMS256.txt.asc"   && gpg --verify SHASUMS256.txt.asc   && grep " iojs-v$IOJS_VERSION-linux-x64.tar.gz\$" SHASUMS256.txt.asc | sha256sum -c -   && tar -xzf "iojs-v$IOJS_VERSION-linux-x64.tar.gz" -C /usr/local --strip-components=1   && rm "iojs-v$IOJS_VERSION-linux-x64.tar.gz" SHASUMS256.txt.asc
```

-	Created: Thu, 10 Sep 2015 07:52:29 GMT
-	Parent Layer: `149f5ebfd6a8b217f6a58329646685df8e696a9ad534b48a504dd1f21d640fcc`
-	Docker Version: 1.7.1
-	Virtual Size: 27.7 MB (27739327 bytes)
-	v2 Blob: `sha256:8dcc546b529c982dc34f742a4246d749f4f25281e22c39faa35f0254e1fe50d7`
-	v2 Content-Length: 8.9 MB (8858076 bytes)
-	v2 Last-Modified: Fri, 11 Sep 2015 04:39:15 GMT

#### `2face4b93cc0e8f3fd806290a7200bcdb3013cf2fd9336602838c27400beb789`

```dockerfile
CMD ["iojs"]
```

-	Created: Thu, 10 Sep 2015 07:52:30 GMT
-	Parent Layer: `c6f6fe91c2b5485eaa591e6d8c18be5967b16589c4f2572d2aba74f716684cb9`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

## `iojs:1-slim`

```console
$ docker pull library/iojs@sha256:f386629f9c6766e6779fc41a11479e6fcf116937290b52eba02139100c26c131
```

-	Total Virtual Size: 197.3 MB (197293565 bytes)
-	Total v2 Content-Length: 78.8 MB (78776351 bytes)

### Layers (8)

#### `843e2bded49837e4846422f3a82a67be3ccc46c3e636e03d8d946c57564468ba`

```dockerfile
ADD file:c7d957020a6ee3df60f2407c7a383cabcfa67d43f6d5151b241b37034f5bc6e0 in /
```

-	Created: Mon, 07 Sep 2015 23:35:05 GMT
-	Docker Version: 1.7.1
-	Virtual Size: 125.2 MB (125159131 bytes)
-	v2 Blob: `sha256:f8efbffe7b954b520805da80ce0cce94e3834482c384c25c8851db98696e7f70`
-	v2 Content-Length: 51.4 MB (51359708 bytes)
-	v2 Last-Modified: Mon, 07 Sep 2015 23:38:06 GMT

#### `8c00acfb017549e44d28098762c3e6296872a1ca9b90385855f1019d84bb0dac`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Mon, 07 Sep 2015 23:35:07 GMT
-	Parent Layer: `843e2bded49837e4846422f3a82a67be3ccc46c3e636e03d8d946c57564468ba`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `8b49fe88b40b6c09bbe751e9b235d1919e704ae1765a304226047bd0b203b3fe`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 08 Sep 2015 15:27:57 GMT
-	Parent Layer: `8c00acfb017549e44d28098762c3e6296872a1ca9b90385855f1019d84bb0dac`
-	Docker Version: 1.7.1
-	Virtual Size: 44.4 MB (44355688 bytes)
-	v2 Blob: `sha256:d6314f6cfecf4fc37f622f99d2a114af91ec678d29c76983249f23995ef77563`
-	v2 Content-Length: 18.5 MB (18538583 bytes)
-	v2 Last-Modified: Thu, 10 Sep 2015 23:36:48 GMT

#### `1e7917dfdd7dc805caa9fe209ae9df3a07529269f4989570f312e72ff4f339c8`

```dockerfile
RUN set -ex   && for key in\
     9554F04D7259F04124DE6B476D5A82AC7E37093B\
     94AE36675C464D64BAFA68DD7434390BDBE9B9C5\
     0034A06D9D9B0064CE8ADF6BF1747F4AD2306D93\
     FD3A5288F042B6850C66B31F09FE44734EB7990E\
     71DCFD284A79C3B38668286BC97EC7A07EDE3FC1\
     DD8F2338BAE7501E3DD5AC78C273792F7D83545D   ; do\
     gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"   ; done
```

-	Created: Thu, 10 Sep 2015 07:52:24 GMT
-	Parent Layer: `8b49fe88b40b6c09bbe751e9b235d1919e704ae1765a304226047bd0b203b3fe`
-	Docker Version: 1.7.1
-	Virtual Size: 39.4 KB (39419 bytes)
-	v2 Blob: `sha256:20f9453d177242021cc6799c74fa2a47f6687a3144251dcb13909e6e8edd0d96`
-	v2 Content-Length: 19.9 KB (19856 bytes)
-	v2 Last-Modified: Fri, 11 Sep 2015 04:39:29 GMT

#### `a2f363d07640f912e4ce880341f1c4a88ce12edaf9be3668776f45da3ca5c73d`

```dockerfile
ENV NPM_CONFIG_LOGLEVEL=info
```

-	Created: Thu, 10 Sep 2015 07:52:25 GMT
-	Parent Layer: `1e7917dfdd7dc805caa9fe209ae9df3a07529269f4989570f312e72ff4f339c8`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `149f5ebfd6a8b217f6a58329646685df8e696a9ad534b48a504dd1f21d640fcc`

```dockerfile
ENV IOJS_VERSION=1.8.4
```

-	Created: Thu, 10 Sep 2015 07:52:25 GMT
-	Parent Layer: `a2f363d07640f912e4ce880341f1c4a88ce12edaf9be3668776f45da3ca5c73d`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `c6f6fe91c2b5485eaa591e6d8c18be5967b16589c4f2572d2aba74f716684cb9`

```dockerfile
RUN curl -SLO "https://iojs.org/dist/v$IOJS_VERSION/iojs-v$IOJS_VERSION-linux-x64.tar.gz"   && curl -SLO "https://iojs.org/dist/v$IOJS_VERSION/SHASUMS256.txt.asc"   && gpg --verify SHASUMS256.txt.asc   && grep " iojs-v$IOJS_VERSION-linux-x64.tar.gz\$" SHASUMS256.txt.asc | sha256sum -c -   && tar -xzf "iojs-v$IOJS_VERSION-linux-x64.tar.gz" -C /usr/local --strip-components=1   && rm "iojs-v$IOJS_VERSION-linux-x64.tar.gz" SHASUMS256.txt.asc
```

-	Created: Thu, 10 Sep 2015 07:52:29 GMT
-	Parent Layer: `149f5ebfd6a8b217f6a58329646685df8e696a9ad534b48a504dd1f21d640fcc`
-	Docker Version: 1.7.1
-	Virtual Size: 27.7 MB (27739327 bytes)
-	v2 Blob: `sha256:8dcc546b529c982dc34f742a4246d749f4f25281e22c39faa35f0254e1fe50d7`
-	v2 Content-Length: 8.9 MB (8858076 bytes)
-	v2 Last-Modified: Fri, 11 Sep 2015 04:39:15 GMT

#### `2face4b93cc0e8f3fd806290a7200bcdb3013cf2fd9336602838c27400beb789`

```dockerfile
CMD ["iojs"]
```

-	Created: Thu, 10 Sep 2015 07:52:30 GMT
-	Parent Layer: `c6f6fe91c2b5485eaa591e6d8c18be5967b16589c4f2572d2aba74f716684cb9`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

## `iojs:2.5.0`

```console
$ docker pull library/iojs@sha256:72c1c26df49c61c24cde00556beb8ee29ecaa98a632e16772de2d61d55367966
```

-	Total Virtual Size: 635.5 MB (635457324 bytes)
-	Total v2 Content-Length: 250.0 MB (250040183 bytes)

### Layers (10)

#### `843e2bded49837e4846422f3a82a67be3ccc46c3e636e03d8d946c57564468ba`

```dockerfile
ADD file:c7d957020a6ee3df60f2407c7a383cabcfa67d43f6d5151b241b37034f5bc6e0 in /
```

-	Created: Mon, 07 Sep 2015 23:35:05 GMT
-	Docker Version: 1.7.1
-	Virtual Size: 125.2 MB (125159131 bytes)
-	v2 Blob: `sha256:f8efbffe7b954b520805da80ce0cce94e3834482c384c25c8851db98696e7f70`
-	v2 Content-Length: 51.4 MB (51359708 bytes)
-	v2 Last-Modified: Mon, 07 Sep 2015 23:38:06 GMT

#### `8c00acfb017549e44d28098762c3e6296872a1ca9b90385855f1019d84bb0dac`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Mon, 07 Sep 2015 23:35:07 GMT
-	Parent Layer: `843e2bded49837e4846422f3a82a67be3ccc46c3e636e03d8d946c57564468ba`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `8b49fe88b40b6c09bbe751e9b235d1919e704ae1765a304226047bd0b203b3fe`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 08 Sep 2015 15:27:57 GMT
-	Parent Layer: `8c00acfb017549e44d28098762c3e6296872a1ca9b90385855f1019d84bb0dac`
-	Docker Version: 1.7.1
-	Virtual Size: 44.4 MB (44355688 bytes)
-	v2 Blob: `sha256:d6314f6cfecf4fc37f622f99d2a114af91ec678d29c76983249f23995ef77563`
-	v2 Content-Length: 18.5 MB (18538583 bytes)
-	v2 Last-Modified: Thu, 10 Sep 2015 23:36:48 GMT

#### `20b348f4d5682b697d2f456322c97d916bafb65f6c4436697209ac1ec0f1803f`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 08 Sep 2015 15:29:05 GMT
-	Parent Layer: `8b49fe88b40b6c09bbe751e9b235d1919e704ae1765a304226047bd0b203b3fe`
-	Docker Version: 1.7.1
-	Virtual Size: 122.3 MB (122317988 bytes)
-	v2 Blob: `sha256:a6f2dac3eb9c26067c12dafd0c917f591d9881ee84a45f750d7a1d58187adfd8`
-	v2 Content-Length: 42.3 MB (42339522 bytes)
-	v2 Last-Modified: Tue, 08 Sep 2015 15:43:42 GMT

#### `16b189cc8ce688f9f1d8f1d837fa0891107450a06c795b1cba8f6c33a4454280`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		autoconf \
		automake \
		bzip2 \
		file \
		g++ \
		gcc \
		imagemagick \
		libbz2-dev \
		libc6-dev \
		libcurl4-openssl-dev \
		libevent-dev \
		libffi-dev \
		libgeoip-dev \
		libglib2.0-dev \
		libjpeg-dev \
		liblzma-dev \
		libmagickcore-dev \
		libmagickwand-dev \
		libmysqlclient-dev \
		libncurses-dev \
		libpng-dev \
		libpq-dev \
		libreadline-dev \
		libsqlite3-dev \
		libssl-dev \
		libtool \
		libwebp-dev \
		libxml2-dev \
		libxslt-dev \
		libyaml-dev \
		make \
		patch \
		xz-utils \
		zlib1g-dev \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 08 Sep 2015 15:31:25 GMT
-	Parent Layer: `20b348f4d5682b697d2f456322c97d916bafb65f6c4436697209ac1ec0f1803f`
-	Docker Version: 1.7.1
-	Virtual Size: 314.7 MB (314652151 bytes)
-	v2 Blob: `sha256:f4f48828d97bcfe36d5697d8f505088a4369e3d660307576f68ae74031884ca7`
-	v2 Content-Length: 128.5 MB (128531143 bytes)
-	v2 Last-Modified: Tue, 08 Sep 2015 15:45:31 GMT

#### `6227f463e6e24a6ea3c8eaae40b4b206aeb3d63b6c615c3512cd9706524f0a3e`

```dockerfile
RUN set -ex   && for key in\
     9554F04D7259F04124DE6B476D5A82AC7E37093B\
     94AE36675C464D64BAFA68DD7434390BDBE9B9C5\
     0034A06D9D9B0064CE8ADF6BF1747F4AD2306D93\
     FD3A5288F042B6850C66B31F09FE44734EB7990E\
     71DCFD284A79C3B38668286BC97EC7A07EDE3FC1\
     DD8F2338BAE7501E3DD5AC78C273792F7D83545D   ; do\
     gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"   ; done
```

-	Created: Thu, 10 Sep 2015 07:50:51 GMT
-	Parent Layer: `16b189cc8ce688f9f1d8f1d837fa0891107450a06c795b1cba8f6c33a4454280`
-	Docker Version: 1.7.1
-	Virtual Size: 39.4 KB (39419 bytes)
-	v2 Blob: `sha256:61f26d33ec3bbef5073f11f8bad058c136159dee3ea81e9f942337e2a919d062`
-	v2 Content-Length: 19.9 KB (19854 bytes)
-	v2 Last-Modified: Fri, 11 Sep 2015 04:31:02 GMT

#### `2e45961f9f233ca9913dff96558d65a5096aa0b2e6a34711d3ac51289a40f50d`

```dockerfile
ENV NPM_CONFIG_LOGLEVEL=info
```

-	Created: Thu, 10 Sep 2015 07:50:51 GMT
-	Parent Layer: `6227f463e6e24a6ea3c8eaae40b4b206aeb3d63b6c615c3512cd9706524f0a3e`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `0d2ef88aff9d5ce7d9eb82781c311c3c78a2db2a866f971080963ede4f8ed07f`

```dockerfile
ENV IOJS_VERSION=2.5.0
```

-	Created: Thu, 10 Sep 2015 07:53:12 GMT
-	Parent Layer: `2e45961f9f233ca9913dff96558d65a5096aa0b2e6a34711d3ac51289a40f50d`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `81a1c07db5ecfb6c2121d2a3dc2b0d6f16cc930001b523c0e2231db2b219799d`

```dockerfile
RUN curl -SLO "https://iojs.org/dist/v$IOJS_VERSION/iojs-v$IOJS_VERSION-linux-x64.tar.gz"   && curl -SLO "https://iojs.org/dist/v$IOJS_VERSION/SHASUMS256.txt.asc"   && gpg --verify SHASUMS256.txt.asc   && grep " iojs-v$IOJS_VERSION-linux-x64.tar.gz\$" SHASUMS256.txt.asc | sha256sum -c -   && tar -xzf "iojs-v$IOJS_VERSION-linux-x64.tar.gz" -C /usr/local --strip-components=1   && rm "iojs-v$IOJS_VERSION-linux-x64.tar.gz" SHASUMS256.txt.asc
```

-	Created: Thu, 10 Sep 2015 07:53:15 GMT
-	Parent Layer: `0d2ef88aff9d5ce7d9eb82781c311c3c78a2db2a866f971080963ede4f8ed07f`
-	Docker Version: 1.7.1
-	Virtual Size: 28.9 MB (28932947 bytes)
-	v2 Blob: `sha256:b86d996ff07ea3616dbb762f5598a137bfea047be884fe8f88d64906d4234405`
-	v2 Content-Length: 9.3 MB (9251245 bytes)
-	v2 Last-Modified: Fri, 11 Sep 2015 04:40:57 GMT

#### `02afbdf878536de7f4c49ebfa9c1efdbb9b2af514f470207d5b7fbe02873a14b`

```dockerfile
CMD ["iojs"]
```

-	Created: Thu, 10 Sep 2015 07:53:16 GMT
-	Parent Layer: `81a1c07db5ecfb6c2121d2a3dc2b0d6f16cc930001b523c0e2231db2b219799d`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

## `iojs:2.5`

```console
$ docker pull library/iojs@sha256:30bcbc0eaf3795979dd6fb4d8d0ff6fd78515d168f714976ca417c18529f36ab
```

-	Total Virtual Size: 635.5 MB (635457324 bytes)
-	Total v2 Content-Length: 250.0 MB (250040183 bytes)

### Layers (10)

#### `843e2bded49837e4846422f3a82a67be3ccc46c3e636e03d8d946c57564468ba`

```dockerfile
ADD file:c7d957020a6ee3df60f2407c7a383cabcfa67d43f6d5151b241b37034f5bc6e0 in /
```

-	Created: Mon, 07 Sep 2015 23:35:05 GMT
-	Docker Version: 1.7.1
-	Virtual Size: 125.2 MB (125159131 bytes)
-	v2 Blob: `sha256:f8efbffe7b954b520805da80ce0cce94e3834482c384c25c8851db98696e7f70`
-	v2 Content-Length: 51.4 MB (51359708 bytes)
-	v2 Last-Modified: Mon, 07 Sep 2015 23:38:06 GMT

#### `8c00acfb017549e44d28098762c3e6296872a1ca9b90385855f1019d84bb0dac`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Mon, 07 Sep 2015 23:35:07 GMT
-	Parent Layer: `843e2bded49837e4846422f3a82a67be3ccc46c3e636e03d8d946c57564468ba`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `8b49fe88b40b6c09bbe751e9b235d1919e704ae1765a304226047bd0b203b3fe`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 08 Sep 2015 15:27:57 GMT
-	Parent Layer: `8c00acfb017549e44d28098762c3e6296872a1ca9b90385855f1019d84bb0dac`
-	Docker Version: 1.7.1
-	Virtual Size: 44.4 MB (44355688 bytes)
-	v2 Blob: `sha256:d6314f6cfecf4fc37f622f99d2a114af91ec678d29c76983249f23995ef77563`
-	v2 Content-Length: 18.5 MB (18538583 bytes)
-	v2 Last-Modified: Thu, 10 Sep 2015 23:36:48 GMT

#### `20b348f4d5682b697d2f456322c97d916bafb65f6c4436697209ac1ec0f1803f`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 08 Sep 2015 15:29:05 GMT
-	Parent Layer: `8b49fe88b40b6c09bbe751e9b235d1919e704ae1765a304226047bd0b203b3fe`
-	Docker Version: 1.7.1
-	Virtual Size: 122.3 MB (122317988 bytes)
-	v2 Blob: `sha256:a6f2dac3eb9c26067c12dafd0c917f591d9881ee84a45f750d7a1d58187adfd8`
-	v2 Content-Length: 42.3 MB (42339522 bytes)
-	v2 Last-Modified: Tue, 08 Sep 2015 15:43:42 GMT

#### `16b189cc8ce688f9f1d8f1d837fa0891107450a06c795b1cba8f6c33a4454280`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		autoconf \
		automake \
		bzip2 \
		file \
		g++ \
		gcc \
		imagemagick \
		libbz2-dev \
		libc6-dev \
		libcurl4-openssl-dev \
		libevent-dev \
		libffi-dev \
		libgeoip-dev \
		libglib2.0-dev \
		libjpeg-dev \
		liblzma-dev \
		libmagickcore-dev \
		libmagickwand-dev \
		libmysqlclient-dev \
		libncurses-dev \
		libpng-dev \
		libpq-dev \
		libreadline-dev \
		libsqlite3-dev \
		libssl-dev \
		libtool \
		libwebp-dev \
		libxml2-dev \
		libxslt-dev \
		libyaml-dev \
		make \
		patch \
		xz-utils \
		zlib1g-dev \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 08 Sep 2015 15:31:25 GMT
-	Parent Layer: `20b348f4d5682b697d2f456322c97d916bafb65f6c4436697209ac1ec0f1803f`
-	Docker Version: 1.7.1
-	Virtual Size: 314.7 MB (314652151 bytes)
-	v2 Blob: `sha256:f4f48828d97bcfe36d5697d8f505088a4369e3d660307576f68ae74031884ca7`
-	v2 Content-Length: 128.5 MB (128531143 bytes)
-	v2 Last-Modified: Tue, 08 Sep 2015 15:45:31 GMT

#### `6227f463e6e24a6ea3c8eaae40b4b206aeb3d63b6c615c3512cd9706524f0a3e`

```dockerfile
RUN set -ex   && for key in\
     9554F04D7259F04124DE6B476D5A82AC7E37093B\
     94AE36675C464D64BAFA68DD7434390BDBE9B9C5\
     0034A06D9D9B0064CE8ADF6BF1747F4AD2306D93\
     FD3A5288F042B6850C66B31F09FE44734EB7990E\
     71DCFD284A79C3B38668286BC97EC7A07EDE3FC1\
     DD8F2338BAE7501E3DD5AC78C273792F7D83545D   ; do\
     gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"   ; done
```

-	Created: Thu, 10 Sep 2015 07:50:51 GMT
-	Parent Layer: `16b189cc8ce688f9f1d8f1d837fa0891107450a06c795b1cba8f6c33a4454280`
-	Docker Version: 1.7.1
-	Virtual Size: 39.4 KB (39419 bytes)
-	v2 Blob: `sha256:61f26d33ec3bbef5073f11f8bad058c136159dee3ea81e9f942337e2a919d062`
-	v2 Content-Length: 19.9 KB (19854 bytes)
-	v2 Last-Modified: Fri, 11 Sep 2015 04:31:02 GMT

#### `2e45961f9f233ca9913dff96558d65a5096aa0b2e6a34711d3ac51289a40f50d`

```dockerfile
ENV NPM_CONFIG_LOGLEVEL=info
```

-	Created: Thu, 10 Sep 2015 07:50:51 GMT
-	Parent Layer: `6227f463e6e24a6ea3c8eaae40b4b206aeb3d63b6c615c3512cd9706524f0a3e`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `0d2ef88aff9d5ce7d9eb82781c311c3c78a2db2a866f971080963ede4f8ed07f`

```dockerfile
ENV IOJS_VERSION=2.5.0
```

-	Created: Thu, 10 Sep 2015 07:53:12 GMT
-	Parent Layer: `2e45961f9f233ca9913dff96558d65a5096aa0b2e6a34711d3ac51289a40f50d`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `81a1c07db5ecfb6c2121d2a3dc2b0d6f16cc930001b523c0e2231db2b219799d`

```dockerfile
RUN curl -SLO "https://iojs.org/dist/v$IOJS_VERSION/iojs-v$IOJS_VERSION-linux-x64.tar.gz"   && curl -SLO "https://iojs.org/dist/v$IOJS_VERSION/SHASUMS256.txt.asc"   && gpg --verify SHASUMS256.txt.asc   && grep " iojs-v$IOJS_VERSION-linux-x64.tar.gz\$" SHASUMS256.txt.asc | sha256sum -c -   && tar -xzf "iojs-v$IOJS_VERSION-linux-x64.tar.gz" -C /usr/local --strip-components=1   && rm "iojs-v$IOJS_VERSION-linux-x64.tar.gz" SHASUMS256.txt.asc
```

-	Created: Thu, 10 Sep 2015 07:53:15 GMT
-	Parent Layer: `0d2ef88aff9d5ce7d9eb82781c311c3c78a2db2a866f971080963ede4f8ed07f`
-	Docker Version: 1.7.1
-	Virtual Size: 28.9 MB (28932947 bytes)
-	v2 Blob: `sha256:b86d996ff07ea3616dbb762f5598a137bfea047be884fe8f88d64906d4234405`
-	v2 Content-Length: 9.3 MB (9251245 bytes)
-	v2 Last-Modified: Fri, 11 Sep 2015 04:40:57 GMT

#### `02afbdf878536de7f4c49ebfa9c1efdbb9b2af514f470207d5b7fbe02873a14b`

```dockerfile
CMD ["iojs"]
```

-	Created: Thu, 10 Sep 2015 07:53:16 GMT
-	Parent Layer: `81a1c07db5ecfb6c2121d2a3dc2b0d6f16cc930001b523c0e2231db2b219799d`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

## `iojs:2`

```console
$ docker pull library/iojs@sha256:e04538f850fc6758cf5de60d9f9e40503d540cfcdc255eb5431fa43e78d684c4
```

-	Total Virtual Size: 635.5 MB (635457324 bytes)
-	Total v2 Content-Length: 250.0 MB (250040183 bytes)

### Layers (10)

#### `843e2bded49837e4846422f3a82a67be3ccc46c3e636e03d8d946c57564468ba`

```dockerfile
ADD file:c7d957020a6ee3df60f2407c7a383cabcfa67d43f6d5151b241b37034f5bc6e0 in /
```

-	Created: Mon, 07 Sep 2015 23:35:05 GMT
-	Docker Version: 1.7.1
-	Virtual Size: 125.2 MB (125159131 bytes)
-	v2 Blob: `sha256:f8efbffe7b954b520805da80ce0cce94e3834482c384c25c8851db98696e7f70`
-	v2 Content-Length: 51.4 MB (51359708 bytes)
-	v2 Last-Modified: Mon, 07 Sep 2015 23:38:06 GMT

#### `8c00acfb017549e44d28098762c3e6296872a1ca9b90385855f1019d84bb0dac`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Mon, 07 Sep 2015 23:35:07 GMT
-	Parent Layer: `843e2bded49837e4846422f3a82a67be3ccc46c3e636e03d8d946c57564468ba`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `8b49fe88b40b6c09bbe751e9b235d1919e704ae1765a304226047bd0b203b3fe`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 08 Sep 2015 15:27:57 GMT
-	Parent Layer: `8c00acfb017549e44d28098762c3e6296872a1ca9b90385855f1019d84bb0dac`
-	Docker Version: 1.7.1
-	Virtual Size: 44.4 MB (44355688 bytes)
-	v2 Blob: `sha256:d6314f6cfecf4fc37f622f99d2a114af91ec678d29c76983249f23995ef77563`
-	v2 Content-Length: 18.5 MB (18538583 bytes)
-	v2 Last-Modified: Thu, 10 Sep 2015 23:36:48 GMT

#### `20b348f4d5682b697d2f456322c97d916bafb65f6c4436697209ac1ec0f1803f`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 08 Sep 2015 15:29:05 GMT
-	Parent Layer: `8b49fe88b40b6c09bbe751e9b235d1919e704ae1765a304226047bd0b203b3fe`
-	Docker Version: 1.7.1
-	Virtual Size: 122.3 MB (122317988 bytes)
-	v2 Blob: `sha256:a6f2dac3eb9c26067c12dafd0c917f591d9881ee84a45f750d7a1d58187adfd8`
-	v2 Content-Length: 42.3 MB (42339522 bytes)
-	v2 Last-Modified: Tue, 08 Sep 2015 15:43:42 GMT

#### `16b189cc8ce688f9f1d8f1d837fa0891107450a06c795b1cba8f6c33a4454280`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		autoconf \
		automake \
		bzip2 \
		file \
		g++ \
		gcc \
		imagemagick \
		libbz2-dev \
		libc6-dev \
		libcurl4-openssl-dev \
		libevent-dev \
		libffi-dev \
		libgeoip-dev \
		libglib2.0-dev \
		libjpeg-dev \
		liblzma-dev \
		libmagickcore-dev \
		libmagickwand-dev \
		libmysqlclient-dev \
		libncurses-dev \
		libpng-dev \
		libpq-dev \
		libreadline-dev \
		libsqlite3-dev \
		libssl-dev \
		libtool \
		libwebp-dev \
		libxml2-dev \
		libxslt-dev \
		libyaml-dev \
		make \
		patch \
		xz-utils \
		zlib1g-dev \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 08 Sep 2015 15:31:25 GMT
-	Parent Layer: `20b348f4d5682b697d2f456322c97d916bafb65f6c4436697209ac1ec0f1803f`
-	Docker Version: 1.7.1
-	Virtual Size: 314.7 MB (314652151 bytes)
-	v2 Blob: `sha256:f4f48828d97bcfe36d5697d8f505088a4369e3d660307576f68ae74031884ca7`
-	v2 Content-Length: 128.5 MB (128531143 bytes)
-	v2 Last-Modified: Tue, 08 Sep 2015 15:45:31 GMT

#### `6227f463e6e24a6ea3c8eaae40b4b206aeb3d63b6c615c3512cd9706524f0a3e`

```dockerfile
RUN set -ex   && for key in\
     9554F04D7259F04124DE6B476D5A82AC7E37093B\
     94AE36675C464D64BAFA68DD7434390BDBE9B9C5\
     0034A06D9D9B0064CE8ADF6BF1747F4AD2306D93\
     FD3A5288F042B6850C66B31F09FE44734EB7990E\
     71DCFD284A79C3B38668286BC97EC7A07EDE3FC1\
     DD8F2338BAE7501E3DD5AC78C273792F7D83545D   ; do\
     gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"   ; done
```

-	Created: Thu, 10 Sep 2015 07:50:51 GMT
-	Parent Layer: `16b189cc8ce688f9f1d8f1d837fa0891107450a06c795b1cba8f6c33a4454280`
-	Docker Version: 1.7.1
-	Virtual Size: 39.4 KB (39419 bytes)
-	v2 Blob: `sha256:61f26d33ec3bbef5073f11f8bad058c136159dee3ea81e9f942337e2a919d062`
-	v2 Content-Length: 19.9 KB (19854 bytes)
-	v2 Last-Modified: Fri, 11 Sep 2015 04:31:02 GMT

#### `2e45961f9f233ca9913dff96558d65a5096aa0b2e6a34711d3ac51289a40f50d`

```dockerfile
ENV NPM_CONFIG_LOGLEVEL=info
```

-	Created: Thu, 10 Sep 2015 07:50:51 GMT
-	Parent Layer: `6227f463e6e24a6ea3c8eaae40b4b206aeb3d63b6c615c3512cd9706524f0a3e`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `0d2ef88aff9d5ce7d9eb82781c311c3c78a2db2a866f971080963ede4f8ed07f`

```dockerfile
ENV IOJS_VERSION=2.5.0
```

-	Created: Thu, 10 Sep 2015 07:53:12 GMT
-	Parent Layer: `2e45961f9f233ca9913dff96558d65a5096aa0b2e6a34711d3ac51289a40f50d`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `81a1c07db5ecfb6c2121d2a3dc2b0d6f16cc930001b523c0e2231db2b219799d`

```dockerfile
RUN curl -SLO "https://iojs.org/dist/v$IOJS_VERSION/iojs-v$IOJS_VERSION-linux-x64.tar.gz"   && curl -SLO "https://iojs.org/dist/v$IOJS_VERSION/SHASUMS256.txt.asc"   && gpg --verify SHASUMS256.txt.asc   && grep " iojs-v$IOJS_VERSION-linux-x64.tar.gz\$" SHASUMS256.txt.asc | sha256sum -c -   && tar -xzf "iojs-v$IOJS_VERSION-linux-x64.tar.gz" -C /usr/local --strip-components=1   && rm "iojs-v$IOJS_VERSION-linux-x64.tar.gz" SHASUMS256.txt.asc
```

-	Created: Thu, 10 Sep 2015 07:53:15 GMT
-	Parent Layer: `0d2ef88aff9d5ce7d9eb82781c311c3c78a2db2a866f971080963ede4f8ed07f`
-	Docker Version: 1.7.1
-	Virtual Size: 28.9 MB (28932947 bytes)
-	v2 Blob: `sha256:b86d996ff07ea3616dbb762f5598a137bfea047be884fe8f88d64906d4234405`
-	v2 Content-Length: 9.3 MB (9251245 bytes)
-	v2 Last-Modified: Fri, 11 Sep 2015 04:40:57 GMT

#### `02afbdf878536de7f4c49ebfa9c1efdbb9b2af514f470207d5b7fbe02873a14b`

```dockerfile
CMD ["iojs"]
```

-	Created: Thu, 10 Sep 2015 07:53:16 GMT
-	Parent Layer: `81a1c07db5ecfb6c2121d2a3dc2b0d6f16cc930001b523c0e2231db2b219799d`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

## `iojs:2.5.0-onbuild`

```console
$ docker pull library/iojs@sha256:262754c1fd11193bdeaa899ee799175d689342d5f5d6749fcf9fae58c8b062b5
```

-	Total Virtual Size: 635.5 MB (635457324 bytes)
-	Total v2 Content-Length: 250.0 MB (250040470 bytes)

### Layers (16)

#### `843e2bded49837e4846422f3a82a67be3ccc46c3e636e03d8d946c57564468ba`

```dockerfile
ADD file:c7d957020a6ee3df60f2407c7a383cabcfa67d43f6d5151b241b37034f5bc6e0 in /
```

-	Created: Mon, 07 Sep 2015 23:35:05 GMT
-	Docker Version: 1.7.1
-	Virtual Size: 125.2 MB (125159131 bytes)
-	v2 Blob: `sha256:f8efbffe7b954b520805da80ce0cce94e3834482c384c25c8851db98696e7f70`
-	v2 Content-Length: 51.4 MB (51359708 bytes)
-	v2 Last-Modified: Mon, 07 Sep 2015 23:38:06 GMT

#### `8c00acfb017549e44d28098762c3e6296872a1ca9b90385855f1019d84bb0dac`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Mon, 07 Sep 2015 23:35:07 GMT
-	Parent Layer: `843e2bded49837e4846422f3a82a67be3ccc46c3e636e03d8d946c57564468ba`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `8b49fe88b40b6c09bbe751e9b235d1919e704ae1765a304226047bd0b203b3fe`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 08 Sep 2015 15:27:57 GMT
-	Parent Layer: `8c00acfb017549e44d28098762c3e6296872a1ca9b90385855f1019d84bb0dac`
-	Docker Version: 1.7.1
-	Virtual Size: 44.4 MB (44355688 bytes)
-	v2 Blob: `sha256:d6314f6cfecf4fc37f622f99d2a114af91ec678d29c76983249f23995ef77563`
-	v2 Content-Length: 18.5 MB (18538583 bytes)
-	v2 Last-Modified: Thu, 10 Sep 2015 23:36:48 GMT

#### `20b348f4d5682b697d2f456322c97d916bafb65f6c4436697209ac1ec0f1803f`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 08 Sep 2015 15:29:05 GMT
-	Parent Layer: `8b49fe88b40b6c09bbe751e9b235d1919e704ae1765a304226047bd0b203b3fe`
-	Docker Version: 1.7.1
-	Virtual Size: 122.3 MB (122317988 bytes)
-	v2 Blob: `sha256:a6f2dac3eb9c26067c12dafd0c917f591d9881ee84a45f750d7a1d58187adfd8`
-	v2 Content-Length: 42.3 MB (42339522 bytes)
-	v2 Last-Modified: Tue, 08 Sep 2015 15:43:42 GMT

#### `16b189cc8ce688f9f1d8f1d837fa0891107450a06c795b1cba8f6c33a4454280`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		autoconf \
		automake \
		bzip2 \
		file \
		g++ \
		gcc \
		imagemagick \
		libbz2-dev \
		libc6-dev \
		libcurl4-openssl-dev \
		libevent-dev \
		libffi-dev \
		libgeoip-dev \
		libglib2.0-dev \
		libjpeg-dev \
		liblzma-dev \
		libmagickcore-dev \
		libmagickwand-dev \
		libmysqlclient-dev \
		libncurses-dev \
		libpng-dev \
		libpq-dev \
		libreadline-dev \
		libsqlite3-dev \
		libssl-dev \
		libtool \
		libwebp-dev \
		libxml2-dev \
		libxslt-dev \
		libyaml-dev \
		make \
		patch \
		xz-utils \
		zlib1g-dev \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 08 Sep 2015 15:31:25 GMT
-	Parent Layer: `20b348f4d5682b697d2f456322c97d916bafb65f6c4436697209ac1ec0f1803f`
-	Docker Version: 1.7.1
-	Virtual Size: 314.7 MB (314652151 bytes)
-	v2 Blob: `sha256:f4f48828d97bcfe36d5697d8f505088a4369e3d660307576f68ae74031884ca7`
-	v2 Content-Length: 128.5 MB (128531143 bytes)
-	v2 Last-Modified: Tue, 08 Sep 2015 15:45:31 GMT

#### `6227f463e6e24a6ea3c8eaae40b4b206aeb3d63b6c615c3512cd9706524f0a3e`

```dockerfile
RUN set -ex   && for key in\
     9554F04D7259F04124DE6B476D5A82AC7E37093B\
     94AE36675C464D64BAFA68DD7434390BDBE9B9C5\
     0034A06D9D9B0064CE8ADF6BF1747F4AD2306D93\
     FD3A5288F042B6850C66B31F09FE44734EB7990E\
     71DCFD284A79C3B38668286BC97EC7A07EDE3FC1\
     DD8F2338BAE7501E3DD5AC78C273792F7D83545D   ; do\
     gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"   ; done
```

-	Created: Thu, 10 Sep 2015 07:50:51 GMT
-	Parent Layer: `16b189cc8ce688f9f1d8f1d837fa0891107450a06c795b1cba8f6c33a4454280`
-	Docker Version: 1.7.1
-	Virtual Size: 39.4 KB (39419 bytes)
-	v2 Blob: `sha256:61f26d33ec3bbef5073f11f8bad058c136159dee3ea81e9f942337e2a919d062`
-	v2 Content-Length: 19.9 KB (19854 bytes)
-	v2 Last-Modified: Fri, 11 Sep 2015 04:31:02 GMT

#### `2e45961f9f233ca9913dff96558d65a5096aa0b2e6a34711d3ac51289a40f50d`

```dockerfile
ENV NPM_CONFIG_LOGLEVEL=info
```

-	Created: Thu, 10 Sep 2015 07:50:51 GMT
-	Parent Layer: `6227f463e6e24a6ea3c8eaae40b4b206aeb3d63b6c615c3512cd9706524f0a3e`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `0d2ef88aff9d5ce7d9eb82781c311c3c78a2db2a866f971080963ede4f8ed07f`

```dockerfile
ENV IOJS_VERSION=2.5.0
```

-	Created: Thu, 10 Sep 2015 07:53:12 GMT
-	Parent Layer: `2e45961f9f233ca9913dff96558d65a5096aa0b2e6a34711d3ac51289a40f50d`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `81a1c07db5ecfb6c2121d2a3dc2b0d6f16cc930001b523c0e2231db2b219799d`

```dockerfile
RUN curl -SLO "https://iojs.org/dist/v$IOJS_VERSION/iojs-v$IOJS_VERSION-linux-x64.tar.gz"   && curl -SLO "https://iojs.org/dist/v$IOJS_VERSION/SHASUMS256.txt.asc"   && gpg --verify SHASUMS256.txt.asc   && grep " iojs-v$IOJS_VERSION-linux-x64.tar.gz\$" SHASUMS256.txt.asc | sha256sum -c -   && tar -xzf "iojs-v$IOJS_VERSION-linux-x64.tar.gz" -C /usr/local --strip-components=1   && rm "iojs-v$IOJS_VERSION-linux-x64.tar.gz" SHASUMS256.txt.asc
```

-	Created: Thu, 10 Sep 2015 07:53:15 GMT
-	Parent Layer: `0d2ef88aff9d5ce7d9eb82781c311c3c78a2db2a866f971080963ede4f8ed07f`
-	Docker Version: 1.7.1
-	Virtual Size: 28.9 MB (28932947 bytes)
-	v2 Blob: `sha256:b86d996ff07ea3616dbb762f5598a137bfea047be884fe8f88d64906d4234405`
-	v2 Content-Length: 9.3 MB (9251245 bytes)
-	v2 Last-Modified: Fri, 11 Sep 2015 04:40:57 GMT

#### `02afbdf878536de7f4c49ebfa9c1efdbb9b2af514f470207d5b7fbe02873a14b`

```dockerfile
CMD ["iojs"]
```

-	Created: Thu, 10 Sep 2015 07:53:16 GMT
-	Parent Layer: `81a1c07db5ecfb6c2121d2a3dc2b0d6f16cc930001b523c0e2231db2b219799d`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `9560cc7fdd94630c15f23604c9d100452e209854e3f3ff8182940ab231b75824`

```dockerfile
RUN mkdir -p /usr/src/app
```

-	Created: Thu, 10 Sep 2015 07:53:54 GMT
-	Parent Layer: `02afbdf878536de7f4c49ebfa9c1efdbb9b2af514f470207d5b7fbe02873a14b`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:185cb7df2a145f643eb4abb9b7a3cd1f9676527ce8ca64d01825d40a21655276`
-	v2 Content-Length: 127.0 B
-	v2 Last-Modified: Fri, 11 Sep 2015 04:42:40 GMT

#### `f3b5558e54d589c3e2efe19406f6586af7e4dbd0c27cea17be997c394b0cd30f`

```dockerfile
WORKDIR /usr/src/app
```

-	Created: Thu, 10 Sep 2015 07:53:54 GMT
-	Parent Layer: `9560cc7fdd94630c15f23604c9d100452e209854e3f3ff8182940ab231b75824`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `2cc10249693a396aec77b4ad7cdb8479cb5277e2be81e29f00ba3b685a590bce`

```dockerfile
ONBUILD COPY package.json /usr/src/app/
```

-	Created: Thu, 10 Sep 2015 07:53:55 GMT
-	Parent Layer: `f3b5558e54d589c3e2efe19406f6586af7e4dbd0c27cea17be997c394b0cd30f`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `2d63ce6e1e701bc30186c87a6152a61e88cabd9ac38a8efb86ba131601f80179`

```dockerfile
ONBUILD RUN npm install
```

-	Created: Thu, 10 Sep 2015 07:53:55 GMT
-	Parent Layer: `2cc10249693a396aec77b4ad7cdb8479cb5277e2be81e29f00ba3b685a590bce`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `e0b622a2a1b54f6f2c226e92a4ab8f7ae5d8e9e4cf02c11aaa0dfd3027cc475f`

```dockerfile
ONBUILD COPY . /usr/src/app
```

-	Created: Thu, 10 Sep 2015 07:53:55 GMT
-	Parent Layer: `2d63ce6e1e701bc30186c87a6152a61e88cabd9ac38a8efb86ba131601f80179`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `1fa04753e5c044c977b4454ea301e81e7b0c9030f117ea70f6e6bea25a176877`

```dockerfile
CMD ["npm" "start"]
```

-	Created: Thu, 10 Sep 2015 07:53:56 GMT
-	Parent Layer: `e0b622a2a1b54f6f2c226e92a4ab8f7ae5d8e9e4cf02c11aaa0dfd3027cc475f`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

## `iojs:2.5-onbuild`

```console
$ docker pull library/iojs@sha256:0635177e0534f109df2e1acc651eb0d6d92b742fae9c5db7d244ce747dc582f8
```

-	Total Virtual Size: 635.5 MB (635457324 bytes)
-	Total v2 Content-Length: 250.0 MB (250040470 bytes)

### Layers (16)

#### `843e2bded49837e4846422f3a82a67be3ccc46c3e636e03d8d946c57564468ba`

```dockerfile
ADD file:c7d957020a6ee3df60f2407c7a383cabcfa67d43f6d5151b241b37034f5bc6e0 in /
```

-	Created: Mon, 07 Sep 2015 23:35:05 GMT
-	Docker Version: 1.7.1
-	Virtual Size: 125.2 MB (125159131 bytes)
-	v2 Blob: `sha256:f8efbffe7b954b520805da80ce0cce94e3834482c384c25c8851db98696e7f70`
-	v2 Content-Length: 51.4 MB (51359708 bytes)
-	v2 Last-Modified: Mon, 07 Sep 2015 23:38:06 GMT

#### `8c00acfb017549e44d28098762c3e6296872a1ca9b90385855f1019d84bb0dac`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Mon, 07 Sep 2015 23:35:07 GMT
-	Parent Layer: `843e2bded49837e4846422f3a82a67be3ccc46c3e636e03d8d946c57564468ba`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `8b49fe88b40b6c09bbe751e9b235d1919e704ae1765a304226047bd0b203b3fe`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 08 Sep 2015 15:27:57 GMT
-	Parent Layer: `8c00acfb017549e44d28098762c3e6296872a1ca9b90385855f1019d84bb0dac`
-	Docker Version: 1.7.1
-	Virtual Size: 44.4 MB (44355688 bytes)
-	v2 Blob: `sha256:d6314f6cfecf4fc37f622f99d2a114af91ec678d29c76983249f23995ef77563`
-	v2 Content-Length: 18.5 MB (18538583 bytes)
-	v2 Last-Modified: Thu, 10 Sep 2015 23:36:48 GMT

#### `20b348f4d5682b697d2f456322c97d916bafb65f6c4436697209ac1ec0f1803f`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 08 Sep 2015 15:29:05 GMT
-	Parent Layer: `8b49fe88b40b6c09bbe751e9b235d1919e704ae1765a304226047bd0b203b3fe`
-	Docker Version: 1.7.1
-	Virtual Size: 122.3 MB (122317988 bytes)
-	v2 Blob: `sha256:a6f2dac3eb9c26067c12dafd0c917f591d9881ee84a45f750d7a1d58187adfd8`
-	v2 Content-Length: 42.3 MB (42339522 bytes)
-	v2 Last-Modified: Tue, 08 Sep 2015 15:43:42 GMT

#### `16b189cc8ce688f9f1d8f1d837fa0891107450a06c795b1cba8f6c33a4454280`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		autoconf \
		automake \
		bzip2 \
		file \
		g++ \
		gcc \
		imagemagick \
		libbz2-dev \
		libc6-dev \
		libcurl4-openssl-dev \
		libevent-dev \
		libffi-dev \
		libgeoip-dev \
		libglib2.0-dev \
		libjpeg-dev \
		liblzma-dev \
		libmagickcore-dev \
		libmagickwand-dev \
		libmysqlclient-dev \
		libncurses-dev \
		libpng-dev \
		libpq-dev \
		libreadline-dev \
		libsqlite3-dev \
		libssl-dev \
		libtool \
		libwebp-dev \
		libxml2-dev \
		libxslt-dev \
		libyaml-dev \
		make \
		patch \
		xz-utils \
		zlib1g-dev \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 08 Sep 2015 15:31:25 GMT
-	Parent Layer: `20b348f4d5682b697d2f456322c97d916bafb65f6c4436697209ac1ec0f1803f`
-	Docker Version: 1.7.1
-	Virtual Size: 314.7 MB (314652151 bytes)
-	v2 Blob: `sha256:f4f48828d97bcfe36d5697d8f505088a4369e3d660307576f68ae74031884ca7`
-	v2 Content-Length: 128.5 MB (128531143 bytes)
-	v2 Last-Modified: Tue, 08 Sep 2015 15:45:31 GMT

#### `6227f463e6e24a6ea3c8eaae40b4b206aeb3d63b6c615c3512cd9706524f0a3e`

```dockerfile
RUN set -ex   && for key in\
     9554F04D7259F04124DE6B476D5A82AC7E37093B\
     94AE36675C464D64BAFA68DD7434390BDBE9B9C5\
     0034A06D9D9B0064CE8ADF6BF1747F4AD2306D93\
     FD3A5288F042B6850C66B31F09FE44734EB7990E\
     71DCFD284A79C3B38668286BC97EC7A07EDE3FC1\
     DD8F2338BAE7501E3DD5AC78C273792F7D83545D   ; do\
     gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"   ; done
```

-	Created: Thu, 10 Sep 2015 07:50:51 GMT
-	Parent Layer: `16b189cc8ce688f9f1d8f1d837fa0891107450a06c795b1cba8f6c33a4454280`
-	Docker Version: 1.7.1
-	Virtual Size: 39.4 KB (39419 bytes)
-	v2 Blob: `sha256:61f26d33ec3bbef5073f11f8bad058c136159dee3ea81e9f942337e2a919d062`
-	v2 Content-Length: 19.9 KB (19854 bytes)
-	v2 Last-Modified: Fri, 11 Sep 2015 04:31:02 GMT

#### `2e45961f9f233ca9913dff96558d65a5096aa0b2e6a34711d3ac51289a40f50d`

```dockerfile
ENV NPM_CONFIG_LOGLEVEL=info
```

-	Created: Thu, 10 Sep 2015 07:50:51 GMT
-	Parent Layer: `6227f463e6e24a6ea3c8eaae40b4b206aeb3d63b6c615c3512cd9706524f0a3e`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `0d2ef88aff9d5ce7d9eb82781c311c3c78a2db2a866f971080963ede4f8ed07f`

```dockerfile
ENV IOJS_VERSION=2.5.0
```

-	Created: Thu, 10 Sep 2015 07:53:12 GMT
-	Parent Layer: `2e45961f9f233ca9913dff96558d65a5096aa0b2e6a34711d3ac51289a40f50d`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `81a1c07db5ecfb6c2121d2a3dc2b0d6f16cc930001b523c0e2231db2b219799d`

```dockerfile
RUN curl -SLO "https://iojs.org/dist/v$IOJS_VERSION/iojs-v$IOJS_VERSION-linux-x64.tar.gz"   && curl -SLO "https://iojs.org/dist/v$IOJS_VERSION/SHASUMS256.txt.asc"   && gpg --verify SHASUMS256.txt.asc   && grep " iojs-v$IOJS_VERSION-linux-x64.tar.gz\$" SHASUMS256.txt.asc | sha256sum -c -   && tar -xzf "iojs-v$IOJS_VERSION-linux-x64.tar.gz" -C /usr/local --strip-components=1   && rm "iojs-v$IOJS_VERSION-linux-x64.tar.gz" SHASUMS256.txt.asc
```

-	Created: Thu, 10 Sep 2015 07:53:15 GMT
-	Parent Layer: `0d2ef88aff9d5ce7d9eb82781c311c3c78a2db2a866f971080963ede4f8ed07f`
-	Docker Version: 1.7.1
-	Virtual Size: 28.9 MB (28932947 bytes)
-	v2 Blob: `sha256:b86d996ff07ea3616dbb762f5598a137bfea047be884fe8f88d64906d4234405`
-	v2 Content-Length: 9.3 MB (9251245 bytes)
-	v2 Last-Modified: Fri, 11 Sep 2015 04:40:57 GMT

#### `02afbdf878536de7f4c49ebfa9c1efdbb9b2af514f470207d5b7fbe02873a14b`

```dockerfile
CMD ["iojs"]
```

-	Created: Thu, 10 Sep 2015 07:53:16 GMT
-	Parent Layer: `81a1c07db5ecfb6c2121d2a3dc2b0d6f16cc930001b523c0e2231db2b219799d`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `9560cc7fdd94630c15f23604c9d100452e209854e3f3ff8182940ab231b75824`

```dockerfile
RUN mkdir -p /usr/src/app
```

-	Created: Thu, 10 Sep 2015 07:53:54 GMT
-	Parent Layer: `02afbdf878536de7f4c49ebfa9c1efdbb9b2af514f470207d5b7fbe02873a14b`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:185cb7df2a145f643eb4abb9b7a3cd1f9676527ce8ca64d01825d40a21655276`
-	v2 Content-Length: 127.0 B
-	v2 Last-Modified: Fri, 11 Sep 2015 04:42:40 GMT

#### `f3b5558e54d589c3e2efe19406f6586af7e4dbd0c27cea17be997c394b0cd30f`

```dockerfile
WORKDIR /usr/src/app
```

-	Created: Thu, 10 Sep 2015 07:53:54 GMT
-	Parent Layer: `9560cc7fdd94630c15f23604c9d100452e209854e3f3ff8182940ab231b75824`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `2cc10249693a396aec77b4ad7cdb8479cb5277e2be81e29f00ba3b685a590bce`

```dockerfile
ONBUILD COPY package.json /usr/src/app/
```

-	Created: Thu, 10 Sep 2015 07:53:55 GMT
-	Parent Layer: `f3b5558e54d589c3e2efe19406f6586af7e4dbd0c27cea17be997c394b0cd30f`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `2d63ce6e1e701bc30186c87a6152a61e88cabd9ac38a8efb86ba131601f80179`

```dockerfile
ONBUILD RUN npm install
```

-	Created: Thu, 10 Sep 2015 07:53:55 GMT
-	Parent Layer: `2cc10249693a396aec77b4ad7cdb8479cb5277e2be81e29f00ba3b685a590bce`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `e0b622a2a1b54f6f2c226e92a4ab8f7ae5d8e9e4cf02c11aaa0dfd3027cc475f`

```dockerfile
ONBUILD COPY . /usr/src/app
```

-	Created: Thu, 10 Sep 2015 07:53:55 GMT
-	Parent Layer: `2d63ce6e1e701bc30186c87a6152a61e88cabd9ac38a8efb86ba131601f80179`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `1fa04753e5c044c977b4454ea301e81e7b0c9030f117ea70f6e6bea25a176877`

```dockerfile
CMD ["npm" "start"]
```

-	Created: Thu, 10 Sep 2015 07:53:56 GMT
-	Parent Layer: `e0b622a2a1b54f6f2c226e92a4ab8f7ae5d8e9e4cf02c11aaa0dfd3027cc475f`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

## `iojs:2-onbuild`

```console
$ docker pull library/iojs@sha256:c0d2aca00d3d886ec2b54b038f9acd569379f37ae6e7c947f6fa3d5807c0cff6
```

-	Total Virtual Size: 635.5 MB (635457324 bytes)
-	Total v2 Content-Length: 250.0 MB (250040470 bytes)

### Layers (16)

#### `843e2bded49837e4846422f3a82a67be3ccc46c3e636e03d8d946c57564468ba`

```dockerfile
ADD file:c7d957020a6ee3df60f2407c7a383cabcfa67d43f6d5151b241b37034f5bc6e0 in /
```

-	Created: Mon, 07 Sep 2015 23:35:05 GMT
-	Docker Version: 1.7.1
-	Virtual Size: 125.2 MB (125159131 bytes)
-	v2 Blob: `sha256:f8efbffe7b954b520805da80ce0cce94e3834482c384c25c8851db98696e7f70`
-	v2 Content-Length: 51.4 MB (51359708 bytes)
-	v2 Last-Modified: Mon, 07 Sep 2015 23:38:06 GMT

#### `8c00acfb017549e44d28098762c3e6296872a1ca9b90385855f1019d84bb0dac`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Mon, 07 Sep 2015 23:35:07 GMT
-	Parent Layer: `843e2bded49837e4846422f3a82a67be3ccc46c3e636e03d8d946c57564468ba`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `8b49fe88b40b6c09bbe751e9b235d1919e704ae1765a304226047bd0b203b3fe`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 08 Sep 2015 15:27:57 GMT
-	Parent Layer: `8c00acfb017549e44d28098762c3e6296872a1ca9b90385855f1019d84bb0dac`
-	Docker Version: 1.7.1
-	Virtual Size: 44.4 MB (44355688 bytes)
-	v2 Blob: `sha256:d6314f6cfecf4fc37f622f99d2a114af91ec678d29c76983249f23995ef77563`
-	v2 Content-Length: 18.5 MB (18538583 bytes)
-	v2 Last-Modified: Thu, 10 Sep 2015 23:36:48 GMT

#### `20b348f4d5682b697d2f456322c97d916bafb65f6c4436697209ac1ec0f1803f`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 08 Sep 2015 15:29:05 GMT
-	Parent Layer: `8b49fe88b40b6c09bbe751e9b235d1919e704ae1765a304226047bd0b203b3fe`
-	Docker Version: 1.7.1
-	Virtual Size: 122.3 MB (122317988 bytes)
-	v2 Blob: `sha256:a6f2dac3eb9c26067c12dafd0c917f591d9881ee84a45f750d7a1d58187adfd8`
-	v2 Content-Length: 42.3 MB (42339522 bytes)
-	v2 Last-Modified: Tue, 08 Sep 2015 15:43:42 GMT

#### `16b189cc8ce688f9f1d8f1d837fa0891107450a06c795b1cba8f6c33a4454280`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		autoconf \
		automake \
		bzip2 \
		file \
		g++ \
		gcc \
		imagemagick \
		libbz2-dev \
		libc6-dev \
		libcurl4-openssl-dev \
		libevent-dev \
		libffi-dev \
		libgeoip-dev \
		libglib2.0-dev \
		libjpeg-dev \
		liblzma-dev \
		libmagickcore-dev \
		libmagickwand-dev \
		libmysqlclient-dev \
		libncurses-dev \
		libpng-dev \
		libpq-dev \
		libreadline-dev \
		libsqlite3-dev \
		libssl-dev \
		libtool \
		libwebp-dev \
		libxml2-dev \
		libxslt-dev \
		libyaml-dev \
		make \
		patch \
		xz-utils \
		zlib1g-dev \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 08 Sep 2015 15:31:25 GMT
-	Parent Layer: `20b348f4d5682b697d2f456322c97d916bafb65f6c4436697209ac1ec0f1803f`
-	Docker Version: 1.7.1
-	Virtual Size: 314.7 MB (314652151 bytes)
-	v2 Blob: `sha256:f4f48828d97bcfe36d5697d8f505088a4369e3d660307576f68ae74031884ca7`
-	v2 Content-Length: 128.5 MB (128531143 bytes)
-	v2 Last-Modified: Tue, 08 Sep 2015 15:45:31 GMT

#### `6227f463e6e24a6ea3c8eaae40b4b206aeb3d63b6c615c3512cd9706524f0a3e`

```dockerfile
RUN set -ex   && for key in\
     9554F04D7259F04124DE6B476D5A82AC7E37093B\
     94AE36675C464D64BAFA68DD7434390BDBE9B9C5\
     0034A06D9D9B0064CE8ADF6BF1747F4AD2306D93\
     FD3A5288F042B6850C66B31F09FE44734EB7990E\
     71DCFD284A79C3B38668286BC97EC7A07EDE3FC1\
     DD8F2338BAE7501E3DD5AC78C273792F7D83545D   ; do\
     gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"   ; done
```

-	Created: Thu, 10 Sep 2015 07:50:51 GMT
-	Parent Layer: `16b189cc8ce688f9f1d8f1d837fa0891107450a06c795b1cba8f6c33a4454280`
-	Docker Version: 1.7.1
-	Virtual Size: 39.4 KB (39419 bytes)
-	v2 Blob: `sha256:61f26d33ec3bbef5073f11f8bad058c136159dee3ea81e9f942337e2a919d062`
-	v2 Content-Length: 19.9 KB (19854 bytes)
-	v2 Last-Modified: Fri, 11 Sep 2015 04:31:02 GMT

#### `2e45961f9f233ca9913dff96558d65a5096aa0b2e6a34711d3ac51289a40f50d`

```dockerfile
ENV NPM_CONFIG_LOGLEVEL=info
```

-	Created: Thu, 10 Sep 2015 07:50:51 GMT
-	Parent Layer: `6227f463e6e24a6ea3c8eaae40b4b206aeb3d63b6c615c3512cd9706524f0a3e`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `0d2ef88aff9d5ce7d9eb82781c311c3c78a2db2a866f971080963ede4f8ed07f`

```dockerfile
ENV IOJS_VERSION=2.5.0
```

-	Created: Thu, 10 Sep 2015 07:53:12 GMT
-	Parent Layer: `2e45961f9f233ca9913dff96558d65a5096aa0b2e6a34711d3ac51289a40f50d`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `81a1c07db5ecfb6c2121d2a3dc2b0d6f16cc930001b523c0e2231db2b219799d`

```dockerfile
RUN curl -SLO "https://iojs.org/dist/v$IOJS_VERSION/iojs-v$IOJS_VERSION-linux-x64.tar.gz"   && curl -SLO "https://iojs.org/dist/v$IOJS_VERSION/SHASUMS256.txt.asc"   && gpg --verify SHASUMS256.txt.asc   && grep " iojs-v$IOJS_VERSION-linux-x64.tar.gz\$" SHASUMS256.txt.asc | sha256sum -c -   && tar -xzf "iojs-v$IOJS_VERSION-linux-x64.tar.gz" -C /usr/local --strip-components=1   && rm "iojs-v$IOJS_VERSION-linux-x64.tar.gz" SHASUMS256.txt.asc
```

-	Created: Thu, 10 Sep 2015 07:53:15 GMT
-	Parent Layer: `0d2ef88aff9d5ce7d9eb82781c311c3c78a2db2a866f971080963ede4f8ed07f`
-	Docker Version: 1.7.1
-	Virtual Size: 28.9 MB (28932947 bytes)
-	v2 Blob: `sha256:b86d996ff07ea3616dbb762f5598a137bfea047be884fe8f88d64906d4234405`
-	v2 Content-Length: 9.3 MB (9251245 bytes)
-	v2 Last-Modified: Fri, 11 Sep 2015 04:40:57 GMT

#### `02afbdf878536de7f4c49ebfa9c1efdbb9b2af514f470207d5b7fbe02873a14b`

```dockerfile
CMD ["iojs"]
```

-	Created: Thu, 10 Sep 2015 07:53:16 GMT
-	Parent Layer: `81a1c07db5ecfb6c2121d2a3dc2b0d6f16cc930001b523c0e2231db2b219799d`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `9560cc7fdd94630c15f23604c9d100452e209854e3f3ff8182940ab231b75824`

```dockerfile
RUN mkdir -p /usr/src/app
```

-	Created: Thu, 10 Sep 2015 07:53:54 GMT
-	Parent Layer: `02afbdf878536de7f4c49ebfa9c1efdbb9b2af514f470207d5b7fbe02873a14b`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:185cb7df2a145f643eb4abb9b7a3cd1f9676527ce8ca64d01825d40a21655276`
-	v2 Content-Length: 127.0 B
-	v2 Last-Modified: Fri, 11 Sep 2015 04:42:40 GMT

#### `f3b5558e54d589c3e2efe19406f6586af7e4dbd0c27cea17be997c394b0cd30f`

```dockerfile
WORKDIR /usr/src/app
```

-	Created: Thu, 10 Sep 2015 07:53:54 GMT
-	Parent Layer: `9560cc7fdd94630c15f23604c9d100452e209854e3f3ff8182940ab231b75824`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `2cc10249693a396aec77b4ad7cdb8479cb5277e2be81e29f00ba3b685a590bce`

```dockerfile
ONBUILD COPY package.json /usr/src/app/
```

-	Created: Thu, 10 Sep 2015 07:53:55 GMT
-	Parent Layer: `f3b5558e54d589c3e2efe19406f6586af7e4dbd0c27cea17be997c394b0cd30f`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `2d63ce6e1e701bc30186c87a6152a61e88cabd9ac38a8efb86ba131601f80179`

```dockerfile
ONBUILD RUN npm install
```

-	Created: Thu, 10 Sep 2015 07:53:55 GMT
-	Parent Layer: `2cc10249693a396aec77b4ad7cdb8479cb5277e2be81e29f00ba3b685a590bce`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `e0b622a2a1b54f6f2c226e92a4ab8f7ae5d8e9e4cf02c11aaa0dfd3027cc475f`

```dockerfile
ONBUILD COPY . /usr/src/app
```

-	Created: Thu, 10 Sep 2015 07:53:55 GMT
-	Parent Layer: `2d63ce6e1e701bc30186c87a6152a61e88cabd9ac38a8efb86ba131601f80179`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `1fa04753e5c044c977b4454ea301e81e7b0c9030f117ea70f6e6bea25a176877`

```dockerfile
CMD ["npm" "start"]
```

-	Created: Thu, 10 Sep 2015 07:53:56 GMT
-	Parent Layer: `e0b622a2a1b54f6f2c226e92a4ab8f7ae5d8e9e4cf02c11aaa0dfd3027cc475f`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

## `iojs:2.5.0-slim`

```console
$ docker pull library/iojs@sha256:d9d15daf807498c44e7c485605eff75ee99fd6b04540459370cdc7c8501ef704
```

-	Total Virtual Size: 198.5 MB (198487185 bytes)
-	Total v2 Content-Length: 79.2 MB (79169527 bytes)

### Layers (8)

#### `843e2bded49837e4846422f3a82a67be3ccc46c3e636e03d8d946c57564468ba`

```dockerfile
ADD file:c7d957020a6ee3df60f2407c7a383cabcfa67d43f6d5151b241b37034f5bc6e0 in /
```

-	Created: Mon, 07 Sep 2015 23:35:05 GMT
-	Docker Version: 1.7.1
-	Virtual Size: 125.2 MB (125159131 bytes)
-	v2 Blob: `sha256:f8efbffe7b954b520805da80ce0cce94e3834482c384c25c8851db98696e7f70`
-	v2 Content-Length: 51.4 MB (51359708 bytes)
-	v2 Last-Modified: Mon, 07 Sep 2015 23:38:06 GMT

#### `8c00acfb017549e44d28098762c3e6296872a1ca9b90385855f1019d84bb0dac`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Mon, 07 Sep 2015 23:35:07 GMT
-	Parent Layer: `843e2bded49837e4846422f3a82a67be3ccc46c3e636e03d8d946c57564468ba`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `8b49fe88b40b6c09bbe751e9b235d1919e704ae1765a304226047bd0b203b3fe`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 08 Sep 2015 15:27:57 GMT
-	Parent Layer: `8c00acfb017549e44d28098762c3e6296872a1ca9b90385855f1019d84bb0dac`
-	Docker Version: 1.7.1
-	Virtual Size: 44.4 MB (44355688 bytes)
-	v2 Blob: `sha256:d6314f6cfecf4fc37f622f99d2a114af91ec678d29c76983249f23995ef77563`
-	v2 Content-Length: 18.5 MB (18538583 bytes)
-	v2 Last-Modified: Thu, 10 Sep 2015 23:36:48 GMT

#### `1e7917dfdd7dc805caa9fe209ae9df3a07529269f4989570f312e72ff4f339c8`

```dockerfile
RUN set -ex   && for key in\
     9554F04D7259F04124DE6B476D5A82AC7E37093B\
     94AE36675C464D64BAFA68DD7434390BDBE9B9C5\
     0034A06D9D9B0064CE8ADF6BF1747F4AD2306D93\
     FD3A5288F042B6850C66B31F09FE44734EB7990E\
     71DCFD284A79C3B38668286BC97EC7A07EDE3FC1\
     DD8F2338BAE7501E3DD5AC78C273792F7D83545D   ; do\
     gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"   ; done
```

-	Created: Thu, 10 Sep 2015 07:52:24 GMT
-	Parent Layer: `8b49fe88b40b6c09bbe751e9b235d1919e704ae1765a304226047bd0b203b3fe`
-	Docker Version: 1.7.1
-	Virtual Size: 39.4 KB (39419 bytes)
-	v2 Blob: `sha256:20f9453d177242021cc6799c74fa2a47f6687a3144251dcb13909e6e8edd0d96`
-	v2 Content-Length: 19.9 KB (19856 bytes)
-	v2 Last-Modified: Fri, 11 Sep 2015 04:39:29 GMT

#### `a2f363d07640f912e4ce880341f1c4a88ce12edaf9be3668776f45da3ca5c73d`

```dockerfile
ENV NPM_CONFIG_LOGLEVEL=info
```

-	Created: Thu, 10 Sep 2015 07:52:25 GMT
-	Parent Layer: `1e7917dfdd7dc805caa9fe209ae9df3a07529269f4989570f312e72ff4f339c8`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `e7d859a7f819f4146c93c4778eead93a1e4e86e970c41c5ecd6e7cb027556e9c`

```dockerfile
ENV IOJS_VERSION=2.5.0
```

-	Created: Thu, 10 Sep 2015 07:54:44 GMT
-	Parent Layer: `a2f363d07640f912e4ce880341f1c4a88ce12edaf9be3668776f45da3ca5c73d`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `def0c773154a8c78b2ff26fc64c2375ed961aa03a7ef43bac516522a00ad5825`

```dockerfile
RUN curl -SLO "https://iojs.org/dist/v$IOJS_VERSION/iojs-v$IOJS_VERSION-linux-x64.tar.gz"   && curl -SLO "https://iojs.org/dist/v$IOJS_VERSION/SHASUMS256.txt.asc"   && gpg --verify SHASUMS256.txt.asc   && grep " iojs-v$IOJS_VERSION-linux-x64.tar.gz\$" SHASUMS256.txt.asc | sha256sum -c -   && tar -xzf "iojs-v$IOJS_VERSION-linux-x64.tar.gz" -C /usr/local --strip-components=1   && rm "iojs-v$IOJS_VERSION-linux-x64.tar.gz" SHASUMS256.txt.asc
```

-	Created: Thu, 10 Sep 2015 07:54:50 GMT
-	Parent Layer: `e7d859a7f819f4146c93c4778eead93a1e4e86e970c41c5ecd6e7cb027556e9c`
-	Docker Version: 1.7.1
-	Virtual Size: 28.9 MB (28932947 bytes)
-	v2 Blob: `sha256:7a58f7d23f0c1b2b82f101a9476e9f2810848885fa5ce1702c102b961c733a37`
-	v2 Content-Length: 9.3 MB (9251252 bytes)
-	v2 Last-Modified: Fri, 11 Sep 2015 04:44:37 GMT

#### `f1c2420e87fc6a1a4939f3effd2bd3e5e83281c9f2d5a86d9897fcd6ed872da8`

```dockerfile
CMD ["iojs"]
```

-	Created: Thu, 10 Sep 2015 07:54:51 GMT
-	Parent Layer: `def0c773154a8c78b2ff26fc64c2375ed961aa03a7ef43bac516522a00ad5825`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

## `iojs:2.5-slim`

```console
$ docker pull library/iojs@sha256:4b7756dbfe68fb64185d3052cfe7d707c8b7dc32f4b9483d4cf56fa8ad3c180b
```

-	Total Virtual Size: 198.5 MB (198487185 bytes)
-	Total v2 Content-Length: 79.2 MB (79169527 bytes)

### Layers (8)

#### `843e2bded49837e4846422f3a82a67be3ccc46c3e636e03d8d946c57564468ba`

```dockerfile
ADD file:c7d957020a6ee3df60f2407c7a383cabcfa67d43f6d5151b241b37034f5bc6e0 in /
```

-	Created: Mon, 07 Sep 2015 23:35:05 GMT
-	Docker Version: 1.7.1
-	Virtual Size: 125.2 MB (125159131 bytes)
-	v2 Blob: `sha256:f8efbffe7b954b520805da80ce0cce94e3834482c384c25c8851db98696e7f70`
-	v2 Content-Length: 51.4 MB (51359708 bytes)
-	v2 Last-Modified: Mon, 07 Sep 2015 23:38:06 GMT

#### `8c00acfb017549e44d28098762c3e6296872a1ca9b90385855f1019d84bb0dac`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Mon, 07 Sep 2015 23:35:07 GMT
-	Parent Layer: `843e2bded49837e4846422f3a82a67be3ccc46c3e636e03d8d946c57564468ba`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `8b49fe88b40b6c09bbe751e9b235d1919e704ae1765a304226047bd0b203b3fe`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 08 Sep 2015 15:27:57 GMT
-	Parent Layer: `8c00acfb017549e44d28098762c3e6296872a1ca9b90385855f1019d84bb0dac`
-	Docker Version: 1.7.1
-	Virtual Size: 44.4 MB (44355688 bytes)
-	v2 Blob: `sha256:d6314f6cfecf4fc37f622f99d2a114af91ec678d29c76983249f23995ef77563`
-	v2 Content-Length: 18.5 MB (18538583 bytes)
-	v2 Last-Modified: Thu, 10 Sep 2015 23:36:48 GMT

#### `1e7917dfdd7dc805caa9fe209ae9df3a07529269f4989570f312e72ff4f339c8`

```dockerfile
RUN set -ex   && for key in\
     9554F04D7259F04124DE6B476D5A82AC7E37093B\
     94AE36675C464D64BAFA68DD7434390BDBE9B9C5\
     0034A06D9D9B0064CE8ADF6BF1747F4AD2306D93\
     FD3A5288F042B6850C66B31F09FE44734EB7990E\
     71DCFD284A79C3B38668286BC97EC7A07EDE3FC1\
     DD8F2338BAE7501E3DD5AC78C273792F7D83545D   ; do\
     gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"   ; done
```

-	Created: Thu, 10 Sep 2015 07:52:24 GMT
-	Parent Layer: `8b49fe88b40b6c09bbe751e9b235d1919e704ae1765a304226047bd0b203b3fe`
-	Docker Version: 1.7.1
-	Virtual Size: 39.4 KB (39419 bytes)
-	v2 Blob: `sha256:20f9453d177242021cc6799c74fa2a47f6687a3144251dcb13909e6e8edd0d96`
-	v2 Content-Length: 19.9 KB (19856 bytes)
-	v2 Last-Modified: Fri, 11 Sep 2015 04:39:29 GMT

#### `a2f363d07640f912e4ce880341f1c4a88ce12edaf9be3668776f45da3ca5c73d`

```dockerfile
ENV NPM_CONFIG_LOGLEVEL=info
```

-	Created: Thu, 10 Sep 2015 07:52:25 GMT
-	Parent Layer: `1e7917dfdd7dc805caa9fe209ae9df3a07529269f4989570f312e72ff4f339c8`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `e7d859a7f819f4146c93c4778eead93a1e4e86e970c41c5ecd6e7cb027556e9c`

```dockerfile
ENV IOJS_VERSION=2.5.0
```

-	Created: Thu, 10 Sep 2015 07:54:44 GMT
-	Parent Layer: `a2f363d07640f912e4ce880341f1c4a88ce12edaf9be3668776f45da3ca5c73d`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `def0c773154a8c78b2ff26fc64c2375ed961aa03a7ef43bac516522a00ad5825`

```dockerfile
RUN curl -SLO "https://iojs.org/dist/v$IOJS_VERSION/iojs-v$IOJS_VERSION-linux-x64.tar.gz"   && curl -SLO "https://iojs.org/dist/v$IOJS_VERSION/SHASUMS256.txt.asc"   && gpg --verify SHASUMS256.txt.asc   && grep " iojs-v$IOJS_VERSION-linux-x64.tar.gz\$" SHASUMS256.txt.asc | sha256sum -c -   && tar -xzf "iojs-v$IOJS_VERSION-linux-x64.tar.gz" -C /usr/local --strip-components=1   && rm "iojs-v$IOJS_VERSION-linux-x64.tar.gz" SHASUMS256.txt.asc
```

-	Created: Thu, 10 Sep 2015 07:54:50 GMT
-	Parent Layer: `e7d859a7f819f4146c93c4778eead93a1e4e86e970c41c5ecd6e7cb027556e9c`
-	Docker Version: 1.7.1
-	Virtual Size: 28.9 MB (28932947 bytes)
-	v2 Blob: `sha256:7a58f7d23f0c1b2b82f101a9476e9f2810848885fa5ce1702c102b961c733a37`
-	v2 Content-Length: 9.3 MB (9251252 bytes)
-	v2 Last-Modified: Fri, 11 Sep 2015 04:44:37 GMT

#### `f1c2420e87fc6a1a4939f3effd2bd3e5e83281c9f2d5a86d9897fcd6ed872da8`

```dockerfile
CMD ["iojs"]
```

-	Created: Thu, 10 Sep 2015 07:54:51 GMT
-	Parent Layer: `def0c773154a8c78b2ff26fc64c2375ed961aa03a7ef43bac516522a00ad5825`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

## `iojs:2-slim`

```console
$ docker pull library/iojs@sha256:21426d90302c4a886403de4628300c3727c44d51f4ed2ee5c03aea91457bde8f
```

-	Total Virtual Size: 198.5 MB (198487185 bytes)
-	Total v2 Content-Length: 79.2 MB (79169527 bytes)

### Layers (8)

#### `843e2bded49837e4846422f3a82a67be3ccc46c3e636e03d8d946c57564468ba`

```dockerfile
ADD file:c7d957020a6ee3df60f2407c7a383cabcfa67d43f6d5151b241b37034f5bc6e0 in /
```

-	Created: Mon, 07 Sep 2015 23:35:05 GMT
-	Docker Version: 1.7.1
-	Virtual Size: 125.2 MB (125159131 bytes)
-	v2 Blob: `sha256:f8efbffe7b954b520805da80ce0cce94e3834482c384c25c8851db98696e7f70`
-	v2 Content-Length: 51.4 MB (51359708 bytes)
-	v2 Last-Modified: Mon, 07 Sep 2015 23:38:06 GMT

#### `8c00acfb017549e44d28098762c3e6296872a1ca9b90385855f1019d84bb0dac`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Mon, 07 Sep 2015 23:35:07 GMT
-	Parent Layer: `843e2bded49837e4846422f3a82a67be3ccc46c3e636e03d8d946c57564468ba`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `8b49fe88b40b6c09bbe751e9b235d1919e704ae1765a304226047bd0b203b3fe`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 08 Sep 2015 15:27:57 GMT
-	Parent Layer: `8c00acfb017549e44d28098762c3e6296872a1ca9b90385855f1019d84bb0dac`
-	Docker Version: 1.7.1
-	Virtual Size: 44.4 MB (44355688 bytes)
-	v2 Blob: `sha256:d6314f6cfecf4fc37f622f99d2a114af91ec678d29c76983249f23995ef77563`
-	v2 Content-Length: 18.5 MB (18538583 bytes)
-	v2 Last-Modified: Thu, 10 Sep 2015 23:36:48 GMT

#### `1e7917dfdd7dc805caa9fe209ae9df3a07529269f4989570f312e72ff4f339c8`

```dockerfile
RUN set -ex   && for key in\
     9554F04D7259F04124DE6B476D5A82AC7E37093B\
     94AE36675C464D64BAFA68DD7434390BDBE9B9C5\
     0034A06D9D9B0064CE8ADF6BF1747F4AD2306D93\
     FD3A5288F042B6850C66B31F09FE44734EB7990E\
     71DCFD284A79C3B38668286BC97EC7A07EDE3FC1\
     DD8F2338BAE7501E3DD5AC78C273792F7D83545D   ; do\
     gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"   ; done
```

-	Created: Thu, 10 Sep 2015 07:52:24 GMT
-	Parent Layer: `8b49fe88b40b6c09bbe751e9b235d1919e704ae1765a304226047bd0b203b3fe`
-	Docker Version: 1.7.1
-	Virtual Size: 39.4 KB (39419 bytes)
-	v2 Blob: `sha256:20f9453d177242021cc6799c74fa2a47f6687a3144251dcb13909e6e8edd0d96`
-	v2 Content-Length: 19.9 KB (19856 bytes)
-	v2 Last-Modified: Fri, 11 Sep 2015 04:39:29 GMT

#### `a2f363d07640f912e4ce880341f1c4a88ce12edaf9be3668776f45da3ca5c73d`

```dockerfile
ENV NPM_CONFIG_LOGLEVEL=info
```

-	Created: Thu, 10 Sep 2015 07:52:25 GMT
-	Parent Layer: `1e7917dfdd7dc805caa9fe209ae9df3a07529269f4989570f312e72ff4f339c8`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `e7d859a7f819f4146c93c4778eead93a1e4e86e970c41c5ecd6e7cb027556e9c`

```dockerfile
ENV IOJS_VERSION=2.5.0
```

-	Created: Thu, 10 Sep 2015 07:54:44 GMT
-	Parent Layer: `a2f363d07640f912e4ce880341f1c4a88ce12edaf9be3668776f45da3ca5c73d`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `def0c773154a8c78b2ff26fc64c2375ed961aa03a7ef43bac516522a00ad5825`

```dockerfile
RUN curl -SLO "https://iojs.org/dist/v$IOJS_VERSION/iojs-v$IOJS_VERSION-linux-x64.tar.gz"   && curl -SLO "https://iojs.org/dist/v$IOJS_VERSION/SHASUMS256.txt.asc"   && gpg --verify SHASUMS256.txt.asc   && grep " iojs-v$IOJS_VERSION-linux-x64.tar.gz\$" SHASUMS256.txt.asc | sha256sum -c -   && tar -xzf "iojs-v$IOJS_VERSION-linux-x64.tar.gz" -C /usr/local --strip-components=1   && rm "iojs-v$IOJS_VERSION-linux-x64.tar.gz" SHASUMS256.txt.asc
```

-	Created: Thu, 10 Sep 2015 07:54:50 GMT
-	Parent Layer: `e7d859a7f819f4146c93c4778eead93a1e4e86e970c41c5ecd6e7cb027556e9c`
-	Docker Version: 1.7.1
-	Virtual Size: 28.9 MB (28932947 bytes)
-	v2 Blob: `sha256:7a58f7d23f0c1b2b82f101a9476e9f2810848885fa5ce1702c102b961c733a37`
-	v2 Content-Length: 9.3 MB (9251252 bytes)
-	v2 Last-Modified: Fri, 11 Sep 2015 04:44:37 GMT

#### `f1c2420e87fc6a1a4939f3effd2bd3e5e83281c9f2d5a86d9897fcd6ed872da8`

```dockerfile
CMD ["iojs"]
```

-	Created: Thu, 10 Sep 2015 07:54:51 GMT
-	Parent Layer: `def0c773154a8c78b2ff26fc64c2375ed961aa03a7ef43bac516522a00ad5825`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

## `iojs:3.3.0`

```console
$ docker pull library/iojs@sha256:e9d7cba25cf9a796789ce1c0c322a85fa9a6bb0fedc782b75dce441fb13d99e1
```

-	Total Virtual Size: 641.2 MB (641174444 bytes)
-	Total v2 Content-Length: 252.3 MB (252271245 bytes)

### Layers (10)

#### `843e2bded49837e4846422f3a82a67be3ccc46c3e636e03d8d946c57564468ba`

```dockerfile
ADD file:c7d957020a6ee3df60f2407c7a383cabcfa67d43f6d5151b241b37034f5bc6e0 in /
```

-	Created: Mon, 07 Sep 2015 23:35:05 GMT
-	Docker Version: 1.7.1
-	Virtual Size: 125.2 MB (125159131 bytes)
-	v2 Blob: `sha256:f8efbffe7b954b520805da80ce0cce94e3834482c384c25c8851db98696e7f70`
-	v2 Content-Length: 51.4 MB (51359708 bytes)
-	v2 Last-Modified: Mon, 07 Sep 2015 23:38:06 GMT

#### `8c00acfb017549e44d28098762c3e6296872a1ca9b90385855f1019d84bb0dac`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Mon, 07 Sep 2015 23:35:07 GMT
-	Parent Layer: `843e2bded49837e4846422f3a82a67be3ccc46c3e636e03d8d946c57564468ba`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `8b49fe88b40b6c09bbe751e9b235d1919e704ae1765a304226047bd0b203b3fe`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 08 Sep 2015 15:27:57 GMT
-	Parent Layer: `8c00acfb017549e44d28098762c3e6296872a1ca9b90385855f1019d84bb0dac`
-	Docker Version: 1.7.1
-	Virtual Size: 44.4 MB (44355688 bytes)
-	v2 Blob: `sha256:d6314f6cfecf4fc37f622f99d2a114af91ec678d29c76983249f23995ef77563`
-	v2 Content-Length: 18.5 MB (18538583 bytes)
-	v2 Last-Modified: Thu, 10 Sep 2015 23:36:48 GMT

#### `20b348f4d5682b697d2f456322c97d916bafb65f6c4436697209ac1ec0f1803f`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 08 Sep 2015 15:29:05 GMT
-	Parent Layer: `8b49fe88b40b6c09bbe751e9b235d1919e704ae1765a304226047bd0b203b3fe`
-	Docker Version: 1.7.1
-	Virtual Size: 122.3 MB (122317988 bytes)
-	v2 Blob: `sha256:a6f2dac3eb9c26067c12dafd0c917f591d9881ee84a45f750d7a1d58187adfd8`
-	v2 Content-Length: 42.3 MB (42339522 bytes)
-	v2 Last-Modified: Tue, 08 Sep 2015 15:43:42 GMT

#### `16b189cc8ce688f9f1d8f1d837fa0891107450a06c795b1cba8f6c33a4454280`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		autoconf \
		automake \
		bzip2 \
		file \
		g++ \
		gcc \
		imagemagick \
		libbz2-dev \
		libc6-dev \
		libcurl4-openssl-dev \
		libevent-dev \
		libffi-dev \
		libgeoip-dev \
		libglib2.0-dev \
		libjpeg-dev \
		liblzma-dev \
		libmagickcore-dev \
		libmagickwand-dev \
		libmysqlclient-dev \
		libncurses-dev \
		libpng-dev \
		libpq-dev \
		libreadline-dev \
		libsqlite3-dev \
		libssl-dev \
		libtool \
		libwebp-dev \
		libxml2-dev \
		libxslt-dev \
		libyaml-dev \
		make \
		patch \
		xz-utils \
		zlib1g-dev \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 08 Sep 2015 15:31:25 GMT
-	Parent Layer: `20b348f4d5682b697d2f456322c97d916bafb65f6c4436697209ac1ec0f1803f`
-	Docker Version: 1.7.1
-	Virtual Size: 314.7 MB (314652151 bytes)
-	v2 Blob: `sha256:f4f48828d97bcfe36d5697d8f505088a4369e3d660307576f68ae74031884ca7`
-	v2 Content-Length: 128.5 MB (128531143 bytes)
-	v2 Last-Modified: Tue, 08 Sep 2015 15:45:31 GMT

#### `6227f463e6e24a6ea3c8eaae40b4b206aeb3d63b6c615c3512cd9706524f0a3e`

```dockerfile
RUN set -ex   && for key in\
     9554F04D7259F04124DE6B476D5A82AC7E37093B\
     94AE36675C464D64BAFA68DD7434390BDBE9B9C5\
     0034A06D9D9B0064CE8ADF6BF1747F4AD2306D93\
     FD3A5288F042B6850C66B31F09FE44734EB7990E\
     71DCFD284A79C3B38668286BC97EC7A07EDE3FC1\
     DD8F2338BAE7501E3DD5AC78C273792F7D83545D   ; do\
     gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"   ; done
```

-	Created: Thu, 10 Sep 2015 07:50:51 GMT
-	Parent Layer: `16b189cc8ce688f9f1d8f1d837fa0891107450a06c795b1cba8f6c33a4454280`
-	Docker Version: 1.7.1
-	Virtual Size: 39.4 KB (39419 bytes)
-	v2 Blob: `sha256:61f26d33ec3bbef5073f11f8bad058c136159dee3ea81e9f942337e2a919d062`
-	v2 Content-Length: 19.9 KB (19854 bytes)
-	v2 Last-Modified: Fri, 11 Sep 2015 04:31:02 GMT

#### `2e45961f9f233ca9913dff96558d65a5096aa0b2e6a34711d3ac51289a40f50d`

```dockerfile
ENV NPM_CONFIG_LOGLEVEL=info
```

-	Created: Thu, 10 Sep 2015 07:50:51 GMT
-	Parent Layer: `6227f463e6e24a6ea3c8eaae40b4b206aeb3d63b6c615c3512cd9706524f0a3e`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `d6121d3249540e18301640b4991e78cb09b84c6598c3754b48ffa3a01c9bc0f5`

```dockerfile
ENV IOJS_VERSION=3.3.0
```

-	Created: Thu, 10 Sep 2015 07:55:34 GMT
-	Parent Layer: `2e45961f9f233ca9913dff96558d65a5096aa0b2e6a34711d3ac51289a40f50d`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `ad6edef3fa19561e563f5b851ad375fcb92c81312271de584bb20c664178a9c1`

```dockerfile
RUN curl -SLO "https://iojs.org/dist/v$IOJS_VERSION/iojs-v$IOJS_VERSION-linux-x64.tar.gz"   && curl -SLO "https://iojs.org/dist/v$IOJS_VERSION/SHASUMS256.txt.asc"   && gpg --verify SHASUMS256.txt.asc   && grep " iojs-v$IOJS_VERSION-linux-x64.tar.gz\$" SHASUMS256.txt.asc | sha256sum -c -   && tar -xzf "iojs-v$IOJS_VERSION-linux-x64.tar.gz" -C /usr/local --strip-components=1   && rm "iojs-v$IOJS_VERSION-linux-x64.tar.gz" SHASUMS256.txt.asc
```

-	Created: Thu, 10 Sep 2015 07:55:39 GMT
-	Parent Layer: `d6121d3249540e18301640b4991e78cb09b84c6598c3754b48ffa3a01c9bc0f5`
-	Docker Version: 1.7.1
-	Virtual Size: 34.7 MB (34650067 bytes)
-	v2 Blob: `sha256:880f632cb30a847917e9d1b7a4d21a6ad328ba64c9184daed59842223e53c54f`
-	v2 Content-Length: 11.5 MB (11482307 bytes)
-	v2 Last-Modified: Fri, 11 Sep 2015 04:46:04 GMT

#### `1b198e14bf1696eff48a52a848bf0d82fa5eac7294afe8778f82360e9a23a4f3`

```dockerfile
CMD ["iojs"]
```

-	Created: Thu, 10 Sep 2015 07:55:40 GMT
-	Parent Layer: `ad6edef3fa19561e563f5b851ad375fcb92c81312271de584bb20c664178a9c1`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

## `iojs:3.3`

```console
$ docker pull library/iojs@sha256:f1c4292fe312b3eca00528edb196c6def69431d0e94ffe1b29ec420f5908c6a0
```

-	Total Virtual Size: 641.2 MB (641174444 bytes)
-	Total v2 Content-Length: 252.3 MB (252271245 bytes)

### Layers (10)

#### `843e2bded49837e4846422f3a82a67be3ccc46c3e636e03d8d946c57564468ba`

```dockerfile
ADD file:c7d957020a6ee3df60f2407c7a383cabcfa67d43f6d5151b241b37034f5bc6e0 in /
```

-	Created: Mon, 07 Sep 2015 23:35:05 GMT
-	Docker Version: 1.7.1
-	Virtual Size: 125.2 MB (125159131 bytes)
-	v2 Blob: `sha256:f8efbffe7b954b520805da80ce0cce94e3834482c384c25c8851db98696e7f70`
-	v2 Content-Length: 51.4 MB (51359708 bytes)
-	v2 Last-Modified: Mon, 07 Sep 2015 23:38:06 GMT

#### `8c00acfb017549e44d28098762c3e6296872a1ca9b90385855f1019d84bb0dac`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Mon, 07 Sep 2015 23:35:07 GMT
-	Parent Layer: `843e2bded49837e4846422f3a82a67be3ccc46c3e636e03d8d946c57564468ba`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `8b49fe88b40b6c09bbe751e9b235d1919e704ae1765a304226047bd0b203b3fe`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 08 Sep 2015 15:27:57 GMT
-	Parent Layer: `8c00acfb017549e44d28098762c3e6296872a1ca9b90385855f1019d84bb0dac`
-	Docker Version: 1.7.1
-	Virtual Size: 44.4 MB (44355688 bytes)
-	v2 Blob: `sha256:d6314f6cfecf4fc37f622f99d2a114af91ec678d29c76983249f23995ef77563`
-	v2 Content-Length: 18.5 MB (18538583 bytes)
-	v2 Last-Modified: Thu, 10 Sep 2015 23:36:48 GMT

#### `20b348f4d5682b697d2f456322c97d916bafb65f6c4436697209ac1ec0f1803f`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 08 Sep 2015 15:29:05 GMT
-	Parent Layer: `8b49fe88b40b6c09bbe751e9b235d1919e704ae1765a304226047bd0b203b3fe`
-	Docker Version: 1.7.1
-	Virtual Size: 122.3 MB (122317988 bytes)
-	v2 Blob: `sha256:a6f2dac3eb9c26067c12dafd0c917f591d9881ee84a45f750d7a1d58187adfd8`
-	v2 Content-Length: 42.3 MB (42339522 bytes)
-	v2 Last-Modified: Tue, 08 Sep 2015 15:43:42 GMT

#### `16b189cc8ce688f9f1d8f1d837fa0891107450a06c795b1cba8f6c33a4454280`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		autoconf \
		automake \
		bzip2 \
		file \
		g++ \
		gcc \
		imagemagick \
		libbz2-dev \
		libc6-dev \
		libcurl4-openssl-dev \
		libevent-dev \
		libffi-dev \
		libgeoip-dev \
		libglib2.0-dev \
		libjpeg-dev \
		liblzma-dev \
		libmagickcore-dev \
		libmagickwand-dev \
		libmysqlclient-dev \
		libncurses-dev \
		libpng-dev \
		libpq-dev \
		libreadline-dev \
		libsqlite3-dev \
		libssl-dev \
		libtool \
		libwebp-dev \
		libxml2-dev \
		libxslt-dev \
		libyaml-dev \
		make \
		patch \
		xz-utils \
		zlib1g-dev \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 08 Sep 2015 15:31:25 GMT
-	Parent Layer: `20b348f4d5682b697d2f456322c97d916bafb65f6c4436697209ac1ec0f1803f`
-	Docker Version: 1.7.1
-	Virtual Size: 314.7 MB (314652151 bytes)
-	v2 Blob: `sha256:f4f48828d97bcfe36d5697d8f505088a4369e3d660307576f68ae74031884ca7`
-	v2 Content-Length: 128.5 MB (128531143 bytes)
-	v2 Last-Modified: Tue, 08 Sep 2015 15:45:31 GMT

#### `6227f463e6e24a6ea3c8eaae40b4b206aeb3d63b6c615c3512cd9706524f0a3e`

```dockerfile
RUN set -ex   && for key in\
     9554F04D7259F04124DE6B476D5A82AC7E37093B\
     94AE36675C464D64BAFA68DD7434390BDBE9B9C5\
     0034A06D9D9B0064CE8ADF6BF1747F4AD2306D93\
     FD3A5288F042B6850C66B31F09FE44734EB7990E\
     71DCFD284A79C3B38668286BC97EC7A07EDE3FC1\
     DD8F2338BAE7501E3DD5AC78C273792F7D83545D   ; do\
     gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"   ; done
```

-	Created: Thu, 10 Sep 2015 07:50:51 GMT
-	Parent Layer: `16b189cc8ce688f9f1d8f1d837fa0891107450a06c795b1cba8f6c33a4454280`
-	Docker Version: 1.7.1
-	Virtual Size: 39.4 KB (39419 bytes)
-	v2 Blob: `sha256:61f26d33ec3bbef5073f11f8bad058c136159dee3ea81e9f942337e2a919d062`
-	v2 Content-Length: 19.9 KB (19854 bytes)
-	v2 Last-Modified: Fri, 11 Sep 2015 04:31:02 GMT

#### `2e45961f9f233ca9913dff96558d65a5096aa0b2e6a34711d3ac51289a40f50d`

```dockerfile
ENV NPM_CONFIG_LOGLEVEL=info
```

-	Created: Thu, 10 Sep 2015 07:50:51 GMT
-	Parent Layer: `6227f463e6e24a6ea3c8eaae40b4b206aeb3d63b6c615c3512cd9706524f0a3e`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `d6121d3249540e18301640b4991e78cb09b84c6598c3754b48ffa3a01c9bc0f5`

```dockerfile
ENV IOJS_VERSION=3.3.0
```

-	Created: Thu, 10 Sep 2015 07:55:34 GMT
-	Parent Layer: `2e45961f9f233ca9913dff96558d65a5096aa0b2e6a34711d3ac51289a40f50d`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `ad6edef3fa19561e563f5b851ad375fcb92c81312271de584bb20c664178a9c1`

```dockerfile
RUN curl -SLO "https://iojs.org/dist/v$IOJS_VERSION/iojs-v$IOJS_VERSION-linux-x64.tar.gz"   && curl -SLO "https://iojs.org/dist/v$IOJS_VERSION/SHASUMS256.txt.asc"   && gpg --verify SHASUMS256.txt.asc   && grep " iojs-v$IOJS_VERSION-linux-x64.tar.gz\$" SHASUMS256.txt.asc | sha256sum -c -   && tar -xzf "iojs-v$IOJS_VERSION-linux-x64.tar.gz" -C /usr/local --strip-components=1   && rm "iojs-v$IOJS_VERSION-linux-x64.tar.gz" SHASUMS256.txt.asc
```

-	Created: Thu, 10 Sep 2015 07:55:39 GMT
-	Parent Layer: `d6121d3249540e18301640b4991e78cb09b84c6598c3754b48ffa3a01c9bc0f5`
-	Docker Version: 1.7.1
-	Virtual Size: 34.7 MB (34650067 bytes)
-	v2 Blob: `sha256:880f632cb30a847917e9d1b7a4d21a6ad328ba64c9184daed59842223e53c54f`
-	v2 Content-Length: 11.5 MB (11482307 bytes)
-	v2 Last-Modified: Fri, 11 Sep 2015 04:46:04 GMT

#### `1b198e14bf1696eff48a52a848bf0d82fa5eac7294afe8778f82360e9a23a4f3`

```dockerfile
CMD ["iojs"]
```

-	Created: Thu, 10 Sep 2015 07:55:40 GMT
-	Parent Layer: `ad6edef3fa19561e563f5b851ad375fcb92c81312271de584bb20c664178a9c1`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

## `iojs:3`

```console
$ docker pull library/iojs@sha256:18107f13115caa7896fda263e97cdeb8b37be2f369f08c143b517bd88f79051c
```

-	Total Virtual Size: 641.2 MB (641174444 bytes)
-	Total v2 Content-Length: 252.3 MB (252271245 bytes)

### Layers (10)

#### `843e2bded49837e4846422f3a82a67be3ccc46c3e636e03d8d946c57564468ba`

```dockerfile
ADD file:c7d957020a6ee3df60f2407c7a383cabcfa67d43f6d5151b241b37034f5bc6e0 in /
```

-	Created: Mon, 07 Sep 2015 23:35:05 GMT
-	Docker Version: 1.7.1
-	Virtual Size: 125.2 MB (125159131 bytes)
-	v2 Blob: `sha256:f8efbffe7b954b520805da80ce0cce94e3834482c384c25c8851db98696e7f70`
-	v2 Content-Length: 51.4 MB (51359708 bytes)
-	v2 Last-Modified: Mon, 07 Sep 2015 23:38:06 GMT

#### `8c00acfb017549e44d28098762c3e6296872a1ca9b90385855f1019d84bb0dac`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Mon, 07 Sep 2015 23:35:07 GMT
-	Parent Layer: `843e2bded49837e4846422f3a82a67be3ccc46c3e636e03d8d946c57564468ba`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `8b49fe88b40b6c09bbe751e9b235d1919e704ae1765a304226047bd0b203b3fe`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 08 Sep 2015 15:27:57 GMT
-	Parent Layer: `8c00acfb017549e44d28098762c3e6296872a1ca9b90385855f1019d84bb0dac`
-	Docker Version: 1.7.1
-	Virtual Size: 44.4 MB (44355688 bytes)
-	v2 Blob: `sha256:d6314f6cfecf4fc37f622f99d2a114af91ec678d29c76983249f23995ef77563`
-	v2 Content-Length: 18.5 MB (18538583 bytes)
-	v2 Last-Modified: Thu, 10 Sep 2015 23:36:48 GMT

#### `20b348f4d5682b697d2f456322c97d916bafb65f6c4436697209ac1ec0f1803f`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 08 Sep 2015 15:29:05 GMT
-	Parent Layer: `8b49fe88b40b6c09bbe751e9b235d1919e704ae1765a304226047bd0b203b3fe`
-	Docker Version: 1.7.1
-	Virtual Size: 122.3 MB (122317988 bytes)
-	v2 Blob: `sha256:a6f2dac3eb9c26067c12dafd0c917f591d9881ee84a45f750d7a1d58187adfd8`
-	v2 Content-Length: 42.3 MB (42339522 bytes)
-	v2 Last-Modified: Tue, 08 Sep 2015 15:43:42 GMT

#### `16b189cc8ce688f9f1d8f1d837fa0891107450a06c795b1cba8f6c33a4454280`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		autoconf \
		automake \
		bzip2 \
		file \
		g++ \
		gcc \
		imagemagick \
		libbz2-dev \
		libc6-dev \
		libcurl4-openssl-dev \
		libevent-dev \
		libffi-dev \
		libgeoip-dev \
		libglib2.0-dev \
		libjpeg-dev \
		liblzma-dev \
		libmagickcore-dev \
		libmagickwand-dev \
		libmysqlclient-dev \
		libncurses-dev \
		libpng-dev \
		libpq-dev \
		libreadline-dev \
		libsqlite3-dev \
		libssl-dev \
		libtool \
		libwebp-dev \
		libxml2-dev \
		libxslt-dev \
		libyaml-dev \
		make \
		patch \
		xz-utils \
		zlib1g-dev \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 08 Sep 2015 15:31:25 GMT
-	Parent Layer: `20b348f4d5682b697d2f456322c97d916bafb65f6c4436697209ac1ec0f1803f`
-	Docker Version: 1.7.1
-	Virtual Size: 314.7 MB (314652151 bytes)
-	v2 Blob: `sha256:f4f48828d97bcfe36d5697d8f505088a4369e3d660307576f68ae74031884ca7`
-	v2 Content-Length: 128.5 MB (128531143 bytes)
-	v2 Last-Modified: Tue, 08 Sep 2015 15:45:31 GMT

#### `6227f463e6e24a6ea3c8eaae40b4b206aeb3d63b6c615c3512cd9706524f0a3e`

```dockerfile
RUN set -ex   && for key in\
     9554F04D7259F04124DE6B476D5A82AC7E37093B\
     94AE36675C464D64BAFA68DD7434390BDBE9B9C5\
     0034A06D9D9B0064CE8ADF6BF1747F4AD2306D93\
     FD3A5288F042B6850C66B31F09FE44734EB7990E\
     71DCFD284A79C3B38668286BC97EC7A07EDE3FC1\
     DD8F2338BAE7501E3DD5AC78C273792F7D83545D   ; do\
     gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"   ; done
```

-	Created: Thu, 10 Sep 2015 07:50:51 GMT
-	Parent Layer: `16b189cc8ce688f9f1d8f1d837fa0891107450a06c795b1cba8f6c33a4454280`
-	Docker Version: 1.7.1
-	Virtual Size: 39.4 KB (39419 bytes)
-	v2 Blob: `sha256:61f26d33ec3bbef5073f11f8bad058c136159dee3ea81e9f942337e2a919d062`
-	v2 Content-Length: 19.9 KB (19854 bytes)
-	v2 Last-Modified: Fri, 11 Sep 2015 04:31:02 GMT

#### `2e45961f9f233ca9913dff96558d65a5096aa0b2e6a34711d3ac51289a40f50d`

```dockerfile
ENV NPM_CONFIG_LOGLEVEL=info
```

-	Created: Thu, 10 Sep 2015 07:50:51 GMT
-	Parent Layer: `6227f463e6e24a6ea3c8eaae40b4b206aeb3d63b6c615c3512cd9706524f0a3e`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `d6121d3249540e18301640b4991e78cb09b84c6598c3754b48ffa3a01c9bc0f5`

```dockerfile
ENV IOJS_VERSION=3.3.0
```

-	Created: Thu, 10 Sep 2015 07:55:34 GMT
-	Parent Layer: `2e45961f9f233ca9913dff96558d65a5096aa0b2e6a34711d3ac51289a40f50d`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `ad6edef3fa19561e563f5b851ad375fcb92c81312271de584bb20c664178a9c1`

```dockerfile
RUN curl -SLO "https://iojs.org/dist/v$IOJS_VERSION/iojs-v$IOJS_VERSION-linux-x64.tar.gz"   && curl -SLO "https://iojs.org/dist/v$IOJS_VERSION/SHASUMS256.txt.asc"   && gpg --verify SHASUMS256.txt.asc   && grep " iojs-v$IOJS_VERSION-linux-x64.tar.gz\$" SHASUMS256.txt.asc | sha256sum -c -   && tar -xzf "iojs-v$IOJS_VERSION-linux-x64.tar.gz" -C /usr/local --strip-components=1   && rm "iojs-v$IOJS_VERSION-linux-x64.tar.gz" SHASUMS256.txt.asc
```

-	Created: Thu, 10 Sep 2015 07:55:39 GMT
-	Parent Layer: `d6121d3249540e18301640b4991e78cb09b84c6598c3754b48ffa3a01c9bc0f5`
-	Docker Version: 1.7.1
-	Virtual Size: 34.7 MB (34650067 bytes)
-	v2 Blob: `sha256:880f632cb30a847917e9d1b7a4d21a6ad328ba64c9184daed59842223e53c54f`
-	v2 Content-Length: 11.5 MB (11482307 bytes)
-	v2 Last-Modified: Fri, 11 Sep 2015 04:46:04 GMT

#### `1b198e14bf1696eff48a52a848bf0d82fa5eac7294afe8778f82360e9a23a4f3`

```dockerfile
CMD ["iojs"]
```

-	Created: Thu, 10 Sep 2015 07:55:40 GMT
-	Parent Layer: `ad6edef3fa19561e563f5b851ad375fcb92c81312271de584bb20c664178a9c1`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

## `iojs:latest`

```console
$ docker pull library/iojs@sha256:1906ecbe478a5bfa5f7860279d37b8dbdf89af2ea3970181692afa290d5cd9ad
```

-	Total Virtual Size: 641.2 MB (641174444 bytes)
-	Total v2 Content-Length: 252.3 MB (252271245 bytes)

### Layers (10)

#### `843e2bded49837e4846422f3a82a67be3ccc46c3e636e03d8d946c57564468ba`

```dockerfile
ADD file:c7d957020a6ee3df60f2407c7a383cabcfa67d43f6d5151b241b37034f5bc6e0 in /
```

-	Created: Mon, 07 Sep 2015 23:35:05 GMT
-	Docker Version: 1.7.1
-	Virtual Size: 125.2 MB (125159131 bytes)
-	v2 Blob: `sha256:f8efbffe7b954b520805da80ce0cce94e3834482c384c25c8851db98696e7f70`
-	v2 Content-Length: 51.4 MB (51359708 bytes)
-	v2 Last-Modified: Mon, 07 Sep 2015 23:38:06 GMT

#### `8c00acfb017549e44d28098762c3e6296872a1ca9b90385855f1019d84bb0dac`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Mon, 07 Sep 2015 23:35:07 GMT
-	Parent Layer: `843e2bded49837e4846422f3a82a67be3ccc46c3e636e03d8d946c57564468ba`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `8b49fe88b40b6c09bbe751e9b235d1919e704ae1765a304226047bd0b203b3fe`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 08 Sep 2015 15:27:57 GMT
-	Parent Layer: `8c00acfb017549e44d28098762c3e6296872a1ca9b90385855f1019d84bb0dac`
-	Docker Version: 1.7.1
-	Virtual Size: 44.4 MB (44355688 bytes)
-	v2 Blob: `sha256:d6314f6cfecf4fc37f622f99d2a114af91ec678d29c76983249f23995ef77563`
-	v2 Content-Length: 18.5 MB (18538583 bytes)
-	v2 Last-Modified: Thu, 10 Sep 2015 23:36:48 GMT

#### `20b348f4d5682b697d2f456322c97d916bafb65f6c4436697209ac1ec0f1803f`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 08 Sep 2015 15:29:05 GMT
-	Parent Layer: `8b49fe88b40b6c09bbe751e9b235d1919e704ae1765a304226047bd0b203b3fe`
-	Docker Version: 1.7.1
-	Virtual Size: 122.3 MB (122317988 bytes)
-	v2 Blob: `sha256:a6f2dac3eb9c26067c12dafd0c917f591d9881ee84a45f750d7a1d58187adfd8`
-	v2 Content-Length: 42.3 MB (42339522 bytes)
-	v2 Last-Modified: Tue, 08 Sep 2015 15:43:42 GMT

#### `16b189cc8ce688f9f1d8f1d837fa0891107450a06c795b1cba8f6c33a4454280`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		autoconf \
		automake \
		bzip2 \
		file \
		g++ \
		gcc \
		imagemagick \
		libbz2-dev \
		libc6-dev \
		libcurl4-openssl-dev \
		libevent-dev \
		libffi-dev \
		libgeoip-dev \
		libglib2.0-dev \
		libjpeg-dev \
		liblzma-dev \
		libmagickcore-dev \
		libmagickwand-dev \
		libmysqlclient-dev \
		libncurses-dev \
		libpng-dev \
		libpq-dev \
		libreadline-dev \
		libsqlite3-dev \
		libssl-dev \
		libtool \
		libwebp-dev \
		libxml2-dev \
		libxslt-dev \
		libyaml-dev \
		make \
		patch \
		xz-utils \
		zlib1g-dev \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 08 Sep 2015 15:31:25 GMT
-	Parent Layer: `20b348f4d5682b697d2f456322c97d916bafb65f6c4436697209ac1ec0f1803f`
-	Docker Version: 1.7.1
-	Virtual Size: 314.7 MB (314652151 bytes)
-	v2 Blob: `sha256:f4f48828d97bcfe36d5697d8f505088a4369e3d660307576f68ae74031884ca7`
-	v2 Content-Length: 128.5 MB (128531143 bytes)
-	v2 Last-Modified: Tue, 08 Sep 2015 15:45:31 GMT

#### `6227f463e6e24a6ea3c8eaae40b4b206aeb3d63b6c615c3512cd9706524f0a3e`

```dockerfile
RUN set -ex   && for key in\
     9554F04D7259F04124DE6B476D5A82AC7E37093B\
     94AE36675C464D64BAFA68DD7434390BDBE9B9C5\
     0034A06D9D9B0064CE8ADF6BF1747F4AD2306D93\
     FD3A5288F042B6850C66B31F09FE44734EB7990E\
     71DCFD284A79C3B38668286BC97EC7A07EDE3FC1\
     DD8F2338BAE7501E3DD5AC78C273792F7D83545D   ; do\
     gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"   ; done
```

-	Created: Thu, 10 Sep 2015 07:50:51 GMT
-	Parent Layer: `16b189cc8ce688f9f1d8f1d837fa0891107450a06c795b1cba8f6c33a4454280`
-	Docker Version: 1.7.1
-	Virtual Size: 39.4 KB (39419 bytes)
-	v2 Blob: `sha256:61f26d33ec3bbef5073f11f8bad058c136159dee3ea81e9f942337e2a919d062`
-	v2 Content-Length: 19.9 KB (19854 bytes)
-	v2 Last-Modified: Fri, 11 Sep 2015 04:31:02 GMT

#### `2e45961f9f233ca9913dff96558d65a5096aa0b2e6a34711d3ac51289a40f50d`

```dockerfile
ENV NPM_CONFIG_LOGLEVEL=info
```

-	Created: Thu, 10 Sep 2015 07:50:51 GMT
-	Parent Layer: `6227f463e6e24a6ea3c8eaae40b4b206aeb3d63b6c615c3512cd9706524f0a3e`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `d6121d3249540e18301640b4991e78cb09b84c6598c3754b48ffa3a01c9bc0f5`

```dockerfile
ENV IOJS_VERSION=3.3.0
```

-	Created: Thu, 10 Sep 2015 07:55:34 GMT
-	Parent Layer: `2e45961f9f233ca9913dff96558d65a5096aa0b2e6a34711d3ac51289a40f50d`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `ad6edef3fa19561e563f5b851ad375fcb92c81312271de584bb20c664178a9c1`

```dockerfile
RUN curl -SLO "https://iojs.org/dist/v$IOJS_VERSION/iojs-v$IOJS_VERSION-linux-x64.tar.gz"   && curl -SLO "https://iojs.org/dist/v$IOJS_VERSION/SHASUMS256.txt.asc"   && gpg --verify SHASUMS256.txt.asc   && grep " iojs-v$IOJS_VERSION-linux-x64.tar.gz\$" SHASUMS256.txt.asc | sha256sum -c -   && tar -xzf "iojs-v$IOJS_VERSION-linux-x64.tar.gz" -C /usr/local --strip-components=1   && rm "iojs-v$IOJS_VERSION-linux-x64.tar.gz" SHASUMS256.txt.asc
```

-	Created: Thu, 10 Sep 2015 07:55:39 GMT
-	Parent Layer: `d6121d3249540e18301640b4991e78cb09b84c6598c3754b48ffa3a01c9bc0f5`
-	Docker Version: 1.7.1
-	Virtual Size: 34.7 MB (34650067 bytes)
-	v2 Blob: `sha256:880f632cb30a847917e9d1b7a4d21a6ad328ba64c9184daed59842223e53c54f`
-	v2 Content-Length: 11.5 MB (11482307 bytes)
-	v2 Last-Modified: Fri, 11 Sep 2015 04:46:04 GMT

#### `1b198e14bf1696eff48a52a848bf0d82fa5eac7294afe8778f82360e9a23a4f3`

```dockerfile
CMD ["iojs"]
```

-	Created: Thu, 10 Sep 2015 07:55:40 GMT
-	Parent Layer: `ad6edef3fa19561e563f5b851ad375fcb92c81312271de584bb20c664178a9c1`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

## `iojs:3.3.0-onbuild`

```console
$ docker pull library/iojs@sha256:63360866bf0b448c9cbe0d0c89cdb25a4c2cb576d092f2e0e0898974b53983df
```

-	Total Virtual Size: 641.2 MB (641174444 bytes)
-	Total v2 Content-Length: 252.3 MB (252271531 bytes)

### Layers (16)

#### `843e2bded49837e4846422f3a82a67be3ccc46c3e636e03d8d946c57564468ba`

```dockerfile
ADD file:c7d957020a6ee3df60f2407c7a383cabcfa67d43f6d5151b241b37034f5bc6e0 in /
```

-	Created: Mon, 07 Sep 2015 23:35:05 GMT
-	Docker Version: 1.7.1
-	Virtual Size: 125.2 MB (125159131 bytes)
-	v2 Blob: `sha256:f8efbffe7b954b520805da80ce0cce94e3834482c384c25c8851db98696e7f70`
-	v2 Content-Length: 51.4 MB (51359708 bytes)
-	v2 Last-Modified: Mon, 07 Sep 2015 23:38:06 GMT

#### `8c00acfb017549e44d28098762c3e6296872a1ca9b90385855f1019d84bb0dac`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Mon, 07 Sep 2015 23:35:07 GMT
-	Parent Layer: `843e2bded49837e4846422f3a82a67be3ccc46c3e636e03d8d946c57564468ba`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `8b49fe88b40b6c09bbe751e9b235d1919e704ae1765a304226047bd0b203b3fe`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 08 Sep 2015 15:27:57 GMT
-	Parent Layer: `8c00acfb017549e44d28098762c3e6296872a1ca9b90385855f1019d84bb0dac`
-	Docker Version: 1.7.1
-	Virtual Size: 44.4 MB (44355688 bytes)
-	v2 Blob: `sha256:d6314f6cfecf4fc37f622f99d2a114af91ec678d29c76983249f23995ef77563`
-	v2 Content-Length: 18.5 MB (18538583 bytes)
-	v2 Last-Modified: Thu, 10 Sep 2015 23:36:48 GMT

#### `20b348f4d5682b697d2f456322c97d916bafb65f6c4436697209ac1ec0f1803f`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 08 Sep 2015 15:29:05 GMT
-	Parent Layer: `8b49fe88b40b6c09bbe751e9b235d1919e704ae1765a304226047bd0b203b3fe`
-	Docker Version: 1.7.1
-	Virtual Size: 122.3 MB (122317988 bytes)
-	v2 Blob: `sha256:a6f2dac3eb9c26067c12dafd0c917f591d9881ee84a45f750d7a1d58187adfd8`
-	v2 Content-Length: 42.3 MB (42339522 bytes)
-	v2 Last-Modified: Tue, 08 Sep 2015 15:43:42 GMT

#### `16b189cc8ce688f9f1d8f1d837fa0891107450a06c795b1cba8f6c33a4454280`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		autoconf \
		automake \
		bzip2 \
		file \
		g++ \
		gcc \
		imagemagick \
		libbz2-dev \
		libc6-dev \
		libcurl4-openssl-dev \
		libevent-dev \
		libffi-dev \
		libgeoip-dev \
		libglib2.0-dev \
		libjpeg-dev \
		liblzma-dev \
		libmagickcore-dev \
		libmagickwand-dev \
		libmysqlclient-dev \
		libncurses-dev \
		libpng-dev \
		libpq-dev \
		libreadline-dev \
		libsqlite3-dev \
		libssl-dev \
		libtool \
		libwebp-dev \
		libxml2-dev \
		libxslt-dev \
		libyaml-dev \
		make \
		patch \
		xz-utils \
		zlib1g-dev \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 08 Sep 2015 15:31:25 GMT
-	Parent Layer: `20b348f4d5682b697d2f456322c97d916bafb65f6c4436697209ac1ec0f1803f`
-	Docker Version: 1.7.1
-	Virtual Size: 314.7 MB (314652151 bytes)
-	v2 Blob: `sha256:f4f48828d97bcfe36d5697d8f505088a4369e3d660307576f68ae74031884ca7`
-	v2 Content-Length: 128.5 MB (128531143 bytes)
-	v2 Last-Modified: Tue, 08 Sep 2015 15:45:31 GMT

#### `6227f463e6e24a6ea3c8eaae40b4b206aeb3d63b6c615c3512cd9706524f0a3e`

```dockerfile
RUN set -ex   && for key in\
     9554F04D7259F04124DE6B476D5A82AC7E37093B\
     94AE36675C464D64BAFA68DD7434390BDBE9B9C5\
     0034A06D9D9B0064CE8ADF6BF1747F4AD2306D93\
     FD3A5288F042B6850C66B31F09FE44734EB7990E\
     71DCFD284A79C3B38668286BC97EC7A07EDE3FC1\
     DD8F2338BAE7501E3DD5AC78C273792F7D83545D   ; do\
     gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"   ; done
```

-	Created: Thu, 10 Sep 2015 07:50:51 GMT
-	Parent Layer: `16b189cc8ce688f9f1d8f1d837fa0891107450a06c795b1cba8f6c33a4454280`
-	Docker Version: 1.7.1
-	Virtual Size: 39.4 KB (39419 bytes)
-	v2 Blob: `sha256:61f26d33ec3bbef5073f11f8bad058c136159dee3ea81e9f942337e2a919d062`
-	v2 Content-Length: 19.9 KB (19854 bytes)
-	v2 Last-Modified: Fri, 11 Sep 2015 04:31:02 GMT

#### `2e45961f9f233ca9913dff96558d65a5096aa0b2e6a34711d3ac51289a40f50d`

```dockerfile
ENV NPM_CONFIG_LOGLEVEL=info
```

-	Created: Thu, 10 Sep 2015 07:50:51 GMT
-	Parent Layer: `6227f463e6e24a6ea3c8eaae40b4b206aeb3d63b6c615c3512cd9706524f0a3e`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `d6121d3249540e18301640b4991e78cb09b84c6598c3754b48ffa3a01c9bc0f5`

```dockerfile
ENV IOJS_VERSION=3.3.0
```

-	Created: Thu, 10 Sep 2015 07:55:34 GMT
-	Parent Layer: `2e45961f9f233ca9913dff96558d65a5096aa0b2e6a34711d3ac51289a40f50d`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `ad6edef3fa19561e563f5b851ad375fcb92c81312271de584bb20c664178a9c1`

```dockerfile
RUN curl -SLO "https://iojs.org/dist/v$IOJS_VERSION/iojs-v$IOJS_VERSION-linux-x64.tar.gz"   && curl -SLO "https://iojs.org/dist/v$IOJS_VERSION/SHASUMS256.txt.asc"   && gpg --verify SHASUMS256.txt.asc   && grep " iojs-v$IOJS_VERSION-linux-x64.tar.gz\$" SHASUMS256.txt.asc | sha256sum -c -   && tar -xzf "iojs-v$IOJS_VERSION-linux-x64.tar.gz" -C /usr/local --strip-components=1   && rm "iojs-v$IOJS_VERSION-linux-x64.tar.gz" SHASUMS256.txt.asc
```

-	Created: Thu, 10 Sep 2015 07:55:39 GMT
-	Parent Layer: `d6121d3249540e18301640b4991e78cb09b84c6598c3754b48ffa3a01c9bc0f5`
-	Docker Version: 1.7.1
-	Virtual Size: 34.7 MB (34650067 bytes)
-	v2 Blob: `sha256:880f632cb30a847917e9d1b7a4d21a6ad328ba64c9184daed59842223e53c54f`
-	v2 Content-Length: 11.5 MB (11482307 bytes)
-	v2 Last-Modified: Fri, 11 Sep 2015 04:46:04 GMT

#### `1b198e14bf1696eff48a52a848bf0d82fa5eac7294afe8778f82360e9a23a4f3`

```dockerfile
CMD ["iojs"]
```

-	Created: Thu, 10 Sep 2015 07:55:40 GMT
-	Parent Layer: `ad6edef3fa19561e563f5b851ad375fcb92c81312271de584bb20c664178a9c1`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `ca0c87731f208965bc024e7f8306e3196213af5743f5be69b891a5d4d9c13dcb`

```dockerfile
RUN mkdir -p /usr/src/app
```

-	Created: Thu, 10 Sep 2015 07:56:33 GMT
-	Parent Layer: `1b198e14bf1696eff48a52a848bf0d82fa5eac7294afe8778f82360e9a23a4f3`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:e0de1387cfbdbef29dc1cd767e3158bd148dd03632abdf070432301d1dfd89a9`
-	v2 Content-Length: 126.0 B
-	v2 Last-Modified: Fri, 11 Sep 2015 04:48:15 GMT

#### `8bda8c066f514f73374a3464c2968117b409c2478f33b336d5ec06322b1fe9c2`

```dockerfile
WORKDIR /usr/src/app
```

-	Created: Thu, 10 Sep 2015 07:56:33 GMT
-	Parent Layer: `ca0c87731f208965bc024e7f8306e3196213af5743f5be69b891a5d4d9c13dcb`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `4904476efc2ea066e1a3c6e273985b94e2de6d3435bb270da4118169d62402f4`

```dockerfile
ONBUILD COPY package.json /usr/src/app/
```

-	Created: Thu, 10 Sep 2015 07:56:34 GMT
-	Parent Layer: `8bda8c066f514f73374a3464c2968117b409c2478f33b336d5ec06322b1fe9c2`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `2e628ba5e514cd9f5b783c993685755ba973a0f5162111f0e0bb3ecb2840535e`

```dockerfile
ONBUILD RUN npm install
```

-	Created: Thu, 10 Sep 2015 07:56:34 GMT
-	Parent Layer: `4904476efc2ea066e1a3c6e273985b94e2de6d3435bb270da4118169d62402f4`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `48b5b95c5a8bb00e2f69f8431f9af46f3674bba58bce55373ab9042c10430ea9`

```dockerfile
ONBUILD COPY . /usr/src/app
```

-	Created: Thu, 10 Sep 2015 07:56:35 GMT
-	Parent Layer: `2e628ba5e514cd9f5b783c993685755ba973a0f5162111f0e0bb3ecb2840535e`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `4bee70652e05216df56c88d0e04dbd62c9e588b7d77e83ca3d62821103bee6d8`

```dockerfile
CMD ["npm" "start"]
```

-	Created: Thu, 10 Sep 2015 07:56:35 GMT
-	Parent Layer: `48b5b95c5a8bb00e2f69f8431f9af46f3674bba58bce55373ab9042c10430ea9`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

## `iojs:3.3-onbuild`

```console
$ docker pull library/iojs@sha256:0116f3445f55b9774ca977512d672a4516e244a902f18d44bf5627b66ae64f41
```

-	Total Virtual Size: 641.2 MB (641174444 bytes)
-	Total v2 Content-Length: 252.3 MB (252271531 bytes)

### Layers (16)

#### `843e2bded49837e4846422f3a82a67be3ccc46c3e636e03d8d946c57564468ba`

```dockerfile
ADD file:c7d957020a6ee3df60f2407c7a383cabcfa67d43f6d5151b241b37034f5bc6e0 in /
```

-	Created: Mon, 07 Sep 2015 23:35:05 GMT
-	Docker Version: 1.7.1
-	Virtual Size: 125.2 MB (125159131 bytes)
-	v2 Blob: `sha256:f8efbffe7b954b520805da80ce0cce94e3834482c384c25c8851db98696e7f70`
-	v2 Content-Length: 51.4 MB (51359708 bytes)
-	v2 Last-Modified: Mon, 07 Sep 2015 23:38:06 GMT

#### `8c00acfb017549e44d28098762c3e6296872a1ca9b90385855f1019d84bb0dac`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Mon, 07 Sep 2015 23:35:07 GMT
-	Parent Layer: `843e2bded49837e4846422f3a82a67be3ccc46c3e636e03d8d946c57564468ba`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `8b49fe88b40b6c09bbe751e9b235d1919e704ae1765a304226047bd0b203b3fe`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 08 Sep 2015 15:27:57 GMT
-	Parent Layer: `8c00acfb017549e44d28098762c3e6296872a1ca9b90385855f1019d84bb0dac`
-	Docker Version: 1.7.1
-	Virtual Size: 44.4 MB (44355688 bytes)
-	v2 Blob: `sha256:d6314f6cfecf4fc37f622f99d2a114af91ec678d29c76983249f23995ef77563`
-	v2 Content-Length: 18.5 MB (18538583 bytes)
-	v2 Last-Modified: Thu, 10 Sep 2015 23:36:48 GMT

#### `20b348f4d5682b697d2f456322c97d916bafb65f6c4436697209ac1ec0f1803f`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 08 Sep 2015 15:29:05 GMT
-	Parent Layer: `8b49fe88b40b6c09bbe751e9b235d1919e704ae1765a304226047bd0b203b3fe`
-	Docker Version: 1.7.1
-	Virtual Size: 122.3 MB (122317988 bytes)
-	v2 Blob: `sha256:a6f2dac3eb9c26067c12dafd0c917f591d9881ee84a45f750d7a1d58187adfd8`
-	v2 Content-Length: 42.3 MB (42339522 bytes)
-	v2 Last-Modified: Tue, 08 Sep 2015 15:43:42 GMT

#### `16b189cc8ce688f9f1d8f1d837fa0891107450a06c795b1cba8f6c33a4454280`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		autoconf \
		automake \
		bzip2 \
		file \
		g++ \
		gcc \
		imagemagick \
		libbz2-dev \
		libc6-dev \
		libcurl4-openssl-dev \
		libevent-dev \
		libffi-dev \
		libgeoip-dev \
		libglib2.0-dev \
		libjpeg-dev \
		liblzma-dev \
		libmagickcore-dev \
		libmagickwand-dev \
		libmysqlclient-dev \
		libncurses-dev \
		libpng-dev \
		libpq-dev \
		libreadline-dev \
		libsqlite3-dev \
		libssl-dev \
		libtool \
		libwebp-dev \
		libxml2-dev \
		libxslt-dev \
		libyaml-dev \
		make \
		patch \
		xz-utils \
		zlib1g-dev \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 08 Sep 2015 15:31:25 GMT
-	Parent Layer: `20b348f4d5682b697d2f456322c97d916bafb65f6c4436697209ac1ec0f1803f`
-	Docker Version: 1.7.1
-	Virtual Size: 314.7 MB (314652151 bytes)
-	v2 Blob: `sha256:f4f48828d97bcfe36d5697d8f505088a4369e3d660307576f68ae74031884ca7`
-	v2 Content-Length: 128.5 MB (128531143 bytes)
-	v2 Last-Modified: Tue, 08 Sep 2015 15:45:31 GMT

#### `6227f463e6e24a6ea3c8eaae40b4b206aeb3d63b6c615c3512cd9706524f0a3e`

```dockerfile
RUN set -ex   && for key in\
     9554F04D7259F04124DE6B476D5A82AC7E37093B\
     94AE36675C464D64BAFA68DD7434390BDBE9B9C5\
     0034A06D9D9B0064CE8ADF6BF1747F4AD2306D93\
     FD3A5288F042B6850C66B31F09FE44734EB7990E\
     71DCFD284A79C3B38668286BC97EC7A07EDE3FC1\
     DD8F2338BAE7501E3DD5AC78C273792F7D83545D   ; do\
     gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"   ; done
```

-	Created: Thu, 10 Sep 2015 07:50:51 GMT
-	Parent Layer: `16b189cc8ce688f9f1d8f1d837fa0891107450a06c795b1cba8f6c33a4454280`
-	Docker Version: 1.7.1
-	Virtual Size: 39.4 KB (39419 bytes)
-	v2 Blob: `sha256:61f26d33ec3bbef5073f11f8bad058c136159dee3ea81e9f942337e2a919d062`
-	v2 Content-Length: 19.9 KB (19854 bytes)
-	v2 Last-Modified: Fri, 11 Sep 2015 04:31:02 GMT

#### `2e45961f9f233ca9913dff96558d65a5096aa0b2e6a34711d3ac51289a40f50d`

```dockerfile
ENV NPM_CONFIG_LOGLEVEL=info
```

-	Created: Thu, 10 Sep 2015 07:50:51 GMT
-	Parent Layer: `6227f463e6e24a6ea3c8eaae40b4b206aeb3d63b6c615c3512cd9706524f0a3e`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `d6121d3249540e18301640b4991e78cb09b84c6598c3754b48ffa3a01c9bc0f5`

```dockerfile
ENV IOJS_VERSION=3.3.0
```

-	Created: Thu, 10 Sep 2015 07:55:34 GMT
-	Parent Layer: `2e45961f9f233ca9913dff96558d65a5096aa0b2e6a34711d3ac51289a40f50d`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `ad6edef3fa19561e563f5b851ad375fcb92c81312271de584bb20c664178a9c1`

```dockerfile
RUN curl -SLO "https://iojs.org/dist/v$IOJS_VERSION/iojs-v$IOJS_VERSION-linux-x64.tar.gz"   && curl -SLO "https://iojs.org/dist/v$IOJS_VERSION/SHASUMS256.txt.asc"   && gpg --verify SHASUMS256.txt.asc   && grep " iojs-v$IOJS_VERSION-linux-x64.tar.gz\$" SHASUMS256.txt.asc | sha256sum -c -   && tar -xzf "iojs-v$IOJS_VERSION-linux-x64.tar.gz" -C /usr/local --strip-components=1   && rm "iojs-v$IOJS_VERSION-linux-x64.tar.gz" SHASUMS256.txt.asc
```

-	Created: Thu, 10 Sep 2015 07:55:39 GMT
-	Parent Layer: `d6121d3249540e18301640b4991e78cb09b84c6598c3754b48ffa3a01c9bc0f5`
-	Docker Version: 1.7.1
-	Virtual Size: 34.7 MB (34650067 bytes)
-	v2 Blob: `sha256:880f632cb30a847917e9d1b7a4d21a6ad328ba64c9184daed59842223e53c54f`
-	v2 Content-Length: 11.5 MB (11482307 bytes)
-	v2 Last-Modified: Fri, 11 Sep 2015 04:46:04 GMT

#### `1b198e14bf1696eff48a52a848bf0d82fa5eac7294afe8778f82360e9a23a4f3`

```dockerfile
CMD ["iojs"]
```

-	Created: Thu, 10 Sep 2015 07:55:40 GMT
-	Parent Layer: `ad6edef3fa19561e563f5b851ad375fcb92c81312271de584bb20c664178a9c1`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `ca0c87731f208965bc024e7f8306e3196213af5743f5be69b891a5d4d9c13dcb`

```dockerfile
RUN mkdir -p /usr/src/app
```

-	Created: Thu, 10 Sep 2015 07:56:33 GMT
-	Parent Layer: `1b198e14bf1696eff48a52a848bf0d82fa5eac7294afe8778f82360e9a23a4f3`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:e0de1387cfbdbef29dc1cd767e3158bd148dd03632abdf070432301d1dfd89a9`
-	v2 Content-Length: 126.0 B
-	v2 Last-Modified: Fri, 11 Sep 2015 04:48:15 GMT

#### `8bda8c066f514f73374a3464c2968117b409c2478f33b336d5ec06322b1fe9c2`

```dockerfile
WORKDIR /usr/src/app
```

-	Created: Thu, 10 Sep 2015 07:56:33 GMT
-	Parent Layer: `ca0c87731f208965bc024e7f8306e3196213af5743f5be69b891a5d4d9c13dcb`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `4904476efc2ea066e1a3c6e273985b94e2de6d3435bb270da4118169d62402f4`

```dockerfile
ONBUILD COPY package.json /usr/src/app/
```

-	Created: Thu, 10 Sep 2015 07:56:34 GMT
-	Parent Layer: `8bda8c066f514f73374a3464c2968117b409c2478f33b336d5ec06322b1fe9c2`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `2e628ba5e514cd9f5b783c993685755ba973a0f5162111f0e0bb3ecb2840535e`

```dockerfile
ONBUILD RUN npm install
```

-	Created: Thu, 10 Sep 2015 07:56:34 GMT
-	Parent Layer: `4904476efc2ea066e1a3c6e273985b94e2de6d3435bb270da4118169d62402f4`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `48b5b95c5a8bb00e2f69f8431f9af46f3674bba58bce55373ab9042c10430ea9`

```dockerfile
ONBUILD COPY . /usr/src/app
```

-	Created: Thu, 10 Sep 2015 07:56:35 GMT
-	Parent Layer: `2e628ba5e514cd9f5b783c993685755ba973a0f5162111f0e0bb3ecb2840535e`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `4bee70652e05216df56c88d0e04dbd62c9e588b7d77e83ca3d62821103bee6d8`

```dockerfile
CMD ["npm" "start"]
```

-	Created: Thu, 10 Sep 2015 07:56:35 GMT
-	Parent Layer: `48b5b95c5a8bb00e2f69f8431f9af46f3674bba58bce55373ab9042c10430ea9`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

## `iojs:3-onbuild`

```console
$ docker pull library/iojs@sha256:00b02aa010b934311b9b7ae747a8eb7e33750d9236b2dba0096215b7bb5ac9bd
```

-	Total Virtual Size: 641.2 MB (641174444 bytes)
-	Total v2 Content-Length: 252.3 MB (252271531 bytes)

### Layers (16)

#### `843e2bded49837e4846422f3a82a67be3ccc46c3e636e03d8d946c57564468ba`

```dockerfile
ADD file:c7d957020a6ee3df60f2407c7a383cabcfa67d43f6d5151b241b37034f5bc6e0 in /
```

-	Created: Mon, 07 Sep 2015 23:35:05 GMT
-	Docker Version: 1.7.1
-	Virtual Size: 125.2 MB (125159131 bytes)
-	v2 Blob: `sha256:f8efbffe7b954b520805da80ce0cce94e3834482c384c25c8851db98696e7f70`
-	v2 Content-Length: 51.4 MB (51359708 bytes)
-	v2 Last-Modified: Mon, 07 Sep 2015 23:38:06 GMT

#### `8c00acfb017549e44d28098762c3e6296872a1ca9b90385855f1019d84bb0dac`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Mon, 07 Sep 2015 23:35:07 GMT
-	Parent Layer: `843e2bded49837e4846422f3a82a67be3ccc46c3e636e03d8d946c57564468ba`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `8b49fe88b40b6c09bbe751e9b235d1919e704ae1765a304226047bd0b203b3fe`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 08 Sep 2015 15:27:57 GMT
-	Parent Layer: `8c00acfb017549e44d28098762c3e6296872a1ca9b90385855f1019d84bb0dac`
-	Docker Version: 1.7.1
-	Virtual Size: 44.4 MB (44355688 bytes)
-	v2 Blob: `sha256:d6314f6cfecf4fc37f622f99d2a114af91ec678d29c76983249f23995ef77563`
-	v2 Content-Length: 18.5 MB (18538583 bytes)
-	v2 Last-Modified: Thu, 10 Sep 2015 23:36:48 GMT

#### `20b348f4d5682b697d2f456322c97d916bafb65f6c4436697209ac1ec0f1803f`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 08 Sep 2015 15:29:05 GMT
-	Parent Layer: `8b49fe88b40b6c09bbe751e9b235d1919e704ae1765a304226047bd0b203b3fe`
-	Docker Version: 1.7.1
-	Virtual Size: 122.3 MB (122317988 bytes)
-	v2 Blob: `sha256:a6f2dac3eb9c26067c12dafd0c917f591d9881ee84a45f750d7a1d58187adfd8`
-	v2 Content-Length: 42.3 MB (42339522 bytes)
-	v2 Last-Modified: Tue, 08 Sep 2015 15:43:42 GMT

#### `16b189cc8ce688f9f1d8f1d837fa0891107450a06c795b1cba8f6c33a4454280`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		autoconf \
		automake \
		bzip2 \
		file \
		g++ \
		gcc \
		imagemagick \
		libbz2-dev \
		libc6-dev \
		libcurl4-openssl-dev \
		libevent-dev \
		libffi-dev \
		libgeoip-dev \
		libglib2.0-dev \
		libjpeg-dev \
		liblzma-dev \
		libmagickcore-dev \
		libmagickwand-dev \
		libmysqlclient-dev \
		libncurses-dev \
		libpng-dev \
		libpq-dev \
		libreadline-dev \
		libsqlite3-dev \
		libssl-dev \
		libtool \
		libwebp-dev \
		libxml2-dev \
		libxslt-dev \
		libyaml-dev \
		make \
		patch \
		xz-utils \
		zlib1g-dev \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 08 Sep 2015 15:31:25 GMT
-	Parent Layer: `20b348f4d5682b697d2f456322c97d916bafb65f6c4436697209ac1ec0f1803f`
-	Docker Version: 1.7.1
-	Virtual Size: 314.7 MB (314652151 bytes)
-	v2 Blob: `sha256:f4f48828d97bcfe36d5697d8f505088a4369e3d660307576f68ae74031884ca7`
-	v2 Content-Length: 128.5 MB (128531143 bytes)
-	v2 Last-Modified: Tue, 08 Sep 2015 15:45:31 GMT

#### `6227f463e6e24a6ea3c8eaae40b4b206aeb3d63b6c615c3512cd9706524f0a3e`

```dockerfile
RUN set -ex   && for key in\
     9554F04D7259F04124DE6B476D5A82AC7E37093B\
     94AE36675C464D64BAFA68DD7434390BDBE9B9C5\
     0034A06D9D9B0064CE8ADF6BF1747F4AD2306D93\
     FD3A5288F042B6850C66B31F09FE44734EB7990E\
     71DCFD284A79C3B38668286BC97EC7A07EDE3FC1\
     DD8F2338BAE7501E3DD5AC78C273792F7D83545D   ; do\
     gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"   ; done
```

-	Created: Thu, 10 Sep 2015 07:50:51 GMT
-	Parent Layer: `16b189cc8ce688f9f1d8f1d837fa0891107450a06c795b1cba8f6c33a4454280`
-	Docker Version: 1.7.1
-	Virtual Size: 39.4 KB (39419 bytes)
-	v2 Blob: `sha256:61f26d33ec3bbef5073f11f8bad058c136159dee3ea81e9f942337e2a919d062`
-	v2 Content-Length: 19.9 KB (19854 bytes)
-	v2 Last-Modified: Fri, 11 Sep 2015 04:31:02 GMT

#### `2e45961f9f233ca9913dff96558d65a5096aa0b2e6a34711d3ac51289a40f50d`

```dockerfile
ENV NPM_CONFIG_LOGLEVEL=info
```

-	Created: Thu, 10 Sep 2015 07:50:51 GMT
-	Parent Layer: `6227f463e6e24a6ea3c8eaae40b4b206aeb3d63b6c615c3512cd9706524f0a3e`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `d6121d3249540e18301640b4991e78cb09b84c6598c3754b48ffa3a01c9bc0f5`

```dockerfile
ENV IOJS_VERSION=3.3.0
```

-	Created: Thu, 10 Sep 2015 07:55:34 GMT
-	Parent Layer: `2e45961f9f233ca9913dff96558d65a5096aa0b2e6a34711d3ac51289a40f50d`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `ad6edef3fa19561e563f5b851ad375fcb92c81312271de584bb20c664178a9c1`

```dockerfile
RUN curl -SLO "https://iojs.org/dist/v$IOJS_VERSION/iojs-v$IOJS_VERSION-linux-x64.tar.gz"   && curl -SLO "https://iojs.org/dist/v$IOJS_VERSION/SHASUMS256.txt.asc"   && gpg --verify SHASUMS256.txt.asc   && grep " iojs-v$IOJS_VERSION-linux-x64.tar.gz\$" SHASUMS256.txt.asc | sha256sum -c -   && tar -xzf "iojs-v$IOJS_VERSION-linux-x64.tar.gz" -C /usr/local --strip-components=1   && rm "iojs-v$IOJS_VERSION-linux-x64.tar.gz" SHASUMS256.txt.asc
```

-	Created: Thu, 10 Sep 2015 07:55:39 GMT
-	Parent Layer: `d6121d3249540e18301640b4991e78cb09b84c6598c3754b48ffa3a01c9bc0f5`
-	Docker Version: 1.7.1
-	Virtual Size: 34.7 MB (34650067 bytes)
-	v2 Blob: `sha256:880f632cb30a847917e9d1b7a4d21a6ad328ba64c9184daed59842223e53c54f`
-	v2 Content-Length: 11.5 MB (11482307 bytes)
-	v2 Last-Modified: Fri, 11 Sep 2015 04:46:04 GMT

#### `1b198e14bf1696eff48a52a848bf0d82fa5eac7294afe8778f82360e9a23a4f3`

```dockerfile
CMD ["iojs"]
```

-	Created: Thu, 10 Sep 2015 07:55:40 GMT
-	Parent Layer: `ad6edef3fa19561e563f5b851ad375fcb92c81312271de584bb20c664178a9c1`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `ca0c87731f208965bc024e7f8306e3196213af5743f5be69b891a5d4d9c13dcb`

```dockerfile
RUN mkdir -p /usr/src/app
```

-	Created: Thu, 10 Sep 2015 07:56:33 GMT
-	Parent Layer: `1b198e14bf1696eff48a52a848bf0d82fa5eac7294afe8778f82360e9a23a4f3`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:e0de1387cfbdbef29dc1cd767e3158bd148dd03632abdf070432301d1dfd89a9`
-	v2 Content-Length: 126.0 B
-	v2 Last-Modified: Fri, 11 Sep 2015 04:48:15 GMT

#### `8bda8c066f514f73374a3464c2968117b409c2478f33b336d5ec06322b1fe9c2`

```dockerfile
WORKDIR /usr/src/app
```

-	Created: Thu, 10 Sep 2015 07:56:33 GMT
-	Parent Layer: `ca0c87731f208965bc024e7f8306e3196213af5743f5be69b891a5d4d9c13dcb`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `4904476efc2ea066e1a3c6e273985b94e2de6d3435bb270da4118169d62402f4`

```dockerfile
ONBUILD COPY package.json /usr/src/app/
```

-	Created: Thu, 10 Sep 2015 07:56:34 GMT
-	Parent Layer: `8bda8c066f514f73374a3464c2968117b409c2478f33b336d5ec06322b1fe9c2`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `2e628ba5e514cd9f5b783c993685755ba973a0f5162111f0e0bb3ecb2840535e`

```dockerfile
ONBUILD RUN npm install
```

-	Created: Thu, 10 Sep 2015 07:56:34 GMT
-	Parent Layer: `4904476efc2ea066e1a3c6e273985b94e2de6d3435bb270da4118169d62402f4`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `48b5b95c5a8bb00e2f69f8431f9af46f3674bba58bce55373ab9042c10430ea9`

```dockerfile
ONBUILD COPY . /usr/src/app
```

-	Created: Thu, 10 Sep 2015 07:56:35 GMT
-	Parent Layer: `2e628ba5e514cd9f5b783c993685755ba973a0f5162111f0e0bb3ecb2840535e`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `4bee70652e05216df56c88d0e04dbd62c9e588b7d77e83ca3d62821103bee6d8`

```dockerfile
CMD ["npm" "start"]
```

-	Created: Thu, 10 Sep 2015 07:56:35 GMT
-	Parent Layer: `48b5b95c5a8bb00e2f69f8431f9af46f3674bba58bce55373ab9042c10430ea9`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

## `iojs:onbuild`

```console
$ docker pull library/iojs@sha256:44bc2038fae76bf5e211b669c570b06bca44930cdc2f51ab802c1a01b987522d
```

-	Total Virtual Size: 641.2 MB (641174444 bytes)
-	Total v2 Content-Length: 252.3 MB (252271531 bytes)

### Layers (16)

#### `843e2bded49837e4846422f3a82a67be3ccc46c3e636e03d8d946c57564468ba`

```dockerfile
ADD file:c7d957020a6ee3df60f2407c7a383cabcfa67d43f6d5151b241b37034f5bc6e0 in /
```

-	Created: Mon, 07 Sep 2015 23:35:05 GMT
-	Docker Version: 1.7.1
-	Virtual Size: 125.2 MB (125159131 bytes)
-	v2 Blob: `sha256:f8efbffe7b954b520805da80ce0cce94e3834482c384c25c8851db98696e7f70`
-	v2 Content-Length: 51.4 MB (51359708 bytes)
-	v2 Last-Modified: Mon, 07 Sep 2015 23:38:06 GMT

#### `8c00acfb017549e44d28098762c3e6296872a1ca9b90385855f1019d84bb0dac`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Mon, 07 Sep 2015 23:35:07 GMT
-	Parent Layer: `843e2bded49837e4846422f3a82a67be3ccc46c3e636e03d8d946c57564468ba`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `8b49fe88b40b6c09bbe751e9b235d1919e704ae1765a304226047bd0b203b3fe`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 08 Sep 2015 15:27:57 GMT
-	Parent Layer: `8c00acfb017549e44d28098762c3e6296872a1ca9b90385855f1019d84bb0dac`
-	Docker Version: 1.7.1
-	Virtual Size: 44.4 MB (44355688 bytes)
-	v2 Blob: `sha256:d6314f6cfecf4fc37f622f99d2a114af91ec678d29c76983249f23995ef77563`
-	v2 Content-Length: 18.5 MB (18538583 bytes)
-	v2 Last-Modified: Thu, 10 Sep 2015 23:36:48 GMT

#### `20b348f4d5682b697d2f456322c97d916bafb65f6c4436697209ac1ec0f1803f`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 08 Sep 2015 15:29:05 GMT
-	Parent Layer: `8b49fe88b40b6c09bbe751e9b235d1919e704ae1765a304226047bd0b203b3fe`
-	Docker Version: 1.7.1
-	Virtual Size: 122.3 MB (122317988 bytes)
-	v2 Blob: `sha256:a6f2dac3eb9c26067c12dafd0c917f591d9881ee84a45f750d7a1d58187adfd8`
-	v2 Content-Length: 42.3 MB (42339522 bytes)
-	v2 Last-Modified: Tue, 08 Sep 2015 15:43:42 GMT

#### `16b189cc8ce688f9f1d8f1d837fa0891107450a06c795b1cba8f6c33a4454280`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		autoconf \
		automake \
		bzip2 \
		file \
		g++ \
		gcc \
		imagemagick \
		libbz2-dev \
		libc6-dev \
		libcurl4-openssl-dev \
		libevent-dev \
		libffi-dev \
		libgeoip-dev \
		libglib2.0-dev \
		libjpeg-dev \
		liblzma-dev \
		libmagickcore-dev \
		libmagickwand-dev \
		libmysqlclient-dev \
		libncurses-dev \
		libpng-dev \
		libpq-dev \
		libreadline-dev \
		libsqlite3-dev \
		libssl-dev \
		libtool \
		libwebp-dev \
		libxml2-dev \
		libxslt-dev \
		libyaml-dev \
		make \
		patch \
		xz-utils \
		zlib1g-dev \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 08 Sep 2015 15:31:25 GMT
-	Parent Layer: `20b348f4d5682b697d2f456322c97d916bafb65f6c4436697209ac1ec0f1803f`
-	Docker Version: 1.7.1
-	Virtual Size: 314.7 MB (314652151 bytes)
-	v2 Blob: `sha256:f4f48828d97bcfe36d5697d8f505088a4369e3d660307576f68ae74031884ca7`
-	v2 Content-Length: 128.5 MB (128531143 bytes)
-	v2 Last-Modified: Tue, 08 Sep 2015 15:45:31 GMT

#### `6227f463e6e24a6ea3c8eaae40b4b206aeb3d63b6c615c3512cd9706524f0a3e`

```dockerfile
RUN set -ex   && for key in\
     9554F04D7259F04124DE6B476D5A82AC7E37093B\
     94AE36675C464D64BAFA68DD7434390BDBE9B9C5\
     0034A06D9D9B0064CE8ADF6BF1747F4AD2306D93\
     FD3A5288F042B6850C66B31F09FE44734EB7990E\
     71DCFD284A79C3B38668286BC97EC7A07EDE3FC1\
     DD8F2338BAE7501E3DD5AC78C273792F7D83545D   ; do\
     gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"   ; done
```

-	Created: Thu, 10 Sep 2015 07:50:51 GMT
-	Parent Layer: `16b189cc8ce688f9f1d8f1d837fa0891107450a06c795b1cba8f6c33a4454280`
-	Docker Version: 1.7.1
-	Virtual Size: 39.4 KB (39419 bytes)
-	v2 Blob: `sha256:61f26d33ec3bbef5073f11f8bad058c136159dee3ea81e9f942337e2a919d062`
-	v2 Content-Length: 19.9 KB (19854 bytes)
-	v2 Last-Modified: Fri, 11 Sep 2015 04:31:02 GMT

#### `2e45961f9f233ca9913dff96558d65a5096aa0b2e6a34711d3ac51289a40f50d`

```dockerfile
ENV NPM_CONFIG_LOGLEVEL=info
```

-	Created: Thu, 10 Sep 2015 07:50:51 GMT
-	Parent Layer: `6227f463e6e24a6ea3c8eaae40b4b206aeb3d63b6c615c3512cd9706524f0a3e`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `d6121d3249540e18301640b4991e78cb09b84c6598c3754b48ffa3a01c9bc0f5`

```dockerfile
ENV IOJS_VERSION=3.3.0
```

-	Created: Thu, 10 Sep 2015 07:55:34 GMT
-	Parent Layer: `2e45961f9f233ca9913dff96558d65a5096aa0b2e6a34711d3ac51289a40f50d`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `ad6edef3fa19561e563f5b851ad375fcb92c81312271de584bb20c664178a9c1`

```dockerfile
RUN curl -SLO "https://iojs.org/dist/v$IOJS_VERSION/iojs-v$IOJS_VERSION-linux-x64.tar.gz"   && curl -SLO "https://iojs.org/dist/v$IOJS_VERSION/SHASUMS256.txt.asc"   && gpg --verify SHASUMS256.txt.asc   && grep " iojs-v$IOJS_VERSION-linux-x64.tar.gz\$" SHASUMS256.txt.asc | sha256sum -c -   && tar -xzf "iojs-v$IOJS_VERSION-linux-x64.tar.gz" -C /usr/local --strip-components=1   && rm "iojs-v$IOJS_VERSION-linux-x64.tar.gz" SHASUMS256.txt.asc
```

-	Created: Thu, 10 Sep 2015 07:55:39 GMT
-	Parent Layer: `d6121d3249540e18301640b4991e78cb09b84c6598c3754b48ffa3a01c9bc0f5`
-	Docker Version: 1.7.1
-	Virtual Size: 34.7 MB (34650067 bytes)
-	v2 Blob: `sha256:880f632cb30a847917e9d1b7a4d21a6ad328ba64c9184daed59842223e53c54f`
-	v2 Content-Length: 11.5 MB (11482307 bytes)
-	v2 Last-Modified: Fri, 11 Sep 2015 04:46:04 GMT

#### `1b198e14bf1696eff48a52a848bf0d82fa5eac7294afe8778f82360e9a23a4f3`

```dockerfile
CMD ["iojs"]
```

-	Created: Thu, 10 Sep 2015 07:55:40 GMT
-	Parent Layer: `ad6edef3fa19561e563f5b851ad375fcb92c81312271de584bb20c664178a9c1`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `ca0c87731f208965bc024e7f8306e3196213af5743f5be69b891a5d4d9c13dcb`

```dockerfile
RUN mkdir -p /usr/src/app
```

-	Created: Thu, 10 Sep 2015 07:56:33 GMT
-	Parent Layer: `1b198e14bf1696eff48a52a848bf0d82fa5eac7294afe8778f82360e9a23a4f3`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:e0de1387cfbdbef29dc1cd767e3158bd148dd03632abdf070432301d1dfd89a9`
-	v2 Content-Length: 126.0 B
-	v2 Last-Modified: Fri, 11 Sep 2015 04:48:15 GMT

#### `8bda8c066f514f73374a3464c2968117b409c2478f33b336d5ec06322b1fe9c2`

```dockerfile
WORKDIR /usr/src/app
```

-	Created: Thu, 10 Sep 2015 07:56:33 GMT
-	Parent Layer: `ca0c87731f208965bc024e7f8306e3196213af5743f5be69b891a5d4d9c13dcb`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `4904476efc2ea066e1a3c6e273985b94e2de6d3435bb270da4118169d62402f4`

```dockerfile
ONBUILD COPY package.json /usr/src/app/
```

-	Created: Thu, 10 Sep 2015 07:56:34 GMT
-	Parent Layer: `8bda8c066f514f73374a3464c2968117b409c2478f33b336d5ec06322b1fe9c2`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `2e628ba5e514cd9f5b783c993685755ba973a0f5162111f0e0bb3ecb2840535e`

```dockerfile
ONBUILD RUN npm install
```

-	Created: Thu, 10 Sep 2015 07:56:34 GMT
-	Parent Layer: `4904476efc2ea066e1a3c6e273985b94e2de6d3435bb270da4118169d62402f4`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `48b5b95c5a8bb00e2f69f8431f9af46f3674bba58bce55373ab9042c10430ea9`

```dockerfile
ONBUILD COPY . /usr/src/app
```

-	Created: Thu, 10 Sep 2015 07:56:35 GMT
-	Parent Layer: `2e628ba5e514cd9f5b783c993685755ba973a0f5162111f0e0bb3ecb2840535e`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `4bee70652e05216df56c88d0e04dbd62c9e588b7d77e83ca3d62821103bee6d8`

```dockerfile
CMD ["npm" "start"]
```

-	Created: Thu, 10 Sep 2015 07:56:35 GMT
-	Parent Layer: `48b5b95c5a8bb00e2f69f8431f9af46f3674bba58bce55373ab9042c10430ea9`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

## `iojs:3.3.0-slim`

```console
$ docker pull library/iojs@sha256:e5f2a22e3e338666d3007c030b0ed0f763794b717d6db83221c04197f307c4d6
```

-	Total Virtual Size: 204.2 MB (204204305 bytes)
-	Total v2 Content-Length: 81.4 MB (81400599 bytes)

### Layers (8)

#### `843e2bded49837e4846422f3a82a67be3ccc46c3e636e03d8d946c57564468ba`

```dockerfile
ADD file:c7d957020a6ee3df60f2407c7a383cabcfa67d43f6d5151b241b37034f5bc6e0 in /
```

-	Created: Mon, 07 Sep 2015 23:35:05 GMT
-	Docker Version: 1.7.1
-	Virtual Size: 125.2 MB (125159131 bytes)
-	v2 Blob: `sha256:f8efbffe7b954b520805da80ce0cce94e3834482c384c25c8851db98696e7f70`
-	v2 Content-Length: 51.4 MB (51359708 bytes)
-	v2 Last-Modified: Mon, 07 Sep 2015 23:38:06 GMT

#### `8c00acfb017549e44d28098762c3e6296872a1ca9b90385855f1019d84bb0dac`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Mon, 07 Sep 2015 23:35:07 GMT
-	Parent Layer: `843e2bded49837e4846422f3a82a67be3ccc46c3e636e03d8d946c57564468ba`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `8b49fe88b40b6c09bbe751e9b235d1919e704ae1765a304226047bd0b203b3fe`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 08 Sep 2015 15:27:57 GMT
-	Parent Layer: `8c00acfb017549e44d28098762c3e6296872a1ca9b90385855f1019d84bb0dac`
-	Docker Version: 1.7.1
-	Virtual Size: 44.4 MB (44355688 bytes)
-	v2 Blob: `sha256:d6314f6cfecf4fc37f622f99d2a114af91ec678d29c76983249f23995ef77563`
-	v2 Content-Length: 18.5 MB (18538583 bytes)
-	v2 Last-Modified: Thu, 10 Sep 2015 23:36:48 GMT

#### `1e7917dfdd7dc805caa9fe209ae9df3a07529269f4989570f312e72ff4f339c8`

```dockerfile
RUN set -ex   && for key in\
     9554F04D7259F04124DE6B476D5A82AC7E37093B\
     94AE36675C464D64BAFA68DD7434390BDBE9B9C5\
     0034A06D9D9B0064CE8ADF6BF1747F4AD2306D93\
     FD3A5288F042B6850C66B31F09FE44734EB7990E\
     71DCFD284A79C3B38668286BC97EC7A07EDE3FC1\
     DD8F2338BAE7501E3DD5AC78C273792F7D83545D   ; do\
     gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"   ; done
```

-	Created: Thu, 10 Sep 2015 07:52:24 GMT
-	Parent Layer: `8b49fe88b40b6c09bbe751e9b235d1919e704ae1765a304226047bd0b203b3fe`
-	Docker Version: 1.7.1
-	Virtual Size: 39.4 KB (39419 bytes)
-	v2 Blob: `sha256:20f9453d177242021cc6799c74fa2a47f6687a3144251dcb13909e6e8edd0d96`
-	v2 Content-Length: 19.9 KB (19856 bytes)
-	v2 Last-Modified: Fri, 11 Sep 2015 04:39:29 GMT

#### `a2f363d07640f912e4ce880341f1c4a88ce12edaf9be3668776f45da3ca5c73d`

```dockerfile
ENV NPM_CONFIG_LOGLEVEL=info
```

-	Created: Thu, 10 Sep 2015 07:52:25 GMT
-	Parent Layer: `1e7917dfdd7dc805caa9fe209ae9df3a07529269f4989570f312e72ff4f339c8`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `b28dd1c16b74874e66cc509537bbbc59f9c2910384feefe315f930d43fecee9f`

```dockerfile
ENV IOJS_VERSION=3.3.0
```

-	Created: Thu, 10 Sep 2015 07:57:43 GMT
-	Parent Layer: `a2f363d07640f912e4ce880341f1c4a88ce12edaf9be3668776f45da3ca5c73d`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `e55726425149363c861ad6c5ade5b136ce1687a3824643aa3d847bc7acc377cc`

```dockerfile
RUN curl -SLO "https://iojs.org/dist/v$IOJS_VERSION/iojs-v$IOJS_VERSION-linux-x64.tar.gz"   && curl -SLO "https://iojs.org/dist/v$IOJS_VERSION/SHASUMS256.txt.asc"   && gpg --verify SHASUMS256.txt.asc   && grep " iojs-v$IOJS_VERSION-linux-x64.tar.gz\$" SHASUMS256.txt.asc | sha256sum -c -   && tar -xzf "iojs-v$IOJS_VERSION-linux-x64.tar.gz" -C /usr/local --strip-components=1   && rm "iojs-v$IOJS_VERSION-linux-x64.tar.gz" SHASUMS256.txt.asc
```

-	Created: Thu, 10 Sep 2015 07:57:50 GMT
-	Parent Layer: `b28dd1c16b74874e66cc509537bbbc59f9c2910384feefe315f930d43fecee9f`
-	Docker Version: 1.7.1
-	Virtual Size: 34.7 MB (34650067 bytes)
-	v2 Blob: `sha256:85c960f80f7078f5a6f85cfeac2e6ada6e1eabbc8bd85c36db6f0d981786532a`
-	v2 Content-Length: 11.5 MB (11482324 bytes)
-	v2 Last-Modified: Fri, 11 Sep 2015 04:50:48 GMT

#### `afa96cc0bfbd5eeb372091abd7558dab5cdc25d5b40ab2b6fb58e86c13425267`

```dockerfile
CMD ["iojs"]
```

-	Created: Thu, 10 Sep 2015 07:57:51 GMT
-	Parent Layer: `e55726425149363c861ad6c5ade5b136ce1687a3824643aa3d847bc7acc377cc`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

## `iojs:3.3-slim`

```console
$ docker pull library/iojs@sha256:1b9d1e203a480a8df388a763b5f20f91d03372dead44ea2279004deeddeddecd
```

-	Total Virtual Size: 204.2 MB (204204305 bytes)
-	Total v2 Content-Length: 81.4 MB (81400599 bytes)

### Layers (8)

#### `843e2bded49837e4846422f3a82a67be3ccc46c3e636e03d8d946c57564468ba`

```dockerfile
ADD file:c7d957020a6ee3df60f2407c7a383cabcfa67d43f6d5151b241b37034f5bc6e0 in /
```

-	Created: Mon, 07 Sep 2015 23:35:05 GMT
-	Docker Version: 1.7.1
-	Virtual Size: 125.2 MB (125159131 bytes)
-	v2 Blob: `sha256:f8efbffe7b954b520805da80ce0cce94e3834482c384c25c8851db98696e7f70`
-	v2 Content-Length: 51.4 MB (51359708 bytes)
-	v2 Last-Modified: Mon, 07 Sep 2015 23:38:06 GMT

#### `8c00acfb017549e44d28098762c3e6296872a1ca9b90385855f1019d84bb0dac`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Mon, 07 Sep 2015 23:35:07 GMT
-	Parent Layer: `843e2bded49837e4846422f3a82a67be3ccc46c3e636e03d8d946c57564468ba`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `8b49fe88b40b6c09bbe751e9b235d1919e704ae1765a304226047bd0b203b3fe`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 08 Sep 2015 15:27:57 GMT
-	Parent Layer: `8c00acfb017549e44d28098762c3e6296872a1ca9b90385855f1019d84bb0dac`
-	Docker Version: 1.7.1
-	Virtual Size: 44.4 MB (44355688 bytes)
-	v2 Blob: `sha256:d6314f6cfecf4fc37f622f99d2a114af91ec678d29c76983249f23995ef77563`
-	v2 Content-Length: 18.5 MB (18538583 bytes)
-	v2 Last-Modified: Thu, 10 Sep 2015 23:36:48 GMT

#### `1e7917dfdd7dc805caa9fe209ae9df3a07529269f4989570f312e72ff4f339c8`

```dockerfile
RUN set -ex   && for key in\
     9554F04D7259F04124DE6B476D5A82AC7E37093B\
     94AE36675C464D64BAFA68DD7434390BDBE9B9C5\
     0034A06D9D9B0064CE8ADF6BF1747F4AD2306D93\
     FD3A5288F042B6850C66B31F09FE44734EB7990E\
     71DCFD284A79C3B38668286BC97EC7A07EDE3FC1\
     DD8F2338BAE7501E3DD5AC78C273792F7D83545D   ; do\
     gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"   ; done
```

-	Created: Thu, 10 Sep 2015 07:52:24 GMT
-	Parent Layer: `8b49fe88b40b6c09bbe751e9b235d1919e704ae1765a304226047bd0b203b3fe`
-	Docker Version: 1.7.1
-	Virtual Size: 39.4 KB (39419 bytes)
-	v2 Blob: `sha256:20f9453d177242021cc6799c74fa2a47f6687a3144251dcb13909e6e8edd0d96`
-	v2 Content-Length: 19.9 KB (19856 bytes)
-	v2 Last-Modified: Fri, 11 Sep 2015 04:39:29 GMT

#### `a2f363d07640f912e4ce880341f1c4a88ce12edaf9be3668776f45da3ca5c73d`

```dockerfile
ENV NPM_CONFIG_LOGLEVEL=info
```

-	Created: Thu, 10 Sep 2015 07:52:25 GMT
-	Parent Layer: `1e7917dfdd7dc805caa9fe209ae9df3a07529269f4989570f312e72ff4f339c8`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `b28dd1c16b74874e66cc509537bbbc59f9c2910384feefe315f930d43fecee9f`

```dockerfile
ENV IOJS_VERSION=3.3.0
```

-	Created: Thu, 10 Sep 2015 07:57:43 GMT
-	Parent Layer: `a2f363d07640f912e4ce880341f1c4a88ce12edaf9be3668776f45da3ca5c73d`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `e55726425149363c861ad6c5ade5b136ce1687a3824643aa3d847bc7acc377cc`

```dockerfile
RUN curl -SLO "https://iojs.org/dist/v$IOJS_VERSION/iojs-v$IOJS_VERSION-linux-x64.tar.gz"   && curl -SLO "https://iojs.org/dist/v$IOJS_VERSION/SHASUMS256.txt.asc"   && gpg --verify SHASUMS256.txt.asc   && grep " iojs-v$IOJS_VERSION-linux-x64.tar.gz\$" SHASUMS256.txt.asc | sha256sum -c -   && tar -xzf "iojs-v$IOJS_VERSION-linux-x64.tar.gz" -C /usr/local --strip-components=1   && rm "iojs-v$IOJS_VERSION-linux-x64.tar.gz" SHASUMS256.txt.asc
```

-	Created: Thu, 10 Sep 2015 07:57:50 GMT
-	Parent Layer: `b28dd1c16b74874e66cc509537bbbc59f9c2910384feefe315f930d43fecee9f`
-	Docker Version: 1.7.1
-	Virtual Size: 34.7 MB (34650067 bytes)
-	v2 Blob: `sha256:85c960f80f7078f5a6f85cfeac2e6ada6e1eabbc8bd85c36db6f0d981786532a`
-	v2 Content-Length: 11.5 MB (11482324 bytes)
-	v2 Last-Modified: Fri, 11 Sep 2015 04:50:48 GMT

#### `afa96cc0bfbd5eeb372091abd7558dab5cdc25d5b40ab2b6fb58e86c13425267`

```dockerfile
CMD ["iojs"]
```

-	Created: Thu, 10 Sep 2015 07:57:51 GMT
-	Parent Layer: `e55726425149363c861ad6c5ade5b136ce1687a3824643aa3d847bc7acc377cc`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

## `iojs:3-slim`

```console
$ docker pull library/iojs@sha256:b379fbc16b8509cd5865daf3391d733bc80b9b522051dfe6fd672897f6d08796
```

-	Total Virtual Size: 204.2 MB (204204305 bytes)
-	Total v2 Content-Length: 81.4 MB (81400599 bytes)

### Layers (8)

#### `843e2bded49837e4846422f3a82a67be3ccc46c3e636e03d8d946c57564468ba`

```dockerfile
ADD file:c7d957020a6ee3df60f2407c7a383cabcfa67d43f6d5151b241b37034f5bc6e0 in /
```

-	Created: Mon, 07 Sep 2015 23:35:05 GMT
-	Docker Version: 1.7.1
-	Virtual Size: 125.2 MB (125159131 bytes)
-	v2 Blob: `sha256:f8efbffe7b954b520805da80ce0cce94e3834482c384c25c8851db98696e7f70`
-	v2 Content-Length: 51.4 MB (51359708 bytes)
-	v2 Last-Modified: Mon, 07 Sep 2015 23:38:06 GMT

#### `8c00acfb017549e44d28098762c3e6296872a1ca9b90385855f1019d84bb0dac`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Mon, 07 Sep 2015 23:35:07 GMT
-	Parent Layer: `843e2bded49837e4846422f3a82a67be3ccc46c3e636e03d8d946c57564468ba`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `8b49fe88b40b6c09bbe751e9b235d1919e704ae1765a304226047bd0b203b3fe`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 08 Sep 2015 15:27:57 GMT
-	Parent Layer: `8c00acfb017549e44d28098762c3e6296872a1ca9b90385855f1019d84bb0dac`
-	Docker Version: 1.7.1
-	Virtual Size: 44.4 MB (44355688 bytes)
-	v2 Blob: `sha256:d6314f6cfecf4fc37f622f99d2a114af91ec678d29c76983249f23995ef77563`
-	v2 Content-Length: 18.5 MB (18538583 bytes)
-	v2 Last-Modified: Thu, 10 Sep 2015 23:36:48 GMT

#### `1e7917dfdd7dc805caa9fe209ae9df3a07529269f4989570f312e72ff4f339c8`

```dockerfile
RUN set -ex   && for key in\
     9554F04D7259F04124DE6B476D5A82AC7E37093B\
     94AE36675C464D64BAFA68DD7434390BDBE9B9C5\
     0034A06D9D9B0064CE8ADF6BF1747F4AD2306D93\
     FD3A5288F042B6850C66B31F09FE44734EB7990E\
     71DCFD284A79C3B38668286BC97EC7A07EDE3FC1\
     DD8F2338BAE7501E3DD5AC78C273792F7D83545D   ; do\
     gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"   ; done
```

-	Created: Thu, 10 Sep 2015 07:52:24 GMT
-	Parent Layer: `8b49fe88b40b6c09bbe751e9b235d1919e704ae1765a304226047bd0b203b3fe`
-	Docker Version: 1.7.1
-	Virtual Size: 39.4 KB (39419 bytes)
-	v2 Blob: `sha256:20f9453d177242021cc6799c74fa2a47f6687a3144251dcb13909e6e8edd0d96`
-	v2 Content-Length: 19.9 KB (19856 bytes)
-	v2 Last-Modified: Fri, 11 Sep 2015 04:39:29 GMT

#### `a2f363d07640f912e4ce880341f1c4a88ce12edaf9be3668776f45da3ca5c73d`

```dockerfile
ENV NPM_CONFIG_LOGLEVEL=info
```

-	Created: Thu, 10 Sep 2015 07:52:25 GMT
-	Parent Layer: `1e7917dfdd7dc805caa9fe209ae9df3a07529269f4989570f312e72ff4f339c8`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `b28dd1c16b74874e66cc509537bbbc59f9c2910384feefe315f930d43fecee9f`

```dockerfile
ENV IOJS_VERSION=3.3.0
```

-	Created: Thu, 10 Sep 2015 07:57:43 GMT
-	Parent Layer: `a2f363d07640f912e4ce880341f1c4a88ce12edaf9be3668776f45da3ca5c73d`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `e55726425149363c861ad6c5ade5b136ce1687a3824643aa3d847bc7acc377cc`

```dockerfile
RUN curl -SLO "https://iojs.org/dist/v$IOJS_VERSION/iojs-v$IOJS_VERSION-linux-x64.tar.gz"   && curl -SLO "https://iojs.org/dist/v$IOJS_VERSION/SHASUMS256.txt.asc"   && gpg --verify SHASUMS256.txt.asc   && grep " iojs-v$IOJS_VERSION-linux-x64.tar.gz\$" SHASUMS256.txt.asc | sha256sum -c -   && tar -xzf "iojs-v$IOJS_VERSION-linux-x64.tar.gz" -C /usr/local --strip-components=1   && rm "iojs-v$IOJS_VERSION-linux-x64.tar.gz" SHASUMS256.txt.asc
```

-	Created: Thu, 10 Sep 2015 07:57:50 GMT
-	Parent Layer: `b28dd1c16b74874e66cc509537bbbc59f9c2910384feefe315f930d43fecee9f`
-	Docker Version: 1.7.1
-	Virtual Size: 34.7 MB (34650067 bytes)
-	v2 Blob: `sha256:85c960f80f7078f5a6f85cfeac2e6ada6e1eabbc8bd85c36db6f0d981786532a`
-	v2 Content-Length: 11.5 MB (11482324 bytes)
-	v2 Last-Modified: Fri, 11 Sep 2015 04:50:48 GMT

#### `afa96cc0bfbd5eeb372091abd7558dab5cdc25d5b40ab2b6fb58e86c13425267`

```dockerfile
CMD ["iojs"]
```

-	Created: Thu, 10 Sep 2015 07:57:51 GMT
-	Parent Layer: `e55726425149363c861ad6c5ade5b136ce1687a3824643aa3d847bc7acc377cc`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

## `iojs:slim`

```console
$ docker pull library/iojs@sha256:48b83ef88d4844e1a6b8aa1c1535c91f754c6f0fef5931c2586d601d25b13493
```

-	Total Virtual Size: 204.2 MB (204204305 bytes)
-	Total v2 Content-Length: 81.4 MB (81400599 bytes)

### Layers (8)

#### `843e2bded49837e4846422f3a82a67be3ccc46c3e636e03d8d946c57564468ba`

```dockerfile
ADD file:c7d957020a6ee3df60f2407c7a383cabcfa67d43f6d5151b241b37034f5bc6e0 in /
```

-	Created: Mon, 07 Sep 2015 23:35:05 GMT
-	Docker Version: 1.7.1
-	Virtual Size: 125.2 MB (125159131 bytes)
-	v2 Blob: `sha256:f8efbffe7b954b520805da80ce0cce94e3834482c384c25c8851db98696e7f70`
-	v2 Content-Length: 51.4 MB (51359708 bytes)
-	v2 Last-Modified: Mon, 07 Sep 2015 23:38:06 GMT

#### `8c00acfb017549e44d28098762c3e6296872a1ca9b90385855f1019d84bb0dac`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Mon, 07 Sep 2015 23:35:07 GMT
-	Parent Layer: `843e2bded49837e4846422f3a82a67be3ccc46c3e636e03d8d946c57564468ba`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `8b49fe88b40b6c09bbe751e9b235d1919e704ae1765a304226047bd0b203b3fe`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 08 Sep 2015 15:27:57 GMT
-	Parent Layer: `8c00acfb017549e44d28098762c3e6296872a1ca9b90385855f1019d84bb0dac`
-	Docker Version: 1.7.1
-	Virtual Size: 44.4 MB (44355688 bytes)
-	v2 Blob: `sha256:d6314f6cfecf4fc37f622f99d2a114af91ec678d29c76983249f23995ef77563`
-	v2 Content-Length: 18.5 MB (18538583 bytes)
-	v2 Last-Modified: Thu, 10 Sep 2015 23:36:48 GMT

#### `1e7917dfdd7dc805caa9fe209ae9df3a07529269f4989570f312e72ff4f339c8`

```dockerfile
RUN set -ex   && for key in\
     9554F04D7259F04124DE6B476D5A82AC7E37093B\
     94AE36675C464D64BAFA68DD7434390BDBE9B9C5\
     0034A06D9D9B0064CE8ADF6BF1747F4AD2306D93\
     FD3A5288F042B6850C66B31F09FE44734EB7990E\
     71DCFD284A79C3B38668286BC97EC7A07EDE3FC1\
     DD8F2338BAE7501E3DD5AC78C273792F7D83545D   ; do\
     gpg --keyserver ha.pool.sks-keyservers.net --recv-keys "$key"   ; done
```

-	Created: Thu, 10 Sep 2015 07:52:24 GMT
-	Parent Layer: `8b49fe88b40b6c09bbe751e9b235d1919e704ae1765a304226047bd0b203b3fe`
-	Docker Version: 1.7.1
-	Virtual Size: 39.4 KB (39419 bytes)
-	v2 Blob: `sha256:20f9453d177242021cc6799c74fa2a47f6687a3144251dcb13909e6e8edd0d96`
-	v2 Content-Length: 19.9 KB (19856 bytes)
-	v2 Last-Modified: Fri, 11 Sep 2015 04:39:29 GMT

#### `a2f363d07640f912e4ce880341f1c4a88ce12edaf9be3668776f45da3ca5c73d`

```dockerfile
ENV NPM_CONFIG_LOGLEVEL=info
```

-	Created: Thu, 10 Sep 2015 07:52:25 GMT
-	Parent Layer: `1e7917dfdd7dc805caa9fe209ae9df3a07529269f4989570f312e72ff4f339c8`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `b28dd1c16b74874e66cc509537bbbc59f9c2910384feefe315f930d43fecee9f`

```dockerfile
ENV IOJS_VERSION=3.3.0
```

-	Created: Thu, 10 Sep 2015 07:57:43 GMT
-	Parent Layer: `a2f363d07640f912e4ce880341f1c4a88ce12edaf9be3668776f45da3ca5c73d`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `e55726425149363c861ad6c5ade5b136ce1687a3824643aa3d847bc7acc377cc`

```dockerfile
RUN curl -SLO "https://iojs.org/dist/v$IOJS_VERSION/iojs-v$IOJS_VERSION-linux-x64.tar.gz"   && curl -SLO "https://iojs.org/dist/v$IOJS_VERSION/SHASUMS256.txt.asc"   && gpg --verify SHASUMS256.txt.asc   && grep " iojs-v$IOJS_VERSION-linux-x64.tar.gz\$" SHASUMS256.txt.asc | sha256sum -c -   && tar -xzf "iojs-v$IOJS_VERSION-linux-x64.tar.gz" -C /usr/local --strip-components=1   && rm "iojs-v$IOJS_VERSION-linux-x64.tar.gz" SHASUMS256.txt.asc
```

-	Created: Thu, 10 Sep 2015 07:57:50 GMT
-	Parent Layer: `b28dd1c16b74874e66cc509537bbbc59f9c2910384feefe315f930d43fecee9f`
-	Docker Version: 1.7.1
-	Virtual Size: 34.7 MB (34650067 bytes)
-	v2 Blob: `sha256:85c960f80f7078f5a6f85cfeac2e6ada6e1eabbc8bd85c36db6f0d981786532a`
-	v2 Content-Length: 11.5 MB (11482324 bytes)
-	v2 Last-Modified: Fri, 11 Sep 2015 04:50:48 GMT

#### `afa96cc0bfbd5eeb372091abd7558dab5cdc25d5b40ab2b6fb58e86c13425267`

```dockerfile
CMD ["iojs"]
```

-	Created: Thu, 10 Sep 2015 07:57:51 GMT
-	Parent Layer: `e55726425149363c861ad6c5ade5b136ce1687a3824643aa3d847bc7acc377cc`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT
