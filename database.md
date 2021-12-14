# User

| id           | Int     | id             | 主键、非空、自增                              |
| :----------- | ------- | -------------- | --------------------------------------------- |
| userName     | String  | 用户名         | 非空，唯一                                    |
| sex          | Integer | 性别           | 0为男，1为女，默认为0                         |
| nickName     | String  | 昵称           | 可以为空，默认为 “用户_id"                    |
| introduction | String  | 个人简介       | 可为空                                        |
| image        | String  | 头像           | 存url，有另外接口上传图片，可为空，有默认头像 |
| contact      | String  | 联系方式       | 可为空                                        |
| email        | String  | 邮箱           | 可为空                                        |
| campus       | Integer | 校区           | 0,1,2,3,4 代表不同校区，默认为0               |
| gmtCreate    | BigInt  | 数据创建时间戳 |                                               |
| gmtModifited | Bigint  | 数据更新时间戳 |                                               |

