# Next Generation Testing Tools

考虑到未来DQL（Defect Query Language）设计和应用部署的方便性，正在将持久层从Hibernate迁移到MyBatis，并用SpringBoot替换SpringMVC。 敬请期待新版本！

AngularJS 4, SockJS, SpringMVC, Hibernate, MySQL

### Quick start
```bash
Setup Tomcat8 and Mysql5.x server
Import database from xdoc/ngtesting-dump.sql
Deploy webapp to path /platform in tomcat
Open http://localhost:8080/platform to test backend web and database server works well
Open chrome browser and goto http://localhost:8080/platform/client
If you use different tomcat path, search and replace below service url to your own in main.*.js
- http://localhost:8080/platform/
```

### Test Project
<img src="https://raw.githubusercontent.com/aaronchen2k/ngtesting-platform/master/xdoc/capture/project_view.jpg" width="800px" style="margin: 10px auto;">

### Test Case
<img src="https://raw.githubusercontent.com/aaronchen2k/ngtesting-platform/master/xdoc/capture/case_edit.jpg" width="800px" style="margin: 10px auto;">

### Test Execution
<img src="https://raw.githubusercontent.com/aaronchen2k/ngtesting-platform/master/xdoc/capture/case_exe.jpg" width="800px" style="margin: 10px auto;">

### Test Plan
<img src="https://raw.githubusercontent.com/aaronchen2k/ngtesting-platform/master/xdoc/capture/plan_exe_result.jpg" width="800px" style="margin: 10px auto;">
<img src="https://raw.githubusercontent.com/aaronchen2k/ngtesting-platform/master/xdoc/capture/plan_exe_progress.jpg" width="800px" style="margin: 10px auto;">
<img src="https://raw.githubusercontent.com/aaronchen2k/ngtesting-platform/master/xdoc/capture/plan_exe_process.jpg" width="800px" style="margin: 10px auto;">
<img src="https://raw.githubusercontent.com/aaronchen2k/ngtesting-platform/master/xdoc/capture/plan_exe_process_by_user.jpg" width="800px" style="margin: 10px auto;">

### Licenses

All source code is licensed under the [GPLv3 License](LICENSE.md).