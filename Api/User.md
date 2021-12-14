`带 * 参数为必填项`
# Register
+ http://120.76.47.219:8080/register
+ 参数

    |            |      |
    | ------------ | ---- |
    | userName     | *    |
    | passWord     | *    |
    | sex          |      |
    | nickName     |      |
    | introduction |      |
    | contact      |      |
    | email        |      |
    | campus       |      |
    |              |      |

+ 请求体：
    ```json
    {
        "userName":"zhl",
        "passWord":"123asd",
        "sex":0,
        "nickName":"ad",
        "introduction":"test",
        "contact":"12345678910",
        "email":"abcd@qq.com",
        "campus":1
    }
    ```
+ 返回
    ```json
    {
        "code":4401,
        "message":"用户名为空"
    }
    ```
    ```json
    {
        "code":4402,
        "message":"用户名已存在"
    }
    ```
    ```json
    {
        "code":4403,
        "message":"密码为空"
    }
    ```
    ```json
    {
        "code":200,
        "message":"success"
    }
    ```
    