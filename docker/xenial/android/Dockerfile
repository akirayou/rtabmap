# Image: introlab3it/rtabmap:android-deps

FROM introlab3it/rtabmap

ENV ANDROID_HOME=/opt/android-sdk
ENV ANDROID_NATIVE_API_LEVEL=android-19
ENV ANDROID_NDK=/opt/android-ndk-r14
ENV PATH=$PATH:/opt/android-sdk/tools:/opt/android-sdk/platform-tools:/opt/android-ndk-r14

WORKDIR /root/
ADD install_deps.bash /root/install_deps.bash
RUN chmod +x install_deps.bash
RUN /bin/bash -c "./install_deps.bash"
