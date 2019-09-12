FROM mono:6.0-slim

RUN apt-get update \
  && apt-get install -y binutils curl mono-devel ca-certificates-mono fsharp mono-vbnc nuget referenceassemblies-pcl mono-xsp4  \
  && rm -rf /var/lib/apt/lists/* /tmp/*