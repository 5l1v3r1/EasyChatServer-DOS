# EasyChatServer-DOS (CVE-2019-20502)
Easy Chat Server Version 3.1 (Remote DOS)

```
body2.ghp receives a variable called message, which allows a buffer to overflow to produce an application block

1- First socket with (GET) generates a valid session to then do step 2.
2- Second we send (POST) the data message in the variable to crashear the application.
```

<p align="center">
  <img src="https://github.com/s1kr10s/EasyChatServer-DOS/blob/master/poc.png" width="600" alt="accessibility text">
</p>
<br>

Video https://www.youtube.com/watch?v=BlOi_-OxOYc

## Exploiting.CL
