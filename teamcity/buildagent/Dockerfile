ENV NODE_VERSION 6.10.3 

# install dotnet core SDK
RUN sh -c 'echo "deb [arch=amd64] https://apt-mo.trafficmanager.net/repos/dotnet-release/ xenial main" > /etc/apt/sources.list.d/dotnetdev.list' && \ 
apt-key adv --keyserver hkp://keyserver.ubuntu.com:80 --recv-keys 417A0893 && \ 
apt-get update && \ 
apt-get install dotnet-sdk-2.0.0 -y
