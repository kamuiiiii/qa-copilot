# qa 环境

> 一个文件 = 一个环境 = 这个环境下的一整组被测站。一次测试选定一个环境（读这一个文件），
> 在其中作用于一个或多个站。新增站就往下表加一行。
>
> `id` 用作 AC 里的 `@site` 标注、session 后缀（`$SID-<id>`）、截图前缀。
> 角色（操作端 / 观察端）是每次测试才定的，**不写在这里**，写进该 run 的 `ac.md`。

- **环境**: qa（日常测试环境；另有 uat）

## 站

| id              | URL                                      | 说明     |
| --------------- | ---------------------------------------- | -------- |
| dispatch-portal | https://dispatch-portal.foodtruck-qa.com | 派单门户 |
| order           | https://orderv2.foodtruck-qa.com         | 订单中心 |
