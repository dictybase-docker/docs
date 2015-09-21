The Dockerfiles and associated scripts are licensed under the [Apache License 2.0](http://www.apache.org/licenses/LICENSE-2.0.html).

Licenses for the products installed within the images are as follows:

-	[IBM WebSphere Application Server](https://public.dhe.ibm.com/ibmdl/export/pub/software/websphere/wasdev/downloads/wlp/8.5.5.5/lafiles/runtime/en.html) in the `latest`/`8.5.5` image (International License Agreement for Non-Warranted Programs)
-	[IBM WebSphere Application Server Liberty v9 Beta with Java EE 7](https://public.dhe.ibm.com/ibmdl/export/pub/software/websphere/wasdev/downloads/wlp/beta/lafiles/en.html) in the `beta` image (International License Agreement for Early Release of Programs)

The product licenses associated with an image can be displayed by specifying the `LICENSE=view` environment variable as described above. Note that these licenses do not permit further distribution and that the terms for WebSphere Application Server in the `latest`/`8.5.5` image restrict usage to a developer machine or build server only, or subject to a maximum 2 gigabyte heap usage across all instances. Instructions are available to enable entitled customers to [upgrade](https://github.com/WASdev/ci.docker/tree/master/websphere-liberty/8.5.5/production-upgrade) the Docker Hub image for production use or [build](https://github.com/WASdev/ci.docker/tree/master/websphere-liberty/8.5.5/production-install) their own production licensed image.
