<p align="center">
<img src="https://raw.githubusercontent.com/zennn08/storage/main/Itsuki.jpg" alt="REST-API" width="128" height="128"/>
</p>
<p align="center">
<a href="#"><img title="REST-API" src="https://img.shields.io/badge/REST%20API-green?colorA=%23ff0000&colorB=%23017e40&style=for-the-badge"></a>
</p>
<p align="center">
<a href="https://github.com/zennn08"><img title="Author" src="https://img.shields.io/badge/Author-zennn08-red.svg?style=for-the-badge&logo=github"></a>
</p>

---

# Features

1. [Tiktok Downloader](#tiktok)
2. [Pinterest Search]()
3. [Instagram Downloader]()
4. [Instagram TV]()
5. [Instagram Stalk]()

---

## Tiktok

_Download video and audio from tiktok_

- **URL**

  [_https://aqulzz.herokuapp.com/tiktok_](https://aqulzz.herokuapp.com/tiktok)

- **Method:**

  `GET`

- **URL Params**

  **Required:**

  `url=[url]`

- **Response:**

| Code |       Response        |
| :--: | :-------------------: |
| 200  |        Success        |
| 400  |      Bad Request      |
| 500  | Internal Server Error |

- **Sample Call:**

  ```js
  const fetch = require("node-fetch");
  fetch(
    "http://aqulzz.herokuapp.com/tiktok?url=https://vt.tiktok.com/ZSJxEbYNN/"
  )
    .then((res) => res.json())
    .then(console.log());
  ```
