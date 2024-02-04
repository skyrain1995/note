
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

![](assets/Pasted%20image%2020240204160556.png)

phone