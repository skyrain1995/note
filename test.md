
```java
@Service  
@Lazy  
@Slf4j  
public class UserService extends GzoneServiceImpl<UserMapper, User> {  
  
    public boolean updateAge(User user) {  
        return baseMapper.updateAge(user);  
    }  
}
```

![[5x3b3xpusp46hpu.jpeg]]

test git
