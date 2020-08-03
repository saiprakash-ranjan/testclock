# testclock

On target:  

mkdir -p /root/mem-devutils  
cp mem.py /root/mem-devutils/
export PYTHONPATH=/root/mem-devutils/:$PYTHONPATH  
cp testclock.py /usr/bin/testclock  
cp mem.py /usr/bin/mem  
  
Reference: https://chromium.googlesource.com/chromiumos/overlays/board-overlays/+/refs/heads/master/chipset-qc845/dev-util/testclock/files/testclock.py  
