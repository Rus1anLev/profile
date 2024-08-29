```cd ~/ && git clone https://github.com/Rus1anLev/profile.git && tee -a ~/.bashrc << END
if [ -f ~/profile/.tool ]; then
    . ~/profile/.tool
fi
END```
