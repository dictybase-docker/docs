<!-- THIS FILE IS GENERATED VIA '.template-helpers/generate-tag-details.pl' -->

# Tags of `python`

-	[`python:2.7.10`](#python2710)
-	[`python:2.7`](#python27)
-	[`python:2`](#python2)
-	[`python:2.7.10-onbuild`](#python2710-onbuild)
-	[`python:2.7-onbuild`](#python27-onbuild)
-	[`python:2-onbuild`](#python2-onbuild)
-	[`python:2.7.10-slim`](#python2710-slim)
-	[`python:2.7-slim`](#python27-slim)
-	[`python:2-slim`](#python2-slim)
-	[`python:2.7.10-wheezy`](#python2710-wheezy)
-	[`python:2.7-wheezy`](#python27-wheezy)
-	[`python:2-wheezy`](#python2-wheezy)
-	[`python:3.2.6`](#python326)
-	[`python:3.2`](#python32)
-	[`python:3.2.6-onbuild`](#python326-onbuild)
-	[`python:3.2-onbuild`](#python32-onbuild)
-	[`python:3.2.6-slim`](#python326-slim)
-	[`python:3.2-slim`](#python32-slim)
-	[`python:3.2.6-wheezy`](#python326-wheezy)
-	[`python:3.2-wheezy`](#python32-wheezy)
-	[`python:3.3.6`](#python336)
-	[`python:3.3`](#python33)
-	[`python:3.3.6-onbuild`](#python336-onbuild)
-	[`python:3.3-onbuild`](#python33-onbuild)
-	[`python:3.3.6-slim`](#python336-slim)
-	[`python:3.3-slim`](#python33-slim)
-	[`python:3.3.6-wheezy`](#python336-wheezy)
-	[`python:3.3-wheezy`](#python33-wheezy)
-	[`python:3.4.3`](#python343)
-	[`python:3.4`](#python34)
-	[`python:3`](#python3)
-	[`python:latest`](#pythonlatest)
-	[`python:3.4.3-onbuild`](#python343-onbuild)
-	[`python:3.4-onbuild`](#python34-onbuild)
-	[`python:3-onbuild`](#python3-onbuild)
-	[`python:onbuild`](#pythononbuild)
-	[`python:3.4.3-slim`](#python343-slim)
-	[`python:3.4-slim`](#python34-slim)
-	[`python:3-slim`](#python3-slim)
-	[`python:slim`](#pythonslim)
-	[`python:3.4.3-wheezy`](#python343-wheezy)
-	[`python:3.4-wheezy`](#python34-wheezy)
-	[`python:3-wheezy`](#python3-wheezy)
-	[`python:wheezy`](#pythonwheezy)
-	[`python:3.5.0`](#python350)
-	[`python:3.5`](#python35)
-	[`python:3.5.0-onbuild`](#python350-onbuild)
-	[`python:3.5-onbuild`](#python35-onbuild)
-	[`python:3.5.0-slim`](#python350-slim)
-	[`python:3.5-slim`](#python35-slim)

## `python:2.7.10`

```console
$ docker pull library/python@sha256:5c3d0430f7394df83833cad357a6f00e25f963b2003e70a0e9cc94bdeab23f55
```

-	Total Virtual Size: 675.4 MB (675386792 bytes)
-	Total v2 Content-Length: 263.7 MB (263693843 bytes)

### Layers (13)

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
-	v2 Blob: `sha256:b3010ec3eb21ac3df74757a47832fb17395b76ad3a30794074cefd07541d3557`
-	v2 Content-Length: 18.5 MB (18538591 bytes)
-	v2 Last-Modified: Thu, 10 Sep 2015 23:36:30 GMT

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

#### `a7131b97316204530af26e42319aeda8ac44cd5ac2891e5dab45e16deb1e592d`

```dockerfile
RUN apt-get purge -y python.*
```

-	Created: Wed, 09 Sep 2015 20:20:46 GMT
-	Parent Layer: `16b189cc8ce688f9f1d8f1d837fa0891107450a06c795b1cba8f6c33a4454280`
-	Docker Version: 1.7.1
-	Virtual Size: 975.3 KB (975277 bytes)
-	v2 Blob: `sha256:20cdbe5b7a6f64396bcabde9b06c16a0b41e2c7fd39b28eff1ee3670a9f0516e`
-	v2 Content-Length: 220.4 KB (220377 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:29:17 GMT

#### `d7cbb60bc416f832c685b38578b77da5f3716cba15d4bcb45d850809a4c112eb`

```dockerfile
ENV LANG=C.UTF-8
```

-	Created: Wed, 09 Sep 2015 20:20:48 GMT
-	Parent Layer: `a7131b97316204530af26e42319aeda8ac44cd5ac2891e5dab45e16deb1e592d`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `8eac5d040779ffe75f218b4bc61eed4dfe4f3716d5c7aea7882c9c650fd0efaa`

```dockerfile
RUN gpg --keyserver ha.pool.sks-keyservers.net --recv-keys C01E1CAD5EA2C4F0B8E3571504C367C218ADD4FF
```

-	Created: Wed, 09 Sep 2015 20:20:53 GMT
-	Parent Layer: `d7cbb60bc416f832c685b38578b77da5f3716cba15d4bcb45d850809a4c112eb`
-	Docker Version: 1.7.1
-	Virtual Size: 28.1 KB (28050 bytes)
-	v2 Blob: `sha256:1fb2fc13fd7a366fe4977910ecd957b79ecb60dc8ef5222d02b45200c6a9b370`
-	v2 Content-Length: 13.4 KB (13449 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:29:12 GMT

#### `3af13f72bde32692aee049d1b305e0aacdba7277dcc2040532240dd8e0b65cf8`

```dockerfile
ENV PYTHON_VERSION=2.7.10
```

-	Created: Wed, 09 Sep 2015 20:20:54 GMT
-	Parent Layer: `8eac5d040779ffe75f218b4bc61eed4dfe4f3716d5c7aea7882c9c650fd0efaa`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `bca7dd61130c752c4c00a6afe2be273ed3c38ad486276c55ba318a38f09e7089`

```dockerfile
ENV PYTHON_PIP_VERSION=7.1.2
```

-	Created: Wed, 09 Sep 2015 20:20:54 GMT
-	Parent Layer: `3af13f72bde32692aee049d1b305e0aacdba7277dcc2040532240dd8e0b65cf8`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `ff7c8fb1be190607d160352fc579d0bdd9bcd35704878a01ab87fa87704952df`

```dockerfile
RUN set -x \
	&& mkdir -p /usr/src/python \
	&& curl -SL "https://www.python.org/ftp/python/$PYTHON_VERSION/Python-$PYTHON_VERSION.tar.xz" -o python.tar.xz \
	&& curl -SL "https://www.python.org/ftp/python/$PYTHON_VERSION/Python-$PYTHON_VERSION.tar.xz.asc" -o python.tar.xz.asc \
	&& gpg --verify python.tar.xz.asc \
	&& tar -xJC /usr/src/python --strip-components=1 -f python.tar.xz \
	&& rm python.tar.xz* \
	&& cd /usr/src/python \
	&& ./configure --enable-shared --enable-unicode=ucs4 \
	&& make -j$(nproc) \
	&& make install \
	&& ldconfig \
	&& curl -SL 'https://bootstrap.pypa.io/get-pip.py' | python2 \
	&& pip install --no-cache-dir --upgrade pip==$PYTHON_PIP_VERSION \
	&& find /usr/local \
		\( -type d -a -name test -o -name tests \) \
		-o \( -type f -a -name '*.pyc' -o -name '*.pyo' \) \
		-exec rm -rf '{}' + \
	&& rm -rf /usr/src/python
```

-	Created: Wed, 09 Sep 2015 20:23:05 GMT
-	Parent Layer: `bca7dd61130c752c4c00a6afe2be273ed3c38ad486276c55ba318a38f09e7089`
-	Docker Version: 1.7.1
-	Virtual Size: 62.0 MB (62048500 bytes)
-	v2 Blob: `sha256:5f532de33fbc60c1f30009208db0bd3a7ec7ce16fda4bac61d78450887fb340e`
-	v2 Content-Length: 19.6 MB (19635932 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:29:06 GMT

#### `23ea4be6ca0c9b58df5c41c9352f54d1e5547ebdfdb12bb9023a8ea2c7dfa311`

```dockerfile
RUN pip install --no-cache-dir virtualenv
```

-	Created: Wed, 09 Sep 2015 20:23:08 GMT
-	Parent Layer: `ff7c8fb1be190607d160352fc579d0bdd9bcd35704878a01ab87fa87704952df`
-	Docker Version: 1.7.1
-	Virtual Size: 5.9 MB (5850007 bytes)
-	v2 Blob: `sha256:96e342cb597dbc9c01c8cb3115f2880f514f39e77d52cd7c5a34c49982966048`
-	v2 Content-Length: 3.1 MB (3054961 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:28:53 GMT

#### `7a7d87336a3328623e3fb332a8752b940097aec03e4d39804721bfda2fa2a08d`

```dockerfile
CMD ["python2"]
```

-	Created: Wed, 09 Sep 2015 20:23:08 GMT
-	Parent Layer: `23ea4be6ca0c9b58df5c41c9352f54d1e5547ebdfdb12bb9023a8ea2c7dfa311`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

## `python:2.7`

```console
$ docker pull library/python@sha256:7c251c89747a4ce208029557f79a9d35a5a7f023e57dc254b1bafd3c42009378
```

-	Total Virtual Size: 675.4 MB (675386792 bytes)
-	Total v2 Content-Length: 263.7 MB (263693843 bytes)

### Layers (13)

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
-	v2 Blob: `sha256:b3010ec3eb21ac3df74757a47832fb17395b76ad3a30794074cefd07541d3557`
-	v2 Content-Length: 18.5 MB (18538591 bytes)
-	v2 Last-Modified: Thu, 10 Sep 2015 23:36:30 GMT

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

#### `a7131b97316204530af26e42319aeda8ac44cd5ac2891e5dab45e16deb1e592d`

```dockerfile
RUN apt-get purge -y python.*
```

-	Created: Wed, 09 Sep 2015 20:20:46 GMT
-	Parent Layer: `16b189cc8ce688f9f1d8f1d837fa0891107450a06c795b1cba8f6c33a4454280`
-	Docker Version: 1.7.1
-	Virtual Size: 975.3 KB (975277 bytes)
-	v2 Blob: `sha256:20cdbe5b7a6f64396bcabde9b06c16a0b41e2c7fd39b28eff1ee3670a9f0516e`
-	v2 Content-Length: 220.4 KB (220377 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:29:17 GMT

#### `d7cbb60bc416f832c685b38578b77da5f3716cba15d4bcb45d850809a4c112eb`

```dockerfile
ENV LANG=C.UTF-8
```

-	Created: Wed, 09 Sep 2015 20:20:48 GMT
-	Parent Layer: `a7131b97316204530af26e42319aeda8ac44cd5ac2891e5dab45e16deb1e592d`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `8eac5d040779ffe75f218b4bc61eed4dfe4f3716d5c7aea7882c9c650fd0efaa`

```dockerfile
RUN gpg --keyserver ha.pool.sks-keyservers.net --recv-keys C01E1CAD5EA2C4F0B8E3571504C367C218ADD4FF
```

-	Created: Wed, 09 Sep 2015 20:20:53 GMT
-	Parent Layer: `d7cbb60bc416f832c685b38578b77da5f3716cba15d4bcb45d850809a4c112eb`
-	Docker Version: 1.7.1
-	Virtual Size: 28.1 KB (28050 bytes)
-	v2 Blob: `sha256:1fb2fc13fd7a366fe4977910ecd957b79ecb60dc8ef5222d02b45200c6a9b370`
-	v2 Content-Length: 13.4 KB (13449 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:29:12 GMT

#### `3af13f72bde32692aee049d1b305e0aacdba7277dcc2040532240dd8e0b65cf8`

```dockerfile
ENV PYTHON_VERSION=2.7.10
```

-	Created: Wed, 09 Sep 2015 20:20:54 GMT
-	Parent Layer: `8eac5d040779ffe75f218b4bc61eed4dfe4f3716d5c7aea7882c9c650fd0efaa`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `bca7dd61130c752c4c00a6afe2be273ed3c38ad486276c55ba318a38f09e7089`

```dockerfile
ENV PYTHON_PIP_VERSION=7.1.2
```

-	Created: Wed, 09 Sep 2015 20:20:54 GMT
-	Parent Layer: `3af13f72bde32692aee049d1b305e0aacdba7277dcc2040532240dd8e0b65cf8`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `ff7c8fb1be190607d160352fc579d0bdd9bcd35704878a01ab87fa87704952df`

```dockerfile
RUN set -x \
	&& mkdir -p /usr/src/python \
	&& curl -SL "https://www.python.org/ftp/python/$PYTHON_VERSION/Python-$PYTHON_VERSION.tar.xz" -o python.tar.xz \
	&& curl -SL "https://www.python.org/ftp/python/$PYTHON_VERSION/Python-$PYTHON_VERSION.tar.xz.asc" -o python.tar.xz.asc \
	&& gpg --verify python.tar.xz.asc \
	&& tar -xJC /usr/src/python --strip-components=1 -f python.tar.xz \
	&& rm python.tar.xz* \
	&& cd /usr/src/python \
	&& ./configure --enable-shared --enable-unicode=ucs4 \
	&& make -j$(nproc) \
	&& make install \
	&& ldconfig \
	&& curl -SL 'https://bootstrap.pypa.io/get-pip.py' | python2 \
	&& pip install --no-cache-dir --upgrade pip==$PYTHON_PIP_VERSION \
	&& find /usr/local \
		\( -type d -a -name test -o -name tests \) \
		-o \( -type f -a -name '*.pyc' -o -name '*.pyo' \) \
		-exec rm -rf '{}' + \
	&& rm -rf /usr/src/python
```

-	Created: Wed, 09 Sep 2015 20:23:05 GMT
-	Parent Layer: `bca7dd61130c752c4c00a6afe2be273ed3c38ad486276c55ba318a38f09e7089`
-	Docker Version: 1.7.1
-	Virtual Size: 62.0 MB (62048500 bytes)
-	v2 Blob: `sha256:5f532de33fbc60c1f30009208db0bd3a7ec7ce16fda4bac61d78450887fb340e`
-	v2 Content-Length: 19.6 MB (19635932 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:29:06 GMT

#### `23ea4be6ca0c9b58df5c41c9352f54d1e5547ebdfdb12bb9023a8ea2c7dfa311`

```dockerfile
RUN pip install --no-cache-dir virtualenv
```

-	Created: Wed, 09 Sep 2015 20:23:08 GMT
-	Parent Layer: `ff7c8fb1be190607d160352fc579d0bdd9bcd35704878a01ab87fa87704952df`
-	Docker Version: 1.7.1
-	Virtual Size: 5.9 MB (5850007 bytes)
-	v2 Blob: `sha256:96e342cb597dbc9c01c8cb3115f2880f514f39e77d52cd7c5a34c49982966048`
-	v2 Content-Length: 3.1 MB (3054961 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:28:53 GMT

#### `7a7d87336a3328623e3fb332a8752b940097aec03e4d39804721bfda2fa2a08d`

```dockerfile
CMD ["python2"]
```

-	Created: Wed, 09 Sep 2015 20:23:08 GMT
-	Parent Layer: `23ea4be6ca0c9b58df5c41c9352f54d1e5547ebdfdb12bb9023a8ea2c7dfa311`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

## `python:2`

```console
$ docker pull library/python@sha256:3a1e82d95d0e75677cdac237b0174425d8ae94dd11d1ef14db73075f1e34c06c
```

-	Total Virtual Size: 675.4 MB (675386792 bytes)
-	Total v2 Content-Length: 263.7 MB (263693843 bytes)

### Layers (13)

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
-	v2 Blob: `sha256:b3010ec3eb21ac3df74757a47832fb17395b76ad3a30794074cefd07541d3557`
-	v2 Content-Length: 18.5 MB (18538591 bytes)
-	v2 Last-Modified: Thu, 10 Sep 2015 23:36:30 GMT

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

#### `a7131b97316204530af26e42319aeda8ac44cd5ac2891e5dab45e16deb1e592d`

```dockerfile
RUN apt-get purge -y python.*
```

-	Created: Wed, 09 Sep 2015 20:20:46 GMT
-	Parent Layer: `16b189cc8ce688f9f1d8f1d837fa0891107450a06c795b1cba8f6c33a4454280`
-	Docker Version: 1.7.1
-	Virtual Size: 975.3 KB (975277 bytes)
-	v2 Blob: `sha256:20cdbe5b7a6f64396bcabde9b06c16a0b41e2c7fd39b28eff1ee3670a9f0516e`
-	v2 Content-Length: 220.4 KB (220377 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:29:17 GMT

#### `d7cbb60bc416f832c685b38578b77da5f3716cba15d4bcb45d850809a4c112eb`

```dockerfile
ENV LANG=C.UTF-8
```

-	Created: Wed, 09 Sep 2015 20:20:48 GMT
-	Parent Layer: `a7131b97316204530af26e42319aeda8ac44cd5ac2891e5dab45e16deb1e592d`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `8eac5d040779ffe75f218b4bc61eed4dfe4f3716d5c7aea7882c9c650fd0efaa`

```dockerfile
RUN gpg --keyserver ha.pool.sks-keyservers.net --recv-keys C01E1CAD5EA2C4F0B8E3571504C367C218ADD4FF
```

-	Created: Wed, 09 Sep 2015 20:20:53 GMT
-	Parent Layer: `d7cbb60bc416f832c685b38578b77da5f3716cba15d4bcb45d850809a4c112eb`
-	Docker Version: 1.7.1
-	Virtual Size: 28.1 KB (28050 bytes)
-	v2 Blob: `sha256:1fb2fc13fd7a366fe4977910ecd957b79ecb60dc8ef5222d02b45200c6a9b370`
-	v2 Content-Length: 13.4 KB (13449 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:29:12 GMT

#### `3af13f72bde32692aee049d1b305e0aacdba7277dcc2040532240dd8e0b65cf8`

```dockerfile
ENV PYTHON_VERSION=2.7.10
```

-	Created: Wed, 09 Sep 2015 20:20:54 GMT
-	Parent Layer: `8eac5d040779ffe75f218b4bc61eed4dfe4f3716d5c7aea7882c9c650fd0efaa`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `bca7dd61130c752c4c00a6afe2be273ed3c38ad486276c55ba318a38f09e7089`

```dockerfile
ENV PYTHON_PIP_VERSION=7.1.2
```

-	Created: Wed, 09 Sep 2015 20:20:54 GMT
-	Parent Layer: `3af13f72bde32692aee049d1b305e0aacdba7277dcc2040532240dd8e0b65cf8`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `ff7c8fb1be190607d160352fc579d0bdd9bcd35704878a01ab87fa87704952df`

```dockerfile
RUN set -x \
	&& mkdir -p /usr/src/python \
	&& curl -SL "https://www.python.org/ftp/python/$PYTHON_VERSION/Python-$PYTHON_VERSION.tar.xz" -o python.tar.xz \
	&& curl -SL "https://www.python.org/ftp/python/$PYTHON_VERSION/Python-$PYTHON_VERSION.tar.xz.asc" -o python.tar.xz.asc \
	&& gpg --verify python.tar.xz.asc \
	&& tar -xJC /usr/src/python --strip-components=1 -f python.tar.xz \
	&& rm python.tar.xz* \
	&& cd /usr/src/python \
	&& ./configure --enable-shared --enable-unicode=ucs4 \
	&& make -j$(nproc) \
	&& make install \
	&& ldconfig \
	&& curl -SL 'https://bootstrap.pypa.io/get-pip.py' | python2 \
	&& pip install --no-cache-dir --upgrade pip==$PYTHON_PIP_VERSION \
	&& find /usr/local \
		\( -type d -a -name test -o -name tests \) \
		-o \( -type f -a -name '*.pyc' -o -name '*.pyo' \) \
		-exec rm -rf '{}' + \
	&& rm -rf /usr/src/python
```

-	Created: Wed, 09 Sep 2015 20:23:05 GMT
-	Parent Layer: `bca7dd61130c752c4c00a6afe2be273ed3c38ad486276c55ba318a38f09e7089`
-	Docker Version: 1.7.1
-	Virtual Size: 62.0 MB (62048500 bytes)
-	v2 Blob: `sha256:5f532de33fbc60c1f30009208db0bd3a7ec7ce16fda4bac61d78450887fb340e`
-	v2 Content-Length: 19.6 MB (19635932 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:29:06 GMT

#### `23ea4be6ca0c9b58df5c41c9352f54d1e5547ebdfdb12bb9023a8ea2c7dfa311`

```dockerfile
RUN pip install --no-cache-dir virtualenv
```

-	Created: Wed, 09 Sep 2015 20:23:08 GMT
-	Parent Layer: `ff7c8fb1be190607d160352fc579d0bdd9bcd35704878a01ab87fa87704952df`
-	Docker Version: 1.7.1
-	Virtual Size: 5.9 MB (5850007 bytes)
-	v2 Blob: `sha256:96e342cb597dbc9c01c8cb3115f2880f514f39e77d52cd7c5a34c49982966048`
-	v2 Content-Length: 3.1 MB (3054961 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:28:53 GMT

#### `7a7d87336a3328623e3fb332a8752b940097aec03e4d39804721bfda2fa2a08d`

```dockerfile
CMD ["python2"]
```

-	Created: Wed, 09 Sep 2015 20:23:08 GMT
-	Parent Layer: `23ea4be6ca0c9b58df5c41c9352f54d1e5547ebdfdb12bb9023a8ea2c7dfa311`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

## `python:2.7.10-onbuild`

```console
$ docker pull library/python@sha256:5817e3799d1114534c9a6063b398514ef36e52d4a233eeeb4bfd6fa7d2b18ea6
```

-	Total Virtual Size: 675.4 MB (675386792 bytes)
-	Total v2 Content-Length: 263.7 MB (263694098 bytes)

### Layers (18)

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
-	v2 Blob: `sha256:b3010ec3eb21ac3df74757a47832fb17395b76ad3a30794074cefd07541d3557`
-	v2 Content-Length: 18.5 MB (18538591 bytes)
-	v2 Last-Modified: Thu, 10 Sep 2015 23:36:30 GMT

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

#### `a7131b97316204530af26e42319aeda8ac44cd5ac2891e5dab45e16deb1e592d`

```dockerfile
RUN apt-get purge -y python.*
```

-	Created: Wed, 09 Sep 2015 20:20:46 GMT
-	Parent Layer: `16b189cc8ce688f9f1d8f1d837fa0891107450a06c795b1cba8f6c33a4454280`
-	Docker Version: 1.7.1
-	Virtual Size: 975.3 KB (975277 bytes)
-	v2 Blob: `sha256:20cdbe5b7a6f64396bcabde9b06c16a0b41e2c7fd39b28eff1ee3670a9f0516e`
-	v2 Content-Length: 220.4 KB (220377 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:29:17 GMT

#### `d7cbb60bc416f832c685b38578b77da5f3716cba15d4bcb45d850809a4c112eb`

```dockerfile
ENV LANG=C.UTF-8
```

-	Created: Wed, 09 Sep 2015 20:20:48 GMT
-	Parent Layer: `a7131b97316204530af26e42319aeda8ac44cd5ac2891e5dab45e16deb1e592d`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `8eac5d040779ffe75f218b4bc61eed4dfe4f3716d5c7aea7882c9c650fd0efaa`

```dockerfile
RUN gpg --keyserver ha.pool.sks-keyservers.net --recv-keys C01E1CAD5EA2C4F0B8E3571504C367C218ADD4FF
```

-	Created: Wed, 09 Sep 2015 20:20:53 GMT
-	Parent Layer: `d7cbb60bc416f832c685b38578b77da5f3716cba15d4bcb45d850809a4c112eb`
-	Docker Version: 1.7.1
-	Virtual Size: 28.1 KB (28050 bytes)
-	v2 Blob: `sha256:1fb2fc13fd7a366fe4977910ecd957b79ecb60dc8ef5222d02b45200c6a9b370`
-	v2 Content-Length: 13.4 KB (13449 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:29:12 GMT

#### `3af13f72bde32692aee049d1b305e0aacdba7277dcc2040532240dd8e0b65cf8`

```dockerfile
ENV PYTHON_VERSION=2.7.10
```

-	Created: Wed, 09 Sep 2015 20:20:54 GMT
-	Parent Layer: `8eac5d040779ffe75f218b4bc61eed4dfe4f3716d5c7aea7882c9c650fd0efaa`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `bca7dd61130c752c4c00a6afe2be273ed3c38ad486276c55ba318a38f09e7089`

```dockerfile
ENV PYTHON_PIP_VERSION=7.1.2
```

-	Created: Wed, 09 Sep 2015 20:20:54 GMT
-	Parent Layer: `3af13f72bde32692aee049d1b305e0aacdba7277dcc2040532240dd8e0b65cf8`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `ff7c8fb1be190607d160352fc579d0bdd9bcd35704878a01ab87fa87704952df`

```dockerfile
RUN set -x \
	&& mkdir -p /usr/src/python \
	&& curl -SL "https://www.python.org/ftp/python/$PYTHON_VERSION/Python-$PYTHON_VERSION.tar.xz" -o python.tar.xz \
	&& curl -SL "https://www.python.org/ftp/python/$PYTHON_VERSION/Python-$PYTHON_VERSION.tar.xz.asc" -o python.tar.xz.asc \
	&& gpg --verify python.tar.xz.asc \
	&& tar -xJC /usr/src/python --strip-components=1 -f python.tar.xz \
	&& rm python.tar.xz* \
	&& cd /usr/src/python \
	&& ./configure --enable-shared --enable-unicode=ucs4 \
	&& make -j$(nproc) \
	&& make install \
	&& ldconfig \
	&& curl -SL 'https://bootstrap.pypa.io/get-pip.py' | python2 \
	&& pip install --no-cache-dir --upgrade pip==$PYTHON_PIP_VERSION \
	&& find /usr/local \
		\( -type d -a -name test -o -name tests \) \
		-o \( -type f -a -name '*.pyc' -o -name '*.pyo' \) \
		-exec rm -rf '{}' + \
	&& rm -rf /usr/src/python
```

-	Created: Wed, 09 Sep 2015 20:23:05 GMT
-	Parent Layer: `bca7dd61130c752c4c00a6afe2be273ed3c38ad486276c55ba318a38f09e7089`
-	Docker Version: 1.7.1
-	Virtual Size: 62.0 MB (62048500 bytes)
-	v2 Blob: `sha256:5f532de33fbc60c1f30009208db0bd3a7ec7ce16fda4bac61d78450887fb340e`
-	v2 Content-Length: 19.6 MB (19635932 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:29:06 GMT

#### `23ea4be6ca0c9b58df5c41c9352f54d1e5547ebdfdb12bb9023a8ea2c7dfa311`

```dockerfile
RUN pip install --no-cache-dir virtualenv
```

-	Created: Wed, 09 Sep 2015 20:23:08 GMT
-	Parent Layer: `ff7c8fb1be190607d160352fc579d0bdd9bcd35704878a01ab87fa87704952df`
-	Docker Version: 1.7.1
-	Virtual Size: 5.9 MB (5850007 bytes)
-	v2 Blob: `sha256:96e342cb597dbc9c01c8cb3115f2880f514f39e77d52cd7c5a34c49982966048`
-	v2 Content-Length: 3.1 MB (3054961 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:28:53 GMT

#### `7a7d87336a3328623e3fb332a8752b940097aec03e4d39804721bfda2fa2a08d`

```dockerfile
CMD ["python2"]
```

-	Created: Wed, 09 Sep 2015 20:23:08 GMT
-	Parent Layer: `23ea4be6ca0c9b58df5c41c9352f54d1e5547ebdfdb12bb9023a8ea2c7dfa311`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `3a1c798449742e8039e78a85724861590e79d399fa1eaf5e9f62f02dba739f3f`

```dockerfile
RUN mkdir -p /usr/src/app
```

-	Created: Wed, 09 Sep 2015 20:24:47 GMT
-	Parent Layer: `7a7d87336a3328623e3fb332a8752b940097aec03e4d39804721bfda2fa2a08d`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:0b2878971f17aa155304c7f80c38f4a1fce18836ca344fca0686355270aea3d0`
-	v2 Content-Length: 127.0 B
-	v2 Last-Modified: Wed, 09 Sep 2015 21:35:25 GMT

#### `e0f67a9d744832440dafe0d2db60ea42f173ef99360182e612cb8de1b2a0f4b0`

```dockerfile
WORKDIR /usr/src/app
```

-	Created: Wed, 09 Sep 2015 20:24:47 GMT
-	Parent Layer: `3a1c798449742e8039e78a85724861590e79d399fa1eaf5e9f62f02dba739f3f`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `93d15bdf212a05daf35859d839a8130ef7a604b8d37891fadfdb46d7dda67b15`

```dockerfile
ONBUILD COPY requirements.txt /usr/src/app/
```

-	Created: Wed, 09 Sep 2015 20:24:48 GMT
-	Parent Layer: `e0f67a9d744832440dafe0d2db60ea42f173ef99360182e612cb8de1b2a0f4b0`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `5da6ee6546576a0db5820966e51d0f1fe9353b24a26c4f8b9ac5cf23725d2e35`

```dockerfile
ONBUILD RUN pip install --no-cache-dir -r requirements.txt
```

-	Created: Wed, 09 Sep 2015 20:24:48 GMT
-	Parent Layer: `93d15bdf212a05daf35859d839a8130ef7a604b8d37891fadfdb46d7dda67b15`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `08fb75f58c40b3e63e2beeab45ca5c62d57e37d2d25c0a7250f3954474041423`

```dockerfile
ONBUILD COPY . /usr/src/app
```

-	Created: Wed, 09 Sep 2015 20:24:48 GMT
-	Parent Layer: `5da6ee6546576a0db5820966e51d0f1fe9353b24a26c4f8b9ac5cf23725d2e35`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

## `python:2.7-onbuild`

```console
$ docker pull library/python@sha256:df2d4429eaee910fcdda0e82b980cfda3321c7449d5cf9a7f441ef47d4ae11dd
```

-	Total Virtual Size: 675.4 MB (675386792 bytes)
-	Total v2 Content-Length: 263.7 MB (263694098 bytes)

### Layers (18)

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
-	v2 Blob: `sha256:b3010ec3eb21ac3df74757a47832fb17395b76ad3a30794074cefd07541d3557`
-	v2 Content-Length: 18.5 MB (18538591 bytes)
-	v2 Last-Modified: Thu, 10 Sep 2015 23:36:30 GMT

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

#### `a7131b97316204530af26e42319aeda8ac44cd5ac2891e5dab45e16deb1e592d`

```dockerfile
RUN apt-get purge -y python.*
```

-	Created: Wed, 09 Sep 2015 20:20:46 GMT
-	Parent Layer: `16b189cc8ce688f9f1d8f1d837fa0891107450a06c795b1cba8f6c33a4454280`
-	Docker Version: 1.7.1
-	Virtual Size: 975.3 KB (975277 bytes)
-	v2 Blob: `sha256:20cdbe5b7a6f64396bcabde9b06c16a0b41e2c7fd39b28eff1ee3670a9f0516e`
-	v2 Content-Length: 220.4 KB (220377 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:29:17 GMT

#### `d7cbb60bc416f832c685b38578b77da5f3716cba15d4bcb45d850809a4c112eb`

```dockerfile
ENV LANG=C.UTF-8
```

-	Created: Wed, 09 Sep 2015 20:20:48 GMT
-	Parent Layer: `a7131b97316204530af26e42319aeda8ac44cd5ac2891e5dab45e16deb1e592d`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `8eac5d040779ffe75f218b4bc61eed4dfe4f3716d5c7aea7882c9c650fd0efaa`

```dockerfile
RUN gpg --keyserver ha.pool.sks-keyservers.net --recv-keys C01E1CAD5EA2C4F0B8E3571504C367C218ADD4FF
```

-	Created: Wed, 09 Sep 2015 20:20:53 GMT
-	Parent Layer: `d7cbb60bc416f832c685b38578b77da5f3716cba15d4bcb45d850809a4c112eb`
-	Docker Version: 1.7.1
-	Virtual Size: 28.1 KB (28050 bytes)
-	v2 Blob: `sha256:1fb2fc13fd7a366fe4977910ecd957b79ecb60dc8ef5222d02b45200c6a9b370`
-	v2 Content-Length: 13.4 KB (13449 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:29:12 GMT

#### `3af13f72bde32692aee049d1b305e0aacdba7277dcc2040532240dd8e0b65cf8`

```dockerfile
ENV PYTHON_VERSION=2.7.10
```

-	Created: Wed, 09 Sep 2015 20:20:54 GMT
-	Parent Layer: `8eac5d040779ffe75f218b4bc61eed4dfe4f3716d5c7aea7882c9c650fd0efaa`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `bca7dd61130c752c4c00a6afe2be273ed3c38ad486276c55ba318a38f09e7089`

```dockerfile
ENV PYTHON_PIP_VERSION=7.1.2
```

-	Created: Wed, 09 Sep 2015 20:20:54 GMT
-	Parent Layer: `3af13f72bde32692aee049d1b305e0aacdba7277dcc2040532240dd8e0b65cf8`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `ff7c8fb1be190607d160352fc579d0bdd9bcd35704878a01ab87fa87704952df`

```dockerfile
RUN set -x \
	&& mkdir -p /usr/src/python \
	&& curl -SL "https://www.python.org/ftp/python/$PYTHON_VERSION/Python-$PYTHON_VERSION.tar.xz" -o python.tar.xz \
	&& curl -SL "https://www.python.org/ftp/python/$PYTHON_VERSION/Python-$PYTHON_VERSION.tar.xz.asc" -o python.tar.xz.asc \
	&& gpg --verify python.tar.xz.asc \
	&& tar -xJC /usr/src/python --strip-components=1 -f python.tar.xz \
	&& rm python.tar.xz* \
	&& cd /usr/src/python \
	&& ./configure --enable-shared --enable-unicode=ucs4 \
	&& make -j$(nproc) \
	&& make install \
	&& ldconfig \
	&& curl -SL 'https://bootstrap.pypa.io/get-pip.py' | python2 \
	&& pip install --no-cache-dir --upgrade pip==$PYTHON_PIP_VERSION \
	&& find /usr/local \
		\( -type d -a -name test -o -name tests \) \
		-o \( -type f -a -name '*.pyc' -o -name '*.pyo' \) \
		-exec rm -rf '{}' + \
	&& rm -rf /usr/src/python
```

-	Created: Wed, 09 Sep 2015 20:23:05 GMT
-	Parent Layer: `bca7dd61130c752c4c00a6afe2be273ed3c38ad486276c55ba318a38f09e7089`
-	Docker Version: 1.7.1
-	Virtual Size: 62.0 MB (62048500 bytes)
-	v2 Blob: `sha256:5f532de33fbc60c1f30009208db0bd3a7ec7ce16fda4bac61d78450887fb340e`
-	v2 Content-Length: 19.6 MB (19635932 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:29:06 GMT

#### `23ea4be6ca0c9b58df5c41c9352f54d1e5547ebdfdb12bb9023a8ea2c7dfa311`

```dockerfile
RUN pip install --no-cache-dir virtualenv
```

-	Created: Wed, 09 Sep 2015 20:23:08 GMT
-	Parent Layer: `ff7c8fb1be190607d160352fc579d0bdd9bcd35704878a01ab87fa87704952df`
-	Docker Version: 1.7.1
-	Virtual Size: 5.9 MB (5850007 bytes)
-	v2 Blob: `sha256:96e342cb597dbc9c01c8cb3115f2880f514f39e77d52cd7c5a34c49982966048`
-	v2 Content-Length: 3.1 MB (3054961 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:28:53 GMT

#### `7a7d87336a3328623e3fb332a8752b940097aec03e4d39804721bfda2fa2a08d`

```dockerfile
CMD ["python2"]
```

-	Created: Wed, 09 Sep 2015 20:23:08 GMT
-	Parent Layer: `23ea4be6ca0c9b58df5c41c9352f54d1e5547ebdfdb12bb9023a8ea2c7dfa311`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `3a1c798449742e8039e78a85724861590e79d399fa1eaf5e9f62f02dba739f3f`

```dockerfile
RUN mkdir -p /usr/src/app
```

-	Created: Wed, 09 Sep 2015 20:24:47 GMT
-	Parent Layer: `7a7d87336a3328623e3fb332a8752b940097aec03e4d39804721bfda2fa2a08d`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:0b2878971f17aa155304c7f80c38f4a1fce18836ca344fca0686355270aea3d0`
-	v2 Content-Length: 127.0 B
-	v2 Last-Modified: Wed, 09 Sep 2015 21:35:25 GMT

#### `e0f67a9d744832440dafe0d2db60ea42f173ef99360182e612cb8de1b2a0f4b0`

```dockerfile
WORKDIR /usr/src/app
```

-	Created: Wed, 09 Sep 2015 20:24:47 GMT
-	Parent Layer: `3a1c798449742e8039e78a85724861590e79d399fa1eaf5e9f62f02dba739f3f`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `93d15bdf212a05daf35859d839a8130ef7a604b8d37891fadfdb46d7dda67b15`

```dockerfile
ONBUILD COPY requirements.txt /usr/src/app/
```

-	Created: Wed, 09 Sep 2015 20:24:48 GMT
-	Parent Layer: `e0f67a9d744832440dafe0d2db60ea42f173ef99360182e612cb8de1b2a0f4b0`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `5da6ee6546576a0db5820966e51d0f1fe9353b24a26c4f8b9ac5cf23725d2e35`

```dockerfile
ONBUILD RUN pip install --no-cache-dir -r requirements.txt
```

-	Created: Wed, 09 Sep 2015 20:24:48 GMT
-	Parent Layer: `93d15bdf212a05daf35859d839a8130ef7a604b8d37891fadfdb46d7dda67b15`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `08fb75f58c40b3e63e2beeab45ca5c62d57e37d2d25c0a7250f3954474041423`

```dockerfile
ONBUILD COPY . /usr/src/app
```

-	Created: Wed, 09 Sep 2015 20:24:48 GMT
-	Parent Layer: `5da6ee6546576a0db5820966e51d0f1fe9353b24a26c4f8b9ac5cf23725d2e35`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

## `python:2-onbuild`

```console
$ docker pull library/python@sha256:603f77771b1615ff0f73903c323d96f4f5ca77afe1822ffa6521367f26e19872
```

-	Total Virtual Size: 675.4 MB (675386792 bytes)
-	Total v2 Content-Length: 263.7 MB (263694098 bytes)

### Layers (18)

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
-	v2 Blob: `sha256:b3010ec3eb21ac3df74757a47832fb17395b76ad3a30794074cefd07541d3557`
-	v2 Content-Length: 18.5 MB (18538591 bytes)
-	v2 Last-Modified: Thu, 10 Sep 2015 23:36:30 GMT

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

#### `a7131b97316204530af26e42319aeda8ac44cd5ac2891e5dab45e16deb1e592d`

```dockerfile
RUN apt-get purge -y python.*
```

-	Created: Wed, 09 Sep 2015 20:20:46 GMT
-	Parent Layer: `16b189cc8ce688f9f1d8f1d837fa0891107450a06c795b1cba8f6c33a4454280`
-	Docker Version: 1.7.1
-	Virtual Size: 975.3 KB (975277 bytes)
-	v2 Blob: `sha256:20cdbe5b7a6f64396bcabde9b06c16a0b41e2c7fd39b28eff1ee3670a9f0516e`
-	v2 Content-Length: 220.4 KB (220377 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:29:17 GMT

#### `d7cbb60bc416f832c685b38578b77da5f3716cba15d4bcb45d850809a4c112eb`

```dockerfile
ENV LANG=C.UTF-8
```

-	Created: Wed, 09 Sep 2015 20:20:48 GMT
-	Parent Layer: `a7131b97316204530af26e42319aeda8ac44cd5ac2891e5dab45e16deb1e592d`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `8eac5d040779ffe75f218b4bc61eed4dfe4f3716d5c7aea7882c9c650fd0efaa`

```dockerfile
RUN gpg --keyserver ha.pool.sks-keyservers.net --recv-keys C01E1CAD5EA2C4F0B8E3571504C367C218ADD4FF
```

-	Created: Wed, 09 Sep 2015 20:20:53 GMT
-	Parent Layer: `d7cbb60bc416f832c685b38578b77da5f3716cba15d4bcb45d850809a4c112eb`
-	Docker Version: 1.7.1
-	Virtual Size: 28.1 KB (28050 bytes)
-	v2 Blob: `sha256:1fb2fc13fd7a366fe4977910ecd957b79ecb60dc8ef5222d02b45200c6a9b370`
-	v2 Content-Length: 13.4 KB (13449 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:29:12 GMT

#### `3af13f72bde32692aee049d1b305e0aacdba7277dcc2040532240dd8e0b65cf8`

```dockerfile
ENV PYTHON_VERSION=2.7.10
```

-	Created: Wed, 09 Sep 2015 20:20:54 GMT
-	Parent Layer: `8eac5d040779ffe75f218b4bc61eed4dfe4f3716d5c7aea7882c9c650fd0efaa`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `bca7dd61130c752c4c00a6afe2be273ed3c38ad486276c55ba318a38f09e7089`

```dockerfile
ENV PYTHON_PIP_VERSION=7.1.2
```

-	Created: Wed, 09 Sep 2015 20:20:54 GMT
-	Parent Layer: `3af13f72bde32692aee049d1b305e0aacdba7277dcc2040532240dd8e0b65cf8`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `ff7c8fb1be190607d160352fc579d0bdd9bcd35704878a01ab87fa87704952df`

```dockerfile
RUN set -x \
	&& mkdir -p /usr/src/python \
	&& curl -SL "https://www.python.org/ftp/python/$PYTHON_VERSION/Python-$PYTHON_VERSION.tar.xz" -o python.tar.xz \
	&& curl -SL "https://www.python.org/ftp/python/$PYTHON_VERSION/Python-$PYTHON_VERSION.tar.xz.asc" -o python.tar.xz.asc \
	&& gpg --verify python.tar.xz.asc \
	&& tar -xJC /usr/src/python --strip-components=1 -f python.tar.xz \
	&& rm python.tar.xz* \
	&& cd /usr/src/python \
	&& ./configure --enable-shared --enable-unicode=ucs4 \
	&& make -j$(nproc) \
	&& make install \
	&& ldconfig \
	&& curl -SL 'https://bootstrap.pypa.io/get-pip.py' | python2 \
	&& pip install --no-cache-dir --upgrade pip==$PYTHON_PIP_VERSION \
	&& find /usr/local \
		\( -type d -a -name test -o -name tests \) \
		-o \( -type f -a -name '*.pyc' -o -name '*.pyo' \) \
		-exec rm -rf '{}' + \
	&& rm -rf /usr/src/python
```

-	Created: Wed, 09 Sep 2015 20:23:05 GMT
-	Parent Layer: `bca7dd61130c752c4c00a6afe2be273ed3c38ad486276c55ba318a38f09e7089`
-	Docker Version: 1.7.1
-	Virtual Size: 62.0 MB (62048500 bytes)
-	v2 Blob: `sha256:5f532de33fbc60c1f30009208db0bd3a7ec7ce16fda4bac61d78450887fb340e`
-	v2 Content-Length: 19.6 MB (19635932 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:29:06 GMT

#### `23ea4be6ca0c9b58df5c41c9352f54d1e5547ebdfdb12bb9023a8ea2c7dfa311`

```dockerfile
RUN pip install --no-cache-dir virtualenv
```

-	Created: Wed, 09 Sep 2015 20:23:08 GMT
-	Parent Layer: `ff7c8fb1be190607d160352fc579d0bdd9bcd35704878a01ab87fa87704952df`
-	Docker Version: 1.7.1
-	Virtual Size: 5.9 MB (5850007 bytes)
-	v2 Blob: `sha256:96e342cb597dbc9c01c8cb3115f2880f514f39e77d52cd7c5a34c49982966048`
-	v2 Content-Length: 3.1 MB (3054961 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:28:53 GMT

#### `7a7d87336a3328623e3fb332a8752b940097aec03e4d39804721bfda2fa2a08d`

```dockerfile
CMD ["python2"]
```

-	Created: Wed, 09 Sep 2015 20:23:08 GMT
-	Parent Layer: `23ea4be6ca0c9b58df5c41c9352f54d1e5547ebdfdb12bb9023a8ea2c7dfa311`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `3a1c798449742e8039e78a85724861590e79d399fa1eaf5e9f62f02dba739f3f`

```dockerfile
RUN mkdir -p /usr/src/app
```

-	Created: Wed, 09 Sep 2015 20:24:47 GMT
-	Parent Layer: `7a7d87336a3328623e3fb332a8752b940097aec03e4d39804721bfda2fa2a08d`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:0b2878971f17aa155304c7f80c38f4a1fce18836ca344fca0686355270aea3d0`
-	v2 Content-Length: 127.0 B
-	v2 Last-Modified: Wed, 09 Sep 2015 21:35:25 GMT

#### `e0f67a9d744832440dafe0d2db60ea42f173ef99360182e612cb8de1b2a0f4b0`

```dockerfile
WORKDIR /usr/src/app
```

-	Created: Wed, 09 Sep 2015 20:24:47 GMT
-	Parent Layer: `3a1c798449742e8039e78a85724861590e79d399fa1eaf5e9f62f02dba739f3f`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `93d15bdf212a05daf35859d839a8130ef7a604b8d37891fadfdb46d7dda67b15`

```dockerfile
ONBUILD COPY requirements.txt /usr/src/app/
```

-	Created: Wed, 09 Sep 2015 20:24:48 GMT
-	Parent Layer: `e0f67a9d744832440dafe0d2db60ea42f173ef99360182e612cb8de1b2a0f4b0`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `5da6ee6546576a0db5820966e51d0f1fe9353b24a26c4f8b9ac5cf23725d2e35`

```dockerfile
ONBUILD RUN pip install --no-cache-dir -r requirements.txt
```

-	Created: Wed, 09 Sep 2015 20:24:48 GMT
-	Parent Layer: `93d15bdf212a05daf35859d839a8130ef7a604b8d37891fadfdb46d7dda67b15`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `08fb75f58c40b3e63e2beeab45ca5c62d57e37d2d25c0a7250f3954474041423`

```dockerfile
ONBUILD COPY . /usr/src/app
```

-	Created: Wed, 09 Sep 2015 20:24:48 GMT
-	Parent Layer: `5da6ee6546576a0db5820966e51d0f1fe9353b24a26c4f8b9ac5cf23725d2e35`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

## `python:2.7.10-slim`

```console
$ docker pull library/python@sha256:dd35a5914d4939ca7605ddf24bb23f2fc55e6002ea61dddb0e163da22bc73d72
```

-	Total Virtual Size: 205.0 MB (204980219 bytes)
-	Total v2 Content-Length: 79.5 MB (79505182 bytes)

### Layers (11)

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

#### `b724829f2124ff81839118c0bb053554742dae49bcf23847b98264867e4da862`

```dockerfile
RUN apt-get purge -y python.*
```

-	Created: Wed, 09 Sep 2015 20:26:09 GMT
-	Parent Layer: `8c00acfb017549e44d28098762c3e6296872a1ca9b90385855f1019d84bb0dac`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `dad2fc2df4957c05b555a45d00adeaaf624ccce5d9dd557ce4c8548ca40f39f0`

```dockerfile
ENV LANG=C.UTF-8
```

-	Created: Wed, 09 Sep 2015 20:26:10 GMT
-	Parent Layer: `b724829f2124ff81839118c0bb053554742dae49bcf23847b98264867e4da862`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `b4b1929946879d72f7304c436913698e312741961589842913329eb8d746fefa`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		libsqlite3-0 \
		libssl1.0.0 \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Wed, 09 Sep 2015 20:26:51 GMT
-	Parent Layer: `dad2fc2df4957c05b555a45d00adeaaf624ccce5d9dd557ce4c8548ca40f39f0`
-	Docker Version: 1.7.1
-	Virtual Size: 7.4 MB (7441496 bytes)
-	v2 Blob: `sha256:aebbd0bd409f97875c3b3bcf8f57e315ba2ef8d3c4a54f81a7f71cfcf80bf4c9`
-	v2 Content-Length: 3.3 MB (3316296 bytes)
-	v2 Last-Modified: Fri, 11 Sep 2015 00:01:36 GMT

#### `de7e773f73d4fbbd118a704ce258377d862fe9c5027ea213da73e5fde9a79704`

```dockerfile
RUN gpg --keyserver ha.pool.sks-keyservers.net --recv-keys C01E1CAD5EA2C4F0B8E3571504C367C218ADD4FF
```

-	Created: Wed, 09 Sep 2015 20:26:59 GMT
-	Parent Layer: `b4b1929946879d72f7304c436913698e312741961589842913329eb8d746fefa`
-	Docker Version: 1.7.1
-	Virtual Size: 28.1 KB (28050 bytes)
-	v2 Blob: `sha256:6ca940a2c7e30bd9f49c14a42b99eae2fcabd435aa2075db460151a14c7ca40c`
-	v2 Content-Length: 13.4 KB (13450 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:37:01 GMT

#### `8b3e6baef3ab76122d1b983dff3d6df416dddec66601f03688a3ccfdfd0a8001`

```dockerfile
ENV PYTHON_VERSION=2.7.10
```

-	Created: Wed, 09 Sep 2015 20:27:00 GMT
-	Parent Layer: `de7e773f73d4fbbd118a704ce258377d862fe9c5027ea213da73e5fde9a79704`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `f038ec4961dd682c5475569c1d28edfab30992a3d3c61067ee0e609267808ecc`

```dockerfile
ENV PYTHON_PIP_VERSION=7.1.2
```

-	Created: Wed, 09 Sep 2015 20:27:00 GMT
-	Parent Layer: `8b3e6baef3ab76122d1b983dff3d6df416dddec66601f03688a3ccfdfd0a8001`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `af086d031545186d1213bdeced5465da5d6491443814999cf98d2a1927b6282e`

```dockerfile
RUN set -x \
	&& buildDeps=' \
		curl \
		gcc \
		libbz2-dev \
		libc6-dev \
		libncurses-dev \
		libreadline-dev \
		libsqlite3-dev \
		libssl-dev \
		make \
		xz-utils \
		zlib1g-dev \
	' \
	&& apt-get update && apt-get install -y $buildDeps --no-install-recommends && rm -rf /var/lib/apt/lists/* \
	&& mkdir -p /usr/src/python \
	&& curl -SL "https://www.python.org/ftp/python/$PYTHON_VERSION/Python-$PYTHON_VERSION.tar.xz" -o python.tar.xz \
	&& curl -SL "https://www.python.org/ftp/python/$PYTHON_VERSION/Python-$PYTHON_VERSION.tar.xz.asc" -o python.tar.xz.asc \
	&& gpg --verify python.tar.xz.asc \
	&& tar -xJC /usr/src/python --strip-components=1 -f python.tar.xz \
	&& rm python.tar.xz* \
	&& cd /usr/src/python \
	&& ./configure --enable-shared --enable-unicode=ucs4 \
	&& make -j$(nproc) \
	&& make install \
	&& ldconfig \
	&& curl -SL 'https://bootstrap.pypa.io/get-pip.py' | python2 \
	&& pip install --no-cache-dir --upgrade pip==$PYTHON_PIP_VERSION \
	&& find /usr/local \
		\( -type d -a -name test -o -name tests \) \
		-o \( -type f -a -name '*.pyc' -o -name '*.pyo' \) \
		-exec rm -rf '{}' + \
	&& apt-get purge -y --auto-remove $buildDeps \
	&& rm -rf /usr/src/python
```

-	Created: Wed, 09 Sep 2015 20:30:07 GMT
-	Parent Layer: `f038ec4961dd682c5475569c1d28edfab30992a3d3c61067ee0e609267808ecc`
-	Docker Version: 1.7.1
-	Virtual Size: 66.5 MB (66501539 bytes)
-	v2 Blob: `sha256:52ceabbfe33323c545565648ee5c0d8562232ffbc95da1e119884db5e2a4fbad`
-	v2 Content-Length: 21.8 MB (21760609 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:36:54 GMT

#### `be949d27143de33cc70b44a705a1a5d5cc54f259f11da79c83ee980639fc03ba`

```dockerfile
RUN pip install --no-cache-dir virtualenv
```

-	Created: Wed, 09 Sep 2015 20:30:12 GMT
-	Parent Layer: `af086d031545186d1213bdeced5465da5d6491443814999cf98d2a1927b6282e`
-	Docker Version: 1.7.1
-	Virtual Size: 5.9 MB (5850003 bytes)
-	v2 Blob: `sha256:ef24d33cd3204b4ffb6a1f6e4f313471e4e7133698a83f37389b16b209fdcde8`
-	v2 Content-Length: 3.1 MB (3054927 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:36:36 GMT

#### `1a977112ac217e1749db38eb598442e8b797439bc22bb2ef8d9d4f94424a736d`

```dockerfile
CMD ["python2"]
```

-	Created: Wed, 09 Sep 2015 20:30:14 GMT
-	Parent Layer: `be949d27143de33cc70b44a705a1a5d5cc54f259f11da79c83ee980639fc03ba`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

## `python:2.7-slim`

```console
$ docker pull library/python@sha256:2fa34483015a239aea56a9e0bb9d1e3aaae76d9b1be4256a365c1015be4ad2bc
```

-	Total Virtual Size: 205.0 MB (204980219 bytes)
-	Total v2 Content-Length: 79.5 MB (79505182 bytes)

### Layers (11)

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

#### `b724829f2124ff81839118c0bb053554742dae49bcf23847b98264867e4da862`

```dockerfile
RUN apt-get purge -y python.*
```

-	Created: Wed, 09 Sep 2015 20:26:09 GMT
-	Parent Layer: `8c00acfb017549e44d28098762c3e6296872a1ca9b90385855f1019d84bb0dac`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `dad2fc2df4957c05b555a45d00adeaaf624ccce5d9dd557ce4c8548ca40f39f0`

```dockerfile
ENV LANG=C.UTF-8
```

-	Created: Wed, 09 Sep 2015 20:26:10 GMT
-	Parent Layer: `b724829f2124ff81839118c0bb053554742dae49bcf23847b98264867e4da862`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `b4b1929946879d72f7304c436913698e312741961589842913329eb8d746fefa`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		libsqlite3-0 \
		libssl1.0.0 \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Wed, 09 Sep 2015 20:26:51 GMT
-	Parent Layer: `dad2fc2df4957c05b555a45d00adeaaf624ccce5d9dd557ce4c8548ca40f39f0`
-	Docker Version: 1.7.1
-	Virtual Size: 7.4 MB (7441496 bytes)
-	v2 Blob: `sha256:aebbd0bd409f97875c3b3bcf8f57e315ba2ef8d3c4a54f81a7f71cfcf80bf4c9`
-	v2 Content-Length: 3.3 MB (3316296 bytes)
-	v2 Last-Modified: Fri, 11 Sep 2015 00:01:36 GMT

#### `de7e773f73d4fbbd118a704ce258377d862fe9c5027ea213da73e5fde9a79704`

```dockerfile
RUN gpg --keyserver ha.pool.sks-keyservers.net --recv-keys C01E1CAD5EA2C4F0B8E3571504C367C218ADD4FF
```

-	Created: Wed, 09 Sep 2015 20:26:59 GMT
-	Parent Layer: `b4b1929946879d72f7304c436913698e312741961589842913329eb8d746fefa`
-	Docker Version: 1.7.1
-	Virtual Size: 28.1 KB (28050 bytes)
-	v2 Blob: `sha256:6ca940a2c7e30bd9f49c14a42b99eae2fcabd435aa2075db460151a14c7ca40c`
-	v2 Content-Length: 13.4 KB (13450 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:37:01 GMT

#### `8b3e6baef3ab76122d1b983dff3d6df416dddec66601f03688a3ccfdfd0a8001`

```dockerfile
ENV PYTHON_VERSION=2.7.10
```

-	Created: Wed, 09 Sep 2015 20:27:00 GMT
-	Parent Layer: `de7e773f73d4fbbd118a704ce258377d862fe9c5027ea213da73e5fde9a79704`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `f038ec4961dd682c5475569c1d28edfab30992a3d3c61067ee0e609267808ecc`

```dockerfile
ENV PYTHON_PIP_VERSION=7.1.2
```

-	Created: Wed, 09 Sep 2015 20:27:00 GMT
-	Parent Layer: `8b3e6baef3ab76122d1b983dff3d6df416dddec66601f03688a3ccfdfd0a8001`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `af086d031545186d1213bdeced5465da5d6491443814999cf98d2a1927b6282e`

```dockerfile
RUN set -x \
	&& buildDeps=' \
		curl \
		gcc \
		libbz2-dev \
		libc6-dev \
		libncurses-dev \
		libreadline-dev \
		libsqlite3-dev \
		libssl-dev \
		make \
		xz-utils \
		zlib1g-dev \
	' \
	&& apt-get update && apt-get install -y $buildDeps --no-install-recommends && rm -rf /var/lib/apt/lists/* \
	&& mkdir -p /usr/src/python \
	&& curl -SL "https://www.python.org/ftp/python/$PYTHON_VERSION/Python-$PYTHON_VERSION.tar.xz" -o python.tar.xz \
	&& curl -SL "https://www.python.org/ftp/python/$PYTHON_VERSION/Python-$PYTHON_VERSION.tar.xz.asc" -o python.tar.xz.asc \
	&& gpg --verify python.tar.xz.asc \
	&& tar -xJC /usr/src/python --strip-components=1 -f python.tar.xz \
	&& rm python.tar.xz* \
	&& cd /usr/src/python \
	&& ./configure --enable-shared --enable-unicode=ucs4 \
	&& make -j$(nproc) \
	&& make install \
	&& ldconfig \
	&& curl -SL 'https://bootstrap.pypa.io/get-pip.py' | python2 \
	&& pip install --no-cache-dir --upgrade pip==$PYTHON_PIP_VERSION \
	&& find /usr/local \
		\( -type d -a -name test -o -name tests \) \
		-o \( -type f -a -name '*.pyc' -o -name '*.pyo' \) \
		-exec rm -rf '{}' + \
	&& apt-get purge -y --auto-remove $buildDeps \
	&& rm -rf /usr/src/python
```

-	Created: Wed, 09 Sep 2015 20:30:07 GMT
-	Parent Layer: `f038ec4961dd682c5475569c1d28edfab30992a3d3c61067ee0e609267808ecc`
-	Docker Version: 1.7.1
-	Virtual Size: 66.5 MB (66501539 bytes)
-	v2 Blob: `sha256:52ceabbfe33323c545565648ee5c0d8562232ffbc95da1e119884db5e2a4fbad`
-	v2 Content-Length: 21.8 MB (21760609 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:36:54 GMT

#### `be949d27143de33cc70b44a705a1a5d5cc54f259f11da79c83ee980639fc03ba`

```dockerfile
RUN pip install --no-cache-dir virtualenv
```

-	Created: Wed, 09 Sep 2015 20:30:12 GMT
-	Parent Layer: `af086d031545186d1213bdeced5465da5d6491443814999cf98d2a1927b6282e`
-	Docker Version: 1.7.1
-	Virtual Size: 5.9 MB (5850003 bytes)
-	v2 Blob: `sha256:ef24d33cd3204b4ffb6a1f6e4f313471e4e7133698a83f37389b16b209fdcde8`
-	v2 Content-Length: 3.1 MB (3054927 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:36:36 GMT

#### `1a977112ac217e1749db38eb598442e8b797439bc22bb2ef8d9d4f94424a736d`

```dockerfile
CMD ["python2"]
```

-	Created: Wed, 09 Sep 2015 20:30:14 GMT
-	Parent Layer: `be949d27143de33cc70b44a705a1a5d5cc54f259f11da79c83ee980639fc03ba`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

## `python:2-slim`

```console
$ docker pull library/python@sha256:3d87134f1f28fa49b718be72f836be114121114c29e28f06dfebecd55328c975
```

-	Total Virtual Size: 205.0 MB (204980219 bytes)
-	Total v2 Content-Length: 79.5 MB (79505182 bytes)

### Layers (11)

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

#### `b724829f2124ff81839118c0bb053554742dae49bcf23847b98264867e4da862`

```dockerfile
RUN apt-get purge -y python.*
```

-	Created: Wed, 09 Sep 2015 20:26:09 GMT
-	Parent Layer: `8c00acfb017549e44d28098762c3e6296872a1ca9b90385855f1019d84bb0dac`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `dad2fc2df4957c05b555a45d00adeaaf624ccce5d9dd557ce4c8548ca40f39f0`

```dockerfile
ENV LANG=C.UTF-8
```

-	Created: Wed, 09 Sep 2015 20:26:10 GMT
-	Parent Layer: `b724829f2124ff81839118c0bb053554742dae49bcf23847b98264867e4da862`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `b4b1929946879d72f7304c436913698e312741961589842913329eb8d746fefa`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		libsqlite3-0 \
		libssl1.0.0 \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Wed, 09 Sep 2015 20:26:51 GMT
-	Parent Layer: `dad2fc2df4957c05b555a45d00adeaaf624ccce5d9dd557ce4c8548ca40f39f0`
-	Docker Version: 1.7.1
-	Virtual Size: 7.4 MB (7441496 bytes)
-	v2 Blob: `sha256:aebbd0bd409f97875c3b3bcf8f57e315ba2ef8d3c4a54f81a7f71cfcf80bf4c9`
-	v2 Content-Length: 3.3 MB (3316296 bytes)
-	v2 Last-Modified: Fri, 11 Sep 2015 00:01:36 GMT

#### `de7e773f73d4fbbd118a704ce258377d862fe9c5027ea213da73e5fde9a79704`

```dockerfile
RUN gpg --keyserver ha.pool.sks-keyservers.net --recv-keys C01E1CAD5EA2C4F0B8E3571504C367C218ADD4FF
```

-	Created: Wed, 09 Sep 2015 20:26:59 GMT
-	Parent Layer: `b4b1929946879d72f7304c436913698e312741961589842913329eb8d746fefa`
-	Docker Version: 1.7.1
-	Virtual Size: 28.1 KB (28050 bytes)
-	v2 Blob: `sha256:6ca940a2c7e30bd9f49c14a42b99eae2fcabd435aa2075db460151a14c7ca40c`
-	v2 Content-Length: 13.4 KB (13450 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:37:01 GMT

#### `8b3e6baef3ab76122d1b983dff3d6df416dddec66601f03688a3ccfdfd0a8001`

```dockerfile
ENV PYTHON_VERSION=2.7.10
```

-	Created: Wed, 09 Sep 2015 20:27:00 GMT
-	Parent Layer: `de7e773f73d4fbbd118a704ce258377d862fe9c5027ea213da73e5fde9a79704`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `f038ec4961dd682c5475569c1d28edfab30992a3d3c61067ee0e609267808ecc`

```dockerfile
ENV PYTHON_PIP_VERSION=7.1.2
```

-	Created: Wed, 09 Sep 2015 20:27:00 GMT
-	Parent Layer: `8b3e6baef3ab76122d1b983dff3d6df416dddec66601f03688a3ccfdfd0a8001`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `af086d031545186d1213bdeced5465da5d6491443814999cf98d2a1927b6282e`

```dockerfile
RUN set -x \
	&& buildDeps=' \
		curl \
		gcc \
		libbz2-dev \
		libc6-dev \
		libncurses-dev \
		libreadline-dev \
		libsqlite3-dev \
		libssl-dev \
		make \
		xz-utils \
		zlib1g-dev \
	' \
	&& apt-get update && apt-get install -y $buildDeps --no-install-recommends && rm -rf /var/lib/apt/lists/* \
	&& mkdir -p /usr/src/python \
	&& curl -SL "https://www.python.org/ftp/python/$PYTHON_VERSION/Python-$PYTHON_VERSION.tar.xz" -o python.tar.xz \
	&& curl -SL "https://www.python.org/ftp/python/$PYTHON_VERSION/Python-$PYTHON_VERSION.tar.xz.asc" -o python.tar.xz.asc \
	&& gpg --verify python.tar.xz.asc \
	&& tar -xJC /usr/src/python --strip-components=1 -f python.tar.xz \
	&& rm python.tar.xz* \
	&& cd /usr/src/python \
	&& ./configure --enable-shared --enable-unicode=ucs4 \
	&& make -j$(nproc) \
	&& make install \
	&& ldconfig \
	&& curl -SL 'https://bootstrap.pypa.io/get-pip.py' | python2 \
	&& pip install --no-cache-dir --upgrade pip==$PYTHON_PIP_VERSION \
	&& find /usr/local \
		\( -type d -a -name test -o -name tests \) \
		-o \( -type f -a -name '*.pyc' -o -name '*.pyo' \) \
		-exec rm -rf '{}' + \
	&& apt-get purge -y --auto-remove $buildDeps \
	&& rm -rf /usr/src/python
```

-	Created: Wed, 09 Sep 2015 20:30:07 GMT
-	Parent Layer: `f038ec4961dd682c5475569c1d28edfab30992a3d3c61067ee0e609267808ecc`
-	Docker Version: 1.7.1
-	Virtual Size: 66.5 MB (66501539 bytes)
-	v2 Blob: `sha256:52ceabbfe33323c545565648ee5c0d8562232ffbc95da1e119884db5e2a4fbad`
-	v2 Content-Length: 21.8 MB (21760609 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:36:54 GMT

#### `be949d27143de33cc70b44a705a1a5d5cc54f259f11da79c83ee980639fc03ba`

```dockerfile
RUN pip install --no-cache-dir virtualenv
```

-	Created: Wed, 09 Sep 2015 20:30:12 GMT
-	Parent Layer: `af086d031545186d1213bdeced5465da5d6491443814999cf98d2a1927b6282e`
-	Docker Version: 1.7.1
-	Virtual Size: 5.9 MB (5850003 bytes)
-	v2 Blob: `sha256:ef24d33cd3204b4ffb6a1f6e4f313471e4e7133698a83f37389b16b209fdcde8`
-	v2 Content-Length: 3.1 MB (3054927 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:36:36 GMT

#### `1a977112ac217e1749db38eb598442e8b797439bc22bb2ef8d9d4f94424a736d`

```dockerfile
CMD ["python2"]
```

-	Created: Wed, 09 Sep 2015 20:30:14 GMT
-	Parent Layer: `be949d27143de33cc70b44a705a1a5d5cc54f259f11da79c83ee980639fc03ba`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

## `python:2.7.10-wheezy`

```console
$ docker pull library/python@sha256:16fa57f7e72d4397d236e2ca24f2640ce2dc9cb46025d6b722bbdaefe58807fa
```

-	Total Virtual Size: 529.2 MB (529208386 bytes)
-	Total v2 Content-Length: 198.3 MB (198341782 bytes)

### Layers (13)

#### `ba249489d0b6512128b60a4910e78fa2000c785d59e0599188a6802bd01155f2`

```dockerfile
ADD file:b908886c97e2b96665b7afc54ff53ebaef1c62896cf83a1199e59fceff1dafb5 in /
```

-	Created: Mon, 07 Sep 2015 23:37:10 GMT
-	Docker Version: 1.7.1
-	Virtual Size: 84.9 MB (84924773 bytes)
-	v2 Blob: `sha256:8f47f7c36e4382b4569bfe8858c0b371313e9c47a72867d69b000949c53637c9`
-	v2 Content-Length: 37.2 MB (37191761 bytes)
-	v2 Last-Modified: Mon, 07 Sep 2015 23:46:29 GMT

#### `19de96c112fcca5b6de16611dc0a359b0b977c551921ca79ac5cf4a8bfff9351`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Mon, 07 Sep 2015 23:37:11 GMT
-	Parent Layer: `ba249489d0b6512128b60a4910e78fa2000c785d59e0599188a6802bd01155f2`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `e83e5b7f7d01ffa47e46b7234799f12d842089df890db8fae765c5a4df26a20b`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 08 Sep 2015 15:38:48 GMT
-	Parent Layer: `19de96c112fcca5b6de16611dc0a359b0b977c551921ca79ac5cf4a8bfff9351`
-	Docker Version: 1.7.1
-	Virtual Size: 14.2 MB (14239819 bytes)
-	v2 Blob: `sha256:7a11528d019acc2b739bd4c1a7e518e247f729fdad40490be9d9fdb13e85c8c8`
-	v2 Content-Length: 6.7 MB (6739553 bytes)
-	v2 Last-Modified: Thu, 10 Sep 2015 23:43:23 GMT

#### `d6b70cefe2bfb76216c96acb6a6c6350eedff489df914b2606b1005e70f73a00`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 08 Sep 2015 15:39:23 GMT
-	Parent Layer: `e83e5b7f7d01ffa47e46b7234799f12d842089df890db8fae765c5a4df26a20b`
-	Docker Version: 1.7.1
-	Virtual Size: 109.4 MB (109431259 bytes)
-	v2 Blob: `sha256:4224b2b7563f71616cbe9215abf5276c51b18d3ceead85a56526519b5391a75f`
-	v2 Content-Length: 37.0 MB (37046780 bytes)
-	v2 Last-Modified: Tue, 08 Sep 2015 16:02:41 GMT

#### `3a5282506aa21c7b21cfdad32a099497bf9839dbc5e427f79bdad6a5e109f3d3`

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

-	Created: Tue, 08 Sep 2015 15:41:19 GMT
-	Parent Layer: `d6b70cefe2bfb76216c96acb6a6c6350eedff489df914b2606b1005e70f73a00`
-	Docker Version: 1.7.1
-	Virtual Size: 250.6 MB (250569275 bytes)
-	v2 Blob: `sha256:89989badb2c249165ed907bdf03e38dffbaefd3c115ad32ac6cf53ebbafab33b`
-	v2 Content-Length: 94.3 MB (94261782 bytes)
-	v2 Last-Modified: Tue, 08 Sep 2015 16:03:53 GMT

#### `1046da491d81f106d762e20009d4dfff16da8b2af4eafc70cba44ca74f7dc53e`

```dockerfile
RUN apt-get purge -y python.*
```

-	Created: Wed, 09 Sep 2015 20:31:23 GMT
-	Parent Layer: `3a5282506aa21c7b21cfdad32a099497bf9839dbc5e427f79bdad6a5e109f3d3`
-	Docker Version: 1.7.1
-	Virtual Size: 833.7 KB (833724 bytes)
-	v2 Blob: `sha256:9bab6257d36f85970d8effd469dcd7c7a44ab5de929035933d165b6a35929905`
-	v2 Content-Length: 196.8 KB (196778 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:39:13 GMT

#### `498b8d9d85457c4a520c8678c4ce95829605287dfb5ca8f39586b76666d446ab`

```dockerfile
ENV LANG=C.UTF-8
```

-	Created: Wed, 09 Sep 2015 20:31:23 GMT
-	Parent Layer: `1046da491d81f106d762e20009d4dfff16da8b2af4eafc70cba44ca74f7dc53e`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `f9ccfd7a016137f63a40c8c1fc6ee17fb988f8c86df77beb2a5761deb61a258a`

```dockerfile
RUN gpg --keyserver ha.pool.sks-keyservers.net --recv-keys C01E1CAD5EA2C4F0B8E3571504C367C218ADD4FF
```

-	Created: Wed, 09 Sep 2015 20:31:25 GMT
-	Parent Layer: `498b8d9d85457c4a520c8678c4ce95829605287dfb5ca8f39586b76666d446ab`
-	Docker Version: 1.7.1
-	Virtual Size: 28.1 KB (28050 bytes)
-	v2 Blob: `sha256:19d5b565dc2af60f19261293fa60b299f1b93317b7d6c686bdab95dc5fd04fbd`
-	v2 Content-Length: 13.4 KB (13449 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:39:09 GMT

#### `d2540b7f44d609aec7d6b66c4c1ee42f22f9081ebf198e7d84a2035151cff348`

```dockerfile
ENV PYTHON_VERSION=2.7.10
```

-	Created: Wed, 09 Sep 2015 20:31:25 GMT
-	Parent Layer: `f9ccfd7a016137f63a40c8c1fc6ee17fb988f8c86df77beb2a5761deb61a258a`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `37551f7dda25cc69f57177c5980cc0788acf8ea1695fb7eedcd244aca2a3bb85`

```dockerfile
ENV PYTHON_PIP_VERSION=7.1.2
```

-	Created: Wed, 09 Sep 2015 20:31:26 GMT
-	Parent Layer: `d2540b7f44d609aec7d6b66c4c1ee42f22f9081ebf198e7d84a2035151cff348`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `259fa29f29c0e64befda6d8a2ebd2e8c788ad283aa25acf91851180676ce6a8e`

```dockerfile
RUN set -x \
	&& mkdir -p /usr/src/python \
	&& curl -SL "https://www.python.org/ftp/python/$PYTHON_VERSION/Python-$PYTHON_VERSION.tar.xz" -o python.tar.xz \
	&& curl -SL "https://www.python.org/ftp/python/$PYTHON_VERSION/Python-$PYTHON_VERSION.tar.xz.asc" -o python.tar.xz.asc \
	&& gpg --verify python.tar.xz.asc \
	&& tar -xJC /usr/src/python --strip-components=1 -f python.tar.xz \
	&& rm python.tar.xz* \
	&& cd /usr/src/python \
	&& ./configure --enable-shared --enable-unicode=ucs4 \
	&& make -j$(nproc) \
	&& make install \
	&& ldconfig \
	&& curl -SL 'https://bootstrap.pypa.io/get-pip.py' | python2 \
	&& pip install --no-cache-dir --upgrade pip==$PYTHON_PIP_VERSION \
	&& find /usr/local \
		\( -type d -a -name test -o -name tests \) \
		-o \( -type f -a -name '*.pyc' -o -name '*.pyo' \) \
		-exec rm -rf '{}' + \
	&& rm -rf /usr/src/python
```

-	Created: Wed, 09 Sep 2015 20:33:20 GMT
-	Parent Layer: `37551f7dda25cc69f57177c5980cc0788acf8ea1695fb7eedcd244aca2a3bb85`
-	Docker Version: 1.7.1
-	Virtual Size: 63.3 MB (63331479 bytes)
-	v2 Blob: `sha256:ea1042595bda9c9199807d9ce8227c4abf3ff20f5db7d5e582771156724efba8`
-	v2 Content-Length: 19.8 MB (19836588 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:39:01 GMT

#### `b03c7f22f1c1cc387adb8a700cee1ee06699309d9ff97841669756b9fff6626a`

```dockerfile
RUN pip install --no-cache-dir virtualenv
```

-	Created: Wed, 09 Sep 2015 20:33:22 GMT
-	Parent Layer: `259fa29f29c0e64befda6d8a2ebd2e8c788ad283aa25acf91851180676ce6a8e`
-	Docker Version: 1.7.1
-	Virtual Size: 5.9 MB (5850007 bytes)
-	v2 Blob: `sha256:f2af8fa88165b6bcf885f44fb45265f3d5c0df16ca03de9e7822b437b31a61f7`
-	v2 Content-Length: 3.1 MB (3054931 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:38:45 GMT

#### `03e86350efc59d109d34d35bffc062358d535a0655fbc67b8d1ef4cf56b01cc4`

```dockerfile
CMD ["python2"]
```

-	Created: Wed, 09 Sep 2015 20:33:23 GMT
-	Parent Layer: `b03c7f22f1c1cc387adb8a700cee1ee06699309d9ff97841669756b9fff6626a`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

## `python:2.7-wheezy`

```console
$ docker pull library/python@sha256:7eebcd7208d57f1393346bc3791a377ca59722402e0ced7ae23097da0caa81b7
```

-	Total Virtual Size: 529.2 MB (529208386 bytes)
-	Total v2 Content-Length: 198.3 MB (198341782 bytes)

### Layers (13)

#### `ba249489d0b6512128b60a4910e78fa2000c785d59e0599188a6802bd01155f2`

```dockerfile
ADD file:b908886c97e2b96665b7afc54ff53ebaef1c62896cf83a1199e59fceff1dafb5 in /
```

-	Created: Mon, 07 Sep 2015 23:37:10 GMT
-	Docker Version: 1.7.1
-	Virtual Size: 84.9 MB (84924773 bytes)
-	v2 Blob: `sha256:8f47f7c36e4382b4569bfe8858c0b371313e9c47a72867d69b000949c53637c9`
-	v2 Content-Length: 37.2 MB (37191761 bytes)
-	v2 Last-Modified: Mon, 07 Sep 2015 23:46:29 GMT

#### `19de96c112fcca5b6de16611dc0a359b0b977c551921ca79ac5cf4a8bfff9351`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Mon, 07 Sep 2015 23:37:11 GMT
-	Parent Layer: `ba249489d0b6512128b60a4910e78fa2000c785d59e0599188a6802bd01155f2`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `e83e5b7f7d01ffa47e46b7234799f12d842089df890db8fae765c5a4df26a20b`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 08 Sep 2015 15:38:48 GMT
-	Parent Layer: `19de96c112fcca5b6de16611dc0a359b0b977c551921ca79ac5cf4a8bfff9351`
-	Docker Version: 1.7.1
-	Virtual Size: 14.2 MB (14239819 bytes)
-	v2 Blob: `sha256:7a11528d019acc2b739bd4c1a7e518e247f729fdad40490be9d9fdb13e85c8c8`
-	v2 Content-Length: 6.7 MB (6739553 bytes)
-	v2 Last-Modified: Thu, 10 Sep 2015 23:43:23 GMT

#### `d6b70cefe2bfb76216c96acb6a6c6350eedff489df914b2606b1005e70f73a00`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 08 Sep 2015 15:39:23 GMT
-	Parent Layer: `e83e5b7f7d01ffa47e46b7234799f12d842089df890db8fae765c5a4df26a20b`
-	Docker Version: 1.7.1
-	Virtual Size: 109.4 MB (109431259 bytes)
-	v2 Blob: `sha256:4224b2b7563f71616cbe9215abf5276c51b18d3ceead85a56526519b5391a75f`
-	v2 Content-Length: 37.0 MB (37046780 bytes)
-	v2 Last-Modified: Tue, 08 Sep 2015 16:02:41 GMT

#### `3a5282506aa21c7b21cfdad32a099497bf9839dbc5e427f79bdad6a5e109f3d3`

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

-	Created: Tue, 08 Sep 2015 15:41:19 GMT
-	Parent Layer: `d6b70cefe2bfb76216c96acb6a6c6350eedff489df914b2606b1005e70f73a00`
-	Docker Version: 1.7.1
-	Virtual Size: 250.6 MB (250569275 bytes)
-	v2 Blob: `sha256:89989badb2c249165ed907bdf03e38dffbaefd3c115ad32ac6cf53ebbafab33b`
-	v2 Content-Length: 94.3 MB (94261782 bytes)
-	v2 Last-Modified: Tue, 08 Sep 2015 16:03:53 GMT

#### `1046da491d81f106d762e20009d4dfff16da8b2af4eafc70cba44ca74f7dc53e`

```dockerfile
RUN apt-get purge -y python.*
```

-	Created: Wed, 09 Sep 2015 20:31:23 GMT
-	Parent Layer: `3a5282506aa21c7b21cfdad32a099497bf9839dbc5e427f79bdad6a5e109f3d3`
-	Docker Version: 1.7.1
-	Virtual Size: 833.7 KB (833724 bytes)
-	v2 Blob: `sha256:9bab6257d36f85970d8effd469dcd7c7a44ab5de929035933d165b6a35929905`
-	v2 Content-Length: 196.8 KB (196778 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:39:13 GMT

#### `498b8d9d85457c4a520c8678c4ce95829605287dfb5ca8f39586b76666d446ab`

```dockerfile
ENV LANG=C.UTF-8
```

-	Created: Wed, 09 Sep 2015 20:31:23 GMT
-	Parent Layer: `1046da491d81f106d762e20009d4dfff16da8b2af4eafc70cba44ca74f7dc53e`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `f9ccfd7a016137f63a40c8c1fc6ee17fb988f8c86df77beb2a5761deb61a258a`

```dockerfile
RUN gpg --keyserver ha.pool.sks-keyservers.net --recv-keys C01E1CAD5EA2C4F0B8E3571504C367C218ADD4FF
```

-	Created: Wed, 09 Sep 2015 20:31:25 GMT
-	Parent Layer: `498b8d9d85457c4a520c8678c4ce95829605287dfb5ca8f39586b76666d446ab`
-	Docker Version: 1.7.1
-	Virtual Size: 28.1 KB (28050 bytes)
-	v2 Blob: `sha256:19d5b565dc2af60f19261293fa60b299f1b93317b7d6c686bdab95dc5fd04fbd`
-	v2 Content-Length: 13.4 KB (13449 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:39:09 GMT

#### `d2540b7f44d609aec7d6b66c4c1ee42f22f9081ebf198e7d84a2035151cff348`

```dockerfile
ENV PYTHON_VERSION=2.7.10
```

-	Created: Wed, 09 Sep 2015 20:31:25 GMT
-	Parent Layer: `f9ccfd7a016137f63a40c8c1fc6ee17fb988f8c86df77beb2a5761deb61a258a`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `37551f7dda25cc69f57177c5980cc0788acf8ea1695fb7eedcd244aca2a3bb85`

```dockerfile
ENV PYTHON_PIP_VERSION=7.1.2
```

-	Created: Wed, 09 Sep 2015 20:31:26 GMT
-	Parent Layer: `d2540b7f44d609aec7d6b66c4c1ee42f22f9081ebf198e7d84a2035151cff348`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `259fa29f29c0e64befda6d8a2ebd2e8c788ad283aa25acf91851180676ce6a8e`

```dockerfile
RUN set -x \
	&& mkdir -p /usr/src/python \
	&& curl -SL "https://www.python.org/ftp/python/$PYTHON_VERSION/Python-$PYTHON_VERSION.tar.xz" -o python.tar.xz \
	&& curl -SL "https://www.python.org/ftp/python/$PYTHON_VERSION/Python-$PYTHON_VERSION.tar.xz.asc" -o python.tar.xz.asc \
	&& gpg --verify python.tar.xz.asc \
	&& tar -xJC /usr/src/python --strip-components=1 -f python.tar.xz \
	&& rm python.tar.xz* \
	&& cd /usr/src/python \
	&& ./configure --enable-shared --enable-unicode=ucs4 \
	&& make -j$(nproc) \
	&& make install \
	&& ldconfig \
	&& curl -SL 'https://bootstrap.pypa.io/get-pip.py' | python2 \
	&& pip install --no-cache-dir --upgrade pip==$PYTHON_PIP_VERSION \
	&& find /usr/local \
		\( -type d -a -name test -o -name tests \) \
		-o \( -type f -a -name '*.pyc' -o -name '*.pyo' \) \
		-exec rm -rf '{}' + \
	&& rm -rf /usr/src/python
```

-	Created: Wed, 09 Sep 2015 20:33:20 GMT
-	Parent Layer: `37551f7dda25cc69f57177c5980cc0788acf8ea1695fb7eedcd244aca2a3bb85`
-	Docker Version: 1.7.1
-	Virtual Size: 63.3 MB (63331479 bytes)
-	v2 Blob: `sha256:ea1042595bda9c9199807d9ce8227c4abf3ff20f5db7d5e582771156724efba8`
-	v2 Content-Length: 19.8 MB (19836588 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:39:01 GMT

#### `b03c7f22f1c1cc387adb8a700cee1ee06699309d9ff97841669756b9fff6626a`

```dockerfile
RUN pip install --no-cache-dir virtualenv
```

-	Created: Wed, 09 Sep 2015 20:33:22 GMT
-	Parent Layer: `259fa29f29c0e64befda6d8a2ebd2e8c788ad283aa25acf91851180676ce6a8e`
-	Docker Version: 1.7.1
-	Virtual Size: 5.9 MB (5850007 bytes)
-	v2 Blob: `sha256:f2af8fa88165b6bcf885f44fb45265f3d5c0df16ca03de9e7822b437b31a61f7`
-	v2 Content-Length: 3.1 MB (3054931 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:38:45 GMT

#### `03e86350efc59d109d34d35bffc062358d535a0655fbc67b8d1ef4cf56b01cc4`

```dockerfile
CMD ["python2"]
```

-	Created: Wed, 09 Sep 2015 20:33:23 GMT
-	Parent Layer: `b03c7f22f1c1cc387adb8a700cee1ee06699309d9ff97841669756b9fff6626a`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

## `python:2-wheezy`

```console
$ docker pull library/python@sha256:420360a6d49f95971813f746cb6f2c855a5dbd8fc33beb7e11e8d9d3f320e60d
```

-	Total Virtual Size: 529.2 MB (529208386 bytes)
-	Total v2 Content-Length: 198.3 MB (198341782 bytes)

### Layers (13)

#### `ba249489d0b6512128b60a4910e78fa2000c785d59e0599188a6802bd01155f2`

```dockerfile
ADD file:b908886c97e2b96665b7afc54ff53ebaef1c62896cf83a1199e59fceff1dafb5 in /
```

-	Created: Mon, 07 Sep 2015 23:37:10 GMT
-	Docker Version: 1.7.1
-	Virtual Size: 84.9 MB (84924773 bytes)
-	v2 Blob: `sha256:8f47f7c36e4382b4569bfe8858c0b371313e9c47a72867d69b000949c53637c9`
-	v2 Content-Length: 37.2 MB (37191761 bytes)
-	v2 Last-Modified: Mon, 07 Sep 2015 23:46:29 GMT

#### `19de96c112fcca5b6de16611dc0a359b0b977c551921ca79ac5cf4a8bfff9351`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Mon, 07 Sep 2015 23:37:11 GMT
-	Parent Layer: `ba249489d0b6512128b60a4910e78fa2000c785d59e0599188a6802bd01155f2`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `e83e5b7f7d01ffa47e46b7234799f12d842089df890db8fae765c5a4df26a20b`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 08 Sep 2015 15:38:48 GMT
-	Parent Layer: `19de96c112fcca5b6de16611dc0a359b0b977c551921ca79ac5cf4a8bfff9351`
-	Docker Version: 1.7.1
-	Virtual Size: 14.2 MB (14239819 bytes)
-	v2 Blob: `sha256:7a11528d019acc2b739bd4c1a7e518e247f729fdad40490be9d9fdb13e85c8c8`
-	v2 Content-Length: 6.7 MB (6739553 bytes)
-	v2 Last-Modified: Thu, 10 Sep 2015 23:43:23 GMT

#### `d6b70cefe2bfb76216c96acb6a6c6350eedff489df914b2606b1005e70f73a00`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 08 Sep 2015 15:39:23 GMT
-	Parent Layer: `e83e5b7f7d01ffa47e46b7234799f12d842089df890db8fae765c5a4df26a20b`
-	Docker Version: 1.7.1
-	Virtual Size: 109.4 MB (109431259 bytes)
-	v2 Blob: `sha256:4224b2b7563f71616cbe9215abf5276c51b18d3ceead85a56526519b5391a75f`
-	v2 Content-Length: 37.0 MB (37046780 bytes)
-	v2 Last-Modified: Tue, 08 Sep 2015 16:02:41 GMT

#### `3a5282506aa21c7b21cfdad32a099497bf9839dbc5e427f79bdad6a5e109f3d3`

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

-	Created: Tue, 08 Sep 2015 15:41:19 GMT
-	Parent Layer: `d6b70cefe2bfb76216c96acb6a6c6350eedff489df914b2606b1005e70f73a00`
-	Docker Version: 1.7.1
-	Virtual Size: 250.6 MB (250569275 bytes)
-	v2 Blob: `sha256:89989badb2c249165ed907bdf03e38dffbaefd3c115ad32ac6cf53ebbafab33b`
-	v2 Content-Length: 94.3 MB (94261782 bytes)
-	v2 Last-Modified: Tue, 08 Sep 2015 16:03:53 GMT

#### `1046da491d81f106d762e20009d4dfff16da8b2af4eafc70cba44ca74f7dc53e`

```dockerfile
RUN apt-get purge -y python.*
```

-	Created: Wed, 09 Sep 2015 20:31:23 GMT
-	Parent Layer: `3a5282506aa21c7b21cfdad32a099497bf9839dbc5e427f79bdad6a5e109f3d3`
-	Docker Version: 1.7.1
-	Virtual Size: 833.7 KB (833724 bytes)
-	v2 Blob: `sha256:9bab6257d36f85970d8effd469dcd7c7a44ab5de929035933d165b6a35929905`
-	v2 Content-Length: 196.8 KB (196778 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:39:13 GMT

#### `498b8d9d85457c4a520c8678c4ce95829605287dfb5ca8f39586b76666d446ab`

```dockerfile
ENV LANG=C.UTF-8
```

-	Created: Wed, 09 Sep 2015 20:31:23 GMT
-	Parent Layer: `1046da491d81f106d762e20009d4dfff16da8b2af4eafc70cba44ca74f7dc53e`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `f9ccfd7a016137f63a40c8c1fc6ee17fb988f8c86df77beb2a5761deb61a258a`

```dockerfile
RUN gpg --keyserver ha.pool.sks-keyservers.net --recv-keys C01E1CAD5EA2C4F0B8E3571504C367C218ADD4FF
```

-	Created: Wed, 09 Sep 2015 20:31:25 GMT
-	Parent Layer: `498b8d9d85457c4a520c8678c4ce95829605287dfb5ca8f39586b76666d446ab`
-	Docker Version: 1.7.1
-	Virtual Size: 28.1 KB (28050 bytes)
-	v2 Blob: `sha256:19d5b565dc2af60f19261293fa60b299f1b93317b7d6c686bdab95dc5fd04fbd`
-	v2 Content-Length: 13.4 KB (13449 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:39:09 GMT

#### `d2540b7f44d609aec7d6b66c4c1ee42f22f9081ebf198e7d84a2035151cff348`

```dockerfile
ENV PYTHON_VERSION=2.7.10
```

-	Created: Wed, 09 Sep 2015 20:31:25 GMT
-	Parent Layer: `f9ccfd7a016137f63a40c8c1fc6ee17fb988f8c86df77beb2a5761deb61a258a`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `37551f7dda25cc69f57177c5980cc0788acf8ea1695fb7eedcd244aca2a3bb85`

```dockerfile
ENV PYTHON_PIP_VERSION=7.1.2
```

-	Created: Wed, 09 Sep 2015 20:31:26 GMT
-	Parent Layer: `d2540b7f44d609aec7d6b66c4c1ee42f22f9081ebf198e7d84a2035151cff348`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `259fa29f29c0e64befda6d8a2ebd2e8c788ad283aa25acf91851180676ce6a8e`

```dockerfile
RUN set -x \
	&& mkdir -p /usr/src/python \
	&& curl -SL "https://www.python.org/ftp/python/$PYTHON_VERSION/Python-$PYTHON_VERSION.tar.xz" -o python.tar.xz \
	&& curl -SL "https://www.python.org/ftp/python/$PYTHON_VERSION/Python-$PYTHON_VERSION.tar.xz.asc" -o python.tar.xz.asc \
	&& gpg --verify python.tar.xz.asc \
	&& tar -xJC /usr/src/python --strip-components=1 -f python.tar.xz \
	&& rm python.tar.xz* \
	&& cd /usr/src/python \
	&& ./configure --enable-shared --enable-unicode=ucs4 \
	&& make -j$(nproc) \
	&& make install \
	&& ldconfig \
	&& curl -SL 'https://bootstrap.pypa.io/get-pip.py' | python2 \
	&& pip install --no-cache-dir --upgrade pip==$PYTHON_PIP_VERSION \
	&& find /usr/local \
		\( -type d -a -name test -o -name tests \) \
		-o \( -type f -a -name '*.pyc' -o -name '*.pyo' \) \
		-exec rm -rf '{}' + \
	&& rm -rf /usr/src/python
```

-	Created: Wed, 09 Sep 2015 20:33:20 GMT
-	Parent Layer: `37551f7dda25cc69f57177c5980cc0788acf8ea1695fb7eedcd244aca2a3bb85`
-	Docker Version: 1.7.1
-	Virtual Size: 63.3 MB (63331479 bytes)
-	v2 Blob: `sha256:ea1042595bda9c9199807d9ce8227c4abf3ff20f5db7d5e582771156724efba8`
-	v2 Content-Length: 19.8 MB (19836588 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:39:01 GMT

#### `b03c7f22f1c1cc387adb8a700cee1ee06699309d9ff97841669756b9fff6626a`

```dockerfile
RUN pip install --no-cache-dir virtualenv
```

-	Created: Wed, 09 Sep 2015 20:33:22 GMT
-	Parent Layer: `259fa29f29c0e64befda6d8a2ebd2e8c788ad283aa25acf91851180676ce6a8e`
-	Docker Version: 1.7.1
-	Virtual Size: 5.9 MB (5850007 bytes)
-	v2 Blob: `sha256:f2af8fa88165b6bcf885f44fb45265f3d5c0df16ca03de9e7822b437b31a61f7`
-	v2 Content-Length: 3.1 MB (3054931 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:38:45 GMT

#### `03e86350efc59d109d34d35bffc062358d535a0655fbc67b8d1ef4cf56b01cc4`

```dockerfile
CMD ["python2"]
```

-	Created: Wed, 09 Sep 2015 20:33:23 GMT
-	Parent Layer: `b03c7f22f1c1cc387adb8a700cee1ee06699309d9ff97841669756b9fff6626a`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

## `python:3.2.6`

```console
$ docker pull library/python@sha256:eedeae6570b8344c4844428280f035d7647a1bb22edb025fc03779f73fbeb0c5
```

-	Total Virtual Size: 667.0 MB (667031076 bytes)
-	Total v2 Content-Length: 258.6 MB (258606530 bytes)

### Layers (13)

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
-	v2 Blob: `sha256:b3010ec3eb21ac3df74757a47832fb17395b76ad3a30794074cefd07541d3557`
-	v2 Content-Length: 18.5 MB (18538591 bytes)
-	v2 Last-Modified: Thu, 10 Sep 2015 23:36:30 GMT

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

#### `a7131b97316204530af26e42319aeda8ac44cd5ac2891e5dab45e16deb1e592d`

```dockerfile
RUN apt-get purge -y python.*
```

-	Created: Wed, 09 Sep 2015 20:20:46 GMT
-	Parent Layer: `16b189cc8ce688f9f1d8f1d837fa0891107450a06c795b1cba8f6c33a4454280`
-	Docker Version: 1.7.1
-	Virtual Size: 975.3 KB (975277 bytes)
-	v2 Blob: `sha256:20cdbe5b7a6f64396bcabde9b06c16a0b41e2c7fd39b28eff1ee3670a9f0516e`
-	v2 Content-Length: 220.4 KB (220377 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:29:17 GMT

#### `d7cbb60bc416f832c685b38578b77da5f3716cba15d4bcb45d850809a4c112eb`

```dockerfile
ENV LANG=C.UTF-8
```

-	Created: Wed, 09 Sep 2015 20:20:48 GMT
-	Parent Layer: `a7131b97316204530af26e42319aeda8ac44cd5ac2891e5dab45e16deb1e592d`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `24ccfa7d2e84006ddb7fe42a70e5d6af49675a02e896f98579c26fbcb8e1ae1b`

```dockerfile
RUN gpg --keyserver ha.pool.sks-keyservers.net --recv-keys 26DEA9D4613391EF3E25C9FF0A5B101836580288
```

-	Created: Wed, 09 Sep 2015 20:34:23 GMT
-	Parent Layer: `d7cbb60bc416f832c685b38578b77da5f3716cba15d4bcb45d850809a4c112eb`
-	Docker Version: 1.7.1
-	Virtual Size: 15.0 KB (14980 bytes)
-	v2 Blob: `sha256:c07c8b7cac8f14fa0ddc06c34b533baa07bb4c765c154904e6748bafe3c151b4`
-	v2 Content-Length: 6.8 KB (6815 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:44:13 GMT

#### `4e621e0485f9e56e798ea729bc66dd296184a4d0404b685887e1025402bd5151`

```dockerfile
ENV PYTHON_VERSION=3.2.6
```

-	Created: Wed, 09 Sep 2015 20:34:24 GMT
-	Parent Layer: `24ccfa7d2e84006ddb7fe42a70e5d6af49675a02e896f98579c26fbcb8e1ae1b`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `64d66dd7866e15b27a77b6c71eb8457b55006824348c6c520cd415e98cd17f61`

```dockerfile
ENV PYTHON_PIP_VERSION=7.1.2
```

-	Created: Wed, 09 Sep 2015 20:34:24 GMT
-	Parent Layer: `4e621e0485f9e56e798ea729bc66dd296184a4d0404b685887e1025402bd5151`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `2d21f69c3d15d951b94bd86e641a37816fbbc6a1c4b244239d1a11da0d912986`

```dockerfile
RUN set -x \
	&& mkdir -p /usr/src/python \
	&& curl -SL "https://www.python.org/ftp/python/$PYTHON_VERSION/Python-$PYTHON_VERSION.tar.xz" -o python.tar.xz \
	&& curl -SL "https://www.python.org/ftp/python/$PYTHON_VERSION/Python-$PYTHON_VERSION.tar.xz.asc" -o python.tar.xz.asc \
	&& gpg --verify python.tar.xz.asc \
	&& tar -xJC /usr/src/python --strip-components=1 -f python.tar.xz \
	&& rm python.tar.xz* \
	&& cd /usr/src/python \
	&& ./configure --enable-shared --enable-unicode=ucs4 \
	&& make -j$(nproc) \
	&& make install \
	&& ldconfig \
	&& curl -SL 'https://bootstrap.pypa.io/get-pip.py' | python3 \
	&& pip install --no-cache-dir --upgrade pip==$PYTHON_PIP_VERSION \
	&& find /usr/local \
		\( -type d -a -name test -o -name tests \) \
		-o \( -type f -a -name '*.pyc' -o -name '*.pyo' \) \
		-exec rm -rf '{}' + \
	&& rm -rf /usr/src/python
```

-	Created: Wed, 09 Sep 2015 20:36:26 GMT
-	Parent Layer: `64d66dd7866e15b27a77b6c71eb8457b55006824348c6c520cd415e98cd17f61`
-	Docker Version: 1.7.1
-	Virtual Size: 59.6 MB (59555829 bytes)
-	v2 Blob: `sha256:6496ad2256e6de9071b2a9349db0af365f5a5a22511ef6e7582991ea1cd53787`
-	v2 Content-Length: 17.6 MB (17609981 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:44:07 GMT

#### `47ea8143784e4c25b85cc777dc4b4bfc1d86eb25cff33ff74869f7d8f11dc82d`

```dockerfile
RUN cd /usr/local/bin \
	&& ln -s idle3 idle \
	&& ln -s pydoc3 pydoc \
	&& ln -s python3 python \
	&& ln -s python-config3 python-config
```

-	Created: Wed, 09 Sep 2015 20:36:28 GMT
-	Parent Layer: `2d21f69c3d15d951b94bd86e641a37816fbbc6a1c4b244239d1a11da0d912986`
-	Docker Version: 1.7.1
-	Virtual Size: 32.0 B
-	v2 Blob: `sha256:908483e62d3fb557efaa13ba6c493e24b8ea8e5c2cb5dc28daddb580b8bf5d02`
-	v2 Content-Length: 233.0 B
-	v2 Last-Modified: Wed, 09 Sep 2015 21:43:53 GMT

#### `9d7b998c3a50d68bcbe37405a22609eefb466cc266a4aec967935b56010c1fc7`

```dockerfile
CMD ["python3"]
```

-	Created: Wed, 09 Sep 2015 20:36:28 GMT
-	Parent Layer: `47ea8143784e4c25b85cc777dc4b4bfc1d86eb25cff33ff74869f7d8f11dc82d`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

## `python:3.2`

```console
$ docker pull library/python@sha256:e06ea9a0df527d24953aa0fab10947d445677890c2f228671fa7066194f61574
```

-	Total Virtual Size: 667.0 MB (667031076 bytes)
-	Total v2 Content-Length: 258.6 MB (258606530 bytes)

### Layers (13)

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
-	v2 Blob: `sha256:b3010ec3eb21ac3df74757a47832fb17395b76ad3a30794074cefd07541d3557`
-	v2 Content-Length: 18.5 MB (18538591 bytes)
-	v2 Last-Modified: Thu, 10 Sep 2015 23:36:30 GMT

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

#### `a7131b97316204530af26e42319aeda8ac44cd5ac2891e5dab45e16deb1e592d`

```dockerfile
RUN apt-get purge -y python.*
```

-	Created: Wed, 09 Sep 2015 20:20:46 GMT
-	Parent Layer: `16b189cc8ce688f9f1d8f1d837fa0891107450a06c795b1cba8f6c33a4454280`
-	Docker Version: 1.7.1
-	Virtual Size: 975.3 KB (975277 bytes)
-	v2 Blob: `sha256:20cdbe5b7a6f64396bcabde9b06c16a0b41e2c7fd39b28eff1ee3670a9f0516e`
-	v2 Content-Length: 220.4 KB (220377 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:29:17 GMT

#### `d7cbb60bc416f832c685b38578b77da5f3716cba15d4bcb45d850809a4c112eb`

```dockerfile
ENV LANG=C.UTF-8
```

-	Created: Wed, 09 Sep 2015 20:20:48 GMT
-	Parent Layer: `a7131b97316204530af26e42319aeda8ac44cd5ac2891e5dab45e16deb1e592d`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `24ccfa7d2e84006ddb7fe42a70e5d6af49675a02e896f98579c26fbcb8e1ae1b`

```dockerfile
RUN gpg --keyserver ha.pool.sks-keyservers.net --recv-keys 26DEA9D4613391EF3E25C9FF0A5B101836580288
```

-	Created: Wed, 09 Sep 2015 20:34:23 GMT
-	Parent Layer: `d7cbb60bc416f832c685b38578b77da5f3716cba15d4bcb45d850809a4c112eb`
-	Docker Version: 1.7.1
-	Virtual Size: 15.0 KB (14980 bytes)
-	v2 Blob: `sha256:c07c8b7cac8f14fa0ddc06c34b533baa07bb4c765c154904e6748bafe3c151b4`
-	v2 Content-Length: 6.8 KB (6815 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:44:13 GMT

#### `4e621e0485f9e56e798ea729bc66dd296184a4d0404b685887e1025402bd5151`

```dockerfile
ENV PYTHON_VERSION=3.2.6
```

-	Created: Wed, 09 Sep 2015 20:34:24 GMT
-	Parent Layer: `24ccfa7d2e84006ddb7fe42a70e5d6af49675a02e896f98579c26fbcb8e1ae1b`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `64d66dd7866e15b27a77b6c71eb8457b55006824348c6c520cd415e98cd17f61`

```dockerfile
ENV PYTHON_PIP_VERSION=7.1.2
```

-	Created: Wed, 09 Sep 2015 20:34:24 GMT
-	Parent Layer: `4e621e0485f9e56e798ea729bc66dd296184a4d0404b685887e1025402bd5151`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `2d21f69c3d15d951b94bd86e641a37816fbbc6a1c4b244239d1a11da0d912986`

```dockerfile
RUN set -x \
	&& mkdir -p /usr/src/python \
	&& curl -SL "https://www.python.org/ftp/python/$PYTHON_VERSION/Python-$PYTHON_VERSION.tar.xz" -o python.tar.xz \
	&& curl -SL "https://www.python.org/ftp/python/$PYTHON_VERSION/Python-$PYTHON_VERSION.tar.xz.asc" -o python.tar.xz.asc \
	&& gpg --verify python.tar.xz.asc \
	&& tar -xJC /usr/src/python --strip-components=1 -f python.tar.xz \
	&& rm python.tar.xz* \
	&& cd /usr/src/python \
	&& ./configure --enable-shared --enable-unicode=ucs4 \
	&& make -j$(nproc) \
	&& make install \
	&& ldconfig \
	&& curl -SL 'https://bootstrap.pypa.io/get-pip.py' | python3 \
	&& pip install --no-cache-dir --upgrade pip==$PYTHON_PIP_VERSION \
	&& find /usr/local \
		\( -type d -a -name test -o -name tests \) \
		-o \( -type f -a -name '*.pyc' -o -name '*.pyo' \) \
		-exec rm -rf '{}' + \
	&& rm -rf /usr/src/python
```

-	Created: Wed, 09 Sep 2015 20:36:26 GMT
-	Parent Layer: `64d66dd7866e15b27a77b6c71eb8457b55006824348c6c520cd415e98cd17f61`
-	Docker Version: 1.7.1
-	Virtual Size: 59.6 MB (59555829 bytes)
-	v2 Blob: `sha256:6496ad2256e6de9071b2a9349db0af365f5a5a22511ef6e7582991ea1cd53787`
-	v2 Content-Length: 17.6 MB (17609981 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:44:07 GMT

#### `47ea8143784e4c25b85cc777dc4b4bfc1d86eb25cff33ff74869f7d8f11dc82d`

```dockerfile
RUN cd /usr/local/bin \
	&& ln -s idle3 idle \
	&& ln -s pydoc3 pydoc \
	&& ln -s python3 python \
	&& ln -s python-config3 python-config
```

-	Created: Wed, 09 Sep 2015 20:36:28 GMT
-	Parent Layer: `2d21f69c3d15d951b94bd86e641a37816fbbc6a1c4b244239d1a11da0d912986`
-	Docker Version: 1.7.1
-	Virtual Size: 32.0 B
-	v2 Blob: `sha256:908483e62d3fb557efaa13ba6c493e24b8ea8e5c2cb5dc28daddb580b8bf5d02`
-	v2 Content-Length: 233.0 B
-	v2 Last-Modified: Wed, 09 Sep 2015 21:43:53 GMT

#### `9d7b998c3a50d68bcbe37405a22609eefb466cc266a4aec967935b56010c1fc7`

```dockerfile
CMD ["python3"]
```

-	Created: Wed, 09 Sep 2015 20:36:28 GMT
-	Parent Layer: `47ea8143784e4c25b85cc777dc4b4bfc1d86eb25cff33ff74869f7d8f11dc82d`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

## `python:3.2.6-onbuild`

```console
$ docker pull library/python@sha256:d080c084b613b94267d200e279a901777a02573750189ab437b8f4ecc56c0dd4
```

-	Total Virtual Size: 667.0 MB (667031076 bytes)
-	Total v2 Content-Length: 258.6 MB (258606784 bytes)

### Layers (18)

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
-	v2 Blob: `sha256:b3010ec3eb21ac3df74757a47832fb17395b76ad3a30794074cefd07541d3557`
-	v2 Content-Length: 18.5 MB (18538591 bytes)
-	v2 Last-Modified: Thu, 10 Sep 2015 23:36:30 GMT

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

#### `a7131b97316204530af26e42319aeda8ac44cd5ac2891e5dab45e16deb1e592d`

```dockerfile
RUN apt-get purge -y python.*
```

-	Created: Wed, 09 Sep 2015 20:20:46 GMT
-	Parent Layer: `16b189cc8ce688f9f1d8f1d837fa0891107450a06c795b1cba8f6c33a4454280`
-	Docker Version: 1.7.1
-	Virtual Size: 975.3 KB (975277 bytes)
-	v2 Blob: `sha256:20cdbe5b7a6f64396bcabde9b06c16a0b41e2c7fd39b28eff1ee3670a9f0516e`
-	v2 Content-Length: 220.4 KB (220377 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:29:17 GMT

#### `d7cbb60bc416f832c685b38578b77da5f3716cba15d4bcb45d850809a4c112eb`

```dockerfile
ENV LANG=C.UTF-8
```

-	Created: Wed, 09 Sep 2015 20:20:48 GMT
-	Parent Layer: `a7131b97316204530af26e42319aeda8ac44cd5ac2891e5dab45e16deb1e592d`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `24ccfa7d2e84006ddb7fe42a70e5d6af49675a02e896f98579c26fbcb8e1ae1b`

```dockerfile
RUN gpg --keyserver ha.pool.sks-keyservers.net --recv-keys 26DEA9D4613391EF3E25C9FF0A5B101836580288
```

-	Created: Wed, 09 Sep 2015 20:34:23 GMT
-	Parent Layer: `d7cbb60bc416f832c685b38578b77da5f3716cba15d4bcb45d850809a4c112eb`
-	Docker Version: 1.7.1
-	Virtual Size: 15.0 KB (14980 bytes)
-	v2 Blob: `sha256:c07c8b7cac8f14fa0ddc06c34b533baa07bb4c765c154904e6748bafe3c151b4`
-	v2 Content-Length: 6.8 KB (6815 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:44:13 GMT

#### `4e621e0485f9e56e798ea729bc66dd296184a4d0404b685887e1025402bd5151`

```dockerfile
ENV PYTHON_VERSION=3.2.6
```

-	Created: Wed, 09 Sep 2015 20:34:24 GMT
-	Parent Layer: `24ccfa7d2e84006ddb7fe42a70e5d6af49675a02e896f98579c26fbcb8e1ae1b`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `64d66dd7866e15b27a77b6c71eb8457b55006824348c6c520cd415e98cd17f61`

```dockerfile
ENV PYTHON_PIP_VERSION=7.1.2
```

-	Created: Wed, 09 Sep 2015 20:34:24 GMT
-	Parent Layer: `4e621e0485f9e56e798ea729bc66dd296184a4d0404b685887e1025402bd5151`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `2d21f69c3d15d951b94bd86e641a37816fbbc6a1c4b244239d1a11da0d912986`

```dockerfile
RUN set -x \
	&& mkdir -p /usr/src/python \
	&& curl -SL "https://www.python.org/ftp/python/$PYTHON_VERSION/Python-$PYTHON_VERSION.tar.xz" -o python.tar.xz \
	&& curl -SL "https://www.python.org/ftp/python/$PYTHON_VERSION/Python-$PYTHON_VERSION.tar.xz.asc" -o python.tar.xz.asc \
	&& gpg --verify python.tar.xz.asc \
	&& tar -xJC /usr/src/python --strip-components=1 -f python.tar.xz \
	&& rm python.tar.xz* \
	&& cd /usr/src/python \
	&& ./configure --enable-shared --enable-unicode=ucs4 \
	&& make -j$(nproc) \
	&& make install \
	&& ldconfig \
	&& curl -SL 'https://bootstrap.pypa.io/get-pip.py' | python3 \
	&& pip install --no-cache-dir --upgrade pip==$PYTHON_PIP_VERSION \
	&& find /usr/local \
		\( -type d -a -name test -o -name tests \) \
		-o \( -type f -a -name '*.pyc' -o -name '*.pyo' \) \
		-exec rm -rf '{}' + \
	&& rm -rf /usr/src/python
```

-	Created: Wed, 09 Sep 2015 20:36:26 GMT
-	Parent Layer: `64d66dd7866e15b27a77b6c71eb8457b55006824348c6c520cd415e98cd17f61`
-	Docker Version: 1.7.1
-	Virtual Size: 59.6 MB (59555829 bytes)
-	v2 Blob: `sha256:6496ad2256e6de9071b2a9349db0af365f5a5a22511ef6e7582991ea1cd53787`
-	v2 Content-Length: 17.6 MB (17609981 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:44:07 GMT

#### `47ea8143784e4c25b85cc777dc4b4bfc1d86eb25cff33ff74869f7d8f11dc82d`

```dockerfile
RUN cd /usr/local/bin \
	&& ln -s idle3 idle \
	&& ln -s pydoc3 pydoc \
	&& ln -s python3 python \
	&& ln -s python-config3 python-config
```

-	Created: Wed, 09 Sep 2015 20:36:28 GMT
-	Parent Layer: `2d21f69c3d15d951b94bd86e641a37816fbbc6a1c4b244239d1a11da0d912986`
-	Docker Version: 1.7.1
-	Virtual Size: 32.0 B
-	v2 Blob: `sha256:908483e62d3fb557efaa13ba6c493e24b8ea8e5c2cb5dc28daddb580b8bf5d02`
-	v2 Content-Length: 233.0 B
-	v2 Last-Modified: Wed, 09 Sep 2015 21:43:53 GMT

#### `9d7b998c3a50d68bcbe37405a22609eefb466cc266a4aec967935b56010c1fc7`

```dockerfile
CMD ["python3"]
```

-	Created: Wed, 09 Sep 2015 20:36:28 GMT
-	Parent Layer: `47ea8143784e4c25b85cc777dc4b4bfc1d86eb25cff33ff74869f7d8f11dc82d`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `66f3cacd79ce083eb87297dd1e6277543d1c768297c0e8b1dadb214b45cbd023`

```dockerfile
RUN mkdir -p /usr/src/app
```

-	Created: Wed, 09 Sep 2015 20:37:01 GMT
-	Parent Layer: `9d7b998c3a50d68bcbe37405a22609eefb466cc266a4aec967935b56010c1fc7`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:98d137c86f60e69c459fbe66b83ede077147e3eea79d11935b853850ecdf432d`
-	v2 Content-Length: 126.0 B
-	v2 Last-Modified: Wed, 09 Sep 2015 21:45:11 GMT

#### `ba0c7e790c2d724f906f38b3adc2db038ece283a31f6b99f7f86569064451985`

```dockerfile
WORKDIR /usr/src/app
```

-	Created: Wed, 09 Sep 2015 20:37:02 GMT
-	Parent Layer: `66f3cacd79ce083eb87297dd1e6277543d1c768297c0e8b1dadb214b45cbd023`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `f8b72298a13dfa20d3f713fa7cab6bbd88ed064f09201cd1ac376b15fff2e7f0`

```dockerfile
ONBUILD COPY requirements.txt /usr/src/app/
```

-	Created: Wed, 09 Sep 2015 20:37:02 GMT
-	Parent Layer: `ba0c7e790c2d724f906f38b3adc2db038ece283a31f6b99f7f86569064451985`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `44d1f752de730f1125dc65b60ef3a0f695a81cd4362431a73a0b19759c713b29`

```dockerfile
ONBUILD RUN pip install --no-cache-dir -r requirements.txt
```

-	Created: Wed, 09 Sep 2015 20:37:03 GMT
-	Parent Layer: `f8b72298a13dfa20d3f713fa7cab6bbd88ed064f09201cd1ac376b15fff2e7f0`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `5036d5b8a89b14eff2cfc776fc95249b821fb016108f4924a60191236e7e3764`

```dockerfile
ONBUILD COPY . /usr/src/app
```

-	Created: Wed, 09 Sep 2015 20:37:03 GMT
-	Parent Layer: `44d1f752de730f1125dc65b60ef3a0f695a81cd4362431a73a0b19759c713b29`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

## `python:3.2-onbuild`

```console
$ docker pull library/python@sha256:82e9d8fcedc53bbbc3812e0dcaf6c0088fa1b89afdfc947f5a6efa3e686e1e12
```

-	Total Virtual Size: 667.0 MB (667031076 bytes)
-	Total v2 Content-Length: 258.6 MB (258606784 bytes)

### Layers (18)

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
-	v2 Blob: `sha256:b3010ec3eb21ac3df74757a47832fb17395b76ad3a30794074cefd07541d3557`
-	v2 Content-Length: 18.5 MB (18538591 bytes)
-	v2 Last-Modified: Thu, 10 Sep 2015 23:36:30 GMT

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

#### `a7131b97316204530af26e42319aeda8ac44cd5ac2891e5dab45e16deb1e592d`

```dockerfile
RUN apt-get purge -y python.*
```

-	Created: Wed, 09 Sep 2015 20:20:46 GMT
-	Parent Layer: `16b189cc8ce688f9f1d8f1d837fa0891107450a06c795b1cba8f6c33a4454280`
-	Docker Version: 1.7.1
-	Virtual Size: 975.3 KB (975277 bytes)
-	v2 Blob: `sha256:20cdbe5b7a6f64396bcabde9b06c16a0b41e2c7fd39b28eff1ee3670a9f0516e`
-	v2 Content-Length: 220.4 KB (220377 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:29:17 GMT

#### `d7cbb60bc416f832c685b38578b77da5f3716cba15d4bcb45d850809a4c112eb`

```dockerfile
ENV LANG=C.UTF-8
```

-	Created: Wed, 09 Sep 2015 20:20:48 GMT
-	Parent Layer: `a7131b97316204530af26e42319aeda8ac44cd5ac2891e5dab45e16deb1e592d`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `24ccfa7d2e84006ddb7fe42a70e5d6af49675a02e896f98579c26fbcb8e1ae1b`

```dockerfile
RUN gpg --keyserver ha.pool.sks-keyservers.net --recv-keys 26DEA9D4613391EF3E25C9FF0A5B101836580288
```

-	Created: Wed, 09 Sep 2015 20:34:23 GMT
-	Parent Layer: `d7cbb60bc416f832c685b38578b77da5f3716cba15d4bcb45d850809a4c112eb`
-	Docker Version: 1.7.1
-	Virtual Size: 15.0 KB (14980 bytes)
-	v2 Blob: `sha256:c07c8b7cac8f14fa0ddc06c34b533baa07bb4c765c154904e6748bafe3c151b4`
-	v2 Content-Length: 6.8 KB (6815 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:44:13 GMT

#### `4e621e0485f9e56e798ea729bc66dd296184a4d0404b685887e1025402bd5151`

```dockerfile
ENV PYTHON_VERSION=3.2.6
```

-	Created: Wed, 09 Sep 2015 20:34:24 GMT
-	Parent Layer: `24ccfa7d2e84006ddb7fe42a70e5d6af49675a02e896f98579c26fbcb8e1ae1b`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `64d66dd7866e15b27a77b6c71eb8457b55006824348c6c520cd415e98cd17f61`

```dockerfile
ENV PYTHON_PIP_VERSION=7.1.2
```

-	Created: Wed, 09 Sep 2015 20:34:24 GMT
-	Parent Layer: `4e621e0485f9e56e798ea729bc66dd296184a4d0404b685887e1025402bd5151`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `2d21f69c3d15d951b94bd86e641a37816fbbc6a1c4b244239d1a11da0d912986`

```dockerfile
RUN set -x \
	&& mkdir -p /usr/src/python \
	&& curl -SL "https://www.python.org/ftp/python/$PYTHON_VERSION/Python-$PYTHON_VERSION.tar.xz" -o python.tar.xz \
	&& curl -SL "https://www.python.org/ftp/python/$PYTHON_VERSION/Python-$PYTHON_VERSION.tar.xz.asc" -o python.tar.xz.asc \
	&& gpg --verify python.tar.xz.asc \
	&& tar -xJC /usr/src/python --strip-components=1 -f python.tar.xz \
	&& rm python.tar.xz* \
	&& cd /usr/src/python \
	&& ./configure --enable-shared --enable-unicode=ucs4 \
	&& make -j$(nproc) \
	&& make install \
	&& ldconfig \
	&& curl -SL 'https://bootstrap.pypa.io/get-pip.py' | python3 \
	&& pip install --no-cache-dir --upgrade pip==$PYTHON_PIP_VERSION \
	&& find /usr/local \
		\( -type d -a -name test -o -name tests \) \
		-o \( -type f -a -name '*.pyc' -o -name '*.pyo' \) \
		-exec rm -rf '{}' + \
	&& rm -rf /usr/src/python
```

-	Created: Wed, 09 Sep 2015 20:36:26 GMT
-	Parent Layer: `64d66dd7866e15b27a77b6c71eb8457b55006824348c6c520cd415e98cd17f61`
-	Docker Version: 1.7.1
-	Virtual Size: 59.6 MB (59555829 bytes)
-	v2 Blob: `sha256:6496ad2256e6de9071b2a9349db0af365f5a5a22511ef6e7582991ea1cd53787`
-	v2 Content-Length: 17.6 MB (17609981 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:44:07 GMT

#### `47ea8143784e4c25b85cc777dc4b4bfc1d86eb25cff33ff74869f7d8f11dc82d`

```dockerfile
RUN cd /usr/local/bin \
	&& ln -s idle3 idle \
	&& ln -s pydoc3 pydoc \
	&& ln -s python3 python \
	&& ln -s python-config3 python-config
```

-	Created: Wed, 09 Sep 2015 20:36:28 GMT
-	Parent Layer: `2d21f69c3d15d951b94bd86e641a37816fbbc6a1c4b244239d1a11da0d912986`
-	Docker Version: 1.7.1
-	Virtual Size: 32.0 B
-	v2 Blob: `sha256:908483e62d3fb557efaa13ba6c493e24b8ea8e5c2cb5dc28daddb580b8bf5d02`
-	v2 Content-Length: 233.0 B
-	v2 Last-Modified: Wed, 09 Sep 2015 21:43:53 GMT

#### `9d7b998c3a50d68bcbe37405a22609eefb466cc266a4aec967935b56010c1fc7`

```dockerfile
CMD ["python3"]
```

-	Created: Wed, 09 Sep 2015 20:36:28 GMT
-	Parent Layer: `47ea8143784e4c25b85cc777dc4b4bfc1d86eb25cff33ff74869f7d8f11dc82d`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `66f3cacd79ce083eb87297dd1e6277543d1c768297c0e8b1dadb214b45cbd023`

```dockerfile
RUN mkdir -p /usr/src/app
```

-	Created: Wed, 09 Sep 2015 20:37:01 GMT
-	Parent Layer: `9d7b998c3a50d68bcbe37405a22609eefb466cc266a4aec967935b56010c1fc7`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:98d137c86f60e69c459fbe66b83ede077147e3eea79d11935b853850ecdf432d`
-	v2 Content-Length: 126.0 B
-	v2 Last-Modified: Wed, 09 Sep 2015 21:45:11 GMT

#### `ba0c7e790c2d724f906f38b3adc2db038ece283a31f6b99f7f86569064451985`

```dockerfile
WORKDIR /usr/src/app
```

-	Created: Wed, 09 Sep 2015 20:37:02 GMT
-	Parent Layer: `66f3cacd79ce083eb87297dd1e6277543d1c768297c0e8b1dadb214b45cbd023`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `f8b72298a13dfa20d3f713fa7cab6bbd88ed064f09201cd1ac376b15fff2e7f0`

```dockerfile
ONBUILD COPY requirements.txt /usr/src/app/
```

-	Created: Wed, 09 Sep 2015 20:37:02 GMT
-	Parent Layer: `ba0c7e790c2d724f906f38b3adc2db038ece283a31f6b99f7f86569064451985`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `44d1f752de730f1125dc65b60ef3a0f695a81cd4362431a73a0b19759c713b29`

```dockerfile
ONBUILD RUN pip install --no-cache-dir -r requirements.txt
```

-	Created: Wed, 09 Sep 2015 20:37:03 GMT
-	Parent Layer: `f8b72298a13dfa20d3f713fa7cab6bbd88ed064f09201cd1ac376b15fff2e7f0`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `5036d5b8a89b14eff2cfc776fc95249b821fb016108f4924a60191236e7e3764`

```dockerfile
ONBUILD COPY . /usr/src/app
```

-	Created: Wed, 09 Sep 2015 20:37:03 GMT
-	Parent Layer: `44d1f752de730f1125dc65b60ef3a0f695a81cd4362431a73a0b19759c713b29`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

## `python:3.2.6-slim`

```console
$ docker pull library/python@sha256:fdf3a1204136b1419ccf9c9635011df040ccb929b2ecbb7e56c024045fe9a1af
```

-	Total Virtual Size: 196.6 MB (196624539 bytes)
-	Total v2 Content-Length: 74.4 MB (74420646 bytes)

### Layers (11)

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

#### `b724829f2124ff81839118c0bb053554742dae49bcf23847b98264867e4da862`

```dockerfile
RUN apt-get purge -y python.*
```

-	Created: Wed, 09 Sep 2015 20:26:09 GMT
-	Parent Layer: `8c00acfb017549e44d28098762c3e6296872a1ca9b90385855f1019d84bb0dac`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `dad2fc2df4957c05b555a45d00adeaaf624ccce5d9dd557ce4c8548ca40f39f0`

```dockerfile
ENV LANG=C.UTF-8
```

-	Created: Wed, 09 Sep 2015 20:26:10 GMT
-	Parent Layer: `b724829f2124ff81839118c0bb053554742dae49bcf23847b98264867e4da862`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `b4b1929946879d72f7304c436913698e312741961589842913329eb8d746fefa`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		libsqlite3-0 \
		libssl1.0.0 \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Wed, 09 Sep 2015 20:26:51 GMT
-	Parent Layer: `dad2fc2df4957c05b555a45d00adeaaf624ccce5d9dd557ce4c8548ca40f39f0`
-	Docker Version: 1.7.1
-	Virtual Size: 7.4 MB (7441496 bytes)
-	v2 Blob: `sha256:aebbd0bd409f97875c3b3bcf8f57e315ba2ef8d3c4a54f81a7f71cfcf80bf4c9`
-	v2 Content-Length: 3.3 MB (3316296 bytes)
-	v2 Last-Modified: Fri, 11 Sep 2015 00:01:36 GMT

#### `2c2bc18871d5df288fd24c76c61faddee6ecd04bcf69bab5628d94c88dc41235`

```dockerfile
RUN gpg --keyserver ha.pool.sks-keyservers.net --recv-keys 26DEA9D4613391EF3E25C9FF0A5B101836580288
```

-	Created: Wed, 09 Sep 2015 20:37:34 GMT
-	Parent Layer: `b4b1929946879d72f7304c436913698e312741961589842913329eb8d746fefa`
-	Docker Version: 1.7.1
-	Virtual Size: 15.0 KB (14980 bytes)
-	v2 Blob: `sha256:c9d4d35a9638b3eadf5e21a15c542f07e055bea1e341024a7d80ff99656dcd47`
-	v2 Content-Length: 6.8 KB (6814 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:46:21 GMT

#### `e2bc6065efeea71f26ea4738004d5f1cf42d52d3decdfd288218e2fd4586e258`

```dockerfile
ENV PYTHON_VERSION=3.2.6
```

-	Created: Wed, 09 Sep 2015 20:37:34 GMT
-	Parent Layer: `2c2bc18871d5df288fd24c76c61faddee6ecd04bcf69bab5628d94c88dc41235`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `592815c4e11e19a7a656c37da2723c2803c242fa94c29157960a6570ab7909d1`

```dockerfile
ENV PYTHON_PIP_VERSION=7.1.2
```

-	Created: Wed, 09 Sep 2015 20:37:35 GMT
-	Parent Layer: `e2bc6065efeea71f26ea4738004d5f1cf42d52d3decdfd288218e2fd4586e258`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `9a8108479778d49593de867bb5aea41bd3b62df5b0278021dba384130e322d40`

```dockerfile
RUN set -x \
	&& buildDeps=' \
		curl \
		gcc \
		libbz2-dev \
		libc6-dev \
		libncurses-dev \
		libreadline-dev \
		libsqlite3-dev \
		libssl-dev \
		make \
		xz-utils \
		zlib1g-dev \
	' \
	&& apt-get update && apt-get install -y $buildDeps --no-install-recommends && rm -rf /var/lib/apt/lists/* \
	&& mkdir -p /usr/src/python \
	&& curl -SL "https://www.python.org/ftp/python/$PYTHON_VERSION/Python-$PYTHON_VERSION.tar.xz" -o python.tar.xz \
	&& curl -SL "https://www.python.org/ftp/python/$PYTHON_VERSION/Python-$PYTHON_VERSION.tar.xz.asc" -o python.tar.xz.asc \
	&& gpg --verify python.tar.xz.asc \
	&& tar -xJC /usr/src/python --strip-components=1 -f python.tar.xz \
	&& rm python.tar.xz* \
	&& cd /usr/src/python \
	&& ./configure --enable-shared --enable-unicode=ucs4 \
	&& make -j$(nproc) \
	&& make install \
	&& ldconfig \
	&& curl -SL 'https://bootstrap.pypa.io/get-pip.py' | python3 \
	&& pip install --no-cache-dir --upgrade pip==$PYTHON_PIP_VERSION \
	&& find /usr/local \
		\( -type d -a -name test -o -name tests \) \
		-o \( -type f -a -name '*.pyc' -o -name '*.pyo' \) \
		-exec rm -rf '{}' + \
	&& apt-get purge -y --auto-remove $buildDeps \
	&& rm -rf /usr/src/python
```

-	Created: Wed, 09 Sep 2015 20:40:29 GMT
-	Parent Layer: `592815c4e11e19a7a656c37da2723c2803c242fa94c29157960a6570ab7909d1`
-	Docker Version: 1.7.1
-	Virtual Size: 64.0 MB (64008900 bytes)
-	v2 Blob: `sha256:e05ffea6ca793ea06134603ba50037e50398d802e3ea0bfcf51f03ced5a22a12`
-	v2 Content-Length: 19.7 MB (19737399 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:46:16 GMT

#### `e2fa17173504a972797f2a3945ed712e3d21a17bbeff0a41583d3699fefaf27f`

```dockerfile
RUN cd /usr/local/bin \
	&& ln -s idle3 idle \
	&& ln -s pydoc3 pydoc \
	&& ln -s python3 python \
	&& ln -s python-config3 python-config
```

-	Created: Wed, 09 Sep 2015 20:40:31 GMT
-	Parent Layer: `9a8108479778d49593de867bb5aea41bd3b62df5b0278021dba384130e322d40`
-	Docker Version: 1.7.1
-	Virtual Size: 32.0 B
-	v2 Blob: `sha256:cee1548feb272910b6a56cf5039e342086106d900e6504304c5577c7a1750268`
-	v2 Content-Length: 237.0 B
-	v2 Last-Modified: Wed, 09 Sep 2015 21:45:58 GMT

#### `cec8bc4a7274a8ef01059cfdd6be912c48987275924dbb4a6bdf4b0a27c58d6d`

```dockerfile
CMD ["python3"]
```

-	Created: Wed, 09 Sep 2015 20:40:31 GMT
-	Parent Layer: `e2fa17173504a972797f2a3945ed712e3d21a17bbeff0a41583d3699fefaf27f`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

## `python:3.2-slim`

```console
$ docker pull library/python@sha256:c8464df1389a8530719b09624e9ab4d0955c5f3108b9bcaec2841006b51bc2d4
```

-	Total Virtual Size: 196.6 MB (196624539 bytes)
-	Total v2 Content-Length: 74.4 MB (74420646 bytes)

### Layers (11)

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

#### `b724829f2124ff81839118c0bb053554742dae49bcf23847b98264867e4da862`

```dockerfile
RUN apt-get purge -y python.*
```

-	Created: Wed, 09 Sep 2015 20:26:09 GMT
-	Parent Layer: `8c00acfb017549e44d28098762c3e6296872a1ca9b90385855f1019d84bb0dac`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `dad2fc2df4957c05b555a45d00adeaaf624ccce5d9dd557ce4c8548ca40f39f0`

```dockerfile
ENV LANG=C.UTF-8
```

-	Created: Wed, 09 Sep 2015 20:26:10 GMT
-	Parent Layer: `b724829f2124ff81839118c0bb053554742dae49bcf23847b98264867e4da862`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `b4b1929946879d72f7304c436913698e312741961589842913329eb8d746fefa`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		libsqlite3-0 \
		libssl1.0.0 \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Wed, 09 Sep 2015 20:26:51 GMT
-	Parent Layer: `dad2fc2df4957c05b555a45d00adeaaf624ccce5d9dd557ce4c8548ca40f39f0`
-	Docker Version: 1.7.1
-	Virtual Size: 7.4 MB (7441496 bytes)
-	v2 Blob: `sha256:aebbd0bd409f97875c3b3bcf8f57e315ba2ef8d3c4a54f81a7f71cfcf80bf4c9`
-	v2 Content-Length: 3.3 MB (3316296 bytes)
-	v2 Last-Modified: Fri, 11 Sep 2015 00:01:36 GMT

#### `2c2bc18871d5df288fd24c76c61faddee6ecd04bcf69bab5628d94c88dc41235`

```dockerfile
RUN gpg --keyserver ha.pool.sks-keyservers.net --recv-keys 26DEA9D4613391EF3E25C9FF0A5B101836580288
```

-	Created: Wed, 09 Sep 2015 20:37:34 GMT
-	Parent Layer: `b4b1929946879d72f7304c436913698e312741961589842913329eb8d746fefa`
-	Docker Version: 1.7.1
-	Virtual Size: 15.0 KB (14980 bytes)
-	v2 Blob: `sha256:c9d4d35a9638b3eadf5e21a15c542f07e055bea1e341024a7d80ff99656dcd47`
-	v2 Content-Length: 6.8 KB (6814 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:46:21 GMT

#### `e2bc6065efeea71f26ea4738004d5f1cf42d52d3decdfd288218e2fd4586e258`

```dockerfile
ENV PYTHON_VERSION=3.2.6
```

-	Created: Wed, 09 Sep 2015 20:37:34 GMT
-	Parent Layer: `2c2bc18871d5df288fd24c76c61faddee6ecd04bcf69bab5628d94c88dc41235`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `592815c4e11e19a7a656c37da2723c2803c242fa94c29157960a6570ab7909d1`

```dockerfile
ENV PYTHON_PIP_VERSION=7.1.2
```

-	Created: Wed, 09 Sep 2015 20:37:35 GMT
-	Parent Layer: `e2bc6065efeea71f26ea4738004d5f1cf42d52d3decdfd288218e2fd4586e258`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `9a8108479778d49593de867bb5aea41bd3b62df5b0278021dba384130e322d40`

```dockerfile
RUN set -x \
	&& buildDeps=' \
		curl \
		gcc \
		libbz2-dev \
		libc6-dev \
		libncurses-dev \
		libreadline-dev \
		libsqlite3-dev \
		libssl-dev \
		make \
		xz-utils \
		zlib1g-dev \
	' \
	&& apt-get update && apt-get install -y $buildDeps --no-install-recommends && rm -rf /var/lib/apt/lists/* \
	&& mkdir -p /usr/src/python \
	&& curl -SL "https://www.python.org/ftp/python/$PYTHON_VERSION/Python-$PYTHON_VERSION.tar.xz" -o python.tar.xz \
	&& curl -SL "https://www.python.org/ftp/python/$PYTHON_VERSION/Python-$PYTHON_VERSION.tar.xz.asc" -o python.tar.xz.asc \
	&& gpg --verify python.tar.xz.asc \
	&& tar -xJC /usr/src/python --strip-components=1 -f python.tar.xz \
	&& rm python.tar.xz* \
	&& cd /usr/src/python \
	&& ./configure --enable-shared --enable-unicode=ucs4 \
	&& make -j$(nproc) \
	&& make install \
	&& ldconfig \
	&& curl -SL 'https://bootstrap.pypa.io/get-pip.py' | python3 \
	&& pip install --no-cache-dir --upgrade pip==$PYTHON_PIP_VERSION \
	&& find /usr/local \
		\( -type d -a -name test -o -name tests \) \
		-o \( -type f -a -name '*.pyc' -o -name '*.pyo' \) \
		-exec rm -rf '{}' + \
	&& apt-get purge -y --auto-remove $buildDeps \
	&& rm -rf /usr/src/python
```

-	Created: Wed, 09 Sep 2015 20:40:29 GMT
-	Parent Layer: `592815c4e11e19a7a656c37da2723c2803c242fa94c29157960a6570ab7909d1`
-	Docker Version: 1.7.1
-	Virtual Size: 64.0 MB (64008900 bytes)
-	v2 Blob: `sha256:e05ffea6ca793ea06134603ba50037e50398d802e3ea0bfcf51f03ced5a22a12`
-	v2 Content-Length: 19.7 MB (19737399 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:46:16 GMT

#### `e2fa17173504a972797f2a3945ed712e3d21a17bbeff0a41583d3699fefaf27f`

```dockerfile
RUN cd /usr/local/bin \
	&& ln -s idle3 idle \
	&& ln -s pydoc3 pydoc \
	&& ln -s python3 python \
	&& ln -s python-config3 python-config
```

-	Created: Wed, 09 Sep 2015 20:40:31 GMT
-	Parent Layer: `9a8108479778d49593de867bb5aea41bd3b62df5b0278021dba384130e322d40`
-	Docker Version: 1.7.1
-	Virtual Size: 32.0 B
-	v2 Blob: `sha256:cee1548feb272910b6a56cf5039e342086106d900e6504304c5577c7a1750268`
-	v2 Content-Length: 237.0 B
-	v2 Last-Modified: Wed, 09 Sep 2015 21:45:58 GMT

#### `cec8bc4a7274a8ef01059cfdd6be912c48987275924dbb4a6bdf4b0a27c58d6d`

```dockerfile
CMD ["python3"]
```

-	Created: Wed, 09 Sep 2015 20:40:31 GMT
-	Parent Layer: `e2fa17173504a972797f2a3945ed712e3d21a17bbeff0a41583d3699fefaf27f`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

## `python:3.2.6-wheezy`

```console
$ docker pull library/python@sha256:095f28f7cba71fab90713807464d2df51bf54d6298d2f8e2938ba129347f6509
```

-	Total Virtual Size: 521.2 MB (521167114 bytes)
-	Total v2 Content-Length: 193.3 MB (193288097 bytes)

### Layers (13)

#### `ba249489d0b6512128b60a4910e78fa2000c785d59e0599188a6802bd01155f2`

```dockerfile
ADD file:b908886c97e2b96665b7afc54ff53ebaef1c62896cf83a1199e59fceff1dafb5 in /
```

-	Created: Mon, 07 Sep 2015 23:37:10 GMT
-	Docker Version: 1.7.1
-	Virtual Size: 84.9 MB (84924773 bytes)
-	v2 Blob: `sha256:8f47f7c36e4382b4569bfe8858c0b371313e9c47a72867d69b000949c53637c9`
-	v2 Content-Length: 37.2 MB (37191761 bytes)
-	v2 Last-Modified: Mon, 07 Sep 2015 23:46:29 GMT

#### `19de96c112fcca5b6de16611dc0a359b0b977c551921ca79ac5cf4a8bfff9351`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Mon, 07 Sep 2015 23:37:11 GMT
-	Parent Layer: `ba249489d0b6512128b60a4910e78fa2000c785d59e0599188a6802bd01155f2`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `e83e5b7f7d01ffa47e46b7234799f12d842089df890db8fae765c5a4df26a20b`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 08 Sep 2015 15:38:48 GMT
-	Parent Layer: `19de96c112fcca5b6de16611dc0a359b0b977c551921ca79ac5cf4a8bfff9351`
-	Docker Version: 1.7.1
-	Virtual Size: 14.2 MB (14239819 bytes)
-	v2 Blob: `sha256:7a11528d019acc2b739bd4c1a7e518e247f729fdad40490be9d9fdb13e85c8c8`
-	v2 Content-Length: 6.7 MB (6739553 bytes)
-	v2 Last-Modified: Thu, 10 Sep 2015 23:43:23 GMT

#### `d6b70cefe2bfb76216c96acb6a6c6350eedff489df914b2606b1005e70f73a00`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 08 Sep 2015 15:39:23 GMT
-	Parent Layer: `e83e5b7f7d01ffa47e46b7234799f12d842089df890db8fae765c5a4df26a20b`
-	Docker Version: 1.7.1
-	Virtual Size: 109.4 MB (109431259 bytes)
-	v2 Blob: `sha256:4224b2b7563f71616cbe9215abf5276c51b18d3ceead85a56526519b5391a75f`
-	v2 Content-Length: 37.0 MB (37046780 bytes)
-	v2 Last-Modified: Tue, 08 Sep 2015 16:02:41 GMT

#### `3a5282506aa21c7b21cfdad32a099497bf9839dbc5e427f79bdad6a5e109f3d3`

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

-	Created: Tue, 08 Sep 2015 15:41:19 GMT
-	Parent Layer: `d6b70cefe2bfb76216c96acb6a6c6350eedff489df914b2606b1005e70f73a00`
-	Docker Version: 1.7.1
-	Virtual Size: 250.6 MB (250569275 bytes)
-	v2 Blob: `sha256:89989badb2c249165ed907bdf03e38dffbaefd3c115ad32ac6cf53ebbafab33b`
-	v2 Content-Length: 94.3 MB (94261782 bytes)
-	v2 Last-Modified: Tue, 08 Sep 2015 16:03:53 GMT

#### `1046da491d81f106d762e20009d4dfff16da8b2af4eafc70cba44ca74f7dc53e`

```dockerfile
RUN apt-get purge -y python.*
```

-	Created: Wed, 09 Sep 2015 20:31:23 GMT
-	Parent Layer: `3a5282506aa21c7b21cfdad32a099497bf9839dbc5e427f79bdad6a5e109f3d3`
-	Docker Version: 1.7.1
-	Virtual Size: 833.7 KB (833724 bytes)
-	v2 Blob: `sha256:9bab6257d36f85970d8effd469dcd7c7a44ab5de929035933d165b6a35929905`
-	v2 Content-Length: 196.8 KB (196778 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:39:13 GMT

#### `498b8d9d85457c4a520c8678c4ce95829605287dfb5ca8f39586b76666d446ab`

```dockerfile
ENV LANG=C.UTF-8
```

-	Created: Wed, 09 Sep 2015 20:31:23 GMT
-	Parent Layer: `1046da491d81f106d762e20009d4dfff16da8b2af4eafc70cba44ca74f7dc53e`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `bce93d89f9c65e5a344ec2e9d57734f0693056a26b359e447408176c63582e4c`

```dockerfile
RUN gpg --keyserver ha.pool.sks-keyservers.net --recv-keys 26DEA9D4613391EF3E25C9FF0A5B101836580288
```

-	Created: Wed, 09 Sep 2015 20:41:11 GMT
-	Parent Layer: `498b8d9d85457c4a520c8678c4ce95829605287dfb5ca8f39586b76666d446ab`
-	Docker Version: 1.7.1
-	Virtual Size: 15.0 KB (14980 bytes)
-	v2 Blob: `sha256:1f31a23778aae08c9fe6fd02507c417d1c8c573a558b912caf06bb1f71dbc5e2`
-	v2 Content-Length: 6.8 KB (6814 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:48:00 GMT

#### `5d0194bfa0915fc59b74f613f41f61bb273567900f10bfc1bc3f1032d0cf011a`

```dockerfile
ENV PYTHON_VERSION=3.2.6
```

-	Created: Wed, 09 Sep 2015 20:41:11 GMT
-	Parent Layer: `bce93d89f9c65e5a344ec2e9d57734f0693056a26b359e447408176c63582e4c`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `598f1666a101fd7b19689c0c0309fd5c87ac0462ab0deb8c9a87027a35557a8e`

```dockerfile
ENV PYTHON_PIP_VERSION=7.1.2
```

-	Created: Wed, 09 Sep 2015 20:41:11 GMT
-	Parent Layer: `5d0194bfa0915fc59b74f613f41f61bb273567900f10bfc1bc3f1032d0cf011a`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `e5822cd720fdea4af1d7f3eeddf0eb96cec9f3caff3210c453b009469c49f22f`

```dockerfile
RUN set -x \
	&& mkdir -p /usr/src/python \
	&& curl -SL "https://www.python.org/ftp/python/$PYTHON_VERSION/Python-$PYTHON_VERSION.tar.xz" -o python.tar.xz \
	&& curl -SL "https://www.python.org/ftp/python/$PYTHON_VERSION/Python-$PYTHON_VERSION.tar.xz.asc" -o python.tar.xz.asc \
	&& gpg --verify python.tar.xz.asc \
	&& tar -xJC /usr/src/python --strip-components=1 -f python.tar.xz \
	&& rm python.tar.xz* \
	&& cd /usr/src/python \
	&& ./configure --enable-shared --enable-unicode=ucs4 \
	&& make -j$(nproc) \
	&& make install \
	&& ldconfig \
	&& curl -SL 'https://bootstrap.pypa.io/get-pip.py' | python3 \
	&& pip install --no-cache-dir --upgrade pip==$PYTHON_PIP_VERSION \
	&& find /usr/local \
		\( -type d -a -name test -o -name tests \) \
		-o \( -type f -a -name '*.pyc' -o -name '*.pyo' \) \
		-exec rm -rf '{}' + \
	&& rm -rf /usr/src/python
```

-	Created: Wed, 09 Sep 2015 20:42:56 GMT
-	Parent Layer: `598f1666a101fd7b19689c0c0309fd5c87ac0462ab0deb8c9a87027a35557a8e`
-	Docker Version: 1.7.1
-	Virtual Size: 61.2 MB (61153252 bytes)
-	v2 Blob: `sha256:8ad65be8daff2b01acf8ca8e952a1b3a148261916135237f64a6337ddab7156d`
-	v2 Content-Length: 17.8 MB (17844233 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:47:52 GMT

#### `fe76e491c6caf900d2aa0d94d43afbf73c41cedc1460cf0dda5b5d1de2649770`

```dockerfile
RUN cd /usr/local/bin \
	&& ln -s idle3 idle \
	&& ln -s pydoc3 pydoc \
	&& ln -s python3 python \
	&& ln -s python-config3 python-config
```

-	Created: Wed, 09 Sep 2015 20:42:58 GMT
-	Parent Layer: `e5822cd720fdea4af1d7f3eeddf0eb96cec9f3caff3210c453b009469c49f22f`
-	Docker Version: 1.7.1
-	Virtual Size: 32.0 B
-	v2 Blob: `sha256:37d1c3b86deeae75a236c9b3574e4a92d90013ad279b73bcae3c522cdbcfdda3`
-	v2 Content-Length: 236.0 B
-	v2 Last-Modified: Wed, 09 Sep 2015 21:47:38 GMT

#### `bd1179182a22b9d3e860cfe5a3d7555bbef426fd2bfe72d1d8eca4e50bb70dfb`

```dockerfile
CMD ["python3"]
```

-	Created: Wed, 09 Sep 2015 20:42:59 GMT
-	Parent Layer: `fe76e491c6caf900d2aa0d94d43afbf73c41cedc1460cf0dda5b5d1de2649770`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

## `python:3.2-wheezy`

```console
$ docker pull library/python@sha256:2bf47afd32c1274c64358c2cbe35f4826d6b4eef16fa0e52cdb5007017f707a9
```

-	Total Virtual Size: 521.2 MB (521167114 bytes)
-	Total v2 Content-Length: 193.3 MB (193288097 bytes)

### Layers (13)

#### `ba249489d0b6512128b60a4910e78fa2000c785d59e0599188a6802bd01155f2`

```dockerfile
ADD file:b908886c97e2b96665b7afc54ff53ebaef1c62896cf83a1199e59fceff1dafb5 in /
```

-	Created: Mon, 07 Sep 2015 23:37:10 GMT
-	Docker Version: 1.7.1
-	Virtual Size: 84.9 MB (84924773 bytes)
-	v2 Blob: `sha256:8f47f7c36e4382b4569bfe8858c0b371313e9c47a72867d69b000949c53637c9`
-	v2 Content-Length: 37.2 MB (37191761 bytes)
-	v2 Last-Modified: Mon, 07 Sep 2015 23:46:29 GMT

#### `19de96c112fcca5b6de16611dc0a359b0b977c551921ca79ac5cf4a8bfff9351`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Mon, 07 Sep 2015 23:37:11 GMT
-	Parent Layer: `ba249489d0b6512128b60a4910e78fa2000c785d59e0599188a6802bd01155f2`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `e83e5b7f7d01ffa47e46b7234799f12d842089df890db8fae765c5a4df26a20b`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 08 Sep 2015 15:38:48 GMT
-	Parent Layer: `19de96c112fcca5b6de16611dc0a359b0b977c551921ca79ac5cf4a8bfff9351`
-	Docker Version: 1.7.1
-	Virtual Size: 14.2 MB (14239819 bytes)
-	v2 Blob: `sha256:7a11528d019acc2b739bd4c1a7e518e247f729fdad40490be9d9fdb13e85c8c8`
-	v2 Content-Length: 6.7 MB (6739553 bytes)
-	v2 Last-Modified: Thu, 10 Sep 2015 23:43:23 GMT

#### `d6b70cefe2bfb76216c96acb6a6c6350eedff489df914b2606b1005e70f73a00`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 08 Sep 2015 15:39:23 GMT
-	Parent Layer: `e83e5b7f7d01ffa47e46b7234799f12d842089df890db8fae765c5a4df26a20b`
-	Docker Version: 1.7.1
-	Virtual Size: 109.4 MB (109431259 bytes)
-	v2 Blob: `sha256:4224b2b7563f71616cbe9215abf5276c51b18d3ceead85a56526519b5391a75f`
-	v2 Content-Length: 37.0 MB (37046780 bytes)
-	v2 Last-Modified: Tue, 08 Sep 2015 16:02:41 GMT

#### `3a5282506aa21c7b21cfdad32a099497bf9839dbc5e427f79bdad6a5e109f3d3`

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

-	Created: Tue, 08 Sep 2015 15:41:19 GMT
-	Parent Layer: `d6b70cefe2bfb76216c96acb6a6c6350eedff489df914b2606b1005e70f73a00`
-	Docker Version: 1.7.1
-	Virtual Size: 250.6 MB (250569275 bytes)
-	v2 Blob: `sha256:89989badb2c249165ed907bdf03e38dffbaefd3c115ad32ac6cf53ebbafab33b`
-	v2 Content-Length: 94.3 MB (94261782 bytes)
-	v2 Last-Modified: Tue, 08 Sep 2015 16:03:53 GMT

#### `1046da491d81f106d762e20009d4dfff16da8b2af4eafc70cba44ca74f7dc53e`

```dockerfile
RUN apt-get purge -y python.*
```

-	Created: Wed, 09 Sep 2015 20:31:23 GMT
-	Parent Layer: `3a5282506aa21c7b21cfdad32a099497bf9839dbc5e427f79bdad6a5e109f3d3`
-	Docker Version: 1.7.1
-	Virtual Size: 833.7 KB (833724 bytes)
-	v2 Blob: `sha256:9bab6257d36f85970d8effd469dcd7c7a44ab5de929035933d165b6a35929905`
-	v2 Content-Length: 196.8 KB (196778 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:39:13 GMT

#### `498b8d9d85457c4a520c8678c4ce95829605287dfb5ca8f39586b76666d446ab`

```dockerfile
ENV LANG=C.UTF-8
```

-	Created: Wed, 09 Sep 2015 20:31:23 GMT
-	Parent Layer: `1046da491d81f106d762e20009d4dfff16da8b2af4eafc70cba44ca74f7dc53e`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `bce93d89f9c65e5a344ec2e9d57734f0693056a26b359e447408176c63582e4c`

```dockerfile
RUN gpg --keyserver ha.pool.sks-keyservers.net --recv-keys 26DEA9D4613391EF3E25C9FF0A5B101836580288
```

-	Created: Wed, 09 Sep 2015 20:41:11 GMT
-	Parent Layer: `498b8d9d85457c4a520c8678c4ce95829605287dfb5ca8f39586b76666d446ab`
-	Docker Version: 1.7.1
-	Virtual Size: 15.0 KB (14980 bytes)
-	v2 Blob: `sha256:1f31a23778aae08c9fe6fd02507c417d1c8c573a558b912caf06bb1f71dbc5e2`
-	v2 Content-Length: 6.8 KB (6814 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:48:00 GMT

#### `5d0194bfa0915fc59b74f613f41f61bb273567900f10bfc1bc3f1032d0cf011a`

```dockerfile
ENV PYTHON_VERSION=3.2.6
```

-	Created: Wed, 09 Sep 2015 20:41:11 GMT
-	Parent Layer: `bce93d89f9c65e5a344ec2e9d57734f0693056a26b359e447408176c63582e4c`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `598f1666a101fd7b19689c0c0309fd5c87ac0462ab0deb8c9a87027a35557a8e`

```dockerfile
ENV PYTHON_PIP_VERSION=7.1.2
```

-	Created: Wed, 09 Sep 2015 20:41:11 GMT
-	Parent Layer: `5d0194bfa0915fc59b74f613f41f61bb273567900f10bfc1bc3f1032d0cf011a`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `e5822cd720fdea4af1d7f3eeddf0eb96cec9f3caff3210c453b009469c49f22f`

```dockerfile
RUN set -x \
	&& mkdir -p /usr/src/python \
	&& curl -SL "https://www.python.org/ftp/python/$PYTHON_VERSION/Python-$PYTHON_VERSION.tar.xz" -o python.tar.xz \
	&& curl -SL "https://www.python.org/ftp/python/$PYTHON_VERSION/Python-$PYTHON_VERSION.tar.xz.asc" -o python.tar.xz.asc \
	&& gpg --verify python.tar.xz.asc \
	&& tar -xJC /usr/src/python --strip-components=1 -f python.tar.xz \
	&& rm python.tar.xz* \
	&& cd /usr/src/python \
	&& ./configure --enable-shared --enable-unicode=ucs4 \
	&& make -j$(nproc) \
	&& make install \
	&& ldconfig \
	&& curl -SL 'https://bootstrap.pypa.io/get-pip.py' | python3 \
	&& pip install --no-cache-dir --upgrade pip==$PYTHON_PIP_VERSION \
	&& find /usr/local \
		\( -type d -a -name test -o -name tests \) \
		-o \( -type f -a -name '*.pyc' -o -name '*.pyo' \) \
		-exec rm -rf '{}' + \
	&& rm -rf /usr/src/python
```

-	Created: Wed, 09 Sep 2015 20:42:56 GMT
-	Parent Layer: `598f1666a101fd7b19689c0c0309fd5c87ac0462ab0deb8c9a87027a35557a8e`
-	Docker Version: 1.7.1
-	Virtual Size: 61.2 MB (61153252 bytes)
-	v2 Blob: `sha256:8ad65be8daff2b01acf8ca8e952a1b3a148261916135237f64a6337ddab7156d`
-	v2 Content-Length: 17.8 MB (17844233 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:47:52 GMT

#### `fe76e491c6caf900d2aa0d94d43afbf73c41cedc1460cf0dda5b5d1de2649770`

```dockerfile
RUN cd /usr/local/bin \
	&& ln -s idle3 idle \
	&& ln -s pydoc3 pydoc \
	&& ln -s python3 python \
	&& ln -s python-config3 python-config
```

-	Created: Wed, 09 Sep 2015 20:42:58 GMT
-	Parent Layer: `e5822cd720fdea4af1d7f3eeddf0eb96cec9f3caff3210c453b009469c49f22f`
-	Docker Version: 1.7.1
-	Virtual Size: 32.0 B
-	v2 Blob: `sha256:37d1c3b86deeae75a236c9b3574e4a92d90013ad279b73bcae3c522cdbcfdda3`
-	v2 Content-Length: 236.0 B
-	v2 Last-Modified: Wed, 09 Sep 2015 21:47:38 GMT

#### `bd1179182a22b9d3e860cfe5a3d7555bbef426fd2bfe72d1d8eca4e50bb70dfb`

```dockerfile
CMD ["python3"]
```

-	Created: Wed, 09 Sep 2015 20:42:59 GMT
-	Parent Layer: `fe76e491c6caf900d2aa0d94d43afbf73c41cedc1460cf0dda5b5d1de2649770`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

## `python:3.3.6`

```console
$ docker pull library/python@sha256:f021908449aaa86efe229c5b5c911c7222861ae5716dd0d2c0bf351fbc357f68
```

-	Total Virtual Size: 679.1 MB (679148626 bytes)
-	Total v2 Content-Length: 261.6 MB (261622402 bytes)

### Layers (13)

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
-	v2 Blob: `sha256:b3010ec3eb21ac3df74757a47832fb17395b76ad3a30794074cefd07541d3557`
-	v2 Content-Length: 18.5 MB (18538591 bytes)
-	v2 Last-Modified: Thu, 10 Sep 2015 23:36:30 GMT

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

#### `a7131b97316204530af26e42319aeda8ac44cd5ac2891e5dab45e16deb1e592d`

```dockerfile
RUN apt-get purge -y python.*
```

-	Created: Wed, 09 Sep 2015 20:20:46 GMT
-	Parent Layer: `16b189cc8ce688f9f1d8f1d837fa0891107450a06c795b1cba8f6c33a4454280`
-	Docker Version: 1.7.1
-	Virtual Size: 975.3 KB (975277 bytes)
-	v2 Blob: `sha256:20cdbe5b7a6f64396bcabde9b06c16a0b41e2c7fd39b28eff1ee3670a9f0516e`
-	v2 Content-Length: 220.4 KB (220377 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:29:17 GMT

#### `d7cbb60bc416f832c685b38578b77da5f3716cba15d4bcb45d850809a4c112eb`

```dockerfile
ENV LANG=C.UTF-8
```

-	Created: Wed, 09 Sep 2015 20:20:48 GMT
-	Parent Layer: `a7131b97316204530af26e42319aeda8ac44cd5ac2891e5dab45e16deb1e592d`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `24ccfa7d2e84006ddb7fe42a70e5d6af49675a02e896f98579c26fbcb8e1ae1b`

```dockerfile
RUN gpg --keyserver ha.pool.sks-keyservers.net --recv-keys 26DEA9D4613391EF3E25C9FF0A5B101836580288
```

-	Created: Wed, 09 Sep 2015 20:34:23 GMT
-	Parent Layer: `d7cbb60bc416f832c685b38578b77da5f3716cba15d4bcb45d850809a4c112eb`
-	Docker Version: 1.7.1
-	Virtual Size: 15.0 KB (14980 bytes)
-	v2 Blob: `sha256:c07c8b7cac8f14fa0ddc06c34b533baa07bb4c765c154904e6748bafe3c151b4`
-	v2 Content-Length: 6.8 KB (6815 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:44:13 GMT

#### `3b9b8d77de064485669ee0ff4273ac2745cbd746eceaa2da574f5f60da63836a`

```dockerfile
ENV PYTHON_VERSION=3.3.6
```

-	Created: Wed, 09 Sep 2015 20:43:35 GMT
-	Parent Layer: `24ccfa7d2e84006ddb7fe42a70e5d6af49675a02e896f98579c26fbcb8e1ae1b`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `a69216da9262bf5f4fac6fc6250af78379855a2349c4f157ae6f946bbba8b3cf`

```dockerfile
ENV PYTHON_PIP_VERSION=7.1.2
```

-	Created: Wed, 09 Sep 2015 20:43:35 GMT
-	Parent Layer: `3b9b8d77de064485669ee0ff4273ac2745cbd746eceaa2da574f5f60da63836a`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `49566fb299de780693bed214047c9d8e83eeca02b0224d79737b09bffa2b754f`

```dockerfile
RUN set -x \
	&& mkdir -p /usr/src/python \
	&& curl -SL "https://www.python.org/ftp/python/$PYTHON_VERSION/Python-$PYTHON_VERSION.tar.xz" -o python.tar.xz \
	&& curl -SL "https://www.python.org/ftp/python/$PYTHON_VERSION/Python-$PYTHON_VERSION.tar.xz.asc" -o python.tar.xz.asc \
	&& gpg --verify python.tar.xz.asc \
	&& tar -xJC /usr/src/python --strip-components=1 -f python.tar.xz \
	&& rm python.tar.xz* \
	&& cd /usr/src/python \
	&& ./configure --enable-shared --enable-unicode=ucs4 \
	&& make -j$(nproc) \
	&& make install \
	&& ldconfig \
	&& curl -SL 'https://bootstrap.pypa.io/get-pip.py' | python3 \
	&& pip install --no-cache-dir --upgrade pip==$PYTHON_PIP_VERSION \
	&& find /usr/local \
		\( -type d -a -name test -o -name tests \) \
		-o \( -type f -a -name '*.pyc' -o -name '*.pyo' \) \
		-exec rm -rf '{}' + \
	&& rm -rf /usr/src/python
```

-	Created: Wed, 09 Sep 2015 20:45:58 GMT
-	Parent Layer: `a69216da9262bf5f4fac6fc6250af78379855a2349c4f157ae6f946bbba8b3cf`
-	Docker Version: 1.7.1
-	Virtual Size: 71.7 MB (71673379 bytes)
-	v2 Blob: `sha256:fa9ced702b0a8295fa8aa4832581e1e4ce486bcb570bd0ec3a0f517feae13a56`
-	v2 Content-Length: 20.6 MB (20625849 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:49:53 GMT

#### `fd22a25847dcffcd81ffe7682e747ac15d807708f361859c14cb0aaac090ad50`

```dockerfile
RUN cd /usr/local/bin \
	&& ln -s idle3 idle \
	&& ln -s pydoc3 pydoc \
	&& ln -s python3 python \
	&& ln -s python-config3 python-config
```

-	Created: Wed, 09 Sep 2015 20:46:00 GMT
-	Parent Layer: `49566fb299de780693bed214047c9d8e83eeca02b0224d79737b09bffa2b754f`
-	Docker Version: 1.7.1
-	Virtual Size: 32.0 B
-	v2 Blob: `sha256:ff7f8f424177b190ca280cc80bd7bf01c4f9ef36221ebd2490d5af748b06a11b`
-	v2 Content-Length: 237.0 B
-	v2 Last-Modified: Wed, 09 Sep 2015 21:49:33 GMT

#### `2f80de19963c73d9cf6c63554e866ea9fe840481d3aba22a6685632b4bec9494`

```dockerfile
CMD ["python3"]
```

-	Created: Wed, 09 Sep 2015 20:46:00 GMT
-	Parent Layer: `fd22a25847dcffcd81ffe7682e747ac15d807708f361859c14cb0aaac090ad50`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

## `python:3.3`

```console
$ docker pull library/python@sha256:8c85b1e9609822f43a76452af094b0f1857813a6b3b7992dfc7c6535d03d242a
```

-	Total Virtual Size: 679.1 MB (679148626 bytes)
-	Total v2 Content-Length: 261.6 MB (261622402 bytes)

### Layers (13)

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
-	v2 Blob: `sha256:b3010ec3eb21ac3df74757a47832fb17395b76ad3a30794074cefd07541d3557`
-	v2 Content-Length: 18.5 MB (18538591 bytes)
-	v2 Last-Modified: Thu, 10 Sep 2015 23:36:30 GMT

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

#### `a7131b97316204530af26e42319aeda8ac44cd5ac2891e5dab45e16deb1e592d`

```dockerfile
RUN apt-get purge -y python.*
```

-	Created: Wed, 09 Sep 2015 20:20:46 GMT
-	Parent Layer: `16b189cc8ce688f9f1d8f1d837fa0891107450a06c795b1cba8f6c33a4454280`
-	Docker Version: 1.7.1
-	Virtual Size: 975.3 KB (975277 bytes)
-	v2 Blob: `sha256:20cdbe5b7a6f64396bcabde9b06c16a0b41e2c7fd39b28eff1ee3670a9f0516e`
-	v2 Content-Length: 220.4 KB (220377 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:29:17 GMT

#### `d7cbb60bc416f832c685b38578b77da5f3716cba15d4bcb45d850809a4c112eb`

```dockerfile
ENV LANG=C.UTF-8
```

-	Created: Wed, 09 Sep 2015 20:20:48 GMT
-	Parent Layer: `a7131b97316204530af26e42319aeda8ac44cd5ac2891e5dab45e16deb1e592d`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `24ccfa7d2e84006ddb7fe42a70e5d6af49675a02e896f98579c26fbcb8e1ae1b`

```dockerfile
RUN gpg --keyserver ha.pool.sks-keyservers.net --recv-keys 26DEA9D4613391EF3E25C9FF0A5B101836580288
```

-	Created: Wed, 09 Sep 2015 20:34:23 GMT
-	Parent Layer: `d7cbb60bc416f832c685b38578b77da5f3716cba15d4bcb45d850809a4c112eb`
-	Docker Version: 1.7.1
-	Virtual Size: 15.0 KB (14980 bytes)
-	v2 Blob: `sha256:c07c8b7cac8f14fa0ddc06c34b533baa07bb4c765c154904e6748bafe3c151b4`
-	v2 Content-Length: 6.8 KB (6815 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:44:13 GMT

#### `3b9b8d77de064485669ee0ff4273ac2745cbd746eceaa2da574f5f60da63836a`

```dockerfile
ENV PYTHON_VERSION=3.3.6
```

-	Created: Wed, 09 Sep 2015 20:43:35 GMT
-	Parent Layer: `24ccfa7d2e84006ddb7fe42a70e5d6af49675a02e896f98579c26fbcb8e1ae1b`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `a69216da9262bf5f4fac6fc6250af78379855a2349c4f157ae6f946bbba8b3cf`

```dockerfile
ENV PYTHON_PIP_VERSION=7.1.2
```

-	Created: Wed, 09 Sep 2015 20:43:35 GMT
-	Parent Layer: `3b9b8d77de064485669ee0ff4273ac2745cbd746eceaa2da574f5f60da63836a`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `49566fb299de780693bed214047c9d8e83eeca02b0224d79737b09bffa2b754f`

```dockerfile
RUN set -x \
	&& mkdir -p /usr/src/python \
	&& curl -SL "https://www.python.org/ftp/python/$PYTHON_VERSION/Python-$PYTHON_VERSION.tar.xz" -o python.tar.xz \
	&& curl -SL "https://www.python.org/ftp/python/$PYTHON_VERSION/Python-$PYTHON_VERSION.tar.xz.asc" -o python.tar.xz.asc \
	&& gpg --verify python.tar.xz.asc \
	&& tar -xJC /usr/src/python --strip-components=1 -f python.tar.xz \
	&& rm python.tar.xz* \
	&& cd /usr/src/python \
	&& ./configure --enable-shared --enable-unicode=ucs4 \
	&& make -j$(nproc) \
	&& make install \
	&& ldconfig \
	&& curl -SL 'https://bootstrap.pypa.io/get-pip.py' | python3 \
	&& pip install --no-cache-dir --upgrade pip==$PYTHON_PIP_VERSION \
	&& find /usr/local \
		\( -type d -a -name test -o -name tests \) \
		-o \( -type f -a -name '*.pyc' -o -name '*.pyo' \) \
		-exec rm -rf '{}' + \
	&& rm -rf /usr/src/python
```

-	Created: Wed, 09 Sep 2015 20:45:58 GMT
-	Parent Layer: `a69216da9262bf5f4fac6fc6250af78379855a2349c4f157ae6f946bbba8b3cf`
-	Docker Version: 1.7.1
-	Virtual Size: 71.7 MB (71673379 bytes)
-	v2 Blob: `sha256:fa9ced702b0a8295fa8aa4832581e1e4ce486bcb570bd0ec3a0f517feae13a56`
-	v2 Content-Length: 20.6 MB (20625849 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:49:53 GMT

#### `fd22a25847dcffcd81ffe7682e747ac15d807708f361859c14cb0aaac090ad50`

```dockerfile
RUN cd /usr/local/bin \
	&& ln -s idle3 idle \
	&& ln -s pydoc3 pydoc \
	&& ln -s python3 python \
	&& ln -s python-config3 python-config
```

-	Created: Wed, 09 Sep 2015 20:46:00 GMT
-	Parent Layer: `49566fb299de780693bed214047c9d8e83eeca02b0224d79737b09bffa2b754f`
-	Docker Version: 1.7.1
-	Virtual Size: 32.0 B
-	v2 Blob: `sha256:ff7f8f424177b190ca280cc80bd7bf01c4f9ef36221ebd2490d5af748b06a11b`
-	v2 Content-Length: 237.0 B
-	v2 Last-Modified: Wed, 09 Sep 2015 21:49:33 GMT

#### `2f80de19963c73d9cf6c63554e866ea9fe840481d3aba22a6685632b4bec9494`

```dockerfile
CMD ["python3"]
```

-	Created: Wed, 09 Sep 2015 20:46:00 GMT
-	Parent Layer: `fd22a25847dcffcd81ffe7682e747ac15d807708f361859c14cb0aaac090ad50`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

## `python:3.3.6-onbuild`

```console
$ docker pull library/python@sha256:0c69d9d225427f80ce7f79a9e5113adb0da18acc6061c16dbebdbb3321ba3d9d
```

-	Total Virtual Size: 679.1 MB (679148626 bytes)
-	Total v2 Content-Length: 261.6 MB (261622657 bytes)

### Layers (18)

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
-	v2 Blob: `sha256:b3010ec3eb21ac3df74757a47832fb17395b76ad3a30794074cefd07541d3557`
-	v2 Content-Length: 18.5 MB (18538591 bytes)
-	v2 Last-Modified: Thu, 10 Sep 2015 23:36:30 GMT

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

#### `a7131b97316204530af26e42319aeda8ac44cd5ac2891e5dab45e16deb1e592d`

```dockerfile
RUN apt-get purge -y python.*
```

-	Created: Wed, 09 Sep 2015 20:20:46 GMT
-	Parent Layer: `16b189cc8ce688f9f1d8f1d837fa0891107450a06c795b1cba8f6c33a4454280`
-	Docker Version: 1.7.1
-	Virtual Size: 975.3 KB (975277 bytes)
-	v2 Blob: `sha256:20cdbe5b7a6f64396bcabde9b06c16a0b41e2c7fd39b28eff1ee3670a9f0516e`
-	v2 Content-Length: 220.4 KB (220377 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:29:17 GMT

#### `d7cbb60bc416f832c685b38578b77da5f3716cba15d4bcb45d850809a4c112eb`

```dockerfile
ENV LANG=C.UTF-8
```

-	Created: Wed, 09 Sep 2015 20:20:48 GMT
-	Parent Layer: `a7131b97316204530af26e42319aeda8ac44cd5ac2891e5dab45e16deb1e592d`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `24ccfa7d2e84006ddb7fe42a70e5d6af49675a02e896f98579c26fbcb8e1ae1b`

```dockerfile
RUN gpg --keyserver ha.pool.sks-keyservers.net --recv-keys 26DEA9D4613391EF3E25C9FF0A5B101836580288
```

-	Created: Wed, 09 Sep 2015 20:34:23 GMT
-	Parent Layer: `d7cbb60bc416f832c685b38578b77da5f3716cba15d4bcb45d850809a4c112eb`
-	Docker Version: 1.7.1
-	Virtual Size: 15.0 KB (14980 bytes)
-	v2 Blob: `sha256:c07c8b7cac8f14fa0ddc06c34b533baa07bb4c765c154904e6748bafe3c151b4`
-	v2 Content-Length: 6.8 KB (6815 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:44:13 GMT

#### `3b9b8d77de064485669ee0ff4273ac2745cbd746eceaa2da574f5f60da63836a`

```dockerfile
ENV PYTHON_VERSION=3.3.6
```

-	Created: Wed, 09 Sep 2015 20:43:35 GMT
-	Parent Layer: `24ccfa7d2e84006ddb7fe42a70e5d6af49675a02e896f98579c26fbcb8e1ae1b`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `a69216da9262bf5f4fac6fc6250af78379855a2349c4f157ae6f946bbba8b3cf`

```dockerfile
ENV PYTHON_PIP_VERSION=7.1.2
```

-	Created: Wed, 09 Sep 2015 20:43:35 GMT
-	Parent Layer: `3b9b8d77de064485669ee0ff4273ac2745cbd746eceaa2da574f5f60da63836a`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `49566fb299de780693bed214047c9d8e83eeca02b0224d79737b09bffa2b754f`

```dockerfile
RUN set -x \
	&& mkdir -p /usr/src/python \
	&& curl -SL "https://www.python.org/ftp/python/$PYTHON_VERSION/Python-$PYTHON_VERSION.tar.xz" -o python.tar.xz \
	&& curl -SL "https://www.python.org/ftp/python/$PYTHON_VERSION/Python-$PYTHON_VERSION.tar.xz.asc" -o python.tar.xz.asc \
	&& gpg --verify python.tar.xz.asc \
	&& tar -xJC /usr/src/python --strip-components=1 -f python.tar.xz \
	&& rm python.tar.xz* \
	&& cd /usr/src/python \
	&& ./configure --enable-shared --enable-unicode=ucs4 \
	&& make -j$(nproc) \
	&& make install \
	&& ldconfig \
	&& curl -SL 'https://bootstrap.pypa.io/get-pip.py' | python3 \
	&& pip install --no-cache-dir --upgrade pip==$PYTHON_PIP_VERSION \
	&& find /usr/local \
		\( -type d -a -name test -o -name tests \) \
		-o \( -type f -a -name '*.pyc' -o -name '*.pyo' \) \
		-exec rm -rf '{}' + \
	&& rm -rf /usr/src/python
```

-	Created: Wed, 09 Sep 2015 20:45:58 GMT
-	Parent Layer: `a69216da9262bf5f4fac6fc6250af78379855a2349c4f157ae6f946bbba8b3cf`
-	Docker Version: 1.7.1
-	Virtual Size: 71.7 MB (71673379 bytes)
-	v2 Blob: `sha256:fa9ced702b0a8295fa8aa4832581e1e4ce486bcb570bd0ec3a0f517feae13a56`
-	v2 Content-Length: 20.6 MB (20625849 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:49:53 GMT

#### `fd22a25847dcffcd81ffe7682e747ac15d807708f361859c14cb0aaac090ad50`

```dockerfile
RUN cd /usr/local/bin \
	&& ln -s idle3 idle \
	&& ln -s pydoc3 pydoc \
	&& ln -s python3 python \
	&& ln -s python-config3 python-config
```

-	Created: Wed, 09 Sep 2015 20:46:00 GMT
-	Parent Layer: `49566fb299de780693bed214047c9d8e83eeca02b0224d79737b09bffa2b754f`
-	Docker Version: 1.7.1
-	Virtual Size: 32.0 B
-	v2 Blob: `sha256:ff7f8f424177b190ca280cc80bd7bf01c4f9ef36221ebd2490d5af748b06a11b`
-	v2 Content-Length: 237.0 B
-	v2 Last-Modified: Wed, 09 Sep 2015 21:49:33 GMT

#### `2f80de19963c73d9cf6c63554e866ea9fe840481d3aba22a6685632b4bec9494`

```dockerfile
CMD ["python3"]
```

-	Created: Wed, 09 Sep 2015 20:46:00 GMT
-	Parent Layer: `fd22a25847dcffcd81ffe7682e747ac15d807708f361859c14cb0aaac090ad50`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `a7b8d9cc2b24a27cef8f1990264432047a91a9ba9715fc24a8d905d0af2f366f`

```dockerfile
RUN mkdir -p /usr/src/app
```

-	Created: Wed, 09 Sep 2015 20:46:28 GMT
-	Parent Layer: `2f80de19963c73d9cf6c63554e866ea9fe840481d3aba22a6685632b4bec9494`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:c505540e7ba43e6f06d9aa67413548759bb9e3b1fa817bb7b09acee985c3d68e`
-	v2 Content-Length: 127.0 B
-	v2 Last-Modified: Wed, 09 Sep 2015 21:51:21 GMT

#### `a238697db10981c466ba8b129b1ed740aa6c26efb15019f7c235e737917d9f80`

```dockerfile
WORKDIR /usr/src/app
```

-	Created: Wed, 09 Sep 2015 20:46:29 GMT
-	Parent Layer: `a7b8d9cc2b24a27cef8f1990264432047a91a9ba9715fc24a8d905d0af2f366f`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `66bf6638ac5271108c2a47f673cd5e6f6137b17f07d6d98bd60c385e9ce13177`

```dockerfile
ONBUILD COPY requirements.txt /usr/src/app/
```

-	Created: Wed, 09 Sep 2015 20:46:29 GMT
-	Parent Layer: `a238697db10981c466ba8b129b1ed740aa6c26efb15019f7c235e737917d9f80`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `ee368bd771cede91bc8edf51eb290c7710609bced2f2160663064f249934a722`

```dockerfile
ONBUILD RUN pip install --no-cache-dir -r requirements.txt
```

-	Created: Wed, 09 Sep 2015 20:46:30 GMT
-	Parent Layer: `66bf6638ac5271108c2a47f673cd5e6f6137b17f07d6d98bd60c385e9ce13177`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `dbb5fbb5a823ea14e57189295376f7547a0dd68258e178c53cebf59111691109`

```dockerfile
ONBUILD COPY . /usr/src/app
```

-	Created: Wed, 09 Sep 2015 20:46:30 GMT
-	Parent Layer: `ee368bd771cede91bc8edf51eb290c7710609bced2f2160663064f249934a722`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

## `python:3.3-onbuild`

```console
$ docker pull library/python@sha256:8c9a3862b92d763e481aaa23643573ae2e9b3abf9d3e276f068ccbef403a607b
```

-	Total Virtual Size: 679.1 MB (679148626 bytes)
-	Total v2 Content-Length: 261.6 MB (261622657 bytes)

### Layers (18)

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
-	v2 Blob: `sha256:b3010ec3eb21ac3df74757a47832fb17395b76ad3a30794074cefd07541d3557`
-	v2 Content-Length: 18.5 MB (18538591 bytes)
-	v2 Last-Modified: Thu, 10 Sep 2015 23:36:30 GMT

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

#### `a7131b97316204530af26e42319aeda8ac44cd5ac2891e5dab45e16deb1e592d`

```dockerfile
RUN apt-get purge -y python.*
```

-	Created: Wed, 09 Sep 2015 20:20:46 GMT
-	Parent Layer: `16b189cc8ce688f9f1d8f1d837fa0891107450a06c795b1cba8f6c33a4454280`
-	Docker Version: 1.7.1
-	Virtual Size: 975.3 KB (975277 bytes)
-	v2 Blob: `sha256:20cdbe5b7a6f64396bcabde9b06c16a0b41e2c7fd39b28eff1ee3670a9f0516e`
-	v2 Content-Length: 220.4 KB (220377 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:29:17 GMT

#### `d7cbb60bc416f832c685b38578b77da5f3716cba15d4bcb45d850809a4c112eb`

```dockerfile
ENV LANG=C.UTF-8
```

-	Created: Wed, 09 Sep 2015 20:20:48 GMT
-	Parent Layer: `a7131b97316204530af26e42319aeda8ac44cd5ac2891e5dab45e16deb1e592d`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `24ccfa7d2e84006ddb7fe42a70e5d6af49675a02e896f98579c26fbcb8e1ae1b`

```dockerfile
RUN gpg --keyserver ha.pool.sks-keyservers.net --recv-keys 26DEA9D4613391EF3E25C9FF0A5B101836580288
```

-	Created: Wed, 09 Sep 2015 20:34:23 GMT
-	Parent Layer: `d7cbb60bc416f832c685b38578b77da5f3716cba15d4bcb45d850809a4c112eb`
-	Docker Version: 1.7.1
-	Virtual Size: 15.0 KB (14980 bytes)
-	v2 Blob: `sha256:c07c8b7cac8f14fa0ddc06c34b533baa07bb4c765c154904e6748bafe3c151b4`
-	v2 Content-Length: 6.8 KB (6815 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:44:13 GMT

#### `3b9b8d77de064485669ee0ff4273ac2745cbd746eceaa2da574f5f60da63836a`

```dockerfile
ENV PYTHON_VERSION=3.3.6
```

-	Created: Wed, 09 Sep 2015 20:43:35 GMT
-	Parent Layer: `24ccfa7d2e84006ddb7fe42a70e5d6af49675a02e896f98579c26fbcb8e1ae1b`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `a69216da9262bf5f4fac6fc6250af78379855a2349c4f157ae6f946bbba8b3cf`

```dockerfile
ENV PYTHON_PIP_VERSION=7.1.2
```

-	Created: Wed, 09 Sep 2015 20:43:35 GMT
-	Parent Layer: `3b9b8d77de064485669ee0ff4273ac2745cbd746eceaa2da574f5f60da63836a`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `49566fb299de780693bed214047c9d8e83eeca02b0224d79737b09bffa2b754f`

```dockerfile
RUN set -x \
	&& mkdir -p /usr/src/python \
	&& curl -SL "https://www.python.org/ftp/python/$PYTHON_VERSION/Python-$PYTHON_VERSION.tar.xz" -o python.tar.xz \
	&& curl -SL "https://www.python.org/ftp/python/$PYTHON_VERSION/Python-$PYTHON_VERSION.tar.xz.asc" -o python.tar.xz.asc \
	&& gpg --verify python.tar.xz.asc \
	&& tar -xJC /usr/src/python --strip-components=1 -f python.tar.xz \
	&& rm python.tar.xz* \
	&& cd /usr/src/python \
	&& ./configure --enable-shared --enable-unicode=ucs4 \
	&& make -j$(nproc) \
	&& make install \
	&& ldconfig \
	&& curl -SL 'https://bootstrap.pypa.io/get-pip.py' | python3 \
	&& pip install --no-cache-dir --upgrade pip==$PYTHON_PIP_VERSION \
	&& find /usr/local \
		\( -type d -a -name test -o -name tests \) \
		-o \( -type f -a -name '*.pyc' -o -name '*.pyo' \) \
		-exec rm -rf '{}' + \
	&& rm -rf /usr/src/python
```

-	Created: Wed, 09 Sep 2015 20:45:58 GMT
-	Parent Layer: `a69216da9262bf5f4fac6fc6250af78379855a2349c4f157ae6f946bbba8b3cf`
-	Docker Version: 1.7.1
-	Virtual Size: 71.7 MB (71673379 bytes)
-	v2 Blob: `sha256:fa9ced702b0a8295fa8aa4832581e1e4ce486bcb570bd0ec3a0f517feae13a56`
-	v2 Content-Length: 20.6 MB (20625849 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:49:53 GMT

#### `fd22a25847dcffcd81ffe7682e747ac15d807708f361859c14cb0aaac090ad50`

```dockerfile
RUN cd /usr/local/bin \
	&& ln -s idle3 idle \
	&& ln -s pydoc3 pydoc \
	&& ln -s python3 python \
	&& ln -s python-config3 python-config
```

-	Created: Wed, 09 Sep 2015 20:46:00 GMT
-	Parent Layer: `49566fb299de780693bed214047c9d8e83eeca02b0224d79737b09bffa2b754f`
-	Docker Version: 1.7.1
-	Virtual Size: 32.0 B
-	v2 Blob: `sha256:ff7f8f424177b190ca280cc80bd7bf01c4f9ef36221ebd2490d5af748b06a11b`
-	v2 Content-Length: 237.0 B
-	v2 Last-Modified: Wed, 09 Sep 2015 21:49:33 GMT

#### `2f80de19963c73d9cf6c63554e866ea9fe840481d3aba22a6685632b4bec9494`

```dockerfile
CMD ["python3"]
```

-	Created: Wed, 09 Sep 2015 20:46:00 GMT
-	Parent Layer: `fd22a25847dcffcd81ffe7682e747ac15d807708f361859c14cb0aaac090ad50`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `a7b8d9cc2b24a27cef8f1990264432047a91a9ba9715fc24a8d905d0af2f366f`

```dockerfile
RUN mkdir -p /usr/src/app
```

-	Created: Wed, 09 Sep 2015 20:46:28 GMT
-	Parent Layer: `2f80de19963c73d9cf6c63554e866ea9fe840481d3aba22a6685632b4bec9494`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:c505540e7ba43e6f06d9aa67413548759bb9e3b1fa817bb7b09acee985c3d68e`
-	v2 Content-Length: 127.0 B
-	v2 Last-Modified: Wed, 09 Sep 2015 21:51:21 GMT

#### `a238697db10981c466ba8b129b1ed740aa6c26efb15019f7c235e737917d9f80`

```dockerfile
WORKDIR /usr/src/app
```

-	Created: Wed, 09 Sep 2015 20:46:29 GMT
-	Parent Layer: `a7b8d9cc2b24a27cef8f1990264432047a91a9ba9715fc24a8d905d0af2f366f`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `66bf6638ac5271108c2a47f673cd5e6f6137b17f07d6d98bd60c385e9ce13177`

```dockerfile
ONBUILD COPY requirements.txt /usr/src/app/
```

-	Created: Wed, 09 Sep 2015 20:46:29 GMT
-	Parent Layer: `a238697db10981c466ba8b129b1ed740aa6c26efb15019f7c235e737917d9f80`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `ee368bd771cede91bc8edf51eb290c7710609bced2f2160663064f249934a722`

```dockerfile
ONBUILD RUN pip install --no-cache-dir -r requirements.txt
```

-	Created: Wed, 09 Sep 2015 20:46:30 GMT
-	Parent Layer: `66bf6638ac5271108c2a47f673cd5e6f6137b17f07d6d98bd60c385e9ce13177`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `dbb5fbb5a823ea14e57189295376f7547a0dd68258e178c53cebf59111691109`

```dockerfile
ONBUILD COPY . /usr/src/app
```

-	Created: Wed, 09 Sep 2015 20:46:30 GMT
-	Parent Layer: `ee368bd771cede91bc8edf51eb290c7710609bced2f2160663064f249934a722`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

## `python:3.3.6-slim`

```console
$ docker pull library/python@sha256:68037e5f80e74a7b31a9bd5b79f6d190a27932c49c5c200967e0d271fe8b801f
```

-	Total Virtual Size: 208.7 MB (208651199 bytes)
-	Total v2 Content-Length: 77.4 MB (77405034 bytes)

### Layers (11)

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

#### `b724829f2124ff81839118c0bb053554742dae49bcf23847b98264867e4da862`

```dockerfile
RUN apt-get purge -y python.*
```

-	Created: Wed, 09 Sep 2015 20:26:09 GMT
-	Parent Layer: `8c00acfb017549e44d28098762c3e6296872a1ca9b90385855f1019d84bb0dac`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `dad2fc2df4957c05b555a45d00adeaaf624ccce5d9dd557ce4c8548ca40f39f0`

```dockerfile
ENV LANG=C.UTF-8
```

-	Created: Wed, 09 Sep 2015 20:26:10 GMT
-	Parent Layer: `b724829f2124ff81839118c0bb053554742dae49bcf23847b98264867e4da862`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `b4b1929946879d72f7304c436913698e312741961589842913329eb8d746fefa`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		libsqlite3-0 \
		libssl1.0.0 \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Wed, 09 Sep 2015 20:26:51 GMT
-	Parent Layer: `dad2fc2df4957c05b555a45d00adeaaf624ccce5d9dd557ce4c8548ca40f39f0`
-	Docker Version: 1.7.1
-	Virtual Size: 7.4 MB (7441496 bytes)
-	v2 Blob: `sha256:aebbd0bd409f97875c3b3bcf8f57e315ba2ef8d3c4a54f81a7f71cfcf80bf4c9`
-	v2 Content-Length: 3.3 MB (3316296 bytes)
-	v2 Last-Modified: Fri, 11 Sep 2015 00:01:36 GMT

#### `2c2bc18871d5df288fd24c76c61faddee6ecd04bcf69bab5628d94c88dc41235`

```dockerfile
RUN gpg --keyserver ha.pool.sks-keyservers.net --recv-keys 26DEA9D4613391EF3E25C9FF0A5B101836580288
```

-	Created: Wed, 09 Sep 2015 20:37:34 GMT
-	Parent Layer: `b4b1929946879d72f7304c436913698e312741961589842913329eb8d746fefa`
-	Docker Version: 1.7.1
-	Virtual Size: 15.0 KB (14980 bytes)
-	v2 Blob: `sha256:c9d4d35a9638b3eadf5e21a15c542f07e055bea1e341024a7d80ff99656dcd47`
-	v2 Content-Length: 6.8 KB (6814 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:46:21 GMT

#### `0799dad5edcaa901784dd7e122efe7a95b218a895c09fcf8df8a7bb922c4782e`

```dockerfile
ENV PYTHON_VERSION=3.3.6
```

-	Created: Wed, 09 Sep 2015 20:47:01 GMT
-	Parent Layer: `2c2bc18871d5df288fd24c76c61faddee6ecd04bcf69bab5628d94c88dc41235`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `b8829beabc235946a383ff31f4f82e323fcbe723a65a0ea6a4c77774770bfe62`

```dockerfile
ENV PYTHON_PIP_VERSION=7.1.2
```

-	Created: Wed, 09 Sep 2015 20:47:01 GMT
-	Parent Layer: `0799dad5edcaa901784dd7e122efe7a95b218a895c09fcf8df8a7bb922c4782e`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `c531536b628efa68791c1a3604c77a12e3407c8a2294789694898a63c12e21c9`

```dockerfile
RUN set -x \
	&& buildDeps=' \
		curl \
		gcc \
		libbz2-dev \
		libc6-dev \
		libncurses-dev \
		libreadline-dev \
		libsqlite3-dev \
		libssl-dev \
		make \
		xz-utils \
		zlib1g-dev \
	' \
	&& apt-get update && apt-get install -y $buildDeps --no-install-recommends && rm -rf /var/lib/apt/lists/* \
	&& mkdir -p /usr/src/python \
	&& curl -SL "https://www.python.org/ftp/python/$PYTHON_VERSION/Python-$PYTHON_VERSION.tar.xz" -o python.tar.xz \
	&& curl -SL "https://www.python.org/ftp/python/$PYTHON_VERSION/Python-$PYTHON_VERSION.tar.xz.asc" -o python.tar.xz.asc \
	&& gpg --verify python.tar.xz.asc \
	&& tar -xJC /usr/src/python --strip-components=1 -f python.tar.xz \
	&& rm python.tar.xz* \
	&& cd /usr/src/python \
	&& ./configure --enable-shared --enable-unicode=ucs4 \
	&& make -j$(nproc) \
	&& make install \
	&& ldconfig \
	&& curl -SL 'https://bootstrap.pypa.io/get-pip.py' | python3 \
	&& pip install --no-cache-dir --upgrade pip==$PYTHON_PIP_VERSION \
	&& find /usr/local \
		\( -type d -a -name test -o -name tests \) \
		-o \( -type f -a -name '*.pyc' -o -name '*.pyo' \) \
		-exec rm -rf '{}' + \
	&& apt-get purge -y --auto-remove $buildDeps \
	&& rm -rf /usr/src/python
```

-	Created: Wed, 09 Sep 2015 20:50:26 GMT
-	Parent Layer: `b8829beabc235946a383ff31f4f82e323fcbe723a65a0ea6a4c77774770bfe62`
-	Docker Version: 1.7.1
-	Virtual Size: 76.0 MB (76035560 bytes)
-	v2 Blob: `sha256:f787abcc2c6dc2e325cb7a2b6b09c9e499c6a4adf272beccf757800350417928`
-	v2 Content-Length: 22.7 MB (22721787 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:52:28 GMT

#### `a731851c1a82b87b3fb28e83a2e4502ce0ac5b4310d7f979ca7b4d394f3f9001`

```dockerfile
RUN cd /usr/local/bin \
	&& ln -s idle3 idle \
	&& ln -s pydoc3 pydoc \
	&& ln -s python3 python \
	&& ln -s python-config3 python-config
```

-	Created: Wed, 09 Sep 2015 20:50:28 GMT
-	Parent Layer: `c531536b628efa68791c1a3604c77a12e3407c8a2294789694898a63c12e21c9`
-	Docker Version: 1.7.1
-	Virtual Size: 32.0 B
-	v2 Blob: `sha256:d9fc7c850bd293440475675a87aafab3b683fadaaa0dc51781a9efd21b519f84`
-	v2 Content-Length: 237.0 B
-	v2 Last-Modified: Wed, 09 Sep 2015 21:52:07 GMT

#### `3ed9a796818b82675fbf43f3eb13d9010105df28525ff71a70d294233b8fc33a`

```dockerfile
CMD ["python3"]
```

-	Created: Wed, 09 Sep 2015 20:50:28 GMT
-	Parent Layer: `a731851c1a82b87b3fb28e83a2e4502ce0ac5b4310d7f979ca7b4d394f3f9001`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

## `python:3.3-slim`

```console
$ docker pull library/python@sha256:12c0ed0ef244ec8a9c5c5df584ca4ce1dc514a3a37ec44b1b36b6031e7fe26b3
```

-	Total Virtual Size: 208.7 MB (208651199 bytes)
-	Total v2 Content-Length: 77.4 MB (77405034 bytes)

### Layers (11)

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

#### `b724829f2124ff81839118c0bb053554742dae49bcf23847b98264867e4da862`

```dockerfile
RUN apt-get purge -y python.*
```

-	Created: Wed, 09 Sep 2015 20:26:09 GMT
-	Parent Layer: `8c00acfb017549e44d28098762c3e6296872a1ca9b90385855f1019d84bb0dac`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `dad2fc2df4957c05b555a45d00adeaaf624ccce5d9dd557ce4c8548ca40f39f0`

```dockerfile
ENV LANG=C.UTF-8
```

-	Created: Wed, 09 Sep 2015 20:26:10 GMT
-	Parent Layer: `b724829f2124ff81839118c0bb053554742dae49bcf23847b98264867e4da862`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `b4b1929946879d72f7304c436913698e312741961589842913329eb8d746fefa`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		libsqlite3-0 \
		libssl1.0.0 \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Wed, 09 Sep 2015 20:26:51 GMT
-	Parent Layer: `dad2fc2df4957c05b555a45d00adeaaf624ccce5d9dd557ce4c8548ca40f39f0`
-	Docker Version: 1.7.1
-	Virtual Size: 7.4 MB (7441496 bytes)
-	v2 Blob: `sha256:aebbd0bd409f97875c3b3bcf8f57e315ba2ef8d3c4a54f81a7f71cfcf80bf4c9`
-	v2 Content-Length: 3.3 MB (3316296 bytes)
-	v2 Last-Modified: Fri, 11 Sep 2015 00:01:36 GMT

#### `2c2bc18871d5df288fd24c76c61faddee6ecd04bcf69bab5628d94c88dc41235`

```dockerfile
RUN gpg --keyserver ha.pool.sks-keyservers.net --recv-keys 26DEA9D4613391EF3E25C9FF0A5B101836580288
```

-	Created: Wed, 09 Sep 2015 20:37:34 GMT
-	Parent Layer: `b4b1929946879d72f7304c436913698e312741961589842913329eb8d746fefa`
-	Docker Version: 1.7.1
-	Virtual Size: 15.0 KB (14980 bytes)
-	v2 Blob: `sha256:c9d4d35a9638b3eadf5e21a15c542f07e055bea1e341024a7d80ff99656dcd47`
-	v2 Content-Length: 6.8 KB (6814 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:46:21 GMT

#### `0799dad5edcaa901784dd7e122efe7a95b218a895c09fcf8df8a7bb922c4782e`

```dockerfile
ENV PYTHON_VERSION=3.3.6
```

-	Created: Wed, 09 Sep 2015 20:47:01 GMT
-	Parent Layer: `2c2bc18871d5df288fd24c76c61faddee6ecd04bcf69bab5628d94c88dc41235`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `b8829beabc235946a383ff31f4f82e323fcbe723a65a0ea6a4c77774770bfe62`

```dockerfile
ENV PYTHON_PIP_VERSION=7.1.2
```

-	Created: Wed, 09 Sep 2015 20:47:01 GMT
-	Parent Layer: `0799dad5edcaa901784dd7e122efe7a95b218a895c09fcf8df8a7bb922c4782e`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `c531536b628efa68791c1a3604c77a12e3407c8a2294789694898a63c12e21c9`

```dockerfile
RUN set -x \
	&& buildDeps=' \
		curl \
		gcc \
		libbz2-dev \
		libc6-dev \
		libncurses-dev \
		libreadline-dev \
		libsqlite3-dev \
		libssl-dev \
		make \
		xz-utils \
		zlib1g-dev \
	' \
	&& apt-get update && apt-get install -y $buildDeps --no-install-recommends && rm -rf /var/lib/apt/lists/* \
	&& mkdir -p /usr/src/python \
	&& curl -SL "https://www.python.org/ftp/python/$PYTHON_VERSION/Python-$PYTHON_VERSION.tar.xz" -o python.tar.xz \
	&& curl -SL "https://www.python.org/ftp/python/$PYTHON_VERSION/Python-$PYTHON_VERSION.tar.xz.asc" -o python.tar.xz.asc \
	&& gpg --verify python.tar.xz.asc \
	&& tar -xJC /usr/src/python --strip-components=1 -f python.tar.xz \
	&& rm python.tar.xz* \
	&& cd /usr/src/python \
	&& ./configure --enable-shared --enable-unicode=ucs4 \
	&& make -j$(nproc) \
	&& make install \
	&& ldconfig \
	&& curl -SL 'https://bootstrap.pypa.io/get-pip.py' | python3 \
	&& pip install --no-cache-dir --upgrade pip==$PYTHON_PIP_VERSION \
	&& find /usr/local \
		\( -type d -a -name test -o -name tests \) \
		-o \( -type f -a -name '*.pyc' -o -name '*.pyo' \) \
		-exec rm -rf '{}' + \
	&& apt-get purge -y --auto-remove $buildDeps \
	&& rm -rf /usr/src/python
```

-	Created: Wed, 09 Sep 2015 20:50:26 GMT
-	Parent Layer: `b8829beabc235946a383ff31f4f82e323fcbe723a65a0ea6a4c77774770bfe62`
-	Docker Version: 1.7.1
-	Virtual Size: 76.0 MB (76035560 bytes)
-	v2 Blob: `sha256:f787abcc2c6dc2e325cb7a2b6b09c9e499c6a4adf272beccf757800350417928`
-	v2 Content-Length: 22.7 MB (22721787 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:52:28 GMT

#### `a731851c1a82b87b3fb28e83a2e4502ce0ac5b4310d7f979ca7b4d394f3f9001`

```dockerfile
RUN cd /usr/local/bin \
	&& ln -s idle3 idle \
	&& ln -s pydoc3 pydoc \
	&& ln -s python3 python \
	&& ln -s python-config3 python-config
```

-	Created: Wed, 09 Sep 2015 20:50:28 GMT
-	Parent Layer: `c531536b628efa68791c1a3604c77a12e3407c8a2294789694898a63c12e21c9`
-	Docker Version: 1.7.1
-	Virtual Size: 32.0 B
-	v2 Blob: `sha256:d9fc7c850bd293440475675a87aafab3b683fadaaa0dc51781a9efd21b519f84`
-	v2 Content-Length: 237.0 B
-	v2 Last-Modified: Wed, 09 Sep 2015 21:52:07 GMT

#### `3ed9a796818b82675fbf43f3eb13d9010105df28525ff71a70d294233b8fc33a`

```dockerfile
CMD ["python3"]
```

-	Created: Wed, 09 Sep 2015 20:50:28 GMT
-	Parent Layer: `a731851c1a82b87b3fb28e83a2e4502ce0ac5b4310d7f979ca7b4d394f3f9001`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

## `python:3.3.6-wheezy`

```console
$ docker pull library/python@sha256:dbaa2441db246cf6766aae5a44d5dec93f951d999c0d8a7b9a3c9d1199233095
```

-	Total Virtual Size: 531.0 MB (530962129 bytes)
-	Total v2 Content-Length: 196.0 MB (196035808 bytes)

### Layers (13)

#### `ba249489d0b6512128b60a4910e78fa2000c785d59e0599188a6802bd01155f2`

```dockerfile
ADD file:b908886c97e2b96665b7afc54ff53ebaef1c62896cf83a1199e59fceff1dafb5 in /
```

-	Created: Mon, 07 Sep 2015 23:37:10 GMT
-	Docker Version: 1.7.1
-	Virtual Size: 84.9 MB (84924773 bytes)
-	v2 Blob: `sha256:8f47f7c36e4382b4569bfe8858c0b371313e9c47a72867d69b000949c53637c9`
-	v2 Content-Length: 37.2 MB (37191761 bytes)
-	v2 Last-Modified: Mon, 07 Sep 2015 23:46:29 GMT

#### `19de96c112fcca5b6de16611dc0a359b0b977c551921ca79ac5cf4a8bfff9351`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Mon, 07 Sep 2015 23:37:11 GMT
-	Parent Layer: `ba249489d0b6512128b60a4910e78fa2000c785d59e0599188a6802bd01155f2`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `e83e5b7f7d01ffa47e46b7234799f12d842089df890db8fae765c5a4df26a20b`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 08 Sep 2015 15:38:48 GMT
-	Parent Layer: `19de96c112fcca5b6de16611dc0a359b0b977c551921ca79ac5cf4a8bfff9351`
-	Docker Version: 1.7.1
-	Virtual Size: 14.2 MB (14239819 bytes)
-	v2 Blob: `sha256:7a11528d019acc2b739bd4c1a7e518e247f729fdad40490be9d9fdb13e85c8c8`
-	v2 Content-Length: 6.7 MB (6739553 bytes)
-	v2 Last-Modified: Thu, 10 Sep 2015 23:43:23 GMT

#### `d6b70cefe2bfb76216c96acb6a6c6350eedff489df914b2606b1005e70f73a00`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 08 Sep 2015 15:39:23 GMT
-	Parent Layer: `e83e5b7f7d01ffa47e46b7234799f12d842089df890db8fae765c5a4df26a20b`
-	Docker Version: 1.7.1
-	Virtual Size: 109.4 MB (109431259 bytes)
-	v2 Blob: `sha256:4224b2b7563f71616cbe9215abf5276c51b18d3ceead85a56526519b5391a75f`
-	v2 Content-Length: 37.0 MB (37046780 bytes)
-	v2 Last-Modified: Tue, 08 Sep 2015 16:02:41 GMT

#### `3a5282506aa21c7b21cfdad32a099497bf9839dbc5e427f79bdad6a5e109f3d3`

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

-	Created: Tue, 08 Sep 2015 15:41:19 GMT
-	Parent Layer: `d6b70cefe2bfb76216c96acb6a6c6350eedff489df914b2606b1005e70f73a00`
-	Docker Version: 1.7.1
-	Virtual Size: 250.6 MB (250569275 bytes)
-	v2 Blob: `sha256:89989badb2c249165ed907bdf03e38dffbaefd3c115ad32ac6cf53ebbafab33b`
-	v2 Content-Length: 94.3 MB (94261782 bytes)
-	v2 Last-Modified: Tue, 08 Sep 2015 16:03:53 GMT

#### `1046da491d81f106d762e20009d4dfff16da8b2af4eafc70cba44ca74f7dc53e`

```dockerfile
RUN apt-get purge -y python.*
```

-	Created: Wed, 09 Sep 2015 20:31:23 GMT
-	Parent Layer: `3a5282506aa21c7b21cfdad32a099497bf9839dbc5e427f79bdad6a5e109f3d3`
-	Docker Version: 1.7.1
-	Virtual Size: 833.7 KB (833724 bytes)
-	v2 Blob: `sha256:9bab6257d36f85970d8effd469dcd7c7a44ab5de929035933d165b6a35929905`
-	v2 Content-Length: 196.8 KB (196778 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:39:13 GMT

#### `498b8d9d85457c4a520c8678c4ce95829605287dfb5ca8f39586b76666d446ab`

```dockerfile
ENV LANG=C.UTF-8
```

-	Created: Wed, 09 Sep 2015 20:31:23 GMT
-	Parent Layer: `1046da491d81f106d762e20009d4dfff16da8b2af4eafc70cba44ca74f7dc53e`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `bce93d89f9c65e5a344ec2e9d57734f0693056a26b359e447408176c63582e4c`

```dockerfile
RUN gpg --keyserver ha.pool.sks-keyservers.net --recv-keys 26DEA9D4613391EF3E25C9FF0A5B101836580288
```

-	Created: Wed, 09 Sep 2015 20:41:11 GMT
-	Parent Layer: `498b8d9d85457c4a520c8678c4ce95829605287dfb5ca8f39586b76666d446ab`
-	Docker Version: 1.7.1
-	Virtual Size: 15.0 KB (14980 bytes)
-	v2 Blob: `sha256:1f31a23778aae08c9fe6fd02507c417d1c8c573a558b912caf06bb1f71dbc5e2`
-	v2 Content-Length: 6.8 KB (6814 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:48:00 GMT

#### `05dc3d1e6d16d66599c114790f98f9897a3a04483269ee6392bcaed6d42dae1c`

```dockerfile
ENV PYTHON_VERSION=3.3.6
```

-	Created: Wed, 09 Sep 2015 20:51:07 GMT
-	Parent Layer: `bce93d89f9c65e5a344ec2e9d57734f0693056a26b359e447408176c63582e4c`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `8526d132178a041cfcc0cc5df38663064b09b80c1bea1662d50284559dca05f6`

```dockerfile
ENV PYTHON_PIP_VERSION=7.1.2
```

-	Created: Wed, 09 Sep 2015 20:51:08 GMT
-	Parent Layer: `05dc3d1e6d16d66599c114790f98f9897a3a04483269ee6392bcaed6d42dae1c`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `44cc5c5a22f5b1bf1c96b0fb80d1c456cbdad800365f43e165cc4643f6f0bbe3`

```dockerfile
RUN set -x \
	&& mkdir -p /usr/src/python \
	&& curl -SL "https://www.python.org/ftp/python/$PYTHON_VERSION/Python-$PYTHON_VERSION.tar.xz" -o python.tar.xz \
	&& curl -SL "https://www.python.org/ftp/python/$PYTHON_VERSION/Python-$PYTHON_VERSION.tar.xz.asc" -o python.tar.xz.asc \
	&& gpg --verify python.tar.xz.asc \
	&& tar -xJC /usr/src/python --strip-components=1 -f python.tar.xz \
	&& rm python.tar.xz* \
	&& cd /usr/src/python \
	&& ./configure --enable-shared --enable-unicode=ucs4 \
	&& make -j$(nproc) \
	&& make install \
	&& ldconfig \
	&& curl -SL 'https://bootstrap.pypa.io/get-pip.py' | python3 \
	&& pip install --no-cache-dir --upgrade pip==$PYTHON_PIP_VERSION \
	&& find /usr/local \
		\( -type d -a -name test -o -name tests \) \
		-o \( -type f -a -name '*.pyc' -o -name '*.pyo' \) \
		-exec rm -rf '{}' + \
	&& rm -rf /usr/src/python
```

-	Created: Wed, 09 Sep 2015 20:53:16 GMT
-	Parent Layer: `8526d132178a041cfcc0cc5df38663064b09b80c1bea1662d50284559dca05f6`
-	Docker Version: 1.7.1
-	Virtual Size: 70.9 MB (70948267 bytes)
-	v2 Blob: `sha256:69b3e34483460444a9288f5a7c860dfb6548d31376ab59fa6ec8d73879670934`
-	v2 Content-Length: 20.6 MB (20591942 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:53:45 GMT

#### `d9c0f04961a4bc17a18f6ca7cfecd049ba8855cf2036b2f164c988c437800177`

```dockerfile
RUN cd /usr/local/bin \
	&& ln -s idle3 idle \
	&& ln -s pydoc3 pydoc \
	&& ln -s python3 python \
	&& ln -s python-config3 python-config
```

-	Created: Wed, 09 Sep 2015 20:53:18 GMT
-	Parent Layer: `44cc5c5a22f5b1bf1c96b0fb80d1c456cbdad800365f43e165cc4643f6f0bbe3`
-	Docker Version: 1.7.1
-	Virtual Size: 32.0 B
-	v2 Blob: `sha256:72b4768ceae776d3488a9b1e8b497368e8ca639680f4fa4a5b9e91b4f9eba7ce`
-	v2 Content-Length: 238.0 B
-	v2 Last-Modified: Wed, 09 Sep 2015 21:53:25 GMT

#### `b8240e0baf202023610193f153b87fc4c2837a0511c15b3b81ef7bb15d0625b2`

```dockerfile
CMD ["python3"]
```

-	Created: Wed, 09 Sep 2015 20:53:18 GMT
-	Parent Layer: `d9c0f04961a4bc17a18f6ca7cfecd049ba8855cf2036b2f164c988c437800177`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

## `python:3.3-wheezy`

```console
$ docker pull library/python@sha256:e85a651cd7bf79cb92577d1663539dbfe449d9a35e7eb2048a013ed6e4f7f6b7
```

-	Total Virtual Size: 531.0 MB (530962129 bytes)
-	Total v2 Content-Length: 196.0 MB (196035808 bytes)

### Layers (13)

#### `ba249489d0b6512128b60a4910e78fa2000c785d59e0599188a6802bd01155f2`

```dockerfile
ADD file:b908886c97e2b96665b7afc54ff53ebaef1c62896cf83a1199e59fceff1dafb5 in /
```

-	Created: Mon, 07 Sep 2015 23:37:10 GMT
-	Docker Version: 1.7.1
-	Virtual Size: 84.9 MB (84924773 bytes)
-	v2 Blob: `sha256:8f47f7c36e4382b4569bfe8858c0b371313e9c47a72867d69b000949c53637c9`
-	v2 Content-Length: 37.2 MB (37191761 bytes)
-	v2 Last-Modified: Mon, 07 Sep 2015 23:46:29 GMT

#### `19de96c112fcca5b6de16611dc0a359b0b977c551921ca79ac5cf4a8bfff9351`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Mon, 07 Sep 2015 23:37:11 GMT
-	Parent Layer: `ba249489d0b6512128b60a4910e78fa2000c785d59e0599188a6802bd01155f2`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `e83e5b7f7d01ffa47e46b7234799f12d842089df890db8fae765c5a4df26a20b`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 08 Sep 2015 15:38:48 GMT
-	Parent Layer: `19de96c112fcca5b6de16611dc0a359b0b977c551921ca79ac5cf4a8bfff9351`
-	Docker Version: 1.7.1
-	Virtual Size: 14.2 MB (14239819 bytes)
-	v2 Blob: `sha256:7a11528d019acc2b739bd4c1a7e518e247f729fdad40490be9d9fdb13e85c8c8`
-	v2 Content-Length: 6.7 MB (6739553 bytes)
-	v2 Last-Modified: Thu, 10 Sep 2015 23:43:23 GMT

#### `d6b70cefe2bfb76216c96acb6a6c6350eedff489df914b2606b1005e70f73a00`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 08 Sep 2015 15:39:23 GMT
-	Parent Layer: `e83e5b7f7d01ffa47e46b7234799f12d842089df890db8fae765c5a4df26a20b`
-	Docker Version: 1.7.1
-	Virtual Size: 109.4 MB (109431259 bytes)
-	v2 Blob: `sha256:4224b2b7563f71616cbe9215abf5276c51b18d3ceead85a56526519b5391a75f`
-	v2 Content-Length: 37.0 MB (37046780 bytes)
-	v2 Last-Modified: Tue, 08 Sep 2015 16:02:41 GMT

#### `3a5282506aa21c7b21cfdad32a099497bf9839dbc5e427f79bdad6a5e109f3d3`

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

-	Created: Tue, 08 Sep 2015 15:41:19 GMT
-	Parent Layer: `d6b70cefe2bfb76216c96acb6a6c6350eedff489df914b2606b1005e70f73a00`
-	Docker Version: 1.7.1
-	Virtual Size: 250.6 MB (250569275 bytes)
-	v2 Blob: `sha256:89989badb2c249165ed907bdf03e38dffbaefd3c115ad32ac6cf53ebbafab33b`
-	v2 Content-Length: 94.3 MB (94261782 bytes)
-	v2 Last-Modified: Tue, 08 Sep 2015 16:03:53 GMT

#### `1046da491d81f106d762e20009d4dfff16da8b2af4eafc70cba44ca74f7dc53e`

```dockerfile
RUN apt-get purge -y python.*
```

-	Created: Wed, 09 Sep 2015 20:31:23 GMT
-	Parent Layer: `3a5282506aa21c7b21cfdad32a099497bf9839dbc5e427f79bdad6a5e109f3d3`
-	Docker Version: 1.7.1
-	Virtual Size: 833.7 KB (833724 bytes)
-	v2 Blob: `sha256:9bab6257d36f85970d8effd469dcd7c7a44ab5de929035933d165b6a35929905`
-	v2 Content-Length: 196.8 KB (196778 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:39:13 GMT

#### `498b8d9d85457c4a520c8678c4ce95829605287dfb5ca8f39586b76666d446ab`

```dockerfile
ENV LANG=C.UTF-8
```

-	Created: Wed, 09 Sep 2015 20:31:23 GMT
-	Parent Layer: `1046da491d81f106d762e20009d4dfff16da8b2af4eafc70cba44ca74f7dc53e`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `bce93d89f9c65e5a344ec2e9d57734f0693056a26b359e447408176c63582e4c`

```dockerfile
RUN gpg --keyserver ha.pool.sks-keyservers.net --recv-keys 26DEA9D4613391EF3E25C9FF0A5B101836580288
```

-	Created: Wed, 09 Sep 2015 20:41:11 GMT
-	Parent Layer: `498b8d9d85457c4a520c8678c4ce95829605287dfb5ca8f39586b76666d446ab`
-	Docker Version: 1.7.1
-	Virtual Size: 15.0 KB (14980 bytes)
-	v2 Blob: `sha256:1f31a23778aae08c9fe6fd02507c417d1c8c573a558b912caf06bb1f71dbc5e2`
-	v2 Content-Length: 6.8 KB (6814 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:48:00 GMT

#### `05dc3d1e6d16d66599c114790f98f9897a3a04483269ee6392bcaed6d42dae1c`

```dockerfile
ENV PYTHON_VERSION=3.3.6
```

-	Created: Wed, 09 Sep 2015 20:51:07 GMT
-	Parent Layer: `bce93d89f9c65e5a344ec2e9d57734f0693056a26b359e447408176c63582e4c`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `8526d132178a041cfcc0cc5df38663064b09b80c1bea1662d50284559dca05f6`

```dockerfile
ENV PYTHON_PIP_VERSION=7.1.2
```

-	Created: Wed, 09 Sep 2015 20:51:08 GMT
-	Parent Layer: `05dc3d1e6d16d66599c114790f98f9897a3a04483269ee6392bcaed6d42dae1c`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `44cc5c5a22f5b1bf1c96b0fb80d1c456cbdad800365f43e165cc4643f6f0bbe3`

```dockerfile
RUN set -x \
	&& mkdir -p /usr/src/python \
	&& curl -SL "https://www.python.org/ftp/python/$PYTHON_VERSION/Python-$PYTHON_VERSION.tar.xz" -o python.tar.xz \
	&& curl -SL "https://www.python.org/ftp/python/$PYTHON_VERSION/Python-$PYTHON_VERSION.tar.xz.asc" -o python.tar.xz.asc \
	&& gpg --verify python.tar.xz.asc \
	&& tar -xJC /usr/src/python --strip-components=1 -f python.tar.xz \
	&& rm python.tar.xz* \
	&& cd /usr/src/python \
	&& ./configure --enable-shared --enable-unicode=ucs4 \
	&& make -j$(nproc) \
	&& make install \
	&& ldconfig \
	&& curl -SL 'https://bootstrap.pypa.io/get-pip.py' | python3 \
	&& pip install --no-cache-dir --upgrade pip==$PYTHON_PIP_VERSION \
	&& find /usr/local \
		\( -type d -a -name test -o -name tests \) \
		-o \( -type f -a -name '*.pyc' -o -name '*.pyo' \) \
		-exec rm -rf '{}' + \
	&& rm -rf /usr/src/python
```

-	Created: Wed, 09 Sep 2015 20:53:16 GMT
-	Parent Layer: `8526d132178a041cfcc0cc5df38663064b09b80c1bea1662d50284559dca05f6`
-	Docker Version: 1.7.1
-	Virtual Size: 70.9 MB (70948267 bytes)
-	v2 Blob: `sha256:69b3e34483460444a9288f5a7c860dfb6548d31376ab59fa6ec8d73879670934`
-	v2 Content-Length: 20.6 MB (20591942 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:53:45 GMT

#### `d9c0f04961a4bc17a18f6ca7cfecd049ba8855cf2036b2f164c988c437800177`

```dockerfile
RUN cd /usr/local/bin \
	&& ln -s idle3 idle \
	&& ln -s pydoc3 pydoc \
	&& ln -s python3 python \
	&& ln -s python-config3 python-config
```

-	Created: Wed, 09 Sep 2015 20:53:18 GMT
-	Parent Layer: `44cc5c5a22f5b1bf1c96b0fb80d1c456cbdad800365f43e165cc4643f6f0bbe3`
-	Docker Version: 1.7.1
-	Virtual Size: 32.0 B
-	v2 Blob: `sha256:72b4768ceae776d3488a9b1e8b497368e8ca639680f4fa4a5b9e91b4f9eba7ce`
-	v2 Content-Length: 238.0 B
-	v2 Last-Modified: Wed, 09 Sep 2015 21:53:25 GMT

#### `b8240e0baf202023610193f153b87fc4c2837a0511c15b3b81ef7bb15d0625b2`

```dockerfile
CMD ["python3"]
```

-	Created: Wed, 09 Sep 2015 20:53:18 GMT
-	Parent Layer: `d9c0f04961a4bc17a18f6ca7cfecd049ba8855cf2036b2f164c988c437800177`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

## `python:3.4.3`

```console
$ docker pull library/python@sha256:7fef2145dbb6d40a2560fc8759f4da2197abf523725ee4ddb1b2ed4da16bd97c
```

-	Total Virtual Size: 685.8 MB (685750767 bytes)
-	Total v2 Content-Length: 263.1 MB (263057951 bytes)

### Layers (13)

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
-	v2 Blob: `sha256:b3010ec3eb21ac3df74757a47832fb17395b76ad3a30794074cefd07541d3557`
-	v2 Content-Length: 18.5 MB (18538591 bytes)
-	v2 Last-Modified: Thu, 10 Sep 2015 23:36:30 GMT

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

#### `a7131b97316204530af26e42319aeda8ac44cd5ac2891e5dab45e16deb1e592d`

```dockerfile
RUN apt-get purge -y python.*
```

-	Created: Wed, 09 Sep 2015 20:20:46 GMT
-	Parent Layer: `16b189cc8ce688f9f1d8f1d837fa0891107450a06c795b1cba8f6c33a4454280`
-	Docker Version: 1.7.1
-	Virtual Size: 975.3 KB (975277 bytes)
-	v2 Blob: `sha256:20cdbe5b7a6f64396bcabde9b06c16a0b41e2c7fd39b28eff1ee3670a9f0516e`
-	v2 Content-Length: 220.4 KB (220377 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:29:17 GMT

#### `d7cbb60bc416f832c685b38578b77da5f3716cba15d4bcb45d850809a4c112eb`

```dockerfile
ENV LANG=C.UTF-8
```

-	Created: Wed, 09 Sep 2015 20:20:48 GMT
-	Parent Layer: `a7131b97316204530af26e42319aeda8ac44cd5ac2891e5dab45e16deb1e592d`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `d8ea027435229a8bdc09fa68db0043f1e2059ec889a3715c3e184553aee36da4`

```dockerfile
RUN gpg --keyserver ha.pool.sks-keyservers.net --recv-keys 97FC712E4C024BBEA48A61ED3A5CA953F73C700D
```

-	Created: Wed, 09 Sep 2015 20:53:54 GMT
-	Parent Layer: `d7cbb60bc416f832c685b38578b77da5f3716cba15d4bcb45d850809a4c112eb`
-	Docker Version: 1.7.1
-	Virtual Size: 12.6 KB (12606 bytes)
-	v2 Blob: `sha256:2fdbb7a55da29a948a258ac37edb8f60a95a8c9757555c009ac32bc5a50e4197`
-	v2 Content-Length: 6.7 KB (6737 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:55:10 GMT

#### `064a8786bf0a61ecaab4d1adb836a4f086b80c867b9b16a592cb28de744f8816`

```dockerfile
ENV PYTHON_VERSION=3.4.3
```

-	Created: Wed, 09 Sep 2015 20:53:55 GMT
-	Parent Layer: `d8ea027435229a8bdc09fa68db0043f1e2059ec889a3715c3e184553aee36da4`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `6917da306757202609231915c206081f6adb4e38a3e8d9756c2120e7b75549f4`

```dockerfile
ENV PYTHON_PIP_VERSION=7.1.2
```

-	Created: Wed, 09 Sep 2015 20:53:55 GMT
-	Parent Layer: `064a8786bf0a61ecaab4d1adb836a4f086b80c867b9b16a592cb28de744f8816`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `9b31409e47d79f324e4c0d1ef93af4cfe0ab538c3054a23f2e4c4ca0b72a01f4`

```dockerfile
RUN set -x \
	&& mkdir -p /usr/src/python \
	&& curl -SL "https://www.python.org/ftp/python/$PYTHON_VERSION/Python-$PYTHON_VERSION.tar.xz" -o python.tar.xz \
	&& curl -SL "https://www.python.org/ftp/python/$PYTHON_VERSION/Python-$PYTHON_VERSION.tar.xz.asc" -o python.tar.xz.asc \
	&& gpg --verify python.tar.xz.asc \
	&& tar -xJC /usr/src/python --strip-components=1 -f python.tar.xz \
	&& rm python.tar.xz* \
	&& cd /usr/src/python \
	&& ./configure --enable-shared --enable-unicode=ucs4 \
	&& make -j$(nproc) \
	&& make install \
	&& ldconfig \
	&& pip3 install --no-cache-dir --upgrade pip==$PYTHON_PIP_VERSION \
	&& find /usr/local \
		\( -type d -a -name test -o -name tests \) \
		-o \( -type f -a -name '*.pyc' -o -name '*.pyo' \) \
		-exec rm -rf '{}' + \
	&& rm -rf /usr/src/python
```

-	Created: Wed, 09 Sep 2015 20:56:24 GMT
-	Parent Layer: `6917da306757202609231915c206081f6adb4e38a3e8d9756c2120e7b75549f4`
-	Docker Version: 1.7.1
-	Virtual Size: 78.3 MB (78277878 bytes)
-	v2 Blob: `sha256:0817c8d4f7a6947ab0a48b0220cb154512ba9855e05588f56d32bf6ec813d136`
-	v2 Content-Length: 22.1 MB (22061444 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:55:04 GMT

#### `60042152b6d8dd1d26dd4155a975ebb3ca1d471df122d576dfb887f477cf5272`

```dockerfile
RUN cd /usr/local/bin \
	&& ln -s easy_install-3.4 easy_install \
	&& ln -s idle3 idle \
	&& ln -s pydoc3 pydoc \
	&& ln -s python3 python \
	&& ln -s python-config3 python-config
```

-	Created: Wed, 09 Sep 2015 20:56:25 GMT
-	Parent Layer: `9b31409e47d79f324e4c0d1ef93af4cfe0ab538c3054a23f2e4c4ca0b72a01f4`
-	Docker Version: 1.7.1
-	Virtual Size: 48.0 B
-	v2 Blob: `sha256:da37f35187ee66f742ec7e3ee6b049b2482461c23c0b9e888e854d8f672f9ef4`
-	v2 Content-Length: 269.0 B
-	v2 Last-Modified: Wed, 09 Sep 2015 21:54:44 GMT

#### `575cb3ad9b670cb1d58f17ce0c7ce7deed835887e1fdd1013002226348c88a6d`

```dockerfile
CMD ["python3"]
```

-	Created: Wed, 09 Sep 2015 20:56:26 GMT
-	Parent Layer: `60042152b6d8dd1d26dd4155a975ebb3ca1d471df122d576dfb887f477cf5272`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

## `python:3.4`

```console
$ docker pull library/python@sha256:a15898ce24108ac46444b47c8dec24b75f0a942d77e131cf3334a5b2d702457d
```

-	Total Virtual Size: 685.8 MB (685750767 bytes)
-	Total v2 Content-Length: 263.1 MB (263057951 bytes)

### Layers (13)

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
-	v2 Blob: `sha256:b3010ec3eb21ac3df74757a47832fb17395b76ad3a30794074cefd07541d3557`
-	v2 Content-Length: 18.5 MB (18538591 bytes)
-	v2 Last-Modified: Thu, 10 Sep 2015 23:36:30 GMT

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

#### `a7131b97316204530af26e42319aeda8ac44cd5ac2891e5dab45e16deb1e592d`

```dockerfile
RUN apt-get purge -y python.*
```

-	Created: Wed, 09 Sep 2015 20:20:46 GMT
-	Parent Layer: `16b189cc8ce688f9f1d8f1d837fa0891107450a06c795b1cba8f6c33a4454280`
-	Docker Version: 1.7.1
-	Virtual Size: 975.3 KB (975277 bytes)
-	v2 Blob: `sha256:20cdbe5b7a6f64396bcabde9b06c16a0b41e2c7fd39b28eff1ee3670a9f0516e`
-	v2 Content-Length: 220.4 KB (220377 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:29:17 GMT

#### `d7cbb60bc416f832c685b38578b77da5f3716cba15d4bcb45d850809a4c112eb`

```dockerfile
ENV LANG=C.UTF-8
```

-	Created: Wed, 09 Sep 2015 20:20:48 GMT
-	Parent Layer: `a7131b97316204530af26e42319aeda8ac44cd5ac2891e5dab45e16deb1e592d`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `d8ea027435229a8bdc09fa68db0043f1e2059ec889a3715c3e184553aee36da4`

```dockerfile
RUN gpg --keyserver ha.pool.sks-keyservers.net --recv-keys 97FC712E4C024BBEA48A61ED3A5CA953F73C700D
```

-	Created: Wed, 09 Sep 2015 20:53:54 GMT
-	Parent Layer: `d7cbb60bc416f832c685b38578b77da5f3716cba15d4bcb45d850809a4c112eb`
-	Docker Version: 1.7.1
-	Virtual Size: 12.6 KB (12606 bytes)
-	v2 Blob: `sha256:2fdbb7a55da29a948a258ac37edb8f60a95a8c9757555c009ac32bc5a50e4197`
-	v2 Content-Length: 6.7 KB (6737 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:55:10 GMT

#### `064a8786bf0a61ecaab4d1adb836a4f086b80c867b9b16a592cb28de744f8816`

```dockerfile
ENV PYTHON_VERSION=3.4.3
```

-	Created: Wed, 09 Sep 2015 20:53:55 GMT
-	Parent Layer: `d8ea027435229a8bdc09fa68db0043f1e2059ec889a3715c3e184553aee36da4`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `6917da306757202609231915c206081f6adb4e38a3e8d9756c2120e7b75549f4`

```dockerfile
ENV PYTHON_PIP_VERSION=7.1.2
```

-	Created: Wed, 09 Sep 2015 20:53:55 GMT
-	Parent Layer: `064a8786bf0a61ecaab4d1adb836a4f086b80c867b9b16a592cb28de744f8816`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `9b31409e47d79f324e4c0d1ef93af4cfe0ab538c3054a23f2e4c4ca0b72a01f4`

```dockerfile
RUN set -x \
	&& mkdir -p /usr/src/python \
	&& curl -SL "https://www.python.org/ftp/python/$PYTHON_VERSION/Python-$PYTHON_VERSION.tar.xz" -o python.tar.xz \
	&& curl -SL "https://www.python.org/ftp/python/$PYTHON_VERSION/Python-$PYTHON_VERSION.tar.xz.asc" -o python.tar.xz.asc \
	&& gpg --verify python.tar.xz.asc \
	&& tar -xJC /usr/src/python --strip-components=1 -f python.tar.xz \
	&& rm python.tar.xz* \
	&& cd /usr/src/python \
	&& ./configure --enable-shared --enable-unicode=ucs4 \
	&& make -j$(nproc) \
	&& make install \
	&& ldconfig \
	&& pip3 install --no-cache-dir --upgrade pip==$PYTHON_PIP_VERSION \
	&& find /usr/local \
		\( -type d -a -name test -o -name tests \) \
		-o \( -type f -a -name '*.pyc' -o -name '*.pyo' \) \
		-exec rm -rf '{}' + \
	&& rm -rf /usr/src/python
```

-	Created: Wed, 09 Sep 2015 20:56:24 GMT
-	Parent Layer: `6917da306757202609231915c206081f6adb4e38a3e8d9756c2120e7b75549f4`
-	Docker Version: 1.7.1
-	Virtual Size: 78.3 MB (78277878 bytes)
-	v2 Blob: `sha256:0817c8d4f7a6947ab0a48b0220cb154512ba9855e05588f56d32bf6ec813d136`
-	v2 Content-Length: 22.1 MB (22061444 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:55:04 GMT

#### `60042152b6d8dd1d26dd4155a975ebb3ca1d471df122d576dfb887f477cf5272`

```dockerfile
RUN cd /usr/local/bin \
	&& ln -s easy_install-3.4 easy_install \
	&& ln -s idle3 idle \
	&& ln -s pydoc3 pydoc \
	&& ln -s python3 python \
	&& ln -s python-config3 python-config
```

-	Created: Wed, 09 Sep 2015 20:56:25 GMT
-	Parent Layer: `9b31409e47d79f324e4c0d1ef93af4cfe0ab538c3054a23f2e4c4ca0b72a01f4`
-	Docker Version: 1.7.1
-	Virtual Size: 48.0 B
-	v2 Blob: `sha256:da37f35187ee66f742ec7e3ee6b049b2482461c23c0b9e888e854d8f672f9ef4`
-	v2 Content-Length: 269.0 B
-	v2 Last-Modified: Wed, 09 Sep 2015 21:54:44 GMT

#### `575cb3ad9b670cb1d58f17ce0c7ce7deed835887e1fdd1013002226348c88a6d`

```dockerfile
CMD ["python3"]
```

-	Created: Wed, 09 Sep 2015 20:56:26 GMT
-	Parent Layer: `60042152b6d8dd1d26dd4155a975ebb3ca1d471df122d576dfb887f477cf5272`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

## `python:3`

```console
$ docker pull library/python@sha256:53aeeaf6a30d3a7106c4a1510b0e898ecce153205205a00af4f685d72d5c15e2
```

-	Total Virtual Size: 685.8 MB (685750767 bytes)
-	Total v2 Content-Length: 263.1 MB (263057951 bytes)

### Layers (13)

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
-	v2 Blob: `sha256:b3010ec3eb21ac3df74757a47832fb17395b76ad3a30794074cefd07541d3557`
-	v2 Content-Length: 18.5 MB (18538591 bytes)
-	v2 Last-Modified: Thu, 10 Sep 2015 23:36:30 GMT

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

#### `a7131b97316204530af26e42319aeda8ac44cd5ac2891e5dab45e16deb1e592d`

```dockerfile
RUN apt-get purge -y python.*
```

-	Created: Wed, 09 Sep 2015 20:20:46 GMT
-	Parent Layer: `16b189cc8ce688f9f1d8f1d837fa0891107450a06c795b1cba8f6c33a4454280`
-	Docker Version: 1.7.1
-	Virtual Size: 975.3 KB (975277 bytes)
-	v2 Blob: `sha256:20cdbe5b7a6f64396bcabde9b06c16a0b41e2c7fd39b28eff1ee3670a9f0516e`
-	v2 Content-Length: 220.4 KB (220377 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:29:17 GMT

#### `d7cbb60bc416f832c685b38578b77da5f3716cba15d4bcb45d850809a4c112eb`

```dockerfile
ENV LANG=C.UTF-8
```

-	Created: Wed, 09 Sep 2015 20:20:48 GMT
-	Parent Layer: `a7131b97316204530af26e42319aeda8ac44cd5ac2891e5dab45e16deb1e592d`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `d8ea027435229a8bdc09fa68db0043f1e2059ec889a3715c3e184553aee36da4`

```dockerfile
RUN gpg --keyserver ha.pool.sks-keyservers.net --recv-keys 97FC712E4C024BBEA48A61ED3A5CA953F73C700D
```

-	Created: Wed, 09 Sep 2015 20:53:54 GMT
-	Parent Layer: `d7cbb60bc416f832c685b38578b77da5f3716cba15d4bcb45d850809a4c112eb`
-	Docker Version: 1.7.1
-	Virtual Size: 12.6 KB (12606 bytes)
-	v2 Blob: `sha256:2fdbb7a55da29a948a258ac37edb8f60a95a8c9757555c009ac32bc5a50e4197`
-	v2 Content-Length: 6.7 KB (6737 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:55:10 GMT

#### `064a8786bf0a61ecaab4d1adb836a4f086b80c867b9b16a592cb28de744f8816`

```dockerfile
ENV PYTHON_VERSION=3.4.3
```

-	Created: Wed, 09 Sep 2015 20:53:55 GMT
-	Parent Layer: `d8ea027435229a8bdc09fa68db0043f1e2059ec889a3715c3e184553aee36da4`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `6917da306757202609231915c206081f6adb4e38a3e8d9756c2120e7b75549f4`

```dockerfile
ENV PYTHON_PIP_VERSION=7.1.2
```

-	Created: Wed, 09 Sep 2015 20:53:55 GMT
-	Parent Layer: `064a8786bf0a61ecaab4d1adb836a4f086b80c867b9b16a592cb28de744f8816`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `9b31409e47d79f324e4c0d1ef93af4cfe0ab538c3054a23f2e4c4ca0b72a01f4`

```dockerfile
RUN set -x \
	&& mkdir -p /usr/src/python \
	&& curl -SL "https://www.python.org/ftp/python/$PYTHON_VERSION/Python-$PYTHON_VERSION.tar.xz" -o python.tar.xz \
	&& curl -SL "https://www.python.org/ftp/python/$PYTHON_VERSION/Python-$PYTHON_VERSION.tar.xz.asc" -o python.tar.xz.asc \
	&& gpg --verify python.tar.xz.asc \
	&& tar -xJC /usr/src/python --strip-components=1 -f python.tar.xz \
	&& rm python.tar.xz* \
	&& cd /usr/src/python \
	&& ./configure --enable-shared --enable-unicode=ucs4 \
	&& make -j$(nproc) \
	&& make install \
	&& ldconfig \
	&& pip3 install --no-cache-dir --upgrade pip==$PYTHON_PIP_VERSION \
	&& find /usr/local \
		\( -type d -a -name test -o -name tests \) \
		-o \( -type f -a -name '*.pyc' -o -name '*.pyo' \) \
		-exec rm -rf '{}' + \
	&& rm -rf /usr/src/python
```

-	Created: Wed, 09 Sep 2015 20:56:24 GMT
-	Parent Layer: `6917da306757202609231915c206081f6adb4e38a3e8d9756c2120e7b75549f4`
-	Docker Version: 1.7.1
-	Virtual Size: 78.3 MB (78277878 bytes)
-	v2 Blob: `sha256:0817c8d4f7a6947ab0a48b0220cb154512ba9855e05588f56d32bf6ec813d136`
-	v2 Content-Length: 22.1 MB (22061444 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:55:04 GMT

#### `60042152b6d8dd1d26dd4155a975ebb3ca1d471df122d576dfb887f477cf5272`

```dockerfile
RUN cd /usr/local/bin \
	&& ln -s easy_install-3.4 easy_install \
	&& ln -s idle3 idle \
	&& ln -s pydoc3 pydoc \
	&& ln -s python3 python \
	&& ln -s python-config3 python-config
```

-	Created: Wed, 09 Sep 2015 20:56:25 GMT
-	Parent Layer: `9b31409e47d79f324e4c0d1ef93af4cfe0ab538c3054a23f2e4c4ca0b72a01f4`
-	Docker Version: 1.7.1
-	Virtual Size: 48.0 B
-	v2 Blob: `sha256:da37f35187ee66f742ec7e3ee6b049b2482461c23c0b9e888e854d8f672f9ef4`
-	v2 Content-Length: 269.0 B
-	v2 Last-Modified: Wed, 09 Sep 2015 21:54:44 GMT

#### `575cb3ad9b670cb1d58f17ce0c7ce7deed835887e1fdd1013002226348c88a6d`

```dockerfile
CMD ["python3"]
```

-	Created: Wed, 09 Sep 2015 20:56:26 GMT
-	Parent Layer: `60042152b6d8dd1d26dd4155a975ebb3ca1d471df122d576dfb887f477cf5272`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

## `python:latest`

```console
$ docker pull library/python@sha256:045137166feacb1f451680a4f79eb3088c238622ed2d783398d901e354667827
```

-	Total Virtual Size: 685.8 MB (685750767 bytes)
-	Total v2 Content-Length: 263.1 MB (263057951 bytes)

### Layers (13)

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
-	v2 Blob: `sha256:b3010ec3eb21ac3df74757a47832fb17395b76ad3a30794074cefd07541d3557`
-	v2 Content-Length: 18.5 MB (18538591 bytes)
-	v2 Last-Modified: Thu, 10 Sep 2015 23:36:30 GMT

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

#### `a7131b97316204530af26e42319aeda8ac44cd5ac2891e5dab45e16deb1e592d`

```dockerfile
RUN apt-get purge -y python.*
```

-	Created: Wed, 09 Sep 2015 20:20:46 GMT
-	Parent Layer: `16b189cc8ce688f9f1d8f1d837fa0891107450a06c795b1cba8f6c33a4454280`
-	Docker Version: 1.7.1
-	Virtual Size: 975.3 KB (975277 bytes)
-	v2 Blob: `sha256:20cdbe5b7a6f64396bcabde9b06c16a0b41e2c7fd39b28eff1ee3670a9f0516e`
-	v2 Content-Length: 220.4 KB (220377 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:29:17 GMT

#### `d7cbb60bc416f832c685b38578b77da5f3716cba15d4bcb45d850809a4c112eb`

```dockerfile
ENV LANG=C.UTF-8
```

-	Created: Wed, 09 Sep 2015 20:20:48 GMT
-	Parent Layer: `a7131b97316204530af26e42319aeda8ac44cd5ac2891e5dab45e16deb1e592d`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `d8ea027435229a8bdc09fa68db0043f1e2059ec889a3715c3e184553aee36da4`

```dockerfile
RUN gpg --keyserver ha.pool.sks-keyservers.net --recv-keys 97FC712E4C024BBEA48A61ED3A5CA953F73C700D
```

-	Created: Wed, 09 Sep 2015 20:53:54 GMT
-	Parent Layer: `d7cbb60bc416f832c685b38578b77da5f3716cba15d4bcb45d850809a4c112eb`
-	Docker Version: 1.7.1
-	Virtual Size: 12.6 KB (12606 bytes)
-	v2 Blob: `sha256:2fdbb7a55da29a948a258ac37edb8f60a95a8c9757555c009ac32bc5a50e4197`
-	v2 Content-Length: 6.7 KB (6737 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:55:10 GMT

#### `064a8786bf0a61ecaab4d1adb836a4f086b80c867b9b16a592cb28de744f8816`

```dockerfile
ENV PYTHON_VERSION=3.4.3
```

-	Created: Wed, 09 Sep 2015 20:53:55 GMT
-	Parent Layer: `d8ea027435229a8bdc09fa68db0043f1e2059ec889a3715c3e184553aee36da4`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `6917da306757202609231915c206081f6adb4e38a3e8d9756c2120e7b75549f4`

```dockerfile
ENV PYTHON_PIP_VERSION=7.1.2
```

-	Created: Wed, 09 Sep 2015 20:53:55 GMT
-	Parent Layer: `064a8786bf0a61ecaab4d1adb836a4f086b80c867b9b16a592cb28de744f8816`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `9b31409e47d79f324e4c0d1ef93af4cfe0ab538c3054a23f2e4c4ca0b72a01f4`

```dockerfile
RUN set -x \
	&& mkdir -p /usr/src/python \
	&& curl -SL "https://www.python.org/ftp/python/$PYTHON_VERSION/Python-$PYTHON_VERSION.tar.xz" -o python.tar.xz \
	&& curl -SL "https://www.python.org/ftp/python/$PYTHON_VERSION/Python-$PYTHON_VERSION.tar.xz.asc" -o python.tar.xz.asc \
	&& gpg --verify python.tar.xz.asc \
	&& tar -xJC /usr/src/python --strip-components=1 -f python.tar.xz \
	&& rm python.tar.xz* \
	&& cd /usr/src/python \
	&& ./configure --enable-shared --enable-unicode=ucs4 \
	&& make -j$(nproc) \
	&& make install \
	&& ldconfig \
	&& pip3 install --no-cache-dir --upgrade pip==$PYTHON_PIP_VERSION \
	&& find /usr/local \
		\( -type d -a -name test -o -name tests \) \
		-o \( -type f -a -name '*.pyc' -o -name '*.pyo' \) \
		-exec rm -rf '{}' + \
	&& rm -rf /usr/src/python
```

-	Created: Wed, 09 Sep 2015 20:56:24 GMT
-	Parent Layer: `6917da306757202609231915c206081f6adb4e38a3e8d9756c2120e7b75549f4`
-	Docker Version: 1.7.1
-	Virtual Size: 78.3 MB (78277878 bytes)
-	v2 Blob: `sha256:0817c8d4f7a6947ab0a48b0220cb154512ba9855e05588f56d32bf6ec813d136`
-	v2 Content-Length: 22.1 MB (22061444 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:55:04 GMT

#### `60042152b6d8dd1d26dd4155a975ebb3ca1d471df122d576dfb887f477cf5272`

```dockerfile
RUN cd /usr/local/bin \
	&& ln -s easy_install-3.4 easy_install \
	&& ln -s idle3 idle \
	&& ln -s pydoc3 pydoc \
	&& ln -s python3 python \
	&& ln -s python-config3 python-config
```

-	Created: Wed, 09 Sep 2015 20:56:25 GMT
-	Parent Layer: `9b31409e47d79f324e4c0d1ef93af4cfe0ab538c3054a23f2e4c4ca0b72a01f4`
-	Docker Version: 1.7.1
-	Virtual Size: 48.0 B
-	v2 Blob: `sha256:da37f35187ee66f742ec7e3ee6b049b2482461c23c0b9e888e854d8f672f9ef4`
-	v2 Content-Length: 269.0 B
-	v2 Last-Modified: Wed, 09 Sep 2015 21:54:44 GMT

#### `575cb3ad9b670cb1d58f17ce0c7ce7deed835887e1fdd1013002226348c88a6d`

```dockerfile
CMD ["python3"]
```

-	Created: Wed, 09 Sep 2015 20:56:26 GMT
-	Parent Layer: `60042152b6d8dd1d26dd4155a975ebb3ca1d471df122d576dfb887f477cf5272`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

## `python:3.4.3-onbuild`

```console
$ docker pull library/python@sha256:9c06c54f98d1bfd16dcc1180471cb4048d97edf63d5862769fb12dd7aaa24176
```

-	Total Virtual Size: 685.8 MB (685750767 bytes)
-	Total v2 Content-Length: 263.1 MB (263058206 bytes)

### Layers (18)

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
-	v2 Blob: `sha256:b3010ec3eb21ac3df74757a47832fb17395b76ad3a30794074cefd07541d3557`
-	v2 Content-Length: 18.5 MB (18538591 bytes)
-	v2 Last-Modified: Thu, 10 Sep 2015 23:36:30 GMT

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

#### `a7131b97316204530af26e42319aeda8ac44cd5ac2891e5dab45e16deb1e592d`

```dockerfile
RUN apt-get purge -y python.*
```

-	Created: Wed, 09 Sep 2015 20:20:46 GMT
-	Parent Layer: `16b189cc8ce688f9f1d8f1d837fa0891107450a06c795b1cba8f6c33a4454280`
-	Docker Version: 1.7.1
-	Virtual Size: 975.3 KB (975277 bytes)
-	v2 Blob: `sha256:20cdbe5b7a6f64396bcabde9b06c16a0b41e2c7fd39b28eff1ee3670a9f0516e`
-	v2 Content-Length: 220.4 KB (220377 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:29:17 GMT

#### `d7cbb60bc416f832c685b38578b77da5f3716cba15d4bcb45d850809a4c112eb`

```dockerfile
ENV LANG=C.UTF-8
```

-	Created: Wed, 09 Sep 2015 20:20:48 GMT
-	Parent Layer: `a7131b97316204530af26e42319aeda8ac44cd5ac2891e5dab45e16deb1e592d`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `d8ea027435229a8bdc09fa68db0043f1e2059ec889a3715c3e184553aee36da4`

```dockerfile
RUN gpg --keyserver ha.pool.sks-keyservers.net --recv-keys 97FC712E4C024BBEA48A61ED3A5CA953F73C700D
```

-	Created: Wed, 09 Sep 2015 20:53:54 GMT
-	Parent Layer: `d7cbb60bc416f832c685b38578b77da5f3716cba15d4bcb45d850809a4c112eb`
-	Docker Version: 1.7.1
-	Virtual Size: 12.6 KB (12606 bytes)
-	v2 Blob: `sha256:2fdbb7a55da29a948a258ac37edb8f60a95a8c9757555c009ac32bc5a50e4197`
-	v2 Content-Length: 6.7 KB (6737 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:55:10 GMT

#### `064a8786bf0a61ecaab4d1adb836a4f086b80c867b9b16a592cb28de744f8816`

```dockerfile
ENV PYTHON_VERSION=3.4.3
```

-	Created: Wed, 09 Sep 2015 20:53:55 GMT
-	Parent Layer: `d8ea027435229a8bdc09fa68db0043f1e2059ec889a3715c3e184553aee36da4`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `6917da306757202609231915c206081f6adb4e38a3e8d9756c2120e7b75549f4`

```dockerfile
ENV PYTHON_PIP_VERSION=7.1.2
```

-	Created: Wed, 09 Sep 2015 20:53:55 GMT
-	Parent Layer: `064a8786bf0a61ecaab4d1adb836a4f086b80c867b9b16a592cb28de744f8816`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `9b31409e47d79f324e4c0d1ef93af4cfe0ab538c3054a23f2e4c4ca0b72a01f4`

```dockerfile
RUN set -x \
	&& mkdir -p /usr/src/python \
	&& curl -SL "https://www.python.org/ftp/python/$PYTHON_VERSION/Python-$PYTHON_VERSION.tar.xz" -o python.tar.xz \
	&& curl -SL "https://www.python.org/ftp/python/$PYTHON_VERSION/Python-$PYTHON_VERSION.tar.xz.asc" -o python.tar.xz.asc \
	&& gpg --verify python.tar.xz.asc \
	&& tar -xJC /usr/src/python --strip-components=1 -f python.tar.xz \
	&& rm python.tar.xz* \
	&& cd /usr/src/python \
	&& ./configure --enable-shared --enable-unicode=ucs4 \
	&& make -j$(nproc) \
	&& make install \
	&& ldconfig \
	&& pip3 install --no-cache-dir --upgrade pip==$PYTHON_PIP_VERSION \
	&& find /usr/local \
		\( -type d -a -name test -o -name tests \) \
		-o \( -type f -a -name '*.pyc' -o -name '*.pyo' \) \
		-exec rm -rf '{}' + \
	&& rm -rf /usr/src/python
```

-	Created: Wed, 09 Sep 2015 20:56:24 GMT
-	Parent Layer: `6917da306757202609231915c206081f6adb4e38a3e8d9756c2120e7b75549f4`
-	Docker Version: 1.7.1
-	Virtual Size: 78.3 MB (78277878 bytes)
-	v2 Blob: `sha256:0817c8d4f7a6947ab0a48b0220cb154512ba9855e05588f56d32bf6ec813d136`
-	v2 Content-Length: 22.1 MB (22061444 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:55:04 GMT

#### `60042152b6d8dd1d26dd4155a975ebb3ca1d471df122d576dfb887f477cf5272`

```dockerfile
RUN cd /usr/local/bin \
	&& ln -s easy_install-3.4 easy_install \
	&& ln -s idle3 idle \
	&& ln -s pydoc3 pydoc \
	&& ln -s python3 python \
	&& ln -s python-config3 python-config
```

-	Created: Wed, 09 Sep 2015 20:56:25 GMT
-	Parent Layer: `9b31409e47d79f324e4c0d1ef93af4cfe0ab538c3054a23f2e4c4ca0b72a01f4`
-	Docker Version: 1.7.1
-	Virtual Size: 48.0 B
-	v2 Blob: `sha256:da37f35187ee66f742ec7e3ee6b049b2482461c23c0b9e888e854d8f672f9ef4`
-	v2 Content-Length: 269.0 B
-	v2 Last-Modified: Wed, 09 Sep 2015 21:54:44 GMT

#### `575cb3ad9b670cb1d58f17ce0c7ce7deed835887e1fdd1013002226348c88a6d`

```dockerfile
CMD ["python3"]
```

-	Created: Wed, 09 Sep 2015 20:56:26 GMT
-	Parent Layer: `60042152b6d8dd1d26dd4155a975ebb3ca1d471df122d576dfb887f477cf5272`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `11b608fa74ec21b9886a0e58797c634839caaf9a7696ab65238adc8f068514f2`

```dockerfile
RUN mkdir -p /usr/src/app
```

-	Created: Wed, 09 Sep 2015 20:57:42 GMT
-	Parent Layer: `575cb3ad9b670cb1d58f17ce0c7ce7deed835887e1fdd1013002226348c88a6d`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:18ae4899185461eb6c5db8738cb28266f494072bca49858810a00477052e77cf`
-	v2 Content-Length: 127.0 B
-	v2 Last-Modified: Wed, 09 Sep 2015 21:57:22 GMT

#### `ca8e82415f8f12859931853204100f11c785a51048e5005cc5b09a761287478b`

```dockerfile
WORKDIR /usr/src/app
```

-	Created: Wed, 09 Sep 2015 20:57:42 GMT
-	Parent Layer: `11b608fa74ec21b9886a0e58797c634839caaf9a7696ab65238adc8f068514f2`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `685adf5465a3ca892b763f7feb5dcf34d33737b59e66f965f5a6a5674d5acd96`

```dockerfile
ONBUILD COPY requirements.txt /usr/src/app/
```

-	Created: Wed, 09 Sep 2015 20:57:43 GMT
-	Parent Layer: `ca8e82415f8f12859931853204100f11c785a51048e5005cc5b09a761287478b`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `04e257c81100d981db8b4d28e90e58602e5f10e5fde156d7245b152961daa332`

```dockerfile
ONBUILD RUN pip install --no-cache-dir -r requirements.txt
```

-	Created: Wed, 09 Sep 2015 20:57:43 GMT
-	Parent Layer: `685adf5465a3ca892b763f7feb5dcf34d33737b59e66f965f5a6a5674d5acd96`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `9ffc70d823599c713dd72f494bf1e9b8c503706fedca54292910cd171f748929`

```dockerfile
ONBUILD COPY . /usr/src/app
```

-	Created: Wed, 09 Sep 2015 20:57:43 GMT
-	Parent Layer: `04e257c81100d981db8b4d28e90e58602e5f10e5fde156d7245b152961daa332`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

## `python:3.4-onbuild`

```console
$ docker pull library/python@sha256:e89babefe89cdb6b8e655a1a0d7bd65e296f4816775c2550c538caa0bc947eee
```

-	Total Virtual Size: 685.8 MB (685750767 bytes)
-	Total v2 Content-Length: 263.1 MB (263058206 bytes)

### Layers (18)

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
-	v2 Blob: `sha256:b3010ec3eb21ac3df74757a47832fb17395b76ad3a30794074cefd07541d3557`
-	v2 Content-Length: 18.5 MB (18538591 bytes)
-	v2 Last-Modified: Thu, 10 Sep 2015 23:36:30 GMT

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

#### `a7131b97316204530af26e42319aeda8ac44cd5ac2891e5dab45e16deb1e592d`

```dockerfile
RUN apt-get purge -y python.*
```

-	Created: Wed, 09 Sep 2015 20:20:46 GMT
-	Parent Layer: `16b189cc8ce688f9f1d8f1d837fa0891107450a06c795b1cba8f6c33a4454280`
-	Docker Version: 1.7.1
-	Virtual Size: 975.3 KB (975277 bytes)
-	v2 Blob: `sha256:20cdbe5b7a6f64396bcabde9b06c16a0b41e2c7fd39b28eff1ee3670a9f0516e`
-	v2 Content-Length: 220.4 KB (220377 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:29:17 GMT

#### `d7cbb60bc416f832c685b38578b77da5f3716cba15d4bcb45d850809a4c112eb`

```dockerfile
ENV LANG=C.UTF-8
```

-	Created: Wed, 09 Sep 2015 20:20:48 GMT
-	Parent Layer: `a7131b97316204530af26e42319aeda8ac44cd5ac2891e5dab45e16deb1e592d`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `d8ea027435229a8bdc09fa68db0043f1e2059ec889a3715c3e184553aee36da4`

```dockerfile
RUN gpg --keyserver ha.pool.sks-keyservers.net --recv-keys 97FC712E4C024BBEA48A61ED3A5CA953F73C700D
```

-	Created: Wed, 09 Sep 2015 20:53:54 GMT
-	Parent Layer: `d7cbb60bc416f832c685b38578b77da5f3716cba15d4bcb45d850809a4c112eb`
-	Docker Version: 1.7.1
-	Virtual Size: 12.6 KB (12606 bytes)
-	v2 Blob: `sha256:2fdbb7a55da29a948a258ac37edb8f60a95a8c9757555c009ac32bc5a50e4197`
-	v2 Content-Length: 6.7 KB (6737 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:55:10 GMT

#### `064a8786bf0a61ecaab4d1adb836a4f086b80c867b9b16a592cb28de744f8816`

```dockerfile
ENV PYTHON_VERSION=3.4.3
```

-	Created: Wed, 09 Sep 2015 20:53:55 GMT
-	Parent Layer: `d8ea027435229a8bdc09fa68db0043f1e2059ec889a3715c3e184553aee36da4`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `6917da306757202609231915c206081f6adb4e38a3e8d9756c2120e7b75549f4`

```dockerfile
ENV PYTHON_PIP_VERSION=7.1.2
```

-	Created: Wed, 09 Sep 2015 20:53:55 GMT
-	Parent Layer: `064a8786bf0a61ecaab4d1adb836a4f086b80c867b9b16a592cb28de744f8816`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `9b31409e47d79f324e4c0d1ef93af4cfe0ab538c3054a23f2e4c4ca0b72a01f4`

```dockerfile
RUN set -x \
	&& mkdir -p /usr/src/python \
	&& curl -SL "https://www.python.org/ftp/python/$PYTHON_VERSION/Python-$PYTHON_VERSION.tar.xz" -o python.tar.xz \
	&& curl -SL "https://www.python.org/ftp/python/$PYTHON_VERSION/Python-$PYTHON_VERSION.tar.xz.asc" -o python.tar.xz.asc \
	&& gpg --verify python.tar.xz.asc \
	&& tar -xJC /usr/src/python --strip-components=1 -f python.tar.xz \
	&& rm python.tar.xz* \
	&& cd /usr/src/python \
	&& ./configure --enable-shared --enable-unicode=ucs4 \
	&& make -j$(nproc) \
	&& make install \
	&& ldconfig \
	&& pip3 install --no-cache-dir --upgrade pip==$PYTHON_PIP_VERSION \
	&& find /usr/local \
		\( -type d -a -name test -o -name tests \) \
		-o \( -type f -a -name '*.pyc' -o -name '*.pyo' \) \
		-exec rm -rf '{}' + \
	&& rm -rf /usr/src/python
```

-	Created: Wed, 09 Sep 2015 20:56:24 GMT
-	Parent Layer: `6917da306757202609231915c206081f6adb4e38a3e8d9756c2120e7b75549f4`
-	Docker Version: 1.7.1
-	Virtual Size: 78.3 MB (78277878 bytes)
-	v2 Blob: `sha256:0817c8d4f7a6947ab0a48b0220cb154512ba9855e05588f56d32bf6ec813d136`
-	v2 Content-Length: 22.1 MB (22061444 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:55:04 GMT

#### `60042152b6d8dd1d26dd4155a975ebb3ca1d471df122d576dfb887f477cf5272`

```dockerfile
RUN cd /usr/local/bin \
	&& ln -s easy_install-3.4 easy_install \
	&& ln -s idle3 idle \
	&& ln -s pydoc3 pydoc \
	&& ln -s python3 python \
	&& ln -s python-config3 python-config
```

-	Created: Wed, 09 Sep 2015 20:56:25 GMT
-	Parent Layer: `9b31409e47d79f324e4c0d1ef93af4cfe0ab538c3054a23f2e4c4ca0b72a01f4`
-	Docker Version: 1.7.1
-	Virtual Size: 48.0 B
-	v2 Blob: `sha256:da37f35187ee66f742ec7e3ee6b049b2482461c23c0b9e888e854d8f672f9ef4`
-	v2 Content-Length: 269.0 B
-	v2 Last-Modified: Wed, 09 Sep 2015 21:54:44 GMT

#### `575cb3ad9b670cb1d58f17ce0c7ce7deed835887e1fdd1013002226348c88a6d`

```dockerfile
CMD ["python3"]
```

-	Created: Wed, 09 Sep 2015 20:56:26 GMT
-	Parent Layer: `60042152b6d8dd1d26dd4155a975ebb3ca1d471df122d576dfb887f477cf5272`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `11b608fa74ec21b9886a0e58797c634839caaf9a7696ab65238adc8f068514f2`

```dockerfile
RUN mkdir -p /usr/src/app
```

-	Created: Wed, 09 Sep 2015 20:57:42 GMT
-	Parent Layer: `575cb3ad9b670cb1d58f17ce0c7ce7deed835887e1fdd1013002226348c88a6d`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:18ae4899185461eb6c5db8738cb28266f494072bca49858810a00477052e77cf`
-	v2 Content-Length: 127.0 B
-	v2 Last-Modified: Wed, 09 Sep 2015 21:57:22 GMT

#### `ca8e82415f8f12859931853204100f11c785a51048e5005cc5b09a761287478b`

```dockerfile
WORKDIR /usr/src/app
```

-	Created: Wed, 09 Sep 2015 20:57:42 GMT
-	Parent Layer: `11b608fa74ec21b9886a0e58797c634839caaf9a7696ab65238adc8f068514f2`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `685adf5465a3ca892b763f7feb5dcf34d33737b59e66f965f5a6a5674d5acd96`

```dockerfile
ONBUILD COPY requirements.txt /usr/src/app/
```

-	Created: Wed, 09 Sep 2015 20:57:43 GMT
-	Parent Layer: `ca8e82415f8f12859931853204100f11c785a51048e5005cc5b09a761287478b`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `04e257c81100d981db8b4d28e90e58602e5f10e5fde156d7245b152961daa332`

```dockerfile
ONBUILD RUN pip install --no-cache-dir -r requirements.txt
```

-	Created: Wed, 09 Sep 2015 20:57:43 GMT
-	Parent Layer: `685adf5465a3ca892b763f7feb5dcf34d33737b59e66f965f5a6a5674d5acd96`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `9ffc70d823599c713dd72f494bf1e9b8c503706fedca54292910cd171f748929`

```dockerfile
ONBUILD COPY . /usr/src/app
```

-	Created: Wed, 09 Sep 2015 20:57:43 GMT
-	Parent Layer: `04e257c81100d981db8b4d28e90e58602e5f10e5fde156d7245b152961daa332`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

## `python:3-onbuild`

```console
$ docker pull library/python@sha256:651dab580369517cf28f0c7a5ba13b2f88ac6c2511d5654a1548e770f7703084
```

-	Total Virtual Size: 685.8 MB (685750767 bytes)
-	Total v2 Content-Length: 263.1 MB (263058206 bytes)

### Layers (18)

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
-	v2 Blob: `sha256:b3010ec3eb21ac3df74757a47832fb17395b76ad3a30794074cefd07541d3557`
-	v2 Content-Length: 18.5 MB (18538591 bytes)
-	v2 Last-Modified: Thu, 10 Sep 2015 23:36:30 GMT

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

#### `a7131b97316204530af26e42319aeda8ac44cd5ac2891e5dab45e16deb1e592d`

```dockerfile
RUN apt-get purge -y python.*
```

-	Created: Wed, 09 Sep 2015 20:20:46 GMT
-	Parent Layer: `16b189cc8ce688f9f1d8f1d837fa0891107450a06c795b1cba8f6c33a4454280`
-	Docker Version: 1.7.1
-	Virtual Size: 975.3 KB (975277 bytes)
-	v2 Blob: `sha256:20cdbe5b7a6f64396bcabde9b06c16a0b41e2c7fd39b28eff1ee3670a9f0516e`
-	v2 Content-Length: 220.4 KB (220377 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:29:17 GMT

#### `d7cbb60bc416f832c685b38578b77da5f3716cba15d4bcb45d850809a4c112eb`

```dockerfile
ENV LANG=C.UTF-8
```

-	Created: Wed, 09 Sep 2015 20:20:48 GMT
-	Parent Layer: `a7131b97316204530af26e42319aeda8ac44cd5ac2891e5dab45e16deb1e592d`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `d8ea027435229a8bdc09fa68db0043f1e2059ec889a3715c3e184553aee36da4`

```dockerfile
RUN gpg --keyserver ha.pool.sks-keyservers.net --recv-keys 97FC712E4C024BBEA48A61ED3A5CA953F73C700D
```

-	Created: Wed, 09 Sep 2015 20:53:54 GMT
-	Parent Layer: `d7cbb60bc416f832c685b38578b77da5f3716cba15d4bcb45d850809a4c112eb`
-	Docker Version: 1.7.1
-	Virtual Size: 12.6 KB (12606 bytes)
-	v2 Blob: `sha256:2fdbb7a55da29a948a258ac37edb8f60a95a8c9757555c009ac32bc5a50e4197`
-	v2 Content-Length: 6.7 KB (6737 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:55:10 GMT

#### `064a8786bf0a61ecaab4d1adb836a4f086b80c867b9b16a592cb28de744f8816`

```dockerfile
ENV PYTHON_VERSION=3.4.3
```

-	Created: Wed, 09 Sep 2015 20:53:55 GMT
-	Parent Layer: `d8ea027435229a8bdc09fa68db0043f1e2059ec889a3715c3e184553aee36da4`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `6917da306757202609231915c206081f6adb4e38a3e8d9756c2120e7b75549f4`

```dockerfile
ENV PYTHON_PIP_VERSION=7.1.2
```

-	Created: Wed, 09 Sep 2015 20:53:55 GMT
-	Parent Layer: `064a8786bf0a61ecaab4d1adb836a4f086b80c867b9b16a592cb28de744f8816`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `9b31409e47d79f324e4c0d1ef93af4cfe0ab538c3054a23f2e4c4ca0b72a01f4`

```dockerfile
RUN set -x \
	&& mkdir -p /usr/src/python \
	&& curl -SL "https://www.python.org/ftp/python/$PYTHON_VERSION/Python-$PYTHON_VERSION.tar.xz" -o python.tar.xz \
	&& curl -SL "https://www.python.org/ftp/python/$PYTHON_VERSION/Python-$PYTHON_VERSION.tar.xz.asc" -o python.tar.xz.asc \
	&& gpg --verify python.tar.xz.asc \
	&& tar -xJC /usr/src/python --strip-components=1 -f python.tar.xz \
	&& rm python.tar.xz* \
	&& cd /usr/src/python \
	&& ./configure --enable-shared --enable-unicode=ucs4 \
	&& make -j$(nproc) \
	&& make install \
	&& ldconfig \
	&& pip3 install --no-cache-dir --upgrade pip==$PYTHON_PIP_VERSION \
	&& find /usr/local \
		\( -type d -a -name test -o -name tests \) \
		-o \( -type f -a -name '*.pyc' -o -name '*.pyo' \) \
		-exec rm -rf '{}' + \
	&& rm -rf /usr/src/python
```

-	Created: Wed, 09 Sep 2015 20:56:24 GMT
-	Parent Layer: `6917da306757202609231915c206081f6adb4e38a3e8d9756c2120e7b75549f4`
-	Docker Version: 1.7.1
-	Virtual Size: 78.3 MB (78277878 bytes)
-	v2 Blob: `sha256:0817c8d4f7a6947ab0a48b0220cb154512ba9855e05588f56d32bf6ec813d136`
-	v2 Content-Length: 22.1 MB (22061444 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:55:04 GMT

#### `60042152b6d8dd1d26dd4155a975ebb3ca1d471df122d576dfb887f477cf5272`

```dockerfile
RUN cd /usr/local/bin \
	&& ln -s easy_install-3.4 easy_install \
	&& ln -s idle3 idle \
	&& ln -s pydoc3 pydoc \
	&& ln -s python3 python \
	&& ln -s python-config3 python-config
```

-	Created: Wed, 09 Sep 2015 20:56:25 GMT
-	Parent Layer: `9b31409e47d79f324e4c0d1ef93af4cfe0ab538c3054a23f2e4c4ca0b72a01f4`
-	Docker Version: 1.7.1
-	Virtual Size: 48.0 B
-	v2 Blob: `sha256:da37f35187ee66f742ec7e3ee6b049b2482461c23c0b9e888e854d8f672f9ef4`
-	v2 Content-Length: 269.0 B
-	v2 Last-Modified: Wed, 09 Sep 2015 21:54:44 GMT

#### `575cb3ad9b670cb1d58f17ce0c7ce7deed835887e1fdd1013002226348c88a6d`

```dockerfile
CMD ["python3"]
```

-	Created: Wed, 09 Sep 2015 20:56:26 GMT
-	Parent Layer: `60042152b6d8dd1d26dd4155a975ebb3ca1d471df122d576dfb887f477cf5272`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `11b608fa74ec21b9886a0e58797c634839caaf9a7696ab65238adc8f068514f2`

```dockerfile
RUN mkdir -p /usr/src/app
```

-	Created: Wed, 09 Sep 2015 20:57:42 GMT
-	Parent Layer: `575cb3ad9b670cb1d58f17ce0c7ce7deed835887e1fdd1013002226348c88a6d`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:18ae4899185461eb6c5db8738cb28266f494072bca49858810a00477052e77cf`
-	v2 Content-Length: 127.0 B
-	v2 Last-Modified: Wed, 09 Sep 2015 21:57:22 GMT

#### `ca8e82415f8f12859931853204100f11c785a51048e5005cc5b09a761287478b`

```dockerfile
WORKDIR /usr/src/app
```

-	Created: Wed, 09 Sep 2015 20:57:42 GMT
-	Parent Layer: `11b608fa74ec21b9886a0e58797c634839caaf9a7696ab65238adc8f068514f2`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `685adf5465a3ca892b763f7feb5dcf34d33737b59e66f965f5a6a5674d5acd96`

```dockerfile
ONBUILD COPY requirements.txt /usr/src/app/
```

-	Created: Wed, 09 Sep 2015 20:57:43 GMT
-	Parent Layer: `ca8e82415f8f12859931853204100f11c785a51048e5005cc5b09a761287478b`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `04e257c81100d981db8b4d28e90e58602e5f10e5fde156d7245b152961daa332`

```dockerfile
ONBUILD RUN pip install --no-cache-dir -r requirements.txt
```

-	Created: Wed, 09 Sep 2015 20:57:43 GMT
-	Parent Layer: `685adf5465a3ca892b763f7feb5dcf34d33737b59e66f965f5a6a5674d5acd96`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `9ffc70d823599c713dd72f494bf1e9b8c503706fedca54292910cd171f748929`

```dockerfile
ONBUILD COPY . /usr/src/app
```

-	Created: Wed, 09 Sep 2015 20:57:43 GMT
-	Parent Layer: `04e257c81100d981db8b4d28e90e58602e5f10e5fde156d7245b152961daa332`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

## `python:onbuild`

```console
$ docker pull library/python@sha256:2796c5fc8433a3b010e496036d91a90bd3f8d326e540e272c3cc4f745c144bb1
```

-	Total Virtual Size: 685.8 MB (685750767 bytes)
-	Total v2 Content-Length: 263.1 MB (263058206 bytes)

### Layers (18)

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
-	v2 Blob: `sha256:b3010ec3eb21ac3df74757a47832fb17395b76ad3a30794074cefd07541d3557`
-	v2 Content-Length: 18.5 MB (18538591 bytes)
-	v2 Last-Modified: Thu, 10 Sep 2015 23:36:30 GMT

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

#### `a7131b97316204530af26e42319aeda8ac44cd5ac2891e5dab45e16deb1e592d`

```dockerfile
RUN apt-get purge -y python.*
```

-	Created: Wed, 09 Sep 2015 20:20:46 GMT
-	Parent Layer: `16b189cc8ce688f9f1d8f1d837fa0891107450a06c795b1cba8f6c33a4454280`
-	Docker Version: 1.7.1
-	Virtual Size: 975.3 KB (975277 bytes)
-	v2 Blob: `sha256:20cdbe5b7a6f64396bcabde9b06c16a0b41e2c7fd39b28eff1ee3670a9f0516e`
-	v2 Content-Length: 220.4 KB (220377 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:29:17 GMT

#### `d7cbb60bc416f832c685b38578b77da5f3716cba15d4bcb45d850809a4c112eb`

```dockerfile
ENV LANG=C.UTF-8
```

-	Created: Wed, 09 Sep 2015 20:20:48 GMT
-	Parent Layer: `a7131b97316204530af26e42319aeda8ac44cd5ac2891e5dab45e16deb1e592d`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `d8ea027435229a8bdc09fa68db0043f1e2059ec889a3715c3e184553aee36da4`

```dockerfile
RUN gpg --keyserver ha.pool.sks-keyservers.net --recv-keys 97FC712E4C024BBEA48A61ED3A5CA953F73C700D
```

-	Created: Wed, 09 Sep 2015 20:53:54 GMT
-	Parent Layer: `d7cbb60bc416f832c685b38578b77da5f3716cba15d4bcb45d850809a4c112eb`
-	Docker Version: 1.7.1
-	Virtual Size: 12.6 KB (12606 bytes)
-	v2 Blob: `sha256:2fdbb7a55da29a948a258ac37edb8f60a95a8c9757555c009ac32bc5a50e4197`
-	v2 Content-Length: 6.7 KB (6737 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:55:10 GMT

#### `064a8786bf0a61ecaab4d1adb836a4f086b80c867b9b16a592cb28de744f8816`

```dockerfile
ENV PYTHON_VERSION=3.4.3
```

-	Created: Wed, 09 Sep 2015 20:53:55 GMT
-	Parent Layer: `d8ea027435229a8bdc09fa68db0043f1e2059ec889a3715c3e184553aee36da4`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `6917da306757202609231915c206081f6adb4e38a3e8d9756c2120e7b75549f4`

```dockerfile
ENV PYTHON_PIP_VERSION=7.1.2
```

-	Created: Wed, 09 Sep 2015 20:53:55 GMT
-	Parent Layer: `064a8786bf0a61ecaab4d1adb836a4f086b80c867b9b16a592cb28de744f8816`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `9b31409e47d79f324e4c0d1ef93af4cfe0ab538c3054a23f2e4c4ca0b72a01f4`

```dockerfile
RUN set -x \
	&& mkdir -p /usr/src/python \
	&& curl -SL "https://www.python.org/ftp/python/$PYTHON_VERSION/Python-$PYTHON_VERSION.tar.xz" -o python.tar.xz \
	&& curl -SL "https://www.python.org/ftp/python/$PYTHON_VERSION/Python-$PYTHON_VERSION.tar.xz.asc" -o python.tar.xz.asc \
	&& gpg --verify python.tar.xz.asc \
	&& tar -xJC /usr/src/python --strip-components=1 -f python.tar.xz \
	&& rm python.tar.xz* \
	&& cd /usr/src/python \
	&& ./configure --enable-shared --enable-unicode=ucs4 \
	&& make -j$(nproc) \
	&& make install \
	&& ldconfig \
	&& pip3 install --no-cache-dir --upgrade pip==$PYTHON_PIP_VERSION \
	&& find /usr/local \
		\( -type d -a -name test -o -name tests \) \
		-o \( -type f -a -name '*.pyc' -o -name '*.pyo' \) \
		-exec rm -rf '{}' + \
	&& rm -rf /usr/src/python
```

-	Created: Wed, 09 Sep 2015 20:56:24 GMT
-	Parent Layer: `6917da306757202609231915c206081f6adb4e38a3e8d9756c2120e7b75549f4`
-	Docker Version: 1.7.1
-	Virtual Size: 78.3 MB (78277878 bytes)
-	v2 Blob: `sha256:0817c8d4f7a6947ab0a48b0220cb154512ba9855e05588f56d32bf6ec813d136`
-	v2 Content-Length: 22.1 MB (22061444 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:55:04 GMT

#### `60042152b6d8dd1d26dd4155a975ebb3ca1d471df122d576dfb887f477cf5272`

```dockerfile
RUN cd /usr/local/bin \
	&& ln -s easy_install-3.4 easy_install \
	&& ln -s idle3 idle \
	&& ln -s pydoc3 pydoc \
	&& ln -s python3 python \
	&& ln -s python-config3 python-config
```

-	Created: Wed, 09 Sep 2015 20:56:25 GMT
-	Parent Layer: `9b31409e47d79f324e4c0d1ef93af4cfe0ab538c3054a23f2e4c4ca0b72a01f4`
-	Docker Version: 1.7.1
-	Virtual Size: 48.0 B
-	v2 Blob: `sha256:da37f35187ee66f742ec7e3ee6b049b2482461c23c0b9e888e854d8f672f9ef4`
-	v2 Content-Length: 269.0 B
-	v2 Last-Modified: Wed, 09 Sep 2015 21:54:44 GMT

#### `575cb3ad9b670cb1d58f17ce0c7ce7deed835887e1fdd1013002226348c88a6d`

```dockerfile
CMD ["python3"]
```

-	Created: Wed, 09 Sep 2015 20:56:26 GMT
-	Parent Layer: `60042152b6d8dd1d26dd4155a975ebb3ca1d471df122d576dfb887f477cf5272`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `11b608fa74ec21b9886a0e58797c634839caaf9a7696ab65238adc8f068514f2`

```dockerfile
RUN mkdir -p /usr/src/app
```

-	Created: Wed, 09 Sep 2015 20:57:42 GMT
-	Parent Layer: `575cb3ad9b670cb1d58f17ce0c7ce7deed835887e1fdd1013002226348c88a6d`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:18ae4899185461eb6c5db8738cb28266f494072bca49858810a00477052e77cf`
-	v2 Content-Length: 127.0 B
-	v2 Last-Modified: Wed, 09 Sep 2015 21:57:22 GMT

#### `ca8e82415f8f12859931853204100f11c785a51048e5005cc5b09a761287478b`

```dockerfile
WORKDIR /usr/src/app
```

-	Created: Wed, 09 Sep 2015 20:57:42 GMT
-	Parent Layer: `11b608fa74ec21b9886a0e58797c634839caaf9a7696ab65238adc8f068514f2`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `685adf5465a3ca892b763f7feb5dcf34d33737b59e66f965f5a6a5674d5acd96`

```dockerfile
ONBUILD COPY requirements.txt /usr/src/app/
```

-	Created: Wed, 09 Sep 2015 20:57:43 GMT
-	Parent Layer: `ca8e82415f8f12859931853204100f11c785a51048e5005cc5b09a761287478b`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `04e257c81100d981db8b4d28e90e58602e5f10e5fde156d7245b152961daa332`

```dockerfile
ONBUILD RUN pip install --no-cache-dir -r requirements.txt
```

-	Created: Wed, 09 Sep 2015 20:57:43 GMT
-	Parent Layer: `685adf5465a3ca892b763f7feb5dcf34d33737b59e66f965f5a6a5674d5acd96`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `9ffc70d823599c713dd72f494bf1e9b8c503706fedca54292910cd171f748929`

```dockerfile
ONBUILD COPY . /usr/src/app
```

-	Created: Wed, 09 Sep 2015 20:57:43 GMT
-	Parent Layer: `04e257c81100d981db8b4d28e90e58602e5f10e5fde156d7245b152961daa332`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

## `python:3.4.3-slim`

```console
$ docker pull library/python@sha256:31084b2919aff3499fd5e9885030774bea3f095f2dd160d0cdbf4e9320ce28f1
```

-	Total Virtual Size: 215.2 MB (215244857 bytes)
-	Total v2 Content-Length: 78.8 MB (78830166 bytes)

### Layers (11)

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

#### `b724829f2124ff81839118c0bb053554742dae49bcf23847b98264867e4da862`

```dockerfile
RUN apt-get purge -y python.*
```

-	Created: Wed, 09 Sep 2015 20:26:09 GMT
-	Parent Layer: `8c00acfb017549e44d28098762c3e6296872a1ca9b90385855f1019d84bb0dac`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `dad2fc2df4957c05b555a45d00adeaaf624ccce5d9dd557ce4c8548ca40f39f0`

```dockerfile
ENV LANG=C.UTF-8
```

-	Created: Wed, 09 Sep 2015 20:26:10 GMT
-	Parent Layer: `b724829f2124ff81839118c0bb053554742dae49bcf23847b98264867e4da862`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `b4b1929946879d72f7304c436913698e312741961589842913329eb8d746fefa`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		libsqlite3-0 \
		libssl1.0.0 \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Wed, 09 Sep 2015 20:26:51 GMT
-	Parent Layer: `dad2fc2df4957c05b555a45d00adeaaf624ccce5d9dd557ce4c8548ca40f39f0`
-	Docker Version: 1.7.1
-	Virtual Size: 7.4 MB (7441496 bytes)
-	v2 Blob: `sha256:aebbd0bd409f97875c3b3bcf8f57e315ba2ef8d3c4a54f81a7f71cfcf80bf4c9`
-	v2 Content-Length: 3.3 MB (3316296 bytes)
-	v2 Last-Modified: Fri, 11 Sep 2015 00:01:36 GMT

#### `c62feeae66a9b278cc147476ae5ee822b4595790c9b96733a6879ade412606b5`

```dockerfile
RUN gpg --keyserver ha.pool.sks-keyservers.net --recv-keys 97FC712E4C024BBEA48A61ED3A5CA953F73C700D
```

-	Created: Wed, 09 Sep 2015 20:58:44 GMT
-	Parent Layer: `b4b1929946879d72f7304c436913698e312741961589842913329eb8d746fefa`
-	Docker Version: 1.7.1
-	Virtual Size: 12.6 KB (12606 bytes)
-	v2 Blob: `sha256:5ed1876c3a86512cc94dd5c18bf7f6d27b5d69f05a21c0c675ef0c695cbf7135`
-	v2 Content-Length: 6.7 KB (6738 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 22:00:10 GMT

#### `29e2f588f2202922c20bd8bc8a430621aed0e27f3b44094498758b6b6f0a6187`

```dockerfile
ENV PYTHON_VERSION=3.4.3
```

-	Created: Wed, 09 Sep 2015 20:58:45 GMT
-	Parent Layer: `c62feeae66a9b278cc147476ae5ee822b4595790c9b96733a6879ade412606b5`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `7363318d8eeb31775e42fade4e8e8eef646e751c5862a264d07a5a81c8d0ede5`

```dockerfile
ENV PYTHON_PIP_VERSION=7.1.2
```

-	Created: Wed, 09 Sep 2015 20:58:45 GMT
-	Parent Layer: `29e2f588f2202922c20bd8bc8a430621aed0e27f3b44094498758b6b6f0a6187`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `2345ebe94950f90a1a19eb7443cb520527e76629dc5d7c872ac4943c9f30f1e8`

```dockerfile
RUN set -x \
	&& buildDeps=' \
		curl \
		gcc \
		libbz2-dev \
		libc6-dev \
		libncurses-dev \
		libreadline-dev \
		libsqlite3-dev \
		libssl-dev \
		make \
		xz-utils \
		zlib1g-dev \
	' \
	&& apt-get update && apt-get install -y $buildDeps --no-install-recommends && rm -rf /var/lib/apt/lists/* \
	&& mkdir -p /usr/src/python \
	&& curl -SL "https://www.python.org/ftp/python/$PYTHON_VERSION/Python-$PYTHON_VERSION.tar.xz" -o python.tar.xz \
	&& curl -SL "https://www.python.org/ftp/python/$PYTHON_VERSION/Python-$PYTHON_VERSION.tar.xz.asc" -o python.tar.xz.asc \
	&& gpg --verify python.tar.xz.asc \
	&& tar -xJC /usr/src/python --strip-components=1 -f python.tar.xz \
	&& rm python.tar.xz* \
	&& cd /usr/src/python \
	&& ./configure --enable-shared --enable-unicode=ucs4 \
	&& make -j$(nproc) \
	&& make install \
	&& ldconfig \
	&& pip3 install --no-cache-dir --upgrade pip==$PYTHON_PIP_VERSION \
	&& find /usr/local \
		\( -type d -a -name test -o -name tests \) \
		-o \( -type f -a -name '*.pyc' -o -name '*.pyo' \) \
		-exec rm -rf '{}' + \
	&& apt-get purge -y --auto-remove $buildDeps \
	&& rm -rf /usr/src/python
```

-	Created: Wed, 09 Sep 2015 21:02:11 GMT
-	Parent Layer: `7363318d8eeb31775e42fade4e8e8eef646e751c5862a264d07a5a81c8d0ede5`
-	Docker Version: 1.7.1
-	Virtual Size: 82.6 MB (82631576 bytes)
-	v2 Blob: `sha256:c85f401212142b7e1fb20bac7dade207e06d3852f00c0c45a8d03eb3c6da7dfd`
-	v2 Content-Length: 24.1 MB (24146963 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 22:00:02 GMT

#### `49e6ab8bdb0047f67c53136a05c565657081d6d5b56adca67723f5d54353bae2`

```dockerfile
RUN cd /usr/local/bin \
	&& ln -s easy_install-3.4 easy_install \
	&& ln -s idle3 idle \
	&& ln -s pydoc3 pydoc \
	&& ln -s python3 python \
	&& ln -s python-config3 python-config
```

-	Created: Wed, 09 Sep 2015 21:02:13 GMT
-	Parent Layer: `2345ebe94950f90a1a19eb7443cb520527e76629dc5d7c872ac4943c9f30f1e8`
-	Docker Version: 1.7.1
-	Virtual Size: 48.0 B
-	v2 Blob: `sha256:b741c7af3a85c1e24705e2d2449ad455d41199153fb3393abfe1db483368f4a3`
-	v2 Content-Length: 269.0 B
-	v2 Last-Modified: Wed, 09 Sep 2015 21:59:39 GMT

#### `5294b6c8936fc64c37ef43a7c4d0a7ad3077c949639a73a9c020aa4ee2305f9e`

```dockerfile
CMD ["python3"]
```

-	Created: Wed, 09 Sep 2015 21:02:13 GMT
-	Parent Layer: `49e6ab8bdb0047f67c53136a05c565657081d6d5b56adca67723f5d54353bae2`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

## `python:3.4-slim`

```console
$ docker pull library/python@sha256:eb80d4f57264563b4be95950dd082ac55096fe14db36fa8c1d0053184587cfb9
```

-	Total Virtual Size: 215.2 MB (215244857 bytes)
-	Total v2 Content-Length: 78.8 MB (78830166 bytes)

### Layers (11)

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

#### `b724829f2124ff81839118c0bb053554742dae49bcf23847b98264867e4da862`

```dockerfile
RUN apt-get purge -y python.*
```

-	Created: Wed, 09 Sep 2015 20:26:09 GMT
-	Parent Layer: `8c00acfb017549e44d28098762c3e6296872a1ca9b90385855f1019d84bb0dac`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `dad2fc2df4957c05b555a45d00adeaaf624ccce5d9dd557ce4c8548ca40f39f0`

```dockerfile
ENV LANG=C.UTF-8
```

-	Created: Wed, 09 Sep 2015 20:26:10 GMT
-	Parent Layer: `b724829f2124ff81839118c0bb053554742dae49bcf23847b98264867e4da862`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `b4b1929946879d72f7304c436913698e312741961589842913329eb8d746fefa`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		libsqlite3-0 \
		libssl1.0.0 \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Wed, 09 Sep 2015 20:26:51 GMT
-	Parent Layer: `dad2fc2df4957c05b555a45d00adeaaf624ccce5d9dd557ce4c8548ca40f39f0`
-	Docker Version: 1.7.1
-	Virtual Size: 7.4 MB (7441496 bytes)
-	v2 Blob: `sha256:aebbd0bd409f97875c3b3bcf8f57e315ba2ef8d3c4a54f81a7f71cfcf80bf4c9`
-	v2 Content-Length: 3.3 MB (3316296 bytes)
-	v2 Last-Modified: Fri, 11 Sep 2015 00:01:36 GMT

#### `c62feeae66a9b278cc147476ae5ee822b4595790c9b96733a6879ade412606b5`

```dockerfile
RUN gpg --keyserver ha.pool.sks-keyservers.net --recv-keys 97FC712E4C024BBEA48A61ED3A5CA953F73C700D
```

-	Created: Wed, 09 Sep 2015 20:58:44 GMT
-	Parent Layer: `b4b1929946879d72f7304c436913698e312741961589842913329eb8d746fefa`
-	Docker Version: 1.7.1
-	Virtual Size: 12.6 KB (12606 bytes)
-	v2 Blob: `sha256:5ed1876c3a86512cc94dd5c18bf7f6d27b5d69f05a21c0c675ef0c695cbf7135`
-	v2 Content-Length: 6.7 KB (6738 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 22:00:10 GMT

#### `29e2f588f2202922c20bd8bc8a430621aed0e27f3b44094498758b6b6f0a6187`

```dockerfile
ENV PYTHON_VERSION=3.4.3
```

-	Created: Wed, 09 Sep 2015 20:58:45 GMT
-	Parent Layer: `c62feeae66a9b278cc147476ae5ee822b4595790c9b96733a6879ade412606b5`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `7363318d8eeb31775e42fade4e8e8eef646e751c5862a264d07a5a81c8d0ede5`

```dockerfile
ENV PYTHON_PIP_VERSION=7.1.2
```

-	Created: Wed, 09 Sep 2015 20:58:45 GMT
-	Parent Layer: `29e2f588f2202922c20bd8bc8a430621aed0e27f3b44094498758b6b6f0a6187`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `2345ebe94950f90a1a19eb7443cb520527e76629dc5d7c872ac4943c9f30f1e8`

```dockerfile
RUN set -x \
	&& buildDeps=' \
		curl \
		gcc \
		libbz2-dev \
		libc6-dev \
		libncurses-dev \
		libreadline-dev \
		libsqlite3-dev \
		libssl-dev \
		make \
		xz-utils \
		zlib1g-dev \
	' \
	&& apt-get update && apt-get install -y $buildDeps --no-install-recommends && rm -rf /var/lib/apt/lists/* \
	&& mkdir -p /usr/src/python \
	&& curl -SL "https://www.python.org/ftp/python/$PYTHON_VERSION/Python-$PYTHON_VERSION.tar.xz" -o python.tar.xz \
	&& curl -SL "https://www.python.org/ftp/python/$PYTHON_VERSION/Python-$PYTHON_VERSION.tar.xz.asc" -o python.tar.xz.asc \
	&& gpg --verify python.tar.xz.asc \
	&& tar -xJC /usr/src/python --strip-components=1 -f python.tar.xz \
	&& rm python.tar.xz* \
	&& cd /usr/src/python \
	&& ./configure --enable-shared --enable-unicode=ucs4 \
	&& make -j$(nproc) \
	&& make install \
	&& ldconfig \
	&& pip3 install --no-cache-dir --upgrade pip==$PYTHON_PIP_VERSION \
	&& find /usr/local \
		\( -type d -a -name test -o -name tests \) \
		-o \( -type f -a -name '*.pyc' -o -name '*.pyo' \) \
		-exec rm -rf '{}' + \
	&& apt-get purge -y --auto-remove $buildDeps \
	&& rm -rf /usr/src/python
```

-	Created: Wed, 09 Sep 2015 21:02:11 GMT
-	Parent Layer: `7363318d8eeb31775e42fade4e8e8eef646e751c5862a264d07a5a81c8d0ede5`
-	Docker Version: 1.7.1
-	Virtual Size: 82.6 MB (82631576 bytes)
-	v2 Blob: `sha256:c85f401212142b7e1fb20bac7dade207e06d3852f00c0c45a8d03eb3c6da7dfd`
-	v2 Content-Length: 24.1 MB (24146963 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 22:00:02 GMT

#### `49e6ab8bdb0047f67c53136a05c565657081d6d5b56adca67723f5d54353bae2`

```dockerfile
RUN cd /usr/local/bin \
	&& ln -s easy_install-3.4 easy_install \
	&& ln -s idle3 idle \
	&& ln -s pydoc3 pydoc \
	&& ln -s python3 python \
	&& ln -s python-config3 python-config
```

-	Created: Wed, 09 Sep 2015 21:02:13 GMT
-	Parent Layer: `2345ebe94950f90a1a19eb7443cb520527e76629dc5d7c872ac4943c9f30f1e8`
-	Docker Version: 1.7.1
-	Virtual Size: 48.0 B
-	v2 Blob: `sha256:b741c7af3a85c1e24705e2d2449ad455d41199153fb3393abfe1db483368f4a3`
-	v2 Content-Length: 269.0 B
-	v2 Last-Modified: Wed, 09 Sep 2015 21:59:39 GMT

#### `5294b6c8936fc64c37ef43a7c4d0a7ad3077c949639a73a9c020aa4ee2305f9e`

```dockerfile
CMD ["python3"]
```

-	Created: Wed, 09 Sep 2015 21:02:13 GMT
-	Parent Layer: `49e6ab8bdb0047f67c53136a05c565657081d6d5b56adca67723f5d54353bae2`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

## `python:3-slim`

```console
$ docker pull library/python@sha256:1297fd6f39d8a75b9fec5b59505dc07e6138b766e4a48fb5b20290d44f251277
```

-	Total Virtual Size: 215.2 MB (215244857 bytes)
-	Total v2 Content-Length: 78.8 MB (78830166 bytes)

### Layers (11)

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

#### `b724829f2124ff81839118c0bb053554742dae49bcf23847b98264867e4da862`

```dockerfile
RUN apt-get purge -y python.*
```

-	Created: Wed, 09 Sep 2015 20:26:09 GMT
-	Parent Layer: `8c00acfb017549e44d28098762c3e6296872a1ca9b90385855f1019d84bb0dac`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `dad2fc2df4957c05b555a45d00adeaaf624ccce5d9dd557ce4c8548ca40f39f0`

```dockerfile
ENV LANG=C.UTF-8
```

-	Created: Wed, 09 Sep 2015 20:26:10 GMT
-	Parent Layer: `b724829f2124ff81839118c0bb053554742dae49bcf23847b98264867e4da862`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `b4b1929946879d72f7304c436913698e312741961589842913329eb8d746fefa`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		libsqlite3-0 \
		libssl1.0.0 \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Wed, 09 Sep 2015 20:26:51 GMT
-	Parent Layer: `dad2fc2df4957c05b555a45d00adeaaf624ccce5d9dd557ce4c8548ca40f39f0`
-	Docker Version: 1.7.1
-	Virtual Size: 7.4 MB (7441496 bytes)
-	v2 Blob: `sha256:aebbd0bd409f97875c3b3bcf8f57e315ba2ef8d3c4a54f81a7f71cfcf80bf4c9`
-	v2 Content-Length: 3.3 MB (3316296 bytes)
-	v2 Last-Modified: Fri, 11 Sep 2015 00:01:36 GMT

#### `c62feeae66a9b278cc147476ae5ee822b4595790c9b96733a6879ade412606b5`

```dockerfile
RUN gpg --keyserver ha.pool.sks-keyservers.net --recv-keys 97FC712E4C024BBEA48A61ED3A5CA953F73C700D
```

-	Created: Wed, 09 Sep 2015 20:58:44 GMT
-	Parent Layer: `b4b1929946879d72f7304c436913698e312741961589842913329eb8d746fefa`
-	Docker Version: 1.7.1
-	Virtual Size: 12.6 KB (12606 bytes)
-	v2 Blob: `sha256:5ed1876c3a86512cc94dd5c18bf7f6d27b5d69f05a21c0c675ef0c695cbf7135`
-	v2 Content-Length: 6.7 KB (6738 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 22:00:10 GMT

#### `29e2f588f2202922c20bd8bc8a430621aed0e27f3b44094498758b6b6f0a6187`

```dockerfile
ENV PYTHON_VERSION=3.4.3
```

-	Created: Wed, 09 Sep 2015 20:58:45 GMT
-	Parent Layer: `c62feeae66a9b278cc147476ae5ee822b4595790c9b96733a6879ade412606b5`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `7363318d8eeb31775e42fade4e8e8eef646e751c5862a264d07a5a81c8d0ede5`

```dockerfile
ENV PYTHON_PIP_VERSION=7.1.2
```

-	Created: Wed, 09 Sep 2015 20:58:45 GMT
-	Parent Layer: `29e2f588f2202922c20bd8bc8a430621aed0e27f3b44094498758b6b6f0a6187`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `2345ebe94950f90a1a19eb7443cb520527e76629dc5d7c872ac4943c9f30f1e8`

```dockerfile
RUN set -x \
	&& buildDeps=' \
		curl \
		gcc \
		libbz2-dev \
		libc6-dev \
		libncurses-dev \
		libreadline-dev \
		libsqlite3-dev \
		libssl-dev \
		make \
		xz-utils \
		zlib1g-dev \
	' \
	&& apt-get update && apt-get install -y $buildDeps --no-install-recommends && rm -rf /var/lib/apt/lists/* \
	&& mkdir -p /usr/src/python \
	&& curl -SL "https://www.python.org/ftp/python/$PYTHON_VERSION/Python-$PYTHON_VERSION.tar.xz" -o python.tar.xz \
	&& curl -SL "https://www.python.org/ftp/python/$PYTHON_VERSION/Python-$PYTHON_VERSION.tar.xz.asc" -o python.tar.xz.asc \
	&& gpg --verify python.tar.xz.asc \
	&& tar -xJC /usr/src/python --strip-components=1 -f python.tar.xz \
	&& rm python.tar.xz* \
	&& cd /usr/src/python \
	&& ./configure --enable-shared --enable-unicode=ucs4 \
	&& make -j$(nproc) \
	&& make install \
	&& ldconfig \
	&& pip3 install --no-cache-dir --upgrade pip==$PYTHON_PIP_VERSION \
	&& find /usr/local \
		\( -type d -a -name test -o -name tests \) \
		-o \( -type f -a -name '*.pyc' -o -name '*.pyo' \) \
		-exec rm -rf '{}' + \
	&& apt-get purge -y --auto-remove $buildDeps \
	&& rm -rf /usr/src/python
```

-	Created: Wed, 09 Sep 2015 21:02:11 GMT
-	Parent Layer: `7363318d8eeb31775e42fade4e8e8eef646e751c5862a264d07a5a81c8d0ede5`
-	Docker Version: 1.7.1
-	Virtual Size: 82.6 MB (82631576 bytes)
-	v2 Blob: `sha256:c85f401212142b7e1fb20bac7dade207e06d3852f00c0c45a8d03eb3c6da7dfd`
-	v2 Content-Length: 24.1 MB (24146963 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 22:00:02 GMT

#### `49e6ab8bdb0047f67c53136a05c565657081d6d5b56adca67723f5d54353bae2`

```dockerfile
RUN cd /usr/local/bin \
	&& ln -s easy_install-3.4 easy_install \
	&& ln -s idle3 idle \
	&& ln -s pydoc3 pydoc \
	&& ln -s python3 python \
	&& ln -s python-config3 python-config
```

-	Created: Wed, 09 Sep 2015 21:02:13 GMT
-	Parent Layer: `2345ebe94950f90a1a19eb7443cb520527e76629dc5d7c872ac4943c9f30f1e8`
-	Docker Version: 1.7.1
-	Virtual Size: 48.0 B
-	v2 Blob: `sha256:b741c7af3a85c1e24705e2d2449ad455d41199153fb3393abfe1db483368f4a3`
-	v2 Content-Length: 269.0 B
-	v2 Last-Modified: Wed, 09 Sep 2015 21:59:39 GMT

#### `5294b6c8936fc64c37ef43a7c4d0a7ad3077c949639a73a9c020aa4ee2305f9e`

```dockerfile
CMD ["python3"]
```

-	Created: Wed, 09 Sep 2015 21:02:13 GMT
-	Parent Layer: `49e6ab8bdb0047f67c53136a05c565657081d6d5b56adca67723f5d54353bae2`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

## `python:slim`

```console
$ docker pull library/python@sha256:6d613a3658ee62bb84bc282e52dc6e12aa4327c5492c6af358f5816584a20fde
```

-	Total Virtual Size: 215.2 MB (215244857 bytes)
-	Total v2 Content-Length: 78.8 MB (78830166 bytes)

### Layers (11)

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

#### `b724829f2124ff81839118c0bb053554742dae49bcf23847b98264867e4da862`

```dockerfile
RUN apt-get purge -y python.*
```

-	Created: Wed, 09 Sep 2015 20:26:09 GMT
-	Parent Layer: `8c00acfb017549e44d28098762c3e6296872a1ca9b90385855f1019d84bb0dac`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `dad2fc2df4957c05b555a45d00adeaaf624ccce5d9dd557ce4c8548ca40f39f0`

```dockerfile
ENV LANG=C.UTF-8
```

-	Created: Wed, 09 Sep 2015 20:26:10 GMT
-	Parent Layer: `b724829f2124ff81839118c0bb053554742dae49bcf23847b98264867e4da862`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `b4b1929946879d72f7304c436913698e312741961589842913329eb8d746fefa`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		libsqlite3-0 \
		libssl1.0.0 \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Wed, 09 Sep 2015 20:26:51 GMT
-	Parent Layer: `dad2fc2df4957c05b555a45d00adeaaf624ccce5d9dd557ce4c8548ca40f39f0`
-	Docker Version: 1.7.1
-	Virtual Size: 7.4 MB (7441496 bytes)
-	v2 Blob: `sha256:aebbd0bd409f97875c3b3bcf8f57e315ba2ef8d3c4a54f81a7f71cfcf80bf4c9`
-	v2 Content-Length: 3.3 MB (3316296 bytes)
-	v2 Last-Modified: Fri, 11 Sep 2015 00:01:36 GMT

#### `c62feeae66a9b278cc147476ae5ee822b4595790c9b96733a6879ade412606b5`

```dockerfile
RUN gpg --keyserver ha.pool.sks-keyservers.net --recv-keys 97FC712E4C024BBEA48A61ED3A5CA953F73C700D
```

-	Created: Wed, 09 Sep 2015 20:58:44 GMT
-	Parent Layer: `b4b1929946879d72f7304c436913698e312741961589842913329eb8d746fefa`
-	Docker Version: 1.7.1
-	Virtual Size: 12.6 KB (12606 bytes)
-	v2 Blob: `sha256:5ed1876c3a86512cc94dd5c18bf7f6d27b5d69f05a21c0c675ef0c695cbf7135`
-	v2 Content-Length: 6.7 KB (6738 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 22:00:10 GMT

#### `29e2f588f2202922c20bd8bc8a430621aed0e27f3b44094498758b6b6f0a6187`

```dockerfile
ENV PYTHON_VERSION=3.4.3
```

-	Created: Wed, 09 Sep 2015 20:58:45 GMT
-	Parent Layer: `c62feeae66a9b278cc147476ae5ee822b4595790c9b96733a6879ade412606b5`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `7363318d8eeb31775e42fade4e8e8eef646e751c5862a264d07a5a81c8d0ede5`

```dockerfile
ENV PYTHON_PIP_VERSION=7.1.2
```

-	Created: Wed, 09 Sep 2015 20:58:45 GMT
-	Parent Layer: `29e2f588f2202922c20bd8bc8a430621aed0e27f3b44094498758b6b6f0a6187`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `2345ebe94950f90a1a19eb7443cb520527e76629dc5d7c872ac4943c9f30f1e8`

```dockerfile
RUN set -x \
	&& buildDeps=' \
		curl \
		gcc \
		libbz2-dev \
		libc6-dev \
		libncurses-dev \
		libreadline-dev \
		libsqlite3-dev \
		libssl-dev \
		make \
		xz-utils \
		zlib1g-dev \
	' \
	&& apt-get update && apt-get install -y $buildDeps --no-install-recommends && rm -rf /var/lib/apt/lists/* \
	&& mkdir -p /usr/src/python \
	&& curl -SL "https://www.python.org/ftp/python/$PYTHON_VERSION/Python-$PYTHON_VERSION.tar.xz" -o python.tar.xz \
	&& curl -SL "https://www.python.org/ftp/python/$PYTHON_VERSION/Python-$PYTHON_VERSION.tar.xz.asc" -o python.tar.xz.asc \
	&& gpg --verify python.tar.xz.asc \
	&& tar -xJC /usr/src/python --strip-components=1 -f python.tar.xz \
	&& rm python.tar.xz* \
	&& cd /usr/src/python \
	&& ./configure --enable-shared --enable-unicode=ucs4 \
	&& make -j$(nproc) \
	&& make install \
	&& ldconfig \
	&& pip3 install --no-cache-dir --upgrade pip==$PYTHON_PIP_VERSION \
	&& find /usr/local \
		\( -type d -a -name test -o -name tests \) \
		-o \( -type f -a -name '*.pyc' -o -name '*.pyo' \) \
		-exec rm -rf '{}' + \
	&& apt-get purge -y --auto-remove $buildDeps \
	&& rm -rf /usr/src/python
```

-	Created: Wed, 09 Sep 2015 21:02:11 GMT
-	Parent Layer: `7363318d8eeb31775e42fade4e8e8eef646e751c5862a264d07a5a81c8d0ede5`
-	Docker Version: 1.7.1
-	Virtual Size: 82.6 MB (82631576 bytes)
-	v2 Blob: `sha256:c85f401212142b7e1fb20bac7dade207e06d3852f00c0c45a8d03eb3c6da7dfd`
-	v2 Content-Length: 24.1 MB (24146963 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 22:00:02 GMT

#### `49e6ab8bdb0047f67c53136a05c565657081d6d5b56adca67723f5d54353bae2`

```dockerfile
RUN cd /usr/local/bin \
	&& ln -s easy_install-3.4 easy_install \
	&& ln -s idle3 idle \
	&& ln -s pydoc3 pydoc \
	&& ln -s python3 python \
	&& ln -s python-config3 python-config
```

-	Created: Wed, 09 Sep 2015 21:02:13 GMT
-	Parent Layer: `2345ebe94950f90a1a19eb7443cb520527e76629dc5d7c872ac4943c9f30f1e8`
-	Docker Version: 1.7.1
-	Virtual Size: 48.0 B
-	v2 Blob: `sha256:b741c7af3a85c1e24705e2d2449ad455d41199153fb3393abfe1db483368f4a3`
-	v2 Content-Length: 269.0 B
-	v2 Last-Modified: Wed, 09 Sep 2015 21:59:39 GMT

#### `5294b6c8936fc64c37ef43a7c4d0a7ad3077c949639a73a9c020aa4ee2305f9e`

```dockerfile
CMD ["python3"]
```

-	Created: Wed, 09 Sep 2015 21:02:13 GMT
-	Parent Layer: `49e6ab8bdb0047f67c53136a05c565657081d6d5b56adca67723f5d54353bae2`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

## `python:3.4.3-wheezy`

```console
$ docker pull library/python@sha256:717df101619386f0a023a11856592f74591c82f4a1c77b3e39150a9bc86188d7
```

-	Total Virtual Size: 537.3 MB (537270261 bytes)
-	Total v2 Content-Length: 197.5 MB (197468584 bytes)

### Layers (13)

#### `ba249489d0b6512128b60a4910e78fa2000c785d59e0599188a6802bd01155f2`

```dockerfile
ADD file:b908886c97e2b96665b7afc54ff53ebaef1c62896cf83a1199e59fceff1dafb5 in /
```

-	Created: Mon, 07 Sep 2015 23:37:10 GMT
-	Docker Version: 1.7.1
-	Virtual Size: 84.9 MB (84924773 bytes)
-	v2 Blob: `sha256:8f47f7c36e4382b4569bfe8858c0b371313e9c47a72867d69b000949c53637c9`
-	v2 Content-Length: 37.2 MB (37191761 bytes)
-	v2 Last-Modified: Mon, 07 Sep 2015 23:46:29 GMT

#### `19de96c112fcca5b6de16611dc0a359b0b977c551921ca79ac5cf4a8bfff9351`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Mon, 07 Sep 2015 23:37:11 GMT
-	Parent Layer: `ba249489d0b6512128b60a4910e78fa2000c785d59e0599188a6802bd01155f2`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `e83e5b7f7d01ffa47e46b7234799f12d842089df890db8fae765c5a4df26a20b`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 08 Sep 2015 15:38:48 GMT
-	Parent Layer: `19de96c112fcca5b6de16611dc0a359b0b977c551921ca79ac5cf4a8bfff9351`
-	Docker Version: 1.7.1
-	Virtual Size: 14.2 MB (14239819 bytes)
-	v2 Blob: `sha256:7a11528d019acc2b739bd4c1a7e518e247f729fdad40490be9d9fdb13e85c8c8`
-	v2 Content-Length: 6.7 MB (6739553 bytes)
-	v2 Last-Modified: Thu, 10 Sep 2015 23:43:23 GMT

#### `d6b70cefe2bfb76216c96acb6a6c6350eedff489df914b2606b1005e70f73a00`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 08 Sep 2015 15:39:23 GMT
-	Parent Layer: `e83e5b7f7d01ffa47e46b7234799f12d842089df890db8fae765c5a4df26a20b`
-	Docker Version: 1.7.1
-	Virtual Size: 109.4 MB (109431259 bytes)
-	v2 Blob: `sha256:4224b2b7563f71616cbe9215abf5276c51b18d3ceead85a56526519b5391a75f`
-	v2 Content-Length: 37.0 MB (37046780 bytes)
-	v2 Last-Modified: Tue, 08 Sep 2015 16:02:41 GMT

#### `3a5282506aa21c7b21cfdad32a099497bf9839dbc5e427f79bdad6a5e109f3d3`

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

-	Created: Tue, 08 Sep 2015 15:41:19 GMT
-	Parent Layer: `d6b70cefe2bfb76216c96acb6a6c6350eedff489df914b2606b1005e70f73a00`
-	Docker Version: 1.7.1
-	Virtual Size: 250.6 MB (250569275 bytes)
-	v2 Blob: `sha256:89989badb2c249165ed907bdf03e38dffbaefd3c115ad32ac6cf53ebbafab33b`
-	v2 Content-Length: 94.3 MB (94261782 bytes)
-	v2 Last-Modified: Tue, 08 Sep 2015 16:03:53 GMT

#### `1046da491d81f106d762e20009d4dfff16da8b2af4eafc70cba44ca74f7dc53e`

```dockerfile
RUN apt-get purge -y python.*
```

-	Created: Wed, 09 Sep 2015 20:31:23 GMT
-	Parent Layer: `3a5282506aa21c7b21cfdad32a099497bf9839dbc5e427f79bdad6a5e109f3d3`
-	Docker Version: 1.7.1
-	Virtual Size: 833.7 KB (833724 bytes)
-	v2 Blob: `sha256:9bab6257d36f85970d8effd469dcd7c7a44ab5de929035933d165b6a35929905`
-	v2 Content-Length: 196.8 KB (196778 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:39:13 GMT

#### `498b8d9d85457c4a520c8678c4ce95829605287dfb5ca8f39586b76666d446ab`

```dockerfile
ENV LANG=C.UTF-8
```

-	Created: Wed, 09 Sep 2015 20:31:23 GMT
-	Parent Layer: `1046da491d81f106d762e20009d4dfff16da8b2af4eafc70cba44ca74f7dc53e`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `a29a9085667cc4e5e918115028e8ec2fcb15d7b4b10347aa2aeb8c344c8c626b`

```dockerfile
RUN gpg --keyserver ha.pool.sks-keyservers.net --recv-keys 97FC712E4C024BBEA48A61ED3A5CA953F73C700D
```

-	Created: Wed, 09 Sep 2015 21:04:22 GMT
-	Parent Layer: `498b8d9d85457c4a520c8678c4ce95829605287dfb5ca8f39586b76666d446ab`
-	Docker Version: 1.7.1
-	Virtual Size: 12.6 KB (12606 bytes)
-	v2 Blob: `sha256:46888fdbf9cc8d120b2ef8b90f7e6485384a4616e7c0e89a9675c41dc3473d7b`
-	v2 Content-Length: 6.7 KB (6737 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 22:03:31 GMT

#### `21647b83a090c12e2857e3d4c0232f2847c4f6e6a4c29d985865ee39a63b282e`

```dockerfile
ENV PYTHON_VERSION=3.4.3
```

-	Created: Wed, 09 Sep 2015 21:04:23 GMT
-	Parent Layer: `a29a9085667cc4e5e918115028e8ec2fcb15d7b4b10347aa2aeb8c344c8c626b`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `a9c792a21255ed5e500f3312a580bad3c905e99abfb1255b9673e461ac07569c`

```dockerfile
ENV PYTHON_PIP_VERSION=7.1.2
```

-	Created: Wed, 09 Sep 2015 21:04:23 GMT
-	Parent Layer: `21647b83a090c12e2857e3d4c0232f2847c4f6e6a4c29d985865ee39a63b282e`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `6715a9546df609218d0f13117aecb1b0258bd3898a8c4f7c68db71b8004399f1`

```dockerfile
RUN set -x \
	&& mkdir -p /usr/src/python \
	&& curl -SL "https://www.python.org/ftp/python/$PYTHON_VERSION/Python-$PYTHON_VERSION.tar.xz" -o python.tar.xz \
	&& curl -SL "https://www.python.org/ftp/python/$PYTHON_VERSION/Python-$PYTHON_VERSION.tar.xz.asc" -o python.tar.xz.asc \
	&& gpg --verify python.tar.xz.asc \
	&& tar -xJC /usr/src/python --strip-components=1 -f python.tar.xz \
	&& rm python.tar.xz* \
	&& cd /usr/src/python \
	&& ./configure --enable-shared --enable-unicode=ucs4 \
	&& make -j$(nproc) \
	&& make install \
	&& ldconfig \
	&& pip3 install --no-cache-dir --upgrade pip==$PYTHON_PIP_VERSION \
	&& find /usr/local \
		\( -type d -a -name test -o -name tests \) \
		-o \( -type f -a -name '*.pyc' -o -name '*.pyo' \) \
		-exec rm -rf '{}' + \
	&& rm -rf /usr/src/python
```

-	Created: Wed, 09 Sep 2015 21:07:05 GMT
-	Parent Layer: `a9c792a21255ed5e500f3312a580bad3c905e99abfb1255b9673e461ac07569c`
-	Docker Version: 1.7.1
-	Virtual Size: 77.3 MB (77258757 bytes)
-	v2 Blob: `sha256:17914ea1c1e60ce16c0de057810986990e8367e1c807709fa21a1bd356a8a516`
-	v2 Content-Length: 22.0 MB (22024763 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 22:03:08 GMT

#### `5af1e19f1a69d8e1f25d69996348cba1b90fcc4ac3ef1cd65d057618f2a53dca`

```dockerfile
RUN cd /usr/local/bin \
	&& ln -s easy_install-3.4 easy_install \
	&& ln -s idle3 idle \
	&& ln -s pydoc3 pydoc \
	&& ln -s python3 python \
	&& ln -s python-config3 python-config
```

-	Created: Wed, 09 Sep 2015 21:07:08 GMT
-	Parent Layer: `6715a9546df609218d0f13117aecb1b0258bd3898a8c4f7c68db71b8004399f1`
-	Docker Version: 1.7.1
-	Virtual Size: 48.0 B
-	v2 Blob: `sha256:e6ddad08c853495a5684ec4c0f4bf60dcbe18ffceae9e08f84a6e4b7410c4f0a`
-	v2 Content-Length: 270.0 B
-	v2 Last-Modified: Wed, 09 Sep 2015 22:02:47 GMT

#### `f6e6ebe683b00495ba71ccdcfd5a90ab4d4cd00c4379a6bd63e39ce2fd707703`

```dockerfile
CMD ["python3"]
```

-	Created: Wed, 09 Sep 2015 21:07:09 GMT
-	Parent Layer: `5af1e19f1a69d8e1f25d69996348cba1b90fcc4ac3ef1cd65d057618f2a53dca`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

## `python:3.4-wheezy`

```console
$ docker pull library/python@sha256:061157964fe102c49c7db118b1d69cb15e3f1a69ffdbb404a6b2f2d222f5ada8
```

-	Total Virtual Size: 537.3 MB (537270261 bytes)
-	Total v2 Content-Length: 197.5 MB (197468584 bytes)

### Layers (13)

#### `ba249489d0b6512128b60a4910e78fa2000c785d59e0599188a6802bd01155f2`

```dockerfile
ADD file:b908886c97e2b96665b7afc54ff53ebaef1c62896cf83a1199e59fceff1dafb5 in /
```

-	Created: Mon, 07 Sep 2015 23:37:10 GMT
-	Docker Version: 1.7.1
-	Virtual Size: 84.9 MB (84924773 bytes)
-	v2 Blob: `sha256:8f47f7c36e4382b4569bfe8858c0b371313e9c47a72867d69b000949c53637c9`
-	v2 Content-Length: 37.2 MB (37191761 bytes)
-	v2 Last-Modified: Mon, 07 Sep 2015 23:46:29 GMT

#### `19de96c112fcca5b6de16611dc0a359b0b977c551921ca79ac5cf4a8bfff9351`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Mon, 07 Sep 2015 23:37:11 GMT
-	Parent Layer: `ba249489d0b6512128b60a4910e78fa2000c785d59e0599188a6802bd01155f2`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `e83e5b7f7d01ffa47e46b7234799f12d842089df890db8fae765c5a4df26a20b`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 08 Sep 2015 15:38:48 GMT
-	Parent Layer: `19de96c112fcca5b6de16611dc0a359b0b977c551921ca79ac5cf4a8bfff9351`
-	Docker Version: 1.7.1
-	Virtual Size: 14.2 MB (14239819 bytes)
-	v2 Blob: `sha256:7a11528d019acc2b739bd4c1a7e518e247f729fdad40490be9d9fdb13e85c8c8`
-	v2 Content-Length: 6.7 MB (6739553 bytes)
-	v2 Last-Modified: Thu, 10 Sep 2015 23:43:23 GMT

#### `d6b70cefe2bfb76216c96acb6a6c6350eedff489df914b2606b1005e70f73a00`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 08 Sep 2015 15:39:23 GMT
-	Parent Layer: `e83e5b7f7d01ffa47e46b7234799f12d842089df890db8fae765c5a4df26a20b`
-	Docker Version: 1.7.1
-	Virtual Size: 109.4 MB (109431259 bytes)
-	v2 Blob: `sha256:4224b2b7563f71616cbe9215abf5276c51b18d3ceead85a56526519b5391a75f`
-	v2 Content-Length: 37.0 MB (37046780 bytes)
-	v2 Last-Modified: Tue, 08 Sep 2015 16:02:41 GMT

#### `3a5282506aa21c7b21cfdad32a099497bf9839dbc5e427f79bdad6a5e109f3d3`

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

-	Created: Tue, 08 Sep 2015 15:41:19 GMT
-	Parent Layer: `d6b70cefe2bfb76216c96acb6a6c6350eedff489df914b2606b1005e70f73a00`
-	Docker Version: 1.7.1
-	Virtual Size: 250.6 MB (250569275 bytes)
-	v2 Blob: `sha256:89989badb2c249165ed907bdf03e38dffbaefd3c115ad32ac6cf53ebbafab33b`
-	v2 Content-Length: 94.3 MB (94261782 bytes)
-	v2 Last-Modified: Tue, 08 Sep 2015 16:03:53 GMT

#### `1046da491d81f106d762e20009d4dfff16da8b2af4eafc70cba44ca74f7dc53e`

```dockerfile
RUN apt-get purge -y python.*
```

-	Created: Wed, 09 Sep 2015 20:31:23 GMT
-	Parent Layer: `3a5282506aa21c7b21cfdad32a099497bf9839dbc5e427f79bdad6a5e109f3d3`
-	Docker Version: 1.7.1
-	Virtual Size: 833.7 KB (833724 bytes)
-	v2 Blob: `sha256:9bab6257d36f85970d8effd469dcd7c7a44ab5de929035933d165b6a35929905`
-	v2 Content-Length: 196.8 KB (196778 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:39:13 GMT

#### `498b8d9d85457c4a520c8678c4ce95829605287dfb5ca8f39586b76666d446ab`

```dockerfile
ENV LANG=C.UTF-8
```

-	Created: Wed, 09 Sep 2015 20:31:23 GMT
-	Parent Layer: `1046da491d81f106d762e20009d4dfff16da8b2af4eafc70cba44ca74f7dc53e`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `a29a9085667cc4e5e918115028e8ec2fcb15d7b4b10347aa2aeb8c344c8c626b`

```dockerfile
RUN gpg --keyserver ha.pool.sks-keyservers.net --recv-keys 97FC712E4C024BBEA48A61ED3A5CA953F73C700D
```

-	Created: Wed, 09 Sep 2015 21:04:22 GMT
-	Parent Layer: `498b8d9d85457c4a520c8678c4ce95829605287dfb5ca8f39586b76666d446ab`
-	Docker Version: 1.7.1
-	Virtual Size: 12.6 KB (12606 bytes)
-	v2 Blob: `sha256:46888fdbf9cc8d120b2ef8b90f7e6485384a4616e7c0e89a9675c41dc3473d7b`
-	v2 Content-Length: 6.7 KB (6737 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 22:03:31 GMT

#### `21647b83a090c12e2857e3d4c0232f2847c4f6e6a4c29d985865ee39a63b282e`

```dockerfile
ENV PYTHON_VERSION=3.4.3
```

-	Created: Wed, 09 Sep 2015 21:04:23 GMT
-	Parent Layer: `a29a9085667cc4e5e918115028e8ec2fcb15d7b4b10347aa2aeb8c344c8c626b`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `a9c792a21255ed5e500f3312a580bad3c905e99abfb1255b9673e461ac07569c`

```dockerfile
ENV PYTHON_PIP_VERSION=7.1.2
```

-	Created: Wed, 09 Sep 2015 21:04:23 GMT
-	Parent Layer: `21647b83a090c12e2857e3d4c0232f2847c4f6e6a4c29d985865ee39a63b282e`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `6715a9546df609218d0f13117aecb1b0258bd3898a8c4f7c68db71b8004399f1`

```dockerfile
RUN set -x \
	&& mkdir -p /usr/src/python \
	&& curl -SL "https://www.python.org/ftp/python/$PYTHON_VERSION/Python-$PYTHON_VERSION.tar.xz" -o python.tar.xz \
	&& curl -SL "https://www.python.org/ftp/python/$PYTHON_VERSION/Python-$PYTHON_VERSION.tar.xz.asc" -o python.tar.xz.asc \
	&& gpg --verify python.tar.xz.asc \
	&& tar -xJC /usr/src/python --strip-components=1 -f python.tar.xz \
	&& rm python.tar.xz* \
	&& cd /usr/src/python \
	&& ./configure --enable-shared --enable-unicode=ucs4 \
	&& make -j$(nproc) \
	&& make install \
	&& ldconfig \
	&& pip3 install --no-cache-dir --upgrade pip==$PYTHON_PIP_VERSION \
	&& find /usr/local \
		\( -type d -a -name test -o -name tests \) \
		-o \( -type f -a -name '*.pyc' -o -name '*.pyo' \) \
		-exec rm -rf '{}' + \
	&& rm -rf /usr/src/python
```

-	Created: Wed, 09 Sep 2015 21:07:05 GMT
-	Parent Layer: `a9c792a21255ed5e500f3312a580bad3c905e99abfb1255b9673e461ac07569c`
-	Docker Version: 1.7.1
-	Virtual Size: 77.3 MB (77258757 bytes)
-	v2 Blob: `sha256:17914ea1c1e60ce16c0de057810986990e8367e1c807709fa21a1bd356a8a516`
-	v2 Content-Length: 22.0 MB (22024763 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 22:03:08 GMT

#### `5af1e19f1a69d8e1f25d69996348cba1b90fcc4ac3ef1cd65d057618f2a53dca`

```dockerfile
RUN cd /usr/local/bin \
	&& ln -s easy_install-3.4 easy_install \
	&& ln -s idle3 idle \
	&& ln -s pydoc3 pydoc \
	&& ln -s python3 python \
	&& ln -s python-config3 python-config
```

-	Created: Wed, 09 Sep 2015 21:07:08 GMT
-	Parent Layer: `6715a9546df609218d0f13117aecb1b0258bd3898a8c4f7c68db71b8004399f1`
-	Docker Version: 1.7.1
-	Virtual Size: 48.0 B
-	v2 Blob: `sha256:e6ddad08c853495a5684ec4c0f4bf60dcbe18ffceae9e08f84a6e4b7410c4f0a`
-	v2 Content-Length: 270.0 B
-	v2 Last-Modified: Wed, 09 Sep 2015 22:02:47 GMT

#### `f6e6ebe683b00495ba71ccdcfd5a90ab4d4cd00c4379a6bd63e39ce2fd707703`

```dockerfile
CMD ["python3"]
```

-	Created: Wed, 09 Sep 2015 21:07:09 GMT
-	Parent Layer: `5af1e19f1a69d8e1f25d69996348cba1b90fcc4ac3ef1cd65d057618f2a53dca`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

## `python:3-wheezy`

```console
$ docker pull library/python@sha256:66a0656b6b0c45603fd3f868bfe9bb690831bac654bda51886b647a93d4c3937
```

-	Total Virtual Size: 537.3 MB (537270261 bytes)
-	Total v2 Content-Length: 197.5 MB (197468584 bytes)

### Layers (13)

#### `ba249489d0b6512128b60a4910e78fa2000c785d59e0599188a6802bd01155f2`

```dockerfile
ADD file:b908886c97e2b96665b7afc54ff53ebaef1c62896cf83a1199e59fceff1dafb5 in /
```

-	Created: Mon, 07 Sep 2015 23:37:10 GMT
-	Docker Version: 1.7.1
-	Virtual Size: 84.9 MB (84924773 bytes)
-	v2 Blob: `sha256:8f47f7c36e4382b4569bfe8858c0b371313e9c47a72867d69b000949c53637c9`
-	v2 Content-Length: 37.2 MB (37191761 bytes)
-	v2 Last-Modified: Mon, 07 Sep 2015 23:46:29 GMT

#### `19de96c112fcca5b6de16611dc0a359b0b977c551921ca79ac5cf4a8bfff9351`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Mon, 07 Sep 2015 23:37:11 GMT
-	Parent Layer: `ba249489d0b6512128b60a4910e78fa2000c785d59e0599188a6802bd01155f2`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `e83e5b7f7d01ffa47e46b7234799f12d842089df890db8fae765c5a4df26a20b`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 08 Sep 2015 15:38:48 GMT
-	Parent Layer: `19de96c112fcca5b6de16611dc0a359b0b977c551921ca79ac5cf4a8bfff9351`
-	Docker Version: 1.7.1
-	Virtual Size: 14.2 MB (14239819 bytes)
-	v2 Blob: `sha256:7a11528d019acc2b739bd4c1a7e518e247f729fdad40490be9d9fdb13e85c8c8`
-	v2 Content-Length: 6.7 MB (6739553 bytes)
-	v2 Last-Modified: Thu, 10 Sep 2015 23:43:23 GMT

#### `d6b70cefe2bfb76216c96acb6a6c6350eedff489df914b2606b1005e70f73a00`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 08 Sep 2015 15:39:23 GMT
-	Parent Layer: `e83e5b7f7d01ffa47e46b7234799f12d842089df890db8fae765c5a4df26a20b`
-	Docker Version: 1.7.1
-	Virtual Size: 109.4 MB (109431259 bytes)
-	v2 Blob: `sha256:4224b2b7563f71616cbe9215abf5276c51b18d3ceead85a56526519b5391a75f`
-	v2 Content-Length: 37.0 MB (37046780 bytes)
-	v2 Last-Modified: Tue, 08 Sep 2015 16:02:41 GMT

#### `3a5282506aa21c7b21cfdad32a099497bf9839dbc5e427f79bdad6a5e109f3d3`

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

-	Created: Tue, 08 Sep 2015 15:41:19 GMT
-	Parent Layer: `d6b70cefe2bfb76216c96acb6a6c6350eedff489df914b2606b1005e70f73a00`
-	Docker Version: 1.7.1
-	Virtual Size: 250.6 MB (250569275 bytes)
-	v2 Blob: `sha256:89989badb2c249165ed907bdf03e38dffbaefd3c115ad32ac6cf53ebbafab33b`
-	v2 Content-Length: 94.3 MB (94261782 bytes)
-	v2 Last-Modified: Tue, 08 Sep 2015 16:03:53 GMT

#### `1046da491d81f106d762e20009d4dfff16da8b2af4eafc70cba44ca74f7dc53e`

```dockerfile
RUN apt-get purge -y python.*
```

-	Created: Wed, 09 Sep 2015 20:31:23 GMT
-	Parent Layer: `3a5282506aa21c7b21cfdad32a099497bf9839dbc5e427f79bdad6a5e109f3d3`
-	Docker Version: 1.7.1
-	Virtual Size: 833.7 KB (833724 bytes)
-	v2 Blob: `sha256:9bab6257d36f85970d8effd469dcd7c7a44ab5de929035933d165b6a35929905`
-	v2 Content-Length: 196.8 KB (196778 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:39:13 GMT

#### `498b8d9d85457c4a520c8678c4ce95829605287dfb5ca8f39586b76666d446ab`

```dockerfile
ENV LANG=C.UTF-8
```

-	Created: Wed, 09 Sep 2015 20:31:23 GMT
-	Parent Layer: `1046da491d81f106d762e20009d4dfff16da8b2af4eafc70cba44ca74f7dc53e`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `a29a9085667cc4e5e918115028e8ec2fcb15d7b4b10347aa2aeb8c344c8c626b`

```dockerfile
RUN gpg --keyserver ha.pool.sks-keyservers.net --recv-keys 97FC712E4C024BBEA48A61ED3A5CA953F73C700D
```

-	Created: Wed, 09 Sep 2015 21:04:22 GMT
-	Parent Layer: `498b8d9d85457c4a520c8678c4ce95829605287dfb5ca8f39586b76666d446ab`
-	Docker Version: 1.7.1
-	Virtual Size: 12.6 KB (12606 bytes)
-	v2 Blob: `sha256:46888fdbf9cc8d120b2ef8b90f7e6485384a4616e7c0e89a9675c41dc3473d7b`
-	v2 Content-Length: 6.7 KB (6737 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 22:03:31 GMT

#### `21647b83a090c12e2857e3d4c0232f2847c4f6e6a4c29d985865ee39a63b282e`

```dockerfile
ENV PYTHON_VERSION=3.4.3
```

-	Created: Wed, 09 Sep 2015 21:04:23 GMT
-	Parent Layer: `a29a9085667cc4e5e918115028e8ec2fcb15d7b4b10347aa2aeb8c344c8c626b`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `a9c792a21255ed5e500f3312a580bad3c905e99abfb1255b9673e461ac07569c`

```dockerfile
ENV PYTHON_PIP_VERSION=7.1.2
```

-	Created: Wed, 09 Sep 2015 21:04:23 GMT
-	Parent Layer: `21647b83a090c12e2857e3d4c0232f2847c4f6e6a4c29d985865ee39a63b282e`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `6715a9546df609218d0f13117aecb1b0258bd3898a8c4f7c68db71b8004399f1`

```dockerfile
RUN set -x \
	&& mkdir -p /usr/src/python \
	&& curl -SL "https://www.python.org/ftp/python/$PYTHON_VERSION/Python-$PYTHON_VERSION.tar.xz" -o python.tar.xz \
	&& curl -SL "https://www.python.org/ftp/python/$PYTHON_VERSION/Python-$PYTHON_VERSION.tar.xz.asc" -o python.tar.xz.asc \
	&& gpg --verify python.tar.xz.asc \
	&& tar -xJC /usr/src/python --strip-components=1 -f python.tar.xz \
	&& rm python.tar.xz* \
	&& cd /usr/src/python \
	&& ./configure --enable-shared --enable-unicode=ucs4 \
	&& make -j$(nproc) \
	&& make install \
	&& ldconfig \
	&& pip3 install --no-cache-dir --upgrade pip==$PYTHON_PIP_VERSION \
	&& find /usr/local \
		\( -type d -a -name test -o -name tests \) \
		-o \( -type f -a -name '*.pyc' -o -name '*.pyo' \) \
		-exec rm -rf '{}' + \
	&& rm -rf /usr/src/python
```

-	Created: Wed, 09 Sep 2015 21:07:05 GMT
-	Parent Layer: `a9c792a21255ed5e500f3312a580bad3c905e99abfb1255b9673e461ac07569c`
-	Docker Version: 1.7.1
-	Virtual Size: 77.3 MB (77258757 bytes)
-	v2 Blob: `sha256:17914ea1c1e60ce16c0de057810986990e8367e1c807709fa21a1bd356a8a516`
-	v2 Content-Length: 22.0 MB (22024763 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 22:03:08 GMT

#### `5af1e19f1a69d8e1f25d69996348cba1b90fcc4ac3ef1cd65d057618f2a53dca`

```dockerfile
RUN cd /usr/local/bin \
	&& ln -s easy_install-3.4 easy_install \
	&& ln -s idle3 idle \
	&& ln -s pydoc3 pydoc \
	&& ln -s python3 python \
	&& ln -s python-config3 python-config
```

-	Created: Wed, 09 Sep 2015 21:07:08 GMT
-	Parent Layer: `6715a9546df609218d0f13117aecb1b0258bd3898a8c4f7c68db71b8004399f1`
-	Docker Version: 1.7.1
-	Virtual Size: 48.0 B
-	v2 Blob: `sha256:e6ddad08c853495a5684ec4c0f4bf60dcbe18ffceae9e08f84a6e4b7410c4f0a`
-	v2 Content-Length: 270.0 B
-	v2 Last-Modified: Wed, 09 Sep 2015 22:02:47 GMT

#### `f6e6ebe683b00495ba71ccdcfd5a90ab4d4cd00c4379a6bd63e39ce2fd707703`

```dockerfile
CMD ["python3"]
```

-	Created: Wed, 09 Sep 2015 21:07:09 GMT
-	Parent Layer: `5af1e19f1a69d8e1f25d69996348cba1b90fcc4ac3ef1cd65d057618f2a53dca`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

## `python:wheezy`

```console
$ docker pull library/python@sha256:c46030d72cf8ce348ac9744b9ef2a9dc9e99057b916692ed32ae2c5252f1ec82
```

-	Total Virtual Size: 537.3 MB (537270261 bytes)
-	Total v2 Content-Length: 197.5 MB (197468584 bytes)

### Layers (13)

#### `ba249489d0b6512128b60a4910e78fa2000c785d59e0599188a6802bd01155f2`

```dockerfile
ADD file:b908886c97e2b96665b7afc54ff53ebaef1c62896cf83a1199e59fceff1dafb5 in /
```

-	Created: Mon, 07 Sep 2015 23:37:10 GMT
-	Docker Version: 1.7.1
-	Virtual Size: 84.9 MB (84924773 bytes)
-	v2 Blob: `sha256:8f47f7c36e4382b4569bfe8858c0b371313e9c47a72867d69b000949c53637c9`
-	v2 Content-Length: 37.2 MB (37191761 bytes)
-	v2 Last-Modified: Mon, 07 Sep 2015 23:46:29 GMT

#### `19de96c112fcca5b6de16611dc0a359b0b977c551921ca79ac5cf4a8bfff9351`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Mon, 07 Sep 2015 23:37:11 GMT
-	Parent Layer: `ba249489d0b6512128b60a4910e78fa2000c785d59e0599188a6802bd01155f2`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `e83e5b7f7d01ffa47e46b7234799f12d842089df890db8fae765c5a4df26a20b`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 08 Sep 2015 15:38:48 GMT
-	Parent Layer: `19de96c112fcca5b6de16611dc0a359b0b977c551921ca79ac5cf4a8bfff9351`
-	Docker Version: 1.7.1
-	Virtual Size: 14.2 MB (14239819 bytes)
-	v2 Blob: `sha256:7a11528d019acc2b739bd4c1a7e518e247f729fdad40490be9d9fdb13e85c8c8`
-	v2 Content-Length: 6.7 MB (6739553 bytes)
-	v2 Last-Modified: Thu, 10 Sep 2015 23:43:23 GMT

#### `d6b70cefe2bfb76216c96acb6a6c6350eedff489df914b2606b1005e70f73a00`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 08 Sep 2015 15:39:23 GMT
-	Parent Layer: `e83e5b7f7d01ffa47e46b7234799f12d842089df890db8fae765c5a4df26a20b`
-	Docker Version: 1.7.1
-	Virtual Size: 109.4 MB (109431259 bytes)
-	v2 Blob: `sha256:4224b2b7563f71616cbe9215abf5276c51b18d3ceead85a56526519b5391a75f`
-	v2 Content-Length: 37.0 MB (37046780 bytes)
-	v2 Last-Modified: Tue, 08 Sep 2015 16:02:41 GMT

#### `3a5282506aa21c7b21cfdad32a099497bf9839dbc5e427f79bdad6a5e109f3d3`

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

-	Created: Tue, 08 Sep 2015 15:41:19 GMT
-	Parent Layer: `d6b70cefe2bfb76216c96acb6a6c6350eedff489df914b2606b1005e70f73a00`
-	Docker Version: 1.7.1
-	Virtual Size: 250.6 MB (250569275 bytes)
-	v2 Blob: `sha256:89989badb2c249165ed907bdf03e38dffbaefd3c115ad32ac6cf53ebbafab33b`
-	v2 Content-Length: 94.3 MB (94261782 bytes)
-	v2 Last-Modified: Tue, 08 Sep 2015 16:03:53 GMT

#### `1046da491d81f106d762e20009d4dfff16da8b2af4eafc70cba44ca74f7dc53e`

```dockerfile
RUN apt-get purge -y python.*
```

-	Created: Wed, 09 Sep 2015 20:31:23 GMT
-	Parent Layer: `3a5282506aa21c7b21cfdad32a099497bf9839dbc5e427f79bdad6a5e109f3d3`
-	Docker Version: 1.7.1
-	Virtual Size: 833.7 KB (833724 bytes)
-	v2 Blob: `sha256:9bab6257d36f85970d8effd469dcd7c7a44ab5de929035933d165b6a35929905`
-	v2 Content-Length: 196.8 KB (196778 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:39:13 GMT

#### `498b8d9d85457c4a520c8678c4ce95829605287dfb5ca8f39586b76666d446ab`

```dockerfile
ENV LANG=C.UTF-8
```

-	Created: Wed, 09 Sep 2015 20:31:23 GMT
-	Parent Layer: `1046da491d81f106d762e20009d4dfff16da8b2af4eafc70cba44ca74f7dc53e`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `a29a9085667cc4e5e918115028e8ec2fcb15d7b4b10347aa2aeb8c344c8c626b`

```dockerfile
RUN gpg --keyserver ha.pool.sks-keyservers.net --recv-keys 97FC712E4C024BBEA48A61ED3A5CA953F73C700D
```

-	Created: Wed, 09 Sep 2015 21:04:22 GMT
-	Parent Layer: `498b8d9d85457c4a520c8678c4ce95829605287dfb5ca8f39586b76666d446ab`
-	Docker Version: 1.7.1
-	Virtual Size: 12.6 KB (12606 bytes)
-	v2 Blob: `sha256:46888fdbf9cc8d120b2ef8b90f7e6485384a4616e7c0e89a9675c41dc3473d7b`
-	v2 Content-Length: 6.7 KB (6737 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 22:03:31 GMT

#### `21647b83a090c12e2857e3d4c0232f2847c4f6e6a4c29d985865ee39a63b282e`

```dockerfile
ENV PYTHON_VERSION=3.4.3
```

-	Created: Wed, 09 Sep 2015 21:04:23 GMT
-	Parent Layer: `a29a9085667cc4e5e918115028e8ec2fcb15d7b4b10347aa2aeb8c344c8c626b`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `a9c792a21255ed5e500f3312a580bad3c905e99abfb1255b9673e461ac07569c`

```dockerfile
ENV PYTHON_PIP_VERSION=7.1.2
```

-	Created: Wed, 09 Sep 2015 21:04:23 GMT
-	Parent Layer: `21647b83a090c12e2857e3d4c0232f2847c4f6e6a4c29d985865ee39a63b282e`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `6715a9546df609218d0f13117aecb1b0258bd3898a8c4f7c68db71b8004399f1`

```dockerfile
RUN set -x \
	&& mkdir -p /usr/src/python \
	&& curl -SL "https://www.python.org/ftp/python/$PYTHON_VERSION/Python-$PYTHON_VERSION.tar.xz" -o python.tar.xz \
	&& curl -SL "https://www.python.org/ftp/python/$PYTHON_VERSION/Python-$PYTHON_VERSION.tar.xz.asc" -o python.tar.xz.asc \
	&& gpg --verify python.tar.xz.asc \
	&& tar -xJC /usr/src/python --strip-components=1 -f python.tar.xz \
	&& rm python.tar.xz* \
	&& cd /usr/src/python \
	&& ./configure --enable-shared --enable-unicode=ucs4 \
	&& make -j$(nproc) \
	&& make install \
	&& ldconfig \
	&& pip3 install --no-cache-dir --upgrade pip==$PYTHON_PIP_VERSION \
	&& find /usr/local \
		\( -type d -a -name test -o -name tests \) \
		-o \( -type f -a -name '*.pyc' -o -name '*.pyo' \) \
		-exec rm -rf '{}' + \
	&& rm -rf /usr/src/python
```

-	Created: Wed, 09 Sep 2015 21:07:05 GMT
-	Parent Layer: `a9c792a21255ed5e500f3312a580bad3c905e99abfb1255b9673e461ac07569c`
-	Docker Version: 1.7.1
-	Virtual Size: 77.3 MB (77258757 bytes)
-	v2 Blob: `sha256:17914ea1c1e60ce16c0de057810986990e8367e1c807709fa21a1bd356a8a516`
-	v2 Content-Length: 22.0 MB (22024763 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 22:03:08 GMT

#### `5af1e19f1a69d8e1f25d69996348cba1b90fcc4ac3ef1cd65d057618f2a53dca`

```dockerfile
RUN cd /usr/local/bin \
	&& ln -s easy_install-3.4 easy_install \
	&& ln -s idle3 idle \
	&& ln -s pydoc3 pydoc \
	&& ln -s python3 python \
	&& ln -s python-config3 python-config
```

-	Created: Wed, 09 Sep 2015 21:07:08 GMT
-	Parent Layer: `6715a9546df609218d0f13117aecb1b0258bd3898a8c4f7c68db71b8004399f1`
-	Docker Version: 1.7.1
-	Virtual Size: 48.0 B
-	v2 Blob: `sha256:e6ddad08c853495a5684ec4c0f4bf60dcbe18ffceae9e08f84a6e4b7410c4f0a`
-	v2 Content-Length: 270.0 B
-	v2 Last-Modified: Wed, 09 Sep 2015 22:02:47 GMT

#### `f6e6ebe683b00495ba71ccdcfd5a90ab4d4cd00c4379a6bd63e39ce2fd707703`

```dockerfile
CMD ["python3"]
```

-	Created: Wed, 09 Sep 2015 21:07:09 GMT
-	Parent Layer: `5af1e19f1a69d8e1f25d69996348cba1b90fcc4ac3ef1cd65d057618f2a53dca`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

## `python:3.5.0`

```console
$ docker pull library/python@sha256:506ae83487c1cda90891140bead0af96ff2cb0e9f0c56b28363db9874924b5b4
```

-	Total Virtual Size: 689.0 MB (689018474 bytes)
-	Total v2 Content-Length: 263.9 MB (263879049 bytes)

### Layers (13)

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
-	v2 Blob: `sha256:b3010ec3eb21ac3df74757a47832fb17395b76ad3a30794074cefd07541d3557`
-	v2 Content-Length: 18.5 MB (18538591 bytes)
-	v2 Last-Modified: Thu, 10 Sep 2015 23:36:30 GMT

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

#### `a7131b97316204530af26e42319aeda8ac44cd5ac2891e5dab45e16deb1e592d`

```dockerfile
RUN apt-get purge -y python.*
```

-	Created: Wed, 09 Sep 2015 20:20:46 GMT
-	Parent Layer: `16b189cc8ce688f9f1d8f1d837fa0891107450a06c795b1cba8f6c33a4454280`
-	Docker Version: 1.7.1
-	Virtual Size: 975.3 KB (975277 bytes)
-	v2 Blob: `sha256:20cdbe5b7a6f64396bcabde9b06c16a0b41e2c7fd39b28eff1ee3670a9f0516e`
-	v2 Content-Length: 220.4 KB (220377 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:29:17 GMT

#### `d7cbb60bc416f832c685b38578b77da5f3716cba15d4bcb45d850809a4c112eb`

```dockerfile
ENV LANG=C.UTF-8
```

-	Created: Wed, 09 Sep 2015 20:20:48 GMT
-	Parent Layer: `a7131b97316204530af26e42319aeda8ac44cd5ac2891e5dab45e16deb1e592d`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `d8ea027435229a8bdc09fa68db0043f1e2059ec889a3715c3e184553aee36da4`

```dockerfile
RUN gpg --keyserver ha.pool.sks-keyservers.net --recv-keys 97FC712E4C024BBEA48A61ED3A5CA953F73C700D
```

-	Created: Wed, 09 Sep 2015 20:53:54 GMT
-	Parent Layer: `d7cbb60bc416f832c685b38578b77da5f3716cba15d4bcb45d850809a4c112eb`
-	Docker Version: 1.7.1
-	Virtual Size: 12.6 KB (12606 bytes)
-	v2 Blob: `sha256:2fdbb7a55da29a948a258ac37edb8f60a95a8c9757555c009ac32bc5a50e4197`
-	v2 Content-Length: 6.7 KB (6737 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:55:10 GMT

#### `195c6cc147afc452d1a28053ccca813778128e777d0b7bb2adfbc07a78ea4f34`

```dockerfile
ENV PYTHON_VERSION=3.5.0
```

-	Created: Mon, 14 Sep 2015 20:18:06 GMT
-	Parent Layer: `d8ea027435229a8bdc09fa68db0043f1e2059ec889a3715c3e184553aee36da4`
-	Docker Version: 1.8.2
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `c45a3c61eb6340b5cffd6817830b073d9a46d814af70f1897802af2669597155`

```dockerfile
ENV PYTHON_PIP_VERSION=7.1.2
```

-	Created: Mon, 14 Sep 2015 20:18:06 GMT
-	Parent Layer: `195c6cc147afc452d1a28053ccca813778128e777d0b7bb2adfbc07a78ea4f34`
-	Docker Version: 1.8.2
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `dafed9a3b9ad76a0401a59d9be5b36b04ffda07f8332186027a59f1eb63e20a0`

```dockerfile
RUN set -x \
	&& mkdir -p /usr/src/python \
	&& curl -SL "https://www.python.org/ftp/python/${PYTHON_VERSION%%[a-z]*}/Python-$PYTHON_VERSION.tar.xz" -o python.tar.xz \
	&& curl -SL "https://www.python.org/ftp/python/${PYTHON_VERSION%%[a-z]*}/Python-$PYTHON_VERSION.tar.xz.asc" -o python.tar.xz.asc \
	&& gpg --verify python.tar.xz.asc \
	&& tar -xJC /usr/src/python --strip-components=1 -f python.tar.xz \
	&& rm python.tar.xz* \
	&& cd /usr/src/python \
	&& ./configure --enable-shared --enable-unicode=ucs4 \
	&& make -j$(nproc) \
	&& make install \
	&& ldconfig \
	&& pip3 install --no-cache-dir --upgrade --ignore-installed pip==$PYTHON_PIP_VERSION \
	&& find /usr/local \
		\( -type d -a -name test -o -name tests \) \
		-o \( -type f -a -name '*.pyc' -o -name '*.pyo' \) \
		-exec rm -rf '{}' + \
	&& rm -rf /usr/src/python
```

-	Created: Mon, 14 Sep 2015 20:20:17 GMT
-	Parent Layer: `c45a3c61eb6340b5cffd6817830b073d9a46d814af70f1897802af2669597155`
-	Docker Version: 1.8.2
-	Virtual Size: 81.5 MB (81545585 bytes)
-	v2 Blob: `sha256:4b321d03baef5c02926eb913e7b8445046b2f34b9a5274a1bdfddc1465efd2d1`
-	v2 Content-Length: 22.9 MB (22882542 bytes)
-	v2 Last-Modified: Mon, 14 Sep 2015 21:03:04 GMT

#### `4610a34007626cc1f90c5a13b2f56afcfac224f91a93ad0a8a1899803f348c96`

```dockerfile
RUN cd /usr/local/bin \
	&& ln -s easy_install-3.5 easy_install \
	&& ln -s idle3 idle \
	&& ln -s pydoc3 pydoc \
	&& ln -s python3 python \
	&& ln -s python-config3 python-config
```

-	Created: Mon, 14 Sep 2015 20:20:19 GMT
-	Parent Layer: `dafed9a3b9ad76a0401a59d9be5b36b04ffda07f8332186027a59f1eb63e20a0`
-	Docker Version: 1.8.2
-	Virtual Size: 48.0 B
-	v2 Blob: `sha256:936a15433462948c9831eafaf52ced79826f46f4be29b9eb79be1a4f4d832b83`
-	v2 Content-Length: 269.0 B
-	v2 Last-Modified: Mon, 14 Sep 2015 21:02:48 GMT

#### `b909084b799498656574bf948b5c0aa7312b850d862cafcfff43153d8b04269d`

```dockerfile
CMD ["python3"]
```

-	Created: Mon, 14 Sep 2015 20:20:19 GMT
-	Parent Layer: `4610a34007626cc1f90c5a13b2f56afcfac224f91a93ad0a8a1899803f348c96`
-	Docker Version: 1.8.2
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

## `python:3.5`

```console
$ docker pull library/python@sha256:1a3d3e147b1e643fc13bccf59960cdcfb1200fb10e2d610016a2d2adbd949a7d
```

-	Total Virtual Size: 689.0 MB (689018474 bytes)
-	Total v2 Content-Length: 263.9 MB (263879049 bytes)

### Layers (13)

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
-	v2 Blob: `sha256:b3010ec3eb21ac3df74757a47832fb17395b76ad3a30794074cefd07541d3557`
-	v2 Content-Length: 18.5 MB (18538591 bytes)
-	v2 Last-Modified: Thu, 10 Sep 2015 23:36:30 GMT

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

#### `a7131b97316204530af26e42319aeda8ac44cd5ac2891e5dab45e16deb1e592d`

```dockerfile
RUN apt-get purge -y python.*
```

-	Created: Wed, 09 Sep 2015 20:20:46 GMT
-	Parent Layer: `16b189cc8ce688f9f1d8f1d837fa0891107450a06c795b1cba8f6c33a4454280`
-	Docker Version: 1.7.1
-	Virtual Size: 975.3 KB (975277 bytes)
-	v2 Blob: `sha256:20cdbe5b7a6f64396bcabde9b06c16a0b41e2c7fd39b28eff1ee3670a9f0516e`
-	v2 Content-Length: 220.4 KB (220377 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:29:17 GMT

#### `d7cbb60bc416f832c685b38578b77da5f3716cba15d4bcb45d850809a4c112eb`

```dockerfile
ENV LANG=C.UTF-8
```

-	Created: Wed, 09 Sep 2015 20:20:48 GMT
-	Parent Layer: `a7131b97316204530af26e42319aeda8ac44cd5ac2891e5dab45e16deb1e592d`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `d8ea027435229a8bdc09fa68db0043f1e2059ec889a3715c3e184553aee36da4`

```dockerfile
RUN gpg --keyserver ha.pool.sks-keyservers.net --recv-keys 97FC712E4C024BBEA48A61ED3A5CA953F73C700D
```

-	Created: Wed, 09 Sep 2015 20:53:54 GMT
-	Parent Layer: `d7cbb60bc416f832c685b38578b77da5f3716cba15d4bcb45d850809a4c112eb`
-	Docker Version: 1.7.1
-	Virtual Size: 12.6 KB (12606 bytes)
-	v2 Blob: `sha256:2fdbb7a55da29a948a258ac37edb8f60a95a8c9757555c009ac32bc5a50e4197`
-	v2 Content-Length: 6.7 KB (6737 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:55:10 GMT

#### `195c6cc147afc452d1a28053ccca813778128e777d0b7bb2adfbc07a78ea4f34`

```dockerfile
ENV PYTHON_VERSION=3.5.0
```

-	Created: Mon, 14 Sep 2015 20:18:06 GMT
-	Parent Layer: `d8ea027435229a8bdc09fa68db0043f1e2059ec889a3715c3e184553aee36da4`
-	Docker Version: 1.8.2
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `c45a3c61eb6340b5cffd6817830b073d9a46d814af70f1897802af2669597155`

```dockerfile
ENV PYTHON_PIP_VERSION=7.1.2
```

-	Created: Mon, 14 Sep 2015 20:18:06 GMT
-	Parent Layer: `195c6cc147afc452d1a28053ccca813778128e777d0b7bb2adfbc07a78ea4f34`
-	Docker Version: 1.8.2
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `dafed9a3b9ad76a0401a59d9be5b36b04ffda07f8332186027a59f1eb63e20a0`

```dockerfile
RUN set -x \
	&& mkdir -p /usr/src/python \
	&& curl -SL "https://www.python.org/ftp/python/${PYTHON_VERSION%%[a-z]*}/Python-$PYTHON_VERSION.tar.xz" -o python.tar.xz \
	&& curl -SL "https://www.python.org/ftp/python/${PYTHON_VERSION%%[a-z]*}/Python-$PYTHON_VERSION.tar.xz.asc" -o python.tar.xz.asc \
	&& gpg --verify python.tar.xz.asc \
	&& tar -xJC /usr/src/python --strip-components=1 -f python.tar.xz \
	&& rm python.tar.xz* \
	&& cd /usr/src/python \
	&& ./configure --enable-shared --enable-unicode=ucs4 \
	&& make -j$(nproc) \
	&& make install \
	&& ldconfig \
	&& pip3 install --no-cache-dir --upgrade --ignore-installed pip==$PYTHON_PIP_VERSION \
	&& find /usr/local \
		\( -type d -a -name test -o -name tests \) \
		-o \( -type f -a -name '*.pyc' -o -name '*.pyo' \) \
		-exec rm -rf '{}' + \
	&& rm -rf /usr/src/python
```

-	Created: Mon, 14 Sep 2015 20:20:17 GMT
-	Parent Layer: `c45a3c61eb6340b5cffd6817830b073d9a46d814af70f1897802af2669597155`
-	Docker Version: 1.8.2
-	Virtual Size: 81.5 MB (81545585 bytes)
-	v2 Blob: `sha256:4b321d03baef5c02926eb913e7b8445046b2f34b9a5274a1bdfddc1465efd2d1`
-	v2 Content-Length: 22.9 MB (22882542 bytes)
-	v2 Last-Modified: Mon, 14 Sep 2015 21:03:04 GMT

#### `4610a34007626cc1f90c5a13b2f56afcfac224f91a93ad0a8a1899803f348c96`

```dockerfile
RUN cd /usr/local/bin \
	&& ln -s easy_install-3.5 easy_install \
	&& ln -s idle3 idle \
	&& ln -s pydoc3 pydoc \
	&& ln -s python3 python \
	&& ln -s python-config3 python-config
```

-	Created: Mon, 14 Sep 2015 20:20:19 GMT
-	Parent Layer: `dafed9a3b9ad76a0401a59d9be5b36b04ffda07f8332186027a59f1eb63e20a0`
-	Docker Version: 1.8.2
-	Virtual Size: 48.0 B
-	v2 Blob: `sha256:936a15433462948c9831eafaf52ced79826f46f4be29b9eb79be1a4f4d832b83`
-	v2 Content-Length: 269.0 B
-	v2 Last-Modified: Mon, 14 Sep 2015 21:02:48 GMT

#### `b909084b799498656574bf948b5c0aa7312b850d862cafcfff43153d8b04269d`

```dockerfile
CMD ["python3"]
```

-	Created: Mon, 14 Sep 2015 20:20:19 GMT
-	Parent Layer: `4610a34007626cc1f90c5a13b2f56afcfac224f91a93ad0a8a1899803f348c96`
-	Docker Version: 1.8.2
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

## `python:3.5.0-onbuild`

```console
$ docker pull library/python@sha256:6e6d824be014be31c2bbe2c038c8889eedcdd722e47e98ba598766a42c7e7618
```

-	Total Virtual Size: 689.0 MB (689018474 bytes)
-	Total v2 Content-Length: 263.9 MB (263879304 bytes)

### Layers (18)

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
-	v2 Blob: `sha256:b3010ec3eb21ac3df74757a47832fb17395b76ad3a30794074cefd07541d3557`
-	v2 Content-Length: 18.5 MB (18538591 bytes)
-	v2 Last-Modified: Thu, 10 Sep 2015 23:36:30 GMT

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

#### `a7131b97316204530af26e42319aeda8ac44cd5ac2891e5dab45e16deb1e592d`

```dockerfile
RUN apt-get purge -y python.*
```

-	Created: Wed, 09 Sep 2015 20:20:46 GMT
-	Parent Layer: `16b189cc8ce688f9f1d8f1d837fa0891107450a06c795b1cba8f6c33a4454280`
-	Docker Version: 1.7.1
-	Virtual Size: 975.3 KB (975277 bytes)
-	v2 Blob: `sha256:20cdbe5b7a6f64396bcabde9b06c16a0b41e2c7fd39b28eff1ee3670a9f0516e`
-	v2 Content-Length: 220.4 KB (220377 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:29:17 GMT

#### `d7cbb60bc416f832c685b38578b77da5f3716cba15d4bcb45d850809a4c112eb`

```dockerfile
ENV LANG=C.UTF-8
```

-	Created: Wed, 09 Sep 2015 20:20:48 GMT
-	Parent Layer: `a7131b97316204530af26e42319aeda8ac44cd5ac2891e5dab45e16deb1e592d`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `d8ea027435229a8bdc09fa68db0043f1e2059ec889a3715c3e184553aee36da4`

```dockerfile
RUN gpg --keyserver ha.pool.sks-keyservers.net --recv-keys 97FC712E4C024BBEA48A61ED3A5CA953F73C700D
```

-	Created: Wed, 09 Sep 2015 20:53:54 GMT
-	Parent Layer: `d7cbb60bc416f832c685b38578b77da5f3716cba15d4bcb45d850809a4c112eb`
-	Docker Version: 1.7.1
-	Virtual Size: 12.6 KB (12606 bytes)
-	v2 Blob: `sha256:2fdbb7a55da29a948a258ac37edb8f60a95a8c9757555c009ac32bc5a50e4197`
-	v2 Content-Length: 6.7 KB (6737 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:55:10 GMT

#### `195c6cc147afc452d1a28053ccca813778128e777d0b7bb2adfbc07a78ea4f34`

```dockerfile
ENV PYTHON_VERSION=3.5.0
```

-	Created: Mon, 14 Sep 2015 20:18:06 GMT
-	Parent Layer: `d8ea027435229a8bdc09fa68db0043f1e2059ec889a3715c3e184553aee36da4`
-	Docker Version: 1.8.2
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `c45a3c61eb6340b5cffd6817830b073d9a46d814af70f1897802af2669597155`

```dockerfile
ENV PYTHON_PIP_VERSION=7.1.2
```

-	Created: Mon, 14 Sep 2015 20:18:06 GMT
-	Parent Layer: `195c6cc147afc452d1a28053ccca813778128e777d0b7bb2adfbc07a78ea4f34`
-	Docker Version: 1.8.2
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `dafed9a3b9ad76a0401a59d9be5b36b04ffda07f8332186027a59f1eb63e20a0`

```dockerfile
RUN set -x \
	&& mkdir -p /usr/src/python \
	&& curl -SL "https://www.python.org/ftp/python/${PYTHON_VERSION%%[a-z]*}/Python-$PYTHON_VERSION.tar.xz" -o python.tar.xz \
	&& curl -SL "https://www.python.org/ftp/python/${PYTHON_VERSION%%[a-z]*}/Python-$PYTHON_VERSION.tar.xz.asc" -o python.tar.xz.asc \
	&& gpg --verify python.tar.xz.asc \
	&& tar -xJC /usr/src/python --strip-components=1 -f python.tar.xz \
	&& rm python.tar.xz* \
	&& cd /usr/src/python \
	&& ./configure --enable-shared --enable-unicode=ucs4 \
	&& make -j$(nproc) \
	&& make install \
	&& ldconfig \
	&& pip3 install --no-cache-dir --upgrade --ignore-installed pip==$PYTHON_PIP_VERSION \
	&& find /usr/local \
		\( -type d -a -name test -o -name tests \) \
		-o \( -type f -a -name '*.pyc' -o -name '*.pyo' \) \
		-exec rm -rf '{}' + \
	&& rm -rf /usr/src/python
```

-	Created: Mon, 14 Sep 2015 20:20:17 GMT
-	Parent Layer: `c45a3c61eb6340b5cffd6817830b073d9a46d814af70f1897802af2669597155`
-	Docker Version: 1.8.2
-	Virtual Size: 81.5 MB (81545585 bytes)
-	v2 Blob: `sha256:4b321d03baef5c02926eb913e7b8445046b2f34b9a5274a1bdfddc1465efd2d1`
-	v2 Content-Length: 22.9 MB (22882542 bytes)
-	v2 Last-Modified: Mon, 14 Sep 2015 21:03:04 GMT

#### `4610a34007626cc1f90c5a13b2f56afcfac224f91a93ad0a8a1899803f348c96`

```dockerfile
RUN cd /usr/local/bin \
	&& ln -s easy_install-3.5 easy_install \
	&& ln -s idle3 idle \
	&& ln -s pydoc3 pydoc \
	&& ln -s python3 python \
	&& ln -s python-config3 python-config
```

-	Created: Mon, 14 Sep 2015 20:20:19 GMT
-	Parent Layer: `dafed9a3b9ad76a0401a59d9be5b36b04ffda07f8332186027a59f1eb63e20a0`
-	Docker Version: 1.8.2
-	Virtual Size: 48.0 B
-	v2 Blob: `sha256:936a15433462948c9831eafaf52ced79826f46f4be29b9eb79be1a4f4d832b83`
-	v2 Content-Length: 269.0 B
-	v2 Last-Modified: Mon, 14 Sep 2015 21:02:48 GMT

#### `b909084b799498656574bf948b5c0aa7312b850d862cafcfff43153d8b04269d`

```dockerfile
CMD ["python3"]
```

-	Created: Mon, 14 Sep 2015 20:20:19 GMT
-	Parent Layer: `4610a34007626cc1f90c5a13b2f56afcfac224f91a93ad0a8a1899803f348c96`
-	Docker Version: 1.8.2
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `149129bb37da6572b0ad2de18d1b0ff1be9cc4d39da6ddb2d737ae091ec70635`

```dockerfile
RUN mkdir -p /usr/src/app
```

-	Created: Mon, 14 Sep 2015 20:20:41 GMT
-	Parent Layer: `b909084b799498656574bf948b5c0aa7312b850d862cafcfff43153d8b04269d`
-	Docker Version: 1.8.2
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:31049d0c8154f9814719b0e6e6c8549a69bdd8ae77fbd526396508f145b40314`
-	v2 Content-Length: 127.0 B
-	v2 Last-Modified: Mon, 14 Sep 2015 21:04:38 GMT

#### `7890fe902afebc6dcb8b1c421b47ca45e6a2f2392dad5415ac631af9d471d441`

```dockerfile
WORKDIR /usr/src/app
```

-	Created: Mon, 14 Sep 2015 20:20:41 GMT
-	Parent Layer: `149129bb37da6572b0ad2de18d1b0ff1be9cc4d39da6ddb2d737ae091ec70635`
-	Docker Version: 1.8.2
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `129b85f95b6944dd0d5e5485da3fb0ea55b2941a0aef1c158aaeee8152e422d0`

```dockerfile
ONBUILD COPY requirements.txt /usr/src/app/
```

-	Created: Mon, 14 Sep 2015 20:20:41 GMT
-	Parent Layer: `7890fe902afebc6dcb8b1c421b47ca45e6a2f2392dad5415ac631af9d471d441`
-	Docker Version: 1.8.2
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `34f645e2664fc5bb198c4be71214d37e64f125a13f985fa5697264a9ccfe6c36`

```dockerfile
ONBUILD RUN pip install --no-cache-dir -r requirements.txt
```

-	Created: Mon, 14 Sep 2015 20:20:42 GMT
-	Parent Layer: `129b85f95b6944dd0d5e5485da3fb0ea55b2941a0aef1c158aaeee8152e422d0`
-	Docker Version: 1.8.2
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `952de03dc5df0c82183856f14ad22426850fa30ec9f1efd4c948ba60cc83d357`

```dockerfile
ONBUILD COPY . /usr/src/app
```

-	Created: Mon, 14 Sep 2015 20:20:42 GMT
-	Parent Layer: `34f645e2664fc5bb198c4be71214d37e64f125a13f985fa5697264a9ccfe6c36`
-	Docker Version: 1.8.2
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

## `python:3.5-onbuild`

```console
$ docker pull library/python@sha256:1b5e23a4f42dcdf77f07fcb4c2cef498043f34944ab4374b5aff1f99589fe519
```

-	Total Virtual Size: 689.0 MB (689018474 bytes)
-	Total v2 Content-Length: 263.9 MB (263879304 bytes)

### Layers (18)

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
-	v2 Blob: `sha256:b3010ec3eb21ac3df74757a47832fb17395b76ad3a30794074cefd07541d3557`
-	v2 Content-Length: 18.5 MB (18538591 bytes)
-	v2 Last-Modified: Thu, 10 Sep 2015 23:36:30 GMT

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

#### `a7131b97316204530af26e42319aeda8ac44cd5ac2891e5dab45e16deb1e592d`

```dockerfile
RUN apt-get purge -y python.*
```

-	Created: Wed, 09 Sep 2015 20:20:46 GMT
-	Parent Layer: `16b189cc8ce688f9f1d8f1d837fa0891107450a06c795b1cba8f6c33a4454280`
-	Docker Version: 1.7.1
-	Virtual Size: 975.3 KB (975277 bytes)
-	v2 Blob: `sha256:20cdbe5b7a6f64396bcabde9b06c16a0b41e2c7fd39b28eff1ee3670a9f0516e`
-	v2 Content-Length: 220.4 KB (220377 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:29:17 GMT

#### `d7cbb60bc416f832c685b38578b77da5f3716cba15d4bcb45d850809a4c112eb`

```dockerfile
ENV LANG=C.UTF-8
```

-	Created: Wed, 09 Sep 2015 20:20:48 GMT
-	Parent Layer: `a7131b97316204530af26e42319aeda8ac44cd5ac2891e5dab45e16deb1e592d`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `d8ea027435229a8bdc09fa68db0043f1e2059ec889a3715c3e184553aee36da4`

```dockerfile
RUN gpg --keyserver ha.pool.sks-keyservers.net --recv-keys 97FC712E4C024BBEA48A61ED3A5CA953F73C700D
```

-	Created: Wed, 09 Sep 2015 20:53:54 GMT
-	Parent Layer: `d7cbb60bc416f832c685b38578b77da5f3716cba15d4bcb45d850809a4c112eb`
-	Docker Version: 1.7.1
-	Virtual Size: 12.6 KB (12606 bytes)
-	v2 Blob: `sha256:2fdbb7a55da29a948a258ac37edb8f60a95a8c9757555c009ac32bc5a50e4197`
-	v2 Content-Length: 6.7 KB (6737 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 21:55:10 GMT

#### `195c6cc147afc452d1a28053ccca813778128e777d0b7bb2adfbc07a78ea4f34`

```dockerfile
ENV PYTHON_VERSION=3.5.0
```

-	Created: Mon, 14 Sep 2015 20:18:06 GMT
-	Parent Layer: `d8ea027435229a8bdc09fa68db0043f1e2059ec889a3715c3e184553aee36da4`
-	Docker Version: 1.8.2
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `c45a3c61eb6340b5cffd6817830b073d9a46d814af70f1897802af2669597155`

```dockerfile
ENV PYTHON_PIP_VERSION=7.1.2
```

-	Created: Mon, 14 Sep 2015 20:18:06 GMT
-	Parent Layer: `195c6cc147afc452d1a28053ccca813778128e777d0b7bb2adfbc07a78ea4f34`
-	Docker Version: 1.8.2
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `dafed9a3b9ad76a0401a59d9be5b36b04ffda07f8332186027a59f1eb63e20a0`

```dockerfile
RUN set -x \
	&& mkdir -p /usr/src/python \
	&& curl -SL "https://www.python.org/ftp/python/${PYTHON_VERSION%%[a-z]*}/Python-$PYTHON_VERSION.tar.xz" -o python.tar.xz \
	&& curl -SL "https://www.python.org/ftp/python/${PYTHON_VERSION%%[a-z]*}/Python-$PYTHON_VERSION.tar.xz.asc" -o python.tar.xz.asc \
	&& gpg --verify python.tar.xz.asc \
	&& tar -xJC /usr/src/python --strip-components=1 -f python.tar.xz \
	&& rm python.tar.xz* \
	&& cd /usr/src/python \
	&& ./configure --enable-shared --enable-unicode=ucs4 \
	&& make -j$(nproc) \
	&& make install \
	&& ldconfig \
	&& pip3 install --no-cache-dir --upgrade --ignore-installed pip==$PYTHON_PIP_VERSION \
	&& find /usr/local \
		\( -type d -a -name test -o -name tests \) \
		-o \( -type f -a -name '*.pyc' -o -name '*.pyo' \) \
		-exec rm -rf '{}' + \
	&& rm -rf /usr/src/python
```

-	Created: Mon, 14 Sep 2015 20:20:17 GMT
-	Parent Layer: `c45a3c61eb6340b5cffd6817830b073d9a46d814af70f1897802af2669597155`
-	Docker Version: 1.8.2
-	Virtual Size: 81.5 MB (81545585 bytes)
-	v2 Blob: `sha256:4b321d03baef5c02926eb913e7b8445046b2f34b9a5274a1bdfddc1465efd2d1`
-	v2 Content-Length: 22.9 MB (22882542 bytes)
-	v2 Last-Modified: Mon, 14 Sep 2015 21:03:04 GMT

#### `4610a34007626cc1f90c5a13b2f56afcfac224f91a93ad0a8a1899803f348c96`

```dockerfile
RUN cd /usr/local/bin \
	&& ln -s easy_install-3.5 easy_install \
	&& ln -s idle3 idle \
	&& ln -s pydoc3 pydoc \
	&& ln -s python3 python \
	&& ln -s python-config3 python-config
```

-	Created: Mon, 14 Sep 2015 20:20:19 GMT
-	Parent Layer: `dafed9a3b9ad76a0401a59d9be5b36b04ffda07f8332186027a59f1eb63e20a0`
-	Docker Version: 1.8.2
-	Virtual Size: 48.0 B
-	v2 Blob: `sha256:936a15433462948c9831eafaf52ced79826f46f4be29b9eb79be1a4f4d832b83`
-	v2 Content-Length: 269.0 B
-	v2 Last-Modified: Mon, 14 Sep 2015 21:02:48 GMT

#### `b909084b799498656574bf948b5c0aa7312b850d862cafcfff43153d8b04269d`

```dockerfile
CMD ["python3"]
```

-	Created: Mon, 14 Sep 2015 20:20:19 GMT
-	Parent Layer: `4610a34007626cc1f90c5a13b2f56afcfac224f91a93ad0a8a1899803f348c96`
-	Docker Version: 1.8.2
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `149129bb37da6572b0ad2de18d1b0ff1be9cc4d39da6ddb2d737ae091ec70635`

```dockerfile
RUN mkdir -p /usr/src/app
```

-	Created: Mon, 14 Sep 2015 20:20:41 GMT
-	Parent Layer: `b909084b799498656574bf948b5c0aa7312b850d862cafcfff43153d8b04269d`
-	Docker Version: 1.8.2
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:31049d0c8154f9814719b0e6e6c8549a69bdd8ae77fbd526396508f145b40314`
-	v2 Content-Length: 127.0 B
-	v2 Last-Modified: Mon, 14 Sep 2015 21:04:38 GMT

#### `7890fe902afebc6dcb8b1c421b47ca45e6a2f2392dad5415ac631af9d471d441`

```dockerfile
WORKDIR /usr/src/app
```

-	Created: Mon, 14 Sep 2015 20:20:41 GMT
-	Parent Layer: `149129bb37da6572b0ad2de18d1b0ff1be9cc4d39da6ddb2d737ae091ec70635`
-	Docker Version: 1.8.2
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `129b85f95b6944dd0d5e5485da3fb0ea55b2941a0aef1c158aaeee8152e422d0`

```dockerfile
ONBUILD COPY requirements.txt /usr/src/app/
```

-	Created: Mon, 14 Sep 2015 20:20:41 GMT
-	Parent Layer: `7890fe902afebc6dcb8b1c421b47ca45e6a2f2392dad5415ac631af9d471d441`
-	Docker Version: 1.8.2
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `34f645e2664fc5bb198c4be71214d37e64f125a13f985fa5697264a9ccfe6c36`

```dockerfile
ONBUILD RUN pip install --no-cache-dir -r requirements.txt
```

-	Created: Mon, 14 Sep 2015 20:20:42 GMT
-	Parent Layer: `129b85f95b6944dd0d5e5485da3fb0ea55b2941a0aef1c158aaeee8152e422d0`
-	Docker Version: 1.8.2
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `952de03dc5df0c82183856f14ad22426850fa30ec9f1efd4c948ba60cc83d357`

```dockerfile
ONBUILD COPY . /usr/src/app
```

-	Created: Mon, 14 Sep 2015 20:20:42 GMT
-	Parent Layer: `34f645e2664fc5bb198c4be71214d37e64f125a13f985fa5697264a9ccfe6c36`
-	Docker Version: 1.8.2
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

## `python:3.5.0-slim`

```console
$ docker pull library/python@sha256:a566780a81186c067df4d0d150ced1e435e69d998846299da18de103a42b0582
```

-	Total Virtual Size: 218.5 MB (218504087 bytes)
-	Total v2 Content-Length: 79.7 MB (79655940 bytes)

### Layers (11)

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

#### `b724829f2124ff81839118c0bb053554742dae49bcf23847b98264867e4da862`

```dockerfile
RUN apt-get purge -y python.*
```

-	Created: Wed, 09 Sep 2015 20:26:09 GMT
-	Parent Layer: `8c00acfb017549e44d28098762c3e6296872a1ca9b90385855f1019d84bb0dac`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `dad2fc2df4957c05b555a45d00adeaaf624ccce5d9dd557ce4c8548ca40f39f0`

```dockerfile
ENV LANG=C.UTF-8
```

-	Created: Wed, 09 Sep 2015 20:26:10 GMT
-	Parent Layer: `b724829f2124ff81839118c0bb053554742dae49bcf23847b98264867e4da862`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `b4b1929946879d72f7304c436913698e312741961589842913329eb8d746fefa`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		libsqlite3-0 \
		libssl1.0.0 \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Wed, 09 Sep 2015 20:26:51 GMT
-	Parent Layer: `dad2fc2df4957c05b555a45d00adeaaf624ccce5d9dd557ce4c8548ca40f39f0`
-	Docker Version: 1.7.1
-	Virtual Size: 7.4 MB (7441496 bytes)
-	v2 Blob: `sha256:aebbd0bd409f97875c3b3bcf8f57e315ba2ef8d3c4a54f81a7f71cfcf80bf4c9`
-	v2 Content-Length: 3.3 MB (3316296 bytes)
-	v2 Last-Modified: Fri, 11 Sep 2015 00:01:36 GMT

#### `c62feeae66a9b278cc147476ae5ee822b4595790c9b96733a6879ade412606b5`

```dockerfile
RUN gpg --keyserver ha.pool.sks-keyservers.net --recv-keys 97FC712E4C024BBEA48A61ED3A5CA953F73C700D
```

-	Created: Wed, 09 Sep 2015 20:58:44 GMT
-	Parent Layer: `b4b1929946879d72f7304c436913698e312741961589842913329eb8d746fefa`
-	Docker Version: 1.7.1
-	Virtual Size: 12.6 KB (12606 bytes)
-	v2 Blob: `sha256:5ed1876c3a86512cc94dd5c18bf7f6d27b5d69f05a21c0c675ef0c695cbf7135`
-	v2 Content-Length: 6.7 KB (6738 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 22:00:10 GMT

#### `ea0c98946c1b62e19651531bc1876f4292e472369915d56ac0c48311471bfd4e`

```dockerfile
ENV PYTHON_VERSION=3.5.0
```

-	Created: Mon, 14 Sep 2015 20:21:05 GMT
-	Parent Layer: `c62feeae66a9b278cc147476ae5ee822b4595790c9b96733a6879ade412606b5`
-	Docker Version: 1.8.2
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `085b5540b762ce8bb2267677ddbb96640824efe108c86f797f8a25ba00ebfe1e`

```dockerfile
ENV PYTHON_PIP_VERSION=7.1.2
```

-	Created: Mon, 14 Sep 2015 20:21:05 GMT
-	Parent Layer: `ea0c98946c1b62e19651531bc1876f4292e472369915d56ac0c48311471bfd4e`
-	Docker Version: 1.8.2
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `eb569c4fc4a8de80d7b63542e10a7bdddbe6d935d2caedfd004e7becd515714b`

```dockerfile
RUN set -x \
	&& buildDeps=' \
		curl \
		gcc \
		libbz2-dev \
		libc6-dev \
		libncurses-dev \
		libreadline-dev \
		libsqlite3-dev \
		libssl-dev \
		make \
		xz-utils \
		zlib1g-dev \
	' \
	&& apt-get update && apt-get install -y $buildDeps --no-install-recommends && rm -rf /var/lib/apt/lists/* \
	&& mkdir -p /usr/src/python \
	&& curl -SL "https://www.python.org/ftp/python/${PYTHON_VERSION%%[a-z]*}/Python-$PYTHON_VERSION.tar.xz" -o python.tar.xz \
	&& curl -SL "https://www.python.org/ftp/python/${PYTHON_VERSION%%[a-z]*}/Python-$PYTHON_VERSION.tar.xz.asc" -o python.tar.xz.asc \
	&& gpg --verify python.tar.xz.asc \
	&& tar -xJC /usr/src/python --strip-components=1 -f python.tar.xz \
	&& rm python.tar.xz* \
	&& cd /usr/src/python \
	&& ./configure --enable-shared --enable-unicode=ucs4 \
	&& make -j$(nproc) \
	&& make install \
	&& ldconfig \
	&& pip3 install --no-cache-dir --upgrade --ignore-installed pip==$PYTHON_PIP_VERSION \
	&& find /usr/local \
		\( -type d -a -name test -o -name tests \) \
		-o \( -type f -a -name '*.pyc' -o -name '*.pyo' \) \
		-exec rm -rf '{}' + \
	&& apt-get purge -y --auto-remove $buildDeps \
	&& rm -rf /usr/src/python
```

-	Created: Mon, 14 Sep 2015 20:24:16 GMT
-	Parent Layer: `085b5540b762ce8bb2267677ddbb96640824efe108c86f797f8a25ba00ebfe1e`
-	Docker Version: 1.8.2
-	Virtual Size: 85.9 MB (85890806 bytes)
-	v2 Blob: `sha256:ebea2ff91798e0254f76625b75d35ddeb7f87933ee3f52cfe314ee25f63e0db3`
-	v2 Content-Length: 25.0 MB (24972734 bytes)
-	v2 Last-Modified: Mon, 14 Sep 2015 21:05:55 GMT

#### `08bac93d78e3936cb17ca284c7bf319175870cd11cef7e211c0cd89ae96e2ee8`

```dockerfile
RUN cd /usr/local/bin \
	&& ln -s easy_install-3.5 easy_install \
	&& ln -s idle3 idle \
	&& ln -s pydoc3 pydoc \
	&& ln -s python3 python \
	&& ln -s python-config3 python-config
```

-	Created: Mon, 14 Sep 2015 20:24:18 GMT
-	Parent Layer: `eb569c4fc4a8de80d7b63542e10a7bdddbe6d935d2caedfd004e7becd515714b`
-	Docker Version: 1.8.2
-	Virtual Size: 48.0 B
-	v2 Blob: `sha256:c744ada63883aee24e1c41450cd929fe5fee390a87c901f5233429c6a8b62c8d`
-	v2 Content-Length: 272.0 B
-	v2 Last-Modified: Mon, 14 Sep 2015 21:05:38 GMT

#### `0519635b82aecb3816c52777a411973abc909355c476d371fff71041c9c63bcc`

```dockerfile
CMD ["python3"]
```

-	Created: Mon, 14 Sep 2015 20:24:19 GMT
-	Parent Layer: `08bac93d78e3936cb17ca284c7bf319175870cd11cef7e211c0cd89ae96e2ee8`
-	Docker Version: 1.8.2
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

## `python:3.5-slim`

```console
$ docker pull library/python@sha256:55017b872a3d2184d8745fba80d2318f7de7e5953aa0647f86bfce4fc6611354
```

-	Total Virtual Size: 218.5 MB (218504087 bytes)
-	Total v2 Content-Length: 79.7 MB (79655940 bytes)

### Layers (11)

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

#### `b724829f2124ff81839118c0bb053554742dae49bcf23847b98264867e4da862`

```dockerfile
RUN apt-get purge -y python.*
```

-	Created: Wed, 09 Sep 2015 20:26:09 GMT
-	Parent Layer: `8c00acfb017549e44d28098762c3e6296872a1ca9b90385855f1019d84bb0dac`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `dad2fc2df4957c05b555a45d00adeaaf624ccce5d9dd557ce4c8548ca40f39f0`

```dockerfile
ENV LANG=C.UTF-8
```

-	Created: Wed, 09 Sep 2015 20:26:10 GMT
-	Parent Layer: `b724829f2124ff81839118c0bb053554742dae49bcf23847b98264867e4da862`
-	Docker Version: 1.7.1
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `b4b1929946879d72f7304c436913698e312741961589842913329eb8d746fefa`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		libsqlite3-0 \
		libssl1.0.0 \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Wed, 09 Sep 2015 20:26:51 GMT
-	Parent Layer: `dad2fc2df4957c05b555a45d00adeaaf624ccce5d9dd557ce4c8548ca40f39f0`
-	Docker Version: 1.7.1
-	Virtual Size: 7.4 MB (7441496 bytes)
-	v2 Blob: `sha256:aebbd0bd409f97875c3b3bcf8f57e315ba2ef8d3c4a54f81a7f71cfcf80bf4c9`
-	v2 Content-Length: 3.3 MB (3316296 bytes)
-	v2 Last-Modified: Fri, 11 Sep 2015 00:01:36 GMT

#### `c62feeae66a9b278cc147476ae5ee822b4595790c9b96733a6879ade412606b5`

```dockerfile
RUN gpg --keyserver ha.pool.sks-keyservers.net --recv-keys 97FC712E4C024BBEA48A61ED3A5CA953F73C700D
```

-	Created: Wed, 09 Sep 2015 20:58:44 GMT
-	Parent Layer: `b4b1929946879d72f7304c436913698e312741961589842913329eb8d746fefa`
-	Docker Version: 1.7.1
-	Virtual Size: 12.6 KB (12606 bytes)
-	v2 Blob: `sha256:5ed1876c3a86512cc94dd5c18bf7f6d27b5d69f05a21c0c675ef0c695cbf7135`
-	v2 Content-Length: 6.7 KB (6738 bytes)
-	v2 Last-Modified: Wed, 09 Sep 2015 22:00:10 GMT

#### `ea0c98946c1b62e19651531bc1876f4292e472369915d56ac0c48311471bfd4e`

```dockerfile
ENV PYTHON_VERSION=3.5.0
```

-	Created: Mon, 14 Sep 2015 20:21:05 GMT
-	Parent Layer: `c62feeae66a9b278cc147476ae5ee822b4595790c9b96733a6879ade412606b5`
-	Docker Version: 1.8.2
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `085b5540b762ce8bb2267677ddbb96640824efe108c86f797f8a25ba00ebfe1e`

```dockerfile
ENV PYTHON_PIP_VERSION=7.1.2
```

-	Created: Mon, 14 Sep 2015 20:21:05 GMT
-	Parent Layer: `ea0c98946c1b62e19651531bc1876f4292e472369915d56ac0c48311471bfd4e`
-	Docker Version: 1.8.2
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT

#### `eb569c4fc4a8de80d7b63542e10a7bdddbe6d935d2caedfd004e7becd515714b`

```dockerfile
RUN set -x \
	&& buildDeps=' \
		curl \
		gcc \
		libbz2-dev \
		libc6-dev \
		libncurses-dev \
		libreadline-dev \
		libsqlite3-dev \
		libssl-dev \
		make \
		xz-utils \
		zlib1g-dev \
	' \
	&& apt-get update && apt-get install -y $buildDeps --no-install-recommends && rm -rf /var/lib/apt/lists/* \
	&& mkdir -p /usr/src/python \
	&& curl -SL "https://www.python.org/ftp/python/${PYTHON_VERSION%%[a-z]*}/Python-$PYTHON_VERSION.tar.xz" -o python.tar.xz \
	&& curl -SL "https://www.python.org/ftp/python/${PYTHON_VERSION%%[a-z]*}/Python-$PYTHON_VERSION.tar.xz.asc" -o python.tar.xz.asc \
	&& gpg --verify python.tar.xz.asc \
	&& tar -xJC /usr/src/python --strip-components=1 -f python.tar.xz \
	&& rm python.tar.xz* \
	&& cd /usr/src/python \
	&& ./configure --enable-shared --enable-unicode=ucs4 \
	&& make -j$(nproc) \
	&& make install \
	&& ldconfig \
	&& pip3 install --no-cache-dir --upgrade --ignore-installed pip==$PYTHON_PIP_VERSION \
	&& find /usr/local \
		\( -type d -a -name test -o -name tests \) \
		-o \( -type f -a -name '*.pyc' -o -name '*.pyo' \) \
		-exec rm -rf '{}' + \
	&& apt-get purge -y --auto-remove $buildDeps \
	&& rm -rf /usr/src/python
```

-	Created: Mon, 14 Sep 2015 20:24:16 GMT
-	Parent Layer: `085b5540b762ce8bb2267677ddbb96640824efe108c86f797f8a25ba00ebfe1e`
-	Docker Version: 1.8.2
-	Virtual Size: 85.9 MB (85890806 bytes)
-	v2 Blob: `sha256:ebea2ff91798e0254f76625b75d35ddeb7f87933ee3f52cfe314ee25f63e0db3`
-	v2 Content-Length: 25.0 MB (24972734 bytes)
-	v2 Last-Modified: Mon, 14 Sep 2015 21:05:55 GMT

#### `08bac93d78e3936cb17ca284c7bf319175870cd11cef7e211c0cd89ae96e2ee8`

```dockerfile
RUN cd /usr/local/bin \
	&& ln -s easy_install-3.5 easy_install \
	&& ln -s idle3 idle \
	&& ln -s pydoc3 pydoc \
	&& ln -s python3 python \
	&& ln -s python-config3 python-config
```

-	Created: Mon, 14 Sep 2015 20:24:18 GMT
-	Parent Layer: `eb569c4fc4a8de80d7b63542e10a7bdddbe6d935d2caedfd004e7becd515714b`
-	Docker Version: 1.8.2
-	Virtual Size: 48.0 B
-	v2 Blob: `sha256:c744ada63883aee24e1c41450cd929fe5fee390a87c901f5233429c6a8b62c8d`
-	v2 Content-Length: 272.0 B
-	v2 Last-Modified: Mon, 14 Sep 2015 21:05:38 GMT

#### `0519635b82aecb3816c52777a411973abc909355c476d371fff71041c9c63bcc`

```dockerfile
CMD ["python3"]
```

-	Created: Mon, 14 Sep 2015 20:24:19 GMT
-	Parent Layer: `08bac93d78e3936cb17ca284c7bf319175870cd11cef7e211c0cd89ae96e2ee8`
-	Docker Version: 1.8.2
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Fri, 27 Mar 2015 17:18:47 GMT
