<div dir="rtl">
# رابط ابرفام



## احراز هویت:
#### توکنی که در اختیارتون قرار داده شده رو در هدر به این صورت بفرستید:
```
X-API-KEY: example-token
```
## متد ها
#### دریافت سرور های ساخته شده

```
  GET https://api.abrfam.ir/servers
```


#### دریافت یک سرور مشخص

```
  GET https://api.abrfam.ir/servers/${id}
```

| متد  | پارامتر | تایپ     | توضیحات                       |
| :---- | :-------- | :------- | :-------------------------------- |
| `GET`  | `id`      | `integer` |  **اجباری** \| آیدی سرور |



#### ساخت سرور
```
  POST https://api.abrfam.ir/servers/create
```
| متد  | پارامتر | تایپ     | توضیحات                       |
| :---- | :-------- | :------- | :-------------------------------- |
| `POST`  | `name`      | `string` |  **اجباری** \| نام سرور |
|`POST` | `plan` | `string` | **اجباری** \| نام پلن
| `POST` | `os_id` | `integer` | **اجباری** \| آیدی سیستم عامل

#### تغییر پسورد سرور

```
  POST https://api.abrfam.ir/servers/${id}/resetPassword
```
| متد  | پارامتر | تایپ     | توضیحات                       |
| :---- | :-------- | :------- | :-------------------------------- |
| `GET`  | `id`      | `integer` |  **اجباری** \| آیدی سرور |

### خاموش کردن سرور

```
  POST https://api.abrfam.ir/servers/${id}/powerOffServer
```
| متد  | پارامتر | تایپ     | توضیحات                       |
| :---- | :-------- | :------- | :-------------------------------- |
| `GET`  | `id`      | `integer` |  **اجباری** \| آیدی سرور |

### روشن کردن سرور

```
  POST https://api.abrfam.ir/servers/${id}/powerOnServer
```
| متد  | پارامتر | تایپ     | توضیحات                       |
| :---- | :-------- | :------- | :-------------------------------- |
| `GET`  | `id`      | `integer` |  **اجباری** \| آیدی سرور |


### حذف سرور

```
  DELETE https://api.abrfam.ir/servers/${id}
```
| متد  | پارامتر | تایپ     | توضیحات                       |
| :---- | :-------- | :------- | :-------------------------------- |
| `GET`  | `id`      | `integer` |  **اجباری** \| آیدی سرور |

####  دریافت نام سیستم عامل ها

```
  GET https://api.abrfam.ir/os
```

#### دریافت ورژن های یک سیستم عامل

```
  GET https://api.abrfam.ir/os/${os}
```

| متد  | پارامتر | تایپ     | توضیحات                       |
| :---- | :-------- | :------- | :-------------------------------- |
| `GET`  | `os`      | `string` |  **اجباری** \|  نام سیستم عامل |

####  دریافت پلن ها

```
  GET https://api.abrfam.ir/plans
```
</div>
