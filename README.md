# AstroNet Developer API Docs

#### Get User Data

```http
  https://astronet-api--tlochsta.repl.co/getUserData.php/${userId}
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `userId` | `string` | **Required**. User ID to get user data |

#### Get Message Content

```http
  https://astronet-api--tlochsta.repl.co/getMessageContent.php/${messageId}
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `messageId`      | `string` | **Required**. Id of message to fetch |

