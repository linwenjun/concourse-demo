```
fly -t lite login -c http://ec2-52-80-168-233.cn-north-1.compute.amazonaws.com.cn:8080

# 默认登录信息
concourse
changeme

./fly -t lite set-pipeline -p busybox -c busybox.yml
```

