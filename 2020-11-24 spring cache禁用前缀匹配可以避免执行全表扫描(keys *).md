## SpringCache中通过禁用前缀匹配来避免全表扫描(keys *)

- 入口在这里：

```
org.springframework.cache.interceptor.CacheAspectSupport#processCacheEvicts
```

![1-1](./img/1-1.jpg)

![1-2](./img/1-2.jpg)

![1-3](./img/1-3.jpg)

![1-4](./img/1-4.jpg)

![1-5](./img/1-5.jpg)

![1-6](./img/1-6.jpg)

![1-7](./img/1-7.jpg)

![1-8](./img/1-8.jpg)

以上就是小编为大家带来的内容啦