# hdbpp-cm
Tango device server able to export HDB++ Configuration Manager and 
HDB++ Event Subscriber devices.

## building
git clone --recursive http://github.com/tango-controls/hdbpp-cm-es.git  
cd hdbpp-cm-es  
export TANGO_DIR=/usr/local/tango-9.2.5a  
export OMNIORB_DIR=/usr/local/omniorb-4.2.1  
export ZMQ_DIR=/usr/local/zeromq-4.0.7  
make
