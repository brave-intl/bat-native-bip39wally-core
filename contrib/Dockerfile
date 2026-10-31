FROM debian:trixie@sha256:2dc419c6d7fe3dad0a2f9fd469c34cc90b0f9ba642d8fde837fe3d7d34a0e7f1
COPY stretch_deps.sh /deps.sh
RUN /deps.sh && rm /deps.sh
VOLUME /wallycore
ENV JAVA_HOME=/usr/lib/jvm/java-1.8.0-openjdk-amd64
ENV ANDROID_NDK=/opt/android-ndk-r14b
