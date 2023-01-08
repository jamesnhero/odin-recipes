FROM ubuntu

ENV TZ=Australia/Melbourne
RUN apt update && apt upgrade -y && apt install software-properties-common -y && add-apt-repository ppa:git-core/ppa -y && apt update && apt install git -y

# ARG USERNAME=vscode
# ARG USER_UID=1000
# ARG USER_GID=$USER_UID

# RUN groupadd --gid $USER_GID $USERNAME \
#     && useradd --uid $USER_UID --gid $USER_GID -m $USERNAME
    
# USER $USERNAME