## SpringCache中通过禁用前缀匹配来避免全表扫描(keys *)

- 入口在这里：

```
org.springframework.cache.interceptor.CacheAspectSupport#processCacheEvicts
```
