### Steps to run python and .cc files in command line

* Download ns3-allinone
* cd ns3
* ./waf build
* ./waf configure --enable-examples
* ./waf --run program name with path


### For example to run simple-global-routing.cc file in ns3/examples/routing folder type this command:
* ./waf --run examples/routing/simple-global-routing

### For example to run simple-global-routing.py file in ns3/examples/routing folder type this command:
* ./waf --pyrun examples/routing/simple-global-routing.py
