FROM ghcr.io/commaai/openpilot-base:latest

# remove gitconfig if exists, since its gonna be replaced by host one
RUN rm -f /root/.gitconfig
RUN apt update && apt install -y vim net-tools usbutils htop ripgrep
RUN pip install ipython jupyter jupyterlab
RUN sudo apt install -y cmake build-essential
RUN sudo apt install -y lsb-core
RUN sudo apt install -y can-utils
#RUN sudo apt install -y qtcreator qtbase5-dev qt5-qmake libqt5serialbus5-dev libqt5svg5-dev qtdeclarative5-dev
