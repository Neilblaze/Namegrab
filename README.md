# Namegrab

Lightweight microservice to fetch URL `<title />` name

### Usage

- This microservice works on **any url** only & only if <title /> tag is present!

**Base URL:** [neilblaze.live](https://neilblaze.live) OR [github.com/Neilblaze](https://github.com/Neilblaze)

**GET** `/:url`

`url` - The URL of the page you want the title of **without the protocol (`http://` or `https://`)**.

**Example**:

* GET [https://namegrab.vercel.app/neilblaze.live](https://namegrab.vercel.app/neilblaze.live)
* Response (text/plain) `NΞILBLAZΞ`

### License

[MIT](LICENSE)
