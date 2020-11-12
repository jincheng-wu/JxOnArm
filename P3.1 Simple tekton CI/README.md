# P3.1 Simple tekton CI

P3.1是一个对于lighthouse对接tekton的简单测试。

## 操作流程

依照lighthouse官方文档，安装部署lighthouse。具体文档参考https://github.com/jenkins-x/lighthouse#installing。安装完成后，利用github的webhook功能，测试lighthouse webhook是否正常运行。

依照tekton官方文档，安装部署tekton https://github.com/tektoncd/pipeline/blob/master/docs/install.md 或依照jenkins-x团队提供的charts，部署tekton https://github.com/jenkins-x-charts/tekton。安装完成后，通过简单的hello-world，测试tekton是否正常运行。

两者全部部署完成后，参考lighthouse官方教程，配置对接。

https://github.com/jenkins-x/lighthouse/blob/master/docs/install_lighthouse_with_tekton.md

