- 大 key 数据拆解
- 常用分级缓存
	* localcache -> redis | rpc
	* async cache ，会定时请求数据源，数据会一直保持缓存状态，没有回源能力