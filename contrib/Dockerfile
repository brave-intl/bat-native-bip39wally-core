FROM debian:trixie@sha256:f324c7ff54321e8d9c588493a20244965938ce0aa50bbd1022d38010e9ffc4b1
COPY stretch_deps.sh /deps.sh
RUN /deps.sh && rm /deps.sh
VOLUME /wallycore
ENV JAVA_HOME=/usr/lib/jvm/java-1.8.0-openjdk-amd64
ENV ANDROID_NDK=/opt/android-ndk-r14b
