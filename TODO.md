1. Revert the update cooldown to 60s.  companion.py 'holdoff' 93c4f85b3c4c25216ec5f5f62754671b9d8d04e2
1. Revert the appname et al changes: 58f9f790a817fff95df239a3ae1f677c59e10ebd
1. Revert forcing bad CLIENT_ID: 3a8e317f09b390d5dee5602011f1567692bef225
1. Revert the "always use a log file" change. 4a3eb98bf4b93313de48effe208f8004448940a2
1. Test all data senders:
	1. EDDN
		1. Revert forcing "is_beta = True" in plugins/eddn.py e54226cbabf68d9e18e2d70b241ce667a788c00e
		1. Station Data
		1. System and Scan data
	1. EDSM
	1. Inara
	1. EDDB
	1. Coriolis
	1. ED shipyard
