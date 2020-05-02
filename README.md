# .bashrc
# Como Usar
mv ~/.bashrc ~/.bashrc_bk && \
wget -O ~/.bashrc https://raw.githubusercontent.com/PAR4NA/.bashrc/master/.bashrc


# Add Landscape
apt-get update -y && \
apt-get install landscape-common -y && \
mv /root/.bashrc /root/.bashrc_bk && \
wget -O /root/.bashrc https://raw.githubusercontent.com/PAR4NA/.bashrc/master/.bashrc
