# BBR-G
A BBR congestion control variant 

The steps to run BBR-G are as follows:
1. Install, configure, and build ns-3-dev using https://github.com/nsnam/ns-3-dev-git
2. Replace the scratch folder of BBR-G with the installed ns-3-dev
3. Replace the tcp-bbr.cc, tcp-bbr.h, tcp-socket-base.cc, tcp-socket-base.h, tcp-socket-state.cc, and tcp-socket-state.h files of BBR-G with the ns-3-dev/src/internet/model/
4. Copy the tcp-bbr-example_bbrg.cc to scratch folder of ns-3 dev
5. build the ns-3-dev
