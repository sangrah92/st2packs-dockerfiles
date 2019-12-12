FROM stackstorm/st2:3.0dev

ONBUILD ARG PACKS
ONBUILD RUN docker build --build-arg  PACKS="https://PRIVATE-TOKEN:aEJFW8JRRZuaPt66ZYrt@scm.dimensiondata.com/vnext/StackStorm-Packs/ntt_network_patch.git \
        https://PRIVATE-TOKEN:aEJFW8JRRZuaPt66ZYrt@scm.dimensiondata.com/vnext/StackStorm-Packs/ntt_vmware.git \
  	https://PRIVATE-TOKEN:aEJFW8JRRZuaPt66ZYrt@scm.dimensiondata.com/vnext/StackStorm-Packs/ntt_o365.git \
  	https://PRIVATE-TOKEN:aEJFW8JRRZuaPt66ZYrt@scm.dimensiondata.com/vnext/StackStorm-Packs/ntt_checkpoint.git \
  	https://PRIVATE-TOKEN:aEJFW8JRRZuaPt66ZYrt@scm.dimensiondata.com/vnext/StackStorm-Packs/ntt_ods.git \
  	https://PRIVATE-TOKEN:aEJFW8JRRZuaPt66ZYrt@scm.dimensiondata.com/vnext/StackStorm-Packs/ntt_utils_json.git \
  	https://PRIVATE-TOKEN:aEJFW8JRRZuaPt66ZYrt@scm.dimensiondata.com/vnext/StackStorm-Packs/ntt_database_oracle.git \
  	https://PRIVATE-TOKEN:aEJFW8JRRZuaPt66ZYrt@scm.dimensiondata.com/vnext/StackStorm-Packs/ntt_windows.git \  
  	https://PRIVATE-TOKEN:aEJFW8JRRZuaPt66ZYrt@scm.dimensiondata.com/vnext/StackStorm-Packs/ntt_voice_cisco.git \
  	https://PRIVATE-TOKEN:aEJFW8JRRZuaPt66ZYrt@scm.dimensiondata.com/vnext/StackStorm-Packs/ntt_vnext_sample_pack.git \
  	https://PRIVATE-TOKEN:aEJFW8JRRZuaPt66ZYrt@scm.dimensiondata.com/vnext/StackStorm-Packs/ntt_unix.git \
	https://PRIVATE-TOKEN:aEJFW8JRRZuaPt66ZYrt@scm.dimensiondata.com/vnext/StackStorm-Packs/ntt_storage.git \
	https://PRIVATE-TOKEN:aEJFW8JRRZuaPt66ZYrt@scm.dimensiondata.com/vnext/StackStorm-Packs/ntt_pfizer.git \
	https://PRIVATE-TOKEN:aEJFW8JRRZuaPt66ZYrt@scm.dimensiondata.com/vnext/StackStorm-Packs/ntt_network_cisco.git \
	https://PRIVATE-TOKEN:aEJFW8JRRZuaPt66ZYrt@scm.dimensiondata.com/vnext/StackStorm-Packs/ntt_network.git	\
	https://PRIVATE-TOKEN:aEJFW8JRRZuaPt66ZYrt@scm.dimensiondata.com/vnext/StackStorm-Packs/ntt_msdc.git \
	https://PRIVATE-TOKEN:aEJFW8JRRZuaPt66ZYrt@scm.dimensiondata.com/vnext/StackStorm-Packs/ntt_ivr.git	\
	https://PRIVATE-TOKEN:aEJFW8JRRZuaPt66ZYrt@scm.dimensiondata.com/vnext/StackStorm-Packs/ntt_itsm.git \
	https://PRIVATE-TOKEN:aEJFW8JRRZuaPt66ZYrt@scm.dimensiondata.com/vnext/StackStorm-Packs/ntt_insite_msen.git" -t stackstorms/custom_st2packs:latest .



