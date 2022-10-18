# 治理工具

---

UBSI-Admin是一个高度集成化的UBSI微服务治理工具，主要的功能包括：

<table>
  <tr>
    <td rowspan="4">运行监控</td>
    <td>服务发现</td>
    <td>微服务/过滤器的自动发现及运行监控</td>
  </tr>
  <tr>
    <td>容器发现</td>
    <td>运行容器的自动发现及配置管理</td>
  </tr>
  <tr>
    <td>WebApp发现</td>
    <td>WebApp的自动发现及配置管理</td>
  </tr>
  <tr>
    <td>手动发现</td>
    <td>手工标记并管理服务容器/WebApp</td>
  </tr>
  <tr>
    <td rowspan="2">服务仓库</td>
    <td>微服务查询</td>
    <td>在仓库中注册的微服务的查询及管理</td>
  </tr>
  <tr>
    <td>JAR包管理</td>
    <td>从Maven仓库中导入的微服务JAR包的管理</td>
  </tr>
  <tr>
    <td rowspan="2">测试管理</td>
    <td>功能测试</td>
    <td>功能测试用例/测试任务的管理</td>
  </tr>
  <tr>
    <td>性能测试</td>
    <td>性能测试用例/测试任务的管理</td>
  </tr>
  <tr>
    <td rowspan="3">日志分析</td>
    <td>服务访问日志</td>
    <td>全局的服务访问日志分析、访问链路跟踪</td>
  </tr>
  <tr>
    <td>服务运行日志</td>
    <td>全局的服务运行日志分析</td>
  </tr>
  <tr>
    <td>日志过滤器设置</td>
    <td>设置过滤特定日志数据的过滤器</td>
  </tr>
  <tr>
    <td rowspan="10">网关管理</td>
    <td>网关运行监控</td>
    <td>网关的运行实例监控以及访问统计</td>
  </tr>
  <tr>
    <td>应用管理</td>
    <td>应用信息及访问密钥的管理</td>
  </tr>
  <tr>
    <td>远程主机管理</td>
    <td>应用所在主机的访问权限控制</td>
  </tr>
  <tr>
    <td>接口访问管理</td>
    <td>应用对服务接口的访问权限控制</td>
  </tr>
  <tr>
    <td>路由规则管理</td>
    <td>应用对服务的访问路由设置</td>
  </tr>
  <tr>
    <td>限流规则管理</td>
    <td>应用对服务的访问流量的限制规则</td>
  </tr>
  <tr>
    <td>请求转发规则管理</td>
    <td>请求流量的转发或镜像</td>
  </tr>
  <tr>
    <td>服务仿真数据管理</td>
    <td>服务接口对应用的数据仿真</td>
  </tr>
  <tr>
    <td>接口缓存规则管理</td>
    <td>应用访问接口的结果缓存规则</td>
  </tr>
  <tr>
    <td>服务访问日志管理</td>
    <td>应用对接口的访问日志记录规则</td>
  </tr>
  <tr>
    <td rowspan="2">任务调度</td>
    <td>代码片段</td>
    <td>任务需要包含的公共脚本代码的管理</td>
  </tr>
  <tr>
    <td>任务管理</td>
    <td>定时任务的设置及运行监控</td>
  </tr>
  <tr>
    <td rowspan="3">Web服务脚本</td>
    <td>脚本管理</td>
    <td>作为rest-api的脚本代码管理</td>
  </tr>
  <tr>
    <td>脚本权限</td>
    <td>脚本代码的执行权限管理</td>
  </tr>
  <tr>
    <td>目录管理</td>
    <td>文件服务rest-api的目录映射管理</td>
  </tr>
  <tr>
    <td rowspan="3">服务流程编排</td>
    <td>事件管理</td>
    <td>用于激活流程的事件定义</td>
  </tr>
  <tr>
    <td>流程定义</td>
    <td>可视化的服务流程编排工具</td>
  </tr>
  <tr>
    <td>流程执行实例</td>
    <td>可视化的流程执行过程跟踪</td>
  </tr>
  <tr>
    <td>事务监控</td>
    <td></td>
    <td>全局/分支事务的执行监控</td>
  </tr>
</table>


> UBSI-Admin治理工具目前只在UBSI正式版本中提供，详见 https://ubsi-home.github.io/docs/admin/readme.html



