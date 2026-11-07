FROM debian:trixie@sha256:9c6e381421d0f48d1b8133e573f33c185ee16cbf505eda9c4a8a4791b25ea8a6
COPY stretch_deps.sh /deps.sh
RUN /deps.sh && rm /deps.sh
VOLUME /wallycore
ENV JAVA_HOME=/usr/lib/jvm/java-1.8.0-openjdk-amd64
ENV ANDROID_NDK=/opt/android-ndk-r14b
