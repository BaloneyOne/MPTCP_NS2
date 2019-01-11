# MPTCP_NS2
The simple implementation of MPTCP on ns-2.35

All the '.patch' file should be used on original ns-2.35.
COMMAND:
1. put '.patch' file outside ns-2.35 folder, but inside 'ns-allinone-2.35' folder.
2. type 'patch -p1 --ignore-whitespace -i mptcp_v1.0.patch'
3. the following changes of files will be list if previous operations are done properly
  patching file ns-2.35/apps/app.cc
  patching file ns-2.35/apps/app.h
  patching file ns-2.35/apps/mptcp.cc
  patching file ns-2.35/apps/mptcp.h
  patching file ns-2.35/classifier/classifier.h
  patching file ns-2.35/classifier/classifier-mpath.cc
  patching file ns-2.35/common/agent.cc
  patching file ns-2.35/common/agent.h
  patching file ns-2.35/Makefile.in
  patching file ns-2.35/mobile/god.cc
  patching file ns-2.35/mobile/god.h
  patching file ns-2.35/queue/drop-tail.cc
  patching file ns-2.35/queue/drop-tail.h
  patching file ns-2.35/tcp/tcp.cc
  patching file ns-2.35/tcp/tcp-fack.cc
  patching file ns-2.35/tcp/tcp-fs.cc
  patching file ns-2.35/tcp/tcp.h
  patching file ns-2.35/tcp/tcp-linux.cc
  patching file ns-2.35/tcp/tcp-newreno.cc
  patching file ns-2.35/tcp/tcp-sink.cc
  patching file ns-2.35/tcp/tcp-sink.h
